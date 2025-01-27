Version history
===============

3.1 (Sep 2019):

- Added compatibility for Elgg 3.x

3.0 (2016-12-12):

- added: plugin id to manifest
- added: a view to add selector as a dropdown
- changed: Elgg version requirement set to 2.0
- changed: moves JS to AMD, moves flags to simplecache
- fixed: some minor translation + encoding issue

2.0.1 (2015-07-08):

- changed: code style fixes
- changed: Update and rename README.txt to README.md
- fixed: line endings
- fixed: 'deprecated' warnings
- fixed: minor fixes (based on PHP notices)
- fixed: only allow language to change to an allowed language

2.0 (2012-03-16):

- added: plugin now Elgg 1.8 compatible

1.1 (2011-11-29):

- fixed: language completeness is now aware of translation_editor
- fixed: some plugin settings were not loaded correctly is some situations
- changed: moved some functions out of start.php
- changed: moved header extension to pagesetup
- changed: available languages are now cached (saving a lot of performance)

1.0.6 (2011-09-29):

- fixed: conflict with translation editor, causing custom translation not being loaded when loggedout

1.0.5:

- added: triggering an event when a loggedin user changes the language
	
1.0.4:

- fixed: secured action url for changing language (needed for Elgg 1.7)
	
1.0.3:

- added: flag for denmark (da)
- changed: flag for sweden (sv)
- fixed: cookie now set for correct path (/)
- fixed: issue with selecting languages for non logged in users (again)

1.0.2:

- fixed: issue with selecting languages for non logged in users
- added: flag for zh (chinese) language

1.0.1:

- added: flag for hebrew
- fixed: current language onclick action incorrect 
- fixed: dutch translations

1.0:

- first release