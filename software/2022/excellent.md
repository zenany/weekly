2022 - Excellent
========  

## 202204  

**Stabilize, Modularize, Modernize: Scaling Slack’s Mobile Codebases**  
https://slack.engineering/stabilize-modularize-modernize-scaling-slacks-mobile-codebases-2/  
https://slack.engineering/stabilize-modularize-modernize-scaling-slacks-mobile-codebases/  
In the first post about the Duplo initiative, we discussed the reasons for launching a project to revamp Slack’s mobile codebases, and what we accomplished in Duplo’s initial Stabilization phase. This post will explore modularization, and then there will be a third post to describe how we modernized our codebase and the overall results of the project.

**Transitional Architecture**  
https://martinfowler.com/articles/patterns-legacy-displacement/transitional-architecture.html  
Software elements installed to ease the displacement of a legacy system that we intend to remove when the displacement is complete.

**In defense of simple architectures**  
https://danluu.com/simple-architectures/  
Wave is a $1.7B company with 70 engineers1 whose product is a CRUD app that adds and subtracts numbers. In keeping with this, our architecture is a standard CRUD app architecture, a Python monolith on top of Postgres. Starting with a simple architecture and solving problems in simple ways where possible has allowed us to scale to this size while engineers mostly focus on work that delivers value to users. Stackoverflow scaled up a monolith to good effect (2013 architecture / 2016 architecture), eventually getting acquired for $1.8B.

## 202203

