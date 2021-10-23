# Image Resizer
Simple html page that will resize an image.

Simply host this html file on a public web server. You can then pass three parameters to the url: width, height, and imageurl. For example: https://flerlageapps.com/resize.html?height=420&width=1000&imageurl=http://flerlageapps.com/logo.png

# Image Embeder
Simple html page that will display an image. Some image sites, such as imgur, won't allow embedding via iFrame (which Tableau uses for web objects). This allows yout to pass a URL of the image, then display it, bypassing that limitation.

Simply host this html file on a public web server. You can then pass one parameter to the url: imageurl. For example: hhttps://flerlageapps.com/image.html?imageurl=https://i.imgur.com/4GK14iv.png


# Twitter Embedder
Simple html page that will load a tweet in a way that is embeddable via simple URL (useful for Tableau).

Simply host this html file on a public web server. You can then pass two parameters to the url: id (the tweet ID), width (Twitter has a min width of 250 and max of 550 px). For example: https://flerlageapps.com/twitterembed.html?width=500&id=1381584193579270144

Base code borrowed from https://www.labnol.org/code/19933-embed-tweet-with-javascript

You can also make changes to other parameters in the code (or parameterize them) according to https://developer.twitter.com/en/docs/twitter-for-websites/embedded-tweets/guides/embedded-tweet-parameter-reference


# Hex Color Embedder
Simple html page that will embed a set of hex color codes using coolors.com. This is done in a way that is embeddable via simple URL (useful for Tableau).

Simply host this html file on a public web server. You can then pass one parameter which inludes a dash-separated list of hex color codes. For example: https://flerlageapps.com/color.html?codes=3b0102-762b2c-b6443f-c67d58-f5d6b1-fff8dc
