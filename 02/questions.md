# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > | the best way I can describe this is that a keyword is a value assigned to a property of an object, such as the object Person having a property of Name and the keyword having the value 'Katherine' |

02. What is the definition of a function?

    > | The dictionary definition is: a relationship or expression involving one or more variables. I feel like in coding the answer is closer to a statement that tells the computer that if something happens, then do 'this' |

03. What are the `SOLID` principles?

    > | ANSWER HERE |

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > | you'd want to use the find function to grab the pineapple. If you wanted to do something with it elsewhere, you could then do that. If you wanted to get everything in the array but leave out pineapple then you could use the find function to assign it a value and then filter the array to make it select everything except the pineapple |

05. Given these two objects: How could you add each to the others friends arrays?

    ```js
    let you = {
        name: "You",
        hair: true,
        friends: []
    }
    let them = {
        name: "Them",
        hair: false,
        friends: []
    }
    ```

    > | go into the brackets by friends and type in the information as a new variable|

06. Give an example of a JavaScript `Conditional`:

    > | if( bob == steven){return true true}else{false} |

07. What is the main difference between `parameters` and `arguments`?

    > | a parameter is something that tells a function what to look for in the html, the argument is the element assigned to an object in html that tells the javascript what it is. EX: getABagel('bagel type') bagel type would be the parameter, and then in the HTML getABagel('Chocolate Chip') would be the argument, telling the function that the bagel the function got was Chocolate Chip |

08. Instead of writing everything to the console, what is a better way to debug your code?

    > | Create a windows error message to tell you what part exactly went wrong |

09. What is the difference between a `primitive` value and a `reference` value?

    > | a reference value refers back to a primitive value (such as assigning a variable to a property of an object in an array) |

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > | for(i = -100; i<=100; i++) |
