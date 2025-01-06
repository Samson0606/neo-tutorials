# How to Create a Smart Contract on Neo X

## Introduction
In this tutorial, you'll learn how to create, deploy, and test a smart contract on Neo X. This guide is beginner-friendly and covers everything from setting up your environment to deploying a simple contract.

---

## Prerequisites
1. Basic understanding of programming (C#, Python, or JavaScript recommended).
2. Installed tools:
   - [Neo Blockchain Toolkit](https://github.com/neo-project/neo-blockchain-toolkit)
   - Visual Studio Code
   - Neo Express
   - Neo CLI
3. A Neo wallet for GAS tokens to deploy your contract.

---

## Step 1: Setting Up Your Environment
1. Install the **Neo Blockchain Toolkit** by following the [official guide](https://github.com/neo-project/neo-blockchain-toolkit).
2. Open Visual Studio Code and install the Neo Debugger extension.
3. Start Neo Express to set up a private blockchain for testing:
   ```bash
   neo-express create my-private-network
   neo-express start