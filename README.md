# ROAD-Sensor-array-optimization

# For Data Availability:

Data S1. (separate file)
The recipes and their scores during the DBTM process for CO2, NH3, and RH.

Data S2. (separate file)
The raw data of t-SNE.

Data S3. (separate file)
The average predictive accuracy at different array size. Ten parallel experiments were conducted at each size except the size of 288, which had only one combination.

Data S4. (separate file)
The detailed recipes for the Product Array, Array A, and Array B.

Data S5. (separate file)
The prediction accuracy of the Product Array, Array A, and Array B based on the calibration data. 


# For Code Availability

In our ROAD method, the code and data collection processes associated with the first two steps are closely linked to the robotic system. Isolating this portion of the code separately is not feasible without the robotic system. Therefore, we provide only the code for the third step, which includes a genetic algorithm for subarray screening and a backpropagation neural network for array readout.
