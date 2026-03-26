# Datto BCDR – Screenshot Verification Failure Troubleshooting

## Issue
Screenshot verification failing for backups in Datto BCDR.

## Symptoms
- Backup completed but screenshot test failed
- Virtualization errors during screenshot process
- Boot failure during verification

## Root Causes Identified
- Network dependency issues during virtualization
- Incorrect VM configuration
- Disk or OS boot-related problems

## Troubleshooting Steps

1. Verified backup integrity in Datto portal  
2. Attempted Instant Virtualization with network enabled  
3. Retested virtualization without network to isolate issue  
4. Checked VM boot configuration and disk status  
5. Reviewed Datto agent logs and alerts  

## Resolution
- Successfully virtualized system without network dependency  
- Identified configuration issue affecting screenshot verification  
- Restored backup reliability and validation success  

## Outcome
- Improved backup verification success rate  
- Reduced repeated backup-related alerts  
