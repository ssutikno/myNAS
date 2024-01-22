# myNAS
My Network Attached Storage. an easy to use and simple UI for managing NAS system. 

Features :
1. Support NFS, and SMB file only
2. Support Cloud Clients for OneDrive, Google Drive, OneDrive Enterprise
3. Support RAID 0,1,10,5
4. Up to 20 TB drives

This system is under design and development, many thanks to supporters

Requirements :
1. Debian linux minimal installation ( Debian installation guide: https://www.debian.org/releases/bullseye/amd64/ )
2. Install nfs-kernel-server for NFS ( NFS configuration guide: https://wiki.debian.org/NFSServerSetup ) and SMB ( Samba configuration guide: https://wiki.debian.org/Samba ) service
3. Node JS ( dependencies )
   Express.js: A popular Node.js framework for building web applications.
   nfs-server: A Node.js package for managing NFS exports.
   smb-with-node: A Node.js package for interacting with SMB shares.
   ejs: A templating engine for generating HTML dynamically.
