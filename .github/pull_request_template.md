<!-- #### READ THIS FIRST ####

If you haven't yet, please read our guidelines:
https://github.com/publicsuffix/list/wiki/Guidelines#submit-the-change

If you'd like an example of what an excellent PR looks like
see https://github.com/publicsuffix/list/pull/615
-->

* [ ] Description of Organization
* [ ] Reason for PSL Inclusion
* [ ] DNS verification via dig
* [ ] Run Syntax Checker (make test)

* [ ] Each domain listed in the PRIVATE section has and shall maintain at least two years remaining on registration.

__Submitter affirms the following:__ 
  * [ ] This request was _not_ made to work around vendor limits other than those listed in rationale (see [Issue #1245](https://github.com/publicsuffix/list/issues/1245) as an example)
  * [ ] The [Guidelines](https://github.com/publicsuffix/list/wiki/Guidelines) were carefully _read_ and _understood_, and this request conforms
  * [ ] The submission follows the [guidelines](https://github.com/publicsuffix/list/wiki/Format) on formatting 

<!--

As you complete each item in the checklist please mark it with an X

Example:

* [x] Description of Organization

-->

Description of Organization
====

Organization Website: <!-- https://example.com -->

<!--
Please tell us who you are and represent (i.e. individual, 
non-profit volunteer, engineer at a business) and what you 
do (i.e. DynDNS, Hosting, etc)

For the org description, there is less interest in the 
promotional / marketing information about the org and more 
a focus on having concise description of the core focus of 
the submitting org, specifically with context/connection 
to this request.
-->

Reason for PSL Inclusion
====

<!--
Please tell us why your domain(s) should be listed in the PSL
(i.e. Cookie Security, Let's Encrypt issuance, IOS/Facebook, 
Cloudflare etc) and clearly confirm that any private section 
names hold registration term longer than 2 years and shall 
maintain more than 1 year term in order to remain listed.

Please also include the numbers of any past Issue # or PR # 
specifically related to this submission or section.
-->

DNS Verification via dig
=======

<!--
For each domain you'd like to add to the list please create
a DNS verification record pointing to your pull request.

For example, if you'd like to add example.com and example.net
you would need to provide the following verifications:

```
dig +short TXT _psl.example.com
"https://github.com/publicsuffix/list/pull/XXXX"
```

```
dig +short TXT _psl.example.net
"https://github.com/publicsuffix/list/pull/XXXX"
```

Note that XXXX is replaced with the number of your pull request.

We ask that you leave this record in place while you want 
your entry to remain in the PSL, so that future (TBD) 
automation can remove entries where the record is not present.

-->

make test
=========

<!--
Please verify that you followed the correct syntax and nothing broke

git clone https://github.com/publicsuffix/list.git
cd list
make test

Simply let us know that you ran the test
-->
