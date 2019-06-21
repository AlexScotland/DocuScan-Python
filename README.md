# DocuScan Package

DocuScan is a lightweight document scanner.

DocuScan allows users to open up document types docx,doc,pdf and return the information inside as strings.

DocuScan also allows for manipulation of this information via regular expressions.

Check out my other projects!

Installation:

run pip install DocuScan

import DocuScan

Usage:

class DocuScan('path/to/file/file.docx') to a variable.

use print(variable.returnFileText())

use print(variable.executeRegex('regex here'))

Functionality:

returnFileText() - Returns the text of a file.

executeRegex(regexExpression) - creates a list of all matching cases of regexExpression
