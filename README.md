# Object-Oriented Programming Demo

This project demonstrates basic **Object-Oriented Programming (OOP)** concepts in Python using two activities:

1. **Smartphone Class with Inheritance**
2. **Polymorphism Challenge with Vehicles**

---

## 1. Smartphone Class with Inheritance

* A base class `Device` defines a generic device with a brand and model.
* A child class `Smartphone` inherits from `Device` and adds:

  * `battery` attribute
  * `make_call()` method
  * `charge()` method
  * An overridden `show_info()` method (example of polymorphism).

**Example output:**

```
Smartphone: Samsung Galaxy S24 | Battery: 50%
Calling 0712345678...
Smartphone: Samsung Galaxy S24 | Battery: 45%
Phone fully charged!
Smartphone: Samsung Galaxy S24 | Battery: 100%
```

---

## 2. Polymorphism Challenge with Vehicles

* A base class `Vehicle` defines a general `move()` method.
* Three child classes (`Car`, `Plane`, `Boat`) each implement their own version of `move()`.

**Example output:**

```
Driving on the road...
Flying in the sky...
Sailing on water...
```

---

## Key Concepts Covered

* **Classes & Objects**: Modeling real-world entities.
* **Constructors (`__init__`)**: Initializing objects with unique values.
* **Inheritance**: Reusing and extending code from a parent class.
* **Encapsulation**: Keeping attributes and methods inside objects.
* **Polymorphism**: Different classes using the same method name but behaving differently.

---

## How to Run

1. Ensure you have **Python 3** installed.
2. Save the code in a file, e.g., `oop_demo.py`.
3. Open a terminal and run:

   ```bash
   python oop_demo.py
   ```
4. You will see demonstrations of both activities in the output.

