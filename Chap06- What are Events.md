## What are Events
Events are a special kind of multicast delegate and they work the same as normal delegates.

However, as delegates can be called by other scripts, event delegates can only be called from within the scripts. This means that they can subscribe and unsubscribe to their own functions but they cannot trigger the events or change the subscription of other functions from other classes.

To use events you’ll need to define a delegate type and an instance, just like when setting up a normal delegate. But instead of the delegate keyword, you have to add the event keyword.

Like this-

```C#
public delegate void onDeath();
public static void onDeath onDeath;
```

Using these event delegates it is easy to manage complex relationships between different behaviours in the game.
However, it is sometimes difficult to declare a new delegate type every time you want to use one.
In order to prevent it, Actions come in handy.

**Benefits of using Events,**

1. Overriding subscribed functions
2. Public invoking
