# www.memewa.rs <-> SKALE = ?
<pre>                           
                       __      __                 __                  ____        __  __      ______      __         ____                                          _    
 /'\_/`\              /\ \  __/\ \               /\ \                /\  _`\     /\ \/\ \    /\  _  \    /\ \       /\  _`\                _______               /'_`\  
/\      \             \ \ \/\ \ \ \              \_\ \___            \ \,\L\_\   \ \ \/'/'   \ \ \L\ \   \ \ \      \ \ \L\_\             /\______\             /\_\/\`\
\ \ \__\ \             \ \ \ \ \ \ \            /\___  __\            \/_\__ \    \ \ , <     \ \  __ \   \ \ \  __  \ \  _\L             \/______/_            \/_//'/'
 \ \ \_/\ \             \ \ \_/ \_\ \           \/__/\ \_/              /\ \L\ \   \ \ \\`\    \ \ \/\ \   \ \ \L\ \  \ \ \L\ \             /\______\              /\_\ 
  \ \_\\ \_\             \ `\___x___/               \ \_\               \ `\____\   \ \_\ \_\   \ \_\ \_\   \ \____/   \ \____/             \/______/              \/\_\
   \/_/ \/_/  _______     '\/__//__/                 \/_/                \/_____/    \/_/\/_/    \/_/\/_/    \/___/     \/___/                                      \/_/
             /\______\                                                                                                                                                  
             \/______/
</pre>
# integration details  +  *devThoughts™*

***tl;dr:** the internet's future is being constructed on Ethereum today*
---

**Thanks to SKALE and many other OSS efforts, an entire category of Ethereum dApps are entering *the realm of the newly possible*. Possible use-cases include: payment systems, co-ordination and voting tools,  composable "money lego"  functions,  sandboxes for experimentation with [ economics / governance / profit-structures / ... ].**  Builders and hackers stand to benefit from an ever-expanding ecosystem of Ethereum / "Web3" open-source-software tools + integrations, which allow a "lone" developer to create powerful digital-systems.
  
**Memewars is a "digital arena for meme-battles and viral sweepstakes"** which will direct ad-revenue $$$ to site-users  (participants / artists + contributors / etc.) **and represents a single example of *a dApp (+DAO) enabled by SKALE***. When it launches (*... soon™...*), a potentially-unbounded *meme economy* will require high-throughput (tx/s) to support and encode [ *meme-battles* / <_format_> contests / voting-logic / stakeholder platform-governance-by-token / site ownership and history-referencing / programmatic (conditional) distribution of roles + assets / player accounts and *$XP* / etc ].

**The Ethereum / "Web3" ecosystem grows more accessible** (for developers and "normal" users) every day, and **SKALE sidechains will accelerate a Cambrian explosion of technical creativity currently unfolding on Ethereum. When SKALE is combined with an onboarding solution like Torus** (*where users can generate / use an Ethereum-wallet by logging into a reddit / $website account, then buy cryptocurrency with a debit-card*), **a number of hurdles that have long plagued *mainstream Ethereum adoption*  suddenly appear surmountable...**

