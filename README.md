# MemoryManipulator
A C# Library used to manipulate memory of a process.

//TODO - Complete this section.

# Download
The Latest Releases can always be found at either:

http://github.com/mullak99/MemoryManipulator/releases/latest

http://builds.mullak99.co.uk/MemoryManipulator/latest

# Usage

- Add the library as a referance to your project
- Create an instance of the library within your code


//TODO - Complete this section.

# Example Code

MemoryManipulator memory = new MemoryManipulator("ProcessName");

memory.WriteInt(offset, bytes);


//TODO - Complete this section.

# Changelog

|---| 1.0.0 |---|

- Initial Release

|--| 1.0.1 |--|

- Added function to easily convert a hexadecimal address into an Int32 and Int64.

|--| 1.1.0 |--|

- Minor code refactoring
- Now builds for various .NET Framework versions