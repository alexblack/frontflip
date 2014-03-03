frontflip
=========

## Frontflip Service
This is the backend service that enables someone to inject templates into a site and preview changes live.

## Frontflip website
We'll have a website http://frontflip.io where users can try out the service, eg get a dropbox folder where they can make changes to http://frontflip.io and see those changes live using a preview url.

## Site integration
We'll use the service on frontflip.io itself. 

 <script src="http://frontflip.io/ffs.js" />
 
## Workflow
* User arrives at frontflip.io website
* User signs in with dropbox account
* A folder is shared with them, the folder contains the CSS and templates for frontflip.io
* They are given a preview url, eg http://frontflip.io?p=12345
* Any changes they make in the dropbox folder can be seen live at the preview url
