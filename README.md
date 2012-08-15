my-first-web-app  
================
             
i have created my first webapp using java6, derby and tomcat7.0.29


Directory structure: parent directory-sudheerWebApp (standard directory structure for tomcat)
-------------------

/pages:

              index.jsp - manages dynamically updating blog.
              
/WEB-INF/classes: package-sudheer:

                 WelcomeServlet.class - manages updates with user's posts.
                 DeleteServlet.class - manages deletion of user's posts.
                 dblink.class - handles derby database for the above servlets.
                 
/WEB-INF/src:

                 contains java source files for the above given classes.
                
/WEB-INF/lib:
                 standard tomcat derby server-client jars contained.
                 
/WEB-INF/web.xml:  standard tomcat web.xml configuration for used servlets.
-----------------

UML diagram given in sudheerWebApp.pdf.

Note:- The character lengths for text inputs are of order 30 characters.