
## world wide web consortium validator W3C 

The Markup Validation Service is a validator by the World Wide Web Consortium (W3C) that allows Internet users to check pre-HTML5 HTML and XHTML documents for well-formed markup against a document type definition. Markup validation is an important step towards ensuring the technical quality of web pages. However, it is not a complete measure of web standards conformance.[1] Though W3C validation is important for browser compatibility and site usability, it has not been confirmed what effect it has on search engine optimization.

As HTML5 has removed the use of DTD in favor of a "Living Standard", the traditional Markup Validation Service is not applicable to these formats. Validation is instead performed using an open-source "Nu Validator", an instance of which is provided by W3C.

W3C validator for Holberton School

https://validator.w3.org/nu/


Requirements
Python 3
Requests: HTTP for Humans™
Quickstart
Clone this repo
git clone https://github.com/holbertonschool/W3C-Validator.git
Run the validator command from within
Single file:

./w3c_validator.py index.html
./w3c_validator.py css/styles.css
Multiple files:

./w3c_validator.py index.html article.html css/styles.css
All errors are printed in STDERR; Exit status = # of errors (0 on success)

Troubleshooting
Error: bad interpreter: No such file or directory If you get this error you might not have Python installed correctly; or the system PATH might not be updated to reflect the installed Python version.
Assuming that Python 3 is indeed installed, you can try to run it like so:

python3 w3c_validator.py index.html
Error: ModuleNotFoundError: No module named 'requests' If you get this error you do not have the module requests installed in your system.
You can install requests using pip:

python3 -m pip install requests

