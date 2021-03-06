## Ponzi Scheme

### Context

A [Ponzi Scheme](https://en.wikipedia.org/wiki/Ponzi_scheme) is a good example to be implemented in Ethereum.

The contract should be really easy. Let's put some conditions:

- The game should be started with 1 ETH
- The next payor will pay 2 ETH
- The first payor will receive 2 ETH
- After a third payor will pay 4 ETH
- The second payor will receive 4 ETH
- A fourth payor will pay 8 ETH
- The third payor will receive 8 ETH
- ... x2 each time
- A contract can only be payable at the exact amount

Notes:

- The first deposit will be locked forever in the contract

### Setup

Meet the dependencies:

```
npm install
```

also the testrpc.

Run the testrpc (install it if you do not have it):

```
testrpc
```

### Tests

Run:

```npm test```

### Usage

You can deploy it through the tests.