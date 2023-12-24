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

There are two types of constructors in Java:

Default constructor (no-arg constructor)
Parameterized constructor
