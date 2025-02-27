---
layout: page
title: Disk Storage 
---

# Disk Storage at Fermilab
## Why do we need to care about disk storage?
There is a limited amount of storage allocated for each experiment at Fermilab. This storage space is split into several different disks, each of which have different sizes and purposes. Using the right disk for the right files can help ensure everyone has the space they need. 

## What disks exist?
There are two areas that contain storage disks from SBN experiments. These are:

- /pnfs/: This disk can talk to the Grid, so all inputs and outputs from grid jobs are stored here
- /exp/: This disk cannot talk to the Grid, so it is used for local development of code, running local scripts, and storage of histogram files

There are multiple disks that exist in each of these areas. These are experiment dependent, but will have the same general structure. The disks you will use the most are:

- /pnfs/[experiment]/scratch/
- /pnfs/[experiment]/resilient/
- /pnfs/[experiment]/persistent/
- /exp/[experiment]/app/
- /exp/[experiment]/data/

Where [experiment] can be sbnd, icarus or sbn. 

### Scratch Disk
The scratch disk is a temporary storage disk that will auto-delete files after a period of non-usage. 


