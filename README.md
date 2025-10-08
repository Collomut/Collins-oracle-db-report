# Oracle Database PDB Report

**Name:** Collins Mutinda

**Student ID:**27842

---------------------------------------------------------------------------
# 1. Overview of Tasks
This document is an assignment on Pluggable Database administration in an Oracle database.It demonstrates an understanding of the creation and management of a Pluggable database and a connection via the Oracle Enterprise Manager interface.

# 2. Creation of a Pluggable Database
The PDB created is named co_pdb_27842 which is to be managed by the Admin user collins_plsqlauca_27842 this task was successful as shown below:-
>creating co_pdb_27842

<img width="454" height="71" alt="creating co_pdb_27842" src="https://github.com/user-attachments/assets/a9d9d4f6-fbec-476f-a985-4ca43d518709" />

>granting the user collins permissions as the DBA

<img width="481" height="49" alt="granting dba collins" src="https://github.com/user-attachments/assets/230ea654-7f19-47f2-920d-10a77b7f1dc6" />


# 3. Creation and Deletion of a Pluggable Database 
The PDB created for this was named co_to_delete_pdb_27842 which was managed by collins_plsqlauca_27842. The pluggable database was then dropped successfuly.

>creating co_to_delete_pdb_27842

<img width="528" height="141" alt="creating database to delete" src="https://github.com/user-attachments/assets/9e237a28-caa7-492f-a30d-625fe17d10f0" />

>Dropping the pluggable database

<img width="523" height="59" alt="dropping db" src="https://github.com/user-attachments/assets/2bd2134a-d89b-4698-95fe-97cc0e657e09" />

# 4. ORACLE ENTERPRISE MANAGER 
The login to the OEM was succesful 

>checking the port in which the OEM is being hosted

<img width="455" height="116" alt="checking port for OEM" src="https://github.com/user-attachments/assets/e7122847-aaed-446f-9195-b4a644e309ff" />

>The Oracle Enterprise Manager login page

<img width="960" height="540" alt="Oracle Enterprise manager login" src="https://github.com/user-attachments/assets/57c12b8a-07b1-47cc-8697-8b89368f1bd5" />

>Oracle Enterprise Manager Dashboard

<img width="960" height="540" alt="oracle Enterprise manager homepage" src="https://github.com/user-attachments/assets/52c6f3a6-b3f9-4e3c-9087-299d866bcf80" />



# 5. Issues Encountered
> The initial assignment was done on the oracle 23c which run smoothly on creation and deletion but got persistent errors while trying to access the Oracle Enterprise Manager this was due to a conflict with the environment variables. The whole problem led to the clean uninstallation of the Oracle 23c and opting for a more stable Oracle 19c which worked well with no issues at all.

