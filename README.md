# Spike Bot  

**Spike Bot** is a Discord bot designed for Brawl Stars players, supporting player information retrieval, battle log tracking, and module management functions.  

Spike Bot 是一款專為 Brawl Stars 玩家設計的 Discord 機器人，支援查詢玩家資料、戰鬥紀錄以及模組管理功能。

---

## Features  

### Public Commands  
1. **`/brawlstars_player <player_tag>`**  
   Retrieve information about a Brawl Stars player, including their trophies, rank, and more.  

2. **`/brawlstars_battlelog <player_tag>`**  
   Retrieve the recent battle logs of a specified Brawl Stars player.  

### Authorized User Commands  
Only authorized users can use the following commands:  
1. **`!load <module name>`**  
   Dynamically load the specified module.  

2. **`!unload <module name>`**  
   Unload the specified module.  

3. **`!reload <module name>`**  
   Reload the specified module.  

---

## Installation Guide  

### 1. System Requirements  
- **Python**: Version 3.8 or above.  
- **discord.py module**: This is the Python module required to interact with Discord's API. Run `pip install discord.py` in the terminal.  
- **Brawl Stars API Token**: You need to register for an API key from the [Brawl Stars Developer Portal](https://developer.brawlstars.com/#/).  

### 2. Brawl Stars API Registration  

To use the Brawl Stars API, follow these steps:  

1. Visit the [Brawl Stars Developer Portal](https://developer.brawlstars.com/#/).  
2. Log in with your Supercell account or create a new one if you don’t have one.  
3. Once logged in, create an application to obtain your API key.  
4. After registration, you'll get an API key that you can use to access the Brawl Stars API.  

Make sure to replace `your_brawl_api_token` with the API key you obtain in your code.  

### 3. File Configuration

```
spike-bot/
├── main.py              # Main program, responsible for starting the bot
├── cogs/                # Folder for functional modules
│   ├── bs_battlelog.py  # Module for querying Brawl Stars battle logs
│   ├── bs_player.py     # Module for querying Brawl Stars player information
```

### 4. Change Variables  
In your code, replace the following variables:  
- `your_user_id` with the Discord user ID of the authorized user.  
- `your_token` with your Discord bot token.  
- `your_brawl_api_token` with your Brawl Stars API token.

### 5. Running the Program  
Run `main.py` to start the bot.  

---

## License  

This project uses the MIT license.  
Please refer to the [LICENSE](LICENSE) file for more details.  

---

## 功能概述  

### 公開指令  
1. **`/brawlstars_player <玩家標籤>`**  
   查詢指定 Brawl Stars 玩家資訊，包括積分、段位等。  

2. **`/brawlstars_battlelog <玩家標籤>`**  
   查詢指定 Brawl Stars 玩家最近的戰鬥紀錄。  

### 授權用戶指令  
僅授權用戶可使用以下命令：  
1. **`!load <模組名>`**  
   動態載入指定模組。  

2. **`!unload <模組名>`**  
   卸載指定模組。  

3. **`!reload <模組名>`**  
   重新載入指定模組。  

---

## 安裝指南  

### 1. 系統需求  
- **Python**：3.8 或以上版本  
- **discord.py 模組**：這是與 Discord API 進行互動所需的 Python 模組。可以在終端機中執行 `pip install discord.py`  
- **Brawl Stars API Token**：需在 [Brawl Stars 開發者](https://developer.brawlstars.com/#/) 中註冊並獲取 API 金鑰。  

### 2. Brawl Stars API 註冊  

要使用 Brawl Stars API，請按照以下步驟操作：  

1. 訪問 [Brawl Stars 開發者平台](https://developer.brawlstars.com/#/)。  
2. 使用 Supercell 帳號登錄，如果還沒有帳號，請創建一個。  
3. 登錄後，創建一個應用並獲取 API 金鑰。  
4. 註冊完成後，您會獲得一個 API 金鑰，並可以用來訪問 Brawl Stars API。  

記得將程式碼中的 `your_brawl_api_token` 替換為您獲得的 API 金鑰。  

### 3. 檔案配置

```
spike-bot/
├── main.py              # 主程式，負責啟動機器人
├── cogs/                # 功能模組資料夾
│   ├── bs_battlelog.py  # 查詢 Brawl Stars 戰鬥紀錄的模組
│   ├── bs_player.py     # 查詢 Brawl Stars 玩家資料的模組
```

### 4. 改變變數  
在你的`main.py`中，將以下變數替換為實際值：  
- `your_user_id` 替換為授權使用者的 Discord 用戶 ID。  
- `your_token` 替換為你的 Discord 機器人 Token。  
- `your_brawl_api_token` 替換為你的 Brawl Stars API 金鑰。  

### 5. 執行程式  
執行 `main.py` 來啟動機器人。  

---

## 許可證  

此專案使用 MIT 許可證。  
請參閱 [LICENSE](LICENSE) 文件了解更多資訊。  
