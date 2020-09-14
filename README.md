# Bioluminescence-predicition
Small project in which I use logistic regression and support vector machine to predict if the analyzed sample comes from a fresh or frozen inoculum.

The data was collected by me by inoculating the 100mL Falcon with BOSS growth medium under sterile conditions.
Of the inoculated samples, 3 come from a culture of subcultivated bacteria in the laboratory, while the remaining 3 come from a frozen mother created directly by the supplier company.

The cultures, both fresh and frozen, were then left in incubator at 22°C for 24 and 48 hours respectively and then measured by a luminometer to assess their viability.

The aim of the experiment was to collect enough data to be able to assert which growth condition was the best to save costs and not to have to source from the manufacturer.
The luminescence was measured using an automatic sampling luminometer and the data collected in an Excel table.

In this project I clean the superfluous data using Pandas and visualizing the data with the seaborn library, finally I used logistic regression and SVM algorithms to obtain an automatic classification of the source state of the inoculum whether FRESH or FROZEN using the inoculum volume and the highlighted luminescence as independent variables.

Both algorithms behave well measuring a reliability with LR of 92% and SVM of 96%.

The bacteria are Allivibrio Fischeri, the purpose of the measurements was to compare the luminescence obtained after a certain number of hours for different µL of inoculum and by state of origin of the inoculum.



