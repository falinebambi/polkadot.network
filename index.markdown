---
title:
header_title:
subtitle: |-
color: dots
background: header
extended_header: true
features:

- title:
  handle: cta
  background: dark-gray
  width: wide

- title: The Auction
  handle: auction
  background: dots-2
  width: wide
  subsections:
  - body: |-
      In the sale, a fixed amount of tokens is sold. 5 million out of the total 10 million DOTs allocated at Genesis time will be sold. The tokens will be split between each participant in the sale, relative to how much they spend. For example, if the sale ends with just three participants, Alice (who spent 20 ETH), Bob (30 ETH) and Charlie (50 ETH), then they would receive, respectively, 1 million DOTs, 1.5 million DOTs and 2.5 million DOTs).
      <br><br>
      The sale is capped, meaning that it will close once a certain amount of ETH has been raised. However, unlike normal capped sales, the cap changes over time; it begins very high and then decreases, fast at first and then more slowly. To avoid an "immediate ending", the initial cap is so high as to make it impossible for anyone to force the sale's end by spending (around $16b at current prices). Within a week of so, the cap is less than $50m.
      <br><br>
      The sale will include an initial "happy hour", whereby all amounts of ETH spent by participants will be raised by 15%. For example, Alice spends 100 ETH within the first hour, whereas Bob spends 115 ETH after the first hour. Both Alice and Bob will receive the same amount of DOT tokens.
    image: "/assets/auction.svg"
    image-text: (y axis) the initial offer price vs the current bid price
      (x axis) the current number of dots sold vs the total number of dots being offered for sale.
      <br><br>
      Please note the auction will end at the point that the current price matches the total number of tokens being offered in this sale (5 million).
      <br><br>
      <small>* target raise is calculated as 5M tokens for sale * current end price.<br>
      ** "raised so far" includes the bonuses</small>

- title: <div class="technicals-header">Technicals</div>
  handle: technicals
  background: dots
  width: wide
  subsections:
  - body: |-      
      More formally, the sale is a "spend-all second-price Dutch auction". In the auction, 5 million out of the total 10 million DOT tokens allocated at Genesis time will be sold. As an auction, by the time is finishes, it finds a "price" in order that all 5 million DOTs are happily sold. The second-price Dutch auction part basically means that the provisional price at which tokens are offered starts high and lowers throughout the auction period in a predefined schedule. The auction closes once the orders received at the current provisional price are enough to purchase the entire 5 million DOTs.      <br><br>      Unlike normal second-price Dutch auctions, you don't bid on a number of DOT tokens given a current provisional price (which will never increase, only decrease), but rather you bid on an amount to spend, and thus will receive more DOT tokens as the auction continues and the price lowers. Everyone who participates receives the same buy-in price, which is the price that the auction ends on.      <br><br>      Pursuant to certain identity requirements forced on us by international regulations, we are happy to allow citizens and organisations of almost all jurisdictions globally the opportunity to participate in this event (we are sad to note that due to legal restrictions, we are unable to accept the contributions of citizens of Japan). We will endeavour to make the certification as cheap, swift and convenient as possible.
    image: "/assets/dots.svg"

- title: What is it?
  subtitle: Polkadot is a blockchain technology. <br>a heterogeneous multi-chain.
  body: It consists of many parachains with potentially differing characteristics, such as ability to provide anonymity or formal verification. Transactions can be spread out across the chains, allowing many more to be processed in the same period of time. Polkadot ensures that each of these blockchains remains secure and that any dealings between the are faithfully executed. Specialised parachains called bridges can be created to link independent chains.
  handle: manage
  width: wide
  background: light-gray
  subsections:
  - title: <img src="assets/one.svg">Relay chain
    handle: collaborate
    body: Coordinates consensus and transaction delivery between chains
    image: "/assets/protocol-1.svg"
  - title:  <img src="assets/two.svg">Parachains
    handle: preview
    body: Constituent blockchains which gather and process transactions
    image: "/assets/protocol-2.svg"
  - title: <img src="assets/three.svg">Bridges
    handle: edit
    body: Link to blockchains with their own consensus such as Ethereum
    image: "/assets/protocol-3.svg"

- title: Polkadot Vision
  handle: vision
  background: dots
  width: wide
  subsections:
  - body: |-
      A truly decentralised internet where independent blockchains are exchanging information and enable trust-free transactions via smart contracts, with the key enabling tenets of scalability, governance and inter-operability.

      Polkadot is a minimal global consensus layer which provides pooled security that is equal to all members, regardless of the protocol they operate on. It also enables trust-free transactions between all its member chains through decentralised consensus. Consensus in Polkadot is reached via a Proof of Stake mechanism that utilizes network tokens called DOTs.

- title:
  handle: free
  background: dots
  width: wide
  subsections:
  - image: "/assets/minimal.svg"
    title: Minimal
    body: Polkadot should have as little functionality as possible
  - image: "/assets/simple.svg"
    title: Simple
    body: No additional complexity should be present in the base protocol.
  - image: "/assets/general.svg"
    title: General
    body: Polkadot can be optimised through making the model into which extensions fit as abstract as possible.
  - image: "/assets/robust.svg"
    title: Robust
    body: Polkadot should provide a fundamentally stable base-layer.

- title:
  handle: how
  background: light-gray
  width: wide
  body: |-
  subsections:

- title: <center>The Token</center>
  subtitle: <h6>The DOT token serves 3 distinct purposes; governance over the network, operation and bonding.</h6>
  handle: token
  background: dark-gray
  width: wide
  subsections:
  - image: "/assets/Governance.svg"
    title: Governance
    body: Polkadot token holders have complete control over the protocol. All privileges, which on other platforms are exclusive to miners, will be given to the relay chain participants (DOT holders), including managing exceptional events such as protocol upgrades and fixes.
  - image: "/assets/Operation.svg"
    title: Operation
    body: Game theory incentivizes token holders to behave in honest ways. Good actors are rewarded by this mechanism whilst bad actors will lose their stake in the network. This ensures the network stays secure.
  - image: "/assets/Bonding.svg"
    title: Bonding
    body: New parachains are added by bonding tokens. Outdated or non-useful parachains are removed by removing bonded tokens. (proof of stake)

- title: Where are we?
  handle: where
  background: white
  width: wide
  subsections:
  - body: |-
          In the sale, a fixed amount of tokens is sold. 5 million out of the total 10 million DOTs allocated at Genesis time will be sold. The tokens will be split between each participant in the sale, relative to how much they spend. For example, if the sale ends with just three participants, Alice (who spent 20 ETH), Bob (30 ETH) and Charlie (50 ETH), then they would receive, respectively, 1 million DOTs, 1.5 million DOTs and 2.5 million DOTs).
    image: "/assets/magnify.svg"

- title: Friends of Polkadot
  handle: friends
  background: dark-gray
  width: wide
  subsections:
  - body: |-
    image: "/assets/friends.svg"  

layout: index
---
