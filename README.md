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
