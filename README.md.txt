# My Static Website on AWS

This project is my first hands-on cloud computing project, where I deployed a static website to AWS S3 using GitHub Actions for automated deployment.

## Project Goals
- Learn cloud basics: hosting, security, and automation
- Practice working with AWS services and GitHub Actions
- Gain practical experience beyond certifications

## Features
- Static website hosted on **AWS S3**
- **Automatic deployment** with GitHub Actions
- **AWS IAM** used for secure access
- Optional CloudFront CDN & HTTPS for global performance and security (future enhancement)

## Tools & Services
- AWS S3
- AWS IAM
- GitHub & GitHub Actions
- Optional: CloudFront, Route G53

## How It Works
1. Site files pushed to GitHub `main` branch
2. GitHub Actions workflow runs automatically
3. Files sync to the designated S3 bucket
4. Site updates go live instantly on AWS

## Next Steps / Future Work
- Add CloudFront for HTTPS and caching
- Use Route 53 to assign a custom domain
- Explore Terraform for fully automated infrastructure se

