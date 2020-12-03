## The website conetent is in web-content dir.

## The screenshots can be found in screenshots dir. 

## static website can be browsed at 
 d2fxiuejn9qe9a.cloudfront.net

## The following steps is performed for hosting static website to s3.
1. Created a s3 bucket.
2. Uploaded file to s3 bucket.
3. The permission access to the bucket is configured to allow public access.
4. The IAM policy is set to allow only read access for content in bucket.
5. The s3 bucket is configured to host static website.
6. Cloudfront is configured with all edge location for content distribution.