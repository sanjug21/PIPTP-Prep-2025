## Question:

Write a program that reads a full name from the user and converts it into a format where all initials (except the last name) are replaced by their first character followed by a period (`.`), and the last name is printed in full.

### Input:
A single line containing a full name (first name, middle names (if any), and last name), with each word separated by a space.

### Output:
The formatted name with initials for all words except the last one. Each initial is followed by a dot and a space.

### Constraints:
- If the input is an empty string print "Name is not Provided".
- The input may contain first name, optional middle names, and a last name.

---

### Example:

#### Input:
```
Kaustubh Verma
```

#### Output:
```
K. Verma
```

---

### Java Code:

```java
import java.util.*;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String name = sc.nextLine();
        String ans = "Name is not Provided";
        if (!name.isEmpty()) ans = initials(name);
        System.out.print(ans);
    }

    public static String initials(String name) {
        String[] str = name.split(" ");
        StringBuilder ans = new StringBuilder();
        for (int i = 0 ; i < str.length - 1 ; i++) { 
            ans.append(str[i].charAt(0)).append(". ");
        }
        ans.append(str[str.length - 1]);
        return ans.toString();
    }
}
```
