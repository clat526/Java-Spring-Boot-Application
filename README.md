This Project is a Java Spring Boot Application that creates tables for a database.
The technologies used for this project is Java, Eclipse, Spring Boot, and DBeaver.
My two favorite parts of this project is running the application and seeing Spring Boot creates the tables for the database and also seeing how Spring Boot works by running the application.
Code Snippets: package pet.store;

import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;

@SpringBootApplication 
public class PetStoreApplication {

	public static void main(String[] args) {
		SpringApplication.run(PetStoreApplication.class, args);

	}

}
Installation Instructions: To install this project first you need to install eclipse and create a new maven project, then you need to go to start.spring.io to add the dependencies for project you will be adding web, jpa, mysql, and lombok. Then you will delete the code that's in your pom.xml file and replace it with the code from start.spring.io with the dependencies you just added and then you will be able to run the application without any errors using the source code.
Contact info: caleblatnie7@gmail.com
