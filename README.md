
![466947487_491180520077650_8041545924581532199_n](https://github.com/user-attachments/assets/6f80a687-b111-4537-9350-6d6559573905)

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
This project incorporates key Object-Oriented Programming principles:

1. **Encapsulation**:
   - Classes like `FitnessClass`, `Student`, and `BookingSystem` encapsulate data and methods relevant to their functionality.
   - Access to class attributes is controlled using getters and setters.

2. **Inheritance**:
   - Specialized classes such as `YogaClass`, `ZumbaClass`, `CyclingClass`, and `DanceClass` inherit common attributes and methods from the `FitnessClass` class.

3. **Polymorphism**:
   - Methods like `bookClass`, `cancelClass`, `showClassDetails`, and `showRegisteredStudents` are overridden in specific `BookingSystem` subclasses to provide unique behavior for each fitness class type.

4. **Abstraction**:
   - The abstract class `BookingSystem` defines a blueprint for managing bookings, ensuring consistency across all subclasses.

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
1. **Conceptualization 💡**: 
   - Defined the project’s purpose and requirements.
2. **System Design ✍️**:
   - Created UML diagrams to structure classes and relationships.
3. **Implementation 🛠️**:
   - Developed core functionality using Java and applied OOP principles.
4. **Testing 🔍**:
   - Conducted rigorous testing for bugs, edge cases, and usability improvements.
5. **Documentation 📋**:
   - Added comments and prepared a detailed README.

---

## 📚 Class Overview

1. **FitnessClass (Base Class)**:
   - Attributes: `className`, `instructor`, `schedule`
   - Methods: `showClassDetails`, getters for class attributes

2. **Student**:
   - Attributes: `name`, `studentId`
   - Methods: Getters for student details

3. **BookingSystem (Abstract Class)**:
   - Attributes: `registeredStudents`, `fitnessClass`
   - Abstract Methods: `bookClass`, `cancelClass`, `showClassDetails`, `showRegisteredStudents`

4. **Specialized Classes**:
   - Subclasses of `FitnessClass`: `YogaClass`, `ZumbaClass`, `CyclingClass`, `DanceClass`
   - Subclasses of `BookingSystem`: `YogaBookingSystem`, `ZumbaBookingSystem`, `CyclingBookingSystem`, `DanceBookingSystem`

---

## 👨‍💻 Project Developer

- **Name**: [Janison Giane A. Bustos](https://github.com/jgianee)
- **Github**: [github.com/jgianee](https://github.com/jgianee)
- **Email**: 23-02686@g.bastate-u.edu.ph

---

**Thank you for exploring FitLife! Stay active and healthy! 💪✨**
