# Emergency Response Geo-Locator 🚑

## Project Overview
This project is a Python prototype for an emergency dispatch system. It uses the **Haversine Formula** to calculate the Great Circle distance between a distress signal (victim) and a database of volunteers, identifying the nearest responders in milliseconds.

## Key Features
* **Haversine Algorithm:** Accurately calculates distances on a spherical Earth (not just straight lines).
* **Nearest Neighbor Search:** Filters and sorts responders by proximity.
* **Real-time Logic:** Simulates a dispatch system used in apps like Uber or 911 response tools.

## Technologies Used
* Python 
* Maths Module (Trigonometry)
* Jupyter Notebook

## How to Run
1. Clone the repository.
2. Open `emergency_locator.ipynb` in VS Code or Jupyter.
3. Run the cells to see the algorithm locate the nearest volunteer to the dummy "Incident" coordinates.