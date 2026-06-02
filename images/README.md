# 放洋留遊學｜照片規格說明

## 每個校區需要的照片

| 檔名 | 用途 | 建議尺寸 | 說明 |
|------|------|---------|------|
| hero.jpg | 城市氛圍卡背景 | 1600×900px | 地標或城市全景，光線充足 |
| area-01.jpg | 校區周邊地圖（上） | 800×600px | 校門口或附近街景 |
| area-02.jpg | 校區周邊地圖（中） | 800×600px | 周邊商圈或交通樞紐 |
| area-03.jpg | 校區周邊地圖（下） | 800×600px | 代表性地標或休閒區 |
| life-01.jpg | 照片牆（一天生活） | 800×800px | 早餐或咖啡廳場景 |
| life-02.jpg | 照片牆（學習環境） | 800×800px | 課堂或校園環境 |
| life-03.jpg | 照片牆（城市探索） | 800×800px | 週末活動或城市景點 |

## 照片風格建議
- 光線自然，避免過度修圖
- 有人的生活感照片比純風景更有感染力
- 色調暖色系，與品牌米白色系相符
- 解析度至少 72dpi，檔案大小建議壓縮至 500KB 以下

## 換圖方式
照片備齊後，把圖片放入對應資料夾，
然後在 HTML 裡全文搜尋 `data-planned="true"`，
把對應 `.photo-slot` 的 inline style 改為：

```html
<img src="./images/canary/hero.jpg" alt="..." loading="lazy">
```

## 校區資料夾清單
- canary／greenford／birmingham／leeds（英國）
- dublin（愛爾蘭）
- berlin（德國）／paris（法國）
- malta（馬爾他）
- dubai（阿聯酋）
- toronto（加拿大）
- brisbane（澳洲）
