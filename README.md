# MMN Microloan - 滾動式動畫

## 技術堆疊

- **前端框架**: React 18.2.0 + TypeScript 5.2.2
- **建置工具**: Vite 5.0.8
- **動畫庫**: GSAP 3.12.2、Rive (Canvas 2.17.2, React Canvas 4.21.3, React WebGL2 4.21.3)、Framer Motion 10.16.4
- **輔助庫**: React Intersection Observer 9.5.3
- **開發工具**: ESLint、TypeScript ESLint、gh-pages 6.3.0

## 專案結構

```
mmn_microloan/
├── public/                              # 靜態資源目錄
│   └── assets/                          # 媒體資源 (audio, data, rive)
├── src/
│   ├── index.tsx                        # 入口點
│   ├── components/                      # React組件
│   │   ├── ScrollAnimationApp.tsx       # 主應用程式
│   │   ├── SectionLanding.tsx           # 首圖區(整合)
│   │   ├── SectionStoryMissh.tsx        # H小姐(整合)
│   │   ├── SectionStoryMickey.tsx       # 米奇(整合)
│   │   ├── landing/                     # 首圖區組件
│   │   ├── missh/                       # H小姐故事組件
│   │   ├── mickey/                      # 米奇故事組件
│   │   └── shared/                      # 共享組件
│   └── styles/                          # 樣式檔案
├── index.html                           # HTML模板
├── ProjectStructure.md                  # 詳細專案結構文件
└── ...
```

> 📋 詳細的檔案結構請參考 [ProjectStructure.md](./ProjectStructure.md)

## 安裝與設定

1. **安裝依賴套件**:
   ```bash
   npm install
   ```

2. **啟動開發伺服器**:
   ```bash
   npm run dev
   ```

3. **建置專案**:
   ```bash
   npm run build
   ```

4. **部署到 GitHub Pages**:
   ```bash
   npm run deploy
   ```

5. **iFrame嵌入測試**:
   ```html
   <iframe src="https://e3kong.github.io/mmn_microloan/" width="100%" height="1080" style="border: none;"></iframe>
   ```