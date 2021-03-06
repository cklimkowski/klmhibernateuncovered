# klmhibernateuncovered
Hibernate Examplified using com.mysql.jdbc.driver to connect with MySQL

This examplifies how to: 
- configure *hibernate.cfg.xml* file to connect to db and set hibernate mapping resources such as *Event.hbm.xml*, *Person.hbm.xml*, *Ticket.hbm.xml*;  
- query db with **session.createQuery**
- persist data with **session.save**
- manage **one-to-many**, **many-to-many** relationships
- use **HQL**
- utilize **lazy-loading**.

This simple sample of what Hibernate can do is truely useful.

All **Hibernate** configuration files, **SQL** db creation file and **Maven** build file are provided and tested.

The main file incorporated with basic unit tests is: **src/main/java/klm/pstryk/HibernateConnection.java**.

After population db with *klm_db_stuff.sql* use: **mvn test** to see how it works.
