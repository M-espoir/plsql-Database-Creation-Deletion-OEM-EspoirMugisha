#Database,Creation,Deletion,OEM  
**Course**: Database Development with PL/SQL (INSY 8311)  
**Instructor**: Eric Maniraguha  
**Student**: Mugisha Espoir 27824                                                                                                                                     

**Group: C**


1. Overview of Tasks

   This report covers the creation, deletion, and management of Oracle Pluggable Databases (PDBs) as well as the configuration of Oracle Enterprise Manager (OEM).

Task 1: Creat of new PDB

In this task, a new Pluggable Database (PDB) was created inside the Oracle multitenant environment. The PDB was named es_pdb_27824, following the required naming format, and a dedicated user account espoir_plsqlauca_27824 was set up with a simple password for authentication. This account will be used exclusively for storing and managing coursework.

Creating the PDB ensured that the work is carried out in a secure and isolated environment without affecting other databases in the container. The dedicated user account provides accountability and controlled access, which is important for proper database management.

The screenshot of this step shows the SQL command used to create the PDB and user, confirming that the database was successfully created and made ready for use.
![Image](https://github.com/user-attachments/assets/4620e92f-744c-4e31-b7b5-e0cc9f8673d2)

This proves that the new PDB (es_pdb_27824) was created successfully with the specified admin username.


Task 2: Created and deleted PDB es_to_delete_pdb_27824.

In this task, another Pluggable Database (PDB) was created with the name es_to_delete_pdb_27824, 
following the required naming convention. This PDB was created successfully using SQL commands, and its presence confirmed that the system was functioning correctly.
![Image](https://github.com/user-attachments/assets/851d6d87-39ae-42fe-8451-33123d1a5d18)
After verifying its creation, the PDB was then deleted using the DROP PLUGGABLE DATABASE ... INCLUDING DATAFILES command.
This step permanently removed the database and its associated data files from the system.

The purpose of this task was to demonstrate the ability to not only create but also properly remove a PDB when it is no longer needed.
This shows an understanding of database lifecycle management, which is critical in real-world environments where databases may need to be retired or replaced.
![Image](https://github.com/user-attachments/assets/a22be159-83d6-403a-a164-b9031ee36b6a)
The screenshots for this task provide evidence of both the successful creation and deletion of the PDB,
confirming that the commands were executed correctly.




Task 3: Oracle Enterprise Manager (OEM)

In this task, Oracle Enterprise Manager (OEM) was configured to monitor and manage the database environment. After creating and deleting the required pluggable databases, OEM was accessed through the browser and used to verify the results. The dashboard confirmed that the new PDB (es_pdb_27824) was active, while the deleted PDB was no longer available.

The dashboard also displayed the username espoir_plsqlauca_27824, ensuring that the work was completed under the correct account. OEM provided an intuitive graphical interface for monitoring database status, managing PDBs, and validating the success of previous tasks without relying solely on SQL commands.

This step confirmed that both the system configuration and the administrative account were functioning as expected.
![Image](https://github.com/user-attachments/assets/b75f2ba7-17fe-4b0c-b091-1969404f0af2)
![Image](https://github.com/user-attachments/assets/99c96f33-e9e5-4525-9c28-7a155e710b77)

All tasks (PDB creation, PDB deletion, and OEM configuration) were completed successfully. The username and dashboard verification confirmed the successful execution of the required steps
