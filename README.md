# DynamoDB

##################################
DynamoDB is a NoSQl database by AWS

I have written some funtions which can used to carry out day to day database operations.
Alot of people working with DynamoDB has faced issues in carrying out these operations with python and seen a lot of requests on StackOverflow , so I have written these functions.I hope these can help you out.

IN order to create a table, first you need to specify the schema of the Table which is generally a key value pair.Specify this in your data_file. 
For e.g:
{"hash_key":"key_id",
"columns":[ "value"]}
Or according to the need of your table structure.

DynamoDB also allows for secondary key as well.You can refer to AWS documentation for that.

####################################
