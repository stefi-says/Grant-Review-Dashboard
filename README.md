# Grant-Review-Dashboard

It has been a while since Gitcoin DAO and the public good defendoors have recognised the importance and neccesity of the development of automated tools that assist in the distribution of public goods. The Grant Review dashboard seeks to accelerate the automation of grant reviews in Gitcoin rounds thus empowering grant owners to manage and analyze the grant applications in a more resource efficient way for all the parties involved in the rounds. 

Luckily the ODC has created the Sandbox initiative, thus people that have a passion for defending public goods have organically organized themselves to start this project independently. The project is build on the open source projects of numerous amazing individuals and accepts other members if they are interested in our work.✨ 

- Created from the [sandbox team proposal](https://forum.opendatacommunity.org/t/sandbox-team-proposal/30/2)
- [Discord channel](https://discord.com/channels/1037443230993743902/1087749094207930389)

### What is the Grant Review Dashboard?  

An open source dashboard that aims to progresivally lead to the automation of grant reviewing/screening before/during the Gitcoin rounds by using and developing a series of Lego analysis on grants that participate in Gitcoin Rounds. Of course we might adapt and evolve along the way as the program is still in the Beta phase and many aspects of it may change. It is very likely that the Grant Review Dashboard will work together with a review protocol that involves actual reviewers that have experience related to the scope of the rounds or want to participate in the defense of public goods.

### Objective:  

The project aims to build a modular, configurable open source dashboard that will assist round owners by automatically screening grant applications in the Gitcoin rounds by detecting various proven suspicious/malicious behaviors related to grant fraud. Over time we might also add functions that will also signal really good grant applications thus enabling almost instant approval for them. As you may know Gitcoin distributed over 75m$ to public goods and it's very likely this number will only grow in the future => it's more important than ever to develop these tools as the program grows.

### Who can use this:  

Gitcoin is the best web3 crowdfunding platform recently launched the Allo [protocol](https://docs.allo.gitcoin.co/getting-started/introduction). By using this tool all the round owners of the Allo protocol will save time and resources by screening out bad grants from their rounds. Grantees hugely benefit also because by filtering out bad grant applications in time they get more matching allocated to them. Gitcoin DAO would also be empowered by the success of this tool as it might save a lot of hard working people working on grant approvals a lot of time!


### Contribution(also important for hackaton participants):  

How to get involved? Well, if you like challanges you are in for a huge one, the Grant Review Dashboard is a very complex project and it remains largely an unsolved problem because it involves multiple areas such as: 
-sybil attacks are an unsolved problem 
-it is a red team-blue time scenario in which even if you lived in a universe where sybils are completely destroyed, people will still find ways to emulate the behaviour of real project as long as the incentives are appealing
-anti grant fraud automation, involving turning signals into [Legos](https://gov.gitcoin.co/t/public-goods-legos-roadmap/12546) 
-creating a LEGO logic that will flag the grants with a level of accuracy and precission that make the dashboard trustworthy 
-pulling and working with onchain data that can be visualized on the Dashboard in a timely manner

Examples of signals for Grant Review legos:
-Github activity of the grant creator
-Check if the website is online
-analyze website data
-analyze onchain behaviour 
-analyze twitter data
-Does he have a Passport with a score over at least 22
-analyze correletions between all of the above
-etc

Check out more info about Sybil Legos [here](https://opendatacommunity.org/docs/legos/) to get inspired

If you read until here and still are confused?(which is very likely, we are also sometimes 🙃) we would recommend taking a look at these anti-sybil dashboards built by the amazing people that participated in past ODC Hackatons:
[GrantLooker-by Kikura](https://www.grantlooker.xyz/projects) - this project provides a interesting functional solution overall, read more about it [here](https://github.com/kikura3/gtclooker)
[Anti-Sybil Dashboard - by Rayfront](https://dashboard-e9cf.vercel.app/) - this one is a cool example of a clean way to visualize the grant round data from past rounds
 
If you wanna join us come say hello in our [Discord](https://discord.gg/bUBExSASBw) channel or check out our issues on Github🙂

###Rough milestones*

1. Creating a grant review dashboard that clearly signals which grants are clear NOs via a couple of Legos(MVP)
2. Developing a grant review dashboard that can be used in the next Gitcoin Round(at least for one of the rounds)
3. Enlarging the scope and making sure the dashboard is configurable enough and can be used by multiple round owners to signal bad grant applications
*modifications can appear along the way 
