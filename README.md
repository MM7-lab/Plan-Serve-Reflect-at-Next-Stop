# 下一站，有人需要你

「賽馬會眾心行善 – 義工推廣校園夥伴計劃」（香港明愛）課程 A 課堂用嘅 3D 互動遊戲。學生喺星期日雨夜嘅車廂入面，由頭到尾行一次「構思．服務．領悟（Plan-Serve-Reflect）」六步曲，最後出善幸卡截圖交 LMS。

## 點樣玩

用電腦或者手機瀏覽器打開 `index.html`，撳「上車 ▸」。需要上網載入 Three.js（cdnjs）同字型；光暈效果由 jsdelivr 載入，學校網絡封咗都照玩得，只係冇光暈。

## 放上網（GitHub Pages）

1. Repo 嘅 **Settings → Pages**。
2. **Source** 揀 **Deploy from a branch**，branch 揀 **main**，folder 揀 **/ (root)**，撳 Save。
3. 一兩分鐘後，網址係 `https://mm7-lab.github.io/Plan-Serve-Reflect-at-Next-Stop/`。

呢個 repo 係公開嘅，任何人都睇到遊戲、插畫同程式。

## 檔案

| 路徑 | 用途 |
|---|---|
| `index.html` | 遊戲本體（單一檔案，插畫已經用 WebP 嵌入） |
| `CLAUDE.md` | 設計說明、六步曲內容、技術細節同修改約束 |
| `character-prompts.md` | 每個角色嘅生圖 prompt 同檔名 |
| `tools/` | 將角色插畫剪成透明圖嘅 Python 工具（numpy、pillow、scipy） |

角色插畫原圖放喺 Google Drive「Plan Serve Reflect Characters」folder。
