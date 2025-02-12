Automated Data Archival & Purging System

Overview

	This project automates the archival and purging of old transactional data from Oracle databases using PL/SQL procedures and DBMS_SCHEDULER jobs.

Features

	Automated Data Archival: Moves data older than 90 days to archive tables.
	
	Automated Data Purging: Deletes data older than 180 days.
	
	Scheduled Execution: Uses DBMS_SCHEDULER to run the procedures daily.
	
	Performance Optimization: Keeps transactional tables lightweight for efficient queries.
	
	Data Retention Compliance: Ensures older data is stored safely before deletion.

Technologies Used

	PL/SQL
	
	Oracle Database
	
	DBMS_SCHEDULER (for automation)

Usage

	The system automatically archives and purges data daily.
	
	DBAs can monitor archived record counts with SQL reports.
	
	Data retention policies can be customized (e.g., change 90/180-day thresholds).
