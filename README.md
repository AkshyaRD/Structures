# Structures

### About Structures
A structure is a keyword that creates user-defined data types in C/C++.   
A structure creates a data type that can be used to group items of possibly different types into a single type. 
We can use this data type to store data of different attributes of different data types.  
For example, If we want to store data on multiple patients such as patient name, age, and blood group.  

**‘struct’ keyword is used to create a structure.**  
### Syntax of Struct
![image](https://user-images.githubusercontent.com/91966613/234246672-7ec7bfde-f058-491d-8553-c50180e69da8.png)

### Syntax To create Structure Variables  
struct (name of structure) (name of variable);

### Syntax to access members of a Structure  
Members of a Structure can be accessed using the member operator '.'
eg: x.year=1999 in the structure car_shop

### car_shop
A structure car_shop is defined that consists of different data types:  char name[20]; int year; float cost; char category  
In the program, a derived data type struct car_shop is defined
x is the structure variable

### datas
A structure datas is defined that consists of different data types:  char name[20]; int age; float gpa;  
In the program, a derived data type struct datas is defined
x is the structure variable

### Why structs in C?
Suppose you want to store information about a person: his/her name, citizenship number, and salary.   
You can create different variables name, citNo and salary to store this information.  
What if you need to store information of more than one person?   
Now, you need to create different variables for each information per person: name1, citNo1, salary1, name2, citNo2, salary2, etc.  
A better approach would be to have a collection of all related information under a single name Person structure and use it for every person.

### OUTPUT SCREENSHOTS
![image](https://user-images.githubusercontent.com/91966613/234251430-76b71d9e-2cc8-4919-8ea0-075afc049f80.png)
![image](https://user-images.githubusercontent.com/91966613/234253421-0fb77574-ae7d-478c-9a4a-5de31beaf39d.png)
![image](https://user-images.githubusercontent.com/91966613/234253099-b27f8dcf-3066-4e60-b616-3d9e10572f73.png)
