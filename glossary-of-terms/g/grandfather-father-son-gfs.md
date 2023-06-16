---
description: >-
  Learn about Grandfather-Father-Son (GFS), a backup rotation scheme that
  provides a comprehensive and scalable approach to data retention.
---

# Grandfather-Father-Son (GFS)

### Definition

Grandfather-Father-Son (GFS) is a backup rotation scheme or strategy used in data protection to manage and retain multiple backup generations over time. It provides a hierarchical approach to backup retention, allowing for long-term backups, incremental backups, and point-in-time recovery options.

### Explanation

The Grandfather-Father-Son (GFS) backup rotation scheme is based on the concept of three backup generations: the grandfather, the father, and the son. Each generation represents a different backup level and retention period, providing a balance between short-term recovery options and long-term data retention.

Here's how the GFS backup rotation scheme typically works:

1. Son Backups: Son backups, also known as daily backups, are frequent incremental backups performed on a daily basis. These backups capture changes made since the last backup, providing a recent point-in-time recovery option. Son backups are typically retained for a short period, such as a week.
2. Father Backups: Father backups, also known as weekly backups, are typically performed once a week. These backups capture the entire dataset, creating a full backup of the system or selected data. Father backups provide a more comprehensive recovery point and are often retained for several weeks or months.
3. Grandfather Backups: Grandfather backups, also known as monthly or long-term backups, are performed less frequently, usually once a month. These backups capture a complete backup of the system or selected data, similar to father backups, but are retained for a much longer duration, such as several months or years. Grandfather backups serve as a long-term archive and enable recovery from specific points in time further back in history.

The GFS backup rotation scheme ensures that recent backups are readily available for quick recovery, while also allowing for historical backups to be retained for compliance, regulatory, or archiving purposes.

### Related terms

* Backup Rotation: The practice of using multiple backup sets and cycling through them in a predefined order. Backup rotation schemes, such as GFS, ensure that backups are retained over time, enabling recovery from different points in time.
* Incremental Backup: A backup strategy that captures and stores only the changes made since the last backup, reducing backup time and storage requirements. Incremental backups are often used in conjunction with GFS or other backup rotation schemes.
* Full Backup: A backup strategy that involves copying all selected files and folders from the source to the backup destination. Full backups capture the entire dataset, creating a baseline for data protection. Father and grandfather backups in the GFS scheme are typically full backups.
* Backup Retention: The duration for which backups are retained and kept available for potential recovery. The GFS backup rotation scheme incorporates different retention periods for son, father, and grandfather backups.
* Point-in-Time Recovery: The ability to restore data to a specific point in time, typically based on the available backup generations. GFS provides point-in-time recovery options by retaining multiple backup generations, allowing for recovery from different backup levels.
* Archive: The long-term storage and preservation of data, typically for compliance, regulatory, or historical purposes. Grandfather backups in the GFS scheme serve as archives, providing access to older versions of data.
* Compliance Requirements: Regulations and standards that organizations must adhere to regarding data protection, privacy, and retention. The GFS backup rotation scheme can help organizations meet compliance requirements by providing a structured approach to data retention.
* Recovery Point Objective (RPO): The maximum acceptable data loss measured in time, indicating the point to which data can be recovered in the event of a disaster or data loss. The GFS backup rotation scheme helps in meeting RPO requirements by offering backups from different points in time.
* Recovery Time Objective (RTO): The maximum acceptable downtime or time it takes to recover data and resume normal operations. The GFS backup rotation scheme, combined with efficient backup strategies, helps in achieving shorter recovery times by having recent backups readily available.
