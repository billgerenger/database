---
description: >-
  Learn about Backup Schedules, a structured approach to planning and executing
  data backups.
---

# Backup schedule

### Definition

A backup schedule is a plan that specifies when and how often data backups should be performed. It typically includes details such as the frequency of backups, the time of day when backups should be performed, and the type of data that should be backed up.

### Explanation

A backup schedule is an important component of a data protection strategy, as it ensures that critical data is backed up on a regular basis and can be restored in the event of a disaster. The backup schedule should be based on the organization's Recovery Point Objective (RPO) and Recovery Time Objective (RTO), which specify the maximum amount of data loss and downtime that can be tolerated.

The frequency of backups in a backup schedule will depend on the rate of data change within the organization. For example, critical systems may need to be backed up every hour or even more frequently, while less critical systems may only need to be backed up once a day or once a week.

The time of day when backups are performed is also an important consideration, as backups can impact system performance and may need to be scheduled during off-peak hours. The backup schedule should also specify the type of data that should be backed up, such as databases, files, or applications, and whether full or incremental backups should be performed.

### Related terms

* Backup window: The period of time during which backups are performed.
* Full backup: A backup of all data on a system.
* Incremental backup: A backup of only the data that has changed since the last backup.
* Differential backup: A backup of only the data that has changed since the last full backup.
* Synthetic full backup: A backup that combines a full backup and one or more incremental backups.
* Backup retention period: The length of time that backups should be retained.
* Backup rotation: A strategy for rotating backup media, such as tapes or disks, to ensure that multiple backup copies are available.
