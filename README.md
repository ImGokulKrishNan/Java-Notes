# Java-Notes
Learning
**What is Java?**
Java is programming language and platform independent ,high level language ,It support Object Oriented programming & system.

- **void** is the return type of the method. It means it doesn't return any value.
![[Pasted image 20231222212323.png]]

JVM,JRE,JDK

**Data Types**
integer   int      = 45321321
float      float    = 5.4f
Char      A         = 'Java'
String   String   = "String"
Boolean Boolean = True or False
Double    Double  =122332.2
short        Short     = 1000
long         long      = 10000
Byte         byte      =  4564135


**Variables**
	Local
	Static
	Instance

**Class Sample**{

	void test(){
	int a=10;   //local  variable
	Static int b=15; //Static variable
	
	}
**public Static void main(String args[]){**

	int c=10; // instance variable
**}}**

***Operators***

- Unary Operator,
- Arithmetic Operator,
- Shift Operator,
- Relational Operator,
- Bitwise Operator,
- Logical Operator,
- Ternary Operator and
- Assignment Operator.


### Java Unary Operator

The Java unary operators require only one operand. Unary operators are used to perform various operations i.e.:

- incrementing/decrementing a value by one
- negating an expression
- inverting the value of a boolean

|Operator Type|Category|Precedence|
|---|---|---|
|Unary|postfix|`_expr_++ _expr_--`|
|prefix|`++_expr_ --_expr_ +_expr_ -_expr_ ~ !`|
|Arithmetic|multiplicative|`* / %`|
|additive|`+ -`|
|Shift|shift|`<< >> >>>`|
|Relational|comparison|`< > <= >= instanceof`|
|equality|`== !=`|
|Bitwise|bitwise AND|`&`|
|bitwise exclusive OR|`^`|
|bitwise inclusive OR|`\|`|
|Logical|logical AND|`&&`|
|logical OR|`\|`|
|Ternary|ternary|`? :`|
|Assignment|assignment|`= += -= *= /= %= &= ^= \|= <<= >>= >>>=`|

Logical AND  &&
0  &&  1 = 0
0  &&  0 = 0
1  && 1 = 1
1  &&  0 = 0

	- If both conditions are true => `true`
	- If one of the two conditions is false => `false`
	- If both conditions are false => `false`
0  &  1 = 0
0  &  0 = 0
1  &  1 = 1
1  &  0 = 0

	- If both conditions are true => `true`
	- If one of the two conditions is false => `false`
	- If both conditions are false => `false`

Logical OR ||

0  | | 1 = 1
0  | | 0 = 0
1  | | 1 = 1
1  | | 0 = 1

	- If both conditions are true => `true`
	- If one of the conditions is true => `true`
	- If both conditions are false => `false`

Logical Bitwise OR |

0  |  1 = 1
0  |  0 = 0
1  |  1 = 1
1  |  0 = 1

	- If both conditions are true => `true`
	- If one of the conditions is true => `true`
	- If both conditions are false => `false`

#  Control Statements
Java provides three types of control flow statements.

1. Decision Making statements
    - if statements
    - switch statement
2. Loop statements
    - do while loop
    - while loop
    - for loop
    - for-each loop
3. Jump statements
    - break statement
    - continue statement
-
1. Simple if statement

		if(condtion){
			//statememt
		}
1. if-else statement

		if(condtion){
			//statememt
		}
		
		else{
			//statememt
		}
1. if-else-if ladder

		if(condtion){
			//statememt
		}
		else-if(condition){
			//statememt
		}
		else{
			//statememt
		}
		
1. Nested if-statement
 
		if(condtion){
			//statememt
		}
		else-if(condition){
			//statememt
		}
		else-if(condition){
			//statememt
		}
		else{
			//statememt
		}