---
<div class="introductions">
**Introductions**
</div>
---
- 	**Memewars** (internet-experiment / Ethereum dApp, *relies on a SKALE sidechain for tx throughput*) 

	-  **A digital "gladiator arena" for *meme-battles*** (a platform for 24/7 *viral-content sweep$takes*), **itself designed to go viral** *with fun + incentives.*
	- **Pays out $** (transparently) **to site users** (*spectators / voters / contestants*) and **artists / coders / translators / promoters / early partners** who contribute to the *m_w universe* or otherwise 🚀 help m_w get big  🚀. 
	- **Context:** $150B+ in online-ad $ will be "earned" by social-media megacorps (ft. dusty vampire shareholders) in 2020. **Internet ads derive their value from *your (!) traffic, data, and memes*, yet TikTok / FB / $platform has never sent you a micro-crumb of a dollar, or granted you a microscopic share of ownership. We could create...
    - **New Structures:** a *for-profit digital collective* that's also a *public-good*, directing $ from online-advertising-campaigns to the (digital) wallets of meme-lovers / digital artists / open-internet causes / "normal" people in a way that hasn't been tried (or possible) before. **Ownership incentives for [ users / potential-investors / internet-figures ]** will be announced before launch.  [More info / get updates re: beta + launch details](https://trello.com/b/gLY2a5Zc/wwwmemewars).

---

- **SKALE** (*elastic* *sidechains* which allow Ethereum dApps to scale)

	-  **Unlocks an entire category of *use-cases* in "the space of possible dApps", especially Web3 (*platforms / structures / smart-contract systems* ) which promise some clear benefit (often: cost-savings / incentive-alignment / efficiency / data-control) over their closest "legacy" (Web 2 / centralized) *equivalents*, but which are *currently* infeasible *on mainnet Ethereum* due to network scalability limitations.** The terms below (`slow` and `expensive`) are used in a *relative* sense — m_w has massive respect and big <3 for an Ethereum that, *as-of-now,* is:
		-   ***Quickly Congested***: Maximum of 15  tx/s (transactions per second). A transaction or digital signature (or both) is behind most"Web3" interactions (sending a token, invoking a smart-contract function, etc).   *For context: Visa claimed [a capacity for 56,000 tx/s in 2015](https://usa.visa.com/dam/VCOM/download/corporate/media/visa-fact-sheet-Jun2015.pdf)*
		-   ***Slow***: Minimum time needed to confirm a transaction is ~15 seconds (*blocktime*: average time-elapsed between finalized blocks. In other words: *longest possible duration before your tx can be "trusted" by other rational actors on Ethereum, after being sent from your computer*)	 
		- ***Expensive***: on-chain data-storage (permanently storing: user-content, interaction-history, mappings of Ethereum addresses to roles and balances) and computation (for example: a *for-loop* over a hypothetical 1M+ collection of user-profiles, registered in a `mapping` belonging to the smart-contracts of a given "dApp") 

---

## In-depth: SKALE + m_w Integration — (motivation, experience) 

**Takeaway**: In addition to the technical gap filled by SKALE's platform, the team is composed of highly-skilled engineers who are a joy to collaborate with.  

**Technical Details**:
- the Web3 *tech-stack* behind m_w
	- TODO
- How does SKALE interact with <Torus, 3Box, Metamask, etc.> ?
	- TODO 

## In-depth: Ethereum in 2020 (dev tools / reflections on "*Mastering Ethereum*" and building on Web3)

### *dev-tools* and the next *hype-cycle*
In the context of Ethereum and "Web3", a number of OSS **dev tools** have been (and will continue to be) crucial in enabling novel (and increasingly user-facing) Ethereum "dApps" (decentralized applications). The challenge of creating a fully-functional Ethereum application (+ associated user-interface) today remains considerable, but has fallen dramatically and continues to trend downwards with every **dev tool** that *abstracts away* some confusing detail involved in "blockchain development", allowing someone like me ( *Zoom University, class of 202? - and a medium-smart AI to boot*) to learn enough to create www.memewars in about 1 year of concerted effort (TODO - link to specific timeline of learning). This was only possible because I enjoyed many tutorials + resources + tools that sufficiently simplified:

- Learning Ethereum (Solidity) Programming
	-  CryptoZombies / "Mastering Ethereum" book / (TODO: more)
 - Writing + Testing + Deploying (Solidity) Smart Contracts 
	 - Truffle Suite / OpenZeppelin / (TODO: more)
 - Onboarding of "mainstream" users to applications which use cryptocurrency and/or digital signatures 
	 - Torus / 3Box / (TODO: more)
- TODO: more

M_W sends sincere^jumbo thanks to the many (mentioned and unmentioned) open-source-software (OSS) packages that it relies on. Sustainable funding-mechanisms for OSS  is an area of interest / potential for those who view Ethereum as 'rails' or as 'infastructure' for a better (along some dimension) or *more sustainable* society in general. And for good reason — a lot of the world depends on OSS which is surprisingly resource-poor or whose maintenance falls on small teams who do not receive compensation *appropriate* for the importance of their software. M_W users will (eventually) be able to allocate some % of site-revenue to OSS / other dApps / <insert_cause_here> ("public-good"), but remains open to advice which might inform a (broad) effort to support OSS and defenders of the open-internet.

A big THX to :
  - SKALE
  - OpenZeppelin
  - Torus 
  - 3box
  - Truffle Suite
  - TODO: more
---


### Learning Web3 + resources 
- TODO


### Remaining hurdles 
- TODO

### Misc Thoughts + Inspiration behind m_W

We're just in time to witness the rise of the internet *as a jurisdiction* — a global technology infrastructure under-girded by math, generally contributing to a global megatrend (well-underway, but too-slow) of increasing prosperity, transparency, and justice. The aforementioned Cambrian explosion of [ technical / financial / artistic / ... ] creativity unleashed by Ethereum is further magnified  by the unprecendented gains that can be found in the alignment (and *engineering*) of incentives among individuals on the internet, even when anonymous / mutually-distrusting.

## Further Details / Explorations / Reading

-  [see Virgil Griffith's writing](https://medium.com/@virgilgr/ethereum-is-game-changing-technology-literally-d67e01a01cf8) for an exploration of the game-theoretic implications of Ethereum: the potential for large-scale incentive-alignment enforced by smart-contracts and "deposit slashing" to dis-incentivize deviations from some *more-globally-optimal* action that would otherwise not be performed (due to *misaligned incentives* or *co-ordination failures*)
- TODO
