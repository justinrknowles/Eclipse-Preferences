Eclipse Templates
=================

Add these templates to your Eclipse environment using
`Preferences > Java > Editor > Templates > Import...`

JUnit Templates
---------------

* `aaa`: declares a JUnit 4 test method with Triple-A comments: Arrange, Act, and Assert.
* `at`: inserts the `assertThat()` method.
* `ee`: inserts the body of a test case that is expecting an exception.
* `eq`: inserts the `equalTo()` matcher.
* `parameters`: declares a JUnit 4 test data method to provide data to a JUnit 4 parameterized test.
* `test`: declares a JUnit 4 test method.

jMock Templates
---------------
 
* `context`: declares a `Mockery` instance.
* `expectations`: declares a context for specifying expectations.
* `mock`: declares a mock instance.
* `rv`: declares a mock's return value.


Eclipse Favorites
=================

Compact readable test code makes use of many static methods. Eclipse provides no content assist for 
these static unless you add them using the Java > Editor > Content Assist > Favorites preference.

* `java.util.Arrays.*`
* `java.util.Collections.asList`
* `org.hamcrest.CoreMatchers.*`
* `org.hamcrest.Matchers.*`
* `org.junit.Assert.*`
* `org.junit.matchers.JUnitMatchers.*`

