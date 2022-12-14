# MetaPavo Whitepaper（中文）

## MetaPavo 是什么？

MetaPavo 是一个 Web3 个人信息助理，具备 分类管理信息/搜索/识别 等核心能力。它旨在帮助 Web3 用户快速获取对他们有用的信息。

![](<.gitbook/assets/dreamstime\_xxl\_250002267 (2).jpg>)

MetaPavo 名字源自一种孔雀品种，它生活在东南亚和南亚地区，有蓝色和绿色两种颜色。

Pavo 的形象寓意了一种整理 Web3 信息的方式，通过分层和分类两种核心手段，将信息附属于信息网络中的主体节点。最终，这种方法形成了一个单一的入口、承载无限信息的信息管理方案，同时清晰有效。MetaPavo 的核心能力无处不在地体现了这种寓意。

## MetaPavo 的产品形态

MetaPavo 的核心产品是一个 chrome 插件，它的核心模块包括默认的新开页（我们称之为 Web3 信息工作台）、注入所有页面的搜索组件、注入所有页面的一个信息识别模块。

请您放心使用它，我们会尽最大努力保护您的隐私，另外 chrome 的隐私机制同样不允许插件获取您的隐私信息。

## MetaPavo 的核心功能

### 一、个人信息工作台，聚合关注的信息，按照 Web3 的特性对信息分类

* 一个浏览器默认新开页
* 一个可编排和调整的工作台
* 一个个人关注的 Web3 信息的快速入口

<figure><img src=".gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

### 二、随时随地快速唤起搜索，搜索各类 Web3 信息

* 任意页随时唤起，搜索各种类别的信息
* 支持各种信息分类
  * NFTs, Tokens, DAPPs, KOLS, Articles, Premints, DAOs, Companys

<figure><img src=".gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

### 三、浏览既识别，在浏览时帮助你识别信息，并快速连接或采集信息

* 一个悬浮在浏览器右下角的可以变化形态的小组件
* 支持各类信息的识别和小组件
  * NFTs, Tokens, DAPPs, KOLS, Articles, Premints, DAOs, Companys, 危险识别和提醒
* 支持各种平台的信息识别
  * Opensea, Twitter, Website, Etherscan, Gem, X2V2, Looksrare, Sudoswap, ...

<figure><img src=".gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure>

### 四、信息共享和价值挖掘，为社区贡献价值并获得激励（即将上线）

* 通过简单的行为贡献信息价值评价的数据
* 通过社区的贡献评价信息价值
* 为其他用户提供实时的、准确的价值判断的信息，使他们能够更好地了解 Web3 世界

## MetaPavo 的实现机制

这里我们核心解析一下这几个机制：信息搜索、信息识别、安全识别、工作台。

### 一、信息搜索

信息搜索是 MetaPavo 的核心功能之一，它的实现机制是通过 chrome 插件的机制，将搜索组件注入到所有页面中，这样用户就可以在任意页面随时唤起搜索组件，进行搜索。

搜索的背后是一个简单的搜索引擎，它的搜索结果是从各个平台的 API 中获取的。

我们在数据服务中对各类信息进行了分类标记，为用户提供已经分类好的搜索结果。

### 二、信息识别

同样的，信息识别也是通过 chrome 插件的机制，将信息识别组件注入到所有页面中。在您浏览特定网站的时候，我们会在本地扫描页面中特定的内容，然后将其按照主体分类识别出来，例如 NFTs, Tokens, DAPPs, KOLS, Articles, Premints, DAOs, Companys 等信息，一旦识别成功，我们会获取他们的详细信息，展开信息识别组件，并将这些信息展示在信息识别组件中。

### 三、安全识别

在浏览 twitter 或者其他网站的过程中，我们会扫描并识别页面中的危险内容，例如钓鱼网站、恶意网站、伪装的 twitter 账号等，一旦识别成功，我们会以明显的方式提醒用户。

### 四、工作台

工作台利用了 chrome 插件的 new tabs 功能来覆盖浏览器默认的新开页，每次您打开一个新的空白标签页的时候，都会默认打开 MetaPavo 的工作台界面。

在此页面中，你可以搜索、查看收藏的信息、调整模块的位置和显隐等，定制属于自己的工作台。

## MetaPavo 的未来

MetaPavo 的未来是一个超级搜索引擎 + 内容互动社区 + 个人信息助理

### 一、个人信息助理

通过产品形态的进化，和更多信息内容的引入，为用户提供更方便、更随时随地、更智能的信息服务，例如 移动端的个人工作台，并且和其他平台做更为深入的打通。

### 二、超级搜索引擎

MetaPavo 的搜索引擎将会支持更多的平台数据的接入，支持更多类型数据的接入，引入更为智能的搜索算法，为用户提供更加精准的搜索结果。

### 三、内容互动社区

MetaPavo 将会鼓励用户对信息进行去中心化的评价、推荐、收藏等，将有价值的信息实时挖掘出来，并且触达给需要这些信息的用户，形成一个良性的信息价值闭环。

###



### MetaPavo 的积分和邀请

[https://app.gitbook.com/o/uDVzlEbUc4No2a3goLbv/s/6WtCEw0AEOaALLXB4oFD/\~/changes/67arttaVBiyh3tJsdn9x/metapavo-invite-and-score-rule](metapavo-invite-and-score-rule.md)
