My NumPy Data Explorer Project

I created this project during my internship at Syntecxhub to explore how NumPy can be used for real-world data analysis. It’s a tool that looks at employee productivity data and gives back useful insights like performance rankings, averages, and even salary calculations.

What this project does
I built this to handle a few specific tasks:

Reading the Data: It pulls productivity numbers from a file called company.txt. Each line in that file represents a different branch, and the script is flexible enough to handle branches with different numbers of employees.

Performance Analysis: The script automatically finds which company branch is performing the best and which one is struggling based on their total output.

Averages: It calculates the average number of products made by an employee in each branch, and then gives a total average for the whole organization.

Salary Tracking: Inside the operationclass.py file, I made a class called IntArray that handles the numbers for each branch. It calculates how much each person should be paid, using a rate of 7 per product.

Visualizing Progress: I also included a feature to plot the productivity of employees on a graph using Matplotlib, which makes it much easier to see the output of each worker visually.

Tools I Used
I used Python as the main language, with NumPy doing all the heavy lifting for the math and array management. For the visual side, I used Matplotlib to generate the charts.

Project Structure
main.py: This is the heart of the project where the files are read and the main analysis happens.

operationclass.py: This is where I defined the IntArray class to keep the code organized and handle specific branch logic.

company.txt: This is the raw data used for the analysis.

It was a great way for me to practice working with arrays and data visualization!
