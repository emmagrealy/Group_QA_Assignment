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
-	Good white spacing helps to improve readability.
-	Nested blocks should be indented.
-	Multiple conditionals should be indented to avoid confusing brackets.
Error Handling
-	Error conditional functions should always return something, to aid the user debugging.
-	Provide useful error messages in your code, this helps identify the problem regardless if the error is due to user input or developer incompetence.
-	Console log unexpected behaviour to help aid others to understand the code.
Testing
-	Write tests before development. This will help the developer to stick to the spec and helps make the code measurable and adhere to the expected behaviour.
-	Make sure that the test coverage covers the code that you have developed. And that all conditionals paths are accounted for.
-	Whenever implementing a new piece of code, run ALL test suits to make sure that the code change doesn’t impact other areas of the application.
-	If the code has any specific behaviour, make sure this is tested.
-	Testing should be done with test data and real data.
