# Address Book

This script is designed to manage an address book with basic functionalities using a Bash terminal interface. It allows you to add, display, search, update, and delete records in the address book. Additionally, you can import records from an external .csv file.

## Prerequisites

To use this script, you need to have the following installed on your system:

- Linux-based operating system (for Bash shell)
- `dialog` package: This package is used to create interactive dialogs in the terminal. Make sure it is installed on your system.

## Usage

1. Clone or download the script file (`addressbook.sh`) to your local machine.
2. Open a terminal and navigate to the directory where the script is located.
3. Make the script executable by running the following command:
 
```bash
chmod +x addressbook.sh
```

4. Run the script using the following command:

```bash
./addressbook.sh
```
 
5. The script will display a menu with various options for managing the address book.

## Important Notes

- The script uses the `dialog` utility to provide a user-friendly interface in the terminal. Make sure you have it installed to use this script.
- Contact information is stored in the `addressbook.csv` file in the same directory as the script.
- Importing data from a CSV file is a one-time operation.

## License
This project is licensed under the [MIT License](LICENSE).
