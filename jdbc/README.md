# Java Servlets & JDBC

Author: [Sofoklis Stouraitis](mailto:sofos@aueb.gr)



## Course Software

* [MySQL Community Edition](https://dev.mysql.com/downloads/installer/) (installer includes [MySQL Workbench](https://dev.mysql.com/downloads/workbench/))
* [MySQL Workbench](https://dev.mysql.com/downloads/workbench/)
* [JDBC driver for MySQL](https://dev.mysql.com/downloads/connector/j/)


## Examples

### Example 1

* **Example Project 2**
  * [Download Eclipse Project](examples/exampleproject2.zip)

    **Import Project into Eclipse IDE**
    ```
    Step 1: Download it and unzip it to your computer . Then Copy the project's root folder (exampleproject2) into your Eclipse Workspace.
    Step 2: Open Eclpise, File -> import, type project in the search bar and choose Existing Projects into Workspace and press next
    Step 3: In field select root directory press Browse and select exampleproject2.
    Step 4: Fix 'Java Build Path' according to your system settings: Right click to the project (exampleproject2) and select 'Properties', from the left choose `Java Build Path` and click Tab 'Libraries' and ensure that 'Apache Tomcat' and 'JRE System Library' are according to your system settings.
    ```

  * Connect to your MySQL Server and to do the following:
    * Create a `database` and a `user` with full privileges for only this database
    * Create table `employee` and insert records ([employee.sql](examples/employee.sql))
  * [View this Example Running online (Tomcat)](http://orfeas.dmst.aueb.gr/exampleproject2/search)

### Online Examples

* [http://ism.dmst.aueb.gr/labExercises/](http://ism.dmst.aueb.gr/labExercises/)


## Useful Links

* [Package java.sql](https://docs.oracle.com/javase/8/docs/api/index.html?java/sql/package-summary.html)
* [https://www.tutorialspoint.com/jdbc/index.htm](https://www.tutorialspoint.com/jdbc/index.htm)