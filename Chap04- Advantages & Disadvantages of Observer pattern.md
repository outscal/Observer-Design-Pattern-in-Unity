## Advantages & Disadvantages of Observer pattern
Advantages are,
1. The code is more maintainable because it is less coupled between the observable classes and their dependencies (the observers).
2. Clean code. The Open-Closed Principle is guaranteed since the new observers (subscribers) can be introduced without breaking the existing code in the observable (and vice versa).
3. Cleaner code. The Single Responsibility Principle (SRP) is respected since the responsibility of each observer is transferred to its update method instead of having that business logic in the Observable object.

Disadvantages are,
1. Subscribers are notified in random order. 
2. There is also a memory leakage problem in the observer design pattern because of the observer's explicit register and unregistering
