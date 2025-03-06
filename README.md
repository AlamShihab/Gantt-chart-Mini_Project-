# gantt-chart
This Python script generates a Gantt chart using Matplotlib and Pandas to visualize project tasks and their timelines.

🚀 Overview
This mini-project is a Python-based tool that creates a Gantt chart to visualize project tasks and their respective timelines. Using Pandas for data manipulation and Matplotlib for plotting, the script transforms a predefined list of tasks into an interactive visual schedule.

🔧 Features
• Task Visualization: Displays tasks with start and end dates as horizontal bars.
• Interactive Date Formatting: Uses Matplotlib's date locators and formatters to neatly present dates.
• Easy Customization: Modify the task list and chart styling to fit your project needs.
• Minimal Setup: A single script that integrates essential libraries for quick deployment.

📁 Project Structure
• gantt_chart.py – Main script that defines tasks, processes dates, and generates the Gantt chart.
• README.md – This file, which provides an overview, usage instructions, and additional project details.

⚙️ Prerequisites
• Python 3.x
• Pandas (https://pandas.pydata.org/)
• Matplotlib (https://matplotlib.org/)

💾 Installation
Install the required libraries using pip:
pip install pandas matplotlib

🚀 How to Use

Clone the Repository:
git clone https://github.com/yourusername/gantt-chart-generator.git
cd gantt-chart-generator
Modify the Script (Optional):
Open gantt_chart.py to update the task list or adjust chart settings if needed.
Run the Script:
python gantt_chart.py
View the Chart:
The Gantt chart will display in a Matplotlib window, visualizing the project timeline.
🎨 Customization Tips
• Adding/Removing Tasks: Edit the tasks list in the script. Each task should include a "Task" name, a "Start" date, and an "End" date.
• Styling Adjustments: Change parameters like color, edgecolor, or figsize in the ax.barh() and plt.subplots() functions to customize the chart appearance.
• Date Format: Adjust the mdates.DateFormatter("%d-%m-%Y") parameter to change how dates are displayed.

🖼️ Example Output
When you run the script, the Gantt chart will look similar to this graphical representation:

![image](https://github.com/user-attachments/assets/a1844600-3f44-4be8-bf3f-3038ab83bb1b)


📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

👤 Author
Alam Shihab
https://github.com/AlamShihab/Gantt-chart-Mini_Project-/

🙏 Acknowledgements
• Pandas – For efficient data structures and tools for data manipulation.
• Matplotlib – For a flexible and easy-to-use plotting interface.
• The Python Community – For continuous support and innovative ideas.
