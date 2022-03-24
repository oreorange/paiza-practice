## C084:枠で囲む
Scannerで入力した文字列を+で囲んで出力
```java
import java.util.*;


public class Main {
    public static void main(String[] args) {
        // 自分の得意な言語で
        // Let's チャレンジ！！
        Scanner sc = new Scanner(System.in);
        String word = sc.next();
        int wordNum = word.length();
        int lineNum = wordNum + 2;
        
        System.out.println("+".repeat(lineNum));
        System.out.println("+" + word + "+");
        System.out.println("+".repeat(lineNum));
    }
}
```
