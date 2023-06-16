---
description: >-
  Explore Differential Backup, an efficient data protection method that captures
  and stores only the changes made since the last full backup.
---

# Differential Backup

### Definition

A differential backup is a type of backup that copies and stores only the data that has changed since the last full backup. It captures the differences between the full backup and the current state of the data, providing a more efficient backup method compared to full backups.

### Explanation

In a differential backup strategy, the first backup performed is a full backup that copies all the selected data. Subsequent backups are then differentials that capture only the changes made since the last full backup. This means that each differential backup includes all the data that has changed since the last full backup, regardless of whether it has been included in previous differential backups.

Differential backups offer a balance between backup efficiency and restore performance. They require less storage space and backup time compared to full backups since only the changed data needs to be processed. However, the restore process can take longer as each differential backup needs to be applied sequentially, starting from the full backup.

It's important to note that differential backups do not affect the integrity of the previous backups. Each differential backup is independent and can be restored on its own, provided the full backup is available.

### Related terms

* Full backup: A backup that copies all selected data, creating a complete copy of the data set at that point in time.
* Incremental backup: A backup that copies only the data that has changed since the last backup, regardless of whether it was a full or incremental backup.
* Backup rotation: The practice of retaining multiple backups over time, often in a predefined schedule, to provide multiple recovery points.
* Backup window: The time frame during which backups are performed, typically during off-peak hours to minimize the impact on system performance.
* Backup strategy: A comprehensive plan that outlines the frequency, type, and retention policies of backups to ensure data protection and recovery.
* Recovery: The process of restoring data from a backup to its original state or a desired point in time.
