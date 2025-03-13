# Synology DSM Management Pack Development

This repository documents and tracks the development of a Synology DSM Management Pack. It includes resources for exploring Synology's APIs and the current Management Pack (MP) export.

## Repository Structure

- **API Exploration**  
  Contains:
  - Links to various pages with examples of Synology API usage (some weren't helpful, but I wanted to track them).
  - A Postman collection and environment setup for testing and supporting API interactions.
  - A reference guide of the Synology APIs explored during development.

- **MP JSON Export**  
  Contains:
  - The JSON export for the current version of the Management Pack, defining its functionality and configuration.

## Management Pack (MP) Overview

Once this is baked, it will act as a tech demonstrator customers can relate to for building their own management packs.

### Current Functionality

- Gathers basic information about the Disk Station
- Gathers Storage Pools
- Gathers Disks
- Gathers Volumes
- Builds a basic relationship between Storage Pools, Disks, and Volumes

### Shortcomings & To-Dos

- I'm stumped creating a relationship between the FileStation and the Storage Pool
- Gather IO stats and stuff for other objects
- Build relationship between iSCSI LUN & VMFS datastore
- Build relationship between NFS export and NFS mounter

## Contributing

Contributions, suggestions, and improvements are welcome. Please open an issue or submit a pull request with your ideas or fixes.  Feel free Email me at scottb@sentania.net / scott.bowe@broadcom.com
