# DocuScan Package

DocuScan is a lightweight document scanner.

DocuScan allows users to open up document types docx,doc,pdf and return the information inside as strings.

DocuScan also allows for manipulation of this information via regular expressions.

[Check out my other projects!](https://github.com/mutster)


Usage:

1. pip install DocuScan

2. import DocuScan_pkg

  Class DocuScan has 2 functions:
    returnFileText(self) - Takes the file that was called when making the class, converts and returns string.
    
   executeRegex(self, regularExpression) - Calls returnFileText, and applies specified regular expression the the text.  Returns results in a list.
