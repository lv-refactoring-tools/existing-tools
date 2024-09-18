# Existing Tools

This is intended as a list of existing LabVIEW tools for refactoring and dealing with legacy code. 

## VIPM List

In addition to this list we also maintain [a package list on VIPM.io](https://www.vipm.io/package-list/59b3e57f-a35e-48dd-8a85-2478bb9fa698/) with many of these 3rd party tools.

## Organization

I think of 4 different types of tools

- **Inspection** These are tools that automatically generate UML or other types of diagrams or reports to help us understand Legacy Code. Examples: Antidoc, Lumos, OpenGDS UML generation, AF trace parsing to generate sequence diagrams.
- **Navigation** These are tools that help navigation within a project. Examples: Tools to find where class datamembers are used, AF OPenPayload, or find all senders for a particular message.
- **Reorganization** These tools help us rename, move, and reorganize code. These allow up to rename/move code on disk and change library and class membership. Examples: Tools for renaming/moving classes/libraries. Tools for moving methods and data up or down class heirarchies.
- **Creation** These are tools that allow us to create new code (based on existing) ie. Example: Extract Interface, Turn cluster into class.

## Built In Tools

These are tools that are built-in to and ship with LabVIEW - broken up by category, but otherwise in no particular order

### Inspection

- VI Analyzer
- Class Hierarchy
- VI Heirarchy
- DETT

### Navigation

- Zoom
- Navigation Window
- Find All Instances
- Find All Callers

### Reorganization

- Files View in Project
- Saves As Dialog

### Creation

- New VI for override
- Convert Cluster to Class

## Third Party Tools

These are 3rd party tools that do not ship with LabVIEW and must be installed separately into your IDE. These take many forms such as quickdrop shortcuts, right click menu shortcuts, project providers, tools menu tools, etc. Many are distributed as VIPM packages. Others are distirbuted in different ways such as the NI forums or simply GitHub or GitLab repositories. Some occur in multiple categories like Open GDS.

### Inspection

- OpenGDS

### Navigation

- View AF Payload
- VI Peek Semantic Zoom

### Reorganization

- OpenGDS

### Creation

- OpenGDS
- Extract Interface
- 