**Switch**
`
```
	`switch (expression){  
		    case value1:  
		      statement1;  
		      break;  
		   .  
		   .  
		   .  
		    case value N:  
		     statement N;  
		      break;  
		     default:  
		      default statement;  
		 `
```

### Loop Statements


1. for loop
2. while loop
3. do-while loop

For
1. for(initialization, condition, increment/decrement) {    
2. //block of statements    
3. }
4. 
5. int sum = 0;  
6. for(int j = 1; j<=10; j++) {  
7. sum = sum + j;  
8. }

While Loop

1. while (condition){    
2. //code to be executed   
3. Increment / decrement statement  
4. }
5. 
1.     int i=1;  
2.     while(i<=10){  
3.         System.out.println(i);  
4.     i++;  
5.     }
Do-While Loop

1. do{    
2. //code to be executed / loop body  
3. //update statement   
4. }

1.   int i=1;    
2.     do{    
3.         System.out.println(i);    
4.     i++;    
5.     }while(i<=10);    
6. }


Break

1. jump-statement;    
2. break;
1.     for(int i=1;i<=10;i++){  
2.         if(i==5){  
3.             //breaking the loop  
4.             break;  
5.         }

## OOPs (Object-Oriented Programming System)

**Object** means a real-world entity such as a pen, chair, table, computer, watch, etc. **Object-Oriented Programming** is a methodology or paradigm to design a program using classes and objects. It simplifies software development and maintenance by providing some concepts:

- [Object](https://www.javatpoint.com/object-and-class-in-java)
- 
	`Real word entity.
	`It create instance of object`
Class 
	 `Collection object is class.
	` blueprint of object
