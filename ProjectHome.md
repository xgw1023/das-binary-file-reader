Binary files are not self described, file structure are required while reading a binary file with specific type.
Das- BinaryFileReader(Das-BFR) were designed to handle custom binary file type by using the file structure template.

Current available template:
1.AxonBinaryFile


Loading the file template before reading the binary file,Application will know the structure which fits the file and will get the values in different types with right sequence.