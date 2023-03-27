# Flutter Password Protected PDF Checker
Sometime we need to check whether the PDF is password protected or not without opening that PDF.
This plugin will help to identify this.


## Getting Started
```
final passwordProtectedChecker = PasswordProtectedPdfChecker();
// here you need to get Uint8List from PDF file and pass that into isPDFPasswordProtected()
final result = await passwordProtectedChecker.isPDFPasswordProtected(bytes);
```

