# CSharp and SQL Fundamentals
01. What is the purpose of a `namespace`?

  > to group files together to more easily access

02. What is the difference between a `class` and an `interface`?

  > a class can be instantiated an interface cannot 

03. What is the method that returns an instance of a class, yet it has no return type?

  > void

05. In the Car example what is the access modifier of the `Start()` method?

  ```c#
  abstract class Car
  {
    public string Start()
    {

      return "Vroooom";

    }
  }
  ```

  > public

06. In the Car example what is `string` an indication of?

  > what kind of data it will return 

07. In the Car example what is `abstract` preventing?

  > preventing the class from being the same as everyone else 

08. In a SQL table, what is the difference between information in a row and information in a column?

  > rows are all the same object and the collumns are the classes on said objects

09. Demonstrate the necessary SQL for creating a table called `characters` with the values `name, age, description` as strings, and an `int` id.

  > CREATE TABLE 
  IF NOT EXISTS characters (
    name varchar(100) NOT NULL,
    age varchar(100) NOT NULL, 
    description varchar(300),
    id INT NOT NULL
  )

10. In SQL how can you query more than a single table? Provide an example.

  > with a join 
ALbum alb JOIN Account act
