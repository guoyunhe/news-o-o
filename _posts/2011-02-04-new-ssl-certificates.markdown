---
author: No Content Found
date: 2011-02-04 17:48:53+00:00

layout: post
link: https://news.opensuse.org/2011/02/04/new-ssl-certificates/
title: "New SSL Certificates"
categories:
- Infrastructure
---
We will be updating our certificates for *.opensuse.org and *.suse.de today, sometime between 19:00 and 22:00 UTC.Â  We will be upgrading to a 2048 bit certificate, which will provide better security for the site.Â  We are also switching to a different vendor who can provide us more efficient support.Â  We plan on chaining the certificate up to the Entrust root CA.

It is possible that a small portion of the community may experience some issues with this switch.Â  Specifically, any system previous to SUSE 10 may not have the Entrust CA in its system certificate store.Â  For these systems, utilities such as wget may present an error when trying to pull a resource from opensuse.org over an SSL connection.Â  The solution is to either run wget with the "--no-check-certificate" option or to add the Entrust root to the system certificate store (found in /etc/ssl/certs).Â  Browsers and cURL use their own certificate store and should not be affected by this switch, even on older systems.

If anyone discovers an issue after we make the switch, please contact webmaster@opensuse.org.		
