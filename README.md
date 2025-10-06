# pl-sql_oracle-pdb-management-cedric-ntwari
# Name: Ntwari Cedric 
# Student ID: 28228 
# Date: 06 October 2025  
# Instructor: Eric Maniraguha 
# courses: Database development with PL/SQL  

# 1. Overview of Tasks 

The objectives of this assignment were: 
• Task 1: Create a new Pluggable Database (PDB) named ce_pdb_28228 and a user 
Cedric_plsqlauca_28228 to store all class work. 
• Task 2: Create and then delete another PDB named ce_to_delete_pdb_28228 to 
practice PDB deletion. 
• Task 3: Configure Oracle Enterprise Manager (OEM) and verify the PDBs visually.

## TASK1: create new pluggable database ( pdb  ) 
I used cmd to connect to my Oracle database using SQL*Plus. After connecting, I began Task 
1 by creating a pluggable database named ce_pdb_28228. The admin user I created for this 
PDB is Cedric_plsqlauca_28228, following the specified format. 
![database creation](https://github.com/ntwari-cedric/pl-sql_oracle-pdb-management-cedric-ntwari/blob/main/work%201%20(creat).png).

After creating it, I opened the PDB, as it will be needed in Task 3 to be displayed in Oracle 
Enterprise Manager. I then verified that it was created successfully. 
![check if is in](https://github.com/ntwari-cedric/pl-sql_oracle-pdb-management-cedric-ntwari/blob/main/work%201(see).png).

Finally, I checked that the user was also created correctly. This completes Task 1. 
![check if all clear](https://github.com/ntwari-cedric/pl-sql_oracle-pdb-management-cedric-ntwari/blob/main/work1%20(open).png).

# Task 2: Create and Delete a PDB 
This task involved creating a PDB for the specific purpose of practicing the deletion process. 
First, I created the pluggable database named ce_to_delete_pdb_28228, following the 
specified format.
![create pdb](https://github.com/ntwari-cedric/pl-sql_oracle-pdb-management-cedric-ntwari/blob/main/work2(create).png).

After creating the PDB, the next step was to verify that it was created successfully. Before 
go to the next step
![check pdb](https://github.com/ntwari-cedric/pl-sql_oracle-pdb-management-cedric-ntwari/blob/main/work2(%20check).png).

With the PDB successfully created and verified, I proceeded to the deletion phase of the 
task, dropping the ce_to_delete_pdb_28228 database. 
![delete pdb](https://github.com/ntwari-cedric/pl-sql_oracle-pdb-management-cedric-ntwari/blob/main/work2(delete).png).

# task3: 
![eml](https://github.com/ntwari-cedric/pl-sql_oracle-pdb-management-cedric-ntwari/blob/main/004%20og.png).

The Oracle Enterprise Manager dashboard confirms the successful visual verification 
required for Task 3, showing both CE_PDB_28228 actively being monitored

## Conclusion  
In conclusion, this assignment's objectives for Oracle Pluggable Database (PDB) management were 
successfully executed and verified. Task 1 involved the creation of the persistent PDB, 
ce_pdb_28228, along with its dedicated administrative user, cedric_plsqlauca_28228. Task 2 
successfully demonstrated the PDB lifecycle by creating and then safely dropping the temporary 
database ce_to_delete_pdb_28228. The full operational status and verification of these tasks 
were confirmed via the Oracle Enterprise Manager (OEM) dashboard provided in Task 3. For 
complete transparency, all steps, scripts, and supporting files used during this assignment have been 
archived and are available above 
