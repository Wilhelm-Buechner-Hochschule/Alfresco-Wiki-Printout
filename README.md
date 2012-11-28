Alfresco Wiki Printout
======================

Alfresco Wiki Printout is a simple extension to Alfresco Share that adds a
`print.css` file for printing Wiki pages.

Installation
------------

Requirements:

- Apache Ant
- Java Compiler

Run

    ant

to create the AMP. After `ant` has been run successfully, you'll find the
module package in the `dist/` subdirectory. Afterwards, you can use the
`alfresco-mmt.jar` program to apply the package, e.g.

    java -jar /opt/alfresco/bin/alfresco-mmt.jar \
        dist/wikiprintout.amp \
        /opt/alfresco/tomcat/webapps/share.war

Restart Alfresco and you're done.

If you want to enable or disable the module manually, just browse to
http://yourhost.example.com:8080/share/pages/modules/deploy and select or
deselect the printout module.

Have a lot of fun!

License
-------

This work is licensed under the Apache License, Version 2.0. You can obtain a
copy of this license from http://www.apache.org/licenses/LICENSE-2.0.
