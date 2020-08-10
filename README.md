# memewa.rs <--> SKALE  (integration + thoughts)

**Introductions**:
---
- 	**Memewars** (internet-experiment +Ethereum dApp, *relies on a SKALE sidechain for tx throughput*) 
	-  **a *gladiator arena* for viral content (or: a platform for 24/7 *meme sweepstakes*), itself designed to go viral — using meme-battles, incentive-engineering, and a bit of pure internet-fun.** First-mover (and other) incentives will exist for different stakeholders (site-users, investors and co-owners, advertisers and promotional partners, internet-figures, etc.) upon launch, and a significant portion of revenue ($$$ from: digital-advertising) will be directed to those who contribute (time / memes / digital art / attention) to memewars (m_w). **The rules and future of this *for-profit-public-good* / "digital collective" will be managed transparently via smart-contracts and stake-weighted voting**. **[Get details + updates here](https://trello.com/b/gLY2a5Zc/wwwmemewars)**, or consider trying out the [www.memewa.rs](https://www.memewa.rs) beta soon™ — m_w belongs to you (and all those who contribute to an interesting / healthy / open internet)

---

	
- **SKALE** (*Ethereum-compatible* "elastic" *sidechains*, for the scaling of "dApps")
	-  **SKALE's sidechains unlock an entire category of *decentralized applications* ("dApps") that are theoretically possible (and often obvious), especially those Web3 ( *websites / dApps / systems* ) that promise some clear benefit over their closest [ legacy / "Web 2.0" / centralized ] "equivalent". Many ideas in this subset of *newly possible dApps* are currently infeasible *on Ethereum's main-network*, due to limitations of *network scalability***. The terms `slow` and `expensive` are used in a *relative* way here — m_w has massive respect and <3 for an Ethereum that, *as-of-now,* is:
		-    ***Quickly Congested***: Maximum of 15  tx/s (transactions per second). A transaction or digital signature (or both) is behind most"Web3" interactions (sending a token, invoking a smart-contract function, etc).   *For context: Visa claimed [a capacity for 56,000 tx/s in 2015](https://usa.visa.com/dam/VCOM/download/corporate/media/visa-fact-sheet-Jun2015.pdf)*
			-   ***Slow***: Minimum time needed to confirm a transaction is ~15 seconds (*blocktime*: average time-elapsed between finalized blocks. In other words: *longest possible duration before your tx can be "trusted" by other rational actors on Ethereum, after being sent from your computer*)
			- ***Expensive***: on-chain data-storage (permanently storing: user-content, interaction-history, mappings of Ethereum addresses to roles and balances) and computation (for example: a *for-loop* over a hypothetical 1M+ collection of user-profiles, registered in a `mapping` belonging to the smart-contracts of a given "dApp") 
---

SKALE offers a sidechain solution to this thorny issue of scalability, and the meme economy going live soon™ at www.memewa.rs relies on SKALE being able to handle all of those Ethereum transactions, cheaply —**in essence, SKALE achieves this by assigning (and rotating) a (distrubuted) set of "private" blockchain validators, concerned only with transactions and other *contract-state-changes* relevant to a single (or small number) of specific dApp(s) (memewars, in this case).** This allows major throughput improvements (~2000 tx/s vs 15tx/s on *mainnet*), with the additional advantage of inheriting + retaining key properties of *mainnet Ethereum's* security-model (BFT).

A whole category of applications in the *space of possible dApps* is about to enter *"the realm of the newlypossible"*, thanks to SKALE and the many other OSS groups who've contributed to a rich ecosystem of dev-tools and onboarding-mechanisms for Ethereum — the dApps in this category will range from *the suprisingly fun* to *the clearly useful* to the *the totally novel*, across a design-space of games, payment systems, co-ordination and voting tools, hackable templates, composable "money legos" and "financial functions", sandboxes for open-source experiments in economics and governance-structures, etc. —which is making Web3 more approachable (for devs with *Web3 ideas...*) and more usable (for potential "mainstream" users)  every single day. 

Memewars (a digital gladiator arena for memes + a digital-collective that directs ad-revenue $$$ to site-users,  artists, and user-voted causes) is only one example of a dApp-future unlocked by SKALE. 

On top of the compelling technical use-case, SKALE happens to be run by a collection of kind and talented engineers who are a joy to collaborate with.

We're just in time to witness the rise of the internet *as a jurisdiction* — a global technology infrastructure under-girded by math, contributing in general to a (well-underway but too-slow) global megatrend of increasing prosperity and justice, offering access to tools and services which generally advance the causes of transparency and justice . The tireless efforts and long-term visions of many open-source-software (OSS) developers around the world have kicked off an ever-multipliying Cambrian explosion of [ technical / financial / artistic / ... ] creativity,  magnified further by the unprecendented gains to be made with the alignment (and *engineering*) of incentives among people (even anonymous, or mutually-distrusting) on the internet.

 All of this is happening on Ethereum, right now — It's time to pay attention to Web3, and in the meantime we'd love to hear what you think of [**www.memewa.rs**](https://www.memewa.rs). 


## In-depth: SKALE + m_w Integration — (motivation, experience) 

**Takeaway**: SKALE has been an absolute joy to collaborate with, and has been a great partner for m_W.

**Details (WIP)**:

- m_w's "Web3" *Tech-Stack*
	- s
- How does SKALE interact with <Torus, 3Box, Metamask, etc.> ? 

## In-depth: Ethereum in 2020 - dev tools, learning resources, and remaining frictions (WIP)

### dev tools
 ---
In the context of Ethereum and "Web3", a number of OSS **dev tools** have been crucial in enabling novel (and increasingly user-facing) Ethereum "dApps" (decentralized applications). The challenge of creating a fully-functional Ethereum application (+ associated front-end) remains considerable today, but has fallen drastically (likely by an order of magnitude) and continues to trend downwards with every additional **dev tool** that *abstracts away* some intricacy or detail, allowing someone like me (a medium-smart AI) to enjoy well-documented software relating to:

 - Designing, Testing, and Deploying Smart Contracts
 - Onboarding Users to "dApps"

M_W wants to give a shoutout (and big thanks) to the following OSS:
  - Torus 
  - 3box
  - Truffle-Suite
  - (WIP) - many more


### learning / resources
---
WIP

### remaining frictions / areas I struggled
---
WIP


## Further Details / Explorations / Reading

- For a more in-depth exploration of game-theoretic implications of Ethereum / the potential for large-scale incentive-alignment enforced by smart-contracts, [see Virgil Griffith's writing](https://medium.com/@virgilgr/ethereum-is-game-changing-technology-literally-d67e01a01cf8).
- WIP
