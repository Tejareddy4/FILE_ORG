# FILE_ORG

FILE_ORG is a utility designed to organize files in your directory based on their file types. This tool scans a specified directory, identifies the file types, and moves them into folders named after their respective types. It's an excellent way to keep your downloads, documents, or any other folder organized without manually sorting each file.

## Features

- **Automatic File Detection:** Automatically detects file types based on file extensions.
- **Customizable Organization:** Users can specify which file types to organize and define custom folders for specific types.
- **Recursive Organization:** Optionally, organize files in subdirectories recursively.
- **Safe to Use:** Before moving any files, FILE_ORG creates a backup to prevent data loss.

## How It Works

FILE_ORG works by scanning the specified directory for files, categorizing them by their extensions, and then moving them to their designated folders. If a folder for a specific file type does not exist, FILE_ORG creates it.

# Cloning the Repository

To clone the FILE_ORG repository to your local machine, follow these steps:

1. Open a terminal or command prompt.
2. Navigate to the directory where you want to clone the repository.
3. Run the command: git clone https://github.com/Tejareddy4/FILE_ORG.git

# Running the Code

After cloning the repository, you can run FILE_ORG by following these steps:

1. Open a terminal or command prompt.
2. Navigate to the directory where FILE_ORG is located. If you just cloned the repository, it should be under the name `FILE_ORG` in the directory where you ran the clone command.
3. Run the command: python file_org.py

## Usage

To use FILE_ORG, follow these steps:

1. **Installation:** Clone the repository or download the source code to your local machine.
2. **Configuration:** Open the `config.json` file (if available) to customize the file types and destination folders. If not present, the default settings will apply.
3. **Running the Tool:**
    - Open a terminal or command prompt.
    - Navigate to the directory where FILE_ORG is located.
    - Run the command: `python file_org.py <path_to_directory>` replacing `<path_to_directory>` with the path to the directory you want to organize.

## Requirements

- Python 3.x
- No external libraries are required for the basic functionality.

## Contributing

Contributions are welcome! If you have suggestions for improvements or bug fixes, please open an issue or submit a pull request.

## License

FILE_ORG is released under the MIT License. See the LICENSE file for more details.