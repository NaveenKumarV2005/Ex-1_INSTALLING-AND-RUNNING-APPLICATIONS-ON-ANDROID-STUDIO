# EX-1: INSTALLING AND RUNNING APPLICATIONS ON ANDROID STUDIO

**Name:** Naveen Kumar V

**Register Number:** 212223220068

## Aim

To develop and run a simple Temperature Converter application using Android Studio, Java, and XML to convert temperature from Celsius to Fahrenheit.

## Software Requirements

- Android Studio
- Java Development Kit (JDK)
- Android SDK
- Android Virtual Device (AVD)
- Java
- XML

---

## Step 1 – System Requirements

The required software tools are used to develop, design, and run Android applications. Android Studio provides the development environment, Java is used to implement the application functionality, and XML is used to design the user interface.

### Required Software

- Android Studio
- Java Development Kit (JDK)
- Android SDK
- Android Emulator

---

## Step 2 – Setup Android Studio

Android Studio is the official Integrated Development Environment (IDE) used for Android application development.

### Installation Procedure

1. Download Android Studio from the official website.
2. Run the installer and follow the installation instructions.
3. Install the required Android SDK components.
4. Configure the Android SDK location.
5. Set up an Android Virtual Device if required.
6. Launch Android Studio.
7. Create a new project using the Empty Views Activity template.
8. Select Java as the programming language.

---

## Temperature Converter Application

1. Open the project in Android Studio.
2. Design the user interface using the `activity_main.xml` file.
3. Add a heading named **Temperature Converter**.
4. Add an EditText field to enter the temperature in Celsius.
5. Add a Button named **Convert**.
6. Add a TextView to display the converted temperature.
7. Open the `MainActivity.java` file.
8. Initialize the EditText, Button, and TextView using `findViewById()`.
9. Implement the button click event using `setOnClickListener()`.
10. Read the temperature entered by the user.
11. Convert Celsius to Fahrenheit using the formula:

   **Fahrenheit = (Celsius × 9/5) + 32**

12. Display the converted temperature in the TextView.


## Output

**Fahrenheit: 98.60 °F**

<img width="253" height="488" alt="688360247-489a8d79-68a6-46b1-ad7f-2fd7a7dcd396" src="https://github.com/user-attachments/assets/d974df75-98ac-49cb-ad2f-cf502ddf32d2" />

---

## Result

Thus, the Temperature Converter application was successfully developed and executed using Android Studio. The application converts temperature from Celsius to Fahrenheit and displays the result when the Convert button is clicked.
