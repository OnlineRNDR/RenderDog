
![logo](https://github.com/user-attachments/assets/86167d0a-3c5b-4aed-afba-d1049a1553c4)



If you find this project useful, consider supporting it by donating some Render tokens or Sol!

If donating isn’t your thing, feel free to contribute by helping maintain or improve the project. Right now, we only use one external source for Chart.js, and there’s plenty of room for adding more functionality.

That said, the goal has always been to keep things simple and streamlined, without relying on external APIs or data. Any help—whether it's donations, feedback, or code contributions—is greatly appreciated!

SOL Account: 9ZbhsKHn9Xx6ShP3bRozzVmLHrMox9Uw5p8LioVakeAP


# RenderDog - Log File Toolkit
![Untitled-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/9f7f47a8-f49c-48ce-8e4d-613a83f31c33)



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
Render-Dog Log Viewer:

Load Rndr Log
Upload your rndr_log.txt file to begin parsing and analyzing your Render Network log data. This step initializes the tool and prepares the logs for processing based on the selected date range.

Save Results:

Save all parsed and displayed results for the selected date range as a single .txt file. This file contains the summarized stats and log details within the chosen calendar period, providing a convenient way to archive data.

Export Report:

 A comprehensive day-by-day report for the selected date range into a file named Report_Dog.txt. This file can be used with the reports.html page to visualize and analyze individual daily logs in more detail.

Export Weekly:

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

# Calendar Navigation
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



# Debug Console
Here you can view and generate custom messages, errors, and logs generated during script execution to help diagnose issues or confirm successful operations.

![image](https://github.com/user-attachments/assets/88b15fba-047a-413e-9889-5a066412b59b)


# Render Log Toolbox
Quick Access Shortcuts:

Reports - Dive deeper with the reports page

Log Split - Split the log into smaller chunks or into weeks, without parsing any text.

Wizard - Read the log file for quick observation 

Weekly Tools - Navigate Weekly Reports and Stats  
 ![image](https://github.com/user-attachments/assets/9e4603d5-fa23-4555-bec2-f5ae58ed4b44)



# Addtional Tools 
Frame Cost Calculator: helps give you an idea of how much you earn per frame / epoch 

Time Convert
Convert's time, perfect for quick calculations 

Avialibity: Wip, a simple tool to work out your availability *subject to change 
![tools_showcase](https://github.com/user-attachments/assets/b4059dc6-e332-4aa6-bf00-4c0a72c809e0)

# Reports Breakdown
![image](https://github.com/user-attachments/assets/3f52c259-5f1a-41aa-9c46-c306872ce322)

Provides a comprehensive daily breakdown of your renders, offering detailed insights and analytics.
Easily export this report using the Export Report button available on the main page for convenient sharing and record-keeping!

# Log Split

Log Splitter Tool
Perfect for breaking large log files into smaller, manageable chunks.

Splits logs around 15,000 lines, ensuring separation at RNDR client restarts on the last known day, so no data is lost.
Includes an option to split logs by specific days of the week, offering tailored control over your log management!
![image](https://github.com/user-attachments/assets/cb8f41c0-ae04-411b-b9a5-5ede91c2eca9)

# The Wizard 
Upload Log File: To load your log file into the tool.
Filter Log File: To apply filters and process the file.
A dropdown menu labeled "Select a common phrase" that allows users to choose predefined log phrases, such as errors, warnings, or rendering events, to filter specific log entries quickly.
Ability to manually enter your search field 
A console output section at the bottom displaying messages, instructions, or the filtered log results.

![image](https://github.com/user-attachments/assets/c0c573e9-1b23-48ca-9438-a2f92073ebdd)

# Weekly Reports
![image](https://github.com/user-attachments/assets/fa7acd36-d5a0-43c3-a429-70a1ff9a0164)

Weekly Export Tool Features

Multi-File Selection: Seamlessly select multiple files exported using the Weekly Export button from the main page.
Quick Navigation: Easily navigate through the files using left and right controls for efficient review.
Combine and Export: Merge all selected reports into a single, comprehensive text file for streamlined analysis and sharing.

Key Metrics Panels:

Date Range: Displays the start and end dates of the analyzed period, total days and hours, and the number of "down days."
Render Statistics: Highlights successful and failed renders, along with success and failure rates.
Time and Efficiency: Provides total rendering time, average daily render time, and percentages for render and idle times.
Notable Days: Identifies days with the most successful frames, longest rendered frame, and most failed frames.
Summary Table:

A tabular breakdown of successful and failed frames per day for clear, day-by-day performance tracking.
This tool provides an organized and


# Extra 
Added a couple of goodies to kill the boredom when watching the render client. 


# Notes from Author 

Please take into consideration I am an artist, not a coder "JIM". 
This was half written by Chat GPT , the messy parts was written by me and 100% not perfect. 
I have a better understanding of the code and my intention is to remake. 
Any bugs or questions please contact me on the Node Opps Slack Channel.

Cheers OnlineRNDR 





