## Advantages and Disadvantages

### 1) **Delegates -**

- **Advantages -**
    - Delegates allow functions to be passed as parameters.
    - Delegates are dynamic and flexible to use, as we can attach and detach delegate instances at run time.
    - Delegates can invoke more than one function using the Multicast feature.
- **Disadvantages -**
    - As delegates are public, other scripts can access the delegate, it is possible for any other script to call it or even clear the assigned functions from the delegate.

### 2) Events -

- **Advantages -**
    - Events help to add an extra layer of protection to the Delegates.
    - Event Delegates cannot be called from other scripts, can be called from within the script itself.
    - Easy to manage complex relationships.
- **Disadvantages -**
    - Sometimes, it is difficult to make a new event delegate every time, you want to use one.

### 3) Actions -

- **Advantages -**
    - We can create delegates and event delegates easily using actions.
- **Disadvantages -**
    - Actions must have a void return type


>💡 🚀 **[Join Discord Server](https://discord.gg/J5zDscnzms) → Get your doubts solved by experts instantly**
