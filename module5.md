# Basic Searching

* Splunk Bar
* App Bar
* Search Bar
* Time Picker
* How to Search Panel
* What to Search
* Search History

Limiting searches by time is key. Becomes a job. **Commands that creat statistics and visualizations are called "transforming commands"**. By default, a search job will remain active for 10 minutes. Shared search jobs remain active for 7 days. Field discovery is disabled in Fast mode. Verbose mode returns as much as it can. Smart toggles behavior. Timeline shows events over time. Selecting or zooming uses the same search job. Zooming out requires a new search job. 

If no bools used in search, AND is implied. Boolean ops have an order of evaluation: NOT, then OR, then AND. Exact terms searched with "". can use \ to escape ".