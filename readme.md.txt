# Oracle Pluggable Database Assignment II
# Student Information
- Name:MUGISHA Parfait
- Student ID:28959
- Course:Database Development with PL/SQL
- Assignment:Pluggable Database II
## 1. Introduction
This assignment illustrates the creation, management, and deletion of Pluggable Databases (PDBs) using Oracle Database 21c. 
     It also includes configuration and access to Oracle Enterprise Manager (OEM Express).
## 2. Oracle Environment Used
     Oracle Database 21c
-    SQL Developer
-    Oracle Enterprise Manager Express (OEM)
## 3.  Task Explanations
  ## Task 1: Create a New Pluggable Database
     Created a PDB named:PA_PDB_28959
-    Opened the PDB in READ WRITE mode
-    Created a user inside the PDB:" parfait_plsqlauca_28959"
-    Granted required privileges
  ## Task 2: Create and Delete a Temporary PDB
     Created temporary PDB:PA_TO_DELETE_PDB_28959
-    Verified existence
-    Closed the PDB
-    Dropped the PDB including datafiles
-    Confirmed deletion
  ## Task 3: Oracle Enterprise Manager (OEM)
     Configured HTTPS port (5500)
-    Accessed OEM via https://localhost:5500/em
-    Verified PDB visibility
-    Confirmed database environment
  ## 4. Challenges Faced
   1.Invalid container name error in OEM login.
   - Solution: Used correct container named: CDB$ROOT.
   2.Browser security warning.
   - Solution: Proceeded using Chrome advanced option due to self-signed certificate
  ## 5. Integrity Statement
     I confirm that this work is my own and was completed according to the assignment guidelines.



