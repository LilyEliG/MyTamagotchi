# MyTamagotchi

Welcome to the Tamagotchi Python Game project! In this project, you will create a virtual pet (Tamagotchi) using the principles of object-oriented programming in Python. The goal is to implement a Tamagotchi class and then use it to play an interactive game.


## Design Summary

The project involves creating a Python implementation of a Tamagotchi pet. The Tamagotchi has various needs such as feeding, bathing, and playing, and it progresses through different life stages. Neglecting the pet may lead to its demise.

## Task 1: Programming a Pet

For this part, you will implement the `Pet` class, controlling interactions with the Tamagotchi pet. The class includes member variables and functions for feeding, playing, bathing, aging up, checking status, and time stepping.

### Member Variables:
- `name`: Name of the pet.
- `fullness`: Integer between 1 and 10 indicating how well-fed the pet is.
- `happiness`: Integer between 1 and 10 indicating how happy the pet is.
- `cleanliness`: Integer between 1 and 10 indicating how clean the pet is.
- `alive`: Boolean value indicating if the pet is alive.
- `stage`: String giving the life stage of the pet (“egg”, “baby”, “child”, “adult”).
- `progress`: Integer between 1 and 20 tracking how close the pet is to progressing to the next stage.

### Member Functions:
- `__init__`: Constructor initializing pet attributes.
- `feed`, `play`, `bathe`: Functions to interact with the pet's needs.
- `age_up`: Function to change the pet's life stage and reset progress.
- `status`: Function to check and return the pet's status.
- `time_step`: Function to randomly decrease a pet's attribute and increase progress.

### Testing Suggestions:
- Test functions incrementally to avoid tracking down errors.
- Manually change member variables for thorough testing.

## Task 2: Playing the Game

Download the `Tamagotchi.py` file provided and run it. Use the `TamagotchiGame` class to interact with your `Pet` class. Ensure the Tamagotchi game runs smoothly in a turtle window.

```python
>>> game = TamagotchiGame('George')
>>> game.run()
```

If errors occur, revisit and check your `Pet` class implementation.

## Task 3: One Last Function

Implement the `play_tamagotchi` function to prompt the user for a pet name, create a TamagotchiGame instance, and run the game.

## How to Test

- Manually check member variable values before and after function calls.
- Thoroughly test functions, including edge cases.

## Final Notes

Ensure your `Pet` class is correctly implemented and works with the `TamagotchiGame` class. Good luck and enjoy creating your virtual pet!
