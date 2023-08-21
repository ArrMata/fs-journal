# A bit more CSharp and SQL
1. What does ***inheritance*** accomplish for us in C#?

  > Inheritance allows us to inherit a class's methods and properties. This allows us to make different versions of an inherited class, allowing us to take what is needed from the inherited class but extend on to it.

2. How does ***member inheritance*** work in C#? Does a `Class` inherit all members of the base `Class`?

  > It does inheirt all the members of a base class, we've done this for RepoItem and Profile/Account.

3. How does ***accessibility*** affect inheritance?

  > If certain members or methods are set private, they are not visible to the derived class.

4. What is the difference between a `PRIMARY KEY` and a `FOREIGN KEY`

  > A primary key is what identifies a row entry within a table, where a foreign key is used to reference a different table's primary key. This allows us to reference another table.

5. What is an ***alias***?

  > Aliases in C# allows us assign a name to a type or namespace, which allows us to use methods and classes from their respective directories without having to write them all out. Like System.Exception.(whatever).Class when using a name space can be condensed down to Class

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

  ```
    SELECT
    patientDoc.*,
    patient.*,
    FROM patient_doctors patientDoc
    JOIN patients patient ON patient.id = patientDoc.patientId
    WHERE patientDoc.doctorId = @DoctorId;
  ```
