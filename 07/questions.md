# Managing the Fullstack Application

1. Describe the two ways to bind Data in Vue?

  > | v-if and v-for, v-if will say that if something is true, do this and v-for will do something for each item specified in the statement |

2. The `SPA` acronym stands for what?

  > | Single Page Application |

3. What are some of the advantages/uses of a `SPA` over a traditional one?

  > | A single page application will download all the data you need once and then it's there unless you refresh the page. In a traditional application it would be downloading and getting that data every time you change pages |

4. What does the `onMounted` method in Vue do?

  > | it calls on functions as soon as the page is loaded |

5. What is the `v-model` attribute in Vue for, and when might you use it?

  > | it's for two-way data binding. We use it to collect user input and fill out forms |

6. What is the package.json file used for?

  > | It contains the data for our project like the name, version, dependencies etc |

7. Which Vue attributes(directives) could you use to conditionally render elements on a page?

  > | v-if will load things only if something is true and v-for will load an element for every item in an array. v-model could also technically work but I feel like that's just for user input |

8. What is the purpose of the `key` attribute when using `v-for` on an element?

  > | It tells the v-for what to look for so it knows what to grab. Such as if you give it a key of 'id', it'll look for items that have a value of id |

9. What is the `<slot>` element and what is it used for?

  > | It's how you load a component inside of another component. I generally throw things in their own components if they start getting too hefty and cluttering up the page of it the components need to be called multiple times within our code, like a form that can be called from multiple locations. |
