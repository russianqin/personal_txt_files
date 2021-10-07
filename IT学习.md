学习ios找工作的同时，初步了解：
计算机图形学
编译原理
操作系统的基础知识
分布式系统的架构
对你的代码进行靠谱的自动化测试
学会写framework和library，不要一味地写application

python的web框架
Flask 很轻，花很少的成本就能够开发一个简单的网站。非常适合初学者学习。
Flask 框架学会以后，可以考虑学习插件的使用。例如使用 WTForm + Flask-WTForm 来验证表单数据，用 SQLAlchemy + Flask-SQLAlchemy 来对你的数据库进行控制。
BTW：果壳网基于 Flask 开发的。
Django。如楼上所说，是一个全能型框架。目前 Django 的使用面还是很广的，有学习的价值，但是不建议初学者学习，因为要学习的东西太多了，一下子难以吸收会失去兴趣。当然，Django 的目的是为了让开发者能够 快速 地开发一个网站，它提供了很多模块，其中我最喜欢的就是 admin 模块，http://your.site.com/admin 就进入了网站的后台（内置的哦~）方便地对数据进行操作，等等。。。。因此，如果对 Django 熟悉的话，papapa 一下子就写好一个网站的原型了。
Tornado。传说中性能高高的框架。Tornado 是一个很好的框架，支持异步处理的功能，这是它的特点，其他框架不支持。另外一点是，Tornado 的设计似乎更注重 RESTful URL。但 Tornado 提供了网站基本需要使用的模块外，剩下的则需要开发者自己进行扩展。例如数据库操作，虽然内置了一个 database 的模块（后来独立出去了，现在叫做 torndb，bdarnell/torndb · GitHub）但是不支持 ORM，快速开发起来还是挺吃力的。如果需要 ORM 支持的话，还需要自己写一层将 SQLAlchemy 和 Tornado 联系起来，而且这里还有一个坑。
BTW：知乎就是基础 Tornado 开发的。
5. web2py。我看楼上都没有对这个框架做介绍。这个框架是 Google 在 web.py 基础上二次开发而来的，兼容 GAE 。性能据说很高，曾经用他来做自己的主页，感觉也还不错。缺点同样是对扩展支持不太好，需要自己进行扩展。
6. Quixote。著名的 豆瓣 就是基于 Quixote 开发的。跟上面几个框架不同，Quixote 的路由会有些特别。另外 Quixote 的性能据说也好。

