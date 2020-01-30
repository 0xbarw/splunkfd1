# Module 2: What is Splunk?

Index is heart of splunk, collects data from any source, like a factory where data is raw materials, labels data with source type, break into single event, stored in index for searching. Can add knowledge to affect how data is interpreted, normalized, and reported on. Can monitor and alert. 

Three main processing components: 
* Indexer
    * Process incoming data, stores events, creates sets of directories by age. 
* Search Head
    * Allows user to search indexed data, distribute requests to indexers, perform the actual searches, then consolodate and enrich the results from the indexers before returning to user. Provides tools like dashes, reports, and viz's to assist search
* Forwarder
    * Splunk Enterprise instance that consumes and forwards data to indexers for processing, minimal resources, resides on machines where data originates. **In most splunk deployments, forwarders serve as the primary way data is supplied for indexing.** Not the only components, but basic building blocks.

Can be deployed in a variety of ways. Single instance: one instance handles everything. Perfect for PoC, Personal, Learning, Small environments. 

When we get to prod, split into dedicated servers. Can scale to fit any environment. 

## Module 2 Quiz
1. In most Splunk deployments, ________ serve as the primary way data is supplied for indexing.
    * **Forwarders**
2. A single-instance deployment of Splunk Enterprise handles:
    * **Searching**
    * **Parsing**
    * **Input**
    * **Indexing**
3. Which function is not a part of a single instance deployment?
    * **Clustering**
4. Which of these is not a main component of Splunk?
    * **Compress and archive**
5. Search requests are processed by the ___________.
    * **Indexers**

