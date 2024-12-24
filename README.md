# RenderDog - Log File Toolkit
Render Network Log Reader 
![Screenshot 2024-12-24 003602](https://github.com/user-attachments/assets/0b5f0a9c-cd49-4369-8a19-633548fd1d1a)

Render-Dog is a specialized tool designed to parse, analyze, and summarize log files from the Render Network, enabling users to track and troubleshoot rendering activity effectively. Key features include:

Quick Stats Overview:

Displays essential metrics like total frames rendered, failed renders, success rates, and render vs. idle times.
Offers percentages and highlights key statistics for efficient performance assessment.
Interactive Date Range Selection:

Users can define a start and end date to filter log data for specific periods.
Total days in the selected range are calculated and displayed.
Log Parsing and Summaries:

Extracts detailed insights, including render engine usage, job statuses, errors, and warnings.
Highlights key events like job cancellations, beta releases, and system warnings.
Visualization Tools:

Graphs such as "Render Time vs. Idle Time" and "Render Over Time" provide visual representations of activity, making it easier to identify trends and bottlenecks.
Debug Console:

Displays real-time updates on log processing and system status.
Logs file uploads, system readiness, and debug messages to help with troubleshooting.
Report Generation:

Options to save results, export reports, or generate weekly summaries for deeper analysis.
Frame Cost Calculator:

Enables users to input token data to estimate rendering costs on the Render Network.
Render-Dog provides an all-in-one solution for professionals using the Render Network, combining detailed log insights, visual analytics, and cost estimation to optimize workflows and improve rendering efficiency.

 
![image](https://github.com/user-attachments/assets/34f666fc-cac6-4047-991d-d3fec4cd46f0)

# Interface
Render-Dog Log Viewer: Features
Load Rndr Log
Upload your rndr_log.txt file to begin parsing and analyzing your Render Network log data. This step initializes the tool and prepares the logs for processing based on the selected date range.

Save Results
Save all parsed and displayed results for the selected date range as a single .txt file. This file contains the summarized stats and log details within the chosen calendar period, providing a convenient way to archive data.

Export Report
Export a comprehensive day-by-day report for the selected date range into a file named Report_Dog.txt. This file can be used with the reports.html page to visualize and analyze individual daily logs in more detail.

Export Weekly
Generate weekly summaries based on the first selected date in the calendar (e.g., Wednesday to Wednesday). Each week’s data will be exported into a separate .txt file, making it ideal for recurring reporting workflows. These files are compatible with the weekly.html page for a deeper breakdown of weekly performance.

Example Workflow
Upload your log file using Load Rndr Log.
Select a date range using the calendar.
Save Results to archive the summarized data for the selected range.
Generate a detailed day-by-day report using Export Report.
Alternatively, create weekly summaries with Export Weekly for broader analysis.
Compatibility
Reports generated with Export Report can be directly loaded into reports.html for visualization.
Weekly summaries from Export Weekly are compatible with weekly.html for weekly breakdowns.

![image](https://github.com/user-attachments/assets/24a7921a-39f4-412f-9394-de1e668aa562)

Calendar Navigation
The Calendar Navigation section allows you to customize and navigate through your log data based on specific date ranges. Below are the key features:

Start and End Date
Select a start and end date to filter and view the log data within the chosen range.
This feature enables precise control over the period you want to analyze.

Navigation Buttons
Left Arrow & Right Arrow
Move the start date forward or backward by one day, allowing easy day-to-day navigation within the calendar range.

Save Icon
Save the currently selected date range for future reference.

Refresh Icon
Recall the previously saved dates using the Save Icon, restoring the date range selection.

Orange Icon
Sync the navigation to the start date of the selected range.
Once synced, you can navigate day-by-day starting from the first date.

Blue Icon
Sync the navigation to the end date of the selected range.
Once synced, you can navigate day-by-day backward starting from the last date.
Example Use Case

 
