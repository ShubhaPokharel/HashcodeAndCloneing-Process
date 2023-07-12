# HashcodeAndCloneing-Process

## Hashcode

- Whenever we create an object, JVM will give a unique number to that object.

 In other words, JVM will assign a unique number to the object we created.

 To print the hashcode we have 2 ways:

 1.

 Print the reference variable

     Ex:

     class Test{

      public static void main(String[] args){
    
        Test t = new Test();
    
        System.out.println(t);
    
         }
    
     }


2.

We can also use '.hashcode()'.

- '.hashcode()' will convert the hexa decimal number to decimal number.


  Example:

  
  class Test{

     public static void main(String[] args){

        Test t1 = new Test();

         System.out.println(t1);

        Test t2 = new Test();
  
        System.out.println(t2.hashcode());
  
     }
  
  }


## Number System

1. Binary Numbers

 - numbers that are 0 and 1
     
2. Octal Number

 - numbers from 0-7 : 0 1 2 3 4 5 6 7
     
3. Decimal numbers

- numbers from 0-9 : 0 1 2 3 4 5 6 7 8 9 
   
5. Hexa Decimal Numbers

- numbers 0-9 and letters a-f




#### To convert binary format to decimal number :


To convert binary format to decimal number we have to use the powers of 2.

Note: 

- 0 is disabled
- 1 is enabled

  64  32  16  8  4 2  1
  
               1  0 0 1  = 9


     32      16       8       4      2     1

              1    1    1   1     = 15
  
        1      0    1    0   1    = 21
  



  
   













     


