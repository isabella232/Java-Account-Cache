About
=====

This project provides methods for storing and accessing all of the videos in
a Brightcove account.

This project relies on the [Brightcove Commons open source libraries](https://github.com/BrightcoveOS/Java-Commons) and [Brightcove Media API Wrapper open source libraries](https://github.com/BrightcoveOS/Java-MAPI-Wrapper).

Documentation
=============

Coming soon - [JavaDocs](null)

Downloads
=========

**Version 4.1.6**:

Includes all fixes from Java-Commns and Java-MAPI-Wrapper 4.1.5 and 4.1.6.
Fundamentally changing the inner workings.  Rather than keeping everything in memory, metadata is saved off to files, and only the id/date indexes are kept around.
This has implications, including:
- Additional search features will be difficult (need to re-examine indexes if we decide to go that route)
- Memory usage is vastly decreased
- A lot of directories/files will be dropped to disk
- Performance will be vastly improved for some actions, slightly decreased for others


Full Download - including all Brightcove libraries:

- [BC Java Account Cache v4.1.6 - with dependencies](https://github.com/downloads/BrightcoveOS/Java-Account-Cache/bc-java-account-cache-4.1.6.zip)

Library Only:

- [BC Java Account Cache v4.1.6 - library only](https://github.com/downloads/BrightcoveOS/Java-Account-Cache/bc-java-account-cache-4.1.6.jar)


**Version 4.1.2**:

Fixing bugs with duplicate videos (same reference id).

Full Download - including all Brightcove libraries:

- [BC Java Account Cache v4.1.2 - with dependencies](https://github.com/downloads/BrightcoveOS/Java-Account-Cache/bc-java-account-cache-4.1.2.zip)

Library Only:

- [BC Java Account Cache v4.1.2 - library only](https://github.com/downloads/BrightcoveOS/Java-Account-Cache/bc-java-account-cache-4.1.2.jar)


**Version 4.1.0**:

This is the first release of this library - the version number corresponds
with the version of the commons and mapi wrapper libraries this relies on.

Full Download - including all Brightcove libraries:

- [BC Java Account Cache v4.1.0 - with dependencies](https://github.com/downloads/BrightcoveOS/Java-Account-Cache/bc-java-account-cache-4.1.0.zip)

Library Only:

- [BC Java Account Cache v4.1.0 - library only](https://github.com/downloads/BrightcoveOS/Java-Account-Cache/bc-java-account-cache-4.1.0.jar)


Latest Source
=============

You can check out the latest source code at the
[GitHub](https://github.com/BrightcoveOS/Java-Account-Cache) page; please
note that there is no guarantee of code usability or stability.