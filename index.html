<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>디지털 전시 여권</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #FDF3CD;
            min-height: 100vh;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .container {
            width: 100%;
            max-width: 1000px;
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 30px;
            background-color: #FDF3CD;
            padding: 40px;
            border-radius: 10px;
        }

        /* ========== 공통 스타일 ========== */
        .title-box {
            padding: 10px 15px;
            border-radius: 5px;
            font-size: 18px;
            font-weight: bold;
            font-style: italic;
            color: black;
            margin-bottom: 20px;
            text-align: left;
        }

        .blue-title {
            background-color: #87CEEB;
        }

        .pink-title {
            background-color: #FFB6D9;
        }

        /* ========== LEFT SECTION (BAGGAGE ENTRY & JOURNEY THREADS) ========== */
        .left-section {
            display: flex;
            flex-direction: column;
        }

        .baggage-entry {
            margin-bottom: 0;
            position: relative;
        }

        .random-question-box {
            background-color: rgba(135, 206, 235, 0.15);
            padding: 15px;
            border-radius: 5px;
            margin-bottom: 20px;
            border-left: 4px solid #87CEEB;
        }

        .random-question-label {
            font-size: 12px;
            color: #666;
            text-transform: uppercase;
            font-weight: 600;
            margin-bottom: 8px;
        }

        .random-question-text {
            font-size: 16px;
            color: #333;
            font-style: italic;
            line-height: 1.5;
        }

        .input-group {
            margin-bottom: 20px;
            display: flex;
            align-items: flex-start;
            gap: 15px;
        }

        .input-group.full {
            flex-direction: column;
        }

        .input-label {
            font-size: 14px;
            font-weight: 600;
            color: #333;
            margin-bottom: 8px;
            display: block;
        }

        .input-line {
            display: flex;
            align-items: flex-end;
            gap: 10px;
            flex: 1;
        }

        .input-underline {
            flex: 1;
            border: none;
            border-bottom: 2px solid #333;
            background-color: transparent;
            padding: 8px 0;
            font-size: 14px;
            font-family: inherit;
            outline: none;
            transition: border-color 0.3s;
        }

        .input-underline:focus {
            border-bottom-color: #87CEEB;
        }

        .input-unit {
            font-size: 14px;
            font-weight: 600;
            color: #333;
            min-width: 20px;
        }

        .weight-group {
            display: flex;
            align-items: flex-end;
            gap: 5px;
        }

        .weight-group .input-underline {
            flex: 0 1 100px;
        }

        .stamp-container {
            display: flex;
            align-items: center;
            justify-content: center;
            min-height: 80px;
            margin-left: auto;
        }

        .stamp-image {
            max-width: 220px;
            max-height: 220px;
            opacity: 0;
            transition: opacity 0.5s ease-in-out;
            transform: rotate(-15deg);
        }

        .stamp-image.show {
            opacity: 1;
        }

        .journey-section {
            background-color: #FFB6D9;
            padding: 15px;
            border-radius: 5px;
            margin-top: 0;
        }

        .journey-title {
            font-size: 14px;
            font-weight: bold;
            font-style: italic;
            color: black;
            margin-bottom: 15px;
        }

        .canvas-container {
            background-color: rgba(255, 255, 255, 0.7);
            border-radius: 5px;
            padding: 10px;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        #journeyCanvas {
            display: block;
            cursor: crosshair;
            touch-action: none;
            background-color: rgba(255, 255, 255, 0.9);
            border-radius: 3px;
        }

        /* ========== RIGHT SECTION (VISIT LOCATION & CHECK-IN) ========== */
        .right-section {
            display: flex;
            flex-direction: column;
        }

        .visit-location {
            margin-bottom: 30px;
            flex-grow: 1;
            display: flex;
            flex-direction: column;
        }

        .location-main-box {
            border: 3px solid #4A90E2;
            background-color: rgba(255, 255, 255, 0.8);
            padding: 20px;
            border-radius: 5px;
            flex-grow: 1;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 250px;
            text-align: center;
            margin-bottom: 15px;
        }

        .location-preview-text {
            font-size: 14px;
            color: #999;
            font-style: italic;
        }

        .location-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 10px;
            margin-bottom: 10px;
        }

        .location-item {
            aspect-ratio: 1;
            border: 2px solid #ddd;
            border-radius: 5px;
            cursor: pointer;
            background-color: white;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 14px;
            font-weight: 600;
            color: #666;
            transition: all 0.3s;
            overflow: hidden;
        }

        .location-item:hover {
            border-color: #4A90E2;
            box-shadow: 0 2px 8px rgba(74, 144, 226, 0.2);
        }

        .location-item.selected {
            border-color: #4A90E2;
            background-color: #4A90E2;
            color: white;
            box-shadow: 0 4px 12px rgba(74, 144, 226, 0.4);
        }

        .check-in-section {
            margin-top: auto;
        }

        .check-in-label {
            font-size: 14px;
            font-weight: 600;
            color: #333;
            margin-bottom: 5px;
        }

        .room-type-label {
            font-size: 12px;
            color: #666;
            margin-bottom: 10px;
        }

        .room-selector {
            display: flex;
            gap: 15px;
            align-items: center;
        }

        .checkbox {
            width: 40px;
            height: 40px;
            border: 3px solid;
            border-radius: 4px;
            cursor: pointer;
            background-color: white;
            transition: all 0.3s;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            color: white;
        }

        .checkbox.blue {
            border-color: #4A90E2;
        }

        .checkbox.blue.selected {
            background-color: #4A90E2;
        }

        .checkbox.orange {
            border-color: #FF9500;
        }

        .checkbox.orange.selected {
            background-color: #FF9500;
        }

        .checkbox.green {
            border-color: #4CAF50;
        }

        .checkbox.green.selected {
            background-color: #4CAF50;
        }

        /* ========== BUTTON & STATS ========== */
        .button-container {
            grid-column: 1 / -1;
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-top: 30px;
        }

        .btn {
            padding: 12px 30px;
            font-size: 16px;
            font-weight: bold;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: all 0.3s;
        }

        .btn-submit {
            background-color: #4A90E2;
            color: white;
        }

        .btn-submit:hover {
            background-color: #2E5C8A;
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
        }

        .btn-reset {
            background-color: #FFB6D9;
            color: #333;
        }

        .btn-reset:hover {
            background-color: #FF95B8;
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
        }

        /* ========== STATS SCREEN ========== */
        .stats-overlay {
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-color: rgba(0, 0, 0, 0.5);
            display: none;
            justify-content: center;
            align-items: center;
            z-index: 1000;
            padding: 20px;
        }

        .stats-overlay.show {
            display: flex;
        }

        .stats-card {
            background-color: #FDF3CD;
            padding: 40px;
            border-radius: 15px;
            max-width: 600px;
            width: 100%;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.3);
            animation: slideUp 0.5s ease-out;
        }

        @keyframes slideUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .stats-title {
            font-size: 24px;
            font-weight: bold;
            color: #333;
            margin-bottom: 30px;
            text-align: center;
        }

        .room-stat {
            margin-bottom: 25px;
            display: flex;
            align-items: center;
            gap: 15px;
        }

        .stat-color-box {
            width: 20px;
            height: 20px;
            border-radius: 3px;
            flex-shrink: 0;
        }

        .stat-info {
            flex-grow: 1;
        }

        .stat-label {
            font-size: 14px;
            font-weight: 600;
            color: #333;
            margin-bottom: 5px;
        }

        .stat-bar {
            background-color: #e0e0e0;
            height: 20px;
            border-radius: 10px;
            overflow: hidden;
            min-width: 150px;
        }

        .stat-fill {
            height: 100%;
            display: flex;
            align-items: center;
            justify-content: flex-end;
            padding-right: 8px;
            color: white;
            font-size: 12px;
            font-weight: bold;
        }

        .stat-fill.blue {
            background-color: #4A90E2;
        }

        .stat-fill.orange {
            background-color: #FF9500;
        }

        .stat-fill.green {
            background-color: #4CAF50;
        }

        .stats-action {
            display: flex;
            gap: 10px;
            justify-content: center;
            margin-top: 30px;
        }

        /* ========== LOADING STATE ========== */
        .loading {
            display: inline-block;
            opacity: 0.6;
            pointer-events: none;
        }

        /* ========== 모바일 반응형 ========== */
        @media (max-width: 768px) {
            .container {
                grid-template-columns: 1fr;
                gap: 20px;
                padding: 20px;
            }

            .title-box {
                font-size: 16px;
            }

            .location-main-box {
                min-height: 200px;
            }

            .input-group {
                flex-direction: column;
            }

            .stamp-container {
                margin-left: 0;
                margin-top: 10px;
            }
        }
    </style>
