# Email-info-alarmid
Create a db in sqlite : id name ip address office region
Suppose the alarm gives only the NE ID as a starting point information to the operator, and then he will need to collect other information in order to prepare a detailed situation report and send it by email.
Why using  database? In some cases the user may check the alarm and see the NE ID, and then he will have to collect different information from different locations before being able to prepare an email and send it, (some information may need to be checked from a GUI interface, some other part on the needed information may be present in a separate document like spreadsheet or other type of files, a database will gather all these information in one single db or even table and makes possible to collect all the needed information with one single sql query.
