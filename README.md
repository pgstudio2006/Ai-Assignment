# Ai-Assignment
## README for Salary vs CGPA Plot

### Introduction
This project shows how to plot a graph using Python's `matplotlib` library to visualize the relationship between salary and CGPA.

### Prerequisites
- Python installed
- `matplotlib` library installed (`pip install matplotlib`)

### Code
```python
import matplotlib.pyplot as plt

# Data
salary = [40000, 45000, 48500, 42500]
cgpa = [8, 8.5, 9, 7]

# Plot
plt.plot(salary, cgpa)
plt.title("Salary vs CGPA")
plt.xlabel("Salary")
plt.ylabel("CGPA")
plt.show()
```

### Explanation
1. **Import Library**: `matplotlib.pyplot` is imported as `plt`.
2. **Prepare Data**: Two lists, `salary` and `cgpa`, hold the data.
3. **Plot Graph**: `plt.plot(salary, cgpa)` creates the graph.
4. **Labels**: `plt.title`, `plt.xlabel`, and `plt.ylabel` add titles and labels.
5. **Show Graph**: `plt.show()` displays the graph.
