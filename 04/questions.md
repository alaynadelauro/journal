# Understanding Asynchronous Code, and API's
01. What is the difference between `asynchronous` code and `synchronous` code?

  > | an async function can run multiple things at a time while a normal (synchronous) function will only run one at a time |

02. What is an event listener?

  > | a little thingy in your controller that listens for when a specified change in the appstate. When that thing changes, it'll execute a function you tell it to |

03. What does *REST* stand for, and in simple terms what does it mean??

  > | representational state transfer: according to google it's "an architectural style providing standards between computer systems on the web, making it easier for systems to communicate with each other". |

04. What is a callback / higher order function?

  > | a function that's only executed after another function has stopped running |

05. What is a `promise`? How do you capture an error from a `promise`?

  > | A promise basically tells a function that we will do something. To catch an error we would put it into a try-catch function and tell it to await what we promised it would happen and if that promise isn't fulfilled, to send us an error in the catch instead such as a pop or windows error |

06. Name three processes used to make requests over `HTTP`?

  > | Get, Push(put), Delete(destroy) |

07. What does the `API` acronym stand for?

  > | Application programming interface |

08. What must you do in order to `await` a promise inside of a function?

  > | make the function async and then type await in front of the function/promise we're waiting on |

09. What is the purpose of encapsulation in programming?

  > | It makes things more secure so that you can't do what Sam did when she was grading my squid farmer and give herself 1000000 squid steaks |

10. What is `HTTP` response code for a successful request?

  > | 200 |

11. What is a 400 error?

  > | The middle finger cat - I mean bad request |
