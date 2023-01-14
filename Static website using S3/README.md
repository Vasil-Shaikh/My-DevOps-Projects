# About
This is a sample project created using AWS services like S3, Route 53, ACM, Cloudfront. 


## High Level Diagram

![App Screenshot](https://miro.medium.com/max/828/1*8RKcmo1W0518aFBjKk5LbQ.webp)

## Usage/Examples

```<html xmlns="http://www.w3.org/1999/xhtml" >
<head>
    <title>My Website Home Page</title>
</head>
<body>
  <h1>Welcome to my website</h1>
  <p>Now hosted on Amazon S3!</p>
</body>
</html>
```
You can use Amazon S3 to host a static website. Static websites deliver #HTML, javascript, images, video, and other files to your website visitors and contain 𝗻𝗼 server-side application code like PHP or ASP.NET.

To use S3 for a static website, you simply #upload files to the S3 bucket and configure your S3 bucket for Web hosting. The Steps involved in this are:

𝗦𝘁𝗲𝗽 1: 𝗖𝗿𝗲𝗮𝘁𝗲 a bucket <br>
𝗦𝘁𝗲𝗽 2: 𝗘𝗻𝗮𝗯𝗹𝗲 Static Website hosting.<br>
𝗦𝘁𝗲𝗽 3: 𝗘𝗱𝗶𝘁 access settings.<br>
𝗦𝘁𝗲𝗽 4: 𝗔𝗱𝗱 a bucket policy to make the bucket content publicly available. (refer the below link to copy the bucket policy)<br>
https://docs.aws.amazon.com/AmazonS3/latest/userguide/WebsiteAccessPermissionsReqd.html#bucket-policy-static-site<br>
𝗦𝘁𝗲𝗽 5: 𝗖𝗼𝗻𝗳𝗶𝗴𝘂𝗿𝗲 an index document. (Create an index.html file on your desktop refer the below link, and upload it to the S3 bucket)<br>
https://docs.aws.amazon.com/AmazonS3/latest/userguide/IndexDocumentSupport.html#configuring-index-document<br>
𝗦𝘁𝗲𝗽 6: 𝗖𝗼𝗻𝗳𝗶𝗴𝘂𝗿𝗲 an error document(optional)<br>
𝗦𝘁𝗲𝗽 7: 𝗧𝗲𝘀𝘁 your website endpoint<br>
𝗦𝘁𝗲𝗽 8: 𝗖𝗹𝗲𝗮𝗻𝘂𝗽<br>

