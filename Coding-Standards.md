# Coding Standards
Coding standards have been introduced into the Software Industry to try and help have a positive impact on businesses. Writing clean code is a matter of personal habit as much as it's a matter of skill.
It is not easy to produce high quality code, consistent efforts and focus is required by all members of the team to ensure their tasks are completed to an acceptable standard.

Coding standards involve a series of procedures for each programming language and specifying a programming style, methods and procedures. These are the essential attributes of software development. By implementing coding standards it ensures each member of a project are following the same guidelines, code can be easily understood and consistency is maintained. 

## Why do we have Coding Standards?
### 1. Security Concerns 
Inconsistent code means it is vulnerable to attacks. Inconsistent code can mean it contains bugs or errors within the logic. Most of these problems arise due to faulty programming code which can be as a result of poor coding practices. 

### 2. Performance Issues
Poor coding standards can have a serious implication on the software performance. Performance issues can have an implication on an abundance of things. It can compromise server response times, reusability, user interaction with the site and many more.

### 3. Motivation
Members of a project will be motivated by knowing other members of the team reviewing their commits. This will ensure that members of the team pay attention to their own code and also thoroughly review their team members code. Recognition of coding standards from your peers is a source of pride and achievement for many programmers.


### 3. Motivation
Members of a project will be motivated by knowing other members of the team reviewing their commits. This will ensure that members of the team pay attention to their own code and also thoroughly review their team members code. Recognition of coding standards from your peers is a source of pride and achievement for many programmers.

## Coding Standards with examples
### Clear and meaningful variable names.
-	Good variable names increase readability of code for users.
-	Use comments to explain logic in code.
-	Helps make long lasting code.
-	Unclear names make unclear code, Avoid (temp, data, p1)
-	If unsure use Hungarian notation for guidelines.
-	Avoid synonyms in naming 
![Variable Name Examples](https://present5.com/presentation/6959192061c9a298410d3d3fc2b8e790/image-5.jpg)


### Well documented code
-	Well documented code is often reused due to its clear definition and explanation.
-	Good documentation encourages maintainability, understandability and legibility.
-	Can help define expected outcome of code, and in turn help debug errors that may arise.
-	Helps make sure the code is staying true to the defined scope.
![Code Documentation Example](https://gitdemo.readthedocs.io/en/latest/_images/doc-code-documentation-inline.png)


### Indentation
-	Good white spacing helps to improve readability.
-	Nested blocks should be indented.
-	Multiple conditionals should be indented to avoid confusing brackets.
![Indentation Example](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/ccd3815d-299e-490e-81ca-4fb02c8209b9/cleancode-3.png)


### Error Handling
-	Error conditional functions should always return something, to aid the user debugging.
-	Provide useful error messages in your code, this helps identify the problem regardless if the error is due to user input or developer incompetence.
-	Console log unexpected behaviour to help aid others to understand the code.
![Error Handling 1](https://res.cloudinary.com/dchysltjf/image/upload/f_auto,q_auto:best/v1574436354/error3.png)
![Error Handling 2](https://dab1nmslvvntp.cloudfront.net/wp-content/uploads/2011/12/error-handling-04.png)


### Testing
-	Write tests before development. This will help the developer to stick to the spec and helps make the code measurable and adhere to the expected behaviour.
-	Make sure that the test coverage covers the code that you have developed. And that all conditionals paths are accounted for.
-	Whenever implementing a new piece of code, run ALL test suits to make sure that the code change doesn’t impact other areas of the application.
-	If the code has any specific behaviour, make sure this is tested.
-	Testing should be done with test data and real data.
![Testing Example](https://qph.fs.quoracdn.net/main-qimg-89a2179ac50965232d0cb59ea819d290)

Links used ---
- https://javarevisited.blogspot.com/2014/10/10-java-best-practices-to-name-variables-methods-classes-packages.html
- https://www.perforce.com/blog/qac/9-coding-standards-best-practices
- https://guide.freecodecamp.org/cplusplus/clean-code-guidelines/
- https://blog.codacy.com/why-coding-standards-matter/
- https://javarevisited.blogspot.com/2014/10/10-java-best-practices-to-name-variables-methods-classes-packages.html?fbclid=IwAR1iY6F6UNmeTkJNEDyUjrj2wrxtmHZK2K8lDLZrjl4VPj8QWSlQIyyGbiA