# i-shall-not-read
A Chrome/Firefox extension that show you Facebook post estimated reading time before having to open them.

### The main focus of this project is to detect facebook application dynamic changes:
* Detection of new posts being added to the news feed
* Add an observer to each loading post to determine when post finish loading 
* Implement background process that listens to URL changes and emits events to content script
* Initialization and termination of event listeners and observers when switching between pages

The project is proven to be especially challenging as facebook use no AJAX call to navigate its UI and provide no API for detecting change event.
