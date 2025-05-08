# oop-assignment

class Superhero:
    def __init__(self, name, power, health):
        self.name = name
        self.power = power
        self.health = health

        def use_power(self):
            print(f"{self.name} is using {self.power!}")

            def take_damage(self, damage):
                self.health -= damage
                print(f"{self.name} took {damage} damage.Remaining health: {self.health}")

                def _str_(self):
                    return f"{self.name} - Power: {self.power} , Health: {self.health}"
                
                class FlyingSuperhero(Superhero):
                    def __init__(self, name, power, health):
                        super().__init__(self, name, power, health, flight_speed):
                        super().__init__(name, power, health)
                        self.flight_speed = flight_speed

                        def fly(self):
                            print(f"{self.name} is also using thier flight ability to enhance their power!")

                            # Create instances
                            iron_man = FlyingSuperhero("Iron Man", "Repulsor", 100, 500)

                            # Use methods
                            print(iron_man)
                            iron_man.use_power()
                            iron_man.fly
                            iron_man.take_damage(20)

                            print(captain_america)
                            captain_america.use_power()
                            captain_america.take_damage(10)


                            class Animal:
                                def __init__(self, name):
                                    self.name = name

                                    def move(self):
                                        pass

                                    class Dog(Animal):
                                        def move(self):
                                            print(f"{self.name} the dog is running!")

                                            class Fish(Animal):
                                                def move(self):
                                                    print(f"{self.name} the dog is swimming!")

                                                    class Bird(Animal):
                                                        def move(self):
                                                            print(f"{self.name} the dog is flying!")

                                                            # Create instances
                                                            dog = Dog("Buddy")
                                                            fish = Fish("Goldie")
                                                            bird = Bird("Tweety")

                                                            # Use polymorphism
                                                            animals = [dog, fish, bird]
                                                            for animal in animals:
                                                                animal.move()


                                            
                                            
