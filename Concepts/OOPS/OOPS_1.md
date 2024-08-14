# OOPS - 1

> Resources - CB Notes, Kunal Khushwaha

```Java
public class Main{
    //store 5 roll nos.
    int[] numbers = new int[5]; // a specific property of element

    //data of the 5 students: {Roll no, Name, Marks}
    // but the problem is they are stored sperately to store them together we can bundle these properties under a class
    int[] rno = new int[5];
    String[] name = new String[5];
    float[] marks = new float[5];
}

```


**We can create different different elements/properties with a specific datatype but If we need to create a data structure which can store different data types in one rather than storing them in seperate data structures. Here the concept of OOPS come in.**

## Class
1. A named group of properties and functions (a group or bundle or collection).
2. Class is a logical construct thats doesnt exist in reality ( That means it doesnt occupy space in memory).
3. Class is a templete for Object.

```Java
// create a class
Student[] students = new Student[5];



```
`Student` is our own data structure. 