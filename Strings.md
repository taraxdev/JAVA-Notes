```java

import java.util.*;

public class Strings {
    public static void main(String[] args) {
        //charAt
        String name = "Akshay";
        for (int i=0;i<name.length();i++){
            System.out.println(name.charAt(i));
        }

        //compareTo
        String name1 = "vinayak";
        String name2 = "vinayak";

        if(name1.compareTo(name2) == 0){
            System.out.println("Strings are equal");
        }else{
            System.out.println("Strings not equal");
        }

        //substring
        String sentence = "I wear titan watches";
        String names = sentence.substring(7,12);
        System.out.println(names);

        //strings are immutable
    }
}


```
