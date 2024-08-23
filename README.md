# File Packer and Unpacker
- This project serves as a tool to pack multiple files into a single file.
- The generated packed file can then later be used to retrieve original files. Both of the above tasks can be called as packing and unpacking activity.

# About
- This tool is used to perform packing and unpacking activity for multiple types of files.
- In case of Packing activity we maintain one file which contains metadata and data of multiple files from specified directory.
- In case of Unpacking activity we extract all data from packed files and according to its metadata we retreive all the original files.
- During the packing process all the data from files is first encrypted and then packed together along with it's checksum to ensure that data is untampered and another unauthorized person can't access it.
- While unpacking the tool first checks if the checksum is correct and the file is untampered. By using the metadata of packed files, it retrieves the original files with their data intact.
