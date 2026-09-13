# Apartment Listing Program

A simple program written in C for my Algorithm and Programming final project, designed to read and manage apartment listing data. The program implements concepts I learned in my Algorithm and Programming class, such as variables, data types, input/output, as well as algorithms like merge sort and linear search.

There are four main functions in the program:
1. Display: Asks the user how many rows they want to see and displays that many rows of data from top to bottom.
2. Search: Asks the user which column they want to search and what value in that column, then displays all rows with that value in the column.
3. Sort: Asks the user which column they want to sort on and whether they want to sort by ascending or descending order (alphabetically for strings).
4. Export: Asks the user what they want to name the export file then exports the data (with the chosen sorting) into a .csv with the chosen name.

As well as an Exit function which terminates the program.

To run the program, you need a compiler that can read and execute C/C++, such as Dev-C++.

---

## 1. Installing Dev-C++

1. **Download Installer**: Obtain the latest installer ([Embarcadero_Dev-Cpp_6.3_TDM-GCC_9.2_Setup.exe](https://github.com/Embarcadero/Dev-Cpp/releases)).
2. **Run Setup**: Execute the downloaded installer file (`.exe`).
3. **Follow Installation Wizard**:
   - Select your preferred language.
   - Accept the license agreement.
   - Keep the default component selections.
   - Choose the installation path and click **Install**.
4. **Initial Launch**: Open Dev-C++ after installation completes and follow the initial configuration wizard to select interface language, font, and theme options.

## 2. Obtaining the Source Code

You can acquire the source code using either **Git** if you have it installed or by downloading a **ZIP archive**.

### Using Git Clone

1. Create a folder where you want to download the project onto.  
2. In that folder, run the following command in your terminal or command prompt:

```bash
git clone https://github.com/julianalby/algopro-final.git
cd algopro-final
```

### Downloading as a ZIP File

1. Navigate to the main page of the repository on GitHub.
2. Click the green **Code** button near the top right.
3. Select **Download ZIP** from the dropdown menu.
4. Extract the contents of the downloaded `.zip` file to a folder on your local machine.

## 3. Compiling and Running the Program

1. Launch **Dev-C++**.
2. Open the program file:
   - Go to **File** > **Open Single File...** (or press `Ctrl + O`).
   - Navigate to the project directory and select the `Question2.cpp` file.
3. Compile and Run:
   - Click **Execute** in the top menu bar, then click **Compile & Run**.
   - Alternatively, press the **F11** shortcut key.
4. The output console window will pop up automatically to display the program interface.
