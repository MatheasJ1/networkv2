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
