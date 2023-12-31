# Geometric Analyzer

Geometric Analyzer provides implementations of four different algorithms for finding the convex hull of a set of points in a 2D plane. The convex hull is the smallest convex polygon that encloses all the given points. The implemented algorithms include Jarvis March, Graham Scan, Quick Hull, and Brute Force approach.

## Features

- **Jarvis March Algorithm**: Finds the convex hull by iteratively selecting the point with the smallest polar angle relative to the current point.
  
- **Graham Scan Algorithm**: Sorts the points by polar angle and then constructs the convex hull by considering points in order.

- **Quick Hull Algorithm**: Divides the set of points into two subsets, constructs the convex hull for each subset, and then merges the results.

- **Brute Force Approach**: Evaluates all possible combinations of points to find the convex hull.

- **User Interface with Streamlit**: Utilizes Streamlit to create an interactive and user-friendly interface for inputting points and visualizing the convex hull.

- **Graphing Libraries for Visualization**: Incorporates graphing libraries to provide clear visual representations of the input points and the convex hulls generated by each algorithm.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/GeometricAnalyzer.git
   ```

2. Navigate to the project directory:

   ```bash
   cd GeometricAnalyzer
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

Run the Streamlit app:

```bash
streamlit run main.py
```

This will open a new tab in your default web browser with the GeometricAnalyzer interface.

Follow the on-screen instructions to input points and choose an algorithm. The visual representation of the convex hull will be displayed dynamically.

## Dependencies

- Python 3.x
- Streamlit
- Graphing libraries (e.g., Matplotlib, Plotly, etc.)


## License

This project is licensed under the MIT License - see the [LICENSE](GeometricAnalyzer\LICENSE) file for details.