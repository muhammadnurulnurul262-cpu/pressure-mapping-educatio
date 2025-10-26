# pressure-mapping-educatio
A simple project about pressure mapping and its concepts. I may not fully understand science yet, but I believe anyone can grow if they have interest and curiosity. If you are interested in science, feel free to add, fix, or improve this project — I really appreciate every contribution and feedback!

<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mapping Tekanan Zat Cair dan Zat Padat</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background-color: #e8f5e8; /* Latar belakang hijau muda untuk tema sains */
            color: #333;
        }
        .mindmap {
            display: flex;
            justify-content: center;
            align-items: flex-start;
            flex-wrap: wrap;
        }
        .node {
            border: 2px solid #333;
            border-radius: 10px;
            padding: 15px;
            margin: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            min-width: 250px;
        }
        .main-node {
            background-color: #b3e5fc; /* Biru muda untuk node utama */
            font-size: 1.5em;
            font-weight: bold;
            text-align: center;
            color: #01579b; /* Biru gelap untuk teks */
        }
        .sub-node {
            background-color: #e1f5fe; /* Biru sangat muda untuk zat cair */
        }
        .sub-node:nth-child(2) { /* Zat padat */
            background-color: #f1f8e9; /* Hijau sangat muda untuk zat padat */
        }
        .sub-sub-node {
            background-color: #fffde7; /* Kuning sangat muda untuk sub-sub-node */
            margin-left: 20px;
            border-left: 3px solid #ffb74d; /* Garis kiri oranye untuk penekanan */
        }
        .formula {
            font-weight: bold;
            color: #d32f2f; /* Merah untuk rumus */
        }
        .example {
            font-style: italic;
            color: #1976d2; /* Biru untuk contoh */
        }
        h1 {
            color: #2e7d32; /* Hijau gelap untuk judul */
            text-align: center;
        }
        p {
            color: #424242; /* Abu-abu gelap untuk teks */
        }
    </style>
</head>
<body>
    <h1>Mapping Konsep: Tekanan Zat Cair dan Zat Padat</h1>
    <p>Berikut adalah peta konsep (mind map) yang menjelaskan tekanan pada zat cair dan zat padat, beserta rumus, penjelasan, dan contoh. Peta ini dibuat menggunakan HTML dan CSS untuk visualisasi sederhana dengan tema sains yang sesuai (biru untuk zat cair, hijau untuk zat padat).</p>
    
    <div class="mindmap">
        <!-- Node Utama -->
        <div class="node main-node">
            Tekanan Zat Cair dan Zat Padat
        </div>
        
        <!-- Sub-node untuk Zat Cair -->
        <div class="node sub-node">
            <h3>Tekanan Zat Cair (Tekanan Hidrostatik)</h3>
            <div class="sub-sub-node">
                <h4>Rumus</h4>
                <p class="formula">P = ρgh</p>
                <p>Dimana:</p>
                <ul>
                    <li>P = Tekanan (Pa)</li>
                    <li>ρ = Massa jenis zat cair (kg/m³)</li>
                    <li>g = Percepatan gravitasi (9,8 m/s²)</li>
                    <li>h = Kedalaman dari permukaan (m)</li>
                </ul>
            </div>
            <div class="sub-sub-node">
                <h4>Penjelasan</h4>
                <p>Tekanan hidrostatik adalah tekanan yang dihasilkan oleh berat zat cair pada kedalaman tertentu. Tekanan ini meningkat seiring dengan kedalaman karena gaya gravitasi menekan cairan ke bawah. Ini berlaku untuk zat cair seperti air, minyak, atau cairan lainnya yang tidak mengalir bebas.</p>
            </div>
            <div class="sub-sub-node">
                <h4>Contoh</h4>
                <p class="example">Di dasar kolam renang dengan kedalaman 2 meter dan massa jenis air 1000 kg/m³, tekanan hidrostatik adalah P = 1000 × 9,8 × 2 = 19.600 Pa (atau sekitar 0,2 atm). Ini menjelaskan mengapa penyelam merasakan tekanan lebih besar di kedalaman.</p>
            </div>
        </div>
        
        <!-- Sub-node untuk Zat Padat -->
        <div class="node sub-node">
            <h3>Tekanan Zat Padat (Tekanan sebagai Gaya per Luas)</h3>
            <div class="sub-sub-node">
                <h4>Rumus</h4>
                <p class="formula">P = F/A</p>
                <p>Dimana:</p>
                <ul>
                    <li>P = Tekanan (Pa)</li>
                    <li>F = Gaya yang diberikan (N)</li>
                    <li>A = Luas permukaan yang menerima gaya (m²)</li>
                </ul>
            </div>
            <div class="sub-sub-node">
                <h4>Penjelasan</h4>
                <p>Tekanan pada zat padat adalah ukuran gaya yang diberikan per unit luas permukaan. Zat padat seperti batu atau logam dapat memberikan tekanan melalui gaya normal atau beratnya. Tekanan ini tidak bergantung pada kedalaman seperti pada zat cair, melainkan pada gaya dan luas kontak.</p>
            </div>
            <div class="sub-sub-node">
                <h4>Contoh</h4>
                <p class="example">Sebuah balok kayu dengan berat 100 N ditempatkan di atas meja dengan luas alas 0,5 m². Tekanan yang diberikan adalah P = 100 / 0,5 = 200 Pa. Jika luas alas lebih kecil (misalnya 0,1 m²), tekanan menjadi lebih besar (1000 Pa), menjelaskan mengapa paku mudah menembus kayu karena luas ujungnya kecil.</p>
            </div>
        </div>
    </div>
    
    <p><strong>Catatan:</strong> Peta konsep ini dapat disimpan sebagai file HTML dan dibuka di browser untuk visualisasi interaktif. Tema sains dengan warna biru untuk zat cair dan hijau untuk zat padat telah diterapkan untuk kemudahan pemahaman. Jika perlu penyesuaian lebih lanjut, edit kode CSS.</p>
</body>
</html>
