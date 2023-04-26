# AWS-Project#1

# Migrating a Static Website to AWS S3

This project demonstrates how to migrate a simple static website to Amazon Web Services (AWS) using Amazon S3 for hosting.

## Project Steps

1. **Choose a simple static website**: Select a basic static website with HTML, CSS, and JavaScript files. If you don't have one, create a new one or use an existing template from sources like HTML5 UP or Start Bootstrap.

2. **Set up an AWS account**: If you don't already have one, sign up for an AWS account. You'll get access to AWS Free Tier services for a limited period, which is useful for learning purposes.

3. **Create an Amazon S3 bucket**: Log in to the AWS Management Console, navigate to Amazon S3, and create a new bucket. Make sure to select a unique name for your bucket and choose the appropriate region.

4. **Enable static website hosting**: In the S3 bucket's properties, locate the "Static website hosting" option and enable it. Set the "Index document" to your website's main HTML file, usually "index.html". You'll also receive a public endpoint (URL) for your website.

5. **Upload your website files**: Using the S3 management console or AWS CLI, upload the static files (HTML, CSS, and JavaScript) to the S3 bucket. Make sure to set the access permissions for these files to "public".

6. *(Optional)* **Set up a custom domain**: If you want to use a custom domain for your website, you can use Amazon Route 53. Register a new domain or configure an existing one to point to your S3 bucket. You'll need to create a new hosted zone and update the DNS settings with your domain registrar.

7. *(Optional)* **Configure a Content Delivery Network (CDN)**: To improve the performance of your website, you can use Amazon CloudFront to distribute your content. Create a new CloudFront distribution, set the S3 bucket's static website hosting URL as the origin, and configure caching settings. Update your DNS records (if using a custom domain) to point to the CloudFront distribution's domain name.

8. **Test your website**: Visit the public URL provided by S3 or your custom domain if you set one up. Ensure that your website is fully functional and that all assets are loading correctly.

