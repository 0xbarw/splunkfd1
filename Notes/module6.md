# Module 6: Using Fields

Fields sidebar shows all fields extracted at search time. Selected fields and interesting fields. Selected is most important. Host, source, sourcetype are default. A is string, # is numeral. Can click for more info. Can add to search, make report, and select. 

Can refine and run better searches using fields. field names are case sensitive, field values are not. = and != can be used with numerical OR string. >, >=, <, and <= can be used with numerical fields. 

NOT and != can return different results. != is for when a field does not equal something. NOT returns all events that don't have that field equalling something. 

Also have an IN operator. i.e. `index=web status IN ("500", "503", "505")`.

### Module 6 Lab:
* 1301 Events ended in errors.


### Module 6 Quiz
1. What attributes describe the circled field below?
    * **It contains string values**
    * **It contains 4 values**

2. Which is not a comparison operator in Splunk?
    * **?=**

3. Wildcards cannot be used with field searches.
    * **False**

4. Field values are case sensitive.
    * **False**

5. Field names are ________.
    * **Case Sensitive**

