# AWS S3 Static Website Hosting Project

## Project Overview
This project demonstrates hosting a static portfolio website using AWS cloud services with a custom domain.

## Architecture
User → Route53 → CloudFront → S3 Bucket

## Services Used
- Amazon S3
- Amazon CloudFront
- Amazon Route53
- GoDaddy Domain
- AWS Certificate Manager (HTTPS)

## Features
- Static website hosting
- CDN caching using CloudFront
- HTTPS secure access
- Custom domain integration
- Low latency global access

## Domain
ramyasiva.space

## Implementation Steps
1. Created static website using HTML, CSS
2. Created S3 bucket and enabled static website hosting
3. Uploaded website files into S3 bucket
4. Configured bucket policy for access
5. Created CloudFront distribution
6. Purchased custom domain from GoDaddy
7. Configured Route53 hosted zone
8. Updated GoDaddy nameservers
9. Mapped Route53 records to CloudFront

## Security Enhancement
Used CloudFront to securely deliver content and improve performance.

## Outcome
Successfully hosted portfolio website globally using AWS cloud services with custom domain access.
