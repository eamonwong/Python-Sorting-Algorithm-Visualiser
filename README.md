# Python-Sorting-Algorithm-Visualizer
This project is a visualization tool for sorting algorithms, built using the pygame library in Python. It allows you to visualize both Bubble Sort and Insertion Sort, with options to reset the list, start sorting, and choose between ascending and descending orders.

## Features and Functionality
- Real-time Visualization: See the sorting algorithms in action.
- Two Sorting Algorithms: Bubble Sort and Insertion Sort are available.
- Custom Controls: You can reset the list, toggle between sorting algorithms, and switch between ascending/descending orders.

## Controls
- R: Reset the list to a new randomly generated set of numbers.
- SPACE: Start the sorting process.
- A: Set sorting to ascending order.
- D: Set sorting to descending order.
- I: Switch to Insertion Sort.
- B: Switch to Bubble Sort.

## Project Structure
# DrawInformation Class
This class handles the drawing of the sorting visualization. It manages the window size, list data, and UI elements.

# Functions
- draw: Handles rendering the UI and the list of numbers on the screen.
- draw_list: Draws the bars representing the numbers in the list, color-coded for clarity during sorting.
- generate_starting_list: Generates a random list of numbers for sorting.
- bubble_sort & insertion_sort: Implement the sorting logic with yield statements, allowing for step-by-step visualization.
main() Function
- The main loop of the application handles user input and updates the sorting visualization based on user actions.

## Future Enhancements
- Add more sorting algorithms (e.g., Merge Sort, Quick Sort).
- Provide an option to adjust the speed of the visualization.
- Allow the user to specify the list size or range dynamically.

Enjoy watching algorithms sort your data in real-time!






