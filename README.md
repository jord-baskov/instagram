# instagram
How to Download Multiple Videos, Images and Instagram Albums via Shell Script

**usage: instagram [options] **[file/url ...]**

 *Options:*

  + **-v,--version  Print version**
  + **-h,--help     Show this help message**
  + **-f,--file     Get urls from file**

 Examples:

{% highlight bash %}
./instagram https://www.instagram.com/p/BnrplkmhY0T/
./instagram https://www.instagram.com/p/BnrplkmhY0T/ https://www.instagram.com/p/CnrpmmmhY0X/ # ...
./instagram -f file.txt
{% endhighlight %}

> * Where the file must have the urls that have Instagram images and/or videos, they can be on each line, 
either separated or with blanks, ... they can not be stuck together.
