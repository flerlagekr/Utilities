To use these utilities, simply host the html file on a public web server. Or feel free to use my server, https://flerlageapps.com.

# Image Resizer
Simple html page that will resize an image.

Pass three parameters to the url: width, height, and imageurl. For example: https://flerlageapps.com/resize.html?height=420&width=1000&imageurl=http://flerlageapps.com/logo.png

# Image Embeder
Some image sites, such as imgur, won't allow embedding via iFrame (which Tableau uses for web objects). This allows yout to pass a URL of the image, then display it, bypassing that limitation.

Pass one parameter to the url: imageurl. For example: https://flerlageapps.com/image.html?imageurl=https://i.imgur.com/4GK14iv.png

# Image Fit
Simple html page that will display an image and fit it to the size of your container.

Pass three parameters to the url: width, height, and imageurl. In this case, width and height apply to the contaiiner and the image will size fit itself to that container. For example: https://flerlageapps.com/imagefit.html?height=500&width=500&imageurl=https://i.imgur.com/4GK14iv.png

# Tweet Embedder
Simple html page that will load a tweet in a way that is embeddable via simple URL (useful for Tableau).

Pass two parameters to the url: id (the tweet ID), width (Twitter has a min width of 250 and max of 550 px). For example: https://flerlageapps.com/twitterembed.html?width=500&id=1381584193579270144

Base code borrowed from https://www.labnol.org/code/19933-embed-tweet-with-javascript

You can also make changes to other parameters in the code (or parameterize them) according to https://developer.twitter.com/en/docs/twitter-for-websites/embedded-tweets/guides/embedded-tweet-parameter-reference

# Twitter Feed Embedder
Simple html page that will load a Twitter feed in a way that is embeddable via simple URL (useful for Tableau).

Pass a single parameter, profile, to the URL containing the profile of the feed you wish to embed (without the @). For example: https://flerlageapps.com/twitterfeed.html?profile=flerlagekr. Note: The embed code is responsive so it should resize based on the window.

# Hex Color Embedder
Simple html page that will embed a set of hex color codes using coolors.com. This is done in a way that is embeddable via simple URL (useful for Tableau).

Pass one parameter which inludes a dash-separated list of hex color codes. For example: https://flerlageapps.com/color.html?codes=3b0102-762b2c-b6443f-c67d58-f5d6b1-fff8dc

# MS Word (SharePoint/OneDrive) Embedder
Simple html page that will load a Word document stored on SharePoint/OneDrive, making it embeddable via simple URL (useful for Tableau).

Pass three parameters to the url:

1) doc - The embed URL for the document. Get this by opening the Word document on the web, clicking File | Share | Embed This Document, then get the url following the "iframe src=". Start with "https" and end witht the right curly bracket.
2) width - Width of the embed, in pixels. This should be a number.
3) height - Height of the embed, in pixels. This should be a number.

Example (This is not a real document so this will not load properly): https://flerlageapps.com/Word.html?width=1000&height=600&doc=https://yoursharepointsite/sites/yoursite/_layouts/15/Doc.aspx?sourcedoc={00ff1265-af22-4479-85e0-f2e1fbca2736}
