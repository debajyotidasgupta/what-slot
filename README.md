# what-slot
[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)       
[![Gitter](https://img.shields.io/gitter/room/:user/:repo.svg)](https://gitter.im/WhatSlotChat/Lobby) [![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)    
[![KWoC 2018](https://img.shields.io/badge/KWoC-2018-0078D6.svg?style=for-the-badge&longCache=true&logo=data:image/png;base64,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)](https://kwoc.kossiitkgp.org/)

     
Organize your time table for additional courses and minor.

## Usage
Currently hosted at [https://whatslot.metakgp.org/](https://whatslot.metakgp.org/)

NOTE: The `master` branch is automatically deployed as an heroku app on the above link.

## Updating for new semester
* Set the environment variable `JSESSIONID` to the cookie of same name by `export JSESSIONID=<session ID>`. The `JSESSIONID` cookie is generated when you visit the academic section in ERP while you are logged in. This can be grabbed from the network requests in your chrome debugger, just open network tab in it and click on academic, then see the request for cookies and copy JSESSIONID.

* Replace the data that have been marked as `xxx` in the headers (as shown below) in the `fetch.py` file by the data that have been grabbed from the cookies as described above for the JSESSIONID.
```python
headers = {
	'Cookie' : 'JSESSIONID=xxx; \
	ssoToken=xxx; \
	JSID#/IIT_ERP3=xxx; \
	JSID#/ERPAccounts=xxx; \
	JSID#/Acad=xxx'
}
```

* `NOTE:` If you are using some cookie handler or chrome extensions for the cookie you will directly get this cookie data from there

* Update `for_session` and `for_semester` (line no. 16 and 17) with the updated details, in `fetch.py`.

* Run `JSESSIONID=[JSESSIONID TAKEN FROM CHROME] python3 fetch.py`, and if all went well you should see a list of subjects being fetched for each department (please install dependencies before this step from requirements.txt or Pipenv). Note that no square brackets should be there in the actual command around JSESSION grabbed from chrome.

* After script has finished executing, the app is ready to be deployed once again for the new semester.

## Runnning locally
1. `git clone https://github.com/metakgp/what-slot.git`
2. `cd what-slot`
3. `pipenv shell --three`
4. `pipenv install` (Only the first time)
5. `python3 app.py`

## Communication
[Gitter](https://gitter.im/WhatSlotChat/Lobby)
