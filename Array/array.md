
````java
  class string1{
  	public static void main(String[] args){
  		int[] arr = new int[5];
  		arr[0] = 23;
  		arr[1] = 43;
  		arr[2] = 55;
  		arr[3] = 76;
  		arr[4] = 77;

  		for(int i=0;i<arr.length;i++){
  			System.out.print(arr[i]+"\n");
  		}
  	}
  }

````

````java
  import java.util.*;
  class string1{
  	public static void main(String[] args){
  		int[] arr = {34,54,56,76,8,87,56};
  		
  		for(int i=0;i<arr.length;i++){
  			System.out.print(arr[i]+"\n");
  		}
  	}
  }

````


### Taking Input from user
````java
  import java.util.*;
  class string1{
  	public static void main(String[] args){
  		int[] arr = new int[5];
  		Scanner sc = new Scanner(System.in);
  		
  		for (int i=0;i<arr.length;i++){
  			arr[i] = sc.nextInt();
  		}
  		for(int i=0;i<arr.length;i++){
  			System.out.print(arr[i]+"\n");
  		}
  	}
  }

````

### Arrays.toString

````java
  import java.util.*;
  class string1{
  	public static void main(String[] args){
  		String[] arr = {"apple","orange","masd"};
  		
  		System.out.print(Arrays.toString(arr));
  		
  	}
  }

````

## MATRIX

````java
  class string1{
  	public static void main(String[] args){
  		// 1 2 3
  		// 4 5 6
  		// 7 8 9

  		int[][] arr = {
  			{1,2,3},
  			{4,5,6},
  			{7,8,9}
  		};

  		for(int i = 0; i<arr.length;i++){
  			for(int j=0;j<arr.length;j++){
  				System.out.print(arr[i][j]+ " ");
  			}
  			System.out.println();

  		}

  	}
  }


````

### Arrays.toString

````java
  import java.util.*;
  class string1{
  	public static void main(String[] args){
  		// 1 2 3
  		// 4 5 6
  		// 7 8 9

  		int[][] arr = {
  			{1,2,3},
  			{4,5,6},
  			{7,8,9}
  		};

  		for(int i = 0; i<arr.length;i++){
  			System.out.print(Arrays.toString(arr[i])+"\n");
  		}
  	}
  }


````
