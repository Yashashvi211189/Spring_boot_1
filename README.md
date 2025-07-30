<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>rest-demo - Spring Boot REST API</title>
</head>
<body>
  <h1>🛠️ rest-demo - Spring Boot REST API</h1>

  <p>This is a <strong>Spring Boot</strong> demo project for building RESTful web services with <strong>Spring Web</strong>, 
  <strong>Spring Data JPA</strong>, <strong>MySQL</strong>, <strong>Swagger API documentation</strong>, and <strong>Actuator</strong> 
  for monitoring. It includes a test database (H2) and standard configurations for testing and development.</p>

  <h2>📦 Project Structure</h2>
  <ul>
    <li><strong>Java Version:</strong> 18</li>
    <li><strong>Spring Boot Version:</strong> 2.7.1</li>
    <li><strong>Maven Compiler Target:</strong> 14</li>
    <li><strong>Build Tool:</strong> Maven</li>
  </ul>

  <h2>📚 Features</h2>
  <ul>
    <li>REST API using Spring Boot Starter Web</li>
    <li>Database access via Spring Data JPA</li>
    <li>MySQL integration</li>
    <li>In-memory H2 database for testing</li>
    <li>Swagger 3 API documentation using Springfox</li>
    <li>Actuator endpoints for application monitoring</li>
    <li>Unit testing support</li>
  </ul>

  <h2>⚙️ Technologies Used</h2>
  <table border="1" cellpadding="6" cellspacing="0">
    <thead>
      <tr>
        <th>Technology</th>
        <th>Purpose</th>
      </tr>
    </thead>
    <tbody>
      <tr><td>Spring Boot</td><td>Backend framework</td></tr>
      <tr><td>Spring Web</td><td>Creating REST APIs</td></tr>
      <tr><td>Spring Data JPA</td><td>Database access and ORM</td></tr>
      <tr><td>MySQL</td><td>Main production database</td></tr>
      <tr><td>H2</td><td>In-memory test database</td></tr>
      <tr><td>Swagger</td><td>API documentation (UI + JSON)</td></tr>
      <tr><td>Actuator</td><td>Health & metrics endpoints</td></tr>
      <tr><td>Maven</td><td>Build and dependency management</td></tr>
    </tbody>
  </table>

  <h2>🚀 Running the Application</h2>

  <h3>1. Prerequisites</h3>
  <ul>
    <li>Java 18 installed</li>
    <li>Maven installed</li>
    <li>MySQL server running</li>
  </ul>

  <h3>2. Clone the repository</h3>
  <pre><code>git clone https://github.com/your-username/rest-demo.git
cd rest-demo</code></pre>

  <h3>3. Configure <code>application.properties</code></h3>
  <pre><code>spring.datasource.url=jdbc:mysql://localhost:3306/your_db_name
spring.datasource.username=your_username
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update</code></pre>

  <h3>4. Build and Run</h3>
  <pre><code>mvn clean install
mvn spring-boot:run</code></pre>

  <h2>📘 API Documentation</h2>
  <p>Once the app is running, visit:</p>
  <pre><code>http://localhost:8080/swagger-ui/</code></pre>

  <h2>🔍 Actuator Endpoints</h2>
  <p>Access actuator metrics at:</p>
  <pre><code>http://localhost:8080/actuator</code></pre>

  <h2>🧪 Running Tests</h2>
  <pre><code>mvn test</code></pre>

  <h2>📁 Folder Structure</h2>
  <pre><code>rest-demo/
│
├── src/
│   ├── main/
│   │   ├── java/com/thinkconstructive/
│   │   └── resources/
│   └── test/
├── pom.xml
└── README.html</code></pre>

