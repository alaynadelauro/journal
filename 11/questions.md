# A bit more CSharp and SQL
1. What does ***inheritance*** accomplish for us in C#?

  > | It allows us to take all of the properties of one class/object etc and put them on another class/object (such as BlahController : ControllerBase - takes everything from ControllerBase and puts it on the BlahController ) |

2. How does ***member inheritance*** work in C#? Does a `Class` inherit all members of the base `Class`?

  > | member inheritance is basically what i described above, it passes everything on a class down to another class. The inheriting class does inherit everything on the parent class, but only public methods can be modified or reused in it |

3. How does ***accessibility*** affect inheritance?

  > | you can only modify/call on methods that aren't private |

4. What is the difference between a `PRIMARY KEY` and a `FOREIGN KEY`

  > | A primary key is the unique identifier(id) of an item. A foreign key is a key that's being stored on another object referenced from an object's primary key |

5. What is an ***alias***?

  > | it assigns another name to something for internal use, such as BlobRepository turning into _repository |

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

  > | 
  SELECT * FROM patient_doctors
  JOIN doctors ON patient_doctors.doctorId = doctors.id
  JOIN patients ON patient_doctors.patientId = patients.id
   |