**Remix: The Yang to React's Yin**  
https://kentcdodds.com/blog/remix-the-yang-to-react-s-yin  
React's tagline is: A JavaScript library for building user interfaces. And it does a terrific job at that. React has never promised "network chasm management," but every web application needs it. With Remix managing that network chasm, we finally have a yang to React's yin. With a great rendering library and a super network chasm manager, you can build better, faster web applications with fewer bugs, simpler code, and more fun. Releated: [Remix – Web Standards Are Cool Again](https://www.simplethread.com/remix-web-standards-are-cool-again/).

**Mozilla’s vision for the evolution of the Web**  
https://webvision.mozilla.org/full/  
Mozilla's mission is to ensure that the Internet is a global public resource, open and accessible to all. We believe in an Internet that puts people first, where individuals can shape their own experience and are empowered, safe, and independent. The Web is an enormous asset to humanity and Mozilla is committed to protecting it and making it better. [..] we believe that we can all work together as a community to make a Web that is truly open and accessible to all.

**反思软件开发：软件本身**  
https://ourai.ws/posts/rethink-software/  
软件是现实世界的映射，通过二进制理论上可以完美复刻现实世界，充满无限可能，但依赖且受限于人们的认知与现实中的条件；对人们的正常生存、生活来说软件不是必需的，软件的存在是为了让人们变得更好；软件提供者不应为了一己私利去恶意利用人性，对用户和社会造成负面影响。回到开头提到的「技术服务于业务」和「你做的事情有什么业务价值」，这两句话实际在说——要先从业务领域和用户需求中分析出问题的确切所在，再根据问题的性质、特点等制定解决方案——毋庸置疑，技术方案是其中的一部分。

**是什么造成了中国软件产业的悲剧**  
https://mp.weixin.qq.com/s/O8klxfWDcGqG1E1TUjyjUg  
经历了这么多年的风风雨雨，作为中国软件的从业者，我常常在思考，为什么中国的软件产业还是很低端，并没有太多的优秀的软件问世，反而我们的邻国俄罗斯，最近这二十年完全无法和中国的经济发展相比较，但在软件行业里，前有大家基本上无法离开的 Nginx，后有现在已经大规模被使用中的 Clickhouse，这些都是有能力影响全世界的产品。中国的软件产业虽然也有长足的发展，但现实中，我们没有真正意义上的软件巨头型企业，大量基础软件被外国垄断，这究竟是为什么呢？

## 202202

**A career ending mistake**  
https://bitfieldconsulting.com/golang/career  
By “the end”, I don't necessarily mean picking your retirement date. What we're really talking about is the aim or goal of your career. Where will you be when you realise that this is where you've always wanted to be? If you love what you're doing now and don't ever want to change jobs, great: you've reached the end of your career, even if it plays out over many decades. If you don't love it, and that's much more likely, then it's worth asking what would make you feel that way, and when it's going to happen. So, where do you want to end up? And is that where you're currently heading? If not, what should you do about it?

**Thoughts On Markdown**  
https://www.smashingmagazine.com/2022/02/thoughts-on-markdown/  
Markdown in all its flavors, interpretations, and forks won’t go away. However, it’s important to look at emerging content formats that try to encompass modern needs. In this article, Knut shares his advice against Markdown by looking back on why it was introduced in the first place, and by going through some of the major developments of content on the web. Relteated: [Github - Include diagrams in your Markdown files with Mermaid](https://github.blog/2022-02-14-include-diagrams-markdown-files-mermaid/).  

**理想、激情、生存 - 一位技术管理人员的20年工作经历和感悟**  
https://sites.google.com/site/yangangwang/%E4%B8%80%E4%BD%8D%E6%8A%80%E6%9C%AF%E7%AE%A1%E7%90%86%E4%BA%BA%E5%91%98%E7%9A%8420%E5%B9%B4%E5%B7%A5%E4%BD%9C%E7%BB%8F%E5%8E%86%E5%92%8C%E6%84%9F%E6%82%9F  
我是一个有10年电子产品研发经验的工程师和10年IT知名公司研发中心管理经验的技术管理者。世上好的管理理念可能归纳起来就那么1~2百条，也都好理解，难的是怎么适当地运用在特定的环境中。下面的文章共18篇，是我20年工作中的片段，也是我在研发及管理中的实际体验和感悟。

**What are the Most Important Statistical Ideas of the Past 50 Years?**  
https://www.tandfonline.com/doi/full/10.1080/01621459.2021.1938081  
We review the most important statistical ideas of the past half century, which we categorize as: counterfactual causal inference, bootstrapping and simulation-based inference, overparameterized models and regularization, Bayesian multilevel models, generic computation algorithms, adaptive decision analysis, robust inference, and exploratory data analysis. We discuss key contributions in these subfields, how they relate to modern computing and big data, and how they might be developed and extended in future decades. The goal of this article is to provoke thought and discussion regarding the larger themes of research in statistics and data science.

**An example of why RSS is useful and important**  
https://tech.chrishardie.com/2022/rss-useful-important/  


## 202201

**所谓“现代Web开发”，都是些什么妖魔鬼怪？**  
https://mp.weixin.qq.com/s/QNqIeFmiaDV0RSxsovZvgQ  
https://unixsheikh.com/articles/no-your-website-is-not-a-webapp-even-if-you-call-it-so.html  
https://unixsheikh.com/articles/so-called-modern-web-developers-are-the-culprits.html  
https://news.ycombinator.com/item?id=29590404  
2022 年已经到来，我们是时候反思 Web 开发中的种种过时软件、炒作歪曲和荒谬趋势了。把握这一年，我们也该重新专注于性能与技术运用，把手段和目的重新统一起来。当然，我不是劝大家用汇编或者 C 语言搞 Web 开发，但关于 JavaScript、Ruby on Rails、Python、Django 以及 PHP 框架的疯狂观点也该消停一下了。另附：[Have Single-Page Apps Ruined the Web? | Transitional Apps with Rich Harris, NYTimes](https://www.youtube.com/watch?v=860d8usGC0o)。

**web3 is Centralized**  
https://blog.wesleyac.com/posts/web3-centralized  
The funny thing is, web3, as it exists today and appears to be building towards, is actually more centralized than the web it seeks to replace. Releated: 
- [My First Impressions of Web3](https://moxie.org/2022/01/07/web3-first-impressions.html)  
- [Web3 Browsers for Decentralized Storage](https://blog.ipfs.io/2022-01-07-web3-browsers-for-decentralized-storage/)  
- [DWeb Holiday Fair – December 2021 Meetup Recap](http://blog.archive.org/2022/01/05/dweb-holiday-fair-december-2021-meetup-recap/)  
- [How to Build a Better Internet: 10 Principles for World leaders Shaping the Future of Web3](https://a16z.com/2022/01/07/how-to-build-a-better-internet-10-principles-for-world-leaders-shaping-the-future-of-web3/)  
- [The web doesn’t have version numbers](https://hiddedevries.nl/en/blog/2022-01-03-the-web-doesnt-have-version-numbers)  

-- THE END --
