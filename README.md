📞 Contact

> [Termux guides if you run on mobile](https://github.com/MeoMunDep/Guides-for-using-my-script-on-termux)

> If you encounter any issues or have questions, feel free to reach out:

- Contact: [Link](t.me/MeoMunDep)
- Group: [Link](t.me/KeoAirDropFreeNe)
- Channel: [Link](t.me/KeoAirDropFreeNee)

> Help me with your referral [Link](https://t.me/realityrush_bot/play?startapp=refererID6713068747)

## 🚀 Getting Started

> Remember to download Nodejs version: **22.11.0** and NPM version: **10.9.0**

To get started with the bot, follow these steps:

0. **Dowload NodeJS to run the bot**

Before running the bot, make sure you have the following installed:

- **Node.js** (Version: `22.11.0`)
- **npm** (Version: `10.9.0`)

Download Node.js and npm here: [Download Link](https://t.me/KeoAirDropFreeNe/257/1462).

-> Double click on `setup.bat` for windows or `setup.sh` for linux/mac if you want to run automatically, remember to fill all the necessary data.

1. **Install Dependencies and Modules:**

   ```
   npm i user-agents cloudscraper axios colors p-limit https-proxy-agent socks-proxy-agent crypto ws qs
   ```

2. **Prepare Configuration Files:**

   > You'll need to set up a few configuration files for the bot to work properly.

## 📁 Configuration Files

### 1. `configs.json` 📜 - Adjust configuration

```json
{
  "limit": 100,
  "countdown": 300,
  "country_time": "en-US",
  "delayEachAccount": [1, 1],
  "autoUpgradeBuildings": false,
  "maximumBuildingPrice": 500000000,
  "howManyEnergyLimitUpgrade": 5,
  "howManyTapMultiplierUpgrade": 5,
  "howManyBoardMultiplierUpgrade": 5,
  "howManyEnergyRegenSpeedUpgrade": 5,
  "howManyUpgradeCityServicesMultiplier": 5,
  "tappingCount": [10000, 50000],
  "doTasks": true,
  "autoArrange": true,
  "watchAds": true,
  "autoMergeBuilding": true,
  "claimTokens": false,
  "stakingPrize": {
    "30 USDT – Instant Crypto Boost": 1,
    "5 TON – Boost your journey": 1,
    "3Lootboxes – Hidden Treasures": 1,
    "3 x NFT Pool – Instant Prizes": 1,
    "3 x Reality Rush Pool – Instant Prizes Await": 1,
    "Premium Lootbox – VIP Treasures": 1,
    "5,000 $RRUSH – Game Power-Up": 1,
    "50,000 $RRUSH – Power Boost": 1
  }
}
```

### 2. `datas.txt` 🗂️ - Get it from here >>> [Link](https://t.me/KeoAirDropFreeNee/1271)

```txt
token
token
token
```

### 3. `wallets.txt` 💼 - Cannot update yet.

- Wallets generator: [Link](https://github.com/MeoMunDep/Automatic-Ultimate-Create-Wallets-for-Airdrop)

```txt - wallet address
abc...xyz
abc...xyz
abc...xyz
```

### 4. `proxies.txt` 🌐 - Proxy is an option. If you have one, fill it in; otherwise, leave it blank.

```txt
http://user:password@host:port
https://user:password@host:port
socks4://user:password@host:port
socks5://user:password@host:port
```

💡 Usage:

> You need to `cd` to the file after extract it
> To run the bot, use the following command: `cd "reality rush-main/reality rush"; node meomundep`

🎇Enjoy!
