Clear and meaningful variable names

Meaningful variable names help any user to understand and follow the code easily. Its best to avoid using ambiguous names such as “temp, data, etc”, Unclear names make unclear code! Another way to increase legibility and aid new users to understand the code is by making concise comments around any logic that may not be intuitive.

Tips when naming variables
•	If you are unsure about what to use when naming variables, its common practice to use the Hungarian Notation for a guideline.
•	Avoid using synonyms for name as the meaning may be misinterpreted.
•	Try not to use digits in variable names.

Well documented code

Well documented code is often reused, due to its clear definition or spec. It also encourages maintainability as code that is written well can be maintained well. The understandability and legibility of code is also very important, and good documentation of the codes functionality, scope and expected results can help promote and maintain this. It can also aid in the process of debugging the code; by having a well-defined spec and documentation it can help us discover bugs and unusual behaviour by comparing it to the expected behaviour.

Tips for documenting code
•	The documentation should include the expected outcome of the feature/code.
•	The document should define the purpose of the feature.
•	The document should list any classes that may be affected by the change.

Indentation

Good spacing can help improve the readability of the code. It also can help view the code in a more linear fashion. The alignment of methods and blocks can help make nested statements easier to follow.

Tips for Indentation
•	Allow white spacing between methods and variables.
•	Nested blocks should be indented.
•	Multiple conditionals should be indented to avoid confusing brackets.

Error Handling

Error handling is key when ensuring good coding practices. It provides assurance when unexpected behaviour arises in code. Good error handling should also be able to account for user error and help provide a meaningful message to the use that will aid them with the problem.

Tips for Error Handling
•	Error conditional functions should always return something, to aid the user debugging.
•	Provide useful error messages in your code, this helps identify the problem regardless if the error is due to user input or developer incompetence.
•	Console log unexpected behaviour to help aid others to understand the code.

Testing

Testing is a large part of coding standards; testing allows us to make sure that the code stays true to the defined spec and allows us to identify and handle any strange behaviour of the code. Testing can also be used as a criteria that the code should meet, for example, when developing a feature it should be developed in such a way that the code written will pass the tests. This will help the code adhere to the given spec and discourage “spaghetti code” throughout the application.

Tips for Testing 
•	Write tests before development. This will help the developer to stick to the spec and helps make the code measurable and adhere to the expected behaviour.
•	Make sure that the test coverage covers the code that you have developed. And that all conditionals paths are accounted for.
•	Whenever implementing a new piece of code, run ALL test suits to make sure that the code change doesn’t impact other areas of the application.
•	Testing should be done with test data and real data.

