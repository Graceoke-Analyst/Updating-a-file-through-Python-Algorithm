# Updating-a-file-through-Python-Algorithm
## Summary
This project shows demonstrate hands on proficiency on the use of python programming language. For this project i updated a file that identifies the employees who can access restricted content using Python algorithm,i created an algorithm that uses Python code to check through the allow list ( a file for IP addresses permitted to sign into the restricted subnetwork) and identify if  any IP address identified on the remove list ( a file  that identifies which employees i must remove from this allow list) is on the allow list so it can be removed.

## Tools
Python (a programmimg language)

## Action
1) I opened the allow_list by assigning the file name as a string to the import_file varible, next i used the "with" statement to open it
2) Next i used the ".read ()" method to converts the content of the allow_list file to into a string so i can read it, then i stored it in the IP_addresses variable.
3) In order to remove individual IP addresses from the allow_list, the IP addresses needed to be in a list format. Therefore, I use the ".split()" method to convert the ip_addresses string into a list.
4) To iterate through the remove list i incoporated a "For" loop using " Element" as the loop variable.
5) Next, to remove the IP addressess on the remove list, within the "for" loop i created i inputed the ".remove()" method to the ip_addresses variable to remove the IP addresses identified in the loop variable " element” by passing in element as the argument into the parentheses after “.remove()” method.
6) Lastly, Now that i have removed these IP addresses from the ip_address variable, i can complete the algorithm by updating the file with this revised list. To do this, i will  first convert the ip_addresses list back into a string using the ".join()" method. i applied ".join() " to the string "\n" in order to separate the elements in the file by placing them on a new line. Then, use another with statement and the ".write()" method to write over the file assigned to the import_file variable.

## Result/Impact
 Successful implemenetation of security control to limit access to one of the organization valuable assessts.

## Project artifacts
see projrct file @ Update a file through python (https://github.com/Graceoke-Analyst/Updating-a-file-through-Python-Algorithm/blob/main/Update%20a%20file%20through%20a%20Python%20algorithm.md)

