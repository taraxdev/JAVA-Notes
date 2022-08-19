
```java

public class strBuilder {
    public static void main(String[] args) {
        StringBuilder sb = new StringBuilder("Akshay");
        System.out.println(sb);

        //set
        sb.setCharAt(1,'n');
        System.out.println(sb);

        //insert
        sb.insert(6,'a');
        System.out.println(sb);

        //delete
        sb.delete(2,3);
        System.out.println(sb);

        //append
        sb.append("z");
        System.out.println(sb);
    }
}



```
