# Norman's Personal website
A website to view the work experiences and achievements of Lim Xing Kang norman

Built using this [guide](https://docs.aws.amazon.com/AmazonS3/latest/userguide/WebsiteHosting.html)

## Visit the site
See the website [normanlim.frenoid.com](https://normanlim.frenoid.com/) and [normanlim.com](https://normanlim.com)

## How to deploy
This website is deployed using AWS Amplify using manually deployments

### Steps to deploy
1. Upload files and assets to `s3://normanlimxk.com` or using the [AWS S3 console](https://ap-southeast-1.console.aws.amazon.com/s3/buckets/normanlimxk.com?region=ap-southeast-1&tab=objects)
2. Go to [AWS Amplify App Page](https://ap-southeast-1.console.aws.amazon.com/amplify/apps/d30vkfxoz9ztim/overview)
3. Click on `Deploy updates`
4. Click on `Amazon S3`
5. Enter `s3://normanlimxk.com/` into the field `S3 location of objects to host`
6. Click on `Save and deploy`
