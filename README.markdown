## chrome-tellTaleTab-rehash
This is a remake of Tell-Tale Tab by chet.luther to repair the problems caused by the 2.0.0 release. I think that this has solved the problems, but I can make no guarantees!

Simplified notification extension for a small but growing number of sites. Inspired by shikakaa's Gmail Favicon Alert extension, the notifications that there is something new of interest in the application's tab is done by the tab's favicon rather than taking up precious space in the "uber-bar."

### Currently Supported Sites
* Gmail & Hosted Gmail
* Google Reader
* Google Wave
* Netvibes
* Facebook
* Twitter
* Google Voice

### TODO -At the moment, I do not plan to continue developing this extension, I simply wanted to make a working release. Chet's original list:
* Google Calendar
* Meebo
* MySpace
* Plurk

### Changelog
* `2.0.1 - 02/01/2010`  
    Forked chet.luther's source to create the rehash.
	Removed SugarCRM support (this had a wide filter that I was not comfortable releasing).
	Added Google Voice support
	Tested to ensure the memory leaks did not continue. (No promises, but this seems to be working for me!)

* `2.0.0 - 01/17/2010`  
    Rearchitecture for better performance and ease of extensibility.
    Added Hosted Gmail support (thanks WayneD!)

* `1.1.0 - 01/04/2010`  
    Added SugarCRM support.

* `1.0.0 - 01/03/2010`  
    Added Facebook and Twitter support.

* `0.9.1 - 01/03/2010`  
    Made the indicators a bit more pleasing to the eye.

* `0.9.0 - 01/02/2010`  
    Added support for Netvibes.

* `0.8.1 - 01/02/2010`  
    Fixed 20 item limit on Google Reader.

* `0.8.0 - 01/01/2010`  
    Added support for Google Wave.

* `0.7.1 - 01/01/2010`  
    Removed 0 count when no unread items.

* `0.7.0 - 12/31/2009`  
    Initial release supporting Gmail and Google Reader.
