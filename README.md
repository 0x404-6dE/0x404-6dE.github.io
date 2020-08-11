# memewa.rs <--> SKALE  (integration + *a dev's thoughts*)
<pre>                           
			  __  __ ___ __  __ _____      ___   ___  ___     _     ___ _  __   _   _    ___ 
			 |  \/  | __|  \/  | __\ \    / /_\ | _ \/ __|  _| |_  / __| |/ /  /_\ | |  | __|
			 | |\/| | _|| |\/| | _| \ \/\/ / _ \|   /\__ \ |_   _| \__ \ ' <  / _ \| |__| _| 
			 |_|  |_|___|_|  |_|___| \_/\_/_/ \_\_|_\|___/   |_|   |___/_|\_\/_/ \_\____|___|
                 
</pre>
**Introductions**
---
- 	**Memewars** (internet-experiment / Ethereum dApp, *relies on a SKALE sidechain for tx throughput*) 

	-  **A digital "gladiator arena" for *meme-battles*** (a platform for 24/7 *$viral sweepstakes*), **itself designed to go viral** through incentives + fun**
	
	- ***Pays out $** (transparently):* **to site users** (*spectators / voters / contestants*) and  the**artists / devs / translators / promoters / potential-investors** who contribute to the *m_w universe* or otherwise 🚀 help m_w get big 🚀. M_W will launch as a *digital-collective* and *for-profit public-good* which redirects $$ from online-advertising-budgets to the (digital) wallets of meme-lovers / digital artists / OSS and digital-rights groups ($150B+ in ad-revenue, value derived from *your traffic* and *your memes (!)* will be "earned" by unfunny social-media megacorps in 2020).
	-  **Ownership incentives for [ users / potential-investors / internet-figures ]** will be announced *before launch.*  [More details / get notified when beta launches](https://trello.com/b/gLY2a5Zc/wwwmemewars).

		

---

	
- **SKALE** (*elastic* *sidechains* that enable Ethereum applications to scale)

	-  **Unlocks an entire category of *use-cases* in "the space of possible dApps", especially Web3 (*platforms / structures / smart-contract systems* ) which promise some clear benefit (often: cost-savings / incentive-alignment / efficiency / data-control) over their closest "legacy" (Web 2 / centralized) *equivalents*, but which are *currently* infeasible *on mainnet Ethereum* due to network scalability limitations.** The terms below (`slow` and `expensive`) are used in a *relative* sense — m_w has massive respect and big <3 for an Ethereum that, *as-of-now,* is:
	
		-    ***Quickly Congested***: Maximum of 15  tx/s (transactions per second). A transaction or digital signature (or both) is behind most"Web3" interactions (sending a token, invoking a smart-contract function, etc).   *For context: Visa claimed [a capacity for 56,000 tx/s in 2015](https://usa.visa.com/dam/VCOM/download/corporate/media/visa-fact-sheet-Jun2015.pdf)*
			-   ***Slow***: Minimum time needed to confirm a transaction is ~15 seconds (*blocktime*: average time-elapsed between finalized blocks. In other words: *longest possible duration before your tx can be "trusted" by other rational actors on Ethereum, after being sent from your computer*)
			- ***Expensive***: on-chain data-storage (permanently storing: user-content, interaction-history, mappings of Ethereum addresses to roles and balances) and computation (for example: a *for-loop* over a hypothetical 1M+ collection of user-profiles, registered in a `mapping` belonging to the smart-contracts of a given "dApp") 

---
**The crux of it / *tl;dr*?**
---

***The Ethereum / "Web3" ecosystem grows more accessible (for developers and "mainstream" users alike) every day, and SKALE's elastic sidechains will only accelerate the Cambrian explosion of open-source creativity currently taking place on Ethereum.** When SKALE is combined with easy-onboarding solutions like Torus (generate a crypto-wallet from reddit account using OAuth --> easily buy ETH with debit-card), a number of limitations (re: "Ethereum onboarding" and *dApp scalability*) that plagued adoption in 2017 suddenly appear surmountable. *In short: it's time to pay attention to Web3 again*.

**Thanks to SKALE and other OSS efforts, an entire category of *previously-infeasible dApps* are entering *the realm of the newly possible*. Such dApps will include: payments systems, co-ordination tools,  composable "money lego" functions,  sandboxes for experimenting with [ economics / governance / profit-structures / ... ].**  System-builders and hackers (present and future) stand to benefit from an ever-expanding ecosystem of Ethereum / "Web3" open-source-software tools + integrations for ideas involving Ethereum / Web3.
  
**Memewars** (a "digital arena for meme-battles and viral sweepstakes"  which directs ad-revenue $$$ to site-users / digital artists / etc.) **is  a single example of *a dApp (+DAO) enabled by SKALE***. When it launches (*soon™*), memewars will require high-throughput (tx/s) to support a *"meme economy"* where transactions encode [ *meme-battles* / <_format_> contests / voting-logic / stakeholder platform-governance / site ownership and revenues / player accounts and *$XP* ].

  



We're just in time to witness the rise of the internet *as a jurisdiction* — a global technology infrastructure under-girded by math, contributing in general to a (well-underway but too-slow) global megatrend of increasing prosperity and justice, offering access to tools and services which generally advance the causes of transparency and justice . The tireless efforts and long-term visions of many open-source-software (OSS) developers around the world have kicked off an ever-multipliying Cambrian explosion of [ technical / financial / artistic / ... ] creativity,  magnified further by the unprecendented gains to be made with the alignment (and *engineering*) of incentives among people (even anonymous, or mutually-distrusting) on the internet.

 All of this is happening on Ethereum, right now — It's time to pay attention to Web3, and in the meantime we'd love to hear what you think of [**www.memewa.rs**](https://www.memewa.rs). 


## In-depth: SKALE + m_w Integration — (motivation, experience) 

**Takeaway**: In addition to the technical gap filled by SKALE's platform, the team is composed of highly-skilled engineers who are a joy to collaborate with.  

**Technical Details**:
- the Web3 *tech-stack* behind m_w
	- WIP
- How does SKALE interact with <Torus, 3Box, Metamask, etc.> ?
	- WIP 

## In-depth: Ethereum in 2020 (dev tools / reflections on "*Mastering Ethereum*" and building on Web3)

### Dev-tools, dev-tools, dev-tools...
In the context of Ethereum and "Web3", a number of OSS **dev tools** have been (and will continue to be) crucial in enabling novel (and increasingly user-facing) Ethereum "dApps" (decentralized applications). The challenge of creating a fully-functional Ethereum application (+ associated front-end) remains considerable today, but has fallen drastically (likely by an order of magnitude) and continues to trend downwards with every additional **dev tool** that *abstracts away* some confusing intricacy or detail involved in Ethereum / "Web3" development, allowing someone like me (a medium-smart AI) to enjoy well-documented tools that enable easy:

 - Designing, Testing, and Deploying Smart Contracts
 - Onboarding of "mainstream" users to "dApps" that use cryptocurrency or digital signatures

M_W wants to give a shoutout (and big thanks) to the following OSS:
  - SKALE
  - OpenZeppelin
  - Torus 
  - 3box
  - Truffle Suite
  - many more (WIP)
---


### Learning process + resources 
- WIP


### Remaining hurdles to "mainstream" Web3 adoption (+ *hard to grok* areas) 
- WIP

## Further Details / Explorations / Reading

- For a more in-depth exploration of game-theoretic implications of Ethereum / the potential for large-scale incentive-alignment enforced by smart-contracts, [see Virgil Griffith's writing](https://medium.com/@virgilgr/ethereum-is-game-changing-technology-literally-d67e01a01cf8).
- WIP
