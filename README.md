# StarkNet Go Client

This Go program interacts with a StarkNet testnet through RPC calls to deploy and invoke transactions.

## Prerequisites

- Go installed on your machine
- Access to a StarkNet testnet
- `rpc.json` file containing RPC endpoint information

## Installation

1. Install Go version 1.22.0 by executing the following commands:

    ```bash
    wget https://golang.org/dl/go1.22.0.linux-amd64.tar.gz
    tar -C /usr/local -xzf go1.22.0.linux-amd64.tar.gz
    export PATH=$PATH:/usr/local/go/bin
    ```

2. Verify the installation by checking the Go version:

    ```bash
    go version
    ```

3. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/shidiqmuh0/avail-madara.git
    cd avail-madara
    ```

4. Update the `rpc.json` file with the RPC endpoint information.

    ```bash
    nano rpc.json
    ```

5. Ensure dependencies are up to date:

    ```bash
    go mod tidy
    ```

## Usage

1. Start a new screen session:

    ```bash
    screen -S tx
    ```

2. Run the following command to execute the program:

    ```bash
    go run main.go
    ```

3. Detach from the screen session by pressing `Ctrl + A` followed by `D`. This will leave the program running in the background.
