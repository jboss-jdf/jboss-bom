JBoss Java EE 6 with Deltaspike
===============================

This BOM builds on the Java EE full profile BOM, adding Deltaspike.
 
Usage
-----

To use the BOM, import into your dependency management:

    <dependencyManagement>
        <dependencies>
            <dependency>
               <groupId>com.redhat.jboss.wfk.boms</groupId>
               <artifactId>jboss-javaee-6.0-with-deltaspike</artifactId>
               <version>1.0.4.Final-redhat-1</version>
               <type>pom</scope>
               <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement>
