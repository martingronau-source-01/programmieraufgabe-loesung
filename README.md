# programmieraufgabe-loesung

* The “programming task” was solved in the given project structure, with additional structures and files being added, in particular to the sub-task to the CEO for strategic sales.
* 1. The dependency jakarta.mail is now also stored in the pom.xml (Maven). 
* 2. The h2 database tables ROLE and EMPLOYEE are in both the schema.sql (structure) and the data.sql (data). They are used here to determine the required profile data of the CEO for strategic sales from persistent storage
* 3. the resource mailsend.properties contains the necessary configuration data for actually sending emails using jakarta.mail (mailtrap.io access was initially used for temporary simulation)
* 4. The MailsendService and MailSendSourceHelper services are used to create and (simulated) send emails, such as the email to the ceo for strategic studies.
* 5. The models Employee, Role, RoleType, the entity enum RatingTypeEntity, the entity classes EmployeeEntity and RoleEntity as well as the EmployeeRepository are primarily used for reading processing of employee and role data
* 6. The temporary database system H2 and the simulated email sending via mailtrap.io correspond to the test or task character of the project. A switch to more permanent persistence such as a MySQL/MariaDB database and/or a real email provider would certainly be possible without any problem.
* 
* Still questions? Simply contact +49163 2380475

