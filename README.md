# Bike-Sale-Dashboard
Creating a dashboard in Ms Excel sheet using Pivot Table. 
Dashboard Readme: Bike Sales

1. Overview and Purpose

This document provides a guide to navigating, interacting with, and maintaining the Bike Sales Excel file.

This dashboard is built on a single Pivot Table and utilizes Slicers and Timeline controls to provide dynamic, real-time insights based on the raw data provided in the Data sheet.

2. File Structure

This workbook contains three primary sheets:

Sheet Name

Description

Key Action

Dashboard

The main visual view. This is the only sheet intended for user interaction and analysis.

Use the Slicers to filter data.

Pivot

Contains the core Pivot Table(s) used to calculate the dashboard metrics.

DO NOT edit this sheet unless adjusting calculated fields.

Data

Contains the raw data used as the source for the Pivot Table.

Paste new data here for updating the dashboard.

3. How to Use the Dashboard

The dashboard is designed for interactive filtering. Do not manually filter the charts or the underlying Pivot Tables.

A. Filtering with Slicers

Slicers are the primary control for filtering data.

Click to Filter: Click on a single item within any Slicer (e.g., a specific Region, Product, or Sales Rep) to filter all visible charts and metrics instantly.

Multi-Select: To select multiple items, hold the Ctrl key while clicking on the desired items.

Clear Filter: Click the "Clear Filter" funnel icon (top-right of the Slicer) to remove all selections and view the entire data set.

B. Filtering by Date (Timeline)

The Timeline control is used to filter all data based on a time period (usually a date column).

Select Period: Use the drop-down menu in the top-right of the Timeline to select the view level (Years, Quarters, Months, or Days).

Drag Selection: Click and drag the selection bar at the bottom of the control to highlight the desired period (e.g., Q1 2024).

4. How to Refresh the Data

The dashboard is dynamic but does not automatically pull new data from external sources. To include new data in your analysis:

Update the Source: Paste the new set of raw data into the Data sheet, ensuring all column headers and data formats remain consistent with the original structure.

Refresh All: Navigate to the Dashboard sheet.

Click the Data tab in the Excel ribbon.

Click Refresh All.

Note: If you add data that extends beyond the Pivot Table's original source range, you may need to update the source range manually in the Pivot sheet settings before refreshing.

5. Troubleshooting and Contact

Problem

Potential Solution

Dashboard looks blank

Check the Slicers. A filter may be applied that excludes all data. Clear all filters.

Data in the dashboard is old

You forgot to perform the Refresh All step after updating the Data sheet.

#REF! or #VALUE! errors

The underlying data structure was likely changed, or a key calculated field was modified in the Pivot sheet.
