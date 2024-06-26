## File Converter

This Python program provides a simple command-line interface (CLI) for converting various file types to different formats. Users can choose from options to convert video to audio, PDF to Word, Word to PDF, and TXT to PDF. The program utilizes popular libraries like `moviepy`, `pdf2docx`, `docx2pdf`, and `reportlab` for handling file conversions.

### Features:

- **Multiple Conversion Options**: Supports conversion between different file types, including video to audio, PDF to Word, Word to PDF, and TXT to PDF.
- **Interactive Interface**: Offers a user-friendly CLI with numbered options for easy selection.
- **Error Handling**: Includes error handling mechanisms to gracefully handle unexpected issues during file conversion.
- **Feedback Messages**: Provides informative messages to guide users through the conversion process and confirm successful completion.

### Technologies Used:

- **Python**: The core programming language used for scripting and logic implementation.
- **Libraries**: Utilizes various Python libraries such as `moviepy`, `pdf2docx`, `docx2pdf`, and `reportlab` for specific file conversion tasks.
- **Tkinter**: Integrated for file selection dialogs in the TXT to PDF conversion functionality.
- **Command-Line Interface**: Presents a CLI interface for users to interact with the program and select conversion options.

### Usage:

1. Run the program by executing the Python script.
2. Choose from the available conversion options by entering the corresponding number.
3. Follow the prompts to select the input file and specify the output location.
4. Wait for the conversion process to complete.
5. View the generated files in the specified output locations.

### How to Run:

1. Clone this repository to your local machine.
2. Ensure you have Python installed.
3. Run the following commands to install the required libraries:
   ```
   pip install moviepy pdf2docx docx2pdf reportlab
   ```
4. Run the `file_converter.py` script using Python.

### Contributions:

Contributions are welcome! If you have any ideas for improvements, additional features, or find any bugs, feel free to open an issue or create a pull request.

### License:

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
