\```markdown
# Crypto Bot

This Telegram bot provides real-time data for cryptocurrencies using the CoinGecko API.

## Requirements

- Python 3.6 or higher
- Python libraries: `telegram`, `requests`, `json`

## Setup

1. Install the required Python libraries:
   \```bash
   pip install python-telegram-bot requests
   \```

2. Obtain your CoinGecko API key from [CoinGecko](https://www.coingecko.com/en/api).

3. Clone or download the repository.

4. Replace `'YOUR_API_KEY'` in the code with your CoinGecko API key.

5. Run the bot using the command:
   \```bash
   python crypto_bot.py
   \```

## Available Commands

- `/start`: Start the bot and get a welcome message.
- `/data <crypto-name>`: Get real-time data for a specific cryptocurrency.
- `/high_low <crypto-name>`: Get the highest and lowest prices of a cryptocurrency in the last 24 hours.
- `/supply <crypto-name>`: Get the circulating supply and total supply of a cryptocurrency.
- `/ranks`: Get information about the top 10 cryptocurrencies.
- `/search_pools <query> <network> <include> <page>`: Search on-chain DEX pool data.

## Example

- To get data for Bitcoin:
  ```
  /data bitcoin
  ```

- To get the highest and lowest prices of Ethereum:
  ```
  /high_low ethereum
  ```

## Contributors

- [AMON] (https://github.com/chumbacash)

## License

This project is licensed under the [MIT License](LICENSE).
\```
\```
