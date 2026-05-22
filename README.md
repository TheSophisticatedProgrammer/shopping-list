# CLI Shopping List

A terminal-based Python tool to build, manage, and check off active shopping list entries.

## Features

- **Order-Preserving List**: Stores shopping entries sequentially in the exact order they are input.
- **Error-Insulated Removal**: Catches missing item exceptions gracefully without breaking the system loop.
- **Dynamic Content Checks**: Prints clear empty-state messaging when no active items exist in the ledger.

## Prerequisites

- Python 3.x

## How to Run

1. Save the code to a file named `main.py`.
2. Open your system terminal.
3. Run the application:
   ```bash
   python main.py
   ```

## Usage Guide

Type one of the explicit menu commands at the terminal prompt:

* **add**: Input a description or name of an item to append to the end of the list.
* **remove**: Target and strip a specific entry by typing its exact name.
* **view**: Output an aligned list of all items currently stored.
* **quit**: End the system run loop and close the script.

## Technical Details

- **Array Modification Patterns**: Exercises `.append()` and `.remove()` array behaviors directly.
- **Action Matrix Structure**: Routes execution flows cleanly through a text-keyed function pointer map.
