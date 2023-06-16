---
description: >-
  Explore the advantages of Full Backup, a comprehensive data protection method
  that backs up all files and data in their entirety.
---

# Full Backup

### Definition

Full Backup, also known as a complete backup, refers to a data backup strategy where all selected data and files are copied from the source to a backup destination. It creates an initial copy of all the data and provides a comprehensive restore point for data recovery.

### Explanation

In a Full Backup, all data, files, and folders that are selected for backup are copied from the source location to a backup destination. This backup method captures and stores a complete replica of the selected data, creating a baseline or starting point for data protection.

During a Full Backup, all data is copied regardless of whether it has been previously backed up or modified. This ensures that all data is captured, providing a reliable and self-contained restore point in the event of data loss, corruption, or system failure.

Here are some key points about Full Backup:

1. Data coverage: Full Backup captures all selected data, including files, folders, databases, applications, and system configurations. It creates a complete snapshot of the source data at a specific point in time.
2. Restoration: Since Full Backup captures all data, restoring from a Full Backup is straightforward. In the event of data loss or system failure, the entire backup set can be restored, allowing for a complete recovery of the source data to its original state.
3. Time and storage requirements: Full Backups require more time and storage space compared to other backup methods. As the entire dataset is copied during each backup operation, the backup process can take longer and consume more storage resources.
4. Standalone backups: Full Backups are self-contained and independent of other backup operations. Each Full Backup constitutes a complete backup set that can be restored individually without relying on other backup types or incremental backups.

### Related terms

* Incremental Backup: A backup strategy that captures and stores only the changes made since the last backup, reducing backup time and storage requirements compared to Full Backups.
* Differential Backup: A backup strategy that captures and stores the changes made since the last Full Backup, providing an intermediate backup point between Full Backups.
* Backup Set: The collection of files, folders, and data that are selected and included in a backup operation, whether it's a Full Backup, Incremental Backup, or Differential Backup.
* Restore Point: A specific point in time to which data can be restored from a backup. In the case of a Full Backup, the backup operation itself serves as a restore point.
* Bare-Metal Backup: A Full Backup that includes the entire system's data, including the operating system, applications, settings, and files. It allows for complete system recovery in case of a system failure or disaster.
* Grandfather-Father-Son (GFS) Backup: A backup rotation scheme that involves Full Backups (grandfather), followed by incremental or differential backups (father), and further incremental backups (son). It provides multiple restore points with different retention periods.
* Backup Retention: The duration for which backup data is retained or preserved before it is purged or overwritten. Full Backups often have longer retention periods due to their comprehensive nature.
