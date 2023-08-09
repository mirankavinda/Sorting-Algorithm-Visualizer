# Sorting Algorithm Visualizer

This Python script uses the pygame library to create a visualizer for sorting algorithms. It allows you to see how different sorting algorithms work by animating the sorting process and displaying the changes in real-time.

## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.2 or above
- pygame library (`pip install pygame`)

## Getting Started

1. Clone or download this repository to your local machine.

2. Open a terminal or command prompt and navigate to the directory containing the downloaded files.

3. Run the following command to start the sorting algorithm visualizer:


## Usage

Once the visualizer is running, you can interact with it using keyboard controls:

- `R`: Reset the list with a new set of random values.
- `SPACE`: Start the sorting animation.
- `A`: Choose ascending order for sorting.
- `D`: Choose descending order for sorting.
- `I`: Select Insertion Sort algorithm.
- `B`: Select Bubble Sort algorithm.
-  Close the window: Exit the visualizer.

## How It Works

The visualizer uses the pygame library to create a window that displays a bar graph representing the list of values to be sorted. Different sorting algorithms can be selected, and you can control the sorting direction (ascending or descending).

The supported sorting algorithms are:

- Bubble Sort
- Insertion Sort (partial implementation)
- (Other sorting algorithms can be added in the future)

The sorting process is animated by updating the display at each step of the sorting algorithm. Swapped elements are highlighted in different colors to make the process more visually understandable.

## Customization

You can modify the following parameters in the `sorting_visualizer.py` script to customize the visualizer:

- `n`: Number of elements in the list.
- `min_val`: Minimum value of elements.
- `max_val`: Maximum value of elements.

Feel free to experiment with these parameters to observe how different algorithms behave with varying input sizes and value ranges.

## Contributing

Contributions are welcome! If you have ideas for improvements or additional sorting algorithms, feel free to fork this repository, make your changes, and create a pull request.
