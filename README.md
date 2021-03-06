# CloudNativeUberUserStory

## 310551010
### Uber Eats
User Story：一個沒有主見的使用者，希望有『給我一點驚喜』的功能，可以根據用餐時間、過去訂餐紀錄、用餐地點等，推薦餐廳給使用者  
Acceptance Criteria :  
    - GIVEN : 在Uber Eats首頁上多一個按鈕『給我一點驚喜』  
    - When：點擊『給我一點驚喜』 後台根據用餐時間、過去訂餐紀錄、用餐地點等計算出符合使用者期待的餐廳  
    - THEN : 直接進入對應餐廳的頁面開始訂餐  
    - GIVEN : 在餐廳頁面的最上方多一個按鈕『還有要其他驚喜』  
    - When : 點擊『還有要其他驚喜』 後台根據用餐時間、過去訂餐紀錄、用餐地點等計算出符合使用者期待的餐廳  
    - Then : 直接進入對應餐廳的頁面開始訂餐(依此類推 直到使用者選定好想吃的餐廳  

## 310554028  
### Uber Eats  
User Story: 一個想減肥的使用者，希望有統計訂餐熱量的功能，並可以根據一天規劃三餐可以吃那些最健康  
Acceptance Criteria :  
    - GIVEN : 頁面上有個地方能設定熱量上限  
    - WHEN  : 點擊該地方並設定熱量上限  
    - THEN  : 系統根據該上限限制點餐的熱量上限  
    - GIVEN : 購物車會統計餐點的熱量  
    - WHEN  : 我加入一個新的餐點  
    - THEN  : 系統根據購物車的餐點再計算一次總熱量  
    - GIVEN : 會根據當日熱量上限限制點餐  
    - WHEN  : 我想加入一個新的餐點  
    - THEN  : 系統計算加入此東西是否會超過熱量上限，並給予反饋(如不讓你訂餐之類的)  

## 310551060
### Uber Eats  
User Story：我是一位肚子餓的使用者，希望外送員能夠優先送我的餐點，這樣我就能早點吃我的晚餐  
Accptance Criteria :  
    - GIVEN : 結帳時能夠選擇優先運送  
    - When：選擇優先運送時，增加訂單金額，訂單附上優先運送條件  
    - THEN : 結帳後外送員取餐完直送

## 310553042
### Uber Eats
User Story：一個有固定飲食習慣的使用者，希望可以快速點餐。
Accptance Criteria :  
    - GIVEN : 製作UberEat widget,方便釘選到手機主畫面  
    - When： 使用者點擊widget上採用歷史訂單  
    - THEN : 訂單完成，等待取餐
    - GIVEN : Widget改成顯示訂單進度   
    - When : 使用者可以快速確認訂單狀態，並決定什麼時候出門拿餐
    - Then : 取得餐點，完成快速的需求