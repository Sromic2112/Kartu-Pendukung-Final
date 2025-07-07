<!DOCTYPE html>
<html lang="id">
<head>
  <script type="module">import { injectIntoGlobalHook } from "/@react-refresh"
injectIntoGlobalHook(window);
window.$RefreshReg$ = () => {};
window.$RefreshSig$ = () => (type) => type;</script>

  <script type="module" src="/@vite/client"></script>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dasbor Kartu Pendukung - Final V6</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/compressorjs@1.2.1/dist/compressor.min.js"></script>
    <style>
        :root {
            --hijau-gelap: #004d40;
            --hijau-utama: #00695c;
            --gold-gradient: linear-gradient(145deg, #BF953F, #FCF6BA, #B38728);
            --hijau-gradient: linear-gradient(145deg, #00695c, #004d40);
            --gelap: #212529;
            --abu-terang: #f8f9fa;
            --putih: #ffffff;
            --lebar-kartu: 85.6mm;
            --tinggi-kartu: 53.98mm;
            --sidebar-width: 240px;
        }
        *, *::before, *::after { box-sizing: border-box; }
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0; 
            background-color: var(--abu-terang); 
            display: flex; 
            height: 100vh;
            color: var(--gelap);
            /* Pastikan body adalah flex container untuk layout utama */
            flex-direction: row; /* Atau column, tergantung layout aplikasi Anda */
            overflow: hidden; /* Mencegah scrollbar ganda */
        }
        /* Pastikan elemen yang hidden tidak mengambil ruang */
        .hidden {
            display: none !important;
        }

        .sidebar {
            width: var(--sidebar-width); background-color: var(--gelap); color: var(--putih);
            flex-shrink: 0; display: flex; flex-direction: column; padding: 20px 0;
            box-shadow: 2px 0 10px rgba(0,0,0,0.1);
        }
        .sidebar-header { text-align: center; padding: 0 20px 20px 20px; border-bottom: 1px solid #495057; margin-bottom: 15px; }
        .sidebar-header h3 { margin: 0; font-size: 1.3em; font-weight: 700; }
        .sidebar-menu { list-style: none; margin: 0; padding: 0; }
        .sidebar-menu li a {
            display: flex; align-items: center; gap: 15px; padding: 15px 20px;
            color: var(--putih); text-decoration: none; transition: background-color 0.2s, border-left-color 0.2s;
            border-left: 3px solid transparent;
            font-weight: 600;
        }
        .sidebar-menu li a:hover { background-color: #495057; }
        .sidebar-menu li a.active { background-color: var(--hijau-utama); border-left-color: #f1e05a; }
        .sidebar-menu li a svg { width: 24px; height: 24px; fill: var(--putih); }
        .sidebar-menu li a.active svg { fill: var(--gelap); }
        .main-content {
            flex-grow: 1; padding: 30px; overflow-y: auto;
            background-color: var(--abu-terang);
        }
        .page { display: none; animation: fadeIn 0.5s ease-in-out; }
        .page.active { display: block; }
        @keyframes fadeIn { from { opacity: 0; transform: translateY(10px); } to { opacity: 1; transform: translateY(0); } }
        .container-box {
            background-color: var(--putih); padding: 30px; border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.08);
            margin-bottom: 30px;
            border: 1px solid #e9ecef;
        }
        h2 {
            font-size: 1.8em; color: var(--hijau-gelap); margin: 0 0 25px 0; padding-bottom: 15px;
            border-bottom: 2px solid var(--hijau-utama);
            font-weight: 700;
        }
        .form-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            margin-bottom: 20px;
        }
        .form-group { margin-bottom: 15px; }
        .form-group label {
            display: block; font-weight: 600; margin-bottom: 8px; color: var(--gelap);
            font-size: 0.95em;
        }
        .form-group input[type="text"],
        .form-group input[type="date"],
        .form-group select,
        .form-group textarea { /* Added textarea */
            width: 100%; padding: 12px; border: 1px solid #ced4da; border-radius: 6px;
            font-size: 1em;
            transition: border-color 0.2s, box-shadow 0.2s;
        }
        .form-group input[type="file"] {
            width: 100%; padding: 10px;
            background-color: var(--abu-terang);
            cursor: pointer;
            border: 1px solid #ced4da; /* Ensure file input has border */
            border-radius: 6px;
            font-size: 1em;
        }
        .form-group input:focus,
        .form-group select:focus,
        .form-group textarea:focus { /* Added textarea */
            border-color: var(--hijau-utama);
            box-shadow: 0 0 0 3px rgba(0, 105, 92, 0.2);
            outline: none;
        }
        .form-buttons {
            display: flex; gap: 15px; margin-top: 30px;
            flex-wrap: wrap;
        }
        .btn {
            padding: 12px 24px; border: none; border-radius: 6px; font-size: 1em;
            font-weight: 600; cursor: pointer; transition: all 0.2s ease-in-out;
            text-transform: uppercase; letter-spacing: 0.5px;
        }
        .btn-primary { background-color: var(--hijau-utama); color: var(--putih); }
        .btn-primary:hover { background-color: var(--hijau-gelap); box-shadow: 0 2px 8px rgba(0, 105, 92, 0.4); }
        .btn-secondary { background-color: #6c757d; color: var(--putih); }
        .btn-secondary:hover { background-color: #5a6268; box-shadow: 0 2px 8px rgba(108, 122, 129, 0.4); }
        .btn-warning {
            background-image: var(--gold-gradient); color: var(--gelap); border: 1px solid #b38728;
            box-shadow: 0 2px 8px rgba(179, 135, 40, 0.4);
        }
        .btn-warning:hover { opacity: 0.9; transform: translateY(-1px); }
        .btn-danger { background-color: #dc3545; color: var(--putih); }
        .btn-danger:hover { background-color: #c82333; }
        
        .card-preview-area {
            display: flex; justify-content: center; flex-wrap: wrap; gap: 30px;
            margin-top: 15px;
        }
        .card-container {
            width: var(--lebar-kartu); height: var(--tinggi-kartu);
            border-radius: 3mm; overflow: hidden; position: relative;
            background: var(--hijau-gradient);
            color: var(--putih); flex-shrink: 0;
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
            border: 2px solid;
            border-image-slice: 1;
            border-image-source: var(--gold-gradient);
            display: flex;
        }
        .card-content {
            position: relative; z-index: 1; padding: 3mm; height: 100%;
            display: flex; flex-direction: column; box-sizing: border-box;
            justify-content: space-between;
            width: 100%;
        }
        .title-box {
            text-align: center; margin-bottom: 2mm;
            background: var(--gold-gradient); color: var(--gelap); padding: 1mm;
            border: 1px solid rgba(0,0,0,0.2); border-radius: 1mm;
            font-weight: 700; text-transform: uppercase; font-size: 2.8mm;
            text-shadow: 0px 1px 1px rgba(255, 255, 255, 0.5);
            letter-spacing: 0.3px;
        }
        .front-card-main {
            display: flex; flex-grow: 1; gap: 3mm; align-items: flex-start;
            margin-bottom: 3mm;
        }
        .data-grid {
            flex-grow: 1; display: grid; font-size: 2mm;
            grid-template-columns: 26mm auto 1fr;
            gap: 0.5mm 2mm; align-items: center;
        }
        .data-grid span:nth-child(3n-2) { font-weight: 600; color: #e0e0e0; }
        .data-grid span:nth-child(3n) { color: #f5f5f5; text-shadow: 1px 1px 2px rgba(0,0,0,0.5); }
        .data-grid .alamat-value {
            word-wrap: break-word; /* Allows long words to break and wrap */
            overflow-wrap: break-word; /* Ensures words break at character level if needed */
        }
        .photo-area { text-align: right; }
        .photo-box {
            width: 20mm; height: 25mm;
            background-color: #ccc; border: 1.5px solid;
            border-image-slice: 1; border-image-source: var(--gold-gradient);
            overflow: hidden; margin-bottom: 1.5mm; padding: 1px;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: rgba(0,0,0,0.1);
        }
        .photo-box img {
            width: 100%; height: 100%; -o-object-fit: cover; object-fit: cover;
            display: block;
        }
        .expiry-date {
            font-size: 2mm; font-style: italic; text-align: center;
            color: #e0e0e0;
        }
        .id-box {
            background: var(--gold-gradient); color: var(--gelap);
            padding: 1.5mm 3mm;
            border: 1px solid rgba(0,0,0,0.2); border-radius: 1mm;
            font-weight: 700; text-align: center;
            font-size: 2.8mm; /* Sesuaikan ukuran font jika perlu */
            width: -moz-fit-content;
            width: fit-content; /* Biarkan lebar menyesuaikan konten */
            max-width: 32mm; /* Batasi lebar jika terlalu panjang */
            position: absolute;
            bottom: 3mm;
            left: 5mm;
            height: 5mm;
            padding-left: 2mm;
            padding-right: 2mm;
            display: flex;
            align-items: center;
            justify-content: center;
            white-space: nowrap; /* Mencegah teks wrapping jika tidak ada spasi */
            overflow: hidden; /* Sembunyikan jika overflow */
            text-overflow: ellipsis; /* Tambahkan elipsis jika terpotong */
        }
        .back-card .card-content {
            align-items: center; justify-content: space-between;
            padding-top: 4mm; padding-bottom: 4mm;
        }
        .back-card-header {
            text-align: center;
            line-height: 1.3;
            margin-bottom: 5mm;
        }
        .member-name-box {
            font-weight: 700;
            font-size: 2.8mm;
            text-transform: uppercase;
            color: var(--putih);
        }
        .party-name-box {
            font-weight: 700;
            font-size: 3.0mm;
            text-transform: uppercase;
            color: var(--putih);
        }
        .back-images {
            display: flex;
            gap: 3mm;
            margin-top: -2.5mm;
            margin-bottom: 20mm;
            justify-content: center;
            width: 100%;
        }
        .back-images .photo-box {
            width: 20mm;
            height: 25mm;
            margin-bottom: 0;
            background-color: #ccc;
            border: 1.5px solid;
            border-image-slice: 1;
            border-image-source: var(--gold-gradient);
            overflow: hidden;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: rgba(0,0,0,0.1);
        }
        .back-images .photo-box img { -o-object-fit: contain; object-fit: contain; }
        .tagline-box {
            position: absolute;
            bottom: 3mm;
            left: 5%;
            width: 90%;
            background: var(--gold-gradient);
            color: var(--gelap);
            padding: 2mm;
            border: 1px solid rgba(0,0,0,0.2);
            font-weight: 700;
            text-align: center;
            font-size: 3mm;
            text-transform: uppercase;
            text-shadow: 0px 1px 1px rgba(255, 255, 255, 0.5);
            letter-spacing: 0.3px;
            height: 7mm;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .rekap-filters { display: flex; gap: 10px; margin-bottom: 20px; flex-wrap: wrap; align-items: center; }
        .rekap-filters .btn { padding: 10px 20px; }
        .search-filter {
            display: flex;
            align-items: center;
            gap: 8px;
            margin-left: auto;
            flex-grow: 1;
            justify-content: flex-end;
            max-width: 350px; /* Batasi lebar search filter */
        }
        .search-filter label {
            margin-bottom: 0;
            font-weight: 600;
            color: var(--gelap);
        }
        .search-filter input[type="text"] {
            padding: 8px 12px;
            border: 1px solid #ced4da;
            border-radius: 4px;
            font-size: 0.95em;
            min-width: 150px;
            flex-grow: 1;
        }
        .search-filter input:focus {
            border-color: var(--hijau-utama);
            box-shadow: 0 0 0 3px rgba(0, 105, 92, 0.2);
            outline: none;
        }
        .rekap-table-wrapper {
            max-height: 600px;
            overflow-y: auto; border: 1px solid #dee2e6; border-radius: 8px;
            background-color: var(--putih);
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
        }
        table { width: 100%; border-collapse: collapse; }
        th, td { padding: 12px 15px; text-align: left; border-bottom: 1px solid #e9ecef; }
        th {
            background-color: var(--hijau-gelap);
            color: var(--putih);
            position: sticky; top: 0; z-index: 2;
            font-weight: 700;
        }
        tr:nth-child(even) { background-color: #fdfdfd; }
        tr:hover { background-color: #f0f0f0; }

        /* Styling untuk checkbox di tabel */
        td input[type="checkbox"] {
            width: 18px;
            height: 18px;
            margin-right: 5px;
            vertical-align: middle;
            cursor: pointer;
            accent-color: var(--hijau-utama); /* Warna centang */
        }

        .action-buttons button {
            padding: 8px 12px; margin-right: 5px; color: white; border: none; border-radius: 4px; cursor: pointer;
            font-size: 0.9em; transition: background-color 0.2s ease;
        }
        .edit-btn { background-color: var(--hijau-utama); }
        .edit-btn:hover { background-color: var(--hijau-gelap); }
        .delete-btn { background-color: #6c757d; }
        .delete-btn:hover { background-color: #5a6268; }
        #age-chart-container {
            max-width: 600px;
            margin: 20px auto;
        }
        #category-details-container {
            margin-top: 20px;
        }
        .category-section {
            margin-bottom: 20px;
        }
        .category-section h3 {
            font-size: 1.4em;
            color: var(--hijau-gelap);
            margin-bottom: 10px;
        }
        .category-list {
            list-style: none;
            padding: 0;
        }
        .category-list li {
            padding: 8px;
            border-bottom: 1px solid #e9ecef;
            font-size: 0.95em;
        }
        #print-area { display: none; }
        
        @media print {
            body {
                display: block;
                font-family: 'Arial', sans-serif;
                margin: 0;
                background-color: white;
                color: black;
            }
            .sidebar,
            .main-content > *:not(#print-area) {
                display: none !important;
            }
            #print-area {
                display: block !important;
                width: 100%;
                margin: 0;
                height: auto;
            }
            .duplex-pair {
                display: flex;
                gap: 2mm;
                page-break-inside: avoid;
                width: -moz-fit-content;
                width: fit-content;
            }
            .card-container {
                box-shadow: none;
                border: 2px solid;
                border-image-slice: 1;
                border-image-source: var(--gold-gradient);
                margin: 0;
                transform-origin: top left;
                width: var(--lebar-kartu);
                height: var(--tinggi-kartu);
                -webkit-print-color-adjust: exact;
                print-color-adjust: exact;
            }
            .card-content {
                padding: 3mm;
                font-size: 0.92em;
            }
            .title-box, .id-box, .tagline-box {
                background: var(--gold-gradient);
                color: var(--gelap);
                text-shadow: none;
                font-size: 0.92em;
            }
            @page {
                size: A4 portrait;
                margin: 9.55mm 18.4mm;
            }
            .print-page {
                page-break-after: always;
                display: flex !important;
                flex-wrap: wrap;
                gap: 2mm 2mm; /* Jarak vertikal 2mm, horizontal 2mm */
                justify-content: flex-start;
                align-items: flex-start;
                align-content: flex-start;
                height: auto;
            }
        }

        /* Responsive adjustments for smaller screens */
        @media (max-width: 768px) {
            body {
                flex-direction: column;
            }
            .sidebar {
                width: 100%;
                height: auto;
                padding: 10px 0;
                flex-direction: row;
                justify-content: center;
                align-items: center;
                box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            }
            .sidebar-header {
                display: none; /* Hide header on small screens */
            }
            .sidebar-menu {
                flex-direction: row;
                width: 100%;
                justify-content: center;
                gap: 10px;
            }
            .sidebar-menu li a {
                padding: 10px 15px;
                font-size: 0.9em;
                border-left: none;
                border-bottom: 3px solid transparent;
            }
            .sidebar-menu li a.active {
                border-left: none;
                border-bottom-color: #f1e05a;
            }
            .sidebar-menu li a span {
                display: none; /* Hide text, show only icon on small screens */
            }
            .sidebar-menu li a svg {
                width: 20px;
                height: 20px;
            }
            .main-content {
                padding: 15px;
            }
            .container-box {
                padding: 20px;
            }
            h2 {
                font-size: 1.5em;
                margin-bottom: 20px;
            }
            .form-grid {
                grid-template-columns: 1fr;
            }
            .form-buttons, .rekap-filters {
                flex-direction: column;
                align-items: stretch;
            }
            .search-filter {
                flex-direction: column;
                align-items: stretch;
                margin-left: 0;
                width: 100%;
                max-width: none;
            }
            .rekap-table-wrapper {
                overflow-x: auto; /* Allow horizontal scrolling for table */
            }
            table {
                min-width: 600px; /* Ensure table is wide enough */
            }
            .card-preview-area {
                flex-direction: column;
                align-items: center;
            }
        }

        /* New styles for login form */
        .login-container {
            /* Mengambil seluruh ruang yang tersedia di body */
            position: fixed; /* Menggunakan fixed agar tidak terpengaruh oleh layout flex body */
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: var(--abu-terang);
            z-index: 1000; /* Pastikan di atas elemen lain */
        }
        .login-box {
            background-color: var(--putih);
            padding: 40px;
            border-radius: 10px;
            box-shadow: 0 4px 20px rgba(0,0,0,0.1);
            width: 100%;
            max-width: 400px;
            text-align: center;
        }
        .login-box h2 {
            color: var(--hijau-gelap);
            margin-bottom: 30px;
            border-bottom: none;
            padding-bottom: 0;
        }
        .login-box .form-group {
            margin-bottom: 20px;
            text-align: left;
        }
        .login-box .form-group label {
            font-size: 1em;
            margin-bottom: 10px;
        }
        .login-box .form-group input {
            padding: 12px;
            font-size: 1.1em;
            border-radius: 8px;
            border: 1px solid #ced4da;
        }
        .login-box .btn-primary {
            width: 100%;
            padding: 15px;
            font-size: 1.1em;
            border-radius: 8px;
        }
        .login-error {
            color: #dc3545;
            margin-top: 15px;
            font-weight: 600;
        }
    </style>
</head>
<body>
    <!-- Login Form -->
    <div class="login-container" id="login-page">
        <div class="login-box">
            <h2>Login Dasbor KPS</h2>
            <form id="login-form">
                <div class="form-group">
                    <label for="username">Username</label>
                    <input type="text" id="username" required>
                </div>
                <div class="form-group">
                    <label for="password">Password</label>
                    <input type="password" id="password" required>
                </div>
                <button type="submit" class="btn btn-primary">Login</button>
                <p id="login-error-message" class="login-error hidden">Username atau password salah.</p>
            </form>
        </div>
    </div>

    <nav class="sidebar hidden" aria-label="Navigasi utama" id="app-sidebar">
        <div class="sidebar-header"><h3>Dasbor KPS</h3></div>
        <ul class="sidebar-menu">
            <li><a href="#input" class="nav-link active" aria-current="page">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"><path d="M19 3H5c-1.11 0-2 .9-2 2v14c0 1.1.89 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zm-2 10h-4v4h-2v-4H7v-2h4V7h2v4h4v2z"/></svg>
                <span>Input Pendukung</span>
            </a></li>
            <li><a href="#rekap" class="nav-link">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"><path d="M3 13h8V3H3v10zm0 8h8v-6H3v6zm10 0h8v-6h-8v6zm0-18v6h8V3h-8z"/></svg>
                <span>Rekap Data</span>
            </a></li>
            <li><a href="#pengaturan" class="nav-link">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"><path d="M19.43 12.98c.04-.32.07-.64.07-.98s-.03-.66-.07-.98l2.11-1.65c.19-.15.24-.42.12-.64l-2-3.46c-.12-.22-.39-.30-.61-.22l-2.49 1c-.52-.4-1.08-.73-1.69-.98l-.38-2.65C14.46 2.18 14.25 2 14 2h-4c-.25 0-.46.18-.49.42l-.38 2.65c-.61.25-1.17-.59-1.69-.98l-2.49-1c-.23-.09-.49 0-.61.22l-2 3.46c-.13.22-.07.49.12.64l2.11 1.65c-.04.32-.07.65-.07.98s.03.66.07.98l-2.11 1.65c-.19.15-.24.42.12.64l2 3.46c.12.22.39.30.61.22l2.49-1c.52.4 1.08.73 1.69.98l.38 2.65c.03.24.24.42.49.42h4c.25 0 .46-.18.49-.42l.38-2.65c.61-.25 1.17-.59 1.69-.98l2.49 1c.23.09.49 0 .61.22l2-3.46c.12-.22.07-.49-.12-.64l-2.11-1.65zM12 15.5c-1.93 0-3.5-1.57-3.5-3.5s1.57-3.5 3.5-3.5 3.5 1.57 3.5 3.5-1.57 3.5-3.5 3.5z"/></svg>
                <span>Pengaturan Kartu</span>
            </a></li>
            <li><a href="#" id="logout-link" class="nav-link">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"><path d="M17 7l-1.41 1.41L18.17 11H8v2h10.17l-2.58 2.58L17 17l5-5zM4 5h8V3H4c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h8v-2H4V5z"/></svg>
                <span>Logout</span>
            </a></li>
        </ul>
    </nav>
    <main class="main-content hidden" id="app-main-content">
        <div id="input" class="page active">
            <div class="container-box">
                <h2 id="form-title">Tambah Pendukung Baru</h2>
                <form id="pendukung-form" aria-label="Formulir input data pendukung">
                    <div class="form-grid">
                        <input type="hidden" id="edit-id">
                        <div class="form-group"><label for="nama">Nama Lengkap</label><input type="text" id="nama" required aria-required="true"></div>
                        <div class="form-group"><label for="nik">NIK (16 Digit)</label><input type="text" id="nik" pattern="\d{16}" required title="NIK harus terdiri dari 16 digit angka." aria-required="true" maxlength="16"></div>
                        <div class="form-group"><label for="jenis_kelamin">Jenis Kelamin</label><select id="jenis_kelamin" required aria-required="true"><option value="">Pilih...</option><option>Laki-laki</option><option>Perempuan</option></select></div>
                        <div class="form-group"><label for="tempat_lahir">Tempat Lahir</label><input type="text" id="tempat_lahir" required aria-required="true"></div>
                        <div class="form-group"><label for="tanggal_lahir">Tanggal Lahir</label><input type="date" id="tanggal_lahir" required aria-required="true"></div>
                        <div class="form-group"><label for="alamat">Alamat</label><textarea id="alamat" rows="3" required aria-required="true"></textarea></div>
                        <div class="form-group"><label for="foto_pendukung_upload">Foto Pendukung (2x2.5 cm)</label><input type="file" id="foto_pendukung_upload" accept="image/*" aria-describedby="foto-help"></div>
                        <small id="foto-help" class="form-text text-muted">Unggah foto berukuran 2x2.5 cm untuk kartu pendukung.</small>
                    </div>
                    <div class="form-buttons">
                        <button type="submit" id="submit-btn" class="btn btn-primary" aria-label="Simpan data pendukung">Simpan</button>
                        <button type="button" id="update-btn" class="btn btn-warning hidden" aria-label="Perbarui data pendukung">Update</button>
                        <button type="button" id="cancel-btn" class="btn btn-secondary" aria-label="Batalkan pengisian formulir">Batal</button>
                    </div>
                </form>
            </div>
            <div class="container-box">
                <h2>Pratinjau Kartu</h2>
                <div class="card-preview-area">
                    <div id="review-front-card" class="card-container front-card"><p style="text-align: center; width: 100%; padding: 20px; color: var(--gelap);">Pratinjau Kartu Depan</p></div>
                    <div id="review-back-card" class="card-container back-card"><p style="text-align: center; width: 100%; padding: 20px; color: var(--gelap);">Pratinjau Kartu Belakang</p></div>
                </div>
            </div>
        </div>

        <div id="rekap" class="page">
            <div class="container-box">
                <h2>Rekapitulasi Data Pendukung</h2>
                <div class="rekap-filters">
                    <button class="btn btn-primary filter-btn" data-filter="semua" aria-label="Tampilkan semua data pendukung">Semua</button>
                    <button class="btn btn-secondary filter-btn" data-filter="Pemula" aria-label="Tampilkan pendukung usia pemula">Pemula (17-35)</button>
                    <button class="btn btn-secondary filter-btn" data-filter="Dewasa" aria-label="Tampilkan pendukung usia dewasa">Dewasa (36-60)</button>
                    <button class="btn btn-secondary filter-btn" data-filter="Senior" aria-label="Tampilkan pendukung usia senior">Senior (61-95)</button>
                    <div class="search-filter">
                        <label for="search-input">Cari:</label>
                        <input type="text" id="search-input" placeholder="NIK, ID, Nama, Alamat..." aria-label="Cari berdasarkan NIK, ID, nama, atau alamat">
                    </div>
                </div>
                <div class="form-buttons" style="margin-bottom: 20px;">
                    <button id="exportCSVBtn" class="btn btn-primary" aria-label="Ekspor data pendukung ke CSV">Ekspor ke CSV</button>
                    <button id="downloadCardsBtn" class="btn btn-warning" aria-label="Download kartu pendukung yang dipilih">Download Kartu</button>
                    <button id="printFrontBtn" class="btn btn-secondary" aria-label="Cetak kartu depan">Cetak Depan Saja</button>
                    <button id="printBackBtn" class="btn btn-secondary" aria-label="Cetak kartu belakang">Cetak Belakang Saja</button>
                    <button id="printDuplexBtn" class="btn btn-primary" aria-label="Cetak kartu depan dan belakang">Cetak Depan-Belakang</button>
                </div>
                <div class="rekap-table-wrapper">
                    <table aria-label="Tabel rekapitulasi data pendukung">
                        <thead>
                            <tr>
                                <th><input type="checkbox" id="select-all-checkbox" title="Pilih Semua" aria-label="Pilih semua kartu untuk dicetak"></th>
                                <th>No</th>
                                <th>ID Pendukung</th>
                                <th>Nama</th>
                                <th>NIK</th> <th>Alamat</th>
                                <th>Usia</th>
                                <th>Kategori</th>
                                <th>Aksi</th>
                            </tr>
                        </thead>
                        <tbody id="rekap-table-body">
                            <tr>
                                <td colspan="9" style="text-align: center;">Memuat data...</td> </tr>
                        </tbody>
                    </table>
                </div>
                <div id="age-chart-container" class="container-box">
                    <h2>Distribusi Kategori Usia Pendukung</h2>
                    <canvas id="ageChart" aria-label="Diagram batang distribusi kategori usia pendukung"></canvas>
                </div>
                <div id="category-details-container" class="container-box">
                    <h2>Detail Pendukung per Kategori Usia</h2>
                    <div id="category-details"></div>
                </div>
            </div>
        </div>

        <div id="pengaturan" class="page">
            <div class="container-box">
                <h2>Pengaturan Kartu</h2>
                <form id="settings-form" aria-label="Formulir pengaturan kartu">
                    <div class="form-grid">
                        <div class="form-group"><label for="setting_nama_anggota">Nama Anggota DPRD</label><input type="text" id="setting_nama_anggota" aria-required="true"></div>
                        <div class="form-group"><label for="setting_dprd_photo_upload">Foto Anggota (2x2.5 cm)</label><input type="file" id="setting_dprd_photo_upload" accept="image/*" aria-describedby="dprd-photo-help"></div>
                        <div class="form-group"><label for="setting_pkb_logo_upload">Logo Partai (2x2.5 cm)</label><input type="file" id="setting_pkb_logo_upload" accept="image/*" aria-describedby="pkb-logo-help"></div>
                        <div class="form-group">
                            <label for="setting_card_title">Judul Kartu Depan</label>
                            <input type="text" id="setting_card_title" placeholder="Contoh: KARTU LOYALIS PENDUKUNG SETIA" aria-required="true">
                        </div>
                        <div class="form-group">
                            <label for="next-id-counter-display">Nomor ID Pendukung Berikutnya</label>
                            <div style="display: flex; gap: 10px; align-items: center;">
                                <input type="text" id="next-id-counter-display" readonly aria-readonly="true" style="background-color: #e9ecef;">
                                <button type="button" id="reset-next-id-btn" class="btn btn-danger" aria-label="Reset nomor ID pendukung berikutnya">Reset ID</button>
                            </div>
                        </div>
                        <small id="dprd-photo-help" class="form-text text-muted">Unggah foto anggota DPRD berukuran 2x2.5 cm.</small>
                        <small id="pkb-logo-help" class="form-text text-muted">Unggah logo partai berukuran 2x2.5 cm.</small>
                    </div>
                    <div class="form-buttons">
                        <button id="save-settings-btn" class="btn btn-primary" aria-label="Simpan pengaturan kartu">Simpan Pengaturan</button>
                    </div>
                </form>
            </div>
        </div>
    </main>

    <div id="templates" style="display: none;">
        <div class="card-container front-card" id="frontCardTemplate">
            <div class="card-content">
                <div class="title-box">KARTU LOYALIS PENDUKUNG SETIA</div>
                <div class="front-card-main">
                    <div class="data-grid">
                        <span>Nama</span><span>:</span><span data-field="nama"></span>
                        <span>NIK</span><span>:</span><span data-field="nik"></span>
                        <span>Jenis Kelamin</span><span>:</span><span data-field="jenis_kelamin"></span>
                        <span>Tempat/Tgl Lahir</span><span>:</span><span data-field="ttl"></span>
                        <span>Alamat</span><span>:</span><span data-field="alamat" class="alamat-value"></span>
                        <span>Usia</span><span>:</span><span data-field="usia"></span>
                    </div>
                    <div class="photo-area">
                        <div class="photo-box"><img data-field="foto" src="" alt="Foto Pendukung"></div>
                        <div class="expiry-date">Berlaku Sejak: <span data-field="berlaku"></span></div>
                    </div>
                </div>
                <div class="id-box"><span data-field="no_pendukung"></span></div>
            </div>
        </div>
        <div class="card-container back-card" id="backCardTemplate">
            <div class="card-content">
                <div class="back-card-header">
                    <div class="party-name-box">PARTAI KEBANGKITAN BANGSA</div>
                    <div class="member-name-box" data-field="namaAnggotaDPRD"></div>
                </div>
                <div class="back-images">
                    <div class="image-item">
                        <div class="photo-box"><img data-field="dprdPhoto" src="" alt="Foto Anggota DPRD"></div>
                    </div>
                    <div class="image-item">
                        <div class="photo-box"><img data-field="pkbLogo" src="" alt="Logo PKB"></div>
                    </div>
                </div>
                <div class="tagline-box">BERSAMA MENUJU KEMENANGAN</div>
            </div>
        </div>
    </div>
    <div id="print-area"></div>

    <script>
    document.addEventListener('DOMContentLoaded', () => {
        // --- APPLICATION STATE & CONFIGURATION ---
        const appState = {
            db: {
                pendukung: [],
                settings: {
                    dprdPhotoUrl: null, // Akan diisi placeholder jika tidak ada yang diupload
                    pkbLogoUrl: null,
                    namaAnggotaDPRD: 'Nama Anggota DPRD',
                    cardTitle: 'KARTU LOYALIS PENDUKUNG SETIA',
                    nextIdCounter: 1
                }
            },
            constants: {
                MAX_SUPPORTERS: 4000,
                MAX_PRINT_PER_BATCH: 10, // Maksimal 5 pasang kartu untuk duplex, atau 10 kartu tunggal
                PLACEHOLDER_PHOTO_URL: 'data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="%23ccc"><path d="M12 12c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm0 2c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4z"/></svg>', // Placeholder SVG Base64
                PLACEHOLDER_LOGO_URL: 'data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="%23ccc"><path d="M12 2L4 5v6c0 5.55 3.84 10.74 9 12 3.82-1.07 6.42-3.83 7.42-7.25C20.66 11.23 20 8.07 20 5l-8-3z"/></svg>' // Placeholder SVG Base64
            },
            currentFilter: 'semua',
            currentSearchTerm: ''
        };

        // --- DOM ELEMENTS CACHING ---
        const domElements = {
            loginPage: document.getElementById('login-page'),
            loginForm: document.getElementById('login-form'),
            usernameInput: document.getElementById('username'),
            passwordInput: document.getElementById('password'),
            loginErrorMessage: document.getElementById('login-error-message'),
            appSidebar: document.getElementById('app-sidebar'),
            appMainContent: document.getElementById('app-main-content'),
            logoutLink: document.getElementById('logout-link'),

            navLinks: document.querySelectorAll('.nav-link'),
            pages: document.querySelectorAll('.page'),
            pendukungForm: document.getElementById('pendukung-form'),
            formTitle: document.getElementById('form-title'),
            // Input fields for pendukung form
            namaInput: document.getElementById('nama'),
            nikInput: document.getElementById('nik'),
            jenisKelaminSelect: document.getElementById('jenis_kelamin'),
            tempatLahirInput: document.getElementById('tempat_lahir'),
            tanggalLahirInput: document.getElementById('tanggal_lahir'),
            alamatInput: document.getElementById('alamat'),
            fotoPendukungUpload: document.getElementById('foto_pendukung_upload'),

            recapTableBody: document.getElementById('rekap-table-body'),
            editIdInput: document.getElementById('edit-id'),
            submitBtn: document.getElementById('submit-btn'),
            updateBtn: document.getElementById('update-btn'),
            cancelBtn: document.getElementById('cancel-btn'),
            reviewFrontContainer: document.getElementById('review-front-card'),
            reviewBackContainer: document.getElementById('review-back-card'),
            selectAllCheckbox: document.getElementById('select-all-checkbox'),
            printFrontBtn: document.getElementById('printFrontBtn'),
            printBackBtn: document.getElementById('printBackBtn'),
            printDuplexBtn: document.getElementById('printDuplexBtn'),
            downloadCardsBtn: document.getElementById('downloadCardsBtn'),
            saveSettingsBtn: document.getElementById('save-settings-btn'),
            settingNamaAnggotaInput: document.getElementById('setting_nama_anggota'),
            settingDprdPhotoUpload: document.getElementById('setting_dprd_photo_upload'),
            settingPkbLogoUpload: document.getElementById('setting_pkb_logo_upload'),
            settingCardTitleInput: document.getElementById('setting_card_title'),
            searchInput: document.getElementById('search-input'),
            exportCSVBtn: document.getElementById('exportCSVBtn'),
            categoryDetailsContainer: document.getElementById('category-details'),
            nextIdCounterDisplay: document.getElementById('next-id-counter-display'),
            resetNextIdBtn: document.getElementById('reset-next-id-btn')
        };

        // --- UTILITY FUNCTIONS ---

        const calculateAge = (dobString) => {
            if (!dobString) return 0;
            const today = new Date();
            const dob = new Date(dobString);
            if (isNaN(dob.getTime()) || dob > today) return 0;
            let age = today.getFullYear() - dob.getFullYear();
            const monthDiff = today.getMonth() - dob.getMonth();
            if (monthDiff < 0 || (monthDiff === 0 && today.getDate() < dob.getDate())) {
                age--;
            }
            return Math.max(0, age);
        };

        const getAgeCategory = (age) => {
            if (age >= 17 && age <= 35) return 'Pemula';
            if (age >= 36 && age <= 60) return 'Dewasa';
            if (age >= 61 && age <= 95) return 'Senior';
            return 'N/A';
        };

        const formatDate = (dateString) => {
            if (!dateString) return '';
            try {
                const date = new Date(dateString);
                const options = { day: '2-digit', month: 'long', year: 'numeric' };
                return date.toLocaleDateString('id-ID', options).replace(/\./g, '');
            } catch (error) {
                console.error("Error formatting date:", error);
                return 'Tanggal tidak valid';
            }
        };

        const compressImage = (file) => {
            return new Promise((resolve, reject) => {
                if (!file) return resolve(null);
                new Compressor(file, {
                    quality: 0.6,
                    maxWidth: 200,
                    maxHeight: 250,
                    mimeType: 'image/jpeg',
                    success(result) {
                        const reader = new FileReader();
                        reader.onload = () => resolve(reader.result);
                        reader.onerror = (e) => reject(e);
                        reader.readAsDataURL(result);
                    },
                    error(err) {
                        reject(err);
                    }
                });
            });
        };

        const validateNIK = (nik) => {
            const nikRegex = /^\d{16}$/;
            return nikRegex.test(nik);
        };

        // --- DATA MANAGEMENT FUNCTIONS ---

        const saveAppStateToLocalStorage = () => {
            try {
                localStorage.setItem('KPS_DB_V6', JSON.stringify(appState.db));
            } catch (e) {
                console.error("Gagal menyimpan ke localStorage:", e);
                alert("Terjadi kesalahan saat menyimpan data. Kapasitas penyimpanan mungkin penuh atau terjadi error lain.");
            }
        };

        const loadAppStateFromLocalStorage = () => {
            const storedDB = localStorage.getItem('KPS_DB_V6');
            if (storedDB) {
                appState.db = JSON.parse(storedDB);
                if (!appState.db.pendukung) appState.db.pendukung = [];
                if (!appState.db.settings) appState.db.settings = {};

                // Inisialisasi placeholder jika belum ada di settings
                if (!appState.db.settings.dprdPhotoUrl) appState.db.settings.dprdPhotoUrl = appState.constants.PLACEHOLDER_PHOTO_URL;
                if (!appState.db.settings.pkbLogoUrl) appState.db.settings.pkbLogoUrl = appState.constants.PLACEHOLDER_LOGO_URL;
                if (!appState.db.settings.namaAnggotaDPRD) appState.db.settings.namaAnggotaDPRD = 'Nama Anggota DPRD';
                if (!appState.db.settings.cardTitle) appState.db.settings.cardTitle = 'KARTU LOYALIS PENDUKUNG SETIA';

                // Muat nextIdCounter atau hitung jika tidak ada
                if (appState.db.settings.nextIdCounter === undefined || appState.db.settings.nextIdCounter < 1) {
                    if (appState.db.pendukung.length > 0) {
                        const maxIdNum = appState.db.pendukung.reduce((max, p) => {
                            const match = p.no_pendukung ? p.no_pendukung.match(/PKB-LOYAL-(\d+)/) : null;
                            if (match && match[1]) {
                                return Math.max(max, parseInt(match[1], 10));
                            }
                            return max;
                        }, 0);
                        appState.db.settings.nextIdCounter = maxIdNum + 1;
                    } else {
                        appState.db.settings.nextIdCounter = 1;
                    }
                }
            } else {
                appState.db = {
                    pendukung: [],
                    settings: {
                        dprdPhotoUrl: appState.constants.PLACEHOLDER_PHOTO_URL,
                        pkbLogoUrl: appState.constants.PLACEHOLDER_LOGO_URL,
                        namaAnggotaDPRD: 'Nama Anggota DPRD',
                        cardTitle: 'KARTU LOYALIS PENDUKUNG SETIA',
                        nextIdCounter: 1
                    }
                };
                // Tambahkan beberapa data contoh untuk testing
                appState.db.pendukung.push(
                    { id: 1, no_pendukung: "PKB-LOYAL-0001", nama: "Budi Santoso", nik: "3171010101800001", jenis_kelamin: "Laki-laki", tempat_lahir: "Surabaya", tanggal_lahir: "1990-05-15", alamat: "Jl. Merdeka No. 123, Surabaya", usia: calculateAge("1990-05-15"), fotoUrl: null },
                    { id: 2, no_pendukung: "PKB-LOYAL-0002", nama: "Siti Aisyah", nik: "3171010101600003", jenis_kelamin: "Perempuan", tempat_lahir: "Bandung", tanggal_lahir: "1960-07-10", alamat: "Jl. Asia Afrika No. 10, Bandung", usia: calculateAge("1960-07-10"), fotoUrl: null },
                    { id: 3, no_pendukung: "PKB-LOYAL-0003", nama: "Joko Widodo", nik: "3171010101400004", jenis_kelamin: "Laki-laki", tempat_lahir: "Yogyakarta", tanggal_lahir: "1940-12-25", alamat: "Jl. Malioboro No. 22, Yogyakarta", usia: calculateAge("1940-12-25"), fotoUrl: null }
                );
                appState.db.settings.nextIdCounter = 4;
                saveAppStateToLocalStorage();
            }
            updateNextIdDisplay();
        };

        const updateNextIdDisplay = () => {
            if (domElements.nextIdCounterDisplay) {
                domElements.nextIdCounterDisplay.value = `PKB-LOYAL-${String(appState.db.settings.nextIdCounter).padStart(4, '0')}`;
            }
        };

        // --- CARD RENDERING FUNCTIONS ---

        const createCardElement = (templateId, data) => {
            const template = document.getElementById(templateId);
            if (!template) {
                console.error(`Template dengan ID "${templateId}" tidak ditemukan.`);
                return null;
            }
            const cardClone = template.cloneNode(true);
            cardClone.removeAttribute('id');
            cardClone.style.display = '';

            const renderData = {
                ...data,
                ...appState.db.settings,
                ttl: `${data.tempat_lahir || ''}, ${formatDate(data.tanggal_lahir)}`,
                usia: `${data.usia !== undefined && data.usia !== null ? data.usia : '-'} Tahun`,
                alamat: data.alamat || '',
                berlaku: formatDate(new Date().toISOString().split('T')[0]), // Format tanggal hari ini
                foto: data.fotoUrl || appState.constants.PLACEHOLDER_PHOTO_URL,
                dprdPhoto: appState.db.settings.dprdPhotoUrl || appState.constants.PLACEHOLDER_PHOTO_URL,
                pkbLogo: appState.db.settings.pkbLogoUrl || appState.constants.PLACEHOLDER_LOGO_URL,
                namaAnggotaDPRD: appState.db.settings.namaAnggotaDPRD || 'Nama Anggota',
                cardTitle: appState.db.settings.cardTitle || 'KARTU LOYALIS PENDUKUNG SETIA'
            };

            cardClone.querySelectorAll('[data-field]').forEach(el => {
                const fieldName = el.dataset.field;
                if (renderData[fieldName] !== undefined && renderData[fieldName] !== null) {
                    if (el.tagName === 'IMG') {
                        el.src = renderData[fieldName];
                        el.alt = `Gambar ${fieldName}`;
                    } else {
                        el.textContent = renderData[fieldName];
                    }
                } else {
                    if (el.tagName === 'IMG') el.src = appState.constants.PLACEHOLDER_PHOTO_URL;
                    else el.textContent = '-';
                }
            });

            const titleBox = cardClone.querySelector('.title-box');
            if (titleBox && renderData['cardTitle']) {
                titleBox.textContent = renderData['cardTitle'];
            }
            return cardClone;
        };

        const updateCardPreview = (pendukungData) => {
            domElements.reviewFrontContainer.innerHTML = '';
            domElements.reviewBackContainer.innerHTML = '';

            const frontCardElement = createCardElement('frontCardTemplate', pendukungData);
            if (frontCardElement) {
                domElements.reviewFrontContainer.appendChild(frontCardElement);
            } else {
                domElements.reviewFrontContainer.innerHTML = `<p style="text-align: center; width: 100%; padding: 20px; color: var(--gelap);">Pratinjau Kartu Depan Gagal Dimuat.</p>`;
            }

            const backCardElement = createCardElement('backCardTemplate', pendukungData);
            if (backCardElement) {
                domElements.reviewBackContainer.appendChild(backCardElement);
            } else {
                domElements.reviewBackContainer.innerHTML = `<p style="text-align: center; width: 100%; padding: 20px; color: var(--gelap);">Pratinjau Kartu Belakang Gagal Dimuat.</p>`;
            }
        };

        // --- TABLE RENDERING FUNCTIONS ---

        let ageChartInstance; // Deklarasi di luar fungsi agar bisa dihancurkan

        const renderRecapTable = () => {
            domElements.recapTableBody.innerHTML = '';

            const filteredPendukung = appState.db.pendukung.filter(pendukung => {
                const matchesCategory = (appState.currentFilter === 'semua') || (getAgeCategory(pendukung.usia) === appState.currentFilter);
                if (!matchesCategory) return false;

                if (appState.currentSearchTerm) {
                    const lowerSearchTerm = appState.currentSearchTerm.toLowerCase();
                    const matchesSearch =
                        (pendukung.nik && pendukung.nik.toLowerCase().includes(lowerSearchTerm)) ||
                        (pendukung.no_pendukung && pendukung.no_pendukung.toLowerCase().includes(lowerSearchTerm)) ||
                        (pendukung.nama && pendukung.nama.toLowerCase().includes(lowerSearchTerm)) ||
                        (pendukung.alamat && pendukung.alamat.toLowerCase().includes(lowerSearchTerm));
                    return matchesSearch;
                }
                return true;
            });

            if (filteredPendukung.length === 0) {
                domElements.recapTableBody.innerHTML = '<tr><td colspan="9" style="text-align: center;">Tidak ada data ditemukan.</td></tr>'; // colspan adjusted
                domElements.selectAllCheckbox.checked = false;
                domElements.selectAllCheckbox.disabled = true;
                renderAgeChart(); // Tetap render chart meskipun kosong
                renderCategoryDetails();
                return;
            }

            domElements.selectAllCheckbox.disabled = false; // Enable select all if there's data

            filteredPendukung.forEach((pendukung, displayIndex) => {
                const row = domElements.recapTableBody.insertRow();
                row.innerHTML = `
                    <td><input type="checkbox" class="select-card-checkbox" value="${pendukung.id}" aria-label="Pilih kartu ${pendukung.nama}"></td>
                    <td>${displayIndex + 1}</td>
                    <td>${pendukung.no_pendukung || '-'}</td>
                    <td>${pendukung.nama || '-'}</td>
                    <td>${pendukung.nik || '-'}</td> <td>${pendukung.alamat || '-'}</td>
                    <td>${pendukung.usia !== undefined && pendukung.usia !== null ? pendukung.usia : '-'}</td>
                    <td>${getAgeCategory(pendukung.usia)}</td>
                    <td class="action-buttons">
                        <button class="edit-btn" data-id="${pendukung.id}" title="Edit" aria-label="Edit data ${pendukung.nama}">Edit</button>
                        <button class="delete-btn" data-id="${pendukung.id}" title="Hapus" aria-label="Hapus data ${pendukung.nama}">Hapus</button>
                    </td>`;
            });

            renderAgeChart();
            renderCategoryDetails();
        };

        const renderCategoryDetails = () => {
            const categories = ['Pemula', 'Dewasa', 'Senior', 'N/A'];
            domElements.categoryDetailsContainer.innerHTML = '';

            categories.forEach(category => {
                const pendukungInCategory = appState.db.pendukung.filter(pendukung => getAgeCategory(pendukung.usia) === category);

                if (pendukungInCategory.length > 0) {
                    const section = document.createElement('div');
                    section.className = 'category-section';
                    section.innerHTML = `<h3>${category} (${pendukungInCategory.length} Pendukung)</h3>`;

                    const list = document.createElement('ul');
                    list.className = 'category-list';
                    pendukungInCategory.forEach(pendukung => {
                        const li = document.createElement('li');
                        li.innerHTML = `<strong>${pendukung.nama}</strong> (ID: ${pendukung.no_pendukung}, NIK: ${pendukung.nik}, Usia: ${pendukung.usia})`;
                        list.appendChild(li);
                    });
                    section.appendChild(list);
                    domElements.categoryDetailsContainer.appendChild(section);
                }
            });

            if (!domElements.categoryDetailsContainer.innerHTML) {
                domElements.categoryDetailsContainer.innerHTML = '<p>Tidak ada data untuk ditampilkan.</p>';
            }
        };

        const renderAgeChart = () => {
            const ctx = document.getElementById('ageChart')?.getContext('2d');
            if (!ctx) return;

            const ageCategories = { Pemula: 0, Dewasa: 0, Senior: 0, 'N/A': 0 };
            appState.db.pendukung.forEach(pendukung => {
                const category = getAgeCategory(pendukung.usia);
                ageCategories[category]++;
            });

            if (ageChartInstance) {
                ageChartInstance.destroy();
            }

            ageChartInstance = new Chart(ctx, {
                type: 'bar',
                data: {
                    labels: ['Pemula (17-35)', 'Dewasa (36-60)', 'Senior (61-95)', 'N/A'],
                    datasets: [{
                        label: 'Jumlah Pendukung',
                        data: [
                            ageCategories.Pemula,
                            ageCategories.Dewasa,
                            ageCategories.Senior,
                            ageCategories['N/A']
                        ],
                        backgroundColor: [
                            'rgba(0, 105, 92, 0.8)',
                            'rgba(179, 135, 40, 0.8)',
                            'rgba(108, 117, 125, 0.8)',
                            'rgba(220, 53, 69, 0.8)'
                        ],
                        borderColor: [
                            'rgba(0, 105, 92, 1)',
                            'rgba(179, 135, 40, 1)',
                            'rgba(108, 117, 125, 1)',
                            'rgba(220, 53, 69, 1)'
                        ],
                        borderWidth: 1
                    }]
                },
                options: {
                    scales: {
                        y: {
                            beginAtZero: true,
                            title: { display: true, text: 'Jumlah Pendukung' },
                            ticks: { precision: 0 } // Hanya tampilkan bilangan bulat
                        },
                        x: {
                            title: { display: true, text: 'Kategori Usia' }
                        }
                    },
                    plugins: {
                        legend: { display: false },
                        title: { display: true, text: 'Distribusi Kategori Usia Pendukung' }
                    }
                }
            });
        };

        // --- FORM HANDLING FUNCTIONS ---

        const resetPendukungForm = () => {
            domElements.pendukungForm.reset();
            domElements.editIdInput.value = '';
            domElements.formTitle.textContent = 'Tambah Pendukung Baru';
            domElements.submitBtn.classList.remove('hidden');
            domElements.updateBtn.classList.add('hidden');
            domElements.fotoPendukungUpload.value = ''; // Clear file input
            updateCardPreview({}); // Clear card preview
            domElements.pendukungForm.dataset.currentPreviewData = ''; // Clear preview data
        };

        const handlePendukungFormSubmit = async (e) => {
            e.preventDefault();

            if (!domElements.pendukungForm.checkValidity()) {
                domElements.pendukungForm.reportValidity();
                return;
            }

            const isEditing = domElements.editIdInput.value !== '';
            if (!isEditing && appState.db.pendukung.length >= appState.constants.MAX_SUPPORTERS) {
                alert(`Batas maksimal ${appState.constants.MAX_SUPPORTERS} pendukung telah tercapai.`);
                return;
            }

            const pendukungData = {
                nama: domElements.namaInput.value.trim(),
                nik: domElements.nikInput.value.trim(),
                jenis_kelamin: domElements.jenisKelaminSelect.value,
                tempat_lahir: domElements.tempatLahirInput.value.trim(),
                tanggal_lahir: domElements.tanggalLahirInput.value,
                alamat: domElements.alamatInput.value.trim(),
            };
            pendukungData.usia = calculateAge(pendukungData.tanggal_lahir);

            if (!validateNIK(pendukungData.nik)) {
                alert('Format NIK tidak valid. NIK harus terdiri dari 16 digit angka.');
                domElements.nikInput.focus();
                return;
            }

            const existingId = isEditing ? parseInt(domElements.editIdInput.value, 10) : null;
            const nikExisting = appState.db.pendukung.find(p => p.nik === pendukungData.nik && (!isEditing || p.id !== existingId));
            if (nikExisting) {
                alert(`Error: NIK "${pendukungData.nik}" sudah terdaftar untuk pendukung lain.`);
                domElements.nikInput.focus();
                return;
            }

            let fotoUrl = null;
            const fotoFile = domElements.fotoPendukungUpload.files[0];

            if (fotoFile) {
                try {
                    fotoUrl = await compressImage(fotoFile);
                } catch (err) {
                    alert('Gagal mengompresi foto pendukung. Coba lagi.');
                    console.error('Compression error:', err);
                    return;
                }
            } else if (isEditing) {
                const existingPendukung = appState.db.pendukung.find(p => p.id === existingId);
                if (existingPendukung) {
                    fotoUrl = existingPendukung.fotoUrl; // Gunakan foto lama jika tidak ada upload baru
                }
            }
            pendukungData.fotoUrl = fotoUrl;


            if (!isEditing) {
                let newPendukungIdCounter = appState.db.settings.nextIdCounter;
                let newPendukungNo = `PKB-LOYAL-${String(newPendukungIdCounter).padStart(4, '0')}`;

                // Loop untuk mencari nomor ID berikutnya yang belum terpakai
                while (appState.db.pendukung.some(p => p.no_pendukung === newPendukungNo)) {
                    newPendukungIdCounter++;
                    newPendukungNo = `PKB-LOYAL-${String(newPendukungIdCounter).padStart(4, '0')}`;
                }
                appState.db.settings.nextIdCounter = newPendukungIdCounter + 1;

                pendukungData.id = appState.db.pendukung.length > 0 ? Math.max(...appState.db.pendukung.map(p => p.id || 0)) + 1 : 1;
                pendukungData.no_pendukung = newPendukungNo;
                
                appState.db.pendukung.push(pendukungData);
                alert('Pendukung baru berhasil ditambahkan!');
            } else {
                const indexToUpdate = appState.db.pendukung.findIndex(p => p.id === existingId);
                if (indexToUpdate === -1) {
                    alert('Kesalahan: Data pendukung yang diedit tidak ditemukan.');
                    return;
                }
                pendukungData.id = existingId;
                pendukungData.no_pendukung = appState.db.pendukung[indexToUpdate].no_pendukung;
                
                appState.db.pendukung[indexToUpdate] = pendukungData;
                alert('Data pendukung berhasil diperbarui!');
            }

            saveAppStateToLocalStorage();
            renderRecapTable();
            resetPendukungForm();
            updateNextIdDisplay(); // Update display after new ID is assigned
        };

        const exportPendukungToCSV = () => {
            const headers = ['ID Internal', 'No Pendukung', 'Nama', 'NIK', 'Jenis Kelamin', 'Tempat Lahir', 'Tanggal Lahir', 'Alamat', 'Usia'];
            const csvRows = [headers.map(h => `"${h.replace(/"/g, '""')}"`).join(',')]; // Ensure headers are quoted

            appState.db.pendukung.forEach(pendukung => {
                const row = [
                    pendukung.id,
                    `"${(pendukung.no_pendukung || '-').replace(/"/g, '""')}"`,
                    `"${(pendukung.nama || '-').replace(/"/g, '""')}"`,
                    `"${(pendukung.nik || '-').replace(/"/g, '""')}"`,
                    `"${(pendukung.jenis_kelamin || '-').replace(/"/g, '""')}"`,
                    `"${(pendukung.tempat_lahir || '-').replace(/"/g, '""')}"`,
                    `"${(pendukung.tanggal_lahir || '-').replace(/"/g, '""')}"`,
                    `"${(pendukung.alamat || '-').replace(/"/g, '""')}"`,
                    pendukung.usia !== undefined && pendukung.usia !== null ? pendukung.usia : '-'
                ];
                csvRows.push(row.join(','));
            });
            const csv = csvRows.join('\n');

            const blob = new Blob([csv], { type: 'text/csv;charset=utf-8;' });
            const url = URL.createObjectURL(blob);
            const a = document.createElement('a');
            a.href = url;
            a.download = 'data_pendukung_kps.csv';
            document.body.appendChild(a); // Append to body for Firefox compatibility
            a.click();
            document.body.removeChild(a);
            URL.revokeObjectURL(url);
        };

        const downloadSelectedCards = () => {
            const selectedCheckboxes = document.querySelectorAll('.select-card-checkbox:checked');
            if (selectedCheckboxes.length === 0) {
                alert('Harap pilih kartu yang ingin di-download terlebih dahulu.');
                return;
            }
            if (selectedCheckboxes.length > appState.constants.MAX_PRINT_PER_BATCH) {
                alert(`Anda hanya dapat men-download maksimal ${appState.constants.MAX_PRINT_PER_BATCH} kartu dalam satu sesi.`);
                return;
            }

            const printArea = document.createElement('div');
            printArea.id = 'print-area';

            let currentPage = document.createElement('div');
            currentPage.className = 'print-page';
            printArea.appendChild(currentPage);

            selectedCheckboxes.forEach(checkbox => {
                const cardId = parseInt(checkbox.value, 10);
                const pendukungData = appState.db.pendukung.find(p => p.id === cardId);
                if (!pendukungData) return;

                const frontCard = createCardElement('frontCardTemplate', pendukungData);
                const backCard = createCardElement('backCardTemplate', pendukungData);
                const duplexPair = document.createElement('div');
                duplexPair.className = 'duplex-pair';
                if (frontCard) duplexPair.appendChild(frontCard);
                if (backCard) duplexPair.appendChild(backCard);
                currentPage.appendChild(duplexPair);
            });

            const styles = document.querySelector('style').innerHTML;
            const htmlToDownload = `
                <!DOCTYPE html>
                <html lang="id">
                <head>
                    <meta charset="UTF-8">
                    <title>Cetak Kartu Pendukung</title>
                    <style>
                        ${styles}
                        body { background-color: #eee; padding: 20px; }
                        #print-area { display: block !important; }
                        .print-page {
                            display: flex !important;
                            flex-wrap: wrap;
                            gap: 2mm 2mm;
                            justify-content: center;
                        }
                    </style>
                </head>
                <body>
                    ${printArea.outerHTML}
                </body>
                </html>
            `;

            const blob = new Blob([htmlToDownload.trim()], { type: 'text/html' });
            const url = URL.createObjectURL(blob);
            const a = document.createElement('a');
            a.href = url;
            a.download = 'kartu-pendukung.html';
            document.body.appendChild(a);
            a.click();
            document.body.removeChild(a);
            URL.revokeObjectURL(url);

            domElements.selectAllCheckbox.checked = false;
            document.querySelectorAll('.select-card-checkbox').forEach(cb => cb.checked = false);
        };

        const printSelectedCards = (printMode) => {
            const selectedCheckboxes = document.querySelectorAll('.select-card-checkbox:checked');
            if (selectedCheckboxes.length === 0) {
                alert('Harap pilih kartu yang ingin dicetak terlebih dahulu.');
                return;
            }
            if (selectedCheckboxes.length > appState.constants.MAX_PRINT_PER_BATCH) {
                alert(`Anda hanya dapat mencetak maksimal ${appState.constants.MAX_PRINT_PER_BATCH} kartu dalam satu sesi.`);
                return;
            }

            const printArea = document.getElementById('print-area');
            printArea.innerHTML = '';

            let cardsPerPrintPage = appState.constants.MAX_PRINT_PER_BATCH; 
            let currentPage = document.createElement('div');
            currentPage.className = 'print-page';
            printArea.appendChild(currentPage);

            let cardOnCurrentPage = 0;

            selectedCheckboxes.forEach(checkbox => {
                const cardId = parseInt(checkbox.value, 10);
                const pendukungData = appState.db.pendukung.find(p => p.id === cardId);

                if (!pendukungData) {
                    console.warn(`Data untuk kartu ID ${cardId} tidak ditemukan.`);
                    return;
                }

                if (cardOnCurrentPage >= cardsPerPrintPage) {
                    currentPage = document.createElement('div');
                    currentPage.className = 'print-page';
                    printArea.appendChild(currentPage);
                    cardOnCurrentPage = 0;
                }

                if (printMode === 'duplex') {
                    const frontCard = createCardElement('frontCardTemplate', pendukungData);
                    const backCard = createCardElement('backCardTemplate', pendukungData);
                    const duplexPair = document.createElement('div');
                    duplexPair.className = 'duplex-pair';
                    if (frontCard) duplexPair.appendChild(frontCard);
                    if (backCard) duplexPair.appendChild(backCard);
                    currentPage.appendChild(duplexPair);
                    cardOnCurrentPage++;
                } else if (printMode === 'front') {
                    const frontCard = createCardElement('frontCardTemplate', pendukungData);
                    if (frontCard) currentPage.appendChild(frontCard);
                    cardOnCurrentPage++;
                } else if (printMode === 'back') {
                    const backCard = createCardElement('backCardTemplate', pendukungData);
                    if (backCard) currentPage.appendChild(backCard);
                    cardOnCurrentPage++;
                }
            });

            window.print();

            domElements.selectAllCheckbox.checked = false;
            document.querySelectorAll('.select-card-checkbox').forEach(cb => cb.checked = false);
        };


        // --- NAVIGATION FUNCTIONS ---

        const handleNavigation = (e) => {
            e.preventDefault();
            const targetId = e.currentTarget.getAttribute('href').substring(1);

            domElements.pages.forEach(page => page.classList.remove('active'));
            domElements.navLinks.forEach(link => link.classList.remove('active'));

            document.getElementById(targetId).classList.add('active');
            e.currentTarget.classList.add('active');

            if (targetId === 'input') {
                resetPendukungForm();
            } else if (targetId === 'rekap') {
                renderRecapTable();
            } else if (targetId === 'pengaturan') {
                domElements.settingNamaAnggotaInput.value = appState.db.settings.namaAnggotaDPRD;
                domElements.settingCardTitleInput.value = appState.db.settings.cardTitle;
                updateNextIdDisplay();
            }
        };

        // --- AUTHENTICATION FUNCTIONS ---
        const performLogin = (username, password) => {
            const USER = 'admin';
            const PASS = 'admin123';

            if (username === USER && password === PASS) {
                sessionStorage.setItem('loggedIn', 'true');
                domElements.loginPage.classList.add('hidden'); // Sembunyikan halaman login
                domElements.appSidebar.classList.remove('hidden');
                domElements.appMainContent.classList.remove('hidden');
                initializeAppContent(); // Initialize app content after successful login
            } else {
                domElements.loginErrorMessage.classList.remove('hidden');
            }
        };

        const performLogout = () => {
            sessionStorage.removeItem('loggedIn');
            domElements.loginPage.classList.remove('hidden');
            domElements.appSidebar.classList.add('hidden');
            domElements.appMainContent.classList.add('hidden');
            domElements.usernameInput.value = '';
            domElements.passwordInput.value = '';
            domElements.loginErrorMessage.classList.add('hidden');
        };

        // --- EVENT LISTENERS SETUP ---

        const setupEventListeners = () => {
            domElements.loginForm.addEventListener('submit', (e) => {
                e.preventDefault();
                performLogin(domElements.usernameInput.value, domElements.passwordInput.value);
            });

            domElements.logoutLink.addEventListener('click', (e) => {
                e.preventDefault();
                performLogout();
            });

            domElements.navLinks.forEach(link => link.addEventListener('click', handleNavigation));
            domElements.pendukungForm.addEventListener('submit', handlePendukungFormSubmit);
            domElements.updateBtn.addEventListener('click', handlePendukungFormSubmit);
            domElements.cancelBtn.addEventListener('click', resetPendukungForm);
            domElements.printFrontBtn.addEventListener('click', () => printSelectedCards('front'));
            domElements.printBackBtn.addEventListener('click', () => printSelectedCards('back'));
            domElements.printDuplexBtn.addEventListener('click', () => printSelectedCards('duplex'));
            domElements.downloadCardsBtn.addEventListener('click', downloadSelectedCards);

            domElements.recapTableBody.addEventListener('click', (e) => {
                if (e.target.classList.contains('edit-btn')) {
                    const id = parseInt(e.target.dataset.id, 10);
                    const pendukungToEdit = appState.db.pendukung.find(p => p.id === id);

                    if (pendukungToEdit) {
                        document.querySelector('.nav-link[href="#input"]').click();

                        domElements.namaInput.value = pendukungToEdit.nama || '';
                        domElements.nikInput.value = pendukungToEdit.nik || '';
                        domElements.jenisKelaminSelect.value = pendukungToEdit.jenis_kelamin || '';
                        domElements.tempatLahirInput.value = pendukungToEdit.tempat_lahir || '';
                        domElements.tanggalLahirInput.value = pendukungToEdit.tanggal_lahir || '';
                        domElements.alamatInput.value = pendukungToEdit.alamat || '';
                        
                        domElements.editIdInput.value = pendukungToEdit.id;

                        domElements.formTitle.textContent = 'Edit Data Pendukung';
                        domElements.submitBtn.classList.add('hidden');
                        domElements.updateBtn.classList.remove('hidden');

                        const previewData = { ...pendukungToEdit, fotoUrl: pendukungToEdit.fotoUrl || null };
                        updateCardPreview(previewData);
                        domElements.pendukungForm.dataset.currentPreviewData = JSON.stringify(previewData);
                    } else {
                        alert('Gagal memuat data untuk diedit. Data tidak ditemukan.');
                    }
                } else if (e.target.classList.contains('delete-btn')) {
                    const id = parseInt(e.target.dataset.id, 10);
                    const pendukungToDelete = appState.db.pendukung.find(p => p.id === id);
                    if (pendukungToDelete && confirm(`Apakah Anda yakin ingin menghapus ${pendukungToDelete.nama}? Aksi ini tidak dapat dibatalkan.`)) {
                        appState.db.pendukung = appState.db.pendukung.filter(p => p.id !== id);
                        saveAppStateToLocalStorage();
                        renderRecapTable();
                        if (parseInt(domElements.editIdInput.value, 10) === id) {
                            resetPendukungForm();
                        }
                    }
                }
            });

            document.querySelectorAll('.filter-btn').forEach(btn => {
                btn.addEventListener('click', () => {
                    document.querySelectorAll('.filter-btn').forEach(b => {
                        b.classList.remove('btn-primary');
                        b.classList.add('btn-secondary');
                    });
                    btn.classList.add('btn-primary');
                    btn.classList.remove('btn-secondary');

                    appState.currentFilter = btn.dataset.filter;
                    renderRecapTable();
                });
            });

            domElements.searchInput.addEventListener('keyup', (e) => {
                appState.currentSearchTerm = e.target.value;
                renderRecapTable();
            });

            domElements.saveSettingsBtn.addEventListener('click', async () => {
                appState.db.settings.namaAnggotaDPRD = domElements.settingNamaAnggotaInput.value.trim();
                appState.db.settings.cardTitle = domElements.settingCardTitleInput.value.trim();

                let dprdPhotoUrl = null;
                const dprdFile = domElements.settingDprdPhotoUpload.files[0];
                if (dprdFile) {
                    try {
                        dprdPhotoUrl = await compressImage(dprdFile);
                    } catch (err) {
                        alert('Gagal mengompresi foto anggota DPRD. Coba lagi.');
                        console.error('Compression error:', err);
                    }
                } else {
                    dprdPhotoUrl = appState.db.settings.dprdPhotoUrl; // Keep existing if no new upload
                }
                appState.db.settings.dprdPhotoUrl = dprdPhotoUrl;

                let pkbLogoUrl = null;
                const pkbFile = domElements.settingPkbLogoUpload.files[0];
                if (pkbFile) {
                    try {
                        pkbLogoUrl = await compressImage(pkbFile);
                    } catch (err) {
                        alert('Gagal mengompresi logo PKB. Coba lagi.');
                        console.error('Compression error:', err);
                    }
                } else {
                    pkbLogoUrl = appState.db.settings.pkbLogoUrl; // Keep existing if no new upload
                }
                appState.db.settings.pkbLogoUrl = pkbLogoUrl;

                saveAppStateToLocalStorage();

                const currentPreviewDataString = domElements.pendukungForm.dataset.currentPreviewData;
                if (currentPreviewDataString) {
                    const dataForPreview = JSON.parse(currentPreviewDataString);
                    updateCardPreview(dataForPreview); // Re-render with new settings
                }
                alert('Pengaturan kartu berhasil disimpan!');
            });

            domElements.selectAllCheckbox.addEventListener('change', (e) => {
                const isChecked = e.target.checked;
                document.querySelectorAll('.select-card-checkbox').forEach(cb => {
                    cb.checked = isChecked;
                });
            });

            domElements.exportCSVBtn.addEventListener('click', exportPendukungToCSV);

            ['nama', 'nik', 'jenis_kelamin', 'tempat_lahir', 'tanggal_lahir', 'alamat'].forEach(id => {
                document.getElementById(id).addEventListener('input', () => {
                    const formDataForPreview = {
                        nama: domElements.namaInput.value,
                        nik: domElements.nikInput.value,
                        jenis_kelamin: domElements.jenisKelaminSelect.value,
                        tempat_lahir: domElements.tempatLahirInput.value,
                        tanggal_lahir: domElements.tanggalLahirInput.value,
                        alamat: domElements.alamatInput.value,
                        usia: calculateAge(domElements.tanggalLahirInput.value),
                        fotoUrl: domElements.fotoPendukungUpload.files[0] ? URL.createObjectURL(domElements.fotoPendukungUpload.files[0]) : (appState.db.pendukung.find(p => p.id === parseInt(domElements.editIdInput.value, 10))?.fotoUrl || null),
                        no_pendukung: domElements.editIdInput.value ? appState.db.pendukung.find(p => p.id === parseInt(domElements.editIdInput.value, 10))?.no_pendukung : `PKB-LOYAL-${String(appState.db.settings.nextIdCounter).padStart(4, '0')}`
                    };
                    updateCardPreview(formDataForPreview);
                    domElements.pendukungForm.dataset.currentPreviewData = JSON.stringify(formDataForPreview);
                });
            });

            domElements.fotoPendukungUpload.addEventListener('change', async (e) => {
                const fotoFile = e.target.files[0];
                let previewFotoUrl = null;
                if (fotoFile) {
                    try {
                        previewFotoUrl = await compressImage(fotoFile);
                    } catch (err) {
                        console.error('Compression error for preview:', err);
                    }
                }

                const currentPreviewDataString = domElements.pendukungForm.dataset.currentPreviewData;
                let currentPreviewData = {};
                if (currentPreviewDataString) {
                    currentPreviewData = JSON.parse(currentPreviewDataString);
                } else {
                    currentPreviewData = {
                        nama: domElements.namaInput.value,
                        nik: domElements.nikInput.value,
                        jenis_kelamin: domElements.jenisKelaminSelect.value,
                        tempat_lahir: domElements.tempatLahirInput.value,
                        tanggal_lahir: domElements.tanggalLahirInput.value,
                        alamat: domElements.alamatInput.value,
                        usia: calculateAge(domElements.tanggalLahirInput.value),
                        no_pendukung: domElements.editIdInput.value ? appState.db.pendukung.find(p => p.id === parseInt(domElements.editIdInput.value, 10))?.no_pendukung : `PKB-LOYAL-${String(appState.db.settings.nextIdCounter).padStart(4, '0')}`
                    };
                }
                currentPreviewData.fotoUrl = previewFotoUrl;
                updateCardPreview(currentPreviewData);
                domElements.pendukungForm.dataset.currentPreviewData = JSON.stringify(currentPreviewData);
            });

            if (domElements.resetNextIdBtn) {
                domElements.resetNextIdBtn.addEventListener('click', () => {
                    if (confirm("PERINGATAN: Anda akan mereset nomor ID pendukung berikutnya ke 'PKB-LOYAL-0001'. Ini mungkin menyebabkan duplikasi ID jika ada pendukung yang ID-nya sudah terpakai sebelumnya. Lanjutkan?")) {
                        appState.db.settings.nextIdCounter = 1;
                        saveAppStateToLocalStorage();
                        updateNextIdDisplay();
                        alert("Nomor ID pendukung berikutnya telah direset ke PKB-LOYAL-0001.");
                    }
                });
            }
        };

        // --- INITIALIZATION ---

        const initializeAppContent = () => {
            loadAppStateFromLocalStorage();
            domElements.settingNamaAnggotaInput.value = appState.db.settings.namaAnggotaDPRD;
            domElements.settingCardTitleInput.value = appState.db.settings.cardTitle;
            
            updateNextIdDisplay();
            renderRecapTable();
            resetPendukungForm();
            
            document.querySelector('.nav-link.active')?.click();
        };

        const checkLoginStatus = () => {
            if (sessionStorage.getItem('loggedIn') === 'true') {
                domElements.loginPage.classList.add('hidden'); // Sembunyikan halaman login
                domElements.appSidebar.classList.remove('hidden');
                domElements.appMainContent.classList.remove('hidden');
                initializeAppContent();
            } else {
                domElements.loginPage.classList.remove('hidden');
                domElements.appSidebar.classList.add('hidden');
                domElements.appMainContent.classList.add('hidden');
            }
        };

        // Initial setup
        setupEventListeners();
        checkLoginStatus();
    });
    </script>
</body>
</html>
