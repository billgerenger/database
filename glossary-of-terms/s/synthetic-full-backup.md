---
description: Explore the concept of Synthetic Full Backup in data protection.
---

# Synthetic Full Backup

### Definition

Synthetic Full Backup is a backup strategy that combines a full backup image with subsequent incremental backups to create a synthetic full backup. Instead of performing a traditional full backup, synthetic full backup leverages the existing full backup and applies incremental changes to create a consolidated and up-to-date backup image.

### Explanation

Synthetic Full Backup offers several advantages in backup and recovery operations:

1. Backup Window Optimization: Performing a traditional full backup can be time-consuming and resource-intensive. Synthetic Full Backup eliminates the need for frequent full backups by leveraging the initial full backup and subsequent incremental backups. This approach significantly reduces the backup window time, allowing backups to be completed more efficiently.
2. Reduced Network Bandwidth and Storage Space: As synthetic full backups only transfer incremental changes since the last full backup, they consume less network bandwidth and storage space compared to traditional full backups. This optimization reduces backup-related costs and minimizes the impact on network performance.
3. Faster Recovery: Synthetic full backups provide a consolidated and up-to-date backup image that can be used for efficient recovery. In case of data loss or system failure, recovery operations can be performed more quickly by using the synthetic full backup as the restore point, eliminating the need to restore multiple incremental backups.
4. Storage Optimization: By consolidating incremental changes into a synthetic full backup, storage utilization is optimized. Redundant data blocks across multiple incremental backups are eliminated, resulting in reduced storage requirements and cost savings.

### Related terms

* Full Backup: A backup type that captures a complete copy of all data and files in a system or environment.
* Incremental Backup: A backup type that captures only the changes made since the last backup, reducing backup time and storage space requirements.
* Backup Window: The time period available for performing backup operations without impacting production systems or causing performance degradation.

Synthetic Full Backup combines the benefits of full and incremental backups, optimizing backup window time, network bandwidth, and storage utilization. By leveraging the initial full backup and subsequent incremental backups, organizations can achieve faster backups, efficient recovery, and cost-effective storage management.

\
