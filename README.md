# Serverless Vector Tiles on AWS
This tutorial and accompanying presentation is based on a talk I gave at [FOSS4G 2018 in Tanzania](https://2018.foss4g.org/) and will cover off the following tasks:

1. Host a simple webpage on AWS (Hello S3!)
2. Host the webpage from our own domain (Hello Route 53!)
3. Create a free HTTPS cert for our domain (Hello ACM!)
4. Publish our simple webpage to a CDN with SSL support (Hello CloudFront!)
5. Add a map (Hello Vector Tiles!)
6. Publish ready-made OSM tiles to S3/CloudFront
7. Publish our own geo data to S3/CloudFront

Once complete you should have something like this running on your own domain on AWS and costing you next to nothing to host!

![My Serverless Vector Tiles Map](https://github.com/addresscloud/serverless-tiles/raw/master/demo2.gif)

You can play around with this yourself at the [Demo Site](https://www.myvectortiles.xyz/)

### Pre-Requisites

-	An AWS account
-	A domain name that can be used for the exercise (this will need to be re-pointed so make sure it is not being used for anything else!). namecheap.com have domains starting at $0.48 per year but make sure you switch off auto-renew!
-	Patience – there is a lot of AWS config to make this work and no sign of a map until Step 5 but this will be worth it, trust me

### Materials

There are a lot of steps involved and a lot of new concepts to learn and so the recommended approach is to [Download the Tutorial](https://github.com/addresscloud/serverless-tiles/raw/master/Serverless%20Vector%20Tiles%20on%20AWS.pdf) and work through this in order as each step builds on the last and a small oversight in config earlier on could easily cause problems later.
