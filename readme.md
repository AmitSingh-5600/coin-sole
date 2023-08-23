# coin-sole CLI

Command line interface written in Node.js to check cryptocurrency prices

Register an API key at https://nomics.com

## Usage

```
npm install


cd todirectory in CLI then node bin/coin-sole

## Commands

```
# Help & Commands
coin-sole -h

# Version
coin-sole -V

# API Key Commands
coin-sole key set
coin-sole key show
coin-sole key remove

# Crypto Check Commands
coin-sole check price

# Check Specific Coins (default: BTN,ETH,XRP)
coin-sole check --coin=BTC,ETH

# Choose Currency (Default: USD)
coin-sole check --cur=EUR
```

### Version

1.0.0

### License

ISC
# coin-sole
