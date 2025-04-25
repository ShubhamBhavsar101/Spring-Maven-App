
# Spring Maven App

## 🛠️ Installation

#### Java
```bash
sudo apt install openjdk-17-jdk
```

#### Maven - [Installing Maven](https://github.com/ShubhamBhavsar101/Installing-Maven)

#### IntelliJ IDEA Community
```bash
sudo snap install intellij-idea-community --classic
```

## 🚀 Creating Project

1. Go to [Spring Initializr](https://start.spring.io/) and create a Maven Spring Project.
2. Open the downloaded project in IntelliJ IDEA Community Edition.
3. Create a class `myClass` with `@RestController` and `@RequestMapping` annotations. Refer to the code in this repo.
4. Add an `index.html` in `src/main/resources/static` to serve as the homepage. Refer to the example in this repo.
5. Run the project from the IDE and verify the index page loads at `http://localhost:8080`.
6. Build the project:
```bash
mvn clean install
```
7. Run the generated `.jar` file:
```bash
java -jar target/maven-demo-0.0.1-SNAPSHOT.jar
```
