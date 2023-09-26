# data_visualization_challenge
This is my data visualization challenge discussion sheet
This analysis consisted of 2 separate datasets, mouse_metadata and study_results which was combined to form one dataset named mouse_data_complete
The number of unique combinations of mouse ID and timrpoints were 1888 with 249 observations
The duplicate was identified as mice with ID number `g989`
Data cleaning was done by dropping duplicates and a new dataset named 'clean_mouse_df'was created

# Statistics Summary
The drug regimen tested was analyzed by computing the mean, median, variance, standard deviation, and standard error with respect to the tumor observation and  output was printed.
It was observe that "capomulin" and "Ramicane" seem to be more effective in treating tumor in the population with the least values with respect to the analysis made, with impressively lower SEM.
It was also observed that the least effective treatement drug was "ketapril" with the highest stats and highest SEM.
It is important to note that the lower the statistical numbers, the more reiable the data is and vice versa.

# Bar Charts and Pie charts
It was observe that "capomulin" and "Ramicane" had the highwst timepoints in observation than any other. The drug with the lowest observations was "Proviva"
The entire population of 249 mice consisted of 127 male mice representing 51% of the entire population with the females representing 49% i.e. 122.

# Quartiles, Outliers, Box plot
For the 4 drug regimetn analyzed for distribution, it was noticed that "Ceftamin", "Ramicane", and "Capomulin" was skewed to some degree. The only drug regiment with a normal distribution was "Infubinol".
The outlier was identified as mice with ID number "c326" with tumor volume of 36.12mm^3.

# Line plot and Scatter Plot
A line plot was created to analyze the tumor volume for mouse with ID "y793" using drug regimen Capomulin and it was observed that the tumor volume reduced drastically with over the time of the study.
The scatter plot visualization the relationship between weight and tumor size of mouse in the Capomulin drug Regimen suggested that some relationship existed.

# Correlation and Regression
A scatter plot was plotted and the correlation coefficient as well as the Regression equation was computed on the Capomulin drug Regimen considering the weight of mice anf the tumor volume or size:
- # Correlation Coefficient: 0.84. There is a strong positive correlation between mouse weight and average tumor volume implying its reliability is 84% with about 16% error or uncertainty.
- # Regression Equation: `Average Tumor Volume = 0.95 * Mouse Weight + 21.55`, which could be interpreted as all other things being equal, the average tumor volume of a mouse in the Capomulin drug Regimen is 95% of the mouse's orignal weight plus a constant of term of 21.55.
