VRProject-馬偕合作紙牌遊戲
===
:::warning
訓練活動 - 數字紙牌遊戲(比大小)
:::
:::warning
本專案需要搭配收集數據的儀器才能正常遊玩，可觀看Demo影片-https://drive.google.com/drive/folders/1IhjYmtPd46zSvSJJYBRANhGP3fzomxqL?usp=sharing
腳本部分在路徑-VRProject-CardGame/CardGame/Assets/FrameDemo Fix/Scripts/
:::
# 地點: 幼兒園教室
- 三張桌子，每張桌子配置四張椅子
- 中間桌子有3個NPC在玩紙牌遊戲，左右兩張桌子沒有坐NPC
- 教室的天花板、左右窗戶、牆壁及教室前的白板、電視都可以和虛擬教室場景相同
- 教室前的海報更換成ABC及數字海報
# 活動流程
- 數字紙牌範圍: 1~10
- 遊戲參與者: User與同桌的三個NPC(NPC1、NPC2、NPC3)
## 遊戲規則:
- 每人一疊牌(共5張)。
- 遊戲總共有兩回合，一回合內有五輪。
- 每輪須將手中那疊牌的最上面那張放到桌面上，數完123後大家一起攤牌，
比較誰的紙牌數字最大，其- 中數字牌最大的人可以獲得金幣一枚。
- 待遊戲兩回合結束後，結算擁有最多金幣者可額外獲得5枚金幣。
## 遊戲開始前:
- 主持人: 「這一關要挑戰的遊戲是數字比大小。數字牌最大的人可以獲得金幣一枚。遊戲結束後，最多金幣者額外獲得5枚金幣。」
(------此時同桌的三個NPC正在玩紙牌遊戲------)
- User此時要說:「你們在玩甚麼? 我也想要一起玩!」
- NPC: 「等我們完好這一疊(剩3張牌)。」
(------等待NPC玩三輪------)
- NPC: 「好了!可以一起來玩了。」
(------接著由NPC進行洗牌與發牌動作------)
- NPC要先在他們三位NPC產生的廢牌堆簡單搓一下，將牌整理成一疊，然後發給每人一疊(5張牌)
## 遊戲進行中:
- 左手拿著一疊牌，右手掌心朝下並同時拿取最上面那張牌，接著將右手置於桌面。
- 待所有人的右手都蓋在桌面上後，大家一起數123，右手一起離開。且在右手一離開的瞬間，
牌會自己由背面轉為有數字的那面。
- 接著比較誰的紙牌數字最大，其中數字牌最大的人可以獲得金幣一枚。
- 遊戲中有廢牌區: 每輪結束後，每人都須右手持牌並放進廢牌觸發區(手一碰到即觸發)，
此時牌會自己掉落進廢牌區。
- 在第一回合結束後，須由NPC進行洗牌與發牌
- NPC要先在他們三位NPC產生的廢牌堆簡單搓一下，將牌整理成一疊，然後發給每人一疊(5張牌)，然後繼續第二回合。
## 遊戲結束後:
- 待遊戲兩回合結束後，結算擁有最多金幣者可額外獲得5枚金幣。
## 需要處理的例外狀況:
- 手如果數到3沒有離開 -> NPC聲音回饋: 「你手要打開。」
- 手如果數到3之前先離開 -> 只會有User的牌翻開，NPC聲音回饋:「你手要等到數到3才可以打開。」，此時這一輪作廢並直接進到下一輪。
- user可以轉動自己的手看到自己的紙牌上的數字
# 情境問題
- 情緒辨識: 輸了不認帳、輸了就不玩、輸了大哭
- 情緒察覺：辨認當下是開心、生氣或是懊惱
