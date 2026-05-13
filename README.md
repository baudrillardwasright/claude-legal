# claude-legal
Collection of various legal skills for Claude.

#Courtlisener MCP
Courtlistener MCP allows Claude to query federal cases nationally using CourtListener's API. These skills require CourtListener MCP to be enabled in Connections. 

Note that CourtListener does _not_ have 100% coverage of all federal cases, nor does it have the text of all decisions, orders, motions, etc. To the extent that a filing is available in CourtListener via RECAP, these tools will pull the filings if necessary, or highlight what you can pull yourself from PACER. 

For more info on CourtListener's coverage and shortcomings, look here: https://www.courtlistener.com/help/coverage/recap/

Based on the skill, party, and use case, you may run into CourtListener's API limits - Claude will wait them out. 

##OC-Research
Uses CourtListener API to conduct research on an attorney to get a top-level view of what's on their docket, including recent filings and current scheduling orders. Conducts national docket search for your opposing counsel (includes name variants/nicknames, middle names, and middle/first initials). Renders a markdown file that summarizes federal court cases in which opposing counsel has appeared in the past 7 years, summarizes open cases, and renders a chronological timeline if possible that compiles scheduling orders entered in their filed cases. 

#TBD
##Courtlistener Party Search
##Courtlistener Judge and case type search

##Admit/deny graph for federal answers
##Discovery request generator
##Discovery objection generator 
##Discovery deficiency letter generator
##Guided legal research
