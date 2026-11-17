# Helpdesk Tickets Dashboard

I built this report in Power BI to look at helpdesk tickets, resolution times and satisfaction scores. I wanted to bring the main figures together and make it easier to compare departments and ticket priorities.

## What is in the report

- Cards for ticket count, average satisfaction score and average hours to resolve.
- A column chart showing tickets resolved within target by department.
- A priority chart showing each priority's share of the total tickets resolved within target.
- A pie chart breaking down the same resolution measure by ticket status.
- Slicers for agent, department and resolution priority.

The priority chart uses a percentage of the grand total. It shows how the resolved-within-target tickets are distributed across priorities; it is not the percentage of all tickets meeting the target within each priority.

## What I practised

I worked on arranging KPI cards, using a measure across different charts and adding slicers so the report can be explored from different angles. The report uses a measure named `tickets resolved within target` alongside the ticket, satisfaction and resolution-time fields.

## Open the report

Download [helpdesk_tickets_messy.pbix](helpdesk_tickets_messy.pbix) and open it in Power BI Desktop. Use the three slicers to explore the report.

The PBIX contains the saved report and data model. The original source files are not included, so refreshing the data may require updating the source connection in Power Query.

## About this project

This is part of my Power BI learning portfolio. I am developing my skills in reporting, measures and making dashboards easier to use.
