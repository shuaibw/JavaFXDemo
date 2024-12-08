# JavaFXDemo

This repository provides a simple example for creating and running JavaFX applications using IntelliJ IDEA and Java JDK (>= 17.0.1).

---

## Prerequisites
- **Java JDK**: Version **17.0.1** or higher.
- **IntelliJ IDEA**: Recommended IDE for this project.

---

## Setup Instructions

### 1. Download the JavaFX SDK
- Visit the official [Gluon JavaFX page](https://gluonhq.com/products/javafx/).
- Download the **JavaFX SDK for Windows**.
- Select version **23.0.1**, as it is compatible with Java 17.
- Unzip the downloaded SDK to a convenient location.

---

### 2. Clone the Repository
Clone this GitHub repository to your local machine:
```bash
git clone https://github.com/shuaibw/JavaFXDemo.git
```
Open the cloned folder in **IntelliJ IDEA**.

---

### 3. Configure JavaFX in IntelliJ
- **Add the JavaFX SDK library to your project**:
    1. Go to **File > Project Structure > Libraries**.
    2. Click the `+` button to add a new library.
    3. Navigate to the unzipped JavaFX SDK folder and select the `lib` directory (e.g., `javafx-sdk-23.0.1/lib`).
    4. Click **OK** to add it.

- **Set the Project Language Level**:
    1. Go to **File > Project Structure > Project**.
    2. Set **Project Language Level** to `17 - Sealed types, always-strict floating-point semantics` or higher.

---

### 4. Run the Application
- Navigate to `src/demo/HelloFX.java` in IntelliJ.
- Click the green **Run** icon next to the `main` method to execute the program.

---

## Additional Notes
- The `module-info.java` file specifies the required JavaFX modules. Without this file, the application will not run.
---