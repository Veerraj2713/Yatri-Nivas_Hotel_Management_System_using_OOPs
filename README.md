# 🏨 Yatri-Nivas Hotel Management System

A comprehensive **Object-Oriented Programming (OOP)** based Hotel Management System implemented in C++. This system provides complete functionality for managing hotel operations including room booking, restaurant services, customer management, and employee services.

## 🌟 Features

### 🏠 **Accommodation Services**
- **Room Management**: Support for different room types (AC, Non-AC, Deluxe)
- **Room Booking**: Easy room reservation with availability checking
- **Room Status Tracking**: Real-time room occupancy status
- **Check-in/Check-out**: Complete guest lifecycle management
- **Billing System**: Automated room rent calculation

### 🍽️ **Restaurant Services**
- **Menu Management**: Comprehensive dish catalog with pricing
- **Order Processing**: Streamlined food ordering system
- **Dish Categories**: Organized by types (Main Course, Starter, Dessert, etc.)
- **Bill Generation**: Automatic order billing

### 👥 **Customer Management**
- **Customer Registration**: Complete guest information capture
- **Customer Types**: Separate handling for accommodation and restaurant customers
- **Unique ID Generation**: Automatic customer ID assignment
- **Customer History**: Track customer interactions and preferences

### 👨‍💼 **Employee Services**
- **Room Service**: Dedicated room service staff
- **Restaurant Staff**: Waiter services for dining
- **Service Assignment**: Dynamic employee task allocation

### 📊 **System Features**
- **Exception Handling**: Robust error management
- **File I/O Operations**: Data persistence for customers, menu, and feedback
- **Feedback System**: Customer satisfaction tracking
- **Singleton Pattern**: Efficient hotel instance management

## 🏗️ **System Architecture**

### **Core Classes**

#### 🏨 **Hotel Class** (Singleton Pattern)
- Central management hub for all hotel operations
- Manages rooms, restaurant, employees, and customers
- Implements singleton pattern for single instance management

#### 👤 **Customer Hierarchy**
```
Customer (Base Class)
├── RoomCustomer (Inheritance)
└── RestaurantCustomer (Inheritance)
```

#### 🏠 **Room Management**
- **Room Class**: Manages room properties and status
- **Room Types**: AC, Non-AC, Deluxe with varying bed counts
- **Status Tracking**: Vacant/Occupied status management

#### 🍽️ **Restaurant System**
- **Dish Class**: Individual dish management
- **Restaurant Class**: Menu and order management
- **Dish Categories**: Organized food classification

#### 👨‍💼 **Employee System**
```
Employee (Abstract Base Class)
├── RoomService (Concrete Implementation)
└── Waiter (Concrete Implementation)
```

## 🚀 **Getting Started**

### **Prerequisites**
- C++ Compiler (GCC, Clang, or MSVC)
- Standard C++ Library support
- File system access for data persistence

### **Compilation**
```bash
# Compile the main program
g++ -o hotel_management main.cpp

# Run the program
./hotel_management
```

### **Alternative Compilation** (if using new.cpp)
```bash
# Compile the improved version
g++ -o hotel_management_new new.cpp

# Run the improved version
./hotel_management_new
```

## 📋 **Usage Guide**

### **Main Menu Options**
1. **Accommodation** - Room booking and management
2. **Restaurant** - Food ordering and dining services
3. **Exit** - Close the application

### **Accommodation Services**
- **Display Rooms**: View available room options
- **Book Room**: Reserve a room for stay
- **Vacate Room**: Check-out and room release
- **Get Invoice**: View billing details
- **Room Service**: Request additional services
- **Cancel Booking**: Cancel existing reservation
- **Give Feedback**: Submit service feedback

### **Restaurant Services**
- **Display Menu**: View available dishes
- **Order Dish**: Place food orders
- **Get Invoice**: View order billing
- **Cancel Order**: Cancel placed orders
- **Give Feedback**: Submit dining feedback

## 🗂️ **File Structure**

```
Yatri-Nivas_Hotel_Management_System_using_OOPs/
├── main.cpp                    # Main implementation file
├── new.cpp                     # Improved/alternative implementation
├── README.md                   # Project documentation
├── Description.txt             # Hotel description
├── Customer.txt                # Customer data storage
├── Menu.txt                    # Restaurant menu data
├── feedback.txt                # Customer feedback storage
├── main.exe                    # Compiled executable
├── new.exe                     # Compiled improved version
└── tempCodeRunnerFile.cpp      # Temporary code file
```

## 🎯 **OOP Concepts Implemented**

### **1. Inheritance**
- `Customer` as base class
- `RoomCustomer` and `RestaurantCustomer` as derived classes
- `Employee` as abstract base class with concrete implementations

### **2. Polymorphism**
- Virtual functions for customer operations
- Dynamic method dispatch for different customer types
- Abstract base class with pure virtual functions

### **3. Encapsulation**
- Private data members with public interfaces
- Data hiding through access specifiers
- Controlled access to class attributes

### **4. Abstraction**
- Abstract `Employee` class
- Interface-based design for employee services
- Simplified client interaction

### **5. Design Patterns**
- **Singleton Pattern**: Hotel class implementation
- **Factory Pattern**: Employee selection mechanism
- **Strategy Pattern**: Different customer behaviors

## 🔧 **Technical Features**

### **Exception Handling**
- Custom `Exception` class for error management
- Comprehensive error codes and messages
- Graceful error recovery

### **File Operations**
- Customer data persistence
- Menu data storage
- Feedback collection and storage
- Data backup and retrieval

### **Memory Management**
- Dynamic object creation
- Proper resource cleanup
- Vector-based data structures

## 📊 **Sample Data**

### **Available Rooms**
- **Deluxe Rooms**: 2-3 beds, ₹3,500-4,500
- **AC Rooms**: 1-2 beds, ₹3,500-5,500
- **Non-AC Rooms**: 2 beds, ₹2,500

### **Restaurant Menu**
- **Starters**: Mushroom Manchurian (₹170)
- **Main Course**: Shahi Paneer (₹220)
- **Desserts**: Chocolate Fondue (₹140)
- **Beverages**: Arizona Tea (₹100)
- **Cocktails**: Pina Colada (₹210)

## 🤝 **Contributing**

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 **License**

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 **Author**

**Veerraj2713**
- GitHub: [@Veerraj2713](https://github.com/Veerraj2713)

## 🙏 **Acknowledgments**

- Object-Oriented Programming principles implementation
- C++ Standard Library utilization
- File I/O operations for data persistence
- Exception handling for robust error management

---

**⭐ Star this repository if you found it helpful!**

*Built with ❤️ using C++ and Object-Oriented Programming principles*