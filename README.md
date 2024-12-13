# Fitness Management System App

## **I. Introduction**

The Fitness Management System is a project built using C# with .NET for cross-platform support, along with Doxygen for code documentation and unit tests. It is a console application that uses keyboard inputs for navigation.

## **II. System Architecture**

The system uses standard C file input/output libraries with custom file operation functions designed for this project:

- **file_read()** – Reads data from a file
- **file_write()** – Deletes all existing data and writes new data to the file
- **file_edit()** – Modifies a specified record line
- **file_line_delete()** – Deletes a specified record line
- **file_append()** – Adds a new record at the end of the file

## **III. Functionalities**

The system provides functionalities to view, register, update, and delete records through a menu-driven interface. Additional features include search and sort capabilities. The system manages the following types of data:

### **a. Member Management:**
- MemberID
- Full Name
- Birth Date
- Phone Number
- First Registration Date

### **b. Subscription Management:**
- MemberID
- Starting Date
- Finishing Date
- Subscription Tier

### **c. Class Management:**
- Tutor Name
- Date
- Starting Hour
- Finishing Hour
- Student List

### **d. Payment Management:**
- MemberID
- Paid Amount
- Payment Date
- Next Payment Date

Additional features include:
- **LCS System:** Warns users when entering very similar records.
- **OTP System:** Requires users to enter a one-time password when logging in.
- **Huffman Coding Algorithm:** Compresses files for efficient storage.

## **IV. Testing and Validation**

The system has been thoroughly tested and documented using Xunit. The tests achieved 95% coverage with 100% success in unit test results.

## Environment Setup

### Prerequisites
Ensure you have the following installed:
- Visual Studio with .NET Core 7.0 and XUnit.
- Package managers: [Chocolatey](https://chocolatey.org/install) and [Scoop](https://scoop.sh/).

### Additional Tools
- **Astyle**: For pre-commit code formatting.
- **Doxygen and Graphviz**: For documentation generation.
- **MkDocs Material Theme**: For creating project websites.

## **Supported Platforms**

![Ubuntu badge](assets/badge-ubuntu.svg)
![macOS badge](assets/badge-macos.svg)
![Windows badge](assets/badge-windows.svg)

## **Test Coverage Ratios**

> **Note**: Due to a known bug in Doxygen, badges with the same name in different folders may overwrite each other in the output directory. Refer to the README.md and web pages for the correct badges.

### **Coverage Comparison**

| Coverage Type | Windows OS                                                             | Linux OS (WSL-Ubuntu 20.04)                                              |
| ------------- | ---------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| Line Based    | ![Line Coverage](assets/codecoveragelibwin/badge_linecoverage.svg)     | ![Line Coverage](assets/codecoverageliblinux/badge_linecoverage.svg)     |
| Branch Based  | ![Branch Coverage](assets/codecoveragelibwin/badge_branchcoverage.svg) | ![Branch Coverage](assets/codecoverageliblinux/badge_branchcoverage.svg) |
| Method Based  | ![Method Coverage](assets/codecoveragelibwin/badge_methodcoverage.svg) | ![Method Coverage](assets/codecoverageliblinux/badge_methodcoverage.svg) |

### **Documentation Coverage Ratios**

|                    | Windows OS                                                        | Linux OS (WSL-Ubuntu 20.04)                                         |
| ------------------ | ----------------------------------------------------------------- | ------------------------------------------------------------------- |
| **Coverage Ratio** | ![Line Coverage](assets/doccoveragelibwin/badge_linecoverage.svg) | ![Line Coverage](assets/doccoverageliblinux/badge_linecoverage.svg) |

---

$End-Of-File$

