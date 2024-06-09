---
{"dg-publish":true,"permalink":"/09-dn-d-wiki/session-summaries/session-overview/"}
---


[[09. DnD-Wiki/Homepage\|🏠 Back Home]]

>[!iinfo] Main Campaign Sessions 
>```dataview
 TABLE join(Date, ", ") AS Date, join(In-Game-Date, ", ") AS "In Game Date", join(link(whichparty), ", ") AS "Party", join(link(Current_Location), ", ") AS "Location"
 FROM #session-notes-summary and #maincampaignsummary
 
 SORT Session ASC

#TODO 
- [ ] someshot summaries
- [ ] rest of main campaign summaries