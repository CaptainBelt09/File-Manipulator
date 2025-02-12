# File-Manipulator Module
## OVERVIEW:
The File-Manipulator Module is a lightweight, efficient, and user-friendly Java package designed to provide robust file and directory management capabilities. It seamlessly integrates into existing Java projects, allowing developers to perform essential file operations such as creating, deleting, and renaming files and directories with ease. The module emphasizes performance, memory efficiency, and comprehensive error handling to ensure reliable operation in diverse use cases.

## REQUIREMENTS:
Functional Requirements:
The module must provide the following capabilities:

## Directory Management:

- Create Directory: Ability to create a new directory at a specified path.
- Delete Directory: Ability to delete an existing directory, including its contents if required.
- Rename Directory: Ability to rename a directory to a new name or path.
## File Management:

- Create File: Ability to create a new file at a specified path.
-Delete File: Ability to delete an existing file.
- Rename File: Ability to rename a file to a new name or path.
- Read File: Ability to read the contents of a file and return it as a string or list of strings.
- Write File: Ability to write text content to a specified file, overwriting existing content or appending to it.
- Append to File: Ability to add content to the end of an existing file without deleting existing data.
## Batch Operations:

- Ability to perform batch operations on multiple files or directories simultaneously, ensuring that all operations complete successfully or handle errors gracefully.
File and Directory Listing:

- Ability to list files and directories within a specified directory to facilitate browsing and management of filesystem contents.
Non-Functional Requirements:
The module must adhere to the following criteria:

## Performance:

- The application should initialize and be ready for use in under 30 seconds under normal operating conditions, with a maximum allowable start-up time of 1 minute for complex initialization conditions.
Memory Efficiency:

- The application should be optimized for low memory usage, utilizing efficient data structures and algorithms to minimize the memory footprint during file operations.
Concurrency:

- The module must handle multiple open documents simultaneously and allow for concurrent file operations without data corruption or inconsistency.
Error Handling:

- Extensive error handling must be implemented throughout the module. This includes:
Catching and managing exceptions gracefully.
Providing meaningful error messages to the users.
Implementing logging capabilities to record errors and exceptions for debugging purposes.
## User-Friendly Interface:

- The module should expose a clear and intuitive API for developers, allowing for easy integration into existing projects. Documentation should be provided to assist developers in understanding and utilizing the functionalities.
Cross-Platform Compatibility:

The module should function correctly across different operating systems (e.g., Windows, macOS, Linux) without requiring changes to the codebase.
