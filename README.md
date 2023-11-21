# Task Management System

This repository contains a Java-based Task Management System that demonstrates the implementation of several design patterns. Each design pattern plays a specific role in enhancing the functionality and flexibility of the task management system.

## Design Patterns Demonstrated

### Singleton Pattern
The `TaskOutputManager` class demonstrates the Singleton pattern, ensuring that there is only one instance of the `TaskOutputManager` throughout the system.

### Strategy Pattern
The `TaskManipulationStrategy` and `BasicTaskManipulationStrategy` classes showcase the Strategy pattern, allowing different strategies for manipulating tasks such as adding, editing, and deleting.

### Decorator Pattern
The `PriorityDecorator` class illustrates the Decorator pattern, enabling the dynamic addition of priority information to tasks.

### Adapter Pattern
The `TaskAdapter` and `TaskAdapterImpl` classes demonstrate the Adapter pattern, providing a way to perform task operations and handle challenges through a standardized interface.

### Observer Pattern
The `TaskObserver` and `TaskEditingObserver` classes showcase the Observer pattern, allowing observers to be notified when a task is edited.

### Factory Method Pattern
The `TaskFactory` and `SimpleTaskFactory` classes illustrate the Factory Method pattern, providing an interface for creating tasks with a concrete implementation.

## How to Use

1. Clone the repository to your local machine.
2. Compile and run the `TaskManagementSystem` class, which contains the `main` method.
3. Observe the console output to see the interactions based on the implemented design patterns.

Feel free to explore and modify the code to better understand the principles of each design pattern.

## Contributors

- Bakhtiyar & Sanzhar

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
