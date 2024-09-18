# 🧪 SQA_TestLab

**SQA_TestLab** is a practical project aimed at mastering **Software Quality Assurance** (SQA) through thorough **manual testing**, detailed **bug tracking**, and effective **test case development**. This project highlights the importance of delivering high-quality software by simulating real-world testing environments and using industry-standard tools.

## 📋 Project Overview

The purpose of this project is to showcase hands-on expertise in **manual software testing** across various modules. The project focuses on improving software quality, reliability, and performance through structured **test cases**, bug reporting, and performance analysis.

### 🔑 Key Features:

- Comprehensive **test case creation** for different application modules.
- In-depth **bug tracking** and issue reporting using **Jira**.
- **API testing** and validation using **Postman**.
- Real-world scenarios for ensuring **software reliability** and **user satisfaction**.

## 🛠️ Tools & Technologies

- **Manual Testing**: Functional, regression, and integration testing.
- **Jira**: For tracking and reporting bugs, issues, and tasks.
- **Postman**: For testing and verifying APIs.
- **Excel/Google Sheets**: For documenting test cases and tracking progress.
  
## 📂 Project Structure

```bash
SQA_TestLab/
│
├── Test_Cases/                   # Test cases for different features
│   └── User_Authentication_TestCases.xlsx
│   └── Payment_Module_TestCases.xlsx
│
├── Bug_Reports/                  # Detailed bug reports with evidence
│   └── Login_Issue_Report.pdf
│   └── Payment_Bug_Report.pdf
│
├── API_Testing/                  # API testing reports and Postman collections
│   └── Postman_Collection.json
│   └── API_Testing_Report.pdf
│
├── Performance_Reports/          # Performance testing and analysis
│   └── API_Performance_Postman_Report.pdf
│
├── README.md                     # Project documentation and overview
```

## 📐 Test Process

1. **Test Case Development**  
   Test cases are created based on application requirements, focusing on key modules such as user authentication and payment processing. These test cases include detailed steps, expected results, and actual outcomes.

2. **Test Execution**  
   Manual testing is conducted to verify functionality, usability, and performance. Each test case is executed, and outcomes are compared against expected results to identify any discrepancies.

3. **Bug Reporting**  
   Bugs and issues discovered during testing are logged in **Jira**, complete with severity, priority, steps to reproduce, and relevant attachments such as screenshots or videos.

4. **API Testing**  
   **Postman** is used for validating API endpoints, ensuring proper responses, data accuracy, and performance under different conditions.

## 🐞 Bug Tracking Example

**Bug Title**: User Authentication Failure on Mobile Devices  
**Severity**: High  
**Priority**: Critical  

**Steps to Reproduce**:
1. Access the login page on a mobile device.
2. Enter valid credentials.
3. Tap the "Login" button, which fails to log in the user.

**Expected Result**: The user is logged in and redirected to the dashboard.  
**Actual Result**: The login button is unresponsive.  

**Resolution**: The issue was replicated and assigned to the development team for fixing.

## 🚀 API Testing Process

**Postman** is used to verify API functionality, response times, and data integrity. The API collection includes tests for user registration, authentication, and payment processing. The **performance of APIs** is measured, and data is logged to ensure stability under different load conditions.

## 🔧 Performance Evaluation

Performance testing was conducted using **Postman**, focusing on the reliability and response time of critical APIs. The API performance report highlights any bottlenecks or slowdowns and provides recommendations for improvement.

## 🔗 How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/AreejPanhwer/SQA_TestLab
   ```

2. Navigate to the **Test_Cases** folder to view detailed manual test cases.
3. Access **Bug_Reports** for documented bugs, including steps to reproduce and resolutions.
4. Open **Postman** and import the **Postman Collection** for API testing.

## 🤝 Contributions

Feel free to contribute by:
- Adding new test cases.
- Reporting bugs or performance issues.
- Suggesting improvements to testing processes.

## 📜 License

This project is licensed under the MIT License. For more details, see the [LICENSE](LICENSE) file.
