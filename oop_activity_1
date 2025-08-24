# Parent class
class Device:
    def __init__(self, brand):
        self.brand = brand
    
    def power_on(self):
        print(f"{self.brand} device is now ON!")

# Child class
class Smartphone(Device):
    def __init__(self, brand, model, year):
        super().__init__(brand)
        self.model = model
        self.year = year

    def call(self, number):
        print(f"Calling {number} from {self.model}...")

    def display_info(self):
        print(f"{self.brand} {self.model} ({self.year})")

# Example usage
phone1 = Smartphone("Apple", "iPhone 15", 2024)
phone1.display_info()
phone1.call("123-456-7890")
phone1.power_on()


#activity_2 polymorphism
# Create a program that includes animals or vehicles with the same action (like move()). However, make each class define move() differently (for example, Car.move() prints "Driving" 🚗, while Plane.move() prints "Flying" ✈️).
class animals:
    def move(self):
        pass
class Dog(animals):
    def move(self):
        print("The dog runs on all fours.")
class Bird(animals):
    def move(self):
        print("The bird flies in the sky.")
class Fish(animals):
    def move(self):
        print("The fish swims in the water.")

class vehicles:
    def move(self):
        pass
class Car(vehicles):
    def move(self):
        print("The car drives on the road.")
class Plane(vehicles):
    def move(self):
        print("The plane flies in the sky.")
class Boat(vehicles):
    def move(self):
        print("The boat sails on the water.")


