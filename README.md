# Splinter
## _An OSINT tool to scan subdomains of any websites_

This project is a fork of subdomain scanner build by [@x4nth055](https://github.com/x4nth055)

## Installation

Splinter requires python module _requests_

clone or download the project

```sh
git clone https://github.com/CYB3R-G0D/Splinter
```

Install _requests_

```sh
pip3 install requests
```

## Usage

Short Form    | Long Form     | Description
------------- | ------------- |-------------
-l            | --wordlist    | Domain name to list subdomains of
-t            | --num-threads | Number of threads to use for subbrute bruteforce
-o            | --output      | Save the results to text file
-h            | --help        | show the help message and exit

### Examples

* To list all the basic options and switches use -h switch:

```python main.py -h```

* To list subdomains of specific domain:

``python main.py example.com``

* To list subdomains of specific domain with custom subdomain list:

``python main.py example.com -l subdomains.txt``

* To list subdomains of specific domain and export result as text file:

``python main.py example.com -o filename.txt``
