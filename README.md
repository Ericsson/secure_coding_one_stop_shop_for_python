# Secure Coding One Stop Shop for Python

Promote secure products by knowing the difference between secure compliant 
and non-compliant code with `CPython >= 3.9` using modules listed on 
[Python Module Index](https://docs.python.org/3.9/py-modindex.html)[Python 2023]. 

This page is in initiative by Ericsson to improve secure coding in Python by providing a location for study. Its structure is based on 
Common Weakness Enamurator (CWE) [Pillar Weakness](https://cwe.mitre.org/documents/glossary/#Pillar%20Weakness) [mitre.org 2023]. 
It currently contains *only* the code examples, documentation will follow.

# Disclaimer
Content comes WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, as stated in the license text [CC-BY-4.0](licenses/CC-BY-4.0.txt) for documentation and [MIT](licenses/MIT.txt).
Following or using the documentation and or code is at your own risk. Code examples are intended purely for educational use and not for products in parts or in full.
Code examples are NOT to be used to cause harm of any kind to anyone or anything. 


# Introduction
Every person writing code shall study the following:

* OWASP Secure Coding [Practices-Quick Reference Guide](https://owasp.org/www-project-secure-coding-practices-quick-reference-guide/) [OWASP 2022]
* OWASP Top 10 Report [OWASP 2022](https://owasp.org/www-project-top-ten/) [OWASP 2022]
* CWE Top 25 2022 [CWE 2022](https://cwe.mitre.org/top25/archive/2022/2022_cwe_top25.html) [MITRE 2023]

# Secure Coding Standard for Python
Code examples are written to explain security design with as little code as possible demonstrating the issue in the `noncompliantXX.py` titled Python file.
The `compliantXX.py` file demonstrates mitigation or removal of the only the described risk.
None of the code examples are intendet to be used 'as is' for production. Using the code is at your own risk. 

It is **not production code** and requires code-style or python best practices to be added such as:
* Inline documentation
* Custom exceptions
* Full descriptive variable names
* Line length limit
* Proper logging instead of printing to `stdout`
* Secure coding compliance outside of described issue

|<div style="width:500px">[CWE-664: Improper Control of a Resource Through its Lifetime](https://cwe.mitre.org/data/definitions/664.html)</div>|<div style="width:120px">Prominent CVE</div>|
|:----------------------------------------------------------------|:----|
|[CWE-134: Use of Externally-Controlled Format String](CWE-664/CWE-134/.)|[CVE-2022-27177](https://www.cvedetails.com/cve/CVE-2022-27177/),<br />CVSSv3.1: **9.8**,<br />EPSS:**00.37**(01.12.2023)|
|[CWE-400: Incorrect behavior order: Validate before Canonicalize](CWE-664/CWE-400/.)||
|[CWE-883: Deadlock](CWE-664/CWE-833/.)||

|<div style="width:500px">[CWE-707: Improper Neutralization](https://cwe.mitre.org/data/definitions/707.html)</div>|<div style="width:120px">Prominent CVE</div>|
|:----------------------------------------------------------------|:----|
|[CWE-117: Use of Externally-Controlled Format String](CWE-707/CWE-117/.)||
|[CWE-180: Incorrect behavior order: Validate before Canonicalize](CWE-707/CWE-180/.)||




# Biblography

|Ref|Detail|
|-----|-----|
|[Python 2023]|[3.9 Module Index](https://docs.python.org/3.9/py-modindex.html)|
|[mitre.org 2023]|[CWE - CWE-1000: Research Concepts](https://cwe.mitre.org/data/definitions/1000.html)|
|[OWASP 2022]|[Secure Coding Practices-Quick Reference Guide](https://owasp.org/www-project-secure-coding-practices-quick-reference-guide/)|
|[OWASP 2022]|[OWASP Top 10 Report 2022](https://owasp.org/www-project-top-ten/)|
|[MITRE 2023]|[CWE Top 25 2022](https://cwe.mitre.org/top25/archive/2022/2022_cwe_top25.html)|


# License
* [CC-BY 4.0](licenses/CC-BY-4.0.txt) for documentation
* [MIT](licenses/MIT.txt) for code snippets
