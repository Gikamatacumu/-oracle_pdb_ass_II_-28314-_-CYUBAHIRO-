# -oracle_pdb_ass_II_-28314-_-CYUBAHIRO-

# Oracle Pluggable Database Management Assignment
## INSY 8311 - Database Development with PL/SQL
**Student:** CYUBAHIRO Ivan | **ID:** 28314 | **Date:** February 16, 2026

---

## Oracle Environment
- **Oracle Version:** Oracle Database 21c Express Edition (21.3.0)
- **Operating System:** Windows 11 Pro (64-bit)
- **Tools Used:** SQL Developer 23.1.1, OEM Express
- **RAM Allocated:** 16 GB
- **Installation Path:** C:\app\oracle

---

## Task 1: Create a New Pluggable Database

### PDB Details
- **PDB Name:** `cy_pdb_28314`
- **Username:** `cy_plsqlauca_28314`
- **Password:** `password123`

Opened successfully and saved.

## Task 2: Create and Delete Temporary PDB
Created:
cy_to_delete_pdb_28314

Deleted using:
DROP PLUGGABLE DATABASE INCLUDING DATAFILES;

 Successful deletion.

## Task 3: Oracle Enterprise Manager
Accessed OEM via:
https://localhost:5500/em

Verified PDBs and container structure.

## Challenges Faced
Initially encountered ORA-65040 error due to being inside a PDB.
Resolved by switching to CDB$ROOT.

## Integrity Statement
I confirm that this assignment was completed individually and reflects my own practical execution.
