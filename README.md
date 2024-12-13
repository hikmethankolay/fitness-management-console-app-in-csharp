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

### Platforms
- ![Ubuntu badge](assets/badge-ubuntu.svg)
- ![macOS badge](assets/badge-macos.svg)
- ![Windows badge](assets/badge-windows.svg)

### Test Coverage
[![.NET Windows + Doxygen + Test + Release](https://github.com/ucoruh/vs-net-core-template/actions/workflows/build_check_ubuntu_windows.yml/badge.svg)](https://github.com/ucoruh/vs-net-core-template/actions/workflows/build_check_ubuntu_windows.yml)

**Coverage Metrics:**
- **Overall**: ![All](assets/badge_combined.svg)
- **Branch Coverage**: ![Branch Coverage](assets/badge_branchcoverage.svg)
- **Line Coverage**: ![Line Coverage](assets/badge_linecoverage.svg)
- **Method Coverage**: ![Method Coverage](assets/badge_methodcoverage.svg)

---

$End-Of-File$

