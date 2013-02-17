# About this repo
This is primarily a place for sharing any small apps or DNA queries related to III's ILS Sierra. I'm storing all Sierra-related stuff here, unless there's an app that grows to the point where it needs to be pushed into its own repo. Consider this as a stepping stone for me to getting into github properly. :cP

# Required disclaimer
Everything here is as-is. Run at own risk. It is not my fault that your computer rickrolls you after running one of the scripts below.

In addition, the queries found in this repo are based on the local setup that my library has with their ILS. YMMV with several of these queries, and it would be worthwhile to ask someone who is familiar with the local data setup if you are looking to run a query on a particular piece of data.

# Repo structure

## Queries
This folder holds various SQL queries I have constructed for retrieving data from Sierra's postgresql database (SierraDNA). The table structure, as well as what data lives where, is in the [CS Direct Techdocs section](http://techdocs.iii.com/sierradna/) (CS Direct login required). You also might want to consult the [Sierra help documentation about DNA](http://csdirect.iii.com/sierrahelp/Default.htm#ssql_direct_access.html) for more information (again, login required).

Each query found here should have an explanation as to what it is retrieving as well as any local data notes.

One recommendation from III is to use the EXPLAIN command to determine the system cost of a particular query. This is especially important when you are modifying any queries found under this folder. **You will lock up the system if you are not careful with your queries.**
