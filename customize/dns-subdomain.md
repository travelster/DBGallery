---
layout: default
title: Your own URL
permalink: /dns-subdomain
parent: Tayloring DBGallery
grand_parent: DBGallery
nav_order: 3
---

# Your own URL

Create your own URL, such as **yourcompany.dbgallery.com** or **digitalassets.yourcompany.com**, by specifying a subdomain of your choice. It may also be a top level domain, such as OurImages-YourCompany.com.  This relates to Enterprise subscriptions and on-premise systems only.  It requires just two small changes:
<ol>
<li>A simple IIS configuration entry.</li>
<li>A DNS entry specifying the subdomain.  The DNS entry is always made on your side, pointing to our server (for Enterprise subscriptions) or to your server (for on-prem installations).  The DNS entry may be an A name or C name (for static IPs a A name is best, if a dynamic IP a C Name is likely better).</li>
</ol>

Once a name has been decided upon, contact us for help with setting this up.