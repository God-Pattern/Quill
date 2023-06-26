# Quill Editor Server-Side Request Forgery

## Description

A vulnerability in the HTML editor of Slab Quill 1.3.7 allows an attacker to execute SSRF Payloads by storing an arbitrary video URL (a crafted SRC attribute of an IFRAME element) in a text field. 

## Affected Versions

Quill Versions <=1.3.7 or All Versions.

## Vendor of Product

https://quilljs.com/

## References

https://github.com/quilljs/quill/issues/3813
https://github.com/God-Pattern/QuillJS/blob/main/Server-Side%20Request%20Forgery.md
