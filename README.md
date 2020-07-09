**暗黑破壞神II 機器人設定中文紀錄**
=======

##### 只是單純自己在玩做個紀錄碰壁好多次一直一直慢慢測試出來的
## A. 安裝步驟
#### 1. 安裝暗黑破壞神準備序號
#### 2. 安裝外掛相依套件
#### 3. 下載配置外掛
#### 4. 開心掛機

## B. 組隊設定
#### 1. 組隊隊長(法師)
```js
17: Scripts.UserAddon = true;

26: Config.MFLeader = true;

128: Config.Leader = "";
129: Config.QuitList = ["EXIT"];
130: Config.QuitListMode = 0;
131: Config.QuitListDelay = [1, 5];

316: Config.ItemInfo = true;

430: Config.PublicMode = 1;

442: Config.MinGameTime = 480;
443: Config.MaxGameTime = 1800;

449: Config.LogExperience = true;
```

#### 2. 組隊隊員
```js
17: Scripts.UserAddon = false;

128: Config.Leader = "TWzeren_a";
129: Config.QuitList = ["EXIT"];
130: Config.QuitListMode = 0;
131: Config.QuitListDelay = [1, 5];

136: Scripts.MFHelper = true;

148: Scripts.BaalHelper = true;

155: Scripts.Follower = true;

316: Config.ItemInfo = true;

430: Config.PublicMode = 2;

442: Config.MinGameTime = 480;
443: Config.MaxGameTime = 1800;

449: Config.LogExperience = true;
```

##### 外掛下載
https://github.com/kolton/d2bot-with-kolbot

##### 編輯器下載
https://notepad-plus-plus.org/

##### 外掛相依套件下載
https://www.microsoft.com/zh-TW/download/details.aspx?id=5555

https://dotnet.microsoft.com/download

@ Markdown