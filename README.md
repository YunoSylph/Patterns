# Patterns Implementation in Python (Google Colab)

## 1. Singleton Pattern

**Intent:** Ensure a class has only one instance and provide a global point of access to it.

**Key Idea:** Use a class-level attribute to store the single instance and control object creation via `__new__`.

**Use Cases:**
- Logging
- Database connections
- Configuration managers

## 2. Command Pattern

**Intent:** Encapsulate a request as an object, allowing parameterization of clients with different requests, queuing of requests, and logging/undo operations.

**Key Idea:** Separate the object that invokes the operation from the one that knows how to perform it.

**Use Cases:**
- GUI buttons
- Transaction systems
- Queued task execution

## 3. Adapter Pattern

**Intent:** Convert the interface of a class into another interface clients expect. Adapter lets classes work together that couldn’t otherwise due to incompatible interfaces.

**Key Idea:** Wrap the incompatible class in a new interface.

**Use Cases:**
- Legacy system integration
- Plug-and-play modules
- External API adapters

## 4. Facade Pattern

**Intent:** Provide a simplified and unified interface to a complex subsystem.

**Key Idea:** The facade delegates client requests to the appropriate subsystem components.

**Use Cases:**
- Simplifying complex APIs
- Layered architecture
- Entry point for libraries

## 5. State Pattern

**Intent:** Allow an object to alter its behavior when its internal state changes, appearing as if it changed its class.

**Key Idea:** Extract state-dependent behavior into separate state classes and switch between them dynamically.

**Use Cases:**
- Finite state machines
- UI controls
- Workflow engines
