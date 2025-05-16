# Heading
Python Program to Pack Two Different Objects into a Tuple and Iterate Through It Using a Car Variable

# Aim
To create two classes, `Ferrari` and `BMW`, each having the same instance methods. Then, pack objects of both classes into a tuple and iterate through it using a variable `car`.

# Procedure
1. Define the `Ferrari` class with the methods `fuel_type()` and `max_speed()`.
2. Define the `BMW` class with the same methods `fuel_type()` and `max_speed()`.
3. Create objects of both classes.
4. Pack the two objects into a tuple.
5. Iterate over the tuple using a variable `car` and call the methods `fuel_type()` and `max_speed()` for each object.
# Program
```python
class Ferrari:
    def fuel_type(self):
        print("Petrol")

    def max_speed(self):
        print("Max speed 350")

class BMW:
    def fuel_type(self):
        print("Diesel")

    def max_speed(self):
        print("Max speed is 240")

ferrari = Ferrari()
bmw = BMW()

# iterate objects of same type
for car in (ferrari, bmw):
    car.fuel_type()
    car.max_speed()
    
```

# Output

![image](https://github.com/user-attachments/assets/d1046f04-07c4-48fd-af62-ebbfb7f5cbbf)

# Result
The program successfully demonstrates how to store different class objects in a tuple and iterate through them, calling the same methods on both objects.

