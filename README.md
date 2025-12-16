### 3D Rubik's Cube Simulator

<div align="Left">
A high-fidelity, web-based 3D Rubik's Cube simulator built with Three.js. Features realistic physics-based rendering (PBR), multi-order support (2x2-4x4), and an integrated Kociemba solver.
</div>

[English](#english) | [中文](#中文)

## <a name="english"></a>English

### Features

**Multi-Order Support**: Seamlessly switch between 2x2 (Pocket), 3x3 (Standard), and 4x4 (Revenge) cubes within the same interface.

**Intelligent Auto-Solver**: Integrated `min2phase.js` implementation of the Kociemba Algorithm for near-optimal 3x3 solutions. Includes mapped solving for 2x2 and a "Rewind" logic for 4x4.

**Realistic Graphics**: Uses Three.js `MeshPhysicalMaterial` and `RoundedBoxGeometry` to simulate plastic textures, gaps, and dynamic lighting (PBR).

**WCA Utilities**: Built-in WCA-compliant scramble generator and a high-precision timer with inspection/running states.

**Customizable Control**: Adjustable animation speeds (0.25x - 1.0x), camera orbit controls, and intuitive UI buttons for specific face rotations.

### Preview

Auto-Solve 

<video src="preview/Demo.mp4" controls="controls" width="400"></video>

### How to Use

1.  **Download**: Clone this repository or simply download the `3D魔術方塊(外觀優化).html` file.
2.  **Run**: Open the HTML file in any modern web browser (Chrome, Edge, Firefox, Safari).
    * *Note: An active internet connection is required to load Three.js and the solver library via CDN.*
3.  **Interact**: 
    * Use the **UI Panel** on the right to Scramble, Reset, or Auto-Solve.
    * **Mouse Drag**: Rotate the camera view.
    * **Buttons**: Click R/L/U/D/F/B buttons to rotate specific layers.
4.  **Solve**: Click "Kociemba Algorithm" to watch the AI solve the cube automatically.

### Tech Stack

- **Three.js**: For 3D rendering and scene management.
- **min2phase.js**: Implementation of Kociemba's two-phase algorithm.
- **HTML5/CSS3**: Responsive UI and layout.

### Legal Disclaimer 

- The content provided in this project is strictly for educational and demonstration purposes.
- This project is not affiliated with the World Cube Association (WCA) or the Rubik's Brand Ltd.
- Users are solely responsible for ensuring that their usage complies with relevant software licenses when modifying or redistributing the code.

### License

This project is released under the [MIT License](LICENSE).

## <a name="中文"></a>中文

<div align="Left"> 基於 Three.js 與 Kociemba 演算法打造的全能 3D 魔術方塊模擬器，具備擬真的 PBR 材質與自動還原功能。 </div>

[View this document in English](#english)

### 功能特色

**多階數支援**: 支援 **2x2 (二階)**、**3x3 (三階)** 與 **4x4 (四階)** 魔術方塊的即時切換與獨立邏輯運算。

**強大的自動還原**: 
- **3x3**: 內建 `min2phase.js` (Kociemba 演算法)，可在毫秒級計算出最佳還原路徑。
- **2x2**: 使用映射演算法進行自動還原。
- **4x4**: 支援「原路回溯 (Rewind)」功能，幫助使用者理解還原步驟。

**擬真視覺體驗**: (外觀優化版) 採用 `MeshPhysicalMaterial` 模擬塑膠質感，搭配圓角幾何與動態光照系統，還原真實方塊的手感與縫隙細節。

**競速輔助工具**: 內建符合 WCA 規範的打亂公式生成器，以及毫秒級精確計時器。

**靈活的操控性**: 支援 0.25x 至 1.0x 的動畫速度調整，並提供直觀的 UI 按鈕進行單層轉動與視角控制。

### 預覽

<video src="preview/Demo.mp4" controls="controls" width="400"></video>

### 如何使用

1.  **下載**: 複製本專案代碼，或直接下載 `3D魔術方塊(外觀優化).html` 檔案。
2.  **開啟**: 使用任何現代瀏覽器 (Chrome, Edge, Firefox) 直接開啟該 HTML 檔案。
    * *注意：需保持網路連線以透過 CDN 載入 Three.js 函式庫。*
3.  **操作**:
    * 利用右側控制面板進行「隨機打亂」或「重置」。
    * 滑鼠拖曳可旋轉視角。
    * 點擊 R/L/U/D/F/B 按鈕進行方塊轉動。
4.  **還原**: 點擊「Kociemba 演算法還原」按鈕，即可觀賞 AI 自動解題過程。

### 技術架構

- **Three.js**: 核心 3D 渲染引擎。
- **min2phase.js**: 實現 Kociemba 二階段演算法的高效函式庫。
- **HTML5/CSS3**: 響應式介面設計。

### 法律免責聲明 

- 本專案所提供之內容嚴格限制於展示前端 3D 工程技術與演算法教學。
- 本專案與世界魔術方塊協會 (WCA) 或 Rubik's Brand Ltd 無官方關聯。
- 使用者須自行確認並承擔透過本專案生成或使用之任何內容的後果。

### 授權條款

本專案採用 [MIT License](LICENSE) 授權。
