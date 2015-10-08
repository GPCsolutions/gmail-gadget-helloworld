Create a GMail gadget
=====================

Google Developers Console project
---------------------------------

Create a new project

Disable all APIs

Enable Google Apps Marketplace API

### Web application Client ID

Create a web application Client ID

### Metadata

- Name (max 15 chars)
- Description (max 200 chars)
- Individual install (bool)
- Icons (see assets)
- Support URLs (see assets)
- Oauth scopes
	- https://www.googleapis.com/auth/gmail.readonly
	- https://www.googleapis.com/auth/gmail.labels
- Universal Navigation extension
	- URL
- GMail Contextual gadget extension
	- Extractor URL: google.com:MessageIDExtractor
	- Gadget URL: https://gpcsolutions.fr/gadgets/hello_world_gadget.xml
	- Scopes
		- Mail - Message Ids

Assets
------

### Icon

PNG format

- 128x128
- 96x96
- 48x48
- 32x32

### Support URLs

#### Conditions d'utilisation

HTML format

Published URL

Debugging tips
--------------

Add ```&nogadgetcache=1``` to GMail URL to make sure the latest version is loaded, not a Google cached version.
