# Image Resizer
Simple html page that will resize an image.

Simply host this html file on a public web server. You can then pass three parameters to the url: width, height, and imageurl. For example, I've hosted this on AWS S3 (https://docs.aws.amazon.com/AmazonS3/latest/userguide/WebsiteHosting.html) in the example below

https://flerlage-apps.s3.us-east-2.amazonaws.com/resize.html?height=84&width=200&imageurl=https://flerlage-apps.s3.us-east-2.amazonaws.com/logo.png


# Twitter Embedder
Simple html page that will load a tweet in a way that is embeddable via simple URL (useful for Tableau).

Simply host this html file on a public web server. You can then pass two parameters to the url: id (the tweet ID), width (Twitter has a min width of 250 and max of 550 px). For example, I've hosted this on AWS S3 in the example below

https://flerlage-apps.s3.us-east-2.amazonaws.com/twitterembed.html?width=500&id=1381584193579270144

Base code borrowed from https://www.labnol.org/code/19933-embed-tweet-with-javascript

You can also make changes to other parameters in the code (or parameterize them) according to https://developer.twitter.com/en/docs/twitter-for-websites/embedded-tweets/guides/embedded-tweet-parameter-reference


# Hex Color Embedder
Simple html page that will embed a set of hex color codes using coolors.com. This is done in a way that is embeddable via simple URL (useful for Tableau).

Simply host this html file on a public web server. You can then pass one parameter which inludes a dash-separated list of hex color codes. For example, I've hosted this on AWS S3 in the example below

https://flerlage-apps.s3.us-east-2.amazonaws.com/color.html?codes=3b0102-762b2c-b6443f-c67d58-f5d6b1-fff8dc
