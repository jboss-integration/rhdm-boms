RHDM Suite BOM
===================================

This BOM contains all supported Maven artifacts for Red Hat Decision Manager.
Usage
-----
 
To use the BOM, import into your dependency management:

    <dependencyManagement>
        <dependencies>
            <dependency>
               <groupId>org.jboss.bom.rhdm</groupId>
               <artifactId>rhdm-bom</artifactId>
               <version>7.0.0-SNAPSHOT</version>
               <type>pom</scope>
               <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement>
