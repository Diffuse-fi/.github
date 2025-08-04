# Diffuse

The Diffuse core team is building a set of tools and building blocks for creating trustless DeFi protocols, both cross-chain and mono-chain.

A while ago, we introduced the concept of zk-Serverless functions, a perfect fit for developing apps and protocols that need both on-chain and off-chain data, whether it's real-time or historical. Right now, the framework is used privately within the Diffuse ecosystem to build our own products, but we’re planning to open it up to the public in the future.

# Diffuse Prime

Diffuse Prime is a non-custodial lending protocol for structured leverage deals with isolated risk. It runs on our custom ZK/TEE infrastructure, bringing our zk-Serverless vision into reality. Here are the main features of Diffuse Prime:

- Liquidity Providers earn safe, competitive yields.
- Hedge Funds access collateralized loan positions.
- Strategy: boost APY on Pendle PT tokens from 12% to 25% using a leverage mechanism.

# Price Feeds

Our custom price feeds let us support any exotic asset without relying on third-party oracles. They're built with the same zk-Serverless approach to cut down unnecessary computations, reduce trust assumptions, and keep everything reliable.

They also make it possible to run more complicated scenarios such as to generate trustless risk parameters based on real historical data.

# Collateral Abstraction

Collateral Abstraction is a sub-protocol that allowes creating synthetic tokens backed by one or more collateral assets. Thanks to the flexibility of our custom price feeds, the choice of assets accepted as collateral is in no way dictated by the tech side.