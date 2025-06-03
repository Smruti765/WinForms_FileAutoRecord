# WinForms File Auto Record

This is a C# Windows Forms application to log user entries with Name, Age, and Email. Each entry is displayed in a DataGridView and saved into a date-wise log file.

## Features

- User input: Name, Age, Email
- Auto-record with current Date & Time
- Saves entries into a `.txt` log file inside `C:\wpf_crud\log\`
- Live entry count
- Clean UI with validation

## Technologies Used

- C# .NET Framework
- WinForms
- File I/O

## How it Works

1. User fills Name, Age, Email.
2. Clicks "Save"
3. Entry is shown in table + saved to `log\dd-MM-yyyy.txt`
