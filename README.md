# routee-checkstyle

The repository's intent is to keep the files that define the coding style of various
[Routee](https://www.routee.net) projects.

### Java (java-checkstyle.xml)
The code style is applied using the [checkstyle development tool](http://checkstyle.sourceforge.net).
Most of the rules are based on the [Google Java style guide](https://google.github.io/styleguide/javaguide.html).
Modifications of that ruleset are the following : 
 * Methods annotated with `@Bean`, `@After`, `@Before` require no javadoc.
 * Constructors require no javadoc (subject to change)
 * Block indentation is using 4 spaces instead of 2
 * Empty catch blocks are allowed
 * Sequential capital letters are allowed in names. (For example `codeISO3`)
 * Octal values and unicode escaped values are allowed (subject to change)
 * Members are allowed to be named : SMS
 * Line length limitations (120 characters) do not apply on lines which start with the `@PreAuthorize` annotation.
