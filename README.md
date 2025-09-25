# Host-a-static-website-on-aws-s3
This project hosts a static website on AWS S3. HTML and CSS files were uploaded using an IAM user with full S3 access. It showcases beginner-level cloud deployment skills and allows easy replication of the website setup.


## Project Overview

This project demonstrates how to host a static website using **Amazon S3**. It includes HTML and CSS files uploaded directly to an S3 bucket. The goal is to learn cloud hosting basics and understand how AWS S3 can serve static content.

## Features

* Fully static website (HTML + CSS)
* Hosted on Amazon S3
* Accessible via a public URL
* Easy to reproduce following the instructions

## Deployment Steps

1. Log in to your AWS account.
2. Create a new IAM user with full access of S3 bucket (bucket name must be globally unique).
3. Enable **Static Website Hosting** in the bucket properties.
4. Upload your website files (`index.html`) to the bucket.
5. Set the bucket policy or object permissions to **public read**.
6. Genrate a policy (get policy).
7. Access your website via the provided S3 endpoint URL.

## Notes

* An IAM user with **full S3 access** is required for uploading files.
* This project does **not** use any JavaScript; it’s purely HTML and CSS.


## License

This project is open-source and available for learning and experimentation.


