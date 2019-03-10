# system_customer 用戶回訪系統

![](https://xxuain.github.io/system_customer/img/demo.png)

## demo
[http://34.80.48.226/login](http://34.80.48.226/login)

## 簡介
處理業務帶回的新客名單，數位化管理取代紙本管理作業。
不同部門以及主管級別皆有不同權限管理。
主管可分配名單給部屬撥打，部署也能自行取到權限內的名單，更有效率管理新客回饋資料。

### 相關技術
+ Laravel 5.3
+ Vue.js
+ axios 操作 API
+ Bootstrap元件編譯

## 使用外掛
+ [bootstrap](https://bootstrap.hexschool.com/)
+ [axios](https://www.npmjs.com/package/axios)
+ [v-msg](https://github.com/nasa8x/v-msg)

## 內容介紹
### 帳號管理
- 新增/編輯/停用/搜尋 帳號
- 能選擇不同權限及所屬部門
- 使用部門人員名單由總公司ERP匯入，並且定時更新
![](https://xxuain.github.io/system_customer/img/staff.png)

### 名單管理
- 匯入/匯出/新增/編輯/結案/搜尋 名單
- 名單取用權限 & 各式狀態處理
![](https://xxuain.github.io/system_customer/img/customer_mgmt.png)
![](https://xxuain.github.io/system_customer/img/customer_mgmt_edit.png)

### 名單撥打
- 使用者能取得自己權限內的名單
- 選擇活動取得欲取用筆數
- 編輯客戶名稱、狀態、預約時間...等
![](https://xxuain.github.io/system_customer/img/customer_call.png)

### 撥打成效
- 單次活動的撥打成效
- 寄出成效EXECL至主管信箱
![](https://xxuain.github.io/system_customer/img/revisit_rate.png)

### 黑名單
- 新增/解除/搜尋 黑名單
- 一旦為黑名單就不能匯入
![](https://xxuain.github.io/system_customer/img/customer_block.png)