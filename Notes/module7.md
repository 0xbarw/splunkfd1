# Module 7: Best Practices

* In Search
    * Use time to filter most efficiently, followed by index, source, host, and sourcetype. Extracted at index time. The more you tell the search engine, the more likely it is that you will get good results. Inclusion is stronger than exclusion. Filter as early as possible.
* Using Time
    * Time selected limits results. Event list will update in real time. Can customize time range heavily. @ can be used to round down to the nearest unit. 
* Using Indexes
    * Admins use multiple indexes to segregate data. Only searching indexes they need is more efficient. Possible to search multiple indexes at once.

### Module 7 Quiz
1. What is the most efficient way to filter events in Splunk?
    * **By time**
2. Time to search can only be set by the time range picker.
    * **False**
3. As a general practice, exclusion is better than inclusion in a Splunk search.
    * **False**
4. This symbol is used in the "Advanced" section of the time range picker to round down to nearest unit of specified time.
    * **@**
5. Having separate indexes allows:
    * **Faster searches**
    * **Ability to limit access**
    * **Multiple retention policies**

