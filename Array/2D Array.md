
## 2D Array

```java
import java.util.*;
public class twoD {
        public static void main(String[] args) {
            Scanner sc = new Scanner(System.in);
            int rows = sc.nextInt();
            int cols = sc.nextInt();

            int[][] arr = new int[rows][cols];

            //input
            for(int i=0;i<rows;i++){
                for(int j=0;j<cols;j++){
                    arr[i][j] = sc.nextInt();

                }
            }

            //output
            for(int i=0;i<rows;i++){
                for(int j=0;j<cols;j++){
                    System.out.print(arr[i][j] + " ");
                }
                System.out.println();
            }
        }
}

```

## Search a particular number x in 2d matrix

```java

import java.util.*;
public class twoD {
        public static void main(String[] args) {
            Scanner sc = new Scanner(System.in);
            int rows = sc.nextInt();
            int cols = sc.nextInt();

            int[][] arr = new int[rows][cols];

            //input
            for(int i=0;i<rows;i++){
                for(int j=0;j<cols;j++){
                    arr[i][j] = sc.nextInt();

                }
            }
            int x = sc.nextInt();
            //output
            for(int i=0;i<rows;i++){
                for(int j=0;j<cols;j++){
                    if(arr[i][j] == x){
                        System.out.printf("x found at location : "+ i + " " + j);
                    }
                }
                System.out.println();
            }
        }
}


```
