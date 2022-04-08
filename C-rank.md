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

## C097:プレゼント応募企画の実施
FizzBuzz亜種
```java
import java.util.*;


public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        
        int[] num = new int[3];
        for(int i = 0; i < num.length; i++) {
            num[i] = sc.nextInt();
        }
        
        int[] arrays = new int[num[0]];
        for(int i = 0; i < arrays.length; i++){
            arrays[i] = i;
        }
        
        for(int array: arrays) {
            if((array + 1) % num[1] == 0 && (array + 1) % num[2] == 0) {
                System.out.println("AB");
            } else if((array + 1) % num[1] == 0) {
                System.out.println("A");
            } else if((array + 1) % num[2] == 0) {
                System.out.println("B");
            } else {
                System.out.println("N");
            }
        }
    }
}
```

## C777:〇〇の計算
```java

```


## C777:〇〇の計算
```java

```
