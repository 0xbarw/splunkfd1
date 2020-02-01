# Module 8: SPL Fundamentals
Search terms, commands, functions, arguments, clauses. Left to right flow is very important. Fields command removes fields to reduce result size. Field extraction is one of the least efficient portion of the search. Table is similar to fields, retains data in tabulated format. Rename lets us rename fields. Must use new name to modify this field further down the pipeline. Can use dedup to remove duplicate events from the results that share a common value. Sort allows us to sort results. 

### Module 8 Quiz
1. What command would you use to remove the status field from the returned events?
    * **fields -**
2. Which command removes results with duplicate field values?
    * **Dedup**
3. What is missing from this search?
    * **Quotation Marks around User IP**
4. Would the ip column be removed in the results of this search? Why or why not?
    * **No, because the name was changed.**
5. Excluding fields using the Fields Command will benefit performance.
    * **False**