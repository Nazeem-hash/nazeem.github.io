# AWS Static Website Hosting

![Architecture Diagram](images/static_website_hosting_drawio.png)

## Project Overview
Hosted a static portfolio website using:
- **AWS S3** for storage and static hosting
- **CloudFront** for global CDN and HTTPS

## Key Steps Implemented
1. Created S3 bucket with static website hosting enabled
2. Configured bucket policy for public read access
3. Set up CloudFront distribution with:
   - HTTPS enforcement
   - Optimal caching settings
4. Verified global accessibility

## Results
- Achieved <500ms load times globally via CloudFront
- Secured site with automatic SSL certificate
- Reduced costs by using S3 static hosting instead of EC2

[View Live Demo](https://d22mk5odvvaxap.cloudfront.net/) | 
[Back to Portfolio](../)
