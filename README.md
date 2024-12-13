![ezgif com-optimize](https://github.com/user-attachments/assets/70fb25a8-16c9-407d-bcc3-38a4c94cfd06)

# FitLife: Fitness Class Booking System 

**FitLife** is a console-based Java application designed to manage fitness class bookings efficiently. The project applies Object-Oriented Programming (OOP) principles to offer a modular, scalable, and user-friendly system. **FitLife** integrates the Sustainable Development Goal (SDG) 3: *Good Health and Well-Being*, by promoting healthy lifestyles through access to fitness classes. 

---

## 📋 SUMMARY OF SECTIONS

1. **Project Overview** 🌟
2. **OOP Principles Applied** 💡
3. **Sustainable Development Goal Integration** 🌍
4. **Instructions for Running the Program** 🚀
5. **Project Development Timeline** 🛠️
6. **Class Overview** 📚
7. **Project Developer** 👨‍💻

---

## 🌟 Project Overview
**FIT LIFE** is a dynamic fitness class booking system supporting various class types, such as Yoga, Zumba, Cycling, and Dance. Users can:

- View available fitness classes. 📅
- Book fitness classes by entering their name and student ID. 📝
- View registered students for specific classes. ❌
- Cancel bookings if needed. 👥

The program handles multiple fitness classes, tracks student bookings, and ensures efficient cancellation and retrieval of records.

---

## 💡 OOP Principles Applied
# OOP Principles in FitLife System

| **OOP Principle**   | **Description**                                                                                     | **Application in FitLife**                                                                                          |
|---------------------|-----------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| **Encapsulation**    | The concept of bundling the data (attributes) and methods (functions) that operate on the data.     | - `Student` and `FitnessClass` have private fields that can only be accessed through getters and setters.             |
| **Inheritance**      | The mechanism by which one class can inherit the attributes and methods of another class.           | - Classes like `YogaClass`, `ZumbaClass`, `CyclingClass`, and `DanceClass` inherit from the `FitnessClass` base class. |
| **Polymorphism**     | The ability of different classes to implement methods that have the same name but behave differently. | - Each `BookingSystem` subclass overrides methods like `bookClass()`, `cancelClass()`, and `showClassDetails()`.       |
| **Abstraction**      | Hiding the complex implementation details and showing only the necessary functionality.            | - `BookingSystem` is an abstract class that defines methods for booking and canceling classes, but the implementation is in subclasses. |


---

## 🌍 Sustainable Development Goal Integration
**SDG 3: Good Health and Well-Being**

FitLife aligns with SDG 3 by promoting active and healthy lifestyles through easily accessible fitness classes. The platform fosters community engagement in health and fitness activities, contributing to improved physical and mental well-being.

---

## 🚀 Instructions for Running the Program

### Requirements
- **Java Development Kit (JDK)** 17 or higher
- Any Java IDE (e.g., IntelliJ IDEA, Eclipse) or terminal with Java installed

### Steps to Run
1. Clone or download the project repository from GitHub.
2. Open the project in your Java IDE or navigate to the folder via terminal.
3. Compile the program by running:
   ```
   javac FitnessClassBookingSystem.java
   ```
4. Run the program using:
   ```
   java FitnessClassBookingSystem
   ```
5. Follow the interactive prompts to explore the system's features.

---

## 🛠️ Project Development Timeline

## 🧠 Conceptualization 💡

The **FitLife** fitness class booking system was developed with the goal of providing a streamlined platform to help users manage their bookings for various fitness classes. The system enables users to:

- View available fitness classes.
- Book a class by entering their personal details.
- Cancel a booking when necessary.
- View the list of registered students for a class.

The system is designed to promote a healthier lifestyle by making it easier for people to engage in physical fitness activities through yoga, Zumba, cycling, and dance classes. The purpose is to offer a simple and user-friendly platform for managing bookings in a fitness-oriented environment.

### Requirements:

- **Java Development Kit (JDK) 17** or higher.
- An Integrated Development Environment (IDE) like **IntelliJ IDEA** or **Eclipse** or a terminal with Java installed.
- Basic understanding of object-oriented programming (OOP) concepts like inheritance, polymorphism, encapsulation, and abstraction.

---

## 📝 System Design ✍️

The system’s design follows Object-Oriented Programming (OOP) principles and structures the system with different classes and objects that interact with each other. Here's an overview:

### **Key Components:**

1. **FitnessClass** - Represents a general fitness class with attributes such as class name, instructor, and schedule. This class is inherited by different fitness class types (e.g., Yoga, Zumba, etc.).
2. **Student** - Contains information about a student, such as their name and student ID. The student can book or cancel their class registration.
3. **BookingSystem** - An abstract class that defines methods for booking, canceling, and viewing class details. Specific classes like **YogaBookingSystem**, **ZumbaBookingSystem**, etc., implement these methods for their respective fitness classes.
4. **Specific Fitness Classes** - Classes like **YogaClass**, **ZumbaClass**, **CyclingClass**, and **DanceClass** inherit from `FitnessClass`, adding specific details about each class type.

### UML Diagram:

For a better understanding of the relationships between classes, the system design can be visualized as follows:

- **FitnessClass** → **YogaClass**, **ZumbaClass**, **CyclingClass**, **DanceClass** (Inheritance)
- **BookingSystem** → **YogaBookingSystem**, **ZumbaBookingSystem**, **CyclingBookingSystem**, **DanceBookingSystem** (Inheritance)
- **Student** is associated with the `BookingSystem` through bookings.

A UML diagram can be drawn to represent the above structure, illustrating how different components interact and extend the base classes.

---

## 🛠️ Implementation 🛠️

The core functionality of the **FitLife** booking system is developed using Java. The implementation follows the principles of OOP for modularity and reusability:

- **Encapsulation** is used to ensure the data for classes like `Student` and `FitnessClass` is protected and accessed through getters and setters.
- **Inheritance** is leveraged to create specific fitness classes (like Yoga, Zumba) from a common base class.
- **Polymorphism** is applied by overriding methods like `bookClass`, `cancelClass`, and `showClassDetails` in specific booking system classes (e.g., `YogaBookingSystem`).
- **Abstraction** is implemented with an abstract class (`BookingSystem`) to define a blueprint for all booking systems.

The program allows users to interact with the system via a simple console interface, where they can:

1. View available fitness classes.
2. Book or cancel a class.
3. View registered students for each class.

---

## 🔍 Testing

Extensive testing was carried out to ensure that the **FitLife** system performs correctly. Tests were designed to cover:

1. **Booking and Cancellation**:
   - Verify that students cannot book the same class twice.
   - Ensure cancellations are processed correctly.
2. **Class Details**:
   - Confirm that correct class information (instructor and schedule) is displayed.
3. **Edge Cases**:
   - Invalid inputs (e.g., non-existent class numbers) are handled gracefully.
   - Ensure the program doesn’t crash when users input invalid data (like text when numbers are expected).
4. **Usability**:
   - The system provides clear prompts for the user and proper feedback after each action.

---

## 📋 Documentation

The documentation includes detailed comments within the code to explain the functionality of each method and class. The **README** provides an overview of the project, system design, usage instructions, and the project's development process.

### Key Highlights:
- A detailed description of classes and their methods is provided.
- Instructions for running the program on a local machine (with JDK and an IDE) are included.
- The system is designed to be easily expandable, supporting additional fitness classes and features.

---

---

## 📚 Class Overview

| **Class Name**           | **Attributes**                                          | **Methods**                                           | **Description**                                                                                   |
|--------------------------|---------------------------------------------------------|------------------------------------------------------|---------------------------------------------------------------------------------------------------|
| **FitnessClass (Base Class)** | `className`, `instructor`, `schedule`                   | `showClassDetails()`, Getters for class attributes    | Base class representing a generic fitness class with basic attributes and methods.                |
| **Student**               | `name`, `studentId`                                     | Getters for student details                           | Represents a student who can book a fitness class, with attributes for their name and ID.         |
| **BookingSystem (Abstract Class)** | `registeredStudents`, `fitnessClass`                        | `bookClass()`, `cancelClass()`, `showClassDetails()`, `showRegisteredStudents()` | Abstract class that defines methods for booking, canceling, and viewing class details and students. |
| **YogaClass**             | Inherits from `FitnessClass`                            | Overrides methods from `FitnessClass`                  | Represents a Yoga class with specific details for the yoga fitness class.                        |
| **ZumbaClass**            | Inherits from `FitnessClass`                            | Overrides methods from `FitnessClass`                  | Represents a Zumba class with specific details for the Zumba fitness class.                       |
| **CyclingClass**          | Inherits from `FitnessClass`                            | Overrides methods from `FitnessClass`                  | Represents a Cycling class with specific details for the cycling fitness class.                   |
| **DanceClass**            | Inherits from `FitnessClass`                            | Overrides methods from `FitnessClass`                  | Represents a Dance class with specific details for the dance fitness class.                       |
| **YogaBookingSystem**     | Inherits from `BookingSystem`                           | Overrides methods from `BookingSystem`                 | Manages bookings for Yoga classes with customized booking, canceling, and viewing methods.        |
| **ZumbaBookingSystem**    | Inherits from `BookingSystem`                           | Overrides methods from `BookingSystem`                 | Manages bookings for Zumba classes with customized booking, canceling, and viewing methods.       |
| **CyclingBookingSystem**  | Inherits from `BookingSystem`                           | Overrides methods from `BookingSystem`                 | Manages bookings for Cycling classes with customized booking, canceling, and viewing methods.     |
| **DanceBookingSystem**    | Inherits from `BookingSystem`                           | Overrides methods from `BookingSystem`                 | Manages bookings for Dance classes with customized booking, canceling, and viewing methods.       |

---

## 👨‍💻 Project Developer

- **Name**: [Janison Giane A. Bustos](https://github.com/jgianee)
- **Github**: [github.com/jgianee](https://github.com/jgianee)
- **Email**: 23-02686@g.bastate-u.edu.ph

---

**Thank you for exploring FitLife! Stay active and healthy! 💪✨**
