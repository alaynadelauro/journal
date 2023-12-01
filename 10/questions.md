# CSharp and SQL Fundamentals
01. What is the purpose of a `namespace`?

  > | it declares what the values of the stuff inside it is |

02. What is the difference between a `class` and an `interface`?

  > | An interface defines functionality but you can't use it while you can use the functionality of a class |

03. What is the method that returns an instance of a class, yet it has no return type?

  > | void |

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

  > | string |

06. In the Car example what is `string` an indication of?

  > | the variable type |

07. In the Car example what is `abstract` preventing?

  > | uuuuh if abstract is the old way to say "private" it means only this service, repo or controller can access this method |

08. In a SQL table, what is the difference between information in a row and information in a column?

  > | a row is an object, a column is the different values the object in the row is expected to have |

09. Demonstrate the necessary SQL for creating a table called `characters` with the values `name, age, description` as strings, and an `int` id.

  > | CREATE TABLE IF NOT EXISTS characters(
    id INT NOT NULL PRIMARY KEY AUTO_INCREMENT
    name CHAR(255) NOT NULL,
    age INT NOT NULL,
    description VARCHAR(500) NOT NULL,
  ); 
  |

10. In SQL how can you query more than a single table? Provide an example.

  > | SELECT * from bob JOIN frank ON bob.id = frank.id |
