# registration_portal_Heckathon
This project is for online open elective Counselling and Registration.
Open Elective Counselling is based on CGPI and Choices just like JEE main Counselling.
# Steps
1.use Eclipse Luna
2.right click on your project->Bulid path->add External Jars->choose Destination
3.import servlet-api.jar
4.import ojdbc14.jar(this is connector to Oracle Database)
5.import mail.jar(Javamail-1.4.7)
6.Activation.jar(jaf-1.1.1)
7.Also copy above jar files in Tomcat 7.0->lib->above jar files 
# Create Databases in Oracle(use port 8080)
# Create NITH1DB table in database 
# Create Column(Don't Change The Order)
a.COUNT(INT,AUTOINCREMENT,UNIQUE)
b.NAME(VARCHAR2)
c.ROLL(VARCHAR2)
d.BRANCH(VARCHAR2)
e.SEM(VARCHAR2)
f.CGPI(NUMBER)
g.FIRSTCHOICE(VARCHAR2)
h.SECONDCHOICE(VARCHAR2)
i.THIRDCHOICE(VARCHAR2)
j.FOURTHCHOICE(VARCHAR2)
k.FIVETHCHOICE(VARCHAR2)
l.FIRST(NUMBER)
m.SECOND(NUMBER)
n.THIRD(NUMBER)
o.FOUR(NUMBER)
p.FIVE(NUMBER)
q.GMAIL(VARCHAR2)
# Create NITHMAINDB table in database 
# Create Column(Don't Change The Order)
b.NAME(VARCHAR2)
c.ROLL(VARCHAR2)
d.BRANCH(VARCHAR2)
e.SEM(VARCHAR2)
f.CGPI(NUMBER)
g.FIRSTCHOICE(VARCHAR2)
h.SECONDCHOICE(VARCHAR2)
i.THIRDCHOICE(VARCHAR2)
j.FOURTHCHOICE(VARCHAR2)
k.FIVETHCHOICE(VARCHAR2)
l.FIRST(NUMBER)
m.SECOND(NUMBER)
n.THIRD(NUMBER)
o.FOUR(NUMBER)
p.FIVE(NUMBER)
q.GMAIL(VARCHAR2)
# Create SEAT table in database 
# Create Column(Don't Change The Order)
a.MATH(number)
b.PHYSICS(NUMBER)
c.CHEMISTRY(NUMBER)
# Create ELECTIVEDB table in database 
# Create Column(Don't Change The Order)
a.ROLL(VARCHAR2)
b.ELECTIVE(VARCHAR2)
# Create VALUE table in database 
# Create Column(Don't Change The Order)
a.VER(NUMBER)
