<dependency>
  	<!-- https://mvnrepository.com/artifact/mysql/mysql-connector-java -->
    <!-- In order to connect our project to data base we need type-4 jdbc driver we are using mysql provided driver-->
    <dependency>
        <groupId>mysql</groupId>
        <artifactId>mysql-connector-java</artifactId>
        <version>8.0.28</version>
    </dependency>
  
    <!-- https://mvnrepository.com/artifact/org.hibernate/hibernate-core -->
    <!-- In order to use hibernate in our project we need to add hiberante dependency-->
    <dependency>
        <groupId>org.hibernate</groupId>
        <artifactId>hibernate-core</artifactId>
        <version>6.1.2.Final</version>
        <type>pom</type>
    </dependency>
      
    <!-- https://mvnrepository.com/artifact/org.springframework/spring-webmvc -->
    <!-- Spring webmvc contains Spring’s model-view-controller (MVC) and REST Web Services implementation for web applications. 
          It provides a clean separation between domain model code and web forms and 
          integrates with all of the other features of the Spring Framework. -->
    <dependency>
        <groupId>org.springframework</groupId>
        <artifactId>spring-webmvc</artifactId>
        <version>5.3.20</version>
    </dependency>
  
    <!-- https://mvnrepository.com/artifact/org.springframework/spring-context -->
    <!-- Spring Context provides access to configured objects like a registry (a context).
          It inherits its features from Spring Beans and adds support for internationalization, event propagation, resource loading, 
          and the transparent creation of contexts. -->
    <dependency>
        <groupId>org.springframework</groupId>
        <artifactId>spring-context</artifactId>
        <version>5.3.23</version>
    </dependency>
 
    <!-- https://mvnrepository.com/artifact/javax.servlet.jsp.jstl/jstl -->
    <dependency>
        <groupId>javax.servlet.jsp.jstl</groupId>
        <artifactId>jstl</artifactId>
        <version>1.2</version>
    </dependency>

    <dependency>
			<groupId>javax.servlet.jsp</groupId>
			<artifactId>jsp-api</artifactId>
			<version>2.2</version>
			<scope>provided</scope>
		</dependency>

    <dependency>
			<groupId>javax.servlet</groupId>
			<artifactId>javax.servlet-api</artifactId>
			<version>4.0.1</version>
			<scope>provided</scope>
		</dependency>
  
    <dependency>
      <groupId>junit</groupId>
      <artifactId>junit</artifactId>
      <version>4.11</version>
      <scope>test</scope>
    </dependency>

</dependency>
