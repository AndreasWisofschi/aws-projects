**Project #1: Host a website on AWS**
**http://andreas-portfolio.com/****

      Step #1: Design Your Website
        Designed own personal website including resume, links -> LinkedIn, GitHub, and website
      
      Step #2: Set Up Amazon S3 Bucket
        Go to the AWS Management Console and open the Amazon S3 console.
        Click "Create bucket" and enter a unique name for your bucket.
        In the "Properties" section, enable "Static website hosting."
        Upload your website files to the bucket.
        Set the bucket permissions to allow public access.
      
      Step #3: Purchase a Custom Domain through Amazon Route 53
        Open the Amazon Route 53 console.
        Choose "Domain registration" and then "Register domain."
        Follow the prompts to purchase your custom domain.
        In the "Route 53 hosted zones," create a new record set.
        Enter your S3 bucket's endpoint as the alias target.

In summary: 
      1. Created custom domain name using Route 53
      2. Used Amazon S3 Bucket to host a sample website
      3. Enable static website hosting and direct the domain to the S3 Bucket.

![image](https://github.com/AndreasWisofschi/aws-projects/assets/46462329/d66739d7-3c62-4f2f-ad7d-edd53660e9de)



**Project #2: Visualize Data using Amazon QuickSight**

      Step #1: Download the Dataset
            Navigate to 2-s3-quicksight to download the "Amazon Bestseller Dataset" CSV file and the "manifest.json" file.
            Click on "raw" and Control+S to save both files onto your computer.
            
      Step #2: Store the Dataset in Amazon S3
            Open the Amazon S3 console and click "Create Bucket."
            Name the bucket (e.g., "lucy-amazon-project") and keep the settings as default.
            Upload the CSV file and the "manifest.json" file into the bucket.
            Replace the URL in the "manifest.json" file with the S3 URL of your dataset.
            
      Step #3: Connect S3 Bucket with Amazon Quicksight
            Open the AWS management console and navigate to Amazon Quicksight.
            Sign up for a free trial of the Enterprise edition if you don't have an account.
            Select Amazon S3 and tick the box for the S3 bucket you created.
            Enter the link to your "manifest.json" file and connect to Quicksight.
            Select "interactive sheet" to start creating visualizations.
            
      Step #4: Create Visualizations
            Drag fields into the graph to create visualizations (e.g., Most popular brands).
            Sort, filter, and customize the graphs as desired.
            Experiment with different types of graphs like bar charts, pie charts, line graphs, etc.














      
