# MyApiProject

電影院停車管理系統 API

## 專案描述
這是一個使用 ASP.NET Core 開發的停車管理系統 API，專為電影院停車場設計。

## 功能特色
- 車輛進場管理
- 車輛出場管理
- 停車位請求
- 停車資料查詢
- 停車費用管理

## API 端點
- `POST /api/enter-parking/vehicle` - 車輛進場
- `DELETE /api/exit-parking/vehicle` - 車輛出場
- `POST /api/car/request-parking-spot` - 請求停車位
- `GET /api/parking-data/vehicle` - 取得停車資料
- `PUT /api/parking-records/update` - 更新停車記錄
- `PATCH /api/parking-records/update-fee` - 更新停車費用

## 技術架構
- ASP.NET Core
- Entity Framework Core
- SQL Server
- Swagger/OpenAPI

## 如何執行
1. 確保已安裝 .NET 8 SDK
2. 設定資料庫連線字串
3. 執行 `dotnet run`

4. 瀏覽 `http://localhost:5065/swagger` 查看 API 文件


[
](https://mail.google.com/mail/u/0?ui=2&ik=8ba2cec2c3&attid=0.0.1&permmsgid=msg-a:r3216820230306426633&th=19656be6253020c3&view=fimg&fur=ip&permmsgid=msg-a:r3216820230306426633&sz=s0-l75-ft&attbid=ANGjdJ-aVUTAqOJJAKMs6tICFKDzGeON10cE4g0IMq_XkpnexL7xoNw8AvhYBT-5PeRK_finEclJI7YSJj5d7vObQHmj8Q1j-yY8nYP-yZq7L9MMf8T77cv23x_V00A&disp=emb&realattid=ii_m9qm68rl1&zw)<img width="1010" height="616" alt="image" src="https://github.com/user-attachments/assets/91c448b9-1652-4f85-9c2c-00893cdbaf51" />




