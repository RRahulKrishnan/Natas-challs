**Natas (OTW)**

**Natas 5 Writeup:**

Natas level 4 —>5

![](Aspose.Words.612224d9-ad09-4034-ba48-69eda7805c0a.001.jpeg)

![](Aspose.Words.612224d9-ad09-4034-ba48-69eda7805c0a.002.jpeg)

![](Aspose.Words.612224d9-ad09-4034-ba48-69eda7805c0a.003.jpeg)

Similar to the previous challenge in this challenge we use owasp zap application. As the hint suggests that we aren't logged in.

![](Aspose.Words.612224d9-ad09-4034-ba48-69eda7805c0a.004.jpeg)

In this case we see that there is a cookie whose value has been set to “0” which is a false value that has been entered,therefore we have to alter this value and set it to “1” which will make the value true and therefore allow us to find the password.

![](Aspose.Words.612224d9-ad09-4034-ba48-69eda7805c0a.005.jpeg)

![](Aspose.Words.612224d9-ad09-4034-ba48-69eda7805c0a.006.jpeg)

We use a cookie editor to alter the value of the cookie and save it to mend the changes , thereafter we get the password to the next challenge.

![](Aspose.Words.612224d9-ad09-4034-ba48-69eda7805c0a.007.jpeg)
