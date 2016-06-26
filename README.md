<!--
# A handy guide to financial support for open source.
*"I do open source work, how do I find funding?"*

Below I've listed every way I know of that people get paid for open source work, roughly ordered from small to large. Each funding category links to several real examples. (Wherever possible, I've tried to link to a useful article or page instead of just a homepage.)

The categories are not mutually exclusive. For example, a project might have a foundation but also use crowdfunding to raise money. Someone else might do consulting and also have a donation button. Etc. The purpose of this guide is to provide an exhaustive list of all the ways you can get paid, so that you can figure out what works best for you.


---


-->

# 开源项目挣钱实用手册
*"我在参与开源项目，但是我该如何挣钱呢？"*

我列出了我从各种渠道所知道的开源项目带来收入的人们的故事，每种出资类型都有一系列的真实案例，粗略的按照出资量从小到大排列。（我已尽可能的将链接指向具体故事而非主页面）

本文中的出资类型并非互斥的，例如一个项目既可以由基金会也可以通过众筹来筹集资金，而一个人既可以靠咨询挣钱也可以获得捐赠。本文的主要目的是提供一个详尽的挣钱方式列表，而你只需要从中选出适合你的。

本中文版是[原版](https://github.com/nayafia/lemonade-stand)的翻译版本。

原项目名称Lemonade Stand是指销售柠檬汁的小摊，而在美国，这种小摊通常是由小朋友运作的。

---

<!--
# Table of Contents
1. [Donation button](#donation-button)
2. [Bounties](#bounties)
3. [Crowdfunding (one-time)](#crowdfunding-one-time)
4. [Crowdfunding (recurring)](#crowdfunding-recurring)
5. [Books and merchandise](#books-and-merchandise)
6. [Advertising & sponsorships](#advertising--sponsorships)
7. [Get hired by a company to work on project](#get-hired-by-a-company-to-work-on-project)
8. [Start a project while currently employed](#start-a-project-while-currently-employed)
9. [Grants](#grants)
10. [Consulting & services](#consulting--services)
11. [SaaS](#saas)
12. [Dual license](#dual-license)
13. [Open core](#open-core)
14. [Foundations & consortiums](#foundations--consortiums)
15. [Venture capital](#venture-capital)

APPENDIX: [Contributing to this guide](#contributing-to-this-guide) // [License & attribution](#license-and-attribution)

**"personal effort" notes when a funding effort was led by an individual, not a project*

-->

# 目录

1. [捐赠按钮](#捐赠按钮)
2. [悬赏](#悬赏)
3. [众筹（一次性）](#众筹（一次性）)
4. [众筹（持续性）](#众筹（持续性）)
5. [卖书及周边](#卖书及周边)
6. [广告](#广告)
7. [受雇于公司并继续你的项目](#受雇于公司并继续你的项目)
8. [在职时启动项目](#在职时启动项目)
9. [补贴](#补贴)
10. [咨询服务](#咨询服务)
11. [SaaS](#saas)
12. [双重协议](#双重协议)
13. [开放核心](#开放核心)
14. [基金会](#基金会)
15. [风险投资](#风险投资)

附录: [贡献](#贡献) // [协议](#协议)

**"个人努力" 用来标记其资金是由个人而非项目主导筹集获得的**


<!--
## Donation button
*Stick a donation button on your site. Stripe and PayPal are examples of services you can use to accept donations.*

-->

## 捐赠按钮

在你的网站页面里放上捐赠按钮。Stripe和PayPal都可以很方便的提供这项服务。

<!--
#### Pros
* Few strings attached
* Little work involved: "set it and forget it"

-->

#### 优点

* 限制条件少
* 工作量小：放好后就可以不管了

<!--
####Cons
* Usually not much money unless you have dedicated fundraising efforts
* Need a legal entity to donate to (ex. [SFC](http://sfconservancy.org), [OpenCollective](http://opencollective.com) are fiscal sponsors for this purpose). Harder for individuals or international donations to manage
* Sometimes not clear who “deserves” money in a project or how it gets distributed

-->

#### 缺点

* 除非你努力筹款，通常都不会有太多钱
* 需要一个法人实体来接受捐赠（[SFC](http://sfconservancy.org), [OpenCollective](http://opencollective.com)可在这方面提供帮助），因此较难管理个人的国际性捐赠
* 在多人项目中很难明确如何分配这笔捐赠

<!--
####Case Studies
* [Twisted](https://twistedmatrix.com/trac/wiki/WhyDonate)
* [Git](https://git-scm.com/sfc)
* [Transmission](https://www.transmissionbt.com/)

-->

#### 案例学习

* [Twisted](https://twistedmatrix.com/trac/wiki/WhyDonate)
* [Git](https://git-scm.com/sfc)
* [Transmission](https://www.transmissionbt.com/)

<!--
##Bounties
*Sometimes, projects or companies post bounties for open source work (ex. "fix this bug and collect $100"). There are several websites, listed below, that help facilitate the posting and collection of bounties.*

-->

## 悬赏

项目或公司可能时不时的张贴开源项目的悬赏工作（例如“修漏洞赚$100”），下面列出了一些网站，他们收集和发布了这类悬赏工作。

<!--
####Pros
* Open to community participation
* Money is tied to doing specific work (more like paying for service than donations)
* Especially popular for security work

-->

#### 优点

* 参与到开源社区
* 确定的工作有确定的回报
* 在修复安全漏洞方面特别流行

<!--
####Cons
* Can create perverse incentives in a project (low quality PRs, distracting priorities)
* Usually not much money per bounty (~<$500)
* Doesn’t provide recurring revenue

-->

#### 缺点

* 会在项目中产生不合理的激励机制（低质量的PR也会影响项目的专注性）
* 通常没多少钱 (~&lt;$500)
* 无法提供持久的收入

<!--
####Case Studies
* [Bountysource](http://bountysource.com)
* [GitHub Bug Bounty Program](https://bounty.github.com/)

-->

#### 案例学习

* [Bountysource](http://bountysource.com)
* [GitHub Bug Bounty Program](https://bounty.github.com/)

<!--
##Crowdfunding (one-time)
*If you have a specific idea you'd like to implement (rather than ongoing project work), a one-time crowdfunding campaign can help raise the funds you need. Both individuals and companies might be willing to donate to your campaign.*

-->

## 众筹（一次性）

如果你想实现一个特别的想法（区别于长期项目），一次性的众筹活动可以帮助你筹集到你需要的资金，许多个人和公司都可能会为你的想法捐款。

<!--
####Pros
* Few strings attached
* Can be easier for an individual to legally manage via, ex. [Kickstarter](https://kickstarter.com/)

-->

#### 优点

* 限制条件少
* 对个人来说也可以很容易合法的进行，例如通过[Kickstarter](https://kickstarter.com/)

<!--
####Cons
* Lots of work involved to market campaign
* Usually has to be tied to concrete outcome, perks
* Usually not that much money (~$50K for one time)
* Companies not always comfortable donating to campaigns

-->

#### 缺点

* 一大堆的市场工作需要做
* 通常都需要为捐赠者提供回报甚至是特权
* 通常钱也不是那么多（一次大约$50K）
* 公司并不常愿意向众筹捐款

<!--
####Case Studies
* [Michal Papis + Rvm (personal effort)](https://www.bountysource.com/teams/rvm/fundraiser)
* [Andrew Godwin + Django (personal effort)](https://www.kickstarter.com/projects/andrewgodwin/schema-migrations-for-django)
* [ribasushi + CPAN (personal effort)](https://www.tilt.com/tilts/year-of-ribasushi-help-him-focus-on-cpan-for-2016)
* [RESTful WP-CLI](https://www.kickstarter.com/projects/danielbachhuber/a-more-restful-wp-cli)

-->

#### 案例学习

* [Michal Papis + Rvm (个人努力)](https://www.bountysource.com/teams/rvm/fundraiser)
* [Andrew Godwin + Django (个人努力)](https://www.kickstarter.com/projects/andrewgodwin/schema-migrations-for-django)
* [ribasushi + CPAN (个人努力)](https://www.tilt.com/tilts/year-of-ribasushi-help-him-focus-on-cpan-for-2016)
* [RESTful WP-CLI](https://www.kickstarter.com/projects/danielbachhuber/a-more-restful-wp-cli)

<!--
##Crowdfunding (recurring)
*If you'd like to fund ongoing project work, you can set up a recurring crowdfunding campaign, with a monthly or annual financial commitment that renews indefinitely (or until the donor cancels). Those who use your project regularly (including both individuals and companies) might be willing to fund your work.*

-->

## 众筹（持续性）

如果你想要为持续性的项目筹集资金，可以设立一个持续性的众筹，捐赠者承诺按月或按年提供资金直到捐赠者退出。对于那些经常使用你的项目的个人或公司可能会愿意为你的项目提供资金。

<!--
####Pros
* Few strings attached
* Can be easier for an individual to legally manage via, ex. [Patreon](https://patreon.com), [Salt](https://salt.bountysource.com/), [Gratipay](https://gratipay.com/), [OpenCollective](https://opencollective.com)

-->

#### 优点

* 限制条件少
* 对个人来说也可以很容易合法的进行，例如通过[Patreon](https://patreon.com), [Salt](https://salt.bountysource.com/), [Gratipay](https://gratipay.com/), [OpenCollective](https://opencollective.com)

<!--
####Cons
* Harder to get commitments to recurring donations (often requires preexisting brand/reputation)
* Harder to explain concrete outcomes, perks that come with recurring donations
* Usually not that much money (~$1-4K monthly)
* Companies not always comfortable donating to campaigns

-->

#### 缺点

* 很难获得承诺的持续性捐赠（这通常需要你或项目已经有一定的名声）
* 很难解释持续性的捐赠能获得什么样明确的回报或特权
* 通常钱也不是那么多（一个月$1-4K）

<!--
####Case Studies
* [MochaJS](https://opencollective.com/mochajs)
* [React-boilerplate](https://opencollective.com/react-boilerplate)
* [jsbin](https://gratipay.com/jsbin/)
* [Tom Christie + Django REST framework (personal effort)](https://fund.django-rest-framework.org/topics/funding/)
* [Ruby Together](https://rubytogether.org)

-->

#### 案例学习

* [MochaJS](https://opencollective.com/mochajs)
* [React-boilerplate](https://opencollective.com/react-boilerplate)
* [jsbin](https://gratipay.com/jsbin/)
* [Tom Christie + Django REST framework (personal effort)](https://fund.django-rest-framework.org/topics/funding/)
* [Ruby Together](https://rubytogether.org)

<!--
##Books and merchandise
*If you are an expert in a domain that other people might find useful to learn about, you could write and sell a book or series of books. You can find a publisher (like O'Reilly) or self-publish. In addition to selling books, some projects sell merchandise (ex. shirts, hoodies) to support their work.*

-->

## 卖书及周边

如果你是某个领域的专家，你可以写书卖书，可以找个出版社（像O'Reilly）或自己出版（译者注：在中国不行）。除了卖书之外，有些项目也卖短袖外套等。

<!--
####Pros
* Outcome not tied to project work itself, so you retain creative freedom
* Can serve as marketing for the project itself
* Can be recurring source of revenue after initial development

-->

#### 优点

* 筹集到的资金并不和项目本身管理关联，所以项目本身可以保持创作的自由
* 销售的商品本身也可以当做为项目做的宣传
* 在初次销售后可以成为持续性的资金来源

<!--
####Cons
* Often not a significant source of revenue
* Can distract from core development of project
* Merchandise can have upfront costs

-->

#### 缺点

* 通常钱也不是那么多
* 会影响用在项目上的精力
* 卖周边需要准备预付资金

<!--
####Case Studies
* [Lua](https://www.lua.org/pil/)
* [Daniel and Audrey Roy Greenfeld + Two Scoops of Django (personal effort)](https://www.twoscoopspress.com/products/two-scoops-of-django-1-8)
* [Sandi Metz + Practical Object-Oriented Design in Ruby (personal effort)](http://www.poodr.com/)

-->

#### 案例学习

* [Lua](https://www.lua.org/pil/)
* [Daniel and Audrey Roy Greenfeld + Two Scoops of Django (个人努力)](https://www.twoscoopspress.com/products/two-scoops-of-django-1-8)
* [Sandi Metz + Practical Object-Oriented Design in Ruby (个人努力)](http://www.poodr.com/)

<!--
##Advertising & sponsorships
*If your project has a large audience, you can sell sponsorships to advertisers who might want to reach them. You probably have a very targeted audience (ex. if you have a Python project, you can assume your audience is likely people who are technically familiar with Python), so use that to your advantage.*

-->

## 广告

如果你的项目已经有了一定的受众，你可以帮助广告商向你的受众推销。通常你的项目都会有明确的受众，这是你的优势也是广告商所喜欢的。（比如你有一个Python项目，那么基本上可以假定你的受众一定是技术上熟悉Python的）

<!--
####Pros
* Business model aligned with something people are willing to pay for

-->

#### 优势

* 这是成熟明确而且大众也能接受的商业模式

<!--
####Cons
* Need large enough audience to justify sponsorships
* Need to manage trust and transparency with user base (ex. no tracking)
* Can be a lot of work to find and manage clients

-->

#### 缺点

* 需要足够多的受众才能请来广告商
* 需要通过透明化来让受众相信你（比如让其信任你不会追踪他们）
* 需要许多精力来寻找和管理广告商

<!--
####Case Studies
* [Read the Docs](http://blog.readthedocs.com/ads-on-read-the-docs/)
* [Hoodie](http://hood.ie/sponsoring/)

-->

#### 案例学习

* [Read the Docs](http://blog.readthedocs.com/ads-on-read-the-docs/)
* [Hoodie](http://hood.ie/sponsoring/)

<!--
##Get hired by a company to work on project
*Companies sometimes hire individuals to do open source work. Find a company that uses the project you want to work on. Often this is a split arrangement (ex. 50% company work, 50% open source work). Alternatively, if you have an idea for a new project, find a company that would be interested in using what you produce. In these situations, having demonstrated experience you can point to will be very helpful.*

-->

## 受雇于公司并继续你的项目

公司有时候会雇佣一些个人来做开源项目，你可以寻找一个正在使用你的开源项目的公司。当然具体在公司里可能公司工作和开源项目工作时间会是五五分。除此之外，也可以找一个愿意尝试使用你的新项目的公司。如果你有展示项目经验，这将会非常有用。

<!--
####Pros
* Taps into those who have resources (i.e. companies)
* Can be well-aligned with company needs
* Steady income

-->

#### 优点

* 可以利用公司的资源
* 可以很好的和公司的需求保持一致
* 稳定的收入

<!--
####Cons
* Usually involves “getting lucky”: no clear, repeatable path to finding this arrangement
* Project already needs to be well-known and used
* Person not contributing to company’s bottom line, which makes them expendable
* Governance issues, company could have undue influence over project
* Can affect project dynamics + balance

-->

#### 缺点

* 获得这样的机会需要极好的运气，现目前没有明确可重复的方式获得这样的机会
* 项目通常需要非常出名并且被使用
* 对于没有为公司的利润工作，这使得个人很容易被公司优先舍弃
* 公司可能会过分影响项目的发展
* 可能会因平衡不好两边而影响项目

<!--
####Case Studies
* [Donald Stufft + Hewlett-Packard and Python packaging (personal effort)](https://twitter.com/dstufft/status/594119386333609984)
* [Rich Hickey + Cognitect and Clojure](http://www.bizjournals.com/triangle/news/2013/09/17/durhams-relevance-to-merge-with.html?full=true)
* [Aaron Patterson + ManageIQ and Ruby, Rails (personal effort)](http://community.redhat.com/blog/2014/09/tenderlove-joins-manageiq/)
* [Ryan Dahl + Joyent and Node.js (opens a YouTube video) (personal effort)](http://www.youtube.com/watch?v=SAc0vQCC6UQ&t=29m20s)

-->

#### 案例学习

* [Donald Stufft + Hewlett-Packard and Python packaging (个人努力)](https://twitter.com/dstufft/status/594119386333609984)
* [Rich Hickey + Cognitect and Clojure](http://www.bizjournals.com/triangle/news/2013/09/17/durhams-relevance-to-merge-with.html?full=true)
* [Aaron Patterson + ManageIQ and Ruby, Rails (个人努力)](http://community.redhat.com/blog/2014/09/tenderlove-joins-manageiq/)
* [Ryan Dahl + Joyent and Node.js (opens a YouTube video) (个人努力)](http://www.youtube.com/watch?v=SAc0vQCC6UQ&t=29m20s)

<!--
##Start a project while currently employed
*Many open source projects started as employee side projects. The project might eventually outgrow the company, but starting it as a side project can be a great way to incubate the idea.*

*If you pursue this path, make sure you understand your company's policy on open source work. Some companies encourage employees to contribute to open source during working hours. Some might treat your open source work as a company project. Don't assume anything; ask someone at your company before starting.*

-->

## 在职时启动项目

许多开源项目最初都是员工的编外项目(Side
Project)，即便其最终可能会成长为一家公司，但以编外项目的形式在公司里进行孵化应该是不错的选择。

如果你想走这条路，请确定你理解了公司在开源项目上的政策。有些公司鼓励员工在工作时间从事开源项目开发，而有些则将你的任何工作视作公司项目。不要假定任何前提，最好在开始前问问你公司里的相关人员。

<!--
####Pros
* Freedom to test new ideas without worrying about salary
* Can be well-aligned with company needs
* Suitable for newer, experimental ideas

-->

#### 优点

* 可以不用担心收入的情况下尝试新想法
* 可以和公司的需求很好的保持一致
* 适合尝试新想法

<!--
####Cons
* Need to do it as a side project or be approved to work on it during salaried time
* Risk of undue company influence
* Can lead to complicated governance later down the line

-->

#### 缺点

* 需要用业余时间开发，或者获准在工作时间开发
* 有被公司过分影响的风险
* 持续下去可能会出现极度复杂的管理情况

<!--
####Case Studies
* [Mozilla and Rust](https://www.rust-lang.org/faq.html#is-this-project-controlled-by-mozilla)
* [Google and Go](https://golang.org/doc/faq#history)
* [Facebook and React](https://www.quora.com/How-was-the-idea-to-develop-React-conceived-and-how-many-people-worked-on-developing-it-and-implementing-it-at-Facebook/answer/Bill-Fisher-17)
* [Futurice's open source program](http://futurice.com/blog/sponsoring-free-time-open-source-activities)

-->

#### 案例学习

* [Mozilla and Rust](https://www.rust-lang.org/faq.html#is-this-project-controlled-by-mozilla)
* [Google and Go](https://golang.org/doc/faq#history)
* [Facebook and React](https://www.quora.com/How-was-the-idea-to-develop-React-conceived-and-how-many-people-worked-on-developing-it-and-implementing-it-at-Facebook/answer/Bill-Fisher-17)
* [Futurice's open source program](http://futurice.com/blog/sponsoring-free-time-open-source-activities)

<!--
##Grants
*Grants are effectively large donations that do not require repayment. Oftentimes the grantmaker receives other benefits from giving you the grant, such as access to you, demonstration of impact, a report of your work, or tax benefits.*

*Grants can come from many places, including companies, software foundations, philanthropic foundations, and the government. The technical and legal aspects of a grant vary greatly depending on where it comes from. For example, a company might give you a "grant" but legally treat it as a consulting invoice. A philanthropic foundation can only make grants to nonprofits, so you would need to be a nonprofit yourself, or (more commonly) find a nonprofit to sponsor you. If you're unfamiliar with grants, the best way to understand how grants work is to talk to someone who has received one before. Some examples of grant recipients are listed below.*

-->

## 补贴

补贴是不需要偿还的极其有效的大笔捐赠，提供补贴的组织通常能够通过给予补贴而从其他方面获得利益，例如接近你，展示其影响力，获得你的工作汇报或税率优惠。

补贴可能来自很多地方，包括公司、软件基金会、慈善基金会以及政府，其技术及法律方面会因其来源的不同有很大的差异。比如一家公司可以通过开咨询费发票给你补贴，而慈善基金会则只能给非盈利组织或个人，通常你得找到一个非盈利组织来帮助你。如果你对补贴不熟悉，了解它的最好方式就是和曾经获得过的人去了解。下面列出了一些成功的案例

<!--
####Pros
* Fewer strings attached
* Guaranteed money can help project focus for an unbroken period of time
* Gives project room to breathe and experiment

-->

#### 优点

* 限制条件少
* 有保证的资金可以确保你能在一段时间里专注在你的项目上
* 让你的项目有时间喘口气和做些试验

<!--
####Cons
* There aren’t many software-related grantmakers (philanthropic, gov’t, corporate)
* Grants are finite. Still need to find sustainability beyond the life of a grant

-->

#### 缺点

* 软件方面没太多提供补贴的组织
* 补贴是有限的，始终需要在用完补贴前找到一个持续方法

<!--
####Case Studies
* [Dat](https://usopendata.org/)
* [Andrey Petrov + Stripe Open-Source Retreat and urllib3](https://medium.com/@shazow/urllib3-stripe-and-open-source-grants-edb9c0e46e82#.45ylnxrh4)
* [Django + Mozilla Open Source Support](https://www.djangoproject.com/weblog/2015/dec/11/django-awarded-moss-grant/)

-->

#### 案例学习
* [Dat](https://usopendata.org/)
* [Andrey Petrov + Stripe Open-Source Retreat and urllib3](https://medium.com/@shazow/urllib3-stripe-and-open-source-grants-edb9c0e46e82#.45ylnxrh4)
* [Django + Mozilla Open Source Support](https://www.djangoproject.com/weblog/2015/dec/11/django-awarded-moss-grant/)

<!--
##Consulting & services
*Consulting can be a flexible way to fund open source work. You have more freedom to structure your time as you wish (for example, consulting 30 hrs of the week and spending 10 hrs of the week on open source work). Consultants can usually charge more for their time than salaried employees because the work is less steady, they don't receive benefits, etc. If you plan on doing this type of work regularly, you will probably want to set up an LLC (or equivalent outside of the US).*

*If your project is popular, you can also offer consulting & services around the project itself. For example, a client might pay you to implement the project for them, build something custom, or train them on how to use it.*

-->

## 咨询服务

咨询是一种为开源项目提供资金的灵活方式。你可以更加自由的规划你的时间，比如一周30小时做咨询业务，10小时做开源项目。咨询师通常收费相对较贵，因为工作不稳定且没有公司福利。如果你打算做这类公司，你应该想要创建一家有限责任公司。

<!--
####Pros
* Business model aligned with something people are willing to pay for

-->

#### 优点

* 这是成熟明确而且大众也能接受的商业模式

<!--
####Cons
* Consulting requires human power, doesn’t scale well (except for rare outliers)
* Business needs can distract from writing code or other tasks related to the project itself
* Can be at odds with making software simple to use
* Project needs to be sufficiently popular that people are willing to pay for related services

-->

#### 缺点

* 咨询工作需要人力，而且不宜规模化（除了极少数）
* 商业本身的需求会分散开源项目上的注意力
* 可能会和软件的简易要求有差异
* 项目需要足够流行，才会让人愿意为相关服务付钱

<!--
####Case Studies
* [Neighbourhoodie](https://neighbourhood.ie/)
* [Baroque Software](http://baroquesoftware.com/)
* [OpenSSL](http://openssl.com/what.html)

-->

#### 案例学习

* [Neighbourhoodie](https://neighbourhood.ie/)
* [Baroque Software](http://baroquesoftware.com/)
* [OpenSSL](http://openssl.com/what.html)

<!--
##SaaS
*SaaS means [Software as a Service](https://en.wikipedia.org/wiki/Software_as_a_service). In this model, the codebase itself is open source, but you might offer additional paid services that make it easier for people to use your project. One common example of a paid service is charging for hosting.*

-->

## SaaS

SaaS 即 [软件即服务(Software as a Service)](https://en.wikipedia.org/wiki/Software_as_a_service)。在这个模型下，代码本身是开源的，但是你可以提供增值服务使得用户更容易使用。一个典型的增值服务就是托管付费。

<!--
####Pros
* Can build community around open project and make money off of services for hosting
* Allows open source project to focus on users and as needs grow to help enterprises adopt the project
* Can scale by number of users

-->

#### 优点

* 可以围绕这个开源项目建立一个社区，然后通过托管服务赚钱
* 让开源项目可以专注在用户层面，当需求增加后再帮助企业采用这个项目
* 可以根据用户数进行规模化改造

<!--
####Cons
* Often means the hosting needs to be cheaper than hiring a dev to run the project for you.
* “Two tiers” of product support can make free users unhappy

-->

#### 缺点

* 对增值服务使用者来说，通常意味着托管服务必须比招聘一个人来维护项目更便宜
* 增值服务有可能会使得免费用户不太高兴

<!--
####Case Studies
* [WordPress.com](http://wordpress.com/)
* [Moodle](https://moodle.org/)
* [Forge Laravel](https://forge.laravel.com/)
* [Gitlab](http://gitlab.com)
* [Sentry](https://getsentry.com/)
* [Travis CI](https://travis-ci.org/)
* [Ghost](https://ghost.org/)

-->

#### 案例学习

* [WordPress.com](http://wordpress.com/)
* [Moodle](https://moodle.org/)
* [Forge Laravel](https://forge.laravel.com/)
* [Gitlab](http://gitlab.com)
* [Sentry](https://getsentry.com/)
* [Travis CI](https://travis-ci.org/)
* [Ghost](https://ghost.org/)

<!--
##Dual License
*Sometimes, projects offer an identical codebase with two different licenses: one that is commercially-friendly, and one that is less so (ex. GPL). The latter is free for anyone to use, but companies pay for the commercial license in order to have legal peace of mind.*

-->

## 双重协议

有时候项目可以在完全相同的代码里提供两种不同的授权协议：一个是商业友好的，而另外一个则不（例如GPL）。后者对于个人来说可以免费使用，而公司需要通过购买商业协议来获得合法的商业授权。

<!--
####Pros
* Business model aligned with something people are willing to pay for
* Can scale well if successful

-->

#### 优点

* 这是成熟明确而且大众也能接受的商业模式
* 如果成功的话，也可以做到规模化

<!--
####Cons
* Can be at odds with making software freely accessible
* Project needs to be big enough that customer need exists

-->

#### 缺点

* 会和让软件自由获得的理想有冲突
* 项目需要足够大以满足客户的需求

<!--
####Case Studies
* [MySQL](http://www.mysql.com/about/legal/licensing/oem/)
* [SQLite](https://www.sqlite.org/copyright.html)

-->

#### 案例学习

* [MySQL](http://www.mysql.com/about/legal/licensing/oem/)
* [SQLite](https://www.sqlite.org/copyright.html)

<!--
##Open core
*Under an [open core](https://en.wikipedia.org/wiki/Open_core) model, some aspects of the project are free, but other features are proprietary and available only to paid users. Usually this works when there is enterprise demand for the project.*

-->

## 开放核心

在[开放核心](https://en.wikipedia.org/wiki/Open_core)模型中，项目的一些方面是免费的，但一些功能则是私有的，且只对付费用户开放，通常要求这个项目有企业的需求。

<!--
####Pros
* Business model aligned with something people are willing to pay for
* Can scale well if successful

-->

#### 优点

* 这是成熟明确而且大众也能接受的商业模式
* 如果成功的话，也可以做到规模化

<!--
####Cons
* Need to have something you can charge for (which means making certain features exclusive)
* Can be at odds with making software freely accessible
* “Two tiers” of product support can make free users unhappy

-->

#### 缺点

* 需要设计付费项目，且该项目应该是独有的
* 会和让软件自由获得的理想有冲突
* 独有功能有可能会使得免费用户不太高兴


<!--
####Case Studies
* [Docker](https://www.docker.com/)
* [Elastic](https://www.elastic.co/)
* [Mesosphere](https://mesosphere.com/)
* [Sidekiq](http://sidekiq.org/)

-->

#### 案例学习

* [Docker](https://www.docker.com/)
* [Elastic](https://www.elastic.co/)
* [Mesosphere](https://mesosphere.com/)
* [Sidekiq](http://sidekiq.org/)

<!--
##Foundations & consortiums
*A [foundation](https://en.wikipedia.org/wiki/Foundation_(nonprofit)) is a legal entity that can accept and/or disburse donations. Because their purpose is not to make profits, they can be a great choice to signal neutrality and steward a project. In the US, foundations are either 501c3 (nonprofit) or 501c6 (trade consortium). Many software foundations are 501c6 because 501c3s require demonstrating a charitable purpose, which can be more difficult in software.*

-->

## 基金会

[基金会](https://en.wikipedia.org/wiki/Foundation_&#40;nonprofit&#41;)是可以接收和支出的合法法人实体。鉴于其目的并非获得利润，因此可以更好保持中立地管理项目。在美国，基金会可以是501c3（非盈利）或501c6（贸易联盟），许多软件基金会都是贸易联盟，因为非盈利基金会要求展示出慈善的目的，这在软件开发中比较困难。

<!--
####Pros
* Neutrality. Foundation protects the code and helps steward community
* Influence distributed across multiple donors
* Can legitimize project, companies might feel more comfortable giving to foundations than individuals

-->

#### 优点

* 中立，基金会可以帮助保护代码和管理社区
* 可以在许多捐赠者中散布影响力
* 使得项目合法，公司会更愿意向基金会付款/捐赠而非个人

<!--
####Cons
* Only really worth it for big projects
* Difficult to set up for IRS reasons (many do 501c6 instead of 501c3), restrictions on what you can do
* Requires serious community effort and diverse skills (you still need to fundraise after setting up the entity!)

-->

#### 缺点

* 只适合大项目
* 由于IRS的限制，项目能做什么会有所限制
* 需要大量社区的努力和各种技能，而且之后仍旧需要努力获得筹款

<!--
####Case Studies
* [Ruby Together](http://rubytogether.org/)
* [Python Software Foundation](https://www.python.org/psf/)
* [Node.js Foundation](https://www.sitepoint.com/goodbye-joyent-hello-node-js-foundation/)

-->

#### 案例学习

* [Ruby Together](http://rubytogether.org/)
* [Python Software Foundation](https://www.python.org/psf/)
* [Node.js Foundation](https://www.sitepoint.com/goodbye-joyent-hello-node-js-foundation/)

<!--
##Venture capital
*Venture capital is a form of funding for high growth businesses. Unlike a bank loan or other forms of debt financing, venture capitaists take equity (a percent ownership in your business) in exchange for funding. The tradeoff is that unlike taking out a loan, you don't have to repay your creditors if your business tanks. If you do succeed, however, you should expect to return capital to your investor at a multiple.*

*Venture capital is "high risk high reward": VCs are more risk tolerant than, say, a bank, but they also expect a large payoff if you are successful. If you plan on raising venture capital, you should set up a business entity structured as a C Corp, preferably Delaware. If you're unfamiliar with the venture capital process, the best place to start is by reaching out to similar founders who have successfully raised venture.*

-->

## 风险投资

风险投资是高增长业务的一种筹资形式，不像银行贷款或者任意一种债务财务形式，风险投资者通过提供资金来占有你业务的一定股份。这种交易不像贷款，如果你的业务挂了你并不需要偿还出资方。当然，如果你成功了，你也需要成倍的返还给你的投资者。

风险投资是高风险高回报的：风投者相比银行对风险更加宽容，当然他们也期待你成功后的巨额回报。如果你打算获得风险投资，你应该建立股份有限公司。如果你对风险投资过程不熟悉，开始的最好方式就是询问成功获得风险投资的人。

<!--
####Pros
* Institutional support can be helpful for growing a business
* Large amounts of capital available

-->

#### 优点

* 制度上的支持对成长中的业务有益
* 大量的风投资金蓄势待发

<!--
####Cons
* Venture capital comes with expectations of an exit (i.e. returning the money to investors at a multiple). History suggests this is structurally difficult to achieve for open source businesses
* Venture capital can change motivations and distract from priorities

-->

#### 缺点

* 风险投资在投资之初便做好了获得成倍回报后退出的打算，历史证明，由于开源项目的结构特点，风险投资的成功很难。
* 风险投资者可能会因为优先级改变其动机

（译者注：在中国有一类风险投资者故意诱导涉世不深的创业者签订不平等协议，尤其是在创业者热情最浓而又最困难的时候，使其在业务失败时也能全身而退，相应的，创业者会输得很惨，值得小心对待）

<!--
####Case Studies
* [Npm](http://blog.npmjs.org/post/76320673650/funding)
* [Confluent](http://www.confluent.io/blog/confluent-raises-a-series-b-funding)
* [NodeSource](https://techcrunch.com/2015/02/09/nodesource-raises-3-million-to-build-new-programming-tools/)
* [Meteor](http://info.meteor.com/blog/announcing-our-20m-series-b-funding)

---

-->

#### 案例学习

* [Npm](http://blog.npmjs.org/post/76320673650/funding)
* [Confluent](http://www.confluent.io/blog/confluent-raises-a-series-b-funding)
* [NodeSource](https://techcrunch.com/2015/02/09/nodesource-raises-3-million-to-build-new-programming-tools/)
* [Meteor](http://info.meteor.com/blog/announcing-our-20m-series-b-funding)

--

<!--
### Contributing to this guide
I wrote up this guide to aggregate knowledge off the top of my head, but I'm not planning to make major contributions or changes. I recognize the pros/cons are somewhat subjective, but they reflect my views.

If something is factually incorrect (especially with a case study example), I welcome your edits. Also, if there's a category you know of that I missed, I would also welcome that addition.

-->

## 贡献

我写这个手册主要是为了将我头脑中的知识都整理出来，不过我并没有打算做主要的贡献或改变。优点和缺点大多是从我的观点出发的主观想法。

如果有什么错误（尤其是案例学习），非常欢迎大家的修改。同时，如果发现有什么分类漏掉了，我也非常欢迎大家的修改。

关于中文版的贡献，如果有信息上的错误或遗失，请到原文中提出，如果有中文翻译上的错误，请在这里直接提出。如果你觉得有信息上的错误或遗失，但又各种原因无法用英文表述，担心中文表述不会被采纳，这种情况请还是在原文中提出，我或者其他同时会英文和中文的小伙伴会帮助解决问题的。

本翻译项目使用[翻译辅助工具](https://github.com/wizicer/TranslationTool)辅助同步原文修订部分。

<!--
### License and attribution
This guide is available under the Creative Commons CC0 1.0 License, meaning you are free to use it for any purpose, commercial or non-commercial, without any attribution back to me (public domain). If you do use it, I'd love to hear about it! (Find me here: [@nayafia](http://twitter.com/nayafia)) But you are in no way required to do so.

-->

## 协议

原文协议为Creative Commons CC0 1.0
License，即你可以自由的使用，商业或非商业，不过如果你用了，很开心能从你那里听到点什么，在这里找到我[@nayafia](http://twitter.com/nayafia)，当然这并不是要求必须做的。

中文版协议为Creative Commons Attribution 4.0 International
License，和原文协议差不多了，基本上可以说怎么用都可以，唯一不要修改原作者名字或以原作者名字声明演绎作品就可以了。

![](https://i.creativecommons.org/l/by/4.0/88x31.png)
