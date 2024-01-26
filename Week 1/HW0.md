# Java Basic Syntax Notes

1- Java Variables have static type, meaning you can't define a variable as an integer, and then reassign it as a string  
* Static Vs Dynamic Typing:  
 
   Static typing means once the variable is created, it must be given a data type which is not changed during runtime..    
   Dynamic typing means the variable is not given a data type when created and it's checked at the run time.
   

2- Java statements must end with a semicolon. 

3- Conditions in java are just like C++ in everything, for example: 

``` java
 public static void main(String [] args) 
 {
     int x = 10; 
     if (x > 10) 
     {
       System.out.println("Hello"); 
     }
     else 
     {
        System.out.println("Sorry"); 
     }
 }
```
4- All java code must be inside a class or enum.

5- Unlike python, indentation does not matter, but curly brackets do.

6- While loops are just like C++, for example: 
```java
    public class WhileLoop {
       public  static void main (String [] args)
       {
           int x = 10; 
           while (x >= 0)
           {
               System.out.println(x); 
               x--; 
           }
       }
}
```
7- Data types in java looks like C++ somehow, there are primitive and non primitive data types..

8- Functions in Java are referred to as Methods.

9- The following code is called method signature
``` java 
   public static int max (int x, int y)
```
as it has the method parameters, return type, method name, and any modifiers.  
here the modifiers are public and static (Will talk about later).

10- Arrays in Java: 
 ``` java
   public static void main (String [] args) 
   { 
        //First approach
        int[] arr = {1,2,3,4}; 
        
        //Second approach
        int numbers []; 
        numbers = new int[]{1,2,3,4};
        
        //If we don't specify the array elements when declaring,
        //we should give it a size, like this: 
        
        boolean[] flags = new boolean[3]; 
        // means that we've created an array of booleans which have 3 elements
   }
 ```
11- For loops in java are just like C++, for example: 

```java
   public class ForLoop {
     public static void main (String [] args)
     {
         for (int i = 0; i < 10; i++)
         {
             System.out.println("Hello"); 
         }
     }
}

```

12 - We can also use enhanced for loop, which corresponds to for each in C++, for example: 
```java
  public class enhancedFor {
    public static void main (String [] args)
    {
        String[] arr = {"Alaa", "Ahmad", "Abd Elhamid"}; 
        for (String s: arr)
        {
            System.out.println(s); 
        }
    }
}

```
