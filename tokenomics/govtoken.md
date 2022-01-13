---
description: Clam Token 🦪
---

# 🪙 Governance Token

The Armada DAO will require a governance token to be used for voting on various AAIP’s/Treasury matters and there must be a framework around the primary distribution of tokens and the ability to mint or burn new tokens.&#x20;

Current Ideas are as follows: Max Supply = infinite Initial circulation = 1.0 X 10^6 The initial circulation will be distributed to all eligible participants (AA-delegators/SPOs) as follows: SPOs - 49% Delegates - 49% Founders - 2% Initial Supply breakdown: Delegators: 1,000,000 x 49% = 490,000 SPOs: 1,000,000 x 49% = 490,000 Founders: 1,000,000 x 2% = 20,000 / (7 founders) = 2857.14285714 (per founder)

The “founders team” are members of the alliance who maintain financials, keys/passwords, website/Github, and legally own the armada DAO LLC. In order to replace the founders would require exceptional effort via some sort of repeal process we have not thought of yet, or the other way would be in the case of incapacitation from doing their duties to personal emergencies or death.

Following the airdrop of the initial supply of the governance token, the minting and or burning of new tokens will be handled by the “armada mint” smart contract. The smart contract is going to execute the minting of new governance tokens automatically based on the conditions we have set and the “minting distribution formula” will determine the amount released per year. Due to the inflationary aspect of this setup, we can increase/decrease the max supply by voting to mint/burn tokens or by changing the minting distribution formula. After the mint releases the total amount of new supply, it will then be distributed automatically to all eligible participants. The number of tokens given to each participant will depend on if they are an SPO, founder, or delegator. This is because SPOs are needed to have increased incentives to maintain their pools, pay the membership fees, and other costs associated with operating a stake pool they will get a marginal benefit per release of new tokens (formulas coming soon). But the rate of return will diminish after a certain number of epochs, delegators, pledge amount, and active stake.

Minting distribution formula should essentially release new tokens every epoch to all delegates and operators based on their specific variables that I have described earlier:

It would be something like the Cobb-Douglas utility function that might suffice so it would be:

T = x^a \* y^b

Where x = delegators, y = pledge , a = epoch, b = blocks

If the pledge is equal to zero you will get no tokens.

If you have zero blocks then the equation becomes T = x^a

If you have zero delegates then the equation becomes T = y^b

