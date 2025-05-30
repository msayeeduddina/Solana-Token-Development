
---

# Solana-Token-Development

This repository provides a guide to creating a Solana token on the Solana Devnet. To get started, follow the detailed steps outlined in the blog post below:

[Creating a Solana Token](https://blog.networkchuck.com/posts/create-a-solana-token/)

### Main Points:

- **What Do You Need?**
  - A computer and a terminal (Mac, Windows, Linux)
  - On Windows, use WSL2

- **Docker**
  - Install Docker on your platform
  - Mac: [Mac Installation Guide](https://docs.docker.com/desktop/setup/install/mac-install/)
  - Linux/Windows (WSL): [Installation Guide](https://docs.docker.com/engine/install/)
  - Ubuntu: [Ubuntu Installation Guide](https://docs.docker.com/engine/install/ubuntu/)

- **Setup Docker’s apt repo**
  - Add Docker's official GPG key
  - Add the repository to Apt sources

- **Install the latest Docker version**
  - Verify the installation with `sudo docker run hello-world`

- **Setup the Solana Docker Container**
  - Create a new folder for your token project
  - Create a Dockerfile

- **Build the Docker Image**
  - Build the Docker image with the Dockerfile

- **Run the Container**
  - Run the Docker container and map your current directory

- **Create a fake Solana Token**
  - Create an account for mint authority
  - Set the account as the default keypair
  - Change to devnet
  - Verify your config

- **Get some SOL from a faucet**
  - Use the Solana Devnet Faucet to get SOL

- **Create a mint address**
  - Mint your token on the Solana devnet

- **Upload Metadata**
  - Upload your token metadata to decentralized storage (e.g., Pinata)

- **Add the metadata to the token**
  - Initialize metadata for your token

- **Let’s make some tokens**
  - Create a token account
  - Mint tokens
  - Check the balance of your wallet
  - Send tokens to a friend

- **Going to Market**
  - Disable minting and freezing
  - Update metadata if needed
  - Burn tokens if necessary

---
