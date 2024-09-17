# Existing Tools

This is intended as a list of existing LabVIEW tools for refactoring and dealing with legacy code.

## Organization

I think of 4 different types of tools

- **Inpsection** These are tools that automatically generate UML or other types of diagrams or reports to help us understand Legacy Code. Examples: Antidoc, Lumos, OpenGDS UML generation, AF trace parsing to generate sequence diagrams.
- **Navigation** These are tools that help navigation within a project. Examples: Tools to find where class datamembers are used, AF OPenPayload, or find all senders for a particular message.
- **Reorganization** These tools help us rename, move, and reorganize code. These allow up to rename/move code on disk and change library and class membership. Examples: Tools for renaming/moving classes/libraries. Tools for moving methods and data up or down class heirarchies.
- **Creation** These are tools that allow us to create new code (based on existing) ie. Example: Extract Interface, Turn cluster into class.
