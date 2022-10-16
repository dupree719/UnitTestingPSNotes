Unit Testing is for confirming that a small unit of code works correctly. This small unit can be a Java class, a specific method in a class, or a static function.

Component tests- When a unit test exercises target code in several classes at once

Benefits of Unit Testing:
#Provides quick feedback
#Automated regression checking
#Helps with design
#Improves confidence
#Form of documentation

"Click to see difference" after a failed test can be useful especially if the differences involve white space.

Annotations: 
@Test annotation marks a method as a test method. *MAKE SURE TESTS ALWAYS FAIL FIRST*
@BeforeEach annotation makes it so you do not have to repeat instances for every test method.
@AfterEach is executed after each test method. This is generally used to clean up the data or to perform an action after a @Test method.
@BeforeAll runs only once before all the test methods of a Test class.
@AfterAll runs only once after all the test methods of a Test class.
@Tag is a repeatable annotation that is used to declare a tag for the annotated test class or test method. Tags are used to filter which tests are executed for a given test plan.

Single Responsibility Principle:
A unit of code does ONE thing.
It should only have one reason to change.

Test Double:
Help you isolate the code under test so that you can test all facets of its behavior.
Test Double is a generic term for any case where you replace a production object for testing purposes.

Test-driven Development (TDD cycle)
Rather than implementing a feature first, then testing it, drive development of the feature from a test.
Works by frequent switching from test to production code and back 

-Write just enough test code to fail
-Then write just enough production code to pass test and no more
-Clean up the implementing code

Benefits: 
#Keeps you focused (very easy to become sidetracked when writing code)
#Produces testable designs
#Helps produce code with clear interfaces
#Helps produce clean code
