JBoss Java EE 7 with RHDM
===================================

This BOM builds on the Java EE full profile BOM, adding Red Hat Decision Manager.
 
Usage
-----
 
To use the BOM, import into your dependency management:

    <dependencyManagement>
        <dependencies>
            <dependency>
               <groupId>org.jboss.bom.rhdm</groupId>
               <artifactId>jboss-javaee-7.0-with-rhdm</artifactId>
               <version>7.1.0-SNAPSHOT</version>
               <type>pom</scope>
               <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement>
