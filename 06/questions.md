# Single Page Applications with Vue
01. What is the entrypoint of an application?

  > | the home page |

02. What is the difference between a vue `component` and `page`?

  > | A page is the parent of a component |

03. What is ***Component-Based Architecture***?

  > | a style of software engineering that aims to build software out of loosely-coupled, modular components. Copied directly from google |

04. What are the three tags that make up a Vue component?

  > | component slot template |

05. What are ***lifecycle hooks***? What are lifecycle hooks used for?

  > | onMount and onUnmount, onMount will run functions on page load, unmount will run functions as soon as you leave a page |

06. Which component in Vue does the vue-router use to mount pages onto?

  > | pages |

07. What is the difference between the `AppState` and the state object within a component?

  > | The AppState stores data for the entire application while the state object just stores data for specific component it's in |

08. What is the responsibility of `Services` in our Vue projects?

  > | to change variables stored in the AppState and handle functions we want abstracted away from the user |

09. What are ***props*** and how are they used? Provide an example

  > | they import variables from parent objects and give them a new name to use in a component |

10. What is the Vue method used to create watchable objects such as `state` or `AppState`?

  > | compute|
