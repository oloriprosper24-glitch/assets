0xda83bce8a60eebb20d1310de6267a20c27ef04f6
# Adding Your Token Logo and Details to BlocksScan Explorer

If you would like to add a logo and details for your token to BlocksScan Explorer, please follow the guidelines below.

## Image Requirements

- **File Extension:** Only `.png` is accepted. Uppercase `.PNG` files will be considered invalid.
- **File Name:** The file name should be your token symbol in lowercase. For example, `tokens/img/usdt.png`.
- **Size:** The image should be 256px by 256px.
- **Background:** Preferably transparent.
- **Optimization:** Use a simple drag-and-drop online service like [TinyPNG](https://tinypng.com/) to optimize the image size.

## Token Information Requirements

- **File Extension:** Only `.json` is accepted. Uppercase `.JSON` files will be considered invalid.
- **File Name:** The file name should be your token symbol in lowercase. For example, `tokens/config/usdt.json`.
- **Required Fields:** `symbol`, `name`, `website`

## Example

Below is an example of a JSON file containing the necessary token information:

```json
{
  "id": "0xd12f7a98c0d740e7ec82e8caf94eb79c56d1b623",
  "symbol": "bss",
  "name": "BlocksScan",
  "description": "BlocksScan's XRC20 token",
  "website": "https://blocksscan.io",
  "auditReport": {
    "SlowMist": ""
  },
  "communities": {
    "email": "support@blocksscan.io",
    "telegram": "https://t.me/blocksscan",
    "reddit": "https://www.reddit.com/r/",
    "medium": "https://medium.com/",
    "youtube": "https://blocksscan.io",
    "twitter": "https://twitter.com/blocksscan",
    "facebook": "https://www.facebook.com/",
    "github": "https://github.com/blocksscan",
    "coinmarketcap": "https://coinmarketcap.com/currencies/",
    "coingecko": "https://www.coingecko.com/en/coins/"
  }
}
```

## Adding a New Account Tag

To add a new account tag, follow these steps:

1. **Locate the Configuration File:** The configuration file is located at \`eaas/config/XDC/AccountName.json\`.
2. **Open the File:** Use a text editor to open \`AccountName.json\`.
3. **Add the Account Tag:** Add a new entry to the JSON file with the appropriate details.

### Example

Below is an example of how to add a new account tag to the \`AccountName.json\` file:

```json
{
  "0xYourAccountAddressHere": "YourAccountTagName"
}
```

Make sure to include the following fields for each new account tag:

- **0xYourAccountAddressHere:** The blockchain address of the account.
- **YourAccountTagName:** The name you want to associate with this account.

By following these guidelines, you can ensure that your token's logo, details, and account tags are correctly displayed on BlocksScan Explorer.