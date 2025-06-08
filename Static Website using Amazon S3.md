**Overview:** This project shows how to build and host a  **static website** using **Amazon S3** (Simple Storage Service).
_________________________________________________________________________________________________________________________________________________
**Features:**
 A basic `index.html` file with:
- “Hello world”
- “I am hosted on Amazon S3”
- An image
_________________________________________________________________________________________________________________________________________________
**HTML Code: **
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Hello from S3</title>
</head>
<body>
  <h1>Hello world</h1>
  <p>I am hosted on Amazon S3</p>
  <img src="Cat.jpg">
</body>
</html>
_________________________________________________________________________________________________________________________________________________
**Code used for bucket policy.  This allows everyone to read/view everything in the bucket.**

{
    "Version": "2012-10-17",
    "Statement": [
    	{
        	"Sid": "PublicReadGetObject",
        	"Effect": "Allow",
        	"Principal": "*",
        	"Action": [
            	"s3:GetObject"
        	],
        	"Resource": [
                "arn:aws:s3:::Bucket-Name/*"
        	]
    	}
    ]
}
_________________________________________________________________________________________________________________________________________________
**Key Achievements:**
- Successfully Hosted a Website on AWS S3
- Deployed a fully functional static website using Amazon's cloud storage platform.
- Gained hands-on experience with cloud-based web hosting.
- Configured Static Website Hosting.
- Enabled and correctly configured Amazon S3 static website hosting settings.
- Understood how to serve content over the web using AWS infrastructure.
- Implemented Public Access and Permissions.
- Applied correct bucket policies to allow public access to static files.
- Learned how to manage security and access controls in AWS.
- Built a Clean HTML Web Page.
- Created a responsive, minimal HTML site with text and image content.
- Integrated External or Self-Hosted Images.
- Added dynamic content (a cat image) using either an external URL or an uploaded asset.
- Navigated the AWS Management Console for creating and configuring resources.
- Delivered a zero-cost, publicly accessible website without traditional web hosting.
_________________________________________________________________________________________________________________________________________________
**Output:**
![image](https://github.com/user-attachments/assets/035bfdf8-f2ae-4cf9-ae15-11a7a7e0fc6d)