</head>
<body>
    <!-- ========== MAIN CONTAINER ========== -->
    <div class="container">
        <!-- LEFT SECTION -->
        <div class="left-section">
            <!-- BAGGAGE ENTRY TITLE -->
            <div class="title-box blue-title">BAGGAGE ENTRY</div>

            <!-- RANDOM QUESTION -->
            <div class="random-question-box">
                <div class="random-question-label">오늘의 질문</div>
                <div class="random-question-text" id="randomQuestion">당신의 여행 가방에 들어있는 물건 하나를 생각해보세요</div>
            </div>

            <!-- BAGGAGE ENTRY INPUTS -->
            <div class="baggage-entry">
                <div class="input-group full">
                    <label class="input-label">Declared Item</label>
                    <input type="text" id="declaredItem" class="input-underline" placeholder="아이템 이름을 입력해주세요">
                </div>

                <div class="input-group">
                    <div>
                        <label class="input-label">Weight</label>
                        <div class="input-line weight-group">
                            <input type="number" id="itemWeight" class="input-underline" placeholder="0" min="0">
                            <span class="input-unit">g</span>
                        </div>
                    </div>
                    <div class="stamp-container">
                        <img class="stamp-image" id="stamp" src="https://raw.githubusercontent.com/lisub303/checkinto/main/pass%EB%8F%84%EC%9E%A5.png" alt="Pass Stamp">
                    </div>
                </div>
            </div>

            <!-- JOURNEY THREADS -->
            <div class="journey-section">
                <div class="journey-title">Journey Threads</div>
                <div class="canvas-container">
                    <canvas id="journeyCanvas" width="220" height="200"></canvas>
                </div>
            </div>
        </div>

        <!-- RIGHT SECTION -->
        <div class="right-section">
            <!-- VISIT LOCATION TITLE -->
            <div class="title-box pink-title">Visit Location</div>

            <!-- VISIT LOCATION - MAIN DISPLAY -->
            <div class="visit-location">
                <div class="location-main-box" id="locationMainBox">
                    <div class="location-preview-text">PDF를 선택하세요</div>
                </div>

                <!-- LOCATION GRID (3x3) -->
                <div class="location-grid" id="locationGrid">
                    <!-- 동적으로 생성됨 -->
                </div>
            </div>

            <!-- CHECK-IN SECTION -->
            <div class="check-in-section">
                <div class="check-in-label">Check-in</div>
                <div class="room-type-label">Room type</div>
                <div class="room-selector">
                    <div class="checkbox blue" data-room="blue"></div>
                    <div class="checkbox orange" data-room="orange"></div>
                    <div class="checkbox green" data-room="green"></div>
                </div>
            </div>
        </div>

        <!-- BUTTON SECTION -->
        <div class="button-container">
            <button class="btn btn-submit" id="submitBtn">여권 발행하기</button>
            <button class="btn btn-reset" id="resetBtn">초기화</button>
        </div>
    </div>

    <!-- ========== STATS MODAL ========== -->
    <div class="stats-overlay" id="statsOverlay">
        <div class="stats-card">
            <div class="stats-title">✨ 방문자 통계</div>
            
            <div class="room-stat">
                <div class="stat-color-box blue" style="background-color: #4A90E2;"></div>
                <div class="stat-info">
                    <div class="stat-label">Blue Room</div>
                    <div class="stat-bar">
                        <div class="stat-fill blue" id="bluePercentage" style="width: 0%">0%</div>
                    </div>
                </div>
            </div>

            <div class="room-stat">
                <div class="stat-color-box orange" style="background-color: #FF9500;"></div>
                <div class="stat-info">
                    <div class="stat-label">Orange Room</div>
                    <div class="stat-bar">
                        <div class="stat-fill orange" id="orangePercentage" style="width: 0%">0%</div>
                    </div>
                </div>
            </div>

            <div class="room-stat">
                <div class="stat-color-box green" style="background-color: #4CAF50;"></div>
                <div class="stat-info">
                    <div class="stat-label">Green Room</div>
                    <div class="stat-bar">
                        <div class="stat-fill green" id="greenPercentage" style="width: 0%">0%</div>
                    </div>
                </div>
            </div>

            <div class="stats-action">
                <button class="btn btn-reset" id="closeStatsBtn">닫기</button>
                <button class="btn btn-submit" id="newEntryBtn">다시 입력하기</button>
            </div>
        </div>
    </div>

    <script>
        /* ========== CONFIGURATION ========== */
        // 구글 웹 앱 URL을 여기에 입력하세요
        const SCRIPT_URL = "YOUR_GOOGLE_WEB_APP_URL";
        
        // GitHub Raw 파일 경로
        const GITHUB_RAW = "https://raw.githubusercontent.com/lisub303/checkinto/main/";

        /* ========== RANDOM QUESTIONS ========== */
        const questions = [
            "가장 최근에 산 물건",
            "가장 마음에 드는 물건",
            "누군가에게 선물 받은 물건",
            "여행 갈 때 꼭 챙기는 물건",
            "충동구매한 물건",
            "내 가방에서만 등장할 것 같은 물건",
            "가장 색이 마음에 드는 물건",
            "누군가 떠오르는 물건",
            "평소보다 오늘 특별히 챙긴 물건"
        ];

        /* ========== PDF LIST ========== */
        const pdfFiles = [
            "location_1.pdf",
            "location_2.pdf",
            "location_3.pdf",
            "location_4.pdf",
            "location_5.pdf",
            "loctaion_6.pdf",
            "location_7.pdf",
            "location_8.pdf",
            "location_9.pdf"
        ];

        /* ========== STATE MANAGEMENT ========== */
        let selectedRoom = null;
        let journeyPath = "";
        let isDrawing = false;
        let startDot = null;
        let dots = [];
        let selectedLocationFile = null;

        /* ========== CANVAS SETUP FOR JOURNEY THREADS ========== */
        const canvas = document.getElementById('journeyCanvas');
        const ctx = canvas.getContext('2d');

        // Dot positions (3, 4, 4 layout in columns)
        const dotPositions = [
            // Column 1 (3 dots)
            { x: 30, y: 30 },
            { x: 30, y: 100 },
            { x: 30, y: 170 },
            
            // Column 2 (4 dots)
            { x: 110, y: 15 },
            { x: 110, y: 65 },
            { x: 110, y: 115 },
            { x: 110, y: 165 },
            
            // Column 3 (4 dots)
            { x: 190, y: 15 },
            { x: 190, y: 65 },
            { x: 190, y: 115 },
            { x: 190, y: 165 }
        ];

        // Initialize dots
        function initializeDots() {
            dots = dotPositions.map((pos, index) => ({
                id: index,
                x: pos.x,
                y: pos.y,
                radius: 4
            }));
            drawCanvas();
        }

        function drawCanvas() {
            ctx.clearRect(0, 0, canvas.width, canvas.height);
            
            // Draw dots
            dots.forEach(dot => {
                ctx.beginPath();
                ctx.arc(dot.x, dot.y, dot.radius, 0, Math.PI * 2);
                ctx.fillStyle = '#333';
                ctx.fill();
            });

            // Draw path
            if (journeyPath) {
                ctx.strokeStyle = '#333';
                ctx.lineWidth = 2;
                ctx.setLineDash([5, 5]);
                const pathIds = journeyPath.split('-').map(Number);
                if (pathIds.length > 0) {
                    ctx.beginPath();
                    const firstDot = dots[pathIds[0]];
                    ctx.moveTo(firstDot.x, firstDot.y);
                    for (let i = 1; i < pathIds.length; i++) {
                        const dot = dots[pathIds[i]];
                        ctx.lineTo(dot.x, dot.y);
                    }
                    ctx.stroke();
                    ctx.setLineDash([]);
                }
            }
        }

        function getDotAtPosition(x, y) {
            for (let dot of dots) {
                const distance = Math.sqrt((x - dot.x) ** 2 + (y - dot.y) ** 2);
                if (distance <= dot.radius + 5) {
                    return dot;
                }
            }
            return null;
        }

        canvas.addEventListener('mousedown', (e) => {
            const rect = canvas.getBoundingClientRect();
            const x = e.clientX - rect.left;
            const y = e.clientY - rect.top;
            const dot = getDotAtPosition(x, y);
            
            if (dot) {
                isDrawing = true;
                startDot = dot;
                if (!journeyPath) {
                    journeyPath = String(dot.id);
                } else {
                    const pathIds = journeyPath.split('-').map(Number);
                    if (!pathIds.includes(dot.id)) {
                        journeyPath += '-' + dot.id;
                    }
                }
                drawCanvas();
            }
        });

        canvas.addEventListener('touchstart', (e) => {
            const touch = e.touches[0];
            const rect = canvas.getBoundingClientRect();
            const x = touch.clientX - rect.left;
            const y = touch.clientY - rect.top;
            const dot = getDotAtPosition(x, y);
            
            if (dot) {
                isDrawing = true;
                startDot = dot;
                if (!journeyPath) {
                    journeyPath = String(dot.id);
                } else {
                    const pathIds = journeyPath.split('-').map(Number);
                    if (!pathIds.includes(dot.id)) {
                        journeyPath += '-' + dot.id;
                    }
                }
                drawCanvas();
            }
        });

        canvas.addEventListener('touchend', () => {
            isDrawing = false;
            startDot = null;
        });

        canvas.addEventListener('mouseup', () => {
            isDrawing = false;
            startDot = null;
        });

        /* ========== RANDOM QUESTION ========== */
        function displayRandomQuestion() {
            const randomIndex = Math.floor(Math.random() * questions.length);
            document.getElementById('randomQuestion').textContent = questions[randomIndex];
        }

        /* ========== WEIGHT VALIDATION & STAMP ========== */
        document.getElementById('itemWeight').addEventListener('change', () => {
            const weight = parseInt(document.getElementById('itemWeight').value) || 0;
            const stamp = document.getElementById('stamp');
            
            if (weight >= 120) {
                stamp.classList.add('show');
            } else {
                stamp.classList.remove('show');
            }
        });

        /* ========== LOCATION GRID SETUP ========== */
        function setupLocationGrid() {
            const grid = document.getElementById('locationGrid');
            grid.innerHTML = '';
            
            pdfFiles.forEach((file, index) => {
                const item = document.createElement('div');
                item.className = 'location-item';
                item.innerHTML = `<span>${index + 1}</span>`;
                item.addEventListener('click', () => selectLocation(file, item));
                grid.appendChild(item);
            });
        }

        function selectLocation(file, element) {
            // Remove previous selection
            document.querySelectorAll('.location-item').forEach(item => {
                item.classList.remove('selected');
            });
            
            // Add selection to clicked item
            element.classList.add('selected');
            selectedLocationFile = file;
            
            // Show preview in main box
            const mainBox = document.getElementById('locationMainBox');
            mainBox.innerHTML = `<div class="location-preview-text">✓ ${file} 선택됨</div>`;
        }

        /* ========== ROOM TYPE SELECTION ========== */
        document.querySelectorAll('.checkbox').forEach(checkbox => {
            checkbox.addEventListener('click', () => {
                document.querySelectorAll('.checkbox').forEach(cb => cb.classList.remove('selected'));
                checkbox.classList.add('selected');
                selectedRoom = checkbox.dataset.room;
            });
        });

        /* ========== SUBMIT FUNCTION ========== */
        async function submitEntry() {
            const declaredItem = document.getElementById('declaredItem').value.trim();
            const itemWeight = parseInt(document.getElementById('itemWeight').value) || 0;
            const questionText = document.getElementById('randomQuestion').textContent;

            if (!declaredItem) {
                alert('아이템 이름을 입력해주세요.');
                return;
            }

            if (itemWeight < 120) {
                alert('무게가 120g 이상이어야 합니다.');
                return;
            }

            if (!selectedRoom) {
                alert('Room type을 선택해주세요.');
                return;
            }

            if (!journeyPath) {
                alert('Journey Threads에서 경로를 그려주세요.');
                return;
            }

            if (!selectedLocationFile) {
                alert('Location PDF를 선택해주세요.');
                return;
            }

            // Prepare data
            const formData = new FormData();
            formData.append('declaredItem', declaredItem);
            formData.append('itemWeight', itemWeight);
            formData.append('journeyPath', journeyPath);
            formData.append('question', questionText);
            formData.append('roomType', selectedRoom);
            formData.append('locationFile', selectedLocationFile);

            try {
                document.getElementById('submitBtn').classList.add('loading');
                document.getElementById('submitBtn').textContent = '전송 중...';

                const response = await fetch(SCRIPT_URL, {
                    method: 'POST',
                    body: formData
                });

                if (!response.ok) {
                    throw new Error('전송 실패');
                }

                // Fetch statistics
                await fetchAndDisplayStats();

            } catch (error) {
                console.error('Error:', error);
                alert('데이터 전송 중 오류가 발생했습니다. (구글 웹 앱 URL이 설정되었는지 확인하세요)');
                document.getElementById('submitBtn').classList.remove('loading');
                document.getElementById('submitBtn').textContent = '여권 발행하기';
            }
        }

        /* ========== FETCH STATISTICS ========== */
        async function fetchAndDisplayStats() {
            try {
                const response = await fetch(SCRIPT_URL + '?action=getStats');
                const data = await response.json();

                const total = data.total || 1;
                const blueCount = data.blue || 0;
                const orangeCount = data.orange || 0;
                const greenCount = data.green || 0;

                const bluePercent = Math.round((blueCount / total) * 100);
                const orangePercent = Math.round((orangeCount / total) * 100);
                const greenPercent = Math.round((greenCount / total) * 100);

                document.getElementById('bluePercentage').style.width = bluePercent + '%';
                document.getElementById('bluePercentage').textContent = bluePercent + '%';

                document.getElementById('orangePercentage').style.width = orangePercent + '%';
                document.getElementById('orangePercentage').textContent = orangePercent + '%';

                document.getElementById('greenPercentage').style.width = greenPercent + '%';
                document.getElementById('greenPercentage').textContent = greenPercent + '%';

                showStatsModal();

            } catch (error) {
                console.error('Error fetching stats:', error);
                showStatsModal(); // Show with default values
            } finally {
                document.getElementById('submitBtn').classList.remove('loading');
                document.getElementById('submitBtn').textContent = '여권 발행하기';
            }
        }

        /* ========== MODAL FUNCTIONS ========== */
        function showStatsModal() {
            document.getElementById('statsOverlay').classList.add('show');
        }

        function closeStatsModal() {
            document.getElementById('statsOverlay').classList.remove('show');
        }

        function resetForm() {
            document.getElementById('declaredItem').value = '';
            document.getElementById('itemWeight').value = '';
            journeyPath = '';
            selectedRoom = null;
            selectedLocationFile = null;
            document.querySelectorAll('.checkbox').forEach(cb => cb.classList.remove('selected'));
            document.querySelectorAll('.location-item').forEach(item => item.classList.remove('selected'));
            document.getElementById('locationMainBox').innerHTML = '<div class="location-preview-text">PDF를 선택하세요</div>';
            document.getElementById('stamp').classList.remove('show');
            drawCanvas();
            displayRandomQuestion();
        }

        /* ========== EVENT LISTENERS ========== */
        document.getElementById('submitBtn').addEventListener('click', submitEntry);
        document.getElementById('resetBtn').addEventListener('click', resetForm);
        document.getElementById('closeStatsBtn').addEventListener('click', closeStatsModal);
        document.getElementById('newEntryBtn').addEventListener('click', () => {
            closeStatsModal();
            resetForm();
        });

        /* ========== INITIALIZATION ========== */
        window.addEventListener('load', () => {
            initializeDots();
            displayRandomQuestion();
            setupLocationGrid();
        });
    </script>
</body>
</html>
