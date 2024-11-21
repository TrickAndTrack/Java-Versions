# Java-Versions

# Java 9 Features

Java 9 introduced several enhancements and new features to improve the language, API, and runtime. Below is an overview of the key features with examples.

## Key Features

### 1. **Java Platform Module System (JPMS)**
- Introduced the module system to improve application scalability and maintainability.
- Enables developers to create modular applications by defining explicit module dependencies.

**Example:**
```java
module com.example.module {
    requires java.sql;
    exports com.example.api;
}
```