- [Inheritance](https://www.javatpoint.com/inheritance-in-java)
	- `Inheritance is aquiare all properties behaviour of parent class. `
- [Polymorphism](https://www.javatpoint.com/runtime-polymorphism-in-java)
	- `If _one task is performed in different ways_, it is known as polymorphism.`
- [Abstraction](https://www.javatpoint.com/abstract-class-in-java)
	`_Hiding internal details and showing functionality_ is known as abstraction.
- [Encapsulation](https://www.javatpoint.com/encapsulation)
	- `_Binding (or wrapping) code and data together into a single unit are known as encapsulation_.`
	- 
-Method Declaration

![[Pasted image 20231222213054.png]]

**Access Specifier:** Access specifier or modifier is the access type of the method. It specifies the visibility of the method. Java provides **four** types of access specifier:

- **Public:** The method is accessible by all classes when we use public specifier in our application.
- **Private:** When we use a private access specifier, the method is accessible only in the classes in which it is defined.
- **Protected:** When we use protected access specifier, the method is accessible within the same package or subclasses in a different package.
- **Default:** When we do not use any access specifier in the method declaration, Java uses default access specifier by default. It is visible only from the same package only.

**Return Type:** Return type is a data type that the method returns. It may have a primitive data type, object, collection, void, etc. If the method does not return anything, we use void keyword.

**Method Name:** It is a unique name that is used to define the name of a method. It must be corresponding to the functionality of the method. Suppose, if we are creating a method for subtraction of two numbers, the method name must be **subtraction().** A method is invoked by its name.

**Parameter List:** It is the list of parameters separated by a comma and enclosed in the pair of parentheses. It contains the data type and variable name. If the method has no parameter, left the parentheses blank.

**Method Body:** It is a part of the method declaration. It contains all the actions to be performed. It is enclosed within the pair of curly braces.

type of Method
	`User defined Method
	`Pre-defined Method`

constructor
In Java, a constructor is a block of codes similar to the method. It is called when an instance of the class is created. At the time of calling constructor, memory for the object is allocated in the memory. 
Types of Java constructors

# Constructors in Java

constructor is a block of codes similar to the method. It is called when an instance of the [class](https://www.javatpoint.com/object-and-class-in-java) is created. At the time of calling constructor, memory for the object is allocated in the memory.

### Rules for creating Java constructor

There are two rules defined for the constructor.

1. Constructor name must be the same as its class name
2. A Constructor must have no explicit return type
3. A Java constructor cannot be abstract, static, final, and synchronized
## Types of Java constructors

There are two types of constructors in Java:

1. Default constructor (no-arg constructor)
2. Parameterized constructor

There are two types of constructors in Java:

Default constructor (no-arg constructor)
Parameterized constructor



static keyword
The **static keyword** in [Java](https://www.javatpoint.com/java-tutorial) is used for memory management mainly. We can apply static keyword with [variables](https://www.javatpoint.com/java-variables), methods, blocks and [nested classes](https://www.javatpoint.com/java-inner-class). The static keyword belongs to the class than an instance of the class.

The static can be:

1. Variable (also known as a class variable)
2. Method (also known as a class method)
3. Block
4. Nested class

# this keyword in Java

There can be a lot of usage of **Java this keyword**. In Java, this is a **reference variable** that refers to the current object.

![java this keyword](https://static.javatpoint.com/images/thisr.jpg)

## Usage of Java this keyword

Here is given the 6 usage of java this keyword.

1. [this can be used to refer current class instance variable.](https://www.javatpoint.com/this1)
2. [this can be used to invoke current class method (implicitly)](https://www.javatpoint.com/this2)
3. [this() can be used to invoke current class constructor.](https://www.javatpoint.com/this3)
4. [this can be passed as an argument in the method call.](https://www.javatpoint.com/this4)
5. [this can be passed as argument in the constructor call.](https://www.javatpoint.com/this5)
6. [this can be used to return the current class instance from the method.](https://www.javatpoint.com/this6)


![[Pasted image 20240101223952.png]]

# Inheritance in Java

1. [Inheritance](https://www.javatpoint.com/inheritance-in-java#)
2. [Types of Inheritance](https://www.javatpoint.com/inheritance-in-java#inheritancetypes)
3. [Why multiple inheritance is not possible in Java in case of class?](https://www.javatpoint.com/inheritance-in-java#inheritancenotmultiple)

**Inheritance in Java** is a mechanism in which one object acquires all the properties and behaviors of a parent object. It is an important part of [OOPs](https://www.javatpoint.com/java-oops-concepts) (Object Oriented programming system).


# Method Overloading in Java
If a [class](https://www.javatpoint.com/object-and-class-in-java) has multiple methods having same name but different in parameters, it is known as **Method Overloading**.

If we have to perform only one operation, having same name of the methods increases the readability of the [program](https://www.javatpoint.com/java-programs).

Suppose you have to perform addition of the given numbers but there can be any number of arguments, if you write the method such as a(int,int) for two parameters, and b(int,int,int) for three parameters then it may be difficult for you as well as other programmers to understand the behavior of the method because its name differs.

## Advantage of method overloading

Method overloading _increases the readability of the program_.

### Different ways to overload the method

There are two ways to overload the method in java

1. By changing number of arguments
2. By changing the data type
### 1) Method Overloading: changing no. of arguments

In this example, we have created two methods, first add() method performs addition of two numbers and second add method performs addition of three numbers.




__Java Array__

__Array is a collection of similar type of elements which has contiguous memory location.__


**Java array** is an object which contains elements of a similar data type. Additionally, The elements of an array are stored in a contiguous memory location. It is a data structure where we store similar elements. We can store only a fixed set of elements in a Java array.

Array in Java is index-based, the first element of the array is stored at the 0th index, 2nd element is stored on 1st index and so on.

![[Pasted image 20240111185516.png]]

### Advantages

- **Code Optimization:** It makes the code optimized, we can retrieve or sort the data efficiently.
- **Random access:** We can get any data located at an index position.

### Disadvantages

- **Size Limit:** We can store only the fixed size of elements in the array. It doesn't grow its size at runtime. To solve this problem, collection framework is used in Java which grows automatically.
### Types of Array in java

There are two types of array.

- Single Dimensional Array
- Multidimensional Array
## Single Dimensional Array in Java

**Syntax to Declare an Array in Java**


``1. dataType[] arr; (or)  
`2. dataType []arr; (or)  
`3. dataType arr[];  

**Instantiation of an Array in Java**

`1. arrayRefVar=new datatype[size];`


Example:
	``class Testarray{
	public static void main(String args[]){
	
	int a[]=new int[5];//declaration and instantiation
	a[0]=10;//initialization
	a[1]=20;
	a[2]=70;
	a[3]=40;
	a[4]=50;
	
	//printing array
	for(int i=0;i<a.length;i++)//length is the property of array
	System.out.println(a[i]);
10
20  
70  
40  
50


## For-each Loop for Java Array

We can also print the Java array using **[for-each loop](https://www.javatpoint.com/for-each-loop)**. The Java for-each loop prints the array elements one by one. It holds an array element in a variable, then executes the body of the loop.

The syntax of the for-each loop is given below:

	1. class Testarray1{  
	2. public static void main(String args[]){  
	3. int arr[]={33,3,4,5};  
	4. //printing array using for-each loop  
	5. for(int i:arr)  
	6. System.out.println(i);  
	7. }}

	output:
	33
	3
	4
	5

## Passing Array to a Method in Java

We can pass the java array to method so that we can reuse the same logic on any array.

Let's see the simple example to get the minimum number of an array using a method.


	1. //Java Program to demonstrate the way of passing an array  
	2. //to method.  
	3. class Testarray2{  
	4. //creating a method which receives an array as a parameter  
	5. static void min(int arr[]){  
	6. int min=arr[0];  
	7. for(int i=1;i<arr.length;i++)  
	8.  if(min>arr[i])  
	9.   min=arr[i];  
	
	11. System.out.println(min);  
	12. }  

14. public static void main(String args[]){  
15. int a[]={33,3,4,5};//declaring and initializing an array  
16. min(a);//passing array to method  
17. }}  


Output:

3

## Anonymous Array in Java

Java supports the feature of an anonymous array, so you don't need to declare the array while passing an array to the method.


1. //Java Program to demonstrate the way of passing an anonymous array  
2. //to method.  
3. public class TestAnonymousArray{  
4. //creating a method which receives an array as a parameter  
5. static void printArray(int arr[]){  
6. for(int i=0;i<arr.length;i++)  
7. System.out.println(arr[i]);  
8. }  

10. public static void main(String args[]){  
11. printArray(new int[]{10,22,44,66});//passing anonymous array to method  
12. }}  


Output:

10
22
44
66

## Returning Array from the Method

We can also return an array from the method in Java.


1. //Java Program to return an array from the method  
2. class TestReturnArray{  
3. //creating method which returns an array  
4. static int[] get(){  
5. return new int[]{10,30,50,90,60};  
6. }  

8. public static void main(String args[]){  
9. //calling method which returns an array  
10. int arr[]=get();  
11. //printing the values of an array  
12. for(int i=0;i<arr.length;i++)  
13. System.out.println(arr[i]);  
14. }}  

[Test it Now](https://www.javatpoint.com/opr/test.jsp?filename=TestReturnArray)

Output:

10
30
50
90
60

## ArrayIndexOutOfBoundsException

The Java Virtual Machine (JVM) throws an ArrayIndexOutOfBoundsException if length of the array in negative, equal to the array size or greater than the array size while traversing the array.



1. //Java Program to demonstrate the case of   
2. //ArrayIndexOutOfBoundsException in a Java Array.  
3. public class TestArrayException{  
4. public static void main(String args[]){  
5. int arr[]={50,60,70,80};  
6. for(int i=0;i<=arr.length;i++){  
7. System.out.println(arr[i]);  
8. }  
9. }}  



Output:

Exception in thread "main" java.lang.ArrayIndexOutOfBoundsException: 4
	at TestArrayException.main(TestArrayException.java:5)
50
60
70
80
## Multidimensional Array in Java


data is stored in row and column based index (also known as matrix form).

**Syntax to Declare Multidimensional Array in Java**



	1. dataType[][] arrayRefVar; (or)  
	2. dataType [][]arrayRefVar; (or)  
	3. dataType arrayRefVar[][]; (or)  
	4. dataType []arrayRefVar[];
**Example to instantiate Multidimensional Array in Java**

	`1. int[][] arr=new int[3][3];//3 row and 3 column  `

**Example to initialize Multidimensional Array in Java**
	
	1. arr[0][0]=1;  
	2. arr[0][1]=2;  
	3. arr[0][2]=3;  
	4. arr[1][0]=4;  
	5. arr[1][1]=5;  
	6. arr[1][2]=6;  
	7. arr[2][0]=7;  
	8. arr[2][1]=8;  
	9. arr[2][2]=9;

 # Return Statement in Java

### What is a return statement in Java?

The return statement is used for returning a value when the execution of the block is completed. The return statement inside a loop will cause the loop to break and further statements will be ignored by the compiler.

### Returning a Value from a Method

In Java, every method is declared with a return type such as int, float, double, string, etc.

These return types required a return statement at the end of the method. A return keyword is used for returning the resulted value.

The void return type doesn't require any return statement. If we try to return a value from a void method, the compiler shows an error.

Following are the important points must remember while returning a value:

- The return type of the method and type of data returned at the end of the method should be of the same type. For example, if a method is declared with the float return type, the value returned should be of float type only.
- The variable that stores the returned value after the method is called should be a similar data type otherwise, the data might get lost.
- If a method is declared with parameters, the sequence of the parameter must be the same while declaration and method call.

### Syntax:

The syntax of a return statement is the return keyword is followed by the value to be returned.

	return return_value;




 
# Recursion in Java

Recursion in java is a process in which a method calls itself continuously. A method in java that calls itself is called recursive method.

It makes the code compact but complex to understand.

**Syntax:**

1. returntype methodname(){  
2. 
3. methodname();//calling same method  
4. }
## Java Recursion Example 1: Infinite times


1. public class RecursionExample1 {  
2. static void p(){  
3. System.out.println("hello");  
4. p();  
5. }  

7. public static void main(String[] args) {  
8. p();  
9. }  
10. }  

Output:

hello
hello

## Java Recursion Example 3: Factorial Number



1. public class RecursionExample3 {  
2.     static int factorial(int n){      
3.           if (n == 1)      
4.             return 1;      
5.           else      
6.             return(n * factorial(n-1));      
7.     }      

9. public static void main(String[] args) {  
10. System.out.println("Factorial of 5 is: "+factorial(5));  
11. }  
12. }  

Output:

Factorial of 5 is: 120


# Wrapper classes in Java

The **wrapper class in Java** provides the mechanism _to convert primitive into object and object into primitive_.

## Use of Wrapper classes in Java

Java is an object-oriented programming language, so we need to deal with objects many times like in Collections, Serialization, Synchronization, etc. Let us see the different scenarios, where we need to use the wrapper classes.

**Change the value in Method: Java supports only call by value. So, if we pass a primitive value, it will not change the original value. But, if we convert the primitive value in an object, it will change the original value.

**Serialization:** We need to convert the objects into streams to perform the serialization. If we have a primitive value, we can convert it in objects through the wrapper classes.

**Synchronization:** Java synchronization works with objects in Multithreading.

**java.util package:** The java.util package provides the utility classes to deal with objects.

 **Collection Framework:** Java collection framework works with objects only. All classes of the collection framework (ArrayList, LinkedList, Vector, HashSet, LinkedHashSet, TreeSet, PriorityQueue, ArrayDeque, etc.) deal with objects only.
