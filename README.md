## Eclipse Templates

Add these templates to your Eclipse environment using
`Preferences > Java > Editor > Templates > Import...`

### JUnit Templates

* `aaa`: declares a JUnit 4 test method with Triple-A comments: Arrange, Act, and Assert.
* `at`: inserts the `assertThat()` method.
* `ee`: inserts the body of a test case that is expecting an exception.
* `eq`: inserts the `equalTo()` matcher.
* `parameters`: declares a JUnit 4 test data method to provide data to a JUnit 4 parameterized test.
* `test`: declares a JUnit 4 test method.

### jMock Templates
 
* `context`: declares a `Mockery` instance.
* `expectations`: declares a context for specifying expectations.
* `mock`: declares a mock instance.
* `rv`: declares a mock's return value.


## Eclipse Preferences

### Eclipse Favorites

Compact readable test code makes use of many static methods. Eclipse provides no content assist for 
these static methods unless you adjust the Java > Editor > Content Assist > Favorites preference.

* `java.util.Arrays.*`
* `java.util.Collections.*`
* `java.util.Collections.asList`
* `org.hamcrest.CoreMatchers.*`
* `org.jmock.Expectations`
* `org.junit.Assert.*`
* `org.junit.matchers.JUnitMatchers.*`

See [Eclispe on E](http://eclipseone.wordpress.com/2010/02/01/generate-static-imports-in-eclipse-on-autocomplete/#more-818).


### Eclipse Refactoring Keys

There are 3 essential refactorings that do not have a default key binding. Add them to the General > Keys preference. 
Note: on a Mac use Option+Command rather than Alt+Shift.

<table>
	<tr><th>Command</th><th>Binding</th></tr>
	<tr><td>Convert Local Variable to Field</td><td>Alt+Shift+F</td></tr>
	<tr><td>Extract Constant</td><td>Alt+Shift+K</td></tr>
	<tr><td>Introduce Parameter</td><td>Alt+Shift+P</td></tr>
</table>


### Typing Semicolons

Java > Typing > Automatically insert at correct position

    Check Semicolons and Braces  

See [Eclipse on E](http://eclipseone.wordpress.com/2010/02/22/place-a-semicolon-at-the-end-of-a-java-statement-in-eclipse/).


### Type Filters for Tweaking Content Assist

Java > Appearance > Type Filters

    com.sun.media.jai*
    com.sun.org.apache.xalan.internal*
    
    
### Disable Annoying Tooltips on Hover

Java > Editor > Hover

    Combined Hover: Shift
    Source: Ctrl + Shit
    
See [Eclipse on E] (http://eclipseone.wordpress.com/2010/08/24/configure-tooltips-in-eclipse-to-only-popup-on-request/#more-1340).


### Eclipse Plug-ins

<table>
	<tr><th>Plugin</th><th>Update Site</th><th>Notes</th></tr>
	<tr><td>EclEmma</td><td>Eclipse Marketplace</td><td>Code coverage</td></tr>
	<tr><td>ExploreFS</td><td>http://www.junginger.biz/eclipse/</td><td>Open file in Finder</td></tr>
	<tr><td>Infinitest</td><td>http://infinitest.github.com</td><td>Alternate test runner</td></tr>
	<tr><td>MoreUnit</td><td>Eclipse Marketplace</td><td>JUnit enhancements</td></tr>
	<tr><td>MouseFeed</td><td>Eclipse Marketplace</td><td>Teaches shortcuts</td></tr>
	<tr><td>Quantum DB</td><td>http://quantum.sourceforge.net/update-site</td><td>Database tooling</td></tr>
</table>


## Other Eclipse Related Configuration

### Adjust the eclipse.ini Configuration File

````
-vmargs
-Xverify:none
-Dosgi.requiredJavaVersion=1.6
-XX:PermSize=256m
-XX:MaxPermSize=256m
-Xms1024m
-Xmx1024m
````

### Configure OS X Spotlight Indexing

Go into System Preferences > Spotlight > Privacy and add your Eclipse Workspace folder
