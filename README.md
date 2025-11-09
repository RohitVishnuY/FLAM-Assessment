# FLAM-Assessment
## Assignment: Parametric Curve Fitting

**Equations submitted:**
x = t*cos(…) - exp(…*abs(t))*sin(0.3*t)*sin(…) + …
y = 42 + t*sin(…) + exp(…*abs(t))*sin(0.3*t)*cos(…)

### Steps and Reasoning

1. Loaded tabular data (xy_data.csv) for 1500 points using pandas.
2. Since t values (6 < t < 60) were not given, mapped them linearly from 6 to 60.
3. Programmed the provided equations in Python.
4. Used scipy’s optimization to minimize total L1 error (sum of absolute differences) between predicted and measured (x, y) values.
5. Submitted the final equation in required format.
6. Visually confirmed fit with a scatter/line plot.

### Obtained Results

Optimal θ (radians): 0.49075933316719783
Optimal θ (degrees): 28.118438547135074
Optimal M: 0.021389025805115012
Optimal X: 54.89978442607421
