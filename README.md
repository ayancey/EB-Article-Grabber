# Encyclopedia Britannica 

Simple Python script that returns plain-text from Encyclopedia Britannica. It probably has some bugs in it. Oh well.

# Example
```python
import eb

# from http://www.britannica.com/EBchecked/topic/1963547/Islamic-State-in-Iraq-and-the-Levant-ISIL
print(eb.get_article_text(1963547).encode('ascii', 'ignore'))
```

![](http://i.imgur.com/uNhtviD.png)

# Requirements
* Python 2.7+
* [requests](https://github.com/kennethreitz/requests)
* [BeautifulSoup4](http://www.crummy.com/software/BeautifulSoup/)

*Made at CodeDay San Francisco 2015*