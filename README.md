# Experiment-8---JAVA
## AIM
Write a java program using Inheritance where one class acquires the properties of the other class.
## ALGORITHM
1. Create a java class "Animal" with a function called walk.
2. Create a java class "Bird" that extends the Animal class and with two functions named fly and sing.
3. Since the Bird class is extends the animal class we can access the Animal class by creating an object for the Bird class.
4. In the Main.java create a object for the Bird class and access all the methods (walk,fly and sing).
5. Print the output and end the program.
## PROGRAM
### Main.java
```
public class Main {
    public static void main(String[] args) {
        Bird bird=new Bird();
        bird.walk();
        bird.fly();
        bird.sing();
    }
}
```
### Animal.java
```
public class Animal {
    void walk(){
        System.out.println("I am walking");
    }
}

```
### Bird.java
```
public class Bird extends Animal {
    void fly(){
        System.out.print("I am flying ");
    }
    void sing(){
        System.out.print("I am singing");
    }
}

```
## OUTPUT
<img width="387" alt="image" src="https://github.com/Shavedha/Experiment-8---JAVA/assets/93427376/b6500c30-17a8-403b-bda0-99a653283236">

## RESULT
Thus a program is implemented where one class acquires the properties of the other class.
