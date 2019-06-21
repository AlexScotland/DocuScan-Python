# DocuScan Package

DocuScan is a lightweight document scanner.

DocuScan allows users to open up document types docx,doc,pdf and return the information inside as strings.

DocuScan also allows for manipulation of this information via regular expressions.

[Check out my other projects!](https://github.com/mutster)


Installation:

1. run pip install DocuScan

2. import DocuScan


Usage:

1. class DocuScan('fileName') to a variable.

###It is worth noting that the fileName must be in the directory.

2. use print(variable.returnFileText())

3. use print(variable.executeRegex('regex here'))

4. use print(executeHeaderRegex('regex here'))

5. use print(executeFooterRegex('regex here'))

Functionality:

1. returnFileText() - Returns the text of a file.

2. executeRegex(regexExpression) - creates a list of all matching cases of regexExpression

3. executeHeaderRegex(regularExpression) - creates a list of all matching cases of regexExpression in the header XML.

4. executeFooterRegex(regularExpression) - creates a list of all matching cases of regexExpression in the Footer XML.
