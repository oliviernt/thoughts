# Creating a REST API with AWS API-Gateway and Lambda

I recently attended AWS Summit Berlin and really enjoyed it a lot. It gave us (two of my colleagues attended with me) new ideas and provided insights in unknown or not well known services provided by Amazon.

One of the major topics was serverless and while I did already know about it in theory it was nice to learn more about Lambda & Co. in a few highly interesting talks. One of those talks was [Think Big - Scaling Seamlessly to Millions of Devices with Serverless Architectures](http://presentations-berlin-summit-2017.s3-website.eu-central-1.amazonaws.com/NGA1-5_AWS_Fuhrmann_ThinkBig_Serverless.pdf) by Dr. Thomas Fuhrmann. It was really well presented and I very much enjoyed listening to it.

But it all sounded so easy and frictionless. Is it really possible to setup web services in minutes?

I was really curious to find out. So when we decided to visit my in-laws over the weekend I though why not try it out.

So here's a description of the actual required steps to setup a REST API in a few minutes:

## a) Register to AWS

You will first have to have an AWS account. So head over to (https://aws.amazon.com/) and register for a free account. The free account will allow you test and play around AWS for free for about a year (it actually depends a lot on what service you will be using and how much you'll be using it).

## b) Setup your account for security

If you just registered to AWS I'd really recommend you follow their security best-practices:

1. Activate MFA (multi-factor authentication) on your root acount
2. Create individual IAM users
3. Use groups to assign permissions
4. Apply an IAM password policy
5. Rotate your access keys

Once you've done that you may get started with setting up your API.

## 1. 

...
