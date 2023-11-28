# RDMS Python code examples
The Refinitiv Data Management Solution (RDMS) is an open platform that allows you to integrate the great depth and breadth of Refinitiv’s commodity data into your workflows.

### STEP 1:
To use these examples, please copy into the directory C:\RDMSPython.  Any other location can be used, but the line in each file that reads:
config.read('C:\\RDMSPython\\config.ini')
will need to be adjusted to reflect the new location.

### STEP 2:
Edit the file config.ini to reflect the RDMS server and API key you will be using.
To do this change the content of the file like this:

```[RDMS]
Api = https://<HOSTNAME>/api/v1
Key = <APIKEY>
```
to e.g.:

```[RDMS]
Api = https://demo.example.com/api/v1
Key = apikey-v1 1-7Ig0JR0tv9Bv5gMg3AgKzLBONKSdj1gDORrOIQ7```
These details should have been supplied to you as part of you subscription to the service.
Each Python script should then be able to be loaded into your Python interpreter and run.
