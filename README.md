# Boolean Bagels

_People love or hate them!_



### Quickstart
1. Fork this repository
2. Clone your fork to your local machine (example command below, see note)
3. Install project dependencies

**NOTE: Replace `YOUR_GITHUB_USERNAME` with your github username if using the command below**
```sh
$ git clone git@github.com:YOUR_GITHUB_USERNAME/boolean-uk-tdd-todo-app.git && cd boolean-uk-tdd-todo-app
$ npm ci # to install dependencies
```

### Instructions
1. Follow a test-driven development process. Start with creating a domain model from the requirements, then write a test, and pass it by writing source code. Repeat until you've finished.

You should be able to run this in your JS console (using your node REPL, or browser console). For any assumptions made, represent this in your domain model.

# User Stories
## Part 1
```
As a member of the public
So I can order a bagel when I want to
I'd like to add an item to my basket

As a member of the public,
So that I can change my order
I'd like to remove an item from my basket
```

## Part 2
```
As a member of the public,
So that I can not overfill my small bagel basket
I'd like to know when my basket is full when I try adding an item beyond my basket capacity.

As a Boolean Bagels manager,
So that I can record more sales
I’d like to create baskets with larger capacity when I need to.

As a member of the public
So that I can maintain my sanity
I'd like to know if I try to remove an item that doesn't exist in my basket. In the same way, I want to know if I try to add an item with the same ID already in my basket.
```

## Part 3
```
As a member of the public,
So that I can know how much my bagels are,
I’d like to see the price of each item before I add it to my basket.

As a member of the public,
So that I can prepare to pay
When I go to checkout I'd like to know the total sum of the bagels in my basket
```
