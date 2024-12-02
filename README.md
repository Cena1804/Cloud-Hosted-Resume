# AWS-Resume-Hosting

A step-by-step guide to build and host a professional online resume using HTML, CSS, and JavaScript, deployed with AWS services like S3, Route 53, CloudFront, and ACM.

## Features
- Static resume website.
- Custom domain with SSL/TLS encryption.
- Hosted on AWS with scalable architecture.

## Project Structure
- `index.html`: The main HTML file for your resume.
- `styles.css`: CSS styles for the resume.
- `script.js`: JavaScript for interactivity.

## Deployment Steps
### 1. Set Up an S3 Bucket
- Log into the AWS Management Console.
- Create a public S3 bucket.
- Enable static website hosting and upload project files.

### 2. Configure Route 53
- Purchase a domain or use an existing one.
- Set up a hosted zone and update your DNS records.

### 3. Add SSL/TLS with ACM
- Use AWS Certificate Manager to request a public certificate.
- Validate via DNS.

### 4. Set Up CloudFront
- Create a CloudFront distribution pointing to the S3 bucket.
- Attach the SSL certificate and configure caching.

### 5. Test Your Website
- Access your resume via the CloudFront distribution's domain or custom domain.

## License
MIT
