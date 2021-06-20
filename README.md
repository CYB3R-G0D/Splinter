# Splinter
## _An OSINT tool to scan subdomains of any websites_

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

This project is a fork of subdomain scanner build by [@x4nth055](https://github.com/x4nth055)

## Installation

Splinter requires python module _requests_

clone or download the project

```sh
git install 
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

```python sublist3r.py -h```

* To list subdomains of specific domain:

``python sublist3r.py example.com``

* To list subdomains of specific domain with custom subdomain list:

``python sublist3r.py example.com -l subdomains.txt``

* To list subdomains of specific domain and export result as text file:

``python sublist3r.py example.com -o filename.txt``