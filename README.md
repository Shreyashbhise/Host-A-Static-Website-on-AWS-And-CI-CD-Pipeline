# Host-A-Static-Website-on-AWS-And-CI-CD-Pipeline
![image](https://github.com/Shreyashbhise/Host-A-Static-Website-on-AWS-And-CI-CD-Pipeline/assets/108046802/49063417-8472-4d25-8511-1928a1d6025f)

    Static Website: You will create a static website (HTML, CSS, JavaScript, and any other assets) that you want to host on AWS. The website can be as simple or complex as you like, and it should have its own Git repository for version control.

    AWS Services: Utilize various AWS services to deploy and host your static website:

        Amazon S3 (Simple Storage Service): Use S3 to store and serve your website's static files. Create an S3 bucket and configure it for static website hosting.

        Amazon Route 53: Register a domain or use an existing one, and configure DNS records to point to your S3-hosted website.

        AWS Identity and Access Management (IAM): Set up IAM roles and permissions to securely manage access to your AWS resources.

        Amazon CloudFront (optional): Implement a CDN (Content Delivery Network) using CloudFront to distribute your website content globally for improved performance.

    CI/CD Pipeline: Implement a CI/CD pipeline to automate the deployment of your static website to AWS:

        Version Control: Use Git for version control and host your project's repository on a platform like GitHub, GitLab, or AWS CodeCommit.

        Continuous Integration (CI): Set up CI triggers to build and test your website code automatically whenever changes are pushed to the repository.

        Continuous Deployment (CD): Automate the deployment of your website to AWS S3 and, if using CloudFront, create mechanisms to invalidate the cache when new content is deployed.

        CI/CD Tools: You can use popular CI/CD tools like Jenkins, Travis CI, CircleCI, AWS CodePipeline, or GitHub Actions to create and manage your pipeline.

    Testing: Ensure your CI/CD pipeline includes testing and quality checks to catch any issues before deploying to production.

