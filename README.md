

# J2EE-Transaction

A Java EE (Jakarta EE) project demonstrating distributed transaction management using JTA (Java Transaction API). This project is packaged as a `.war` and is intended for deployment in a Java EE compatible application server such as **WildFly**, **GlassFish**, or **Payara**.

## 📦 Project Info

- **Group ID:** `lk.mydomain.rmi`
- **Artifact ID:** `J2EE-Transaction`
- **Version:** `1.0-SNAPSHOT`
- **Packaging:** `war`
- **Java Version:** `11`
- **Jakarta EE Version:** `10`

## ⚙️ Technologies Used

- Java 11
- Jakarta EE 10 (jakarta.jakartaee-api)
- Maven
- JTA (Java Transaction API)
- WAR packaging for deployment

## 📁 Project Structure


J2EE-Transaction/
│
├── src/
│   ├── main/
│   │   ├── java/               # Java source code
│   │   ├── resources/          # Configuration files
│   │   └── webapp/             # Web resources (JSP, HTML, etc.)
│
├── pom.xml                     # Maven build configuration
└── README.md                   # Project documentation
```

## 🚀 How to Run

1. **Build the Project:**

```bash
mvn clean package
```

2. **Deploy the WAR:**

Copy the generated `.war` file from the `target` directory to your application server's deployment directory.

For example, in **WildFly**:

```bash
cp target/web-jta.war $WILDFLY_HOME/standalone/deployments/
```

3. **Access the Application:**

Visit the deployed app in your browser:

```
http://localhost:8080/web-jta/
```

## 🧪 Testing

You can test transaction behavior using REST endpoints or servlets (to be implemented) that demonstrate commit/rollback scenarios using JTA.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙌 Author

**Sasanda Saumya**  
🔗 [GitHub](https://github.com/SasadaSaumya)
```
You can save this content as `README.md` at the root of your GitHub repository. Let me know if you need any further modifications or additions!
