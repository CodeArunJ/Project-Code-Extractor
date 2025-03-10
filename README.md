Project Code Extractor
📌 Overview
Project Code Extractor is a Python script that scans a project directory, extracts source code from relevant files, and compiles it into a structured .docx document. It helps in organizing and documenting project code efficiently.

🎯 Features
✅ Extracts source code from files with extensions like .py, .js, .java, .cpp, .c, .html, .css, .ts, .kt, .swift, .php
✅ Skips node_modules and unnecessary third-party libraries
✅ Ignores minified files like .min.js and .min.css
✅ Displays total code file count before processing
✅ Formats filenames as headings for better readability
✅ Handles encoding errors gracefully
✅ Saves output in a .docx file with structured sections

🚀 How to Use
1️⃣ Clone the Repository
sh
Copy
Edit
git clone https://github.com/yourusername/Project-Code-Extractor.git
2️⃣ Install Required Packages
sh
Copy
Edit
pip install python-docx
3️⃣ Run the Script
sh
Copy
Edit
python save_code.py
4️⃣ Provide Input Paths
Enter the project folder path to scan
Enter the output folder path where the .docx file will be saved
5️⃣ Output
The extracted code is saved as Project_Code_Documentation.docx in the specified output folder.

🛠 Example Usage
sh
Copy
Edit
Enter the full path of the project folder: C:\Users\Admin\React\AcademiX  
Enter the full path where the output file should be saved: C:\Users\Admin\Documents  
✅ Code successfully copied to: C:\Users\Admin\Documents\Project_Code_Documentation.docx  
📌 Total Code Files Processed: 12  
📌 Notes
The script skips node_modules to prevent unnecessary processing.
Minified files (.min.js, .min.css) are ignored to ensure readability.
If an error occurs while reading a file, the script stops execution and displays the error details.
📝 License
This project is open-source and available under the MIT License.

