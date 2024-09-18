# Multi-Sig Project

## Overview

This project is a multi-signature wallet implementation using TypeScript and the Polkadot JS utility library. It allows multiple addresses to collectively control a single account, requiring a minimum number of approvals (threshold) to execute transactions.

## Prerequisites

- Node.js
- npm

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/crazydevlegend/substrate-multi-sig.git
    cd substrate-multi-sig
    ```

2. Install the dependencies:

    ```sh
    npm install
    ```

## Usage

To run the project, use the following command:

```sh
npm start
```

This will execute the `index.ts` file using `ts-node`.

## Configuration

### `package.json`

The `package.json` file includes the necessary scripts and dependencies for the project.

### `tsconfig.json`

The `tsconfig.json` file contains the TypeScript configuration for the project.

## Example

The `index.ts` file provides an example of how to create a multi-signature address and sort the signatories.

## References

- [What is Multi-sig wallet?](https://wiki.polkadot.network/docs/learn-account-multisig)
- [How to create and use multi-sig wallet?](https://support.polkadot.network/support/solutions/articles/65000181826-how-to-create-and-use-a-multisig-account)
- [Example](https://polkadot.js.org/docs/util-crypto/examples/create-multisig/)

## License

This project is licensed under the ISC License. See the `LICENSE` file for more details.
