### **GovNo Townhall Meeting 1 Notes**

### Date: December 14th, 2023

[Link to recording](https://x.com/Allinbits_inc/status/1735383245787701589?s=20)

Meeting notes from the first GovNo townhall.

Action: Create Discord moderation policy and setup

- **Introduction: What is the [GovNo](https://github.com/atomone-hub/genesis/issues/71) chain: definition, purpose, utility**
    - GovNo is primarily a governance chain, with the design to get a large consensus amongst the No/NWV voters on what and how AtomOne should work
    - Purpose of GovNo is to find sentiment and get direction
    - Why GovNo? The genesis for AtomOne and GovNo stems from prop 848, which defined a split. No/NWV voters are key, and AtomOne wouldn’t make sense if there wasn’t support from No/NWV voters on this proposal.
    - GovNo is not governance for AtomOne, but a way to bootstrap governance to kick it off
    - What is AiB’s part? We are a participant and contributor in GovNo having voted No on prop 848, along with many members of the community, and you are an equal in this project;we want to facilitate a way for the No/NWV vote community to speak out. We are primarily here to serve and moderate the discussion on No/NWV voters.
    - For building GovNo, we should consider our available tooling
- Audits: important, but as there is no central authority it isn’t always done, so everyone has to be cautious about the technology they are using
- Questions, we need to answer:
- How much support do we need from No/NWV voters? We need to find the right answers to find consensus among No/NWV voters
- What ratio of Yes and No/NWV voters should be included in AtomOne?
- **Define the Governance Token**
    - **GovNo token and the governance structure:**
        - The purpose of the GovNo chain, token and structure is to help us answer questions and coordinate together
        - We don’t have the infrastructure to deal with per person uniqueness, so anything to modify distribution will end up creating distortions that other people will exploit. Example: Bot accounts ended up voting yes - 164,000 yes voters and 6,867 No voters.
        - NWV for purity will receive the same as No voters and those that abstained could also receive a proportionate amount..
        - Proposal for a two step distribution: GovNo token to be distributed only to NWV and No and they can decide to increase the distribution to share with delegators who didn’t vote but inherited the vote from their validators
        - Proposal for $ATONE distribution, abstainers and non voters to receive 50% of the rewards that No voters receive and on top of that a slight penalty for not participating that shouldn’t be significant and open to making it 0. Why? You don’t want to force people to vote.
    - **GovNo governance vs. Cosmos Hub governance**
    - **Who are the members of GovNo?**
        - No voting members and NWV voters
    - **How will the voting system work?**
        - Start simple, minimal modifications to the Cosmos governance module. Over time, we can iterate and improve it.
        - We can create a multitude of GovNo chains, maybe throw them away, but ultimately the community will select the primary GovNo chain.
        - It is important to not require new tooling to use the system. However, if there is new software, it could be a vulnerability at this time since we are loosely coordinated. There is no central authority to audit the software, so we have to be cautious.
        - Suggested change: In terms of editing code, it is to increase governance duration. Let's consider infinite duration, all proposals last forever and you can change your votes or even create a duplicate because you want a new measure.
- **GovNo and AtomOne:**
    - **What is the relation between GovNo and AtomOne?**
        - We fork the chain of Gaia, GovNo chain, we don’t make a lot of changes, the governance proposals on GovNo shouldn’t have much effect.
    - **How is GovNo contributing to AtomOne?**
- **How to contribute to GovNo:**
    - **Validators**
        - Should disclose relations without validators, this is required and if related should follow certain rules so there is independence among split validators.
        - If a validator and associations are too big, we find a way to cap group validators, because what we want and need is more or less equal full size validators unless we make it explicit.
        - In the constitution, we need to clearly state the rules or the rails for decision making and require full disclosure on chain that might be enough.
    - **If you are a member:**
        - Contribute early on GitHub
        - Make contributions and propose ideas
    - **If you are an external contributor (but not a member)**
        - Contribute early on on GitHub
        - Make contributions and propose ideas
- **Self organization and autonomy**
    - **How can you advance discussions and contributions**
        - Ideally GitHub for discussion and topics that they would like to contribute to
        - AtomOne arguably should be allowed to be called AtomOne regardless of ICF
        - AtomOne is consistent with writings during Atom2, a minimal hub
        - AiB should not own it, start with No voters and grow
        - Link to all forks from atom one repo
        - Community creating a split and using GovNo and everyone can play a role here
    - **What is the best way for people to self organize?**
        - **Are there dedicated channels to stay in touch with the current development?**
            - Discord, and build a Discord moderation policy
    - Are there dedicated channels to stay in touch with the current development?
        - GitHub and Discord will be the main ones.
- **What’s next?**
    - **Discord issue on GitHub to build the guidelines and then appoint someone from the community to open it**
- Create Discord channel
- Discuss there where and when for the next townhall
- Discord. Markdown file
- Gabriel suggests proposals on branding and identity of AtomOne and GovNo this will affect the channels
- GitHub is the place to have permanent discussion, move from Discord to GitHub. Discord is the live chat medium.

**Questions and discussion from community during the townhall Q&A:**

- If you have delegated and did not vote on prop 848 but your validator voted NO, should you receive GovNo tokens?
    - GovNo is a sentiment chain
    - Proposal is to focus on the votes without delegation
    - Fork Gaia, create GovNo chain, don’t make a lot of changes
        - Primary purpose is to understand the sentiment of the community
        - Increase the threshold to 67% from 50%+1
        - Snapshot of GovNo- limited to the NO voters at the limit of #848
        - GovNo- the GovNo chain ideally should not be transferable to preserve the initial distribution set
    - We should not count validator delegations, GovNo is a sentiment chain, we don’t know who to delegate to
    - How can we delegate and trust that delegation system? Because of that it’s better to focus on votes without delegation.
    - Chain is called GovNo, GovNo is staking token, distribution to be decided
    - Minimal changes, proposals on GovNo have little effect, not trying to change parameters or improve the chain but the primary purpose is to understand what portion of the chain believes this or that.
    - Nothing is really decided on GovNo until there’s a higher percentages (67%) from 51 to 67 because that’s safer
    - With GovNo we should follow the desired governance structure of AtomOne
- How do you enforce legal jurisdiction?
    - AtomOne has its own court and we can look at the evidence, for a simple court procedure.
- How do avoid a super majority
- Should the community support raising the threshold to change parameters of the chain?
- Instead of ICS chains, having their own tokens they can use base tokens of the main chain.
- Validators voting with their own tokens, not their delegators?
    - For AtomOne is not decided
    - Use GovNo to come to consensus
    - Approval of validators and stakers
        - Two parties?
    - For GovNo, no value to protect so validators don’t have as much weight
- What about newcomers?
    - Some of us want after launching AtomOne that they are out of luck
    - It makes more sense to demonstrate a split in a friendly and constructive way, if we slash them out, we’re incentivizing the narrative that we overtly competing
    - Supporting AtomOne in spite of Gaia is not logical, it should be collaborative
    - Secondary mechanism to acquire AtomOne tokens aside from airdrop, what that looks like is up for discussion on repo
        - If you bring atoms to AtomOne then you can earn AtomOne over time using liquid staking
            - Benefit to AtomOne is that AtomOne gets voting power in Gaia
            - Gaia becomes like LikeCoin to AtomOne’s Bitcoin, more flexible while AtomOne is more immutable
        - Premine? Distributed to Atom holders in a premine
        - Liquid stake?
            - AtomOne liquid staked token is photon
            - Atom liquid tokens become Phantom
            - Phantom convert to Photons?
            - Photon holders will get diluted “when gaia fails”
            - Can they merge? Can they work together?
            - Better idea of what people are comfortable with after GovNo launches
- Should we limit transfers of GovNo tokens?
    - For GovNo, absolutely. Use them, delegate/stake and vote but cannot send
- Is the snapshot for GovNo tokens done by 848 closing vote?
    - Yes for the purpose of GovNo, which is sentiment understanding for the purpose of AtomOne, so limit only to No voters.
    - Question: validator delegation included?
    - Question: Changes occurring to the state impact?
        - No only the snapshot
- Consider using DAODAO?
- Would be good to rely on what we have, going with general idea of not introducing too many things
- GovNo can start creating validator base community for AtomOne
- Makes sense to eat our own dog food that way we have a base for validator community
- Full functionality from app and web browser?
    - Yes
- Potentially try both, DAODAO as a temporary solution to get direction for GovNo
- Purpose of GovNo is to find sentiment?
    - Yes, to get direction
- Will people be excluded for not voting?
    - No voters need to support GovNo decisions and will probably agree that we should include non voters
    - Even yes voters should be included
    - 7th comment in issue 12 on repo
    - Start with same distribution of 848
        - Only slash ICF
        - If you voted no is 3x
        - If you voted yes, 1:1
        - If you abstain or no vote is 1.5x
- When we talked about no voters are no and NWV voters different?
- For GovNo we shouldn’t, it’s a question because we don’t know. Keep it simple for NWV
- Was this a veto worthy proposal?
    - Yes from perspective of security
    - Are we gonna punish most of us?
- How do we consider punishing of non voters
    - Counterproductive to not punish because you should DYOR on validators
    - Member for punishing non voters, “if we include lazy voters they stay lazy” for GovNo
- Do we have a timeline for when we expect AtomOne?
    - January Q1
    - Being scrappy is better
    - Launch with simple fork
    - Before Gno.land
- “You can fork a chain but not a community of developers”, are there plans to build incentives for builders in AtomOne?
    - Different approach than Swiss foundation
    - Do as much on chain, transparent, according to specs and budget plans
    - Funding comes from premine, inflation, transaction fees (main source) should go into the community pool to fund developers.
    - Devs should be funded through contracts that specify how much and for what and in combination of stable coin and $ATONE tokens
    - Specify what happens when price changes
    - Governance of chain should be deciding what system to use
    - Best solution comes from expressive platform
    - Support smart contract DAO systems there should be diversity of them
        - Gno.land
    - Define the scope of how community funds are used in the constitution, don’t focus on investments of other projects
    - KYC for validators?
        - Genesis validators of AtomOne, maybe makes sense to KYC the validators
        - After launch - up to the stakers of the chain to decide
        - Not for GovNo
        - Issue 75: https://github.com/atomone-hub/genesis/issues/75