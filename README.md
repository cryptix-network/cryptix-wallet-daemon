# Cryptix Wallet Daemon

The daemon also works with the new Rusty Cryptix Node:
https://github.com/cryptix-network/rusty-cryptix

The Wallet Daemon can also be independently extracted from the cryptixd source code:
https://github.com/cryptix-network/cryptixd


## Usage and Commands

Create a new Wallet:
cryptixwallet create

Create new Address:
cryptixwallet new-address

Start the Daemon:
cryptixwallet start daemon


### More:

Usage:
cryptixwallet [OPTIONS] <command>


Application Options:

  /V, /version                    Display version information and exit
  
      /testnet                    Use the test network
	  
      /simnet                     Use the simulation test network
	  
      /devnet                     Use the development test network
	  
      /override-dag-params-file:  Overrides DAG params (allowed only on devnet)
	  
	  

Help Options:

  /?                              Show this help message
  
  /h, /help                       Show this help message
  
  

Available commands:

  balance                      Shows the balance of a public address
  
  broadcast                    Broadcast the given transaction
  
  create                       Creates a new wallet
  
  create-unsigned-transaction  Create an unsigned Cryptix transaction
  
  dump-unencrypted-data        Prints the unencrypted wallet data
  
  get-daemon-version           Get the wallet daemon version
  
  new-address                  Generates new public address of the current wallet and shows it
  
  parse                        Parse the given transaction and print its contents
  
  send                         Sends a Cryptix transaction to a public address
  
  show-addresses               Shows all generated public addresses of the current wallet
  
  sign                         Sign the given partially signed transaction
  
  start-daemon                 Start the wallet daemon
  
  sweep                        Sends all funds associated with the given schnorr private key to a new address of the current wallet
  
  version                      Get the wallet version