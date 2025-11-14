4. the link from message post to post gets taken off since the lass doesn't exend that one anymore.
5. Yes you can call the inherited methods but they are now in like a folder of the class they've been inherited from to not get it mixed up.
7. Fields get assigned variables since the comment is being created and we can see this step by step through the debugger.
9. Food item
--- Fruit
      ----- Apple
      ----- Orange
--- Bread 
      ---------- Baguette
Dessert
--- Ice cream
--- Chocolate mousse
---cereal

10. they're both hardware for a computer. they're both toold that help computer navigation 
11. a square can not inherit a rectangle as both do not share the same properties. lets say at one point in the code a sqaure inherits a
 rectangles values for width and height well that would make the program not relevant anymore since
you do not hav a square anymore but two rectangles.

11. a) 
    1 is good
    2 is good
    5 is good
    b) 3 and 5 is good

14. we have to make it inherit the post class so it is linked to it.

15.           Collection
    
       List       Set      Queue

   ArrayList   HashSet   PriorityQueue
   LinkedList  TreeSet   ArrayDeque


                 Map

              HashMap
              TreeMap
              
17. 

                        ComputerComponent

    
 Processor         Storage         Peripheral     InputDevice

     Memory       DiskDrive Printer  Scanner Keyboard     Mouse

        HDD            DVDDrive

18.     M
       / \
      X   T
        |  
        O
19. java.lang.Object
       │
java.util.AbstractCollection
       │
java.util.AbstractList
       │
       ├───────────────────────────────┐
       │                               │
 java.util.ArrayList            java.util.AbstractSequentialList
                                         │
                                         ├───────────────┐
                                         │               │
                               java.util.LinkedList   java.util.Vector
                                                         │
                                                  java.util.Stack
PART 2 : (Using same file)

1. well it will never compile because the fields that are being assigned in the method come from the post class and 
are private so they are not able to be called in other classes for security reasons.

2. the messagepost class display method is my prediction. 
the display() methods of messagePost and photoPost.

3. yes everything works as expected and there isn't any problems with what the method does.

4. it takes no parameters and is return type is of type string.

9. directly defines 5, inherits 69.
 
10. yes because some can violate some inheritance rules. like arraylist 

11. each room has a value, we use a randomizer to randomize in the range of the room numbers, 
of course the transporter class extends room and when you enter that room the statemnt triggrs and it randomizes 
and sends you to that room depending on where it landed for the user. 

12. we make a character class that extends both payer and montser and assign their respective values and fileds.

13. no it should not. 
14. Device and printer. 
15. Device 
16. yes it will compile and it will just call the objet.toString method which turns it into a string anyways. 
17. this will not work and st is a field and not a string value.
18. yes it does compile and it will print the names of the studens in the list mylist. what happens is for every st of type object in the myList list its gonna print a line with every st in the list.
19.1.class T 
2.class D extends T 
main. T x = new D(); 
    


