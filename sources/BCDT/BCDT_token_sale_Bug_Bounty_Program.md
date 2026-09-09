# BCDT token sale Bug Bounty Program

> This program ended in 2018 and is kept for historical reference only. Submissions are no longer accepted.

## Rewards

Paid out **Rewards** in ether are guided by the **Severity** category of the submission according to [OWASP](https://github.com/weifund/weifund-contracts/blob/master/BUG-BOUNTY-DETAILS.md)'s risk model, up to a maximum of $5,000 in ETH for program.

## Rules

* Issues that have already been submitted by another user or are already known to BCD are not eligible for bounty rewards
* Public disclosure of a vulnerability without BCD's prior consent results in ineligibility for a bounty

## Targets

### In scope:

**BCDT Smart Contracts**: [contracts/BCDToken](contracts/BCDToken)

**Examples of what's in scope** 

* Being able to obtain more tokens than expected
* Being able to obtain tokens from someone without their permission
* Bugs that lead to loss or theft of ether
* Bugs causing a transaction to be sent that was different from what user confirmed: for example, user transfers 10 ether in the UI, but exactly 10 wasn't transferred.
* Bugs that could lead to the direct loss of funds such as paying out to non-intended payout beneficiaries
* Bugs that lead to tokens being claimed before they should be
* Bugs that lead to the wrong amount of funds being refunded if the crowdsale is not successful
* Different behavior than expected in specifications: [contracts/BCDToken/README.md](contracts/BCDToken/README.md)


### Out of scope:

* Known behaviors indicated in specifications: [contracts/BCDToken/README.md](contracts/BCDToken/README.md)
* Gas consumption improvement
* Code or comment style improvement

**Examples of what's out of scope**

* An address that has already contributed can be removed from the whitelist
