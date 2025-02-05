---
description: View and understand the lifecycle of a Multisig RootDAO proposal.
---

# RootDAO Proposal Lifecycle

## Overview

A proposal in a Multisig RootDAO follows the lifecycle displayed in the diagram below.

The different phases are explained in a key underneath.

![](../../../../.gitbook/assets/multisig-root-dao-proposal-lifecycle.png)

## Key

#### Active
As soon as the proposal has been created, it becomes active and any signer on the DAO can vote on the proposal. There is no voting period, and the proposal will be able to be voted on as long as the proposal is not passed or executed.

#### Executable
Once the threshold number of signers have signed the proposal, the proposal is passed and becomes executable.

A proposal that is executable can be executed, executing the transactions in the proposal.

#### Executed
After a proposal is executed, it enters the Executed state.

#### Rejected
If another proposal with the same nonce is executed, then a proposal with the same nonce which is not executed will enter a Rejected state. A rejected proposal can no longer be executed.