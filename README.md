# VRM 檢視器 / VRM Viewer

在瀏覽器裡檢視 VRM 模型、播放 VRMA 動作、擺姿勢、調表情、換背景、配音樂、顯示彈簧骨碰撞體。
A browser-only viewer for VRM models: play VRMA motions, poses, expression sliders, backgrounds, music, spring-bone colliders.

- 線上使用 / Live: https://silentvow.github.io/vrm-viewer/
- 檔案只在你的瀏覽器內讀取，不會上傳。Files are read locally in your browser and never uploaded.
- 內建 11 個小型 VRMA（MIT）與 21 個 Mixamo X Bot 動作（授權見 THIRD_PARTY_NOTICES）；VRM 請自行選擇檔案或拖進畫面（支援 VRM 1.0 與 0.x）。11 small built-in VRMA motions (MIT) and 21 Mixamo X Bot motions (see THIRD_PARTY_NOTICES); load your own VRM via the file picker or drag & drop.
- 沒有內建任何 VRM 模型。No VRM models are bundled.
- 背景：除了純色，還有演唱會舞台、攝影棚、櫻花庭園、賽博雨夜、星空極光（全部由程式產生，沒有外部素材），各有數種配色。Backgrounds: besides solid colours, a concert stage, photo studio, cherry-blossom garden, cyberpunk rainy night and starry aurora (all generated in code, no external assets), each with colour themes.
- 音樂：可選擇自己的音樂檔（.ogg／.mp3／.wav／.m4a）或拖進畫面，與動作同步播放，有音量與靜音。Music: pick or drop your own audio file; it plays in sync with the motion, with volume and mute.
- 打光與渲染：主光／補光／輪廓光、陰影、曝光與色調映射、輪廓線、MToon 偵錯檢視。Lighting & rendering: key/fill/rim lights, shadows, exposure & tone mapping, outlines, MToon debug views.

頁面需要網路：three.js 與 three-vrm 由 jsDelivr 載入（three 0.184.0、@pixiv/three-vrm 3.5.5）。
The page needs network access: three.js and three-vrm are loaded from jsDelivr.

本專案以 MIT 授權釋出（見 [LICENSE](LICENSE)）。第三方內容與授權見 [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)。
