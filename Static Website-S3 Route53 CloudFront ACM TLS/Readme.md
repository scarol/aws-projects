Utilized Amazon S3 and Route 53 to host a static website, directing HTTP custom domain URL requests to the S3 bucket containing the website files, where the S3 bucket configuration has the reference to the landing page, the index.html

Additionally, set up an Amazon CloudFront distribution to enforce HTTPS communication, employing a TLS certificate generated via AWS Certificate Manager (ACM).

Registered new DNS: skarol.click

Website URL : https://skarol.click/

Note: To see if CDN enforces secure access, try http and notice how the request redirects to https
