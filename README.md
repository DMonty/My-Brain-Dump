# My-Brain-Dump

We have all been there, particularly as Administrators, someone sends a list of hundreds of accounts by name, email or some ID and requires either to pull information or to take an action. The information they supply must usually be cleaned and standardized, converted unto CSVs, saved to a file, then imported into PowerShell. This is repetitive and can turn a simple request into a lengthy process. 

To deal with this I have written a function which employs a GUI allowing this information to be cut & pasted directly into a variable. 

For anyone not needing this type of script there are still some examples which may be beneficial so see. 

•	The GUI is created using Winforms. It would not be difficult to repurpose.
•	GUIs can create threading issues when run in PowerShell resulting in the shell window crashing. This script provides an example on how to run a Multithreaded (MTA) GUI within a single threaded PowerShell instance (STA) using & managing runspaces.
•	You will find a Regex example who showing how to deal with varying string formats I have seen clients submit.
•	You will also see how strings can be managed to deal with empty rows, concatenated CSV strings, mixed strings with carriage returns and CSV, display name email addresses (i.e. descriptive name <emailname@somerandomservice.com>)
