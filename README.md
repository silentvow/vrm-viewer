# VRM 檢視器 / VRM Viewer

在瀏覽器裡檢視 VRM 模型、播放 VRMA 動作、擺測試姿勢、調表情、顯示彈簧骨碰撞體。
A browser-only viewer for VRM models: play VRMA motions, test poses, expression sliders, spring-bone colliders.

- 線上使用 / Live: https://silentvow.github.io/vrm-viewer/
- 檔案只在你的瀏覽器內讀取，不會上傳。Files are read locally in your browser and never uploaded.
- 內建 12 個小型 VRMA（MIT）；VRM 請自行選擇檔案或拖進畫面（支援 VRM 1.0 與 0.x）。12 small built-in VRMA motions (MIT); load your own VRM via the file picker or drag & drop.
- 沒有內建任何 VRM 模型。No VRM models are bundled.

頁面需要網路：three.js 與 three-vrm 由 jsDelivr 載入（three 0.184.0、@pixiv/three-vrm 3.5.5）。
The page needs network access: three.js and three-vrm are loaded from jsDelivr.

第三方內容與授權見 [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)。
