prerequisite
============

This is a simple project to enable workspace validation prior taking the course.

Your workspace must include the following:
- IDE
- Java 7
- Maven 3
- Tomcat 7
- Git

All following steps **MUST** pass successfully:

1. Import attached project into your IDE.
2. Run: mvn clean install (can do it inside IDE)<br/>
**If the build fails then you have a problem in your environment**
3. Add a Tomcat configuration and add the project artifact (deployment tab)
4. Run the tomcat, open browser to your tomcat host:port (you should see *"PASSED, you are good to go"*)<br/>
**If the tomcat fails to lad then you have a problem in your environment**<br/>


