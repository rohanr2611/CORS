Instructions to establish CORS configuration for Static Website Hosting using Amazon S3:

Find detailed article at https://medium.com/@rohanrajsisodia/static-website-hosting-using-cors-cross-origin-resource-sharing-a80766dd9568
Steps to use files in this repository:

1. Copy index.html in the origin/ primary bucket.
2. Copy extra.html in the cross-origin bucket.
3. Copy the contents of CORS.txt to the cross-origin bucket CORS configuration. Remember to update AllowedOrigin to have Endpoint URL of the origin bucket.
