# A bit more CSharp and SQL
1. What does ***inheritance*** accomplish for us in C#?

  > allows attributes to be passed from class to class 

2. How does ***member inheritance*** work in C#? Does a `Class` inherit all members of the base `Class`?

  > it is selective inheritance rather then full inheritance 

3. How does ***accessibility*** affect inheritance?

  > the order affects how the object will be inheritated

4. What is the difference between a `PRIMARY KEY` and a `FOREIGN KEY`

  > primary key is how it is named locally and foreign is from another file

5. What is an ***alias***?

  > naming convention to make code smaller and more clean

6. Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

  ```SQL
  CREATE TABLE doctors (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patients (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patient_doctors (
    id INT NOT NULL AUTO_INCREMENT,
    doctorId INT NOT NULL,
    patientId INT NOT NULL,

    FOREIGN KEY (doctorId)
      REFERENCES doctors(id),
    FOREIGN KEY (patientId)
      REFERENCES patients(id),
  )

  ```

  > | ANSWER HERE |
