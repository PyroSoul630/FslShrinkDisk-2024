## 2020 08 12
- Removed unecessary partition resize from script
- Fixed Diskpart wasn't running against disks with spaces in the path
- Improved Shrink for legacy vhd disks making them more consistent
- Added better error reporting if the disk doesn't mount properly
- Improved file filtering so it doesn't pick up false positives

## 2024 07 17
- Updated multiple lines in script to include IFS partition types
- Reduced "Cannot get partition information" errors for IFS partitions
- Tested on latest version of FSLogix
-        FSLogix 2210 hotfix 4 (2.9.8884.27471)
