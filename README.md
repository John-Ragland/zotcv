# zotcv

[![PyPI - Version](https://img.shields.io/pypi/v/zotcv.svg)](https://pypi.org/project/zotcv)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/zotcv.svg)](https://pypi.org/project/zotcv)

-----

A tool for auto-populating a CV from Zotero citations.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Installation
clone directory from github, and install with pip
```console
git clone <url to package>
cd zotcv
pip install .
```

### initialize zotero library
you need to initialize you zotero library credentials.
```console
init_zotcv
```
You can then supply your credentials to the prompt. The following information is required:
- Library ID : 
- Library Type : [group or individual]
- API Key : you can set this in your online account to zotero. Best practice is to make this a read only key.
- Subcollection IDs : these can be found in the URL of the sub-collections through online zotero access
	- Talks Collection ID 
	- Publications Collection ID
	- Theses Collection ID
	- Invited Talks Collection ID

These variables are written to src/zotcv/config.ini. 

## Usage
For now, the markdown CV templates are combined with personal information to include in the CV.
In future work, these will be separated.


### update_cv


## License

`zotcv` is distributed under the terms of the [MIT](https://spdx.org/licenses/MIT.html) license.
