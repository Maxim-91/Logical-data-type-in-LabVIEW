# Logical Data Type in LabVIEW

This project demonstrates the use of logical (Boolean) data types in LabVIEW, specifically using an event structure and conditional logic to control the program flow.

## Overview

The code consists of two event-handling examples for an "OK Button" that demonstrate different logical operations:

1. **Event Structure for Button Press Handling**  
   When the user presses the "OK Button", the event structure captures this action and triggers a response.

2. **Two Scenarios: True and False Conditions**  
   Depending on the Boolean state (`True` or `False`) of a specific condition, different actions are executed:

   - **True Condition:**
     - The program shows a `1` constant connected to an LED indicator, meaning that the `True` case results in activating the output LED.
   - **False Condition:**
     - The program generates a random number between `0` and `1` using the Random Number Generator (`RNG`). The output value is displayed on the front panel.

## How It Works

- The event structure listens for an event related to the "OK Button".
- Once the button is pressed:
  - If the Boolean condition is `True`, an LED indicator is activated.
  - If the Boolean condition is `False`, a random value is generated and displayed, illustrating the difference in behavior depending on the Boolean state.

This example shows how logical decision-making can be implemented in LabVIEW using Boolean controls and conditional structures.

## Usage

- Run the VI and interact with the "OK Button" on the front panel.
- Observe the changes to the LED indicator or the random value display, depending on the Boolean logic.

## Requirements

- LabVIEW software to open and run the VI.
