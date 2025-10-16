<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jaring-Jaring Volume Eksponen - Alat Peraga Edukatif</title>
    <style>
        body {
            box-sizing: border-box;
            font-family: 'Comic Sans MS', cursive, sans-serif;
            margin: 0;
            padding: 20px;
            background: linear-gradient(135deg, #e3f2fd 0%, #f3e5f5 50%, #fff3e0 100%);
            min-height: 100vh;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            background: white;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            overflow: hidden;
        }

        .header {
            background: linear-gradient(45deg, #42a5f5, #66bb6a);
            color: white;
            text-align: center;
            padding: 40px 30px;
        }

        .header h1 {
            font-size: 2.8rem;
            margin: 0;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
            letter-spacing: 2px;
        }

        .header p {
            font-size: 1.3rem;
            margin: 15px 0 0 0;
            opacity: 0.95;
        }

        .main-content {
            padding: 40px;
        }

        .menu-section {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin-bottom: 30px;
        }

        .menu-button {
            background: linear-gradient(135deg, #42a5f5, #1976d2);
            color: white;
            border: none;
            border-radius: 15px;
            padding: 20px;
            cursor: pointer;
            font-size: 1.1rem;
            font-weight: bold;
            transition: all 0.3s ease;
            box-shadow: 0 4px 12px rgba(66, 165, 245, 0.3);
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }

        .menu-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(66, 165, 245, 0.4);
        }

        .menu-button.learning { background: linear-gradient(135deg, #ff7043, #d84315); }
        .menu-button.concept { background: linear-gradient(135deg, #66bb6a, #388e3c); }
        .menu-button.spec { background: linear-gradient(135deg, #ab47bc, #7b1fa2); }
        .menu-button.interactive { background: linear-gradient(135deg, #ffa726, #f57c00); }

        .content-panel {
            background: #f8f9fa;
            border-radius: 15px;
            padding: 30px;
            margin: 20px 0;
            border-left: 5px solid #42a5f5;
            display: none;
            animation: slideIn 0.5s ease-out;
        }

        .content-panel.active {
            display: block;
        }

        @keyframes slideIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .content-panel h3 {
            color: #1976d2;
            margin-top: 0;
            display: flex;
            align-items: center;
            gap: 10px;
            font-size: 1.5rem;
        }

        .concept-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin: 25px 0;
        }

        .concept-card {
            background: white;
            border-radius: 12px;
            padding: 20px;
            text-align: center;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }

        .concept-card:hover {
            transform: translateY(-5px);
        }

        .concept-card.dim1 { border-top: 4px solid #ff7043; }
        .concept-card.dim2 { border-top: 4px solid #42a5f5; }
        .concept-card.dim3 { border-top: 4px solid #66bb6a; }

        .concept-card h4 {
            font-size: 1.8rem;
            margin: 0 0 10px 0;
            color: #333;
        }

        /* Interactive Controls Section */
        .interactive-main {
            background: white;
            border-radius: 15px;
            padding: 25px;
            margin: 20px 0;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }

        .base-selector {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 20px;
            margin-bottom: 25px;
            flex-wrap: wrap;
        }

        .base-input {
            width: 80px;
            height: 50px;
            border: 3px solid #42a5f5;
            border-radius: 10px;
            text-align: center;
            font-size: 1.5rem;
            font-weight: bold;
            color: #1976d2;
        }

        .result-display {
            font-size: 1.3rem;
            font-weight: bold;
            color: #1976d2;
            background: #e3f2fd;
            padding: 10px 20px;
            border-radius: 25px;
        }

        .dimension-buttons {
            display: flex;
            gap: 15px;
            margin: 25px 0;
            justify-content: center;
            flex-wrap: wrap;
        }

        .dim-btn {
            padding: 15px 25px;
            border: none;
            border-radius: 30px;
            cursor: pointer;
            font-weight: bold;
            font-size: 1.1rem;
            transition: all 0.3s ease;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        }

        .dim-btn.active { 
            transform: scale(1.1); 
            box-shadow: 0 6px 15px rgba(0,0,0,0.3);
        }
        .dim-btn.dim1 { background: #ff7043; color: white; }
        .dim-btn.dim2 { background: #42a5f5; color: white; }
        .dim-btn.dim3 { background: #66bb6a; color: white; }

        .visualization-area {
            width: 100%;
            height: 450px;
            background: linear-gradient(135deg, #f5f5f5, #e8e8e8);
            border-radius: 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
            overflow: hidden;
            margin: 25px 0;
            box-shadow: inset 0 4px 8px rgba(0,0,0,0.1);
        }

        .cube-3d {
            width: 250px;
            height: 250px;
            position: relative;
            transform-style: preserve-3d;
            animation: rotate3d 10s infinite linear;
        }

        .cube-3d.paused {
            animation-play-state: paused;
        }

        .cube-face {
            position: absolute;
            width: 250px;
            height: 250px;
            border: 4px solid #333;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.8rem;
            font-weight: bold;
            color: white;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
            border-radius: 10px;
        }

        .cube-face.front { background: linear-gradient(135deg, #42a5f5, #1976d2); transform: rotateY(0deg) translateZ(125px); }
        .cube-face.back { background: linear-gradient(135deg, #66bb6a, #388e3c); transform: rotateY(180deg) translateZ(125px); }
        .cube-face.right { background: linear-gradient(135deg, #ff7043, #d84315); transform: rotateY(90deg) translateZ(125px); }
        .cube-face.left { background: linear-gradient(135deg, #ab47bc, #7b1fa2); transform: rotateY(-90deg) translateZ(125px); }
        .cube-face.top { background: linear-gradient(135deg, #ffa726, #f57c00); transform: rotateX(90deg) translateZ(125px); }
        .cube-face.bottom { background: linear-gradient(135deg, #26a69a, #00695c); transform: rotateX(-90deg) translateZ(125px); }

        @keyframes rotate3d {
            0% { transform: rotateX(0deg) rotateY(0deg); }
            100% { transform: rotateX(360deg) rotateY(360deg); }
        }

        .line-1d {
            width: 400px;
            height: 30px;
            background: linear-gradient(90deg, #ff7043 0%, #ffab91 100%);
            border-radius: 15px;
            position: relative;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        }

        .line-segment {
            position: absolute;
            top: 0;
            height: 100%;
            border-right: 3px solid white;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-weight: bold;
            font-size: 1.2rem;
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0%, 100% { opacity: 1; transform: scale(1); }
            50% { opacity: 0.8; transform: scale(1.05); }
        }

        .grid-2d {
            display: grid;
            gap: 3px;
            background: #42a5f5;
            padding: 15px;
            border-radius: 15px;
            box-shadow: 0 4px 12px rgba(66, 165, 245, 0.3);
        }

        .grid-cell {
            width: 40px;
            height: 40px;
            background: white;
            border-radius: 6px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1rem;
            font-weight: bold;
            color: #42a5f5;
            animation: fadeIn 0.6s ease forwards;
            opacity: 0;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        @keyframes fadeIn {
            to { 
                opacity: 1; 
                transform: scale(1);
            }
            from {
                transform: scale(0.8);
            }
        }

        .control-buttons {
            display: flex;
            gap: 15px;
            margin: 25px 0;
            justify-content: center;
            flex-wrap: wrap;
        }

        .control-btn {
            padding: 12px 24px;
            border: none;
            border-radius: 25px;
            background: linear-gradient(135deg, #42a5f5, #1976d2);
            color: white;
            cursor: pointer;
            font-weight: bold;
            font-size: 1.1rem;
            transition: all 0.3s ease;
            box-shadow: 0 4px 8px rgba(66, 165, 245, 0.3);
        }

        .control-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 15px rgba(66, 165, 245, 0.4);
        }

        .calculator {
            background: white;
            border-radius: 15px;
            padding: 25px;
            margin: 25px 0;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            text-align: center;
        }

        .calc-display {
            background: linear-gradient(135deg, #f5f5f5, #e8e8e8);
            padding: 20px;
            border-radius: 12px;
            text-align: center;
            font-size: 1.8rem;
            font-weight: bold;
            margin-bottom: 20px;
            color: #1976d2;
            box-shadow: inset 0 2px 4px rgba(0,0,0,0.1);
        }

        .educational-text {
            background: #fff3e0;
            border-radius: 15px;
            padding: 25px;
            margin: 25px 0;
            border-left: 5px solid #ffa726;
        }

        .real-world-examples {
            background: #e8f5e8;
            border-radius: 15px;
            padding: 25px;
            margin: 25px 0;
        }

        .example-item {
            display: flex;
            align-items: center;
            gap: 15px;
            margin-bottom: 15px;
            padding: 15px;
            background: white;
            border-radius: 10px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }

        .example-item:hover {
            transform: translateX(5px);
        }

        .assembly-guide {
            background: #e3f2fd;
            border-radius: 15px;
            padding: 25px;
            margin: 25px 0;
        }

        .guide-step {
            display: flex;
            align-items: center;
            gap: 20px;
            margin-bottom: 20px;
            padding: 15px;
            background: white;
            border-radius: 10px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
        }

        .step-number {
            width: 40px;
            height: 40px;
            background: linear-gradient(135deg, #66bb6a, #388e3c);
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            font-size: 1.2rem;
        }

        .explorer-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
            gap: 15px;
            margin: 25px 0;
        }

        .explorer-cube {
            background: white;
            border-radius: 12px;
            padding: 20px;
            text-align: center;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            border: 3px solid transparent;
        }

        .explorer-cube:hover {
            transform: translateY(-5px);
            border-color: #42a5f5;
            box-shadow: 0 8px 20px rgba(66, 165, 245, 0.3);
        }

        .explorer-cube.active {
            border-color: #42a5f5;
            background: #e3f2fd;
        }

        .cube-detail {
            background: #f8f9fa;
            border-radius: 10px;
            padding: 20px;
            margin: 15px 0;
            display: none;
            animation: slideIn 0.3s ease-out;
        }

        .cube-detail.active {
            display: block;
        }

        .cube-net-container {
            background: white;
            border-radius: 15px;
            padding: 25px;
            margin: 25px 0;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }

        .print-instructions {
            background: #e3f2fd;
            border-radius: 10px;
            padding: 15px;
            margin-bottom: 20px;
            border-left: 4px solid #42a5f5;
        }

        .cube-net-printable {
            background: white;
            border: 2px solid #ddd;
            border-radius: 10px;
            padding: 20px;
            margin: 20px 0;
            text-align: center;
        }

        .cube-net-svg {
            width: 100%;
            max-width: 600px;
            height: auto;
            border-radius: 8px;
        }

        .net-face {
            transition: all 0.3s ease;
        }

        .net-face:hover {
            opacity: 0.8;
        }

        .glue-tabs polygon {
            transition: fill 0.3s ease;
        }

        .glue-tabs polygon:hover {
            fill: #e0e0e0;
        }

        .print-controls {
            display: flex;
            gap: 15px;
            justify-content: center;
            flex-wrap: wrap;
            margin-top: 20px;
        }

        .legend text, .instructions text {
            font-family: 'Comic Sans MS', cursive, sans-serif;
        }

        @media print {
            .cube-net-container {
                page-break-inside: avoid;
            }
            
            .print-controls, .control-buttons {
                display: none;
            }
            
            .cube-net-svg {
                width: 100%;
                height: auto;
            }
        }

        .viz-content {
            display: none;
            width: 100%;
            height: 100%;
            align-items: center;
            justify-content: center;
        }

        .viz-content.active {
            display: flex;
        }

        @media (max-width: 768px) {
            .header h1 {
                font-size: 2.2rem;
            }
            
            .menu-section {
                grid-template-columns: 1fr;
            }
            
            .concept-grid {
                grid-template-columns: 1fr;
            }
            
            .dimension-buttons, .control-buttons {
                flex-direction: column;
                align-items: center;
            }
            
            .base-selector {
                flex-direction: column;
                gap: 15px;
            }
            
            .visualization-area {
                height: 350px;
            }
            
            .cube-3d {
                width: 200px;
                height: 200px;
            }
            
            .cube-face {
                width: 200px;
                height: 200px;
                font-size: 1.4rem;
            }
            
            .line-1d {
                width: 300px;
            }
            
            .print-controls {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header class="header">
            <h1>🎲 JARING-JARING VOLUME EKSPONEN</h1>
            <p>Alat Peraga Edukatif Interaktif untuk Memahami Konsep Eksponen melalui Bangun Ruang 3D</p>
        </header>

        <div class="main-content">
            <!-- Menu Buttons -->
            <div class="menu-section">
                <button class="menu-button learning" onclick="togglePanel('learning')">
                    🎯 Tujuan Pembelajaran
                </button>
                <button class="menu-button concept" onclick="togglePanel('concept')">
                    📐 Konsep Matematika
                </button>
                <button class="menu-button spec" onclick="togglePanel('spec')">
                    🔧 Spesifikasi Alat
                </button>
                <button class="menu-button interactive" onclick="togglePanel('interactive')">
                    🎮 Fitur Interaktif
                </button>
            </div>

            <!-- Content Panels -->
            <div id="learning" class="content-panel">
                <h3>🎯 Tujuan Pembelajaran</h3>
                <p>Memahami hubungan antara bilangan berpangkat dan dimensi bangun ruang:</p>
                <div class="concept-grid">
                    <div class="concept-card dim1">
                        <h4>a¹</h4>
                        <p><strong>Panjang</strong><br>(Dimensi 1)</p>
                        <p>Garis lurus dengan panjang a satuan</p>
                    </div>
                    <div class="concept-card dim2">
                        <h4>a²</h4>
                        <p><strong>Luas Persegi</strong><br>(Dimensi 2)</p>
                        <p>Persegi dengan sisi a × a satuan</p>
                    </div>
                    <div class="concept-card dim3">
                        <h4>a³</h4>
                        <p><strong>Volume Kubus</strong><br>(Dimensi 3)</p>
                        <p>Kubus dengan sisi a × a × a satuan</p>
                    </div>
                </div>
            </div>

            <div id="concept" class="content-panel">
                <h3>📐 Konsep Matematika</h3>
                <div id="conceptExplanation">
                    <div class="concept-card dim1">
                        <h4>2¹ = 2</h4>
                        <p>Panjang garis 2 satuan</p>
                    </div>
                    <div class="concept-card dim2">
                        <h4>2² = 4</h4>
                        <p>Luas persegi 2×2 = 4 satuan²</p>
                    </div>
                    <div class="concept-card dim3">
                        <h4>2³ = 8</h4>
                        <p>Volume kubus 2×2×2 = 8 satuan³</p>
                    </div>
                </div>
                
                <div class="real-world-examples">
                    <h3>🌍 Penerapan dalam Kehidupan</h3>
                    <div class="example-item">
                        <span style="font-size: 1.5rem;">📄</span>
                        <span>Lipatan kertas: 2ⁿ lembar setelah n kali lipat</span>
                    </div>
                    <div class="example-item">
                        <span style="font-size: 1.5rem;">🦠</span>
                        <span>Pertumbuhan bakteri: populasi × 2ⁿ</span>
                    </div>
                    <div class="example-item">
                        <span style="font-size: 1.5rem;">🏗️</span>
                        <span>Desain bangunan: perhitungan volume ruang</span>
                    </div>
                    <div class="example-item">
                        <span style="font-size: 1.5rem;">💾</span>
                        <span>Kapasitas memori: 2ⁿ byte</span>
                    </div>
                </div>
            </div>

            <div id="spec" class="content-panel">
                <h3>🔧 Spesifikasi Alat Peraga</h3>
                <div class="concept-grid">
                    <div class="concept-card">
                        <h4>📋 Bahan</h4>
                        <p>Kertas karton A4<br>Siap dipotong dan dilipat</p>
                    </div>
                    <div class="concept-card">
                        <h4>🎨 Komponen</h4>
                        <p>3 kubus berwarna<br>Label 2¹, 2², 2³</p>
                    </div>
                    <div class="concept-card">
                        <h4>✂️ Petunjuk</h4>
                        <p>Garis tebal: Potong<br>Garis putus-putus: Lipat</p>
                    </div>
                </div>
                
                <div class="assembly-guide">
                    <h3>🔨 Panduan Perakitan</h3>
                    <div class="guide-step">
                        <div class="step-number">1</div>
                        <span>Potong sepanjang garis tebal menggunakan gunting</span>
                    </div>
                    <div class="guide-step">
                        <div class="step-number">2</div>
                        <span>Lipat sepanjang garis putus-putus dengan hati-hati</span>
                    </div>
                    <div class="guide-step">
                        <div class="step-number">3</div>
                        <span>Gunakan lem pada tab bertanda "LEM" untuk merekatkan</span>
                    </div>
                    <div class="guide-step">
                        <div class="step-number">4</div>
                        <span>Bentuk kubus dengan menekan semua sisi hingga rapi</span>
                    </div>
                </div>
            </div>

            <div id="interactive" class="content-panel">
                <h3>🎮 Fitur Interaktif</h3>
                
                <!-- Main Interactive Controls -->
                <div class="interactive-main">
                    <div class="base-selector">
                        <label for="baseInput"><strong>📊 Editor Basis (a):</strong></label>
                        <input type="number" id="baseInput" class="base-input" value="2" min="1" max="9">
                        <div class="result-display" id="resultDisplay">a³ = 8</div>
                    </div>
                    
                    <!-- Dimension Selection Buttons -->
                    <div class="dimension-buttons">
                        <button class="dim-btn dim1" onclick="showVisualization(1)">📏 1D - Panjang</button>
                        <button class="dim-btn dim2" onclick="showVisualization(2)">📊 2D - Luas</button>
                        <button class="dim-btn dim3 active" onclick="showVisualization(3)">🎲 3D - Volume</button>
                    </div>
                    
                    <!-- Visualization Area -->
                    <div class="visualization-area" id="mainVisualizationArea">
                        <!-- 3D Cube (default) -->
                        <div id="viz3DContent" class="viz-content active">
                            <div class="cube-3d" id="cube3d">
                                <div class="cube-face front">2³</div>
                                <div class="cube-face back">8</div>
                                <div class="cube-face right">2×2×2</div>
                                <div class="cube-face left">KUBUS</div>
                                <div class="cube-face top">TOP</div>
                                <div class="cube-face bottom">BOT</div>
                            </div>
                        </div>
                        
                        <!-- 2D Grid -->
                        <div id="viz2DContent" class="viz-content">
                            <!-- Grid will be generated here -->
                        </div>
                        
                        <!-- 1D Line -->
                        <div id="viz1DContent" class="viz-content">
                            <!-- Line will be generated here -->
                        </div>
                    </div>

                    <!-- Control Buttons -->
                    <div class="control-buttons">
                        <button class="control-btn" onclick="toggleRotation()">⏸️ Pause/Play</button>
                        <button class="control-btn" onclick="resetView()">🔄 Reset</button>
                        <button class="control-btn" onclick="showCubeNet()">📄 Jaring-Jaring</button>
                    </div>
                    
                    <!-- Educational Text -->
                    <div class="educational-text" id="vizEducationalText">
                        <p><strong>🎲 Setiap sisi kubus menampilkan informasi berbeda:</strong></p>
                        <p>• Depan: Formula eksponen (2³)</p>
                        <p>• Belakang: Hasil perhitungan (8)</p>
                        <p>• Kanan: Perkalian berulang (2×2×2)</p>
                        <p>• Kiri: Nama bangun (KUBUS)</p>
                        
                        <div class="educational-text">
                            <p><strong>💡 "Eksponen berarti perkalian berulang"</strong></p>
                            <p><strong>2³ = 2 × 2 × 2 = 8</strong> (kubus dengan 2 satuan di setiap sisi)</p>
                        </div>
                    </div>
                </div>

                <!-- Eksponen Explorer -->
                <div class="interactive-main">
                    <h3>🔍 Eksponen Explorer</h3>
                    <div class="explorer-grid">
                        <div class="explorer-cube" onclick="showCubeDetail(1)">
                            <h4>1³</h4>
                            <p>= 1</p>
                        </div>
                        <div class="explorer-cube" onclick="showCubeDetail(2)">
                            <h4>2³</h4>
                            <p>= 8</p>
                        </div>
                        <div class="explorer-cube" onclick="showCubeDetail(3)">
                            <h4>3³</h4>
                            <p>= 27</p>
                        </div>
                        <div class="explorer-cube" onclick="showCubeDetail(4)">
                            <h4>4³</h4>
                            <p>= 64</p>
                        </div>
                    </div>
                    
                    <div id="cubeDetail1" class="cube-detail">
                        <h4>1³ = 1 × 1 × 1 = 1</h4>
                        <p>Kubus terkecil dengan volume 1 satuan kubik. Setiap sisi berukuran 1 satuan.</p>
                    </div>
                    <div id="cubeDetail2" class="cube-detail">
                        <h4>2³ = 2 × 2 × 2 = 8</h4>
                        <p>Kubus dengan volume 8 satuan kubik. Setiap sisi berukuran 2 satuan.</p>
                    </div>
                    <div id="cubeDetail3" class="cube-detail">
                        <h4>3³ = 3 × 3 × 3 = 27</h4>
                        <p>Kubus dengan volume 27 satuan kubik. Setiap sisi berukuran 3 satuan.</p>
                    </div>
                    <div id="cubeDetail4" class="cube-detail">
                        <h4>4³ = 4 × 4 × 4 = 64</h4>
                        <p>Kubus dengan volume 64 satuan kubik. Setiap sisi berukuran 4 satuan.</p>
                    </div>
                </div>
                
                <!-- Calculator -->
                <div class="calculator">
                    <h3>🧮 Kalkulator Volume</h3>
                    <div class="calc-display" id="calcDisplay">
                        2³ = 2 × 2 × 2 = 8
                    </div>
                    <div class="educational-text">
                        <p><strong>💡 "Eksponen berarti perkalian berulang"</strong></p>
                        <p><strong>2³ = 2 × 2 × 2 = 8</strong> (kubus dengan 2 satuan di setiap sisi)</p>
                    </div>
                </div>

                <!-- Cube Net Section -->
                <div id="cubeNetSection" class="cube-net-container" style="display: none;">
                    <h3>📄 Jaring-Jaring Kubus Siap Cetak (A4)</h3>
                    <div class="print-instructions">
                        <p><strong>📋 Petunjuk Cetak:</strong></p>
                        <p>• Cetak pada kertas A4 (210 × 297 mm)</p>
                        <p>• Gunakan kertas karton untuk hasil terbaik</p>
                        <p>• Pastikan skala cetak 100% (tidak diperkecil)</p>
                    </div>
                    
                    <div class="cube-net-printable" id="cubeNetPrintable">
                        <svg viewBox="0 0 600 450" class="cube-net-svg">
                            <!-- Cube Net Pattern -->
                            <!-- Top face -->
                            <g class="net-face" data-face="top">
                                <rect x="200" y="0" width="100" height="100" fill="#ffa726" stroke="#333" stroke-width="2" stroke-dasharray="5,5"/>
                                <text x="250" y="35" text-anchor="middle" font-size="14" font-weight="bold">TOP</text>
                                <text x="250" y="55" text-anchor="middle" font-size="20" font-weight="bold" id="topLabel">2³</text>
                                <text x="250" y="75" text-anchor="middle" font-size="12" id="topValue">= 8</text>
                                <!-- Fold lines -->
                                <line x1="200" y1="100" x2="300" y2="100" stroke="#666" stroke-width="1" stroke-dasharray="3,3"/>
                            </g>
                            
                            <!-- Left face -->
                            <g class="net-face" data-face="left">
                                <rect x="100" y="100" width="100" height="100" fill="#ab47bc" stroke="#333" stroke-width="2"/>
                                <text x="150" y="125" text-anchor="middle" font-size="12" font-weight="bold">SISI</text>
                                <text x="150" y="145" text-anchor="middle" font-size="12" font-weight="bold">KIRI</text>
                                <text x="150" y="165" text-anchor="middle" font-size="16" font-weight="bold" id="leftLabel">a³</text>
                                <text x="150" y="185" text-anchor="middle" font-size="10" id="leftValue">Volume</text>
                                <!-- Fold lines -->
                                <line x1="200" y1="100" x2="200" y2="200" stroke="#666" stroke-width="1" stroke-dasharray="3,3"/>
                            </g>
                            
                            <!-- Front face -->
                            <g class="net-face" data-face="front">
                                <rect x="200" y="100" width="100" height="100" fill="#42a5f5" stroke="#333" stroke-width="2"/>
                                <text x="250" y="125" text-anchor="middle" font-size="12" font-weight="bold">DEPAN</text>
                                <text x="250" y="150" text-anchor="middle" font-size="24" font-weight="bold" id="frontLabel">2³</text>
                                <text x="250" y="175" text-anchor="middle" font-size="12" id="frontCalc">2×2×2</text>
                                <text x="250" y="190" text-anchor="middle" font-size="14" font-weight="bold" id="frontResult">= 8</text>
                                <!-- Fold lines -->
                                <line x1="300" y1="100" x2="300" y2="200" stroke="#666" stroke-width="1" stroke-dasharray="3,3"/>
                                <line x1="200" y1="200" x2="300" y2="200" stroke="#666" stroke-width="1" stroke-dasharray="3,3"/>
                            </g>
                            
                            <!-- Right face -->
                            <g class="net-face" data-face="right">
                                <rect x="300" y="100" width="100" height="100" fill="#ff7043" stroke="#333" stroke-width="2"/>
                                <text x="350" y="125" text-anchor="middle" font-size="12" font-weight="bold">SISI</text>
                                <text x="350" y="145" text-anchor="middle" font-size="12" font-weight="bold">KANAN</text>
                                <text x="350" y="165" text-anchor="middle" font-size="16" font-weight="bold" id="rightLabel">2³</text>
                                <text x="350" y="185" text-anchor="middle" font-size="10" id="rightValue">Kubus</text>
                                <!-- Fold lines -->
                                <line x1="400" y1="100" x2="400" y2="200" stroke="#666" stroke-width="1" stroke-dasharray="3,3"/>
                            </g>
                            
                            <!-- Back face -->
                            <g class="net-face" data-face="back">
                                <rect x="400" y="100" width="100" height="100" fill="#66bb6a" stroke="#333" stroke-width="2"/>
                                <text x="450" y="125" text-anchor="middle" font-size="12" font-weight="bold">BELAKANG</text>
                                <text x="450" y="150" text-anchor="middle" font-size="28" font-weight="bold" id="backLabel">8</text>
                                <text x="450" y="175" text-anchor="middle" font-size="12">Hasil</text>
                                <text x="450" y="190" text-anchor="middle" font-size="12" id="backUnit">satuan³</text>
                            </g>
                            
                            <!-- Bottom face -->
                            <g class="net-face" data-face="bottom">
                                <rect x="200" y="200" width="100" height="100" fill="#26a69a" stroke="#333" stroke-width="2" stroke-dasharray="5,5"/>
                                <text x="250" y="225" text-anchor="middle" font-size="14" font-weight="bold">BOTTOM</text>
                                <text x="250" y="245" text-anchor="middle" font-size="12">Alas</text>
                                <text x="250" y="265" text-anchor="middle" font-size="16" font-weight="bold" id="bottomLabel">2³</text>
                                <text x="250" y="285" text-anchor="middle" font-size="10" id="bottomValue">= 8</text>
                            </g>
                            
                            <!-- Glue tabs -->
                            <g class="glue-tabs">
                                <!-- Tab for top -->
                                <polygon points="220,0 280,0 270,15 230,15" fill="#f0f0f0" stroke="#333" stroke-width="1"/>
                                <text x="250" y="10" text-anchor="middle" font-size="8" font-weight="bold">LEM</text>
                                
                                <!-- Tab for left -->
                                <polygon points="100,120 85,120 85,180 100,180" fill="#f0f0f0" stroke="#333" stroke-width="1"/>
                                <text x="92" y="155" text-anchor="middle" font-size="6" font-weight="bold" transform="rotate(-90 92 155)">LEM</text>
                                
                                <!-- Tab for right -->
                                <polygon points="400,120 415,120 415,180 400,180" fill="#f0f0f0" stroke="#333" stroke-width="1"/>
                                <text x="408" y="155" text-anchor="middle" font-size="6" font-weight="bold" transform="rotate(90 408 155)">LEM</text>
                                
                                <!-- Tab for back -->
                                <polygon points="500,120 515,120 515,180 500,180" fill="#f0f0f0" stroke="#333" stroke-width="1"/>
                                <text x="508" y="155" text-anchor="middle" font-size="6" font-weight="bold" transform="rotate(90 508 155)">LEM</text>
                                
                                <!-- Tab for bottom -->
                                <polygon points="220,300 280,300 270,315 230,315" fill="#f0f0f0" stroke="#333" stroke-width="1"/>
                                <text x="250" y="310" text-anchor="middle" font-size="8" font-weight="bold">LEM</text>
                            </g>
                            
                            <!-- Cut lines legend -->
                            <g class="legend">
                                <line x1="50" y1="350" x2="80" y2="350" stroke="#333" stroke-width="2"/>
                                <text x="90" y="355" font-size="12">Garis Potong (Tebal)</text>
                                
                                <line x1="50" y1="370" x2="80" y2="370" stroke="#666" stroke-width="1" stroke-dasharray="3,3"/>
                                <text x="90" y="375" font-size="12">Garis Lipat (Putus-putus)</text>
                                
                                <rect x="50" y="385" width="15" height="10" fill="#f0f0f0" stroke="#333" stroke-width="1"/>
                                <text x="75" y="393" font-size="12">Tab Lem</text>
                            </g>
                            
                            <!-- Assembly instructions -->
                            <g class="instructions">
                                <text x="350" y="350" font-size="14" font-weight="bold">📋 Panduan Perakitan:</text>
                                <text x="350" y="370" font-size="12">1. Potong sepanjang garis tebal</text>
                                <text x="350" y="385" font-size="12">2. Lipat sepanjang garis putus-putus</text>
                                <text x="350" y="400" font-size="12">3. Oleskan lem pada tab bertanda "LEM"</text>
                                <text x="350" y="415" font-size="12">4. Rekatkan untuk membentuk kubus</text>
                            </g>
                        </svg>
                    </div>
                    
                    <div class="print-controls">
                        <button class="control-btn" onclick="printCubeNet()">🖨️ Cetak Jaring-Jaring</button>
                        <button class="control-btn" onclick="downloadCubeNet()">💾 Download SVG</button>
                        <button class="control-btn" onclick="updateCubeNet()">🔄 Update Nilai</button>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <script>
        let currentBase = 2;
        let currentDimension = 3;
        let isRotating = true;
        let activePanel = null;

        const baseInput = document.getElementById('baseInput');
        const resultDisplay = document.getElementById('resultDisplay');
        const conceptExplanation = document.getElementById('conceptExplanation');
        const calcDisplay = document.getElementById('calcDisplay');

        baseInput.addEventListener('input', function() {
            currentBase = parseInt(this.value) || 1;
            if (currentBase < 1) currentBase = 1;
            if (currentBase > 9) currentBase = 9;
            this.value = currentBase;
            updateDisplay();
        });

        function togglePanel(panelId) {
            // Hide all panels
            document.querySelectorAll('.content-panel').forEach(panel => {
                panel.classList.remove('active');
            });
            
            // Show selected panel
            const panel = document.getElementById(panelId);
            if (activePanel === panelId) {
                activePanel = null;
            } else {
                panel.classList.add('active');
                activePanel = panelId;
                
                // Initialize visualizations when interactive panel is opened
                if (panelId === 'interactive') {
                    initVisualization3D(); // Default to 3D
                    currentDimension = 3;
                }
            }
        }

        function updateDisplay() {
            const power1 = currentBase;
            const power2 = currentBase * currentBase;
            const power3 = currentBase * currentBase * currentBase;

            resultDisplay.textContent = `a³ = ${power3}`;
            
            conceptExplanation.innerHTML = `
                <div class="concept-card dim1">
                    <h4>${currentBase}¹ = ${power1}</h4>
                    <p>Panjang garis ${currentBase} satuan</p>
                </div>
                <div class="concept-card dim2">
                    <h4>${currentBase}² = ${power2}</h4>
                    <p>Luas persegi ${currentBase}×${currentBase} = ${power2} satuan²</p>
                </div>
                <div class="concept-card dim3">
                    <h4>${currentBase}³ = ${power3}</h4>
                    <p>Volume kubus ${currentBase}×${currentBase}×${currentBase} = ${power3} satuan³</p>
                </div>
            `;

            updateCalculator();
            
            // Update active visualizations
            if (activePanel === 'interactive') {
                if (currentDimension === 1) {
                    updateVisualization1D();
                    updateEducationalText(1);
                } else if (currentDimension === 2) {
                    updateVisualization2D();
                    updateEducationalText(2);
                } else if (currentDimension === 3) {
                    updateVisualization3D();
                    updateEducationalText(3);
                }
            }
        }

        function updateCalculator() {
            const power = Math.pow(currentBase, currentDimension);
            let calculation = '';
            
            if (currentDimension === 1) {
                calculation = `${currentBase}¹ = ${power}`;
            } else if (currentDimension === 2) {
                calculation = `${currentBase}² = ${currentBase} × ${currentBase} = ${power}`;
            } else {
                calculation = `${currentBase}³ = ${currentBase} × ${currentBase} × ${currentBase} = ${power}`;
            }
            
            calcDisplay.textContent = calculation;
        }

        function showVisualization(dimension) {
            // Update dimension buttons
            document.querySelectorAll('.dim-btn').forEach(btn => btn.classList.remove('active'));
            document.querySelector(`.dim-btn.dim${dimension}`).classList.add('active');
            
            // Hide all visualization contents
            document.querySelectorAll('.viz-content').forEach(content => content.classList.remove('active'));
            
            // Show selected visualization
            currentDimension = dimension;
            
            if (dimension === 1) {
                document.getElementById('viz1DContent').classList.add('active');
                initVisualization1D();
                updateEducationalText(1);
            } else if (dimension === 2) {
                document.getElementById('viz2DContent').classList.add('active');
                initVisualization2D();
                updateEducationalText(2);
            } else if (dimension === 3) {
                document.getElementById('viz3DContent').classList.add('active');
                initVisualization3D();
                updateEducationalText(3);
            }
            
            updateCalculator();
        }

        function updateEducationalText(dimension) {
            const textElement = document.getElementById('vizEducationalText');
            
            if (dimension === 1) {
                textElement.innerHTML = `
                    <p><strong>📏 a¹ menunjukkan panjang garis:</strong></p>
                    <p>• Setiap segmen bernomor dan berpulsa</p>
                    <p>• Garis terbagi menjadi a segmen</p>
                    <p>• Total panjang = a¹ = a</p>
                    
                    <div class="educational-text">
                        <p><strong>💡 "Eksponen 1 berarti bilangan itu sendiri"</strong></p>
                        <p><strong>${currentBase}¹ = ${currentBase}</strong> (garis dengan ${currentBase} satuan panjang)</p>
                    </div>
                `;
            } else if (dimension === 2) {
                textElement.innerHTML = `
                    <p><strong>📊 a² menunjukkan luas persegi:</strong></p>
                    <p>• Setiap sel muncul dengan animasi bertahap</p>
                    <p>• Grid berubah sesuai basis yang dipilih</p>
                    <p>• Total sel = a × a = a²</p>
                    
                    <div class="educational-text">
                        <p><strong>💡 "Eksponen 2 berarti perkalian dua kali"</strong></p>
                        <p><strong>${currentBase}² = ${currentBase} × ${currentBase} = ${Math.pow(currentBase, 2)}</strong> (persegi dengan sisi ${currentBase} satuan)</p>
                    </div>
                `;
            } else {
                textElement.innerHTML = `
                    <p><strong>🎲 Setiap sisi kubus menampilkan informasi berbeda:</strong></p>
                    <p>• Depan: Formula eksponen (${currentBase}³)</p>
                    <p>• Belakang: Hasil perhitungan (${Math.pow(currentBase, 3)})</p>
                    <p>• Kanan: Perkalian berulang (${currentBase}×${currentBase}×${currentBase})</p>
                    <p>• Kiri: Nama bangun (KUBUS)</p>
                    
                    <div class="educational-text">
                        <p><strong>💡 "Eksponen berarti perkalian berulang"</strong></p>
                        <p><strong>${currentBase}³ = ${currentBase} × ${currentBase} × ${currentBase} = ${Math.pow(currentBase, 3)}</strong> (kubus dengan ${currentBase} satuan di setiap sisi)</p>
                    </div>
                `;
            }
        }

        function initVisualization3D() {
            updateVisualization3D();
        }

        function updateVisualization3D() {
            const power = Math.pow(currentBase, 3);
            const area = document.getElementById('viz3DContent');
            
            area.innerHTML = `
                <div class="cube-3d" id="cube3d">
                    <div class="cube-face front">${currentBase}³</div>
                    <div class="cube-face back">${power}</div>
                    <div class="cube-face right">${currentBase}×${currentBase}×${currentBase}</div>
                    <div class="cube-face left">KUBUS</div>
                    <div class="cube-face top">TOP</div>
                    <div class="cube-face bottom">BOT</div>
                </div>
            `;
            
            if (!isRotating) {
                document.getElementById('cube3d').classList.add('paused');
            }
        }

        function initVisualization2D() {
            updateVisualization2D();
        }

        function updateVisualization2D() {
            const power = Math.pow(currentBase, 2);
            const area = document.getElementById('viz2DContent');
            
            const grid = document.createElement('div');
            grid.className = 'grid-2d';
            grid.style.gridTemplateColumns = `repeat(${currentBase}, 1fr)`;
            
            for (let i = 0; i < power; i++) {
                const cell = document.createElement('div');
                cell.className = 'grid-cell';
                cell.textContent = i + 1;
                cell.style.animationDelay = `${i * 0.1}s`;
                grid.appendChild(cell);
            }
            
            area.innerHTML = '';
            area.appendChild(grid);
        }

        function initVisualization1D() {
            updateVisualization1D();
        }

        function updateVisualization1D() {
            const area = document.getElementById('viz1DContent');
            
            area.innerHTML = `<div class="line-1d" id="line1d"></div>`;
            const line = document.getElementById('line1d');
            line.innerHTML = '';
            
            for (let i = 0; i < currentBase; i++) {
                const segment = document.createElement('div');
                segment.className = 'line-segment';
                segment.style.left = `${(i / currentBase) * 100}%`;
                segment.style.width = `${100 / currentBase}%`;
                segment.textContent = i + 1;
                segment.style.animationDelay = `${i * 0.3}s`;
                line.appendChild(segment);
            }
        }

        function toggleRotation() {
            isRotating = !isRotating;
            const cube = document.getElementById('cube3d');
            if (cube) {
                if (isRotating) {
                    cube.classList.remove('paused');
                } else {
                    cube.classList.add('paused');
                }
            }
        }

        function resetView() {
            currentBase = 2;
            currentDimension = 3;
            isRotating = true;
            baseInput.value = 2;
            
            updateDisplay();
            
            if (activePanel === 'interactive') {
                updateVisualization3D();
            }
        }

        function showCubeDetail(cubeNum) {
            // Remove active class from all cubes and details
            document.querySelectorAll('.explorer-cube').forEach(cube => cube.classList.remove('active'));
            document.querySelectorAll('.cube-detail').forEach(detail => detail.classList.remove('active'));
            
            // Add active class to selected cube and detail
            document.querySelectorAll('.explorer-cube')[cubeNum - 1].classList.add('active');
            document.getElementById(`cubeDetail${cubeNum}`).classList.add('active');
        }

        function showCubeNet() {
            const netSection = document.getElementById('cubeNetSection');
            if (netSection.style.display === 'none') {
                netSection.style.display = 'block';
                updateCubeNet();
            } else {
                netSection.style.display = 'none';
            }
        }

        function updateCubeNet() {
            const power = Math.pow(currentBase, 3);
            
            // Update all labels in the cube net
            const elements = {
                'topLabel': `${currentBase}³`,
                'topValue': `= ${power}`,
                'leftLabel': `${currentBase}³`,
                'frontLabel': `${currentBase}³`,
                'frontCalc': `${currentBase}×${currentBase}×${currentBase}`,
                'frontResult': `= ${power}`,
                'rightLabel': `${currentBase}³`,
                'backLabel': `${power}`,
                'backUnit': 'satuan³',
                'bottomLabel': `${currentBase}³`,
                'bottomValue': `= ${power}`
            };
            
            Object.entries(elements).forEach(([id, value]) => {
                const element = document.getElementById(id);
                if (element) {
                    element.textContent = value;
                }
            });
        }

        function printCubeNet() {
            // Create a new window for printing
            const printWindow = window.open('', '_blank');
            const cubeNetHTML = document.getElementById('cubeNetPrintable').innerHTML;
            
            printWindow.document.write(`
                <!DOCTYPE html>
                <html>
                <head>
                    <title>Jaring-Jaring Kubus Eksponen</title>
                    <style>
                        body { 
                            margin: 0; 
                            padding: 20px; 
                            font-family: 'Comic Sans MS', cursive, sans-serif;
                        }
                        .cube-net-svg { 
                            width: 100%; 
                            max-width: 600px; 
                            height: auto; 
                        }
                        @page { 
                            size: A4; 
                            margin: 1cm; 
                        }
                    </style>
                </head>
                <body>
                    <h2>🎲 Jaring-Jaring Volume Eksponen</h2>
                    <p><strong>Basis: ${currentBase}</strong> | <strong>Volume: ${Math.pow(currentBase, 3)} satuan³</strong></p>
                    ${cubeNetHTML}
                </body>
                </html>
            `);
            
            printWindow.document.close();
            printWindow.print();
        }

        function downloadCubeNet() {
            const svg = document.querySelector('.cube-net-svg');
            const svgData = new XMLSerializer().serializeToString(svg);
            const svgBlob = new Blob([svgData], {type: 'image/svg+xml;charset=utf-8'});
            const svgUrl = URL.createObjectURL(svgBlob);
            
            const downloadLink = document.createElement('a');
            downloadLink.href = svgUrl;
            downloadLink.download = `jaring-jaring-kubus-${currentBase}pangkat3.svg`;
            document.body.appendChild(downloadLink);
            downloadLink.click();
            document.body.removeChild(downloadLink);
            URL.revokeObjectURL(svgUrl);
        }

        // Initialize display
        updateDisplay();
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'98f6183ed0e64ad1',t:'MTc2MDYwMjM4My4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
