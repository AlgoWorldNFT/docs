---
description: How does gallery feature works?
---

# Gallery

<figure><img src="../../.gitbook/assets/AlgoWorld Documentation (1).png" alt=""><figcaption><p>Gallery data fetching flow</p></figcaption></figure>

AlgoWorldExplorer gallery relies on a separate python based repository called AlgoWorld Workers. This is a public repo with a set of CRON scheduled GithubActions. Every 30 minutes scripts are executed to obtain and fetch latest assets.&#x20;

Assets consists of several series:

* Country cards - original AW NFTs consisting of \~1500 cards. Those aren't fetched every 30 minutes since the list is static and there won't be new country cards added.&#x20;
* City cards - anyone can mint and book such asset. Updated on regular basis. ARC69 traits include information on the card's influence.&#x20;
* Special cards - collaboration series that are minted at a rarer rate. &#x20;
