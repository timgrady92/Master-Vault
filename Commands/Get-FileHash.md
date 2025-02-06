# Metadata

2025-02-06 13:45

**Tags:** [[PowerShell]]

----
# Get-FileHash

**Base Operating System:**

- Windows

**Terminal Type:**

- PowerShell

**Main Purpose of Command:**

- Check a file's hash value with a variety of supported hashing algorithms

**Examples:**

```
Get-FileHash C:\Users\Admin\Desktop\TestFile.txt
```
```
Get-FileHash C:\Users\User123\Documents\Test.txt -Algorithm MD5
```
**Notes:**

- If an algorithm is not specified, the command will generate the file's SHA256 hash value
