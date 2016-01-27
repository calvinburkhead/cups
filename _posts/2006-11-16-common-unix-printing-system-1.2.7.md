---
title: Common UNIX Printing System 1.2.7
layout: post
---

<P>CUPS 1.2.7 is now available for download from the CUPS web site at:</P>
- Documentation updates (<A HREF="http://www.cups.org/str.php?L2089">Issue #2089</A>)
- The PostScript filter now rotates the bounding box values as needed (<A HREF="http://www.cups.org/str.php?L2079">Issue #2079</A>)
- The scheduler no longer loads the remote printer cache when browsing is disabled (<A HREF="http://www.cups.org/str.php?L2084">Issue #2084</A>)
- The scheduler no longer writes a new launchd configuration file if it doesn't have to (<A HREF="http://www.cups.org/str.php?L2083">Issue #2083</A>)
- Updated the USB and PAP backends for Mac OS X (<A HREF="http://www.cups.org/str.php?L2086">Issue #2086</A>)
- The scheduler now picks up on changes to IPv6 and DNS configuration on Mac OS X (<A HREF="http://www.cups.org/str.php?L2085">Issue #2085</A>)
- The lpstat program could still hang (<A HREF="http://www.cups.org/str.php?L2098">Issue #2098</A>)
- Fixed an inefficiency in the SNMP IPP detection code (<A HREF="http://www.cups.org/str.php?L2100">Issue #2100</A>)
- The SSL negotiation code did not implement short timeouts (<A HREF="http://www.cups.org/str.php?L2091">Issue #2091</A>)