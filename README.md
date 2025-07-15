
# 🧪 SoapUI Test Project

This project contains automated tests for web services using **SoapUI Open Source**. It is designed to validate SOAP endpoints through structured and executable test cases from the command line.
## ⚙️ Tools used

- [SoapUI Open Source](https://www.soapui.org/)
- PowerShell / CMD for CLI execution
- HTML Reports for manual viewing

## 🚀 Execution from CLI

You can run the test cases and generate reports with the following command:

``` powershell
& "C:\Program Files\SmartBear\SoapUI-5.7.0\bin\testrunner.bat" `
  -s"TestSuite 1" `
  -c"GetUser" `
  -r -j `
  -f"C:\Users\youruser\soapui" `
  "C:\Users\youruser\soapui\miProyecto-soapui.xml"
```
## 👨‍💻 Autor

Renzo Steven Medina Olaya
Backend Developer transitioning into DevOps

