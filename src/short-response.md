# Short Response

## Question 1

For each scenario, identify whether the relationship is **inheritance** or **composition**, and provide a brief explanation.

For example, a `Song` and a `MediaItem` have an inheritance relationship because "a song is a type of media item". Meanwhile a team and player have a composition relationship because "a team has many players".

1. A `Car` class and an `Engine` class, where a car contains an engine
2. A `Dog` class and an `Animal` class, where a dog is a type of animal
3. A `Classroom` class and a `Student` class, where a classroom contains multiple students
4. A `Rectangle` class and a `Shape` class, where a rectangle is a type of shape
5. A `Computer` class and a `CPU` class, where a computer contains a CPU
6. A `Manager` class and an `Employee` class, where a manager is a type of employee

### Response 1

1. A car and an engine have a composition relationship because a car can only have one engine.
2. A dog and an animal is an inheritance relationship because a dog is a type of animal
3. A classroom and a student is a composition relationship
4. A rectangle is a type of shape making it an inheritance relationship
5. A computer has a cpu making it a composition relationship
6. A manager is a type of employee making it an inhertiance relationship

---

## Question 2

In Problem 1, you are asked to implement a `Song`, `Podcast`, and `Audiobook` classes that all extend the `MediaItem` base class. Each class has their own `play()` method. This demonstrates **polymorphism**.

In your own words, explain what polymorphism means and why it is useful. Use the `MediaItem` example from this assignment to support your explanation.

### Response 2

Your response...
Polymorphism occurs when different classes share a method with the same name, but each class implements that method in its own way. For example, both a `Song` class and a `Podcast` class might have a `play()` method. In the `Song` class, `play()` could display the song title and artist currently playing. In the `Podcast` class, however, `play()` might show the podcast name along with the specific episode being played. Even though the method name is the same, the behavior differs depending on the object using it.

---

## Question 3

In JavaScript classes, properties and methods can be either **instance-level** or **static**.

a) What is the difference between an instance property and a static property?

b) Give an example of when you would want to use a static property or method instead of an instance property or method.

### Response 3

a) An instance property belongs to each individual object, so every instance can have different values. A static property belongs to the class itself and is shared by all instances.

b) You would use a static property when the data should be shared across all objects, like a list of all bank accounts in a system. Instance properties would store unique details, such as each account holder’s name or balance.
