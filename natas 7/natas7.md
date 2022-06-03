**Natas (OTW)**

**Natas 7 Writeup:**

Natas level 6 —>7

![](Aspose.Words.16f3b595-37d3-4c19-adba-521864899ebd.001.jpeg)

In this challenge we were given a web page with 2 hyperlinks as home and about pages with a simple php based code.

![](Aspose.Words.16f3b595-37d3-4c19-adba-521864899ebd.002.jpeg)

The following is the about page:

![](Aspose.Words.16f3b595-37d3-4c19-adba-521864899ebd.003.jpeg)

![](Aspose.Words.16f3b595-37d3-4c19-adba-521864899ebd.004.jpeg)

On inspecting the source code of the page we find out that there is a certain directory that holds some information , therefore we will input the file location as the payload in the url so that we can retrieve the data.

![](Aspose.Words.16f3b595-37d3-4c19-adba-521864899ebd.005.jpeg)

**Payload : [http://natas7.natas.labs.overthewire.org/index.php?page=/etc/natas_webpass/natas8**](http://natas7.natas.labs.overthewire.org/index.php?page=/etc/natas_webpass/natas8)**

![](Aspose.Words.16f3b595-37d3-4c19-adba-521864899ebd.006.jpeg)
