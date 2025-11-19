## Why can’t you instantiate the Enemy class?
 Because Enemy is declared as an abstract class and abstract classes can't have abstract methods.
## What would happen if a subclass did not implement update() or attack()?
The code would not run because any subclass of Enemy must implement all inhierited abstract methods.
## How does using Enemy[] demonstrate polymorphism?
I store all the objects inside one array called Enemy and when I call on the abstract methods java finds which methods is for whatever object.
## Why is it helpful for Enemy to have a concrete method like takeDamage()?
Because all enemies take damage and implementing this enemy makes it so we dont have to re-type it in every subclass. Each subclass now inhierits it.
## Could this design be implemented using interfaces alone? Why or why not?
Not really because interfaces can't hold shared variables like health/damage.
