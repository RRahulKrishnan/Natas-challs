**Natas (OTW)**

**Natas 4 Writeup:**

Natas level 3 —>4

The basic idea of this particular challenge is to change the status of the refer from natas 4 to natas 5

![](Aspose.Words.9b966a22-0d16-461c-ab84-97b79a044ee8.001.jpeg)

![](Aspose.Words.9b966a22-0d16-461c-ab84-97b79a044ee8.002.jpeg)

![](Aspose.Words.9b966a22-0d16-461c-ab84-97b79a044ee8.003.jpeg)

Using the hint that has been given to us in the above source code we get an idea that the refer has to be changed or modified in order to retain the password

![](Aspose.Words.9b966a22-0d16-461c-ab84-97b79a044ee8.004.jpeg)

Here we decode the authorization value using base 64 decoding  that is inbuilt within the owasp zap application.

![](Aspose.Words.9b966a22-0d16-461c-ab84-97b79a044ee8.005.jpeg)

After base 64 decoding the authorization key we find the value of the password that is required for opening the next level.

**Natas4 :** Z9tkRkWmpt9Qr7XrR5jWRkgOU901swEZ

![](Aspose.Words.9b966a22-0d16-461c-ab84-97b79a044ee8.006.jpeg)

Now we manually change the referrer from natas 4 to natas 5  by editing to get a different password value , which is the password to unlock the next level..

**Natas5 :** iX6IOfmpN7AYOQGPwtn3fXpbaJVJcHfq
