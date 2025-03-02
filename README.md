# weekly-assignments
import numpy as np
import matplotlib.pyplot as plt

# Adjusting parameters
mean = 10
variance = 4  # Standard deviation = sqrt(variance)
data = np.random.normal(mean, np.sqrt(variance), 1000)

# Plotting the adjusted distribution
plt.hist(data, bins=30, density=True)
plt.title(f"Normal Distribution (Mean={mean}, Variance={variance})")
plt.show()
