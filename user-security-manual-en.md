# User Security Manual(en)

## User Security Manual

1. This plug-in will apply for the following browser permissions from you. **All permissions are used transparently and will not involve any user sensitive data operations**.
   1. **tabs permission, used to open the login page**, in addition, the gas data is uniformly obtained in the plug-in, and sent to all pages, and the real-time gas fee is displayed at the bottom right corner of the page all the time.
   2. **storage permission**, this permission **is used to store some cached data**, such as user sessions and a small amount of cached data.
   3. **topSites permission**, obtain the most frequently used websites of users, and display these websites in the new page for easy use.
2. This plugin will replace your newly opened page by default, of course you can also choose not to replace, but most of the functions will be lost.
3. Apart from this, we will not apply for any other permissions, and we especially emphasize the following:
   1. Due to browser restrictions, **we do not have permission to read and write to the user's clipboard**, but we still recommend that you do not copy and paste the private key on the computer, which is a very unsafe behavior.
   2. The browser plug-in is a sandbox environment, **we cannot obtain the content of the program running on your webpage**, including the MetaMask instance injected into the page, etc. At the same time, **we cannot obtain the data of any other plug-ins\* \*, such as wallet plug-in data, you can use our plug-in with confidence. **This is the security guarantee provided by the browser, and it is a limitation that plug-ins cannot break through. \*\*
4. What will we obtain in order to realize our basic functions?
   1. When you use our more in-depth functions, we **require you to log in with your wallet and make a plaintext signature**, **this plaintext signature will be used to verify that you have control of your wallet, and all users who need to log in Web3 APP will have this step, which is safe**. We will generate a unique user ID for you on the server side, and your favorite items and alarm clocks can be synchronized on different devices in the future.
      1. This operation only requires the wallet to make a clear text signature once, and will not initiate any real transactions. **Our only purpose is to verify that you are the owner of the wallet** to generate a unique user on the server.
      2. After using the wallet to sign once, your login status will be retained within 7 days, and there is no need to re-sign.
      3. During this process, the only data we obtain is your wallet address and the signature of the plaintext signature.
   2. The core function of MetaPavo is to efficiently identify more Web3 related information of the current webpage for you, and display it for you. The implementation logic is as follows:
      1. For the Twitter personal homepage, we will get the Twitter id on the page, and then initiate a request to verify whether there is a project that is an affiliated party of this Twitter, and return the project information. At this time, the MetaPavo ball at the front end will slide out the project information.
      2. For trading platforms (OpenSea, x2y2, gem, sudoswap, looksrare, etc.), we will first match the contract address, project name, tokenId from the URL, and then send this information to the server to query related project information. After the query is successful , the front-end MetaPavo ball will slide out item information.
      3. For other websites, we will obtain the URL of the website and send it to the server to query relevant project information. After the query is successful, the MetaPavo ball at the front end will slide out the project information.
      4. Our plug-in provides the History function to facilitate review of recently viewed items, and the data is currently stored locally.
      5. Statement 1: \*\*In the process of sending information query items to the server above, we will only do data query, and will not transfer and store any data that can be associated with users. We also do not use technologies such as cookies to track you at all. \*\* Therefore, we cannot obtain the specific access behavior of users, we do not need these data, and we will not record these data.
      6. Statement 2: At present, most of the most common information assistance plug-ins on the market will obtain page information for data query and display. \*\*

### How do we ensure security?

#### This project is maintained by [LXDAO](https://lxdao.io/)

- **LXDAO is a Web3 DAO organization that focuses on research and development**. LX = conscience is our core value, we hope to do some valuable and meaningful projects for Web3.
- We are collaborating in a Web3 way to create some useful and valuable Web3 products for Web3 users. \*\*
- **LXDAO's products are supervised by the community and the whole process is open and transparent**. Most of the code will be open source. **Everyone can apply to join LXDAO and deeply participate in project development. **
- **LXDAO's products have no technical and commercial needs to do evil**, because the project team members come from the community, and everyone's interests are the same. This is also one of the advantages of Web3 collaboration.

#### We will open source the plugin code

- At present, considering the rapid modification and code quality, we have not open sourced yet. If you are interested and able to contribute or audit, you can contact us to pull your GitHub account into the project.
- After finishing our internal testing and producing a stable version, **will sort out the plug-in code and make it open source, then everyone can audit the code to see the specific implementation logic**. We will also release it through official channels such as the plug-in store.

#### Summarize

1. We don't get any redundant permissions like clipboard, etc. All permissions are listed.
2. We cannot obtain the JS environment on the page you browse, nor can we obtain and control the content and data of other plug-ins. **This is guaranteed by the isolation mechanism of browser plug-ins, which we cannot do even if we want to. **
3. We will not save query data that can be associated with your account.
4. We don't need your wallet to initiate any transactions. **Connecting to the wallet requires only one clear text signature, which is only used to verify that you have control over the wallet**.
5. **MetaPavo is initiated and maintained by LXDAO**. It is a DAO-based, community-driven product, open and transparent, and has no need for evil.

#### Disclaimer:

During the product iteration process, some functions and logic will change as community feedback and demands increase. Project team members will try to update this document in a timely manner, there may be delays or inconsistencies. ** But what remains unchanged is that as a DAO, we remain open and transparent and welcome anyone to apply to join. We welcome the community to raise questions and discuss, because this can truly make the product more successful, bring more benefits and a safer experience for everyone . This is one of the reasons why we use the Web3 way to create and maintain products. **
