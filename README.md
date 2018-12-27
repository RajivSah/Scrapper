# Scrapper
Compilation of Competitor Analysis - Step by Step

Sample of completed version: https://docs.google.com/spreadsheets/d/1VPWAfLfBje4C6Pu6ntE28SOGPKhgvr4yai8NvdHKVMQ/edit?usp=sharing 

Step 1: Bulk Export from Apptweak
    • Navigate to relevant app from Dashboard: https://app.apptweak.com/ 
    • Select “Export full report to XLS” and set date range to “past year”

    • Download export from “Exports” tab:
https://app.apptweak.com/dashboard/dashboard/exports 
    • Import the exported xls document into relevant Client folder in Google Drive
    • Name the file “clientnameabbreviation_competitor_anaylsis” eg for Racing Post: rp_competitor_analysis
    • Amend all tabs to begin with the prefix “clientnameabbreviation_” eg rp_keywords 
    • Delete Legacy data - these tabs have (Legacy) in the name

Step 2: Add in additional data excluded from export - in Apptweak
    • Keyword Density Data:
2.1 Description Analysis
    • Navigate to Keyword Density on left navigation panel with App dashboard
    • Leave on default of “Description Analysis” and “1 word”
    • Change to display 100 rows

    • Copy and paste table data into a new tab in Google Sheet, tab to be named “prefix_desc_kw_density_1” eg rp_desc_kw_density_1
    • In sheet, name columns according to app names instead of icons
    • All blank cells to be populated with “0” 
    • Entire table to be formatted to percentages
    • Within Description Analysis, repeat same steps for “2 words” and “3 words” (tab names updated to end _2 and _3 respectively)
    • Be sure to create new tab for each

	2.2 App Name Analysis
    • Repeat all steps in 2.1, with tabs labelled “prefix_app_name_kw_density_1”
    • App name analysis to be done for 2 and 3 words too

    • Note - for these tabs, tables to be formatted to numeric values not percentages as in 2.1
    • Be sure to create new tab for each
	2.3 Subtitle Analysis
    • Repeat all steps in 2.1, with tabs labelled “prefix_subtitle_kw_density_1”
    • Subtitle Analysis to be done for 2 and 3 words too
    • Tables to be formatted to numeric values not percentages
    • Be sure to create new tab for each

    • Promotional text:
    • Navigate to Promotional text on left hand side panel on app dashboard
    • Copy and paste table into a new tab in master sheet
    • Format first column to reflect app names (not icons)
    • Format count column to only numeric values
    • Name tab “prefix_promo_text” 


    • Subtitle text:
    • Navigate to Subtitle on left hand side panel on app dashboard
    • Copy and paste table into a new tab in master sheet
    • Format first column to reflect app names (not icons)
    • Format count column to only numeric values
    • Name tab “prefix_subtitle_length” 

    • Description Word Count
    • Navigate to App Description on the left hand side panel on the app dashboard
    • Create new tab in sheet named “prefix_desc_word_count”
    • Data manually entered - column for app name plus column for description count
    • Count can be seen by clicking on the icons of each app (see below)
    • Alternatively counts can be found in the Descriptions tab from the master export


    • Rating & Review Count
    • Navigate to Reviews & Ratings tab on the to section app dashboard

    • Create new tab in sheet named “prefix_rating_review_count”
    • Data manually entered - column for app name plus column for average rating plus column for review count
    • Figures can be seen by clicking on the icons of each app (see below)



Step 3: Competitor Ranking - in Apptweak
    • Navigate to Keywords tab in the top menu of the app dashboard

    • Select “Competition Analysis” and export to XLS

    • Retrieve the export from Exports tab (as in step one) 
    • Import XLS into new tab in the master Google Sheet
    • Rename tab “prefix_comp_ranking”

Step 4: App Link Profile
    • This data is retrieved from www.majestic.com 
    • Using their bulk backlink checker (https://majestic.com/reports/bulk-backlink-checker) gather the link profile of the apps that are being tracking. 
    • To get the URL type the exact name of the app + ios into Google. 
    • Paste each url into majestic 
    • Run the report and download the data. 
    • Copy and paste the export into a new tab called 'prefix_links'.

