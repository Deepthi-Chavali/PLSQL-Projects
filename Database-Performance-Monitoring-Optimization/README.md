Database Performance Monitoring & Optimization

Overview

	This project aims to track and optimize database performance by identifying slow queries, analyzing indexing strategies, and monitoring execution trends using PL/SQL scripts and scheduled jobs.

Features

	Automatically captures slow-running queries from v$sql.

	Logs execution time, CPU usage, and IO wait time.

	Schedules monitoring jobs to run every 30 minutes.

	Generates performance reports for analysis.

	Sends email alerts for queries exceeding 5 seconds execution time.

	Implements data archival and purging for long-term performance tracking.

Technologies Used

	PL/SQL (Stored Procedures, Triggers, DBMS_SCHEDULER)

	Oracle Database (v$sql, AWR Reports, Indexing)

	UTL_MAIL (for sending alerts)

Usage

	The system logs slow queries automatically every 30 minutes.

	DBAs can analyze performance trends using SQL reports.

	Index optimization can be performed based on captured query execution plans.

	Alerts notify the DBA team when performance thresholds are breached.
