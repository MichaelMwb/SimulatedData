# SimulatedData
📄 Dataset Description: Statistical_Model_of_Revision_vs_ExamScore.csv

📊 Overview

This dataset simulates the relationship between the amount of revision time spent studying and the resulting exam score. It is designed to model real-world educational scenarios using a controlled linear regression framework with added random noise.

🧪 Data Generation Process
The data was generated using the following statistical model:

𝑌 = 44.54 + 0.555𝑋 + 𝜀, where 𝜀∼𝑁(0,6.3542^2)

X: revision time in minutes (fixed across trials)

Y: exam score

ε: normally distributed random error simulating variability in test performance

The model reflects realistic assumptions commonly used in educational and behavioral research. It assumes a linear relationship between revision time and exam score, which is standard for studying marginal effects. The inclusion of normally distributed random error accounts for variability in performance due to unmeasured factors like test anxiety or prior knowledge. The coefficients were chosen to reflect plausible academic outcomes, and the model's structure allows for clear, reproducible analysis of statistical inference techniques.

Three independent trials were simulated using the same revision times but different randomly generated noise to model the effect of sampling variability.

Each trial contains 17 observations, totaling 51 observations across:

Trial 1

Trial 2

Trial 3

