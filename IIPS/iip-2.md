---
iip: 2
title: Improved Personal Performance Report Features
author: RayQuin
status: Draft
category: Platform
created: 2018-07-04
---

<!--You can leave these HTML comments in your merged IIP and delete the visible duplicate text guides, they will not appear and may be helpful to refer to if you edit it again. This is the suggested template for new IIPs. Note that an IIP number will be assigned by an editor. When opening a pull request to submit your IIP, please use an abbreviated title in the filename, `iip-title_abbrev.md`. The title should be 50 characters or less.-->

## Description
<!--Provide a simplified and layman-accessible explanation of the IIP.-->
As part of the ICONOMI 2018 roadmap, a major upgrade for user statistics is planned. ICONOMI have made some progress already with this.

>The first phase of this upgrade has been implemented: full price history with charting is now available, as well as several additional indicators.  
[Source.](https://medium.com/iconominet/development-overview-q2-2018-fd11fc14388b)

These upgrades have made it easier for users to assess the performance of the performance of individual DAAs on the platform. So far there has not been a corresponding upgrade to a user's aggregate performance page, under the portfolio tab of the platform.

This IIP proposes unifying reported equity performance information and additionally providing the user with more powerful and varied tools to assess their equity performance, including comparing DAA performance at-a-glance with Bitcoin and Ethereum.


## Motivation
<!-- The motivation should clearly explain why the existing system is inadequate to address the problem that the IIP solves. -->
### 1. Information disparity
ICONOMI provide a variety of information about performance of an individual investor's equity. The majority of this 'floats' through time with the user, for example the 3 month performance of a DAA. Some information on all-time performance of individual DAAs is available.

However, not all information is available for all holdings on the platform - most notably the lack of any performance information on digital assets held outside of DAAs, and the lack of historic performance information for the investor's portfolio as a whole.

##### Currently, a user can find the following information on their equity performance once logged into the ICONOMI platform:

Current Portfolio total value - available on most pages.  
Current aggregate Digital Assets value and aggregate DAA values - available on portfolio page.  
Individual DAA holding $/% profit/loss taken, current, and all time - available on individual DAA dashboard page.  
Current Individual Digital Asset value - available on portfolio page.  

##### A user can not find:

Historic Portfolio total value.  
Historic aggregate Digital Assets value and aggregate DAA values.  
Historic Individual DAA holding profit/loss taken, current, and all time as measured against digital assets, such as BTC or ETH, rather than the Dollar.  
Historic Individual DAA holding profit/loss taken, current, and all time as measured against other fiat currencies, such as the Euro, rather than the Dollar. 
Historic Total Portfolio $/% profit/loss taken, current, and all time, and also as measured against digital assets, such as BTC/ETH.  
Historic Individual Digital Asset value.  

*This IIP proposes that the features that cannot be found currently by users are of value to investors, and so to the platform, and ought to be made easily discoverable to users.*

### 2. Charting and Comparison Tools
On the 'Compare' tab on the ICONOMI platform, it is possible to compare any two DAAs with each other. It is not however possible to compare a DAA with an individual Digital Asset, such as Bitcoin or Ethereum.
It may be an effective tool both for existing and prospective users to easily access this information. Additionally, as this page is available without being logged into the platform, it would aid in creating a compelling pitch to new investors.

If a DAA is consistently outperforming BTC/ETH over time, that should be shouted from the rooftops and used to explain the value and importance of diversification. If a DAA is consistently under-performing the market, then both potential investors and the DAA manager should be aware of that. Several DAA managers specifically say that their goal is to outperform the market - but right now neither they nor the community have an easy way of measuring performance and seeing whether they're achieving that goal or not.

*This IIP proposes that the additional functionality of comparing DAAs to BTC and ETH will be a valuable feature for the platform and for its users.*


## Research
<!--Showing test cases, examples or research of how and why the idea has worked before (in other projects or other walks of life) will help strengthen the case for the IIP.-->
Having consulted with other members in the ICONOMI rocket.chat, there is general community support for these suggestions to be implemented on the ICONOMI platform. 
