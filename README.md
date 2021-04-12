# CDNself
Host your own Content Delivery System/Network on your own server. Recommended Server Software: cPanel
## Installation
1. Go to your cPanel or equivalent.
2. Create a subdomain as: ``cdn.yourdomain.tld``
3. Upload the CDN files to the folder called ``cdn.yourdomain.tld`` (in cPanel or try and find the equivalent for yours if you don't have cPanel).
4. Edit the areas on the ``index.php`` that have the lables: ``<!-- EDIT THIS \/ -->`` and do not edit anything in ``upload.php``.

## How to find the file's link
All uploads are sent to a folder called ``uploads`` so you can find the link as ``cdn.yourdomain.yld/uploads/file.filextension``.
If you changed the name of the ``uploads`` folder then the system will not work and we will have a guide to help you change it later on.

## What is this to be used for?
This is a low-scale CDN system that may not be able to handle high-traffic usage. 
You can use it for personal use and commercial but you will have to limit the amount of uses it gets per min.

## Support
Please use the ``Issues`` page for questions and also issues.
