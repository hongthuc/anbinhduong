<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
  <title>CÔNG TY TNHH MTV AN BÌNH DƯƠNG - Giải Pháp Lọc Nước Water 4.0 Đà Nẵng | anbinhduong.com</title>
  <meta name="description" content="CÔNG TY TNHH MTV AN BÌNH DƯƠNG (anbinhduong.com) - Chuyên Lọc Tổng Đầu Nguồn Karofi, Lọc Nước RO Y Tế, Máy Tạo Nước Ion Kiềm, Máy Lọc Nước Gia Đình tại Đà Nẵng. Địa chỉ: 25 Cẩm Nam 6, Phường Hòa Xuân, TP Đà Nẵng. Hotline: 0905.457.936">

  <!-- Open Graph / Thumbnail là ảnh Logo trang web khi gửi link chia sẻ -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://anbinhduong.com/">
  <meta property="og:site_name" content="anbinhduong.com - CÔNG TY TNHH MTV AN BÌNH DƯƠNG">
  <meta property="og:title" content="CÔNG TY TNHH MTV AN BÌNH DƯƠNG - Hệ Thống Lọc Nước Water 4.0 Đà Nẵng">
  <meta property="og:description" content="Chuyên Lọc Tổng Karofi, Lọc Nước RO Y Tế, Máy Tạo Nước Ion Kiềm, Máy Lọc Nước Gia Đình. Đ/c: 25 Cẩm Nam 6, P. Hòa Xuân, TP Đà Nẵng - ĐT: 0905.457.936">
  <meta property="og:image" content="https://placehold.co/1200x630/0066b3/ffffff?text=AN+BINH+DUONG+-+WATER+4.0+%7C+anbinhduong.com">
  <meta property="og:image:width" content="1200">
  <meta property="og:image:height" content="630">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:image" content="https://placehold.co/1200x630/0066b3/ffffff?text=AN+BINH+DUONG+-+WATER+4.0+%7C+anbinhduong.com">

  <!-- Google Fonts: Inter / Roboto chuẩn Flatsome -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
          },
          colors: {
            brand: {
              50: '#f0f8ff',
              100: '#e0f1fe',
              500: '#0284c7',
              600: '#0066b3', /* Màu xanh chủ đạo theo màu Logo An Bình Dương Water 4.0 */
              700: '#005291',
              800: '#003e6e',
              accent: '#00a8e8',
              sale: '#e63946' /* Màu đỏ cam badge giảm giá chuẩn Flatsome */
            }
          }
        }
      }
    }
  </script>

  <style>
    /* Đảm bảo tuyệt đối không tràn viền, không lệch sang phải trên mọi thiết bị */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100vw;
      overflow-x: hidden;
      font-family: 'Inter', sans-serif;
      background-color: #f8fafc;
      color: #1e293b;
      scroll-behavior: smooth;
    }

    /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính */
    .flatsome-container {
      width: 100%;
      padding-left: 10px;
      padding-right: 10px;
      margin-left: auto;
      margin-right: auto;
    }
    @media (min-width: 1024px) {
      .flatsome-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Tiêu đề danh mục chuẩn UX Builder Flatsome (Section Title Normal / Center) */
    .flatsome-section-title {
      display: flex;
      align-items: center;
      justify-content: space-between;
      border-bottom: 2px solid #e2e8f0;
      margin-bottom: 16px;
      padding-bottom: 8px;
    }
    .flatsome-section-title h2 {
      position: relative;
      font-weight: 700;
      color: #0066b3;
      text-transform: uppercase;
      letter-spacing: 0.02em;
    }
    .flatsome-section-title h2::after {
      content: '';
      position: absolute;
      bottom: -10px;
      left: 0;
      width: 100%;
      height: 3px;
      background-color: #0066b3;
    }

    /* Vòng tròn giảm giá góc trên bên trái chuẩn Flatsome */
    .flatsome-badge-sale {
      position: absolute;
      top: 8px;
      left: 8px;
      z-index: 10;
      background-color: #d9251d;
      color: #ffffff;
      font-weight: 700;
      font-size: 11px;
      width: 38px;
      height: 38px;
      border-radius: 9999px;
      display: flex;
      align-items: center;
      justify-content: center;
      box-shadow: 0 2px 6px rgba(217, 37, 29, 0.35);
      line-height: 1;
    }
    @media (max-width: 640px) {
      .flatsome-badge-sale {
        width: 34px;
        height: 34px;
        font-size: 10px;
        top: 6px;
        left: 6px;
      }
    }

    /* Hiệu ứng pulse nhẹ cho nút liên hệ nổi */
    @keyframes pulse-ring {
      0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(0, 102, 179, 0.6); }
      70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(0, 102, 179, 0); }
      100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(0, 102, 179, 0); }
    }
    .contact-pulse {
      animation: pulse-ring 2s infinite;
    }
  </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased">

  <!-- ==================== TOP BAR CHUẨN FLATSOME ==================== -->
  <div class="bg-brand-700 text-white text-[11px] sm:text-xs py-1.5 border-b border-brand-800">
    <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
      <div class="flex items-center gap-3 truncate">
        <span class="font-semibold tracking-wide">CÔNG TY TNHH MTV AN BÌNH DƯƠNG - GIẢI PHÁP NƯỚC SẠCH WATER 4.0</span>
        <span class="hidden md:inline-block text-brand-100">|</span>
        <span class="hidden md:inline-flex items-center gap-1 text-brand-100">
          <i class="fa-solid fa-location-dot text-cyan-300"></i>
          25 Cẩm Nam 6, Phường Hòa Xuân, TP Đà Nẵng
        </span>
      </div>
      <div class="hidden sm:flex items-center gap-4 text-brand-100 shrink-0">
        <a href="https://www.facebook.com/water4.0" target="_blank" rel="noopener noreferrer" class="hover:text-white transition flex items-center gap-1">
          <i class="fa-brands fa-facebook"></i> Fanpage Water 4.0
        </a>
        <span>|</span>
        <a href="#form-bao-gia" class="hover:text-white transition flex items-center gap-1">
          <i class="fa-solid fa-file-invoice"></i> Yêu cầu báo giá
        </a>
        <span>|</span>
        <span class="text-cyan-200 font-medium">Website: anbinhduong.com</span>
      </div>
    </div>
  </div>

  <!-- ==================== HEADER CHÍNH (KHÔNG ĐỂ NÚT GỌI NGAY TRÁNH TRÀN VIỀN) ==================== -->
  <header class="bg-white sticky top-0 z-40 shadow-sm border-b border-slate-200">
    <div class="flatsome-container py-2.5 flex items-center justify-between gap-2 sm:gap-4">
      
      <!-- Nút mở Menu trên Điện Thoại -->
      <button id="btn-mobile-menu" type="button" aria-label="Mở danh mục" class="lg:hidden p-2 rounded-lg text-brand-600 hover:bg-brand-50 border border-slate-200 shrink-0">
        <i class="fa-solid fa-bars text-base"></i>
      </button>

      <!-- LOGO MỚI CHUYÊN NGHIỆP - CHỈNH GỌN NHỎ LẠI -->
      <a href="#" class="flex items-center gap-2 shrink-0 group focus:outline-none">
        <!-- Biểu tượng SVG Logo An Bình Dương Water 4.0 nhỏ gọn -->
        <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-xl bg-gradient-to-br from-brand-600 to-brand-accent flex items-center justify-center shadow-sm shrink-0">
          <svg class="w-6 h-6 sm:w-6 sm:h-6 text-white" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M32 6C32 6 14 26.5 14 40C14 49.9411 22.0589 58 32 58C41.9411 58 50 49.9411 50 40C50 26.5 32 6 32 6Z" fill="white" fill-opacity="0.2"/>
            <path d="M32 10C32 10 17 28 17 40C17 48.2843 23.7157 55 32 55C40.2843 55 47 48.2843 47 40C47 28 32 10 32 10Z" stroke="white" stroke-width="3.2" stroke-linecap="round" stroke-linejoin="round"/>
            <path d="M22 41C25 38 29 38 32 41C35 44 39 44 42 41" stroke="#bae6fd" stroke-width="3" stroke-linecap="round"/>
            <circle cx="32" cy="27" r="3" fill="white"/>
          </svg>
        </div>
        <div class="leading-tight">
          <div class="flex items-center gap-1">
            <span class="text-[13px] sm:text-[15px] font-extrabold text-brand-600 tracking-tight">AN BÌNH DƯƠNG</span>
            <span class="hidden sm:inline-block text-[10px] font-bold bg-brand-50 text-brand-600 border border-brand-200 px-1.5 py-0.5 rounded">WATER 4.0</span>
          </div>
          <p class="text-[10px] sm:text-[11px] text-slate-500 font-medium">anbinhduong.com • Lọc Nước Đà Nẵng</p>
        </div>
      </a>

      <!-- Thanh tìm kiếm sản phẩm chuẩn Flatsome -->
      <div class="hidden md:flex flex-1 max-w-md mx-2">
        <form onsubmit="handleSearch(event)" class="w-full relative flex items-center">
          <input id="search-input" type="text" placeholder="Tìm máy lọc tổng Karofi, lọc RO y tế, máy ion kiềm..." 
            class="w-full pl-3.5 pr-10 py-1.5 text-xs sm:text-sm bg-slate-50 border border-slate-300 rounded-full focus:outline-none focus:border-brand-600 focus:bg-white transition">
          <button type="submit" aria-label="Tìm kiếm" class="absolute right-1 top-1 bottom-1 px-3 bg-brand-600 text-white rounded-full hover:bg-brand-700 transition flex items-center justify-center">
            <i class="fa-solid fa-magnifying-glass text-xs"></i>
          </button>
        </form>
      </div>

      <!-- Cam kết chính hãng nhỏ gọn trên máy tính & Nút Yêu cầu báo giá nhanh (Không để nút gọi ngay tránh tràn viền) -->
      <div class="flex items-center gap-2 sm:gap-3 shrink-0">
        <div class="hidden xl:flex items-center gap-2 text-xs text-slate-600 bg-slate-50 px-2.5 py-1.5 rounded-lg border border-slate-200">
          <i class="fa-solid fa-shield-halved text-brand-600"></i>
          <span>Chính hãng 100%</span>
        </div>
        <a href="#form-bao-gia" class="px-2.5 sm:px-3.5 py-1.5 rounded-lg bg-brand-50 hover:bg-brand-100 text-brand-600 border border-brand-200 text-[11px] sm:text-xs font-semibold transition flex items-center gap-1.5 shrink-0">
          <i class="fa-solid fa-paper-plane"></i>
          <span>Báo giá</span>
        </a>
      </div>
    </div>

    <!-- Thanh tìm kiếm dưới Header cho Điện Thoại -->
    <div class="md:hidden flatsome-container pb-2">
      <form onsubmit="handleSearch(event)" class="w-full relative flex items-center">
        <input id="search-input-mobile" type="text" placeholder="Tìm sản phẩm lọc nước An Bình Dương..." 
          class="w-full pl-3 pr-9 py-1.5 text-xs bg-slate-50 border border-slate-300 rounded-lg focus:outline-none focus:border-brand-600">
        <button type="submit" aria-label="Tìm kiếm" class="absolute right-1.5 text-brand-600 p-1">
          <i class="fa-solid fa-magnifying-glass text-xs"></i>
        </button>
      </form>
    </div>

    <!-- ==================== THANH DANH MỤC TRÊN MÁY TÍNH ==================== -->
    <!-- Tối ưu chữ nhỏ gọn, viết liền trên 1 hàng (whitespace-nowrap), nếu màn hình hẹp tự rớt nguyên cụm sang hàng 2, tuyệt đối không gãy chữ trong tên danh mục -->
    <nav class="hidden lg:block bg-brand-600 text-white border-t border-brand-700">
      <div class="flatsome-container">
        <ul class="flex flex-wrap items-center justify-center gap-x-1 gap-y-0.5 py-1">
          <li>
            <a href="#" class="whitespace-nowrap inline-flex items-center gap-1 px-2.5 py-1.5 rounded text-[12.5px] font-semibold bg-brand-700 text-white transition">
              <i class="fa-solid fa-house text-[11px]"></i> Trang chủ
            </a>
          </li>
          <li>
            <a href="#gioi-thieu" class="whitespace-nowrap inline-block px-2.5 py-1.5 rounded text-[12.5px] font-semibold hover:bg-brand-700 transition">
              Giới thiệu
            </a>
          </li>
          <li>
            <a href="#dm-loc-tong-karofi" class="whitespace-nowrap inline-block px-2.5 py-1.5 rounded text-[12.5px] font-semibold hover:bg-brand-700 transition">
              Lọc tổng Karofi
            </a>
          </li>
          <li>
            <a href="#dm-loc-ro-y-te" class="whitespace-nowrap inline-block px-2.5 py-1.5 rounded text-[12.5px] font-semibold hover:bg-brand-700 transition">
              Lọc nước RO y tế
            </a>
          </li>
          <li>
            <a href="#dm-may-ion-kiem" class="whitespace-nowrap inline-block px-2.5 py-1.5 rounded text-[12.5px] font-semibold hover:bg-brand-700 transition">
              Máy tạo nước ion kiềm
            </a>
          </li>
          <li>
            <a href="#dm-loc-nuoc-gia-dinh" class="whitespace-nowrap inline-block px-2.5 py-1.5 rounded text-[12.5px] font-semibold hover:bg-brand-700 transition">
              Máy lọc nước gia đình
            </a>
          </li>
          <li>
            <a href="#dm-vat-lieu-loc" class="whitespace-nowrap inline-block px-2.5 py-1.5 rounded text-[12.5px] font-semibold hover:bg-brand-700 transition">
              Vật liệu lọc nước
            </a>
          </li>
          <li>
            <a href="#du-an-da-nang" class="whitespace-nowrap inline-block px-2.5 py-1.5 rounded text-[12.5px] font-semibold hover:bg-brand-700 transition">
              Dự án Đà Nẵng
            </a>
          </li>
          <li>
            <a href="#doi-tac" class="whitespace-nowrap inline-block px-2.5 py-1.5 rounded text-[12.5px] font-semibold hover:bg-brand-700 transition">
              Đối tác
            </a>
          </li>
          <li>
            <a href="#tin-tuc" class="whitespace-nowrap inline-block px-2.5 py-1.5 rounded text-[12.5px] font-semibold hover:bg-brand-700 transition">
              Tin tức
            </a>
          </li>
          <li>
            <a href="#lien-he-map" class="whitespace-nowrap inline-block px-2.5 py-1.5 rounded text-[12.5px] font-semibold hover:bg-brand-700 transition">
              Liên hệ
            </a>
          </li>
        </ul>
      </div>
    </nav>

    <!-- ==================== MENU DANH MỤC ĐIỆN THOẠI (DRAWER GỌN ĐẸP) ==================== -->
    <div id="mobile-menu-drawer" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
      <div class="flatsome-container py-3">
        <div class="grid grid-cols-2 gap-1.5 text-xs font-semibold text-slate-700">
          <a href="#" onclick="closeMobileMenu()" class="px-3 py-2 rounded-lg bg-brand-50 text-brand-600 flex items-center gap-2">
            <i class="fa-solid fa-house"></i> Trang chủ
          </a>
          <a href="#gioi-thieu" onclick="closeMobileMenu()" class="px-3 py-2 rounded-lg hover:bg-slate-100 flex items-center gap-2">
            <i class="fa-solid fa-building text-brand-600"></i> Giới thiệu
          </a>
          <a href="#dm-loc-tong-karofi" onclick="closeMobileMenu()" class="px-3 py-2 rounded-lg hover:bg-slate-100 flex items-center gap-2">
            <i class="fa-solid fa-filter text-brand-600"></i> Lọc tổng Karofi
          </a>
          <a href="#dm-loc-ro-y-te" onclick="closeMobileMenu()" class="px-3 py-2 rounded-lg hover:bg-slate-100 flex items-center gap-2">
            <i class="fa-solid fa-hospital text-brand-600"></i> Lọc nước RO y tế
          </a>
          <a href="#dm-may-ion-kiem" onclick="closeMobileMenu()" class="px-3 py-2 rounded-lg hover:bg-slate-100 flex items-center gap-2">
            <i class="fa-solid fa-droplet text-brand-600"></i> Máy tạo ion kiềm
          </a>
          <a href="#dm-loc-nuoc-gia-dinh" onclick="closeMobileMenu()" class="px-3 py-2 rounded-lg hover:bg-slate-100 flex items-center gap-2">
            <i class="fa-solid fa-faucet-drip text-brand-600"></i> Lọc nước gia đình
          </a>
          <a href="#dm-vat-lieu-loc" onclick="closeMobileMenu()" class="px-3 py-2 rounded-lg hover:bg-slate-100 flex items-center gap-2">
            <i class="fa-solid fa-layer-group text-brand-600"></i> Vật liệu lọc nước
          </a>
          <a href="#du-an-da-nang" onclick="closeMobileMenu()" class="px-3 py-2 rounded-lg hover:bg-slate-100 flex items-center gap-2">
            <i class="fa-solid fa-diagram-project text-brand-600"></i> Dự án Đà Nẵng
          </a>
          <a href="#tin-tuc" onclick="closeMobileMenu()" class="px-3 py-2 rounded-lg hover:bg-slate-100 flex items-center gap-2">
            <i class="fa-solid fa-newspaper text-brand-600"></i> Bài viết - Tin tức
          </a>
          <a href="#lien-he-map" onclick="closeMobileMenu()" class="px-3 py-2 rounded-lg hover:bg-slate-100 flex items-center gap-2">
            <i class="fa-solid fa-map-location-dot text-brand-600"></i> Bản đồ & Liên hệ
          </a>
        </div>
      </div>
    </div>
  </header>

  <!-- ==================== SLIDER 2 ẢNH BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU ==================== -->
  <!-- Thiết kế mới ảnh banner điện thoại khác với ảnh banner trên máy tính để tối ưu chữ bên trong ảnh, chữ nhỏ gọn nằm hết trong ảnh banner -->
  <section class="py-3 sm:py-4">
    <div class="flatsome-container">
      <div class="relative rounded-xl overflow-hidden shadow-sm border border-slate-200 bg-brand-800">
        
        <!-- Vùng chứa 2 Slide -->
        <div id="banner-slider" class="relative w-full">

          <!-- ==================== SLIDE 1 ==================== -->
          <div class="banner-slide block transition-opacity duration-500">
            
            <!-- BANNER 1 - GIAO DIỆN MÁY TÍNH (Desktop Only - kích thước cố định 350px bằng tuyệt đối với Slide 2) -->
            <div class="hidden md:flex items-center justify-between w-full h-[350px] bg-gradient-to-r from-[#003966] via-[#0066b3] to-[#0284c7] px-12 lg:px-16 relative overflow-hidden">
              <!-- Họa tiết sóng nước nền SVG -->
              <svg class="absolute inset-0 w-full h-full opacity-15 pointer-events-none" viewBox="0 0 1200 350" preserveAspectRatio="none">
                <path d="M0,220 C300,300 600,120 1200,240 L1200,350 L0,350 Z" fill="#ffffff"/>
                <circle cx="1050" cy="80" r="160" fill="#38bdf8" opacity="0.25"/>
              </svg>

              <!-- Cột nội dung chữ bên trái (chữ nhỏ gọn, nằm trọn trong ảnh banner) -->
              <div class="relative z-10 w-[58%] text-white pr-6">
                <p class="text-xs font-bold uppercase tracking-widest text-cyan-200 mb-1.5">
                  CÔNG TY TNHH MTV AN BÌNH DƯƠNG • WATER 4.0 ĐÀ NẴNG
                </p>
                <h1 class="text-xl lg:text-2xl font-extrabold leading-snug mb-2.5 text-white">
                  CHUYÊN HỆ THỐNG LỌC TỔNG ĐẦU NGUỒN KAROFI, LỌC RO Y TẾ & MÁY TẠO NƯỚC ION KIỀM
                </h1>
                <p class="text-xs lg:text-[13px] text-sky-100 leading-relaxed mb-4">
                  Giải pháp xử lý nước sinh hoạt, nước uống chuẩn Y tế cho gia đình, biệt thự, bệnh viện và doanh nghiệp tại Đà Nẵng & Miền Trung. Khảo sát nguồn nước và lắp đặt tận nơi.
                </p>
                <div class="flex flex-wrap items-center gap-3 text-xs">
                  <span class="bg-white text-brand-700 font-bold px-3.5 py-2 rounded-lg shadow-sm">
                    <i class="fa-solid fa-phone-volume mr-1"></i> Hotline: 0905.457.936
                  </span>
                  <span class="bg-brand-900/50 border border-cyan-300/40 text-white px-3.5 py-2 rounded-lg">
                    <i class="fa-solid fa-location-dot text-cyan-300 mr-1"></i> 25 Cẩm Nam 6, P. Hòa Xuân, TP Đà Nẵng
                  </span>
                </div>
              </div>

              <!-- Cột hình ảnh thực tế sản phẩm bên phải -->
              <div class="relative z-10 w-[40%] flex items-center justify-center gap-3">
                <div class="bg-white/95 p-2 rounded-xl shadow-lg w-44 h-60 flex flex-col items-center justify-center">
                  <img src="https://drive.google.com/thumbnail?id=1RyN2L6jXsXypf7BlkoRmelwy8nRZN3Wa&sz=w600" 
                       onerror="handleDriveImgError(this, '1RyN2L6jXsXypf7BlkoRmelwy8nRZN3Wa', 'Lọc Tổng Karofi')"
                       alt="Lọc tổng Karofi An Bình Dương" class="w-full h-44 object-contain rounded">
                  <span class="text-[11px] font-bold text-brand-700 mt-1">Lọc Tổng Đầu Nguồn</span>
                </div>
                <div class="bg-white/95 p-2 rounded-xl shadow-lg w-44 h-60 flex flex-col items-center justify-center">
                  <img src="https://drive.google.com/thumbnail?id=1NfaePBKw2OBu8M9yWw7QarsrCAQpY8Mr&sz=w600" 
                       onerror="handleDriveImgError(this, '1NfaePBKw2OBu8M9yWw7QarsrCAQpY8Mr', 'Hệ Thống Lọc Nước')"
                       alt="Máy lọc nước An Bình Dương" class="w-full h-44 object-contain rounded">
                  <span class="text-[11px] font-bold text-brand-700 mt-1">Lọc RO & Ion Kiềm</span>
                </div>
              </div>
            </div>

            <!-- BANNER 1 - GIAO DIỆN ĐIỆN THOẠI RIÊNG BIỆT (Mobile Only - kích thước cố định 240px bằng tuyệt đối với Slide 2) -->
            <!-- Chữ nhỏ gọn, bố cục tối ưu riêng cho màn hình hẹp, không tràn viền -->
            <div class="flex md:hidden items-center justify-between w-full h-[240px] bg-gradient-to-br from-[#00447a] via-[#0066b3] to-[#0096c7] px-4 py-3 relative overflow-hidden">
              <div class="w-[62%] text-white pr-2 z-10">
                <p class="text-[10px] font-bold text-cyan-200 uppercase tracking-wider mb-1">
                  AN BÌNH DƯƠNG • WATER 4.0
                </p>
                <h2 class="text-[13.5px] sm:text-[15px] font-extrabold leading-tight mb-1.5 text-white">
                  LỌC TỔNG ĐẦU NGUỒN KAROFI & MÁY TẠO ION KIỀM ĐÀ NẴNG
                </h2>
                <p class="text-[10.5px] text-sky-100 leading-snug mb-2">
                  Xử lý nước phèn, vôi, clo dư. Bảo vệ sức khỏe & thiết bị toàn diện.
                </p>
                <div class="inline-block bg-white text-brand-700 font-bold text-[10.5px] px-2.5 py-1 rounded shadow-sm">
                  ĐT: 0905.457.936 • Hòa Xuân, ĐN
                </div>
              </div>
              <div class="w-[36%] h-[190px] bg-white/95 rounded-lg p-1.5 flex flex-col items-center justify-center shadow z-10">
                <img src="https://drive.google.com/thumbnail?id=1RyN2L6jXsXypf7BlkoRmelwy8nRZN3Wa&sz=w500" 
                     onerror="handleDriveImgError(this, '1RyN2L6jXsXypf7BlkoRmelwy8nRZN3Wa', 'Lọc Tổng Karofi')"
                     alt="Lọc tổng đầu nguồn" class="w-full h-36 object-contain rounded">
                <span class="text-[9.5px] font-bold text-brand-700 text-center mt-0.5">anbinhduong.com</span>
              </div>
            </div>

          </div>

          <!-- ==================== SLIDE 2 ==================== -->
          <div class="banner-slide hidden transition-opacity duration-500">
            
            <!-- BANNER 2 - GIAO DIỆN MÁY TÍNH (Desktop Only - kích thước cố định 350px bằng tuyệt đối với Slide 1) -->
            <div class="hidden md:flex items-center justify-between w-full h-[350px] bg-gradient-to-r from-[#004e64] via-[#0066b3] to-[#00a8e8] px-12 lg:px-16 relative overflow-hidden">
              <svg class="absolute inset-0 w-full h-full opacity-15 pointer-events-none" viewBox="0 0 1200 350" preserveAspectRatio="none">
                <path d="M0,120 C400,260 800,60 1200,200 L1200,350 L0,350 Z" fill="#ffffff"/>
              </svg>

              <!-- Cột nội dung chữ bên trái (chữ nhỏ gọn, nằm trọn trong ảnh banner) -->
              <div class="relative z-10 w-[58%] text-white pr-6">
                <p class="text-xs font-bold uppercase tracking-widest text-cyan-200 mb-1.5">
                  GIẢI PHÁP CÔNG NGHỆ NƯỚC SẠCH 4.0 • ANBINHDUONG.COM
                </p>
                <h2 class="text-xl lg:text-2xl font-extrabold leading-snug mb-2.5 text-white">
                  THI CÔNG HỆ THỐNG LỌC NƯỚC RO Y TẾ, BỆNH VIỆN & LỌC TỔNG CÔNG NGHIỆP
                </h2>
                <p class="text-xs lg:text-[13px] text-sky-100 leading-relaxed mb-4">
                  Cung cấp vật liệu lọc nước chính hãng, hệ thống nước RO chạy thận, nước cấp phòng mổ, phòng xét nghiệm và máy lọc nước gia đình. Bảo hành tận tâm 24/7 tại Đà Nẵng.
                </p>
                <div class="flex flex-wrap items-center gap-3 text-xs">
                  <span class="bg-white text-brand-700 font-bold px-3.5 py-2 rounded-lg shadow-sm">
                    <i class="fa-solid fa-screwdriver-wrench mr-1"></i> Tư vấn kỹ thuật: 0905.457.936
                  </span>
                  <span class="bg-brand-900/50 border border-cyan-300/40 text-white px-3.5 py-2 rounded-lg">
                    <i class="fa-solid fa-globe text-cyan-300 mr-1"></i> Website: anbinhduong.com
                  </span>
                </div>
              </div>

              <!-- Cột hình ảnh thực tế sản phẩm bên phải -->
              <div class="relative z-10 w-[40%] flex items-center justify-center gap-3">
                <div class="bg-white/95 p-2 rounded-xl shadow-lg w-44 h-60 flex flex-col items-center justify-center">
                  <img src="https://drive.google.com/thumbnail?id=1gEsKV9IPQwNpI-LDtRw384ElM2Co3yDW&sz=w600" 
                       onerror="handleDriveImgError(this, '1gEsKV9IPQwNpI-LDtRw384ElM2Co3yDW', 'Lọc RO Y Tế')"
                       alt="Hệ thống RO Y tế An Bình Dương" class="w-full h-44 object-contain rounded">
                  <span class="text-[11px] font-bold text-brand-700 mt-1">Hệ Thống RO Y Tế</span>
                </div>
                <div class="bg-white/95 p-2 rounded-xl shadow-lg w-44 h-60 flex flex-col items-center justify-center">
                  <img src="https://drive.google.com/thumbnail?id=1duMuOfXOjVtTQ-AJ2Kmium-rO6DT-x_V&sz=w600" 
                       onerror="handleDriveImgError(this, '1duMuOfXOjVtTQ-AJ2Kmium-rO6DT-x_V', 'Máy Ion Kiềm')"
                       alt="Máy tạo nước Ion kiềm" class="w-full h-44 object-contain rounded">
                  <span class="text-[11px] font-bold text-brand-700 mt-1">Máy Tạo Ion Kiềm</span>
                </div>
              </div>
            </div>

            <!-- BANNER 2 - GIAO DIỆN ĐIỆN THOẠI RIÊNG BIỆT (Mobile Only - kích thước cố định 240px bằng tuyệt đối với Slide 1) -->
            <div class="flex md:hidden items-center justify-between w-full h-[240px] bg-gradient-to-br from-[#004e64] via-[#0066b3] to-[#0284c7] px-4 py-3 relative overflow-hidden">
              <div class="w-[62%] text-white pr-2 z-10">
                <p class="text-[10px] font-bold text-cyan-200 uppercase tracking-wider mb-1">
                  CÔNG TY TNHH MTV AN BÌNH DƯƠNG
                </p>
                <h2 class="text-[13.5px] sm:text-[15px] font-extrabold leading-tight mb-1.5 text-white">
                  HỆ THỐNG LỌC NƯỚC RO Y TẾ & VẬT LIỆU LỌC CHÍNH HÃNG
                </h2>
                <p class="text-[10.5px] text-sky-100 leading-snug mb-2">
                  Lắp đặt tận nơi tại Đà Nẵng. Cam kết nước đạt chuẩn Bộ Y Tế.
                </p>
                <div class="inline-block bg-white text-brand-700 font-bold text-[10.5px] px-2.5 py-1 rounded shadow-sm">
                  Đ/c: 25 Cẩm Nam 6, Hòa Xuân
                </div>
              </div>
              <div class="w-[36%] h-[190px] bg-white/95 rounded-lg p-1.5 flex flex-col items-center justify-center shadow z-10">
                <img src="https://drive.google.com/thumbnail?id=1gEsKV9IPQwNpI-LDtRw384ElM2Co3yDW&sz=w500" 
                     onerror="handleDriveImgError(this, '1gEsKV9IPQwNpI-LDtRw384ElM2Co3yDW', 'Lọc RO Y Tế')"
                     alt="Lọc nước RO Y tế" class="w-full h-36 object-contain rounded">
                <span class="text-[9.5px] font-bold text-brand-700 text-center mt-0.5">0905.457.936</span>
              </div>
            </div>

          </div>

          <!-- Nút chuyển Banner Trái / Phải chuẩn Flatsome -->
          <button type="button" onclick="prevSlide()" aria-label="Slide trước" class="absolute left-2 top-1/2 -translate-y-1/2 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/30 hover:bg-black/50 text-white flex items-center justify-center transition z-20">
            <i class="fa-solid fa-chevron-left text-xs"></i>
          </button>
          <button type="button" onclick="nextSlide()" aria-label="Slide tiếp theo" class="absolute right-2 top-1/2 -translate-y-1/2 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/30 hover:bg-black/50 text-white flex items-center justify-center transition z-20">
            <i class="fa-solid fa-chevron-right text-xs"></i>
          </button>

          <!-- Chấm tròn chỉ báo Slide -->
          <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 flex items-center gap-2 z-20">
            <button type="button" onclick="goToSlide(0)" id="dot-0" aria-label="Banner 1" class="w-6 h-2 rounded-full bg-white transition-all"></button>
            <button type="button" onclick="goToSlide(1)" id="dot-1" aria-label="Banner 2" class="w-2 h-2 rounded-full bg-white/50 transition-all"></button>
          </div>

        </div>
      </div>
    </div>
  </section>

  <!-- ==================== 4 Ô CAM KẾT DỊCH VỤ GIỐNG WEB MẪU LOCNUOCDANANG.VN ==================== -->
  <section class="py-2">
    <div class="flatsome-container">
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-2.5 sm:gap-4">
        <div class="bg-white p-3 sm:p-4 rounded-xl border border-slate-200 flex items-center gap-3 shadow-sm">
          <div class="w-10 h-10 rounded-full bg-brand-50 text-brand-600 flex items-center justify-center shrink-0">
            <i class="fa-solid fa-award text-lg"></i>
          </div>
          <div>
            <h3 class="text-xs sm:text-sm font-bold text-slate-800">Cam kết chính hãng</h3>
            <p class="text-[11px] text-slate-500 leading-tight mt-0.5">Đền bù nếu phát hiện hàng giả, hàng nhái</p>
          </div>
        </div>
        <div class="bg-white p-3 sm:p-4 rounded-xl border border-slate-200 flex items-center gap-3 shadow-sm">
          <div class="w-10 h-10 rounded-full bg-brand-50 text-brand-600 flex items-center justify-center shrink-0">
            <i class="fa-solid fa-tags text-lg"></i>
          </div>
          <div>
            <h3 class="text-xs sm:text-sm font-bold text-slate-800">Chiết khấu hấp dẫn</h3>
            <p class="text-[11px] text-slate-500 leading-tight mt-0.5">Giá tốt nhất thị trường Đà Nẵng & Miền Trung</p>
          </div>
        </div>
        <div class="bg-white p-3 sm:p-4 rounded-xl border border-slate-200 flex items-center gap-3 shadow-sm">
          <div class="w-10 h-10 rounded-full bg-brand-50 text-brand-600 flex items-center justify-center shrink-0">
            <i class="fa-solid fa-truck-fast text-lg"></i>
          </div>
          <div>
            <h3 class="text-xs sm:text-sm font-bold text-slate-800">Giao & lắp miễn phí</h3>
            <p class="text-[11px] text-slate-500 leading-tight mt-0.5">Khảo sát và lắp đặt nhanh tại nội thành Đà Nẵng</p>
          </div>
        </div>
        <div class="bg-white p-3 sm:p-4 rounded-xl border border-slate-200 flex items-center gap-3 shadow-sm">
          <div class="w-10 h-10 rounded-full bg-brand-50 text-brand-600 flex items-center justify-center shrink-0">
            <i class="fa-solid fa-headset text-lg"></i>
          </div>
          <div>
            <h3 class="text-xs sm:text-sm font-bold text-slate-800">Bảo hành tận nơi 24/7</h3>
            <p class="text-[11px] text-slate-500 leading-tight mt-0.5">Đội ngũ kỹ thuật Water 4.0 giàu kinh nghiệm</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== DANH MỤC SẢN PHẨM TRANG CHỦ (CHỮ NHỎ GỌN, ĐẸP MẮT) ==================== -->
  <section class="py-4">
    <div class="flatsome-container">
      <div class="bg-white rounded-xl border border-slate-200 p-3 sm:p-4 shadow-sm">
        <div class="flatsome-section-title">
          <h2 class="text-sm sm:text-base">DANH MỤC SẢN PHẨM</h2>
          <span class="text-[11px] text-slate-500">Chọn nhanh danh mục</span>
        </div>
        <!-- Lưới danh mục chữ nhỏ gọn, cân đối trên cả máy tính và điện thoại -->
        <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2.5">
          <a href="#dm-loc-tong-karofi" class="group p-2.5 rounded-lg border border-slate-200 hover:border-brand-600 hover:bg-brand-50/40 transition flex flex-col items-center text-center">
            <div class="w-10 h-10 rounded-full bg-brand-50 text-brand-600 flex items-center justify-center mb-1.5 group-hover:bg-brand-600 group-hover:text-white transition">
              <i class="fa-solid fa-filter text-sm"></i>
            </div>
            <span class="text-[12px] font-semibold text-slate-800 group-hover:text-brand-600 leading-tight">Lọc tổng Karofi</span>
          </a>
          <a href="#dm-loc-ro-y-te" class="group p-2.5 rounded-lg border border-slate-200 hover:border-brand-600 hover:bg-brand-50/40 transition flex flex-col items-center text-center">
            <div class="w-10 h-10 rounded-full bg-brand-50 text-brand-600 flex items-center justify-center mb-1.5 group-hover:bg-brand-600 group-hover:text-white transition">
              <i class="fa-solid fa-hospital text-sm"></i>
            </div>
            <span class="text-[12px] font-semibold text-slate-800 group-hover:text-brand-600 leading-tight">Lọc nước RO y tế</span>
          </a>
          <a href="#dm-may-ion-kiem" class="group p-2.5 rounded-lg border border-slate-200 hover:border-brand-600 hover:bg-brand-50/40 transition flex flex-col items-center text-center">
            <div class="w-10 h-10 rounded-full bg-brand-50 text-brand-600 flex items-center justify-center mb-1.5 group-hover:bg-brand-600 group-hover:text-white transition">
              <i class="fa-solid fa-hand-holding-droplet text-sm"></i>
            </div>
            <span class="text-[12px] font-semibold text-slate-800 group-hover:text-brand-600 leading-tight">Máy tạo nước ion kiềm</span>
          </a>
          <a href="#dm-loc-nuoc-gia-dinh" class="group p-2.5 rounded-lg border border-slate-200 hover:border-brand-600 hover:bg-brand-50/40 transition flex flex-col items-center text-center">
            <div class="w-10 h-10 rounded-full bg-brand-50 text-brand-600 flex items-center justify-center mb-1.5 group-hover:bg-brand-600 group-hover:text-white transition">
              <i class="fa-solid fa-faucet-drip text-sm"></i>
            </div>
            <span class="text-[12px] font-semibold text-slate-800 group-hover:text-brand-600 leading-tight">Máy lọc nước gia đình</span>
          </a>
          <a href="#dm-vat-lieu-loc" class="group p-2.5 rounded-lg border border-slate-200 hover:border-brand-600 hover:bg-brand-50/40 transition flex flex-col items-center text-center">
            <div class="w-10 h-10 rounded-full bg-brand-50 text-brand-600 flex items-center justify-center mb-1.5 group-hover:bg-brand-600 group-hover:text-white transition">
              <i class="fa-solid fa-layer-group text-sm"></i>
            </div>
            <span class="text-[12px] font-semibold text-slate-800 group-hover:text-brand-600 leading-tight">Vật liệu lọc nước</span>
          </a>
          <a href="#du-an-da-nang" class="group p-2.5 rounded-lg border border-slate-200 hover:border-brand-600 hover:bg-brand-50/40 transition flex flex-col items-center text-center">
            <div class="w-10 h-10 rounded-full bg-brand-50 text-brand-600 flex items-center justify-center mb-1.5 group-hover:bg-brand-600 group-hover:text-white transition">
              <i class="fa-solid fa-Screwdriver-wrench text-sm"></i>
            </div>
            <span class="text-[12px] font-semibold text-slate-800 group-hover:text-brand-600 leading-tight">Dự án tại Đà Nẵng</span>
          </a>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== DANH MỤC 1: LỌC TỔNG ĐẦU NGUỒN KAROFI ==================== -->
  <!-- Sản phẩm chia 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4). Có % giảm giá góc trên bên trái giống Flatsome. Tên sản phẩm hiển thị đầy đủ không tràn không mất chữ -->
  <section id="dm-loc-tong-karofi" class="py-3">
    <div class="flatsome-container">
      <div class="bg-white rounded-xl border border-slate-200 p-3 sm:p-5 shadow-sm">
        <div class="flatsome-section-title">
          <h2 class="text-sm sm:text-base">LỌC TỔNG KAROFI & ĐẦU NGUỒN</h2>
          <a href="#form-bao-gia" class="text-xs font-semibold text-brand-600 hover:underline flex items-center gap-1">
            Xem tất cả <i class="fa-solid fa-angle-right text-[10px]"></i>
          </a>
        </div>

        <div class="grid grid-cols-2 lg:grid-cols-4 gap-2.5 sm:gap-4">
          
          <!-- Sản phẩm 1 (File Drive 1: 1RyN2L6jXsXypf7BlkoRmelwy8nRZN3Wa) -->
          <div class="product-card bg-white border border-slate-200 rounded-xl overflow-hidden flex flex-col justify-between hover:shadow-md transition">
            <div>
              <div class="relative bg-slate-50 p-2 flex items-center justify-center h-40 sm:h-52 border-b border-slate-100">
                <div class="flatsome-badge-sale">-15%</div>
                <img src="https://drive.google.com/thumbnail?id=1RyN2L6jXsXypf7BlkoRmelwy8nRZN3Wa&sz=w700"
                     onerror="handleDriveImgError(this, '1RyN2L6jXsXypf7BlkoRmelwy8nRZN3Wa', 'Karofi KST-79')"
                     alt="Máy lọc nước đầu nguồn Karofi KST-79" class="max-h-full max-w-full object-contain">
              </div>
              <div class="p-2.5 sm:p-3.5">
                <h3 class="text-[12.5px] sm:text-sm font-semibold text-slate-800 leading-snug break-words">
                  Máy lọc nước đầu nguồn Karofi KST-79 chính hãng
                </h3>
              </div>
            </div>
            <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1">
              <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5 mb-2">
                <span class="text-[11px] sm:text-xs text-slate-400 line-through">82.000.000₫</span>
                <span class="text-xs sm:text-sm font-bold text-brand-sale">69.700.000₫</span>
              </div>
              <button type="button" onclick="selectProductForQuote('Máy lọc nước đầu nguồn Karofi KST-79 chính hãng')" class="w-full py-1.5 px-2 rounded-lg bg-brand-600 hover:bg-brand-700 text-white text-[11px] sm:text-xs font-semibold transition">
                Nhận báo giá
              </button>
            </div>
          </div>

          <!-- Sản phẩm 2 (File Drive 2: 1NfaePBKw2OBu8M9yWw7QarsrCAQpY8Mr) -->
          <div class="product-card bg-white border border-slate-200 rounded-xl overflow-hidden flex flex-col justify-between hover:shadow-md transition">
            <div>
              <div class="relative bg-slate-50 p-2 flex items-center justify-center h-40 sm:h-52 border-b border-slate-100">
                <div class="flatsome-badge-sale">-14%</div>
                <img src="https://drive.google.com/thumbnail?id=1NfaePBKw2OBu8M9yWw7QarsrCAQpY8Mr&sz=w700"
                     onerror="handleDriveImgError(this, '1NfaePBKw2OBu8M9yWw7QarsrCAQpY8Mr', 'Karofi KMF-68')"
                     alt="Máy lọc nước đầu nguồn Karofi KMF-68" class="max-h-full max-w-full object-contain">
              </div>
              <div class="p-2.5 sm:p-3.5">
                <h3 class="text-[12.5px] sm:text-sm font-semibold text-slate-800 leading-snug break-words">
                  Máy lọc nước đầu nguồn Karofi KMF-68 cao cấp
                </h3>
              </div>
            </div>
            <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1">
              <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5 mb-2">
                <span class="text-[11px] sm:text-xs text-slate-400 line-through">79.000.000₫</span>
                <span class="text-xs sm:text-sm font-bold text-brand-sale">68.000.000₫</span>
              </div>
              <button type="button" onclick="selectProductForQuote('Máy lọc nước đầu nguồn Karofi KMF-68 cao cấp')" class="w-full py-1.5 px-2 rounded-lg bg-brand-600 hover:bg-brand-700 text-white text-[11px] sm:text-xs font-semibold transition">
                Nhận báo giá
              </button>
            </div>
          </div>

          <!-- Sản phẩm 3 (File Drive 3: 19BjKIk2YsT1jGRhGC-nQC80GMshO8DkM) -->
          <div class="product-card bg-white border border-slate-200 rounded-xl overflow-hidden flex flex-col justify-between hover:shadow-md transition">
            <div>
              <div class="relative bg-slate-50 p-2 flex items-center justify-center h-40 sm:h-52 border-b border-slate-100">
                <div class="flatsome-badge-sale">-16%</div>
                <img src="https://drive.google.com/thumbnail?id=19BjKIk2YsT1jGRhGC-nQC80GMshO8DkM&sz=w700"
                     onerror="handleDriveImgError(this, '19BjKIk2YsT1jGRhGC-nQC80GMshO8DkM', 'Karofi KTF-662')"
                     alt="Hệ thống lọc tổng Karofi KTF 662 ECO" class="max-h-full max-w-full object-contain">
              </div>
              <div class="p-2.5 sm:p-3.5">
                <h3 class="text-[12.5px] sm:text-sm font-semibold text-slate-800 leading-snug break-words">
                  Hệ thống lọc tổng đầu nguồn Karofi KTF 662 ECO
                </h3>
              </div>
            </div>
            <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1">
              <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5 mb-2">
                <span class="text-[11px] sm:text-xs text-slate-400 line-through">74.000.000₫</span>
                <span class="text-xs sm:text-sm font-bold text-brand-sale">62.000.000₫</span>
              </div>
              <button type="button" onclick="selectProductForQuote('Hệ thống lọc tổng đầu nguồn Karofi KTF 662 ECO')" class="w-full py-1.5 px-2 rounded-lg bg-brand-600 hover:bg-brand-700 text-white text-[11px] sm:text-xs font-semibold transition">
                Nhận báo giá
              </button>
            </div>
          </div>

          <!-- Sản phẩm 4 (File Drive 4: 1nu7ewhDmuXuax5M-z1HJGfMmkGxdJ_c1) -->
          <div class="product-card bg-white border border-slate-200 rounded-xl overflow-hidden flex flex-col justify-between hover:shadow-md transition">
            <div>
              <div class="relative bg-slate-50 p-2 flex items-center justify-center h-40 sm:h-52 border-b border-slate-100">
                <div class="flatsome-badge-sale">-20%</div>
                <img src="https://drive.google.com/thumbnail?id=1nu7ewhDmuXuax5M-z1HJGfMmkGxdJ_c1&sz=w700"
                     onerror="handleDriveImgError(this, '1nu7ewhDmuXuax5M-z1HJGfMmkGxdJ_c1', 'Lọc Tổng KTF-552')"
                     alt="Hệ thống lọc tổng Karofi KTF 552 ECO" class="max-h-full max-w-full object-contain">
              </div>
              <div class="p-2.5 sm:p-3.5">
                <h3 class="text-[12.5px] sm:text-sm font-semibold text-slate-800 leading-snug break-words">
                  Hệ thống lọc tổng đầu nguồn Karofi KTF 552 ECO
                </h3>
              </div>
            </div>
            <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1">
              <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5 mb-2">
                <span class="text-[11px] sm:text-xs text-slate-400 line-through">59.000.000₫</span>
                <span class="text-xs sm:text-sm font-bold text-brand-sale">47.200.000₫</span>
              </div>
              <button type="button" onclick="selectProductForQuote('Hệ thống lọc tổng đầu nguồn Karofi KTF 552 ECO')" class="w-full py-1.5 px-2 rounded-lg bg-brand-600 hover:bg-brand-700 text-white text-[11px] sm:text-xs font-semibold transition">
                Nhận báo giá
              </button>
            </div>
          </div>

        </div>
      </div>
    </div>
  </section>

  <!-- ==================== DANH MỤC 2: LỌC NƯỚC RO Y TẾ & CÔNG NGHIỆP ==================== -->
  <section id="dm-loc-ro-y-te" class="py-3">
    <div class="flatsome-container">
      <div class="bg-white rounded-xl border border-slate-200 p-3 sm:p-5 shadow-sm">
        <div class="flatsome-section-title">
          <h2 class="text-sm sm:text-base">LỌC NƯỚC RO Y TẾ & BỆNH VIỆN</h2>
          <a href="#form-bao-gia" class="text-xs font-semibold text-brand-600 hover:underline flex items-center gap-1">
            Xem tất cả <i class="fa-solid fa-angle-right text-[10px]"></i>
          </a>
        </div>

        <div class="grid grid-cols-2 lg:grid-cols-4 gap-2.5 sm:gap-4">
          
          <!-- Sản phẩm 5 (File Drive 5: 1gEsKV9IPQwNpI-LDtRw384ElM2Co3yDW) -->
          <div class="product-card bg-white border border-slate-200 rounded-xl overflow-hidden flex flex-col justify-between hover:shadow-md transition">
            <div>
              <div class="relative bg-slate-50 p-2 flex items-center justify-center h-40 sm:h-52 border-b border-slate-100">
                <div class="flatsome-badge-sale">-12%</div>
                <img src="https://drive.google.com/thumbnail?id=1gEsKV9IPQwNpI-LDtRw384ElM2Co3yDW&sz=w700"
                     onerror="handleDriveImgError(this, '1gEsKV9IPQwNpI-LDtRw384ElM2Co3yDW', 'RO Chạy Thận')"
                     alt="Hệ thống nước RO chạy thận 2000L/h" class="max-h-full max-w-full object-contain">
              </div>
              <div class="p-2.5 sm:p-3.5">
                <h3 class="text-[12.5px] sm:text-sm font-semibold text-slate-800 leading-snug break-words">
                  Hệ thống lọc nước RO chạy thận nhân tạo 2000L/h
                </h3>
              </div>
            </div>
            <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1">
              <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5 mb-2">
                <span class="text-[11px] sm:text-xs text-slate-400 line-through">185.000.000₫</span>
                <span class="text-xs sm:text-sm font-bold text-brand-sale">162.800.000₫</span>
              </div>
              <button type="button" onclick="selectProductForQuote('Hệ thống lọc nước RO chạy thận nhân tạo 2000L/h')" class="w-full py-1.5 px-2 rounded-lg bg-brand-600 hover:bg-brand-700 text-white text-[11px] sm:text-xs font-semibold transition">
                Nhận báo giá
              </button>
            </div>
          </div>

          <!-- Sản phẩm 6 (File Drive 6: 1K_VpuMVSqlqKKxAY7cdJvkFltfGMs2QF) -->
          <div class="product-card bg-white border border-slate-200 rounded-xl overflow-hidden flex flex-col justify-between hover:shadow-md transition">
            <div>
              <div class="relative bg-slate-50 p-2 flex items-center justify-center h-40 sm:h-52 border-b border-slate-100">
                <div class="flatsome-badge-sale">-15%</div>
                <img src="https://drive.google.com/thumbnail?id=1K_VpuMVSqlqKKxAY7cdJvkFltfGMs2QF&sz=w700"
                     onerror="handleDriveImgError(this, '1K_VpuMVSqlqKKxAY7cdJvkFltfGMs2QF', 'RO Phòng Mổ')"
                     alt="Hệ thống nước cấp cho phòng mổ" class="max-h-full max-w-full object-contain">
              </div>
              <div class="p-2.5 sm:p-3.5">
                <h3 class="text-[12.5px] sm:text-sm font-semibold text-slate-800 leading-snug break-words">
                  Hệ thống lọc RO cấp nước vô trùng cho phòng mổ
                </h3>
              </div>
            </div>
            <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1">
              <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5 mb-2">
                <span class="text-[11px] sm:text-xs text-slate-400 line-through">96.000.000₫</span>
                <span class="text-xs sm:text-sm font-bold text-brand-sale">81.600.000₫</span>
              </div>
              <button type="button" onclick="selectProductForQuote('Hệ thống lọc RO cấp nước vô trùng cho phòng mổ')" class="w-full py-1.5 px-2 rounded-lg bg-brand-600 hover:bg-brand-700 text-white text-[11px] sm:text-xs font-semibold transition">
                Nhận báo giá
              </button>
            </div>
          </div>

          <!-- Sản phẩm 7 (File Drive 7: 1dJCH1Sme20twAgMT74p1sa13g0BX8UwP) -->
          <div class="product-card bg-white border border-slate-200 rounded-xl overflow-hidden flex flex-col justify-between hover:shadow-md transition">
            <div>
              <div class="relative bg-slate-50 p-2 flex items-center justify-center h-40 sm:h-52 border-b border-slate-100">
                <div class="flatsome-badge-sale">-18%</div>
                <img src="https://drive.google.com/thumbnail?id=1dJCH1Sme20twAgMT74p1sa13g0BX8UwP&sz=w700"
                     onerror="handleDriveImgError(this, '1dJCH1Sme20twAgMT74p1sa13g0BX8UwP', 'RO Xét Nghiệm')"
                     alt="Hệ thống cấp nước phòng xét nghiệm hóa lý" class="max-h-full max-w-full object-contain">
              </div>
              <div class="p-2.5 sm:p-3.5">
                <h3 class="text-[12.5px] sm:text-sm font-semibold text-slate-800 leading-snug break-words">
                  Hệ thống cấp nước RO-DI phòng xét nghiệm hóa lý
                </h3>
              </div>
            </div>
            <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1">
              <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5 mb-2">
                <span class="text-[11px] sm:text-xs text-slate-400 line-through">68.000.000₫</span>
                <span class="text-xs sm:text-sm font-bold text-brand-sale">55.700.000₫</span>
              </div>
              <button type="button" onclick="selectProductForQuote('Hệ thống cấp nước RO-DI phòng xét nghiệm hóa lý')" class="w-full py-1.5 px-2 rounded-lg bg-brand-600 hover:bg-brand-700 text-white text-[11px] sm:text-xs font-semibold transition">
                Nhận báo giá
              </button>
            </div>
          </div>

          <!-- Sản phẩm 8 (File Drive 8: 1dpB1awfhzdIFvpGpjsQakyUzhz-1T96D) -->
          <div class="product-card bg-white border border-slate-200 rounded-xl overflow-hidden flex flex-col justify-between hover:shadow-md transition">
            <div>
              <div class="relative bg-slate-50 p-2 flex items-center justify-center h-40 sm:h-52 border-b border-slate-100">
                <div class="flatsome-badge-sale">-16%</div>
                <img src="https://drive.google.com/thumbnail?id=1dpB1awfhzdIFvpGpjsQakyUzhz-1T96D&sz=w700"
                     onerror="handleDriveImgError(this, '1dpB1awfhzdIFvpGpjsQakyUzhz-1T96D', 'RO Bệnh Viện')"
                     alt="Hệ thống nước uống bệnh viện" class="max-h-full max-w-full object-contain">
              </div>
              <div class="p-2.5 sm:p-3.5">
                <h3 class="text-[12.5px] sm:text-sm font-semibold text-slate-800 leading-snug break-words">
                  Hệ thống lọc nước uống trực tiếp bệnh viện & trường học
                </h3>
              </div>
            </div>
            <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1">
              <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5 mb-2">
                <span class="text-[11px] sm:text-xs text-slate-400 line-through">45.000.000₫</span>
                <span class="text-xs sm:text-sm font-bold text-brand-sale">37.800.000₫</span>
              </div>
              <button type="button" onclick="selectProductForQuote('Hệ thống lọc nước uống trực tiếp bệnh viện & trường học')" class="w-full py-1.5 px-2 rounded-lg bg-brand-600 hover:bg-brand-700 text-white text-[11px] sm:text-xs font-semibold transition">
                Nhận báo giá
              </button>
            </div>
          </div>

        </div>
      </div>
    </div>
  </section>

  <!-- ==================== DANH MỤC 3: MÁY TẠO NƯỚC ION KIỀM & MÁY LỌC NƯỚC GIA ĐÌNH & VẬT LIỆU LỌC ==================== -->
  <section id="dm-may-ion-kiem" class="py-3">
    <div class="flatsome-container">
      <div id="dm-loc-nuoc-gia-dinh" class="bg-white rounded-xl border border-slate-200 p-3 sm:p-5 shadow-sm">
        <div id="dm-vat-lieu-loc" class="flatsome-section-title">
          <h2 class="text-sm sm:text-base">MÁY TẠO NƯỚC ION KIỀM & LỌC NƯỚC GIA ĐÌNH</h2>
          <a href="#form-bao-gia" class="text-xs font-semibold text-brand-600 hover:underline flex items-center gap-1">
            Xem tất cả <i class="fa-solid fa-angle-right text-[10px]"></i>
          </a>
        </div>

        <div class="grid grid-cols-2 lg:grid-cols-4 gap-2.5 sm:gap-4">
          
          <!-- Sản phẩm 9 (File Drive 9: 1duMuOfXOjVtTQ-AJ2Kmium-rO6DT-x_V) -->
          <div class="product-card bg-white border border-slate-200 rounded-xl overflow-hidden flex flex-col justify-between hover:shadow-md transition">
            <div>
              <div class="relative bg-slate-50 p-2 flex items-center justify-center h-40 sm:h-52 border-b border-slate-100">
                <div class="flatsome-badge-sale">-26%</div>
                <img src="https://drive.google.com/thumbnail?id=1duMuOfXOjVtTQ-AJ2Kmium-rO6DT-x_V&sz=w700"
                     onerror="handleDriveImgError(this, '1duMuOfXOjVtTQ-AJ2Kmium-rO6DT-x_V', 'Trim Ion Hyper')"
                     alt="Máy tạo nước ion kiềm Trim Ion Hyper" class="max-h-full max-w-full object-contain">
              </div>
              <div class="p-2.5 sm:p-3.5">
                <h3 class="text-[12.5px] sm:text-sm font-semibold text-slate-800 leading-snug break-words">
                  Máy lọc nước tạo Ion Kiềm Trim Ion Hyper Nhật Bản
                </h3>
              </div>
            </div>
            <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1">
              <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5 mb-2">
                <span class="text-[11px] sm:text-xs text-slate-400 line-through">63.000.000₫</span>
                <span class="text-xs sm:text-sm font-bold text-brand-sale">46.500.000₫</span>
              </div>
              <button type="button" onclick="selectProductForQuote('Máy lọc nước tạo Ion Kiềm Trim Ion Hyper Nhật Bản')" class="w-full py-1.5 px-2 rounded-lg bg-brand-600 hover:bg-brand-700 text-white text-[11px] sm:text-xs font-semibold transition">
                Nhận báo giá
              </button>
            </div>
          </div>

          <!-- Sản phẩm 10 (File Drive 10: 1HIaAdL4GNG66awtaThPLxXBPPhILnGJB) -->
          <div class="product-card bg-white border border-slate-200 rounded-xl overflow-hidden flex flex-col justify-between hover:shadow-md transition">
            <div>
              <div class="relative bg-slate-50 p-2 flex items-center justify-center h-40 sm:h-52 border-b border-slate-100">
                <div class="flatsome-badge-sale">-44%</div>
                <img src="https://drive.google.com/thumbnail?id=1HIaAdL4GNG66awtaThPLxXBPPhILnGJB&sz=w700"
                     onerror="handleDriveImgError(this, '1HIaAdL4GNG66awtaThPLxXBPPhILnGJB', 'Ion Kiềm 9 Tấm')"
                     alt="Máy Ion Kiềm 9 tấm điện cực" class="max-h-full max-w-full object-contain">
              </div>
              <div class="p-2.5 sm:p-3.5">
                <h3 class="text-[12.5px] sm:text-sm font-semibold text-slate-800 leading-snug break-words">
                  Máy tạo nước Ion Kiềm 9 tấm điện cực Titanium phủ Platinum
                </h3>
              </div>
            </div>
            <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1">
              <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5 mb-2">
                <span class="text-[11px] sm:text-xs text-slate-400 line-through">80.000.000₫</span>
                <span class="text-xs sm:text-sm font-bold text-brand-sale">45.000.000₫</span>
              </div>
              <button type="button" onclick="selectProductForQuote('Máy tạo nước Ion Kiềm 9 tấm điện cực Titanium phủ Platinum')" class="w-full py-1.5 px-2 rounded-lg bg-brand-600 hover:bg-brand-700 text-white text-[11px] sm:text-xs font-semibold transition">
                Nhận báo giá
              </button>
            </div>
          </div>

          <!-- Sản phẩm 11 (File Drive 11: 1fKSrPpoUsjKzHTXAMF4NgdlXQaYimvUY) -->
          <div class="product-card bg-white border border-slate-200 rounded-xl overflow-hidden flex flex-col justify-between hover:shadow-md transition">
            <div>
              <div class="relative bg-slate-50 p-2 flex items-center justify-center h-40 sm:h-52 border-b border-slate-100">
                <div class="flatsome-badge-sale">-21%</div>
                <img src="https://drive.google.com/thumbnail?id=1fKSrPpoUsjKzHTXAMF4NgdlXQaYimvUY&sz=w700"
                     onerror="handleDriveImgError(this, '1fKSrPpoUsjKzHTXAMF4NgdlXQaYimvUY', 'Máy Lọc Gia Đình')"
                     alt="Máy lọc nước RO Nóng Nguội Lạnh gia đình" class="max-h-full max-w-full object-contain">
              </div>
              <div class="p-2.5 sm:p-3.5">
                <h3 class="text-[12.5px] sm:text-sm font-semibold text-slate-800 leading-snug break-words">
                  Máy lọc nước RO nóng nguội lạnh gia đình Water 4.0 Hydrogen
                </h3>
              </div>
            </div>
            <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1">
              <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5 mb-2">
                <span class="text-[11px] sm:text-xs text-slate-400 line-through">13.800.000₫</span>
                <span class="text-xs sm:text-sm font-bold text-brand-sale">10.900.000₫</span>
              </div>
              <button type="button" onclick="selectProductForQuote('Máy lọc nước RO nóng nguội lạnh gia đình Water 4.0 Hydrogen')" class="w-full py-1.5 px-2 rounded-lg bg-brand-600 hover:bg-brand-700 text-white text-[11px] sm:text-xs font-semibold transition">
                Nhận báo giá
              </button>
            </div>
          </div>

          <!-- Sản phẩm 12 (File Drive 12: 147f4zcIZDY2qiniRU1d6PkYaMwgIn2DP) -->
          <div class="product-card bg-white border border-slate-200 rounded-xl overflow-hidden flex flex-col justify-between hover:shadow-md transition">
            <div>
              <div class="relative bg-slate-50 p-2 flex items-center justify-center h-40 sm:h-52 border-b border-slate-100">
                <div class="flatsome-badge-sale">-20%</div>
                <img src="https://drive.google.com/thumbnail?id=147f4zcIZDY2qiniRU1d6PkYaMwgIn2DP&sz=w700"
                     onerror="handleDriveImgError(this, '147f4zcIZDY2qiniRU1d6PkYaMwgIn2DP', 'Vật Liệu Lọc Nước')"
                     alt="Bộ vật liệu lọc nước đầu nguồn ODM 2F Than Hoạt Tính" class="max-h-full max-w-full object-contain">
              </div>
              <div class="p-2.5 sm:p-3.5">
                <h3 class="text-[12.5px] sm:text-sm font-semibold text-slate-800 leading-snug break-words">
                  Trọn bộ vật liệu lọc tổng đầu nguồn (Than hoạt tính, Cát Mangan, Cation)
                </h3>
              </div>
            </div>
            <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1">
              <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5 mb-2">
                <span class="text-[11px] sm:text-xs text-slate-400 line-through">4.500.000₫</span>
                <span class="text-xs sm:text-sm font-bold text-brand-sale">3.600.000₫</span>
              </div>
              <button type="button" onclick="selectProductForQuote('Trọn bộ vật liệu lọc tổng đầu nguồn (Than hoạt tính, Cát Mangan, Cation)')" class="w-full py-1.5 px-2 rounded-lg bg-brand-600 hover:bg-brand-700 text-white text-[11px] sm:text-xs font-semibold transition">
                Nhận báo giá
              </button>
            </div>
          </div>

        </div>
      </div>
    </div>
  </section>

  <!-- ==================== GIỚI THIỆU CÔNG TY TNHH MTV AN BÌNH DƯƠNG ==================== -->
  <section id="gioi-thieu" class="py-3">
    <div class="flatsome-container">
      <div class="bg-white rounded-xl border border-slate-200 p-4 sm:p-6 shadow-sm">
        <div class="flatsome-section-title">
          <h2 class="text-sm sm:text-base">VỀ CÔNG TY TNHH MTV AN BÌNH DƯƠNG (WATER 4.0)</h2>
          <span class="text-xs text-brand-600 font-semibold">MST: 0402001807</span>
        </div>
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-center">
          <div class="lg:col-span-7 text-xs sm:text-sm text-slate-600 space-y-2.5 leading-relaxed">
            <p class="font-bold text-slate-800 text-sm sm:text-base">
              Đơn vị chuyên tư vấn, thiết kế và thi công hệ thống lọc nước hàng đầu tại TP Đà Nẵng & Khu vực Miền Trung.
            </p>
            <p>
              <strong>CÔNG TY TNHH MTV AN BÌNH DƯƠNG</strong> (Thương hiệu <strong>Water 4.0</strong> - Website: <strong>anbinhduong.com</strong>) có trụ sở tại <strong>25 Cẩm Nam 6, Phường Hòa Xuân, TP Đà Nẵng</strong>. Chúng tôi chuyên phân phối và lắp đặt hệ thống lọc tổng đầu nguồn Karofi, hệ thống lọc nước RO Y tế cho bệnh viện/phòng khám, máy tạo nước Ion kiềm giàu Hydro và máy lọc nước gia đình chính hãng.
            </p>
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-2 pt-1 text-xs">
              <div class="flex items-center gap-2 bg-slate-50 p-2.5 rounded-lg border border-slate-200">
                <i class="fa-solid fa-circle-check text-brand-600"></i>
                <span>Kiểm tra chất lượng nước miễn phí tận nhà</span>
              </div>
              <div class="flex items-center gap-2 bg-slate-50 p-2.5 rounded-lg border border-slate-200">
                <i class="fa-solid fa-circle-check text-brand-600"></i>
                <span>Nước đầu ra đạt quy chuẩn QCVN 6-1:2010/BYT</span>
              </div>
              <div class="flex items-center gap-2 bg-slate-50 p-2.5 rounded-lg border border-slate-200">
                <i class="fa-solid fa-circle-check text-brand-600"></i>
                <span>Lắp đặt thẩm mỹ, gọn gàng, đúng tiến độ</span>
              </div>
              <div class="flex items-center gap-2 bg-slate-50 p-2.5 rounded-lg border border-slate-200">
                <i class="fa-solid fa-circle-check text-brand-600"></i>
                <span>Nhắc lịch thay lõi và bảo trì định kỳ tự động</span>
              </div>
            </div>
          </div>
          <div class="lg:col-span-5 grid grid-cols-2 gap-2.5">
            <div class="bg-slate-50 p-2 rounded-xl border border-slate-200 flex flex-col items-center">
              <img src="https://drive.google.com/thumbnail?id=19BjKIk2YsT1jGRhGC-nQC80GMshO8DkM&sz=w500"
                   onerror="handleDriveImgError(this, '19BjKIk2YsT1jGRhGC-nQC80GMshO8DkM', 'Thi Công Lọc Tổng')"
                   alt="Thi công thực tế An Bình Dương" class="h-32 w-full object-contain rounded">
              <span class="text-[11px] font-semibold text-slate-700 mt-1.5 text-center">Lọc tổng biệt thự Hòa Xuân</span>
            </div>
            <div class="bg-slate-50 p-2 rounded-xl border border-slate-200 flex flex-col items-center">
              <img src="https://drive.google.com/thumbnail?id=1K_VpuMVSqlqKKxAY7cdJvkFltfGMs2QF&sz=w500"
                   onerror="handleDriveImgError(this, '1K_VpuMVSqlqKKxAY7cdJvkFltfGMs2QF', 'Hệ Thống RO')"
                   alt="Hệ thống RO công nghiệp Đà Nẵng" class="h-32 w-full object-contain rounded">
              <span class="text-[11px] font-semibold text-slate-700 mt-1.5 text-center">Hệ thống RO Y tế & Công nghiệp</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== DỰ ÁN THI CÔNG THỰC TẾ TẠI ĐÀ NẴNG ==================== -->
  <section id="du-an-da-nang" class="py-3">
    <div class="flatsome-container">
      <div class="bg-white rounded-xl border border-slate-200 p-3 sm:p-5 shadow-sm">
        <div class="flatsome-section-title">
          <h2 class="text-sm sm:text-base">DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG</h2>
          <span class="text-xs text-slate-500">Hình ảnh lắp đặt thực tế</span>
        </div>

        <div class="grid grid-cols-2 lg:grid-cols-4 gap-2.5 sm:gap-4">
          <div class="border border-slate-200 rounded-xl overflow-hidden bg-slate-50/50 flex flex-col justify-between">
            <div class="h-36 sm:h-44 bg-white p-2 flex items-center justify-center border-b border-slate-200">
              <img src="https://drive.google.com/thumbnail?id=1RyN2L6jXsXypf7BlkoRmelwy8nRZN3Wa&sz=w600"
                   onerror="handleDriveImgError(this, '1RyN2L6jXsXypf7BlkoRmelwy8nRZN3Wa', 'Dự Án Hòa Xuân')"
                   alt="Dự án lọc tổng Khu đô thị Hòa Xuân Đà Nẵng" class="max-h-full max-w-full object-contain">
            </div>
            <div class="p-2.5 sm:p-3">
              <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 leading-snug">
                Lắp đặt hệ thống lọc tổng Karofi tại KĐT Sinh thái Hòa Xuân, Cẩm Lệ, Đà Nẵng
              </h3>
              <p class="text-[11px] text-slate-500 mt-1">Xử lý nước máy sinh hoạt đạt chuẩn cao cấp cho biệt thự gia đình.</p>
            </div>
          </div>

          <div class="border border-slate-200 rounded-xl overflow-hidden bg-slate-50/50 flex flex-col justify-between">
            <div class="h-36 sm:h-44 bg-white p-2 flex items-center justify-center border-b border-slate-200">
              <img src="https://drive.google.com/thumbnail?id=1gEsKV9IPQwNpI-LDtRw384ElM2Co3yDW&sz=w600"
                   onerror="handleDriveImgError(this, '1gEsKV9IPQwNpI-LDtRw384ElM2Co3yDW', 'Dự Án RO Y Tế')"
                   alt="Dự án lọc nước RO Y tế tại Quận Hải Châu Đà Nẵng" class="max-h-full max-w-full object-contain">
            </div>
            <div class="p-2.5 sm:p-3">
              <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 leading-snug">
                Thi công hệ thống lọc nước RO Y tế phòng khám đa khoa tại Quận Hải Châu, Đà Nẵng
              </h3>
              <p class="text-[11px] text-slate-500 mt-1">Cung cấp nguồn nước tinh khiết vô trùng phục vụ xét nghiệm và y tế.</p>
            </div>
          </div>

          <div class="border border-slate-200 rounded-xl overflow-hidden bg-slate-50/50 flex flex-col justify-between">
            <div class="h-36 sm:h-44 bg-white p-2 flex items-center justify-center border-b border-slate-200">
              <img src="https://drive.google.com/thumbnail?id=1duMuOfXOjVtTQ-AJ2Kmium-rO6DT-x_V&sz=w600"
                   onerror="handleDriveImgError(this, '1duMuOfXOjVtTQ-AJ2Kmium-rO6DT-x_V', 'Dự Án Euro Village')"
                   alt="Dự án máy tạo nước Ion kiềm tại Sơn Trà Đà Nẵng" class="max-h-full max-w-full object-contain">
            </div>
            <div class="p-2.5 sm:p-3">
              <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 leading-snug">
                Bàn giao máy tạo nước Ion Kiềm & lọc tổng tại khu biệt thự Euro Village, Sơn Trà, Đà Nẵng
              </h3>
              <p class="text-[11px] text-slate-500 mt-1">Giải pháp nước uống giàu Hydro chăm sóc sức khỏe toàn diện.</p>
            </div>
          </div>

          <div class="border border-slate-200 rounded-xl overflow-hidden bg-slate-50/50 flex flex-col justify-between">
            <div class="h-36 sm:h-44 bg-white p-2 flex items-center justify-center border-b border-slate-200">
              <img src="https://drive.google.com/thumbnail?id=1dpB1awfhzdIFvpGpjsQakyUzhz-1T96D&sz=w600"
                   onerror="handleDriveImgError(this, '1dpB1awfhzdIFvpGpjsQakyUzhz-1T96D', 'Dự Án Trường Học')"
                   alt="Dự án hệ thống lọc nước bán công nghiệp Liên Chiểu Đà Nẵng" class="max-h-full max-w-full object-contain">
            </div>
            <div class="p-2.5 sm:p-3">
              <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 leading-snug">
                Lắp đặt hệ thống lọc nước RO công suất lớn cho trường học & xưởng sản xuất tại Đà Nẵng
              </h3>
              <p class="text-[11px] text-slate-500 mt-1">Đảm bảo lưu lượng nước uống trực tiếp ổn định cho 500+ người.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ ==================== -->
  <section id="form-bao-gia" class="py-3">
    <div class="flatsome-container">
      <div class="bg-gradient-to-r from-brand-700 to-brand-600 rounded-xl p-4 sm:p-6 text-white shadow-sm">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
          
          <div class="lg:col-span-5 space-y-2.5">
            <span class="inline-block text-[11px] font-bold uppercase tracking-wider bg-white/15 px-3 py-1 rounded-full text-cyan-200">
              TƯ VẤN & KHẢO SÁT MIỄN PHÍ TẠI ĐÀ NẴNG
            </span>
            <h2 class="text-base sm:text-xl font-extrabold leading-snug">
               ĐĂNG KÝ YÊU CẦU TƯ VẤN & NHẬN BÁO GIÁ ƯU ĐÃI
            </h2>
            <p class="text-xs sm:text-sm text-sky-100 leading-relaxed">
              Quý khách để lại thông tin hoặc sản phẩm quan tâm, kỹ thuật viên của <strong>CÔNG TY TNHH MTV AN BÌNH DƯƠNG</strong> sẽ liên hệ gửi bảng báo giá chi tiết và khảo sát nguồn nước tận nơi trong 15 phút.
            </p>
            <div class="pt-1 space-y-1.5 text-xs sm:text-sm text-white font-medium">
              <p><i class="fa-solid fa-phone-volume text-cyan-300 mr-2"></i> Hotline / Zalo: <strong>0905.457.936</strong></p>
              <p><i class="fa-solid fa-location-dot text-cyan-300 mr-2"></i> Địa chỉ: <strong>25 Cẩm Nam 6, Phường Hòa Xuân, TP Đà Nẵng</strong></p>
              <p><i class="fa-solid fa-globe text-cyan-300 mr-2"></i> Website: <strong>anbinhduong.com</strong></p>
            </div>
          </div>

          <div class="lg:col-span-7 bg-white rounded-xl p-4 sm:p-5 text-slate-800 shadow">
            <form id="quote-form" onsubmit="submitQuoteForm(event)" class="space-y-3">
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                <div>
                  <label class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên quý khách *</label>
                  <input id="q-name" type="text" required placeholder="Nhập họ và tên..." 
                    class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand-600">
                </div>
                <div>
                  <label class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                  <input id="q-phone" type="tel" required placeholder="Ví dụ: 0905xxxxxx" 
                    class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand-600">
                </div>
              </div>

              <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                <div>
                  <label class="block text-xs font-semibold text-slate-700 mb-1">Danh mục cần báo giá</label>
                  <select id="q-category" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand-600 bg-white">
                    <option value="Lọc tổng đầu nguồn Karofi">Lọc tổng đầu nguồn Karofi</option>
                    <option value="Hệ thống lọc nước RO Y tế">Hệ thống lọc nước RO Y tế</option>
                    <option value="Máy tạo nước Ion kiềm">Máy tạo nước Ion kiềm</option>
                    <option value="Máy lọc nước gia đình">Máy lọc nước gia đình</option>
                    <option value="Vật liệu lọc nước & Thay lõi">Vật liệu lọc nước & Thay lõi</option>
                  </select>
                </div>
                <div>
                  <label class="block text-xs font-semibold text-slate-700 mb-1">Địa chỉ lắp đặt (Quận/Phường)</label>
                  <input id="q-address" type="text" placeholder="Ví dụ: Hòa Xuân, Cẩm Lệ, Đà Nẵng" 
                    class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand-600">
                </div>
              </div>

              <div>
                <label class="block text-xs font-semibold text-slate-700 mb-1">Sản phẩm quan tâm / Yêu cầu chi tiết</label>
                <input id="q-note" type="text" placeholder="Nhập tên sản phẩm hoặc nhu cầu xử lý nước..." 
                  class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand-600">
              </div>

              <button type="submit" class="w-full py-2.5 px-4 bg-brand-600 hover:bg-brand-700 text-white font-bold text-xs sm:text-sm rounded-lg shadow transition flex items-center justify-center gap-2">
                <i class="fa-solid fa-paper-plane"></i> GỬI YÊU CẦU BÁO GIÁ NGAY
              </button>

              <!-- Thông báo gửi thành công hiển thị trực tiếp (Không dùng alert) -->
              <div id="quote-success-msg" class="hidden p-3 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs font-medium">
                <i class="fa-solid fa-circle-check text-emerald-600 mr-1"></i>
                Cảm ơn quý khách! Yêu cầu báo giá đã được ghi nhận. Bộ phận kỹ thuật Công ty TNHH MTV An Bình Dương (0905.457.936) sẽ liên hệ ngay.
              </div>
            </form>
          </div>

        </div>
      </div>
    </div>
  </section>

  <!-- ==================== DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC GIỐNG WEB MẪU) ==================== -->
  <section id="tin-tuc" class="py-3">
    <div class="flatsome-container">
      <div class="bg-white rounded-xl border border-slate-200 p-3 sm:p-5 shadow-sm">
        <div class="flatsome-section-title">
          <h2 class="text-sm sm:text-base">TIN TỨC & KIẾN THỨC LỌC NƯỚC</h2>
          <a href="#form-bao-gia" class="text-xs font-semibold text-brand-600 hover:underline">Xem tất cả</a>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-4">
          <article class="border border-slate-200 rounded-xl overflow-hidden hover:shadow-sm transition bg-white flex flex-col justify-between">
            <div>
              <div class="h-36 bg-slate-100 p-2 flex items-center justify-center border-b border-slate-100">
                <img src="https://drive.google.com/thumbnail?id=19BjKIk2YsT1jGRhGC-nQC80GMshO8DkM&sz=w500"
                     onerror="handleDriveImgError(this, '19BjKIk2YsT1jGRhGC-nQC80GMshO8DkM', 'Lọc Nước Sinh Hoạt')"
                     alt="Giải pháp cải thiện chất lượng nước máy sinh hoạt" class="max-h-full max-w-full object-contain">
              </div>
              <div class="p-3">
                <span class="text-[10px] text-brand-600 font-semibold">Kiến thức nước sạch</span>
                <h3 class="text-xs sm:text-sm font-bold text-slate-800 mt-1 leading-snug">
                  Giải pháp cải thiện chất lượng nước máy sinh hoạt cho gia đình tại Đà Nẵng
                </h3>
                <p class="text-[11px] text-slate-500 mt-1.5 leading-relaxed">
                  Lọc nước đầu nguồn giúp loại bỏ clo dư, kim loại nặng, cặn bẩn trong bồn chứa nước sân thượng, bảo vệ da tóc và thiết bị gia dụng.
                </p>
              </div>
            </div>
          </article>

          <article class="border border-slate-200 rounded-xl overflow-hidden hover:shadow-sm transition bg-white flex flex-col justify-between">
            <div>
              <div class="h-36 bg-slate-100 p-2 flex items-center justify-center border-b border-slate-100">
                <img src="https://drive.google.com/thumbnail?id=1fKSrPpoUsjKzHTXAMF4NgdlXQaYimvUY&sz=w500"
                     onerror="handleDriveImgError(this, '1fKSrPpoUsjKzHTXAMF4NgdlXQaYimvUY', 'Máy Lọc Nước Gia Đình')"
                     alt="Máy lọc nước gia đình bảo vệ sức khỏe" class="max-h-full max-w-full object-contain">
              </div>
              <div class="p-3">
                <span class="text-[10px] text-brand-600 font-semibold">Tư vấn gia đình</span>
                <h3 class="text-xs sm:text-sm font-bold text-slate-800 mt-1 leading-snug">
                  Máy lọc nước gia đình bảo vệ sức khỏe khỏi nguồn nước ô nhiễm
                </h3>
                <p class="text-[11px] text-slate-500 mt-1.5 leading-relaxed">
                  Chuyên gia lý giải vì sao nước trong vắt chưa chắc đã sạch và vai trò của màng lọc RO chuẩn y tế đối với sức khỏe.
                </p>
              </div>
            </div>
          </article>

          <article class="border border-slate-200 rounded-xl overflow-hidden hover:shadow-sm transition bg-white flex flex-col justify-between">
            <div>
              <div class="h-36 bg-slate-100 p-2 flex items-center justify-center border-b border-slate-100">
                <img src="https://drive.google.com/thumbnail?id=1HIaAdL4GNG66awtaThPLxXBPPhILnGJB&sz=w500"
                     onerror="handleDriveImgError(this, '1HIaAdL4GNG66awtaThPLxXBPPhILnGJB', 'Nước Ion Kiềm')"
                     alt="Uống nước Ion kiềm mỗi ngày" class="max-h-full max-w-full object-contain">
              </div>
              <div class="p-3">
                <span class="text-[10px] text-brand-600 font-semibold">Sức khỏe & Đời sống</span>
                <h3 class="text-xs sm:text-sm font-bold text-slate-800 mt-1 leading-snug">
                  Lợi ích của máy tạo nước Ion Kiềm giàu Hydro đối với sức khỏe gia đình
                </h3>
                <p class="text-[11px] text-slate-500 mt-1.5 leading-relaxed">
                  Nước điện giải Ion kiềm có độ pH 8.5 - 9.5 giúp trung hòa axit dư thừa, chống oxy hóa và hỗ trợ hệ tiêu hóa khỏe mạnh.
                </p>
              </div>
            </div>
          </article>

          <article class="border border-slate-200 rounded-xl overflow-hidden hover:shadow-sm transition bg-white flex flex-col justify-between">
            <div>
              <div class="h-36 bg-slate-100 p-2 flex items-center justify-center border-b border-slate-100">
                <img src="https://drive.google.com/thumbnail?id=147f4zcIZDY2qiniRU1d6PkYaMwgIn2DP&sz=w500"
                     onerror="handleDriveImgError(this, '147f4zcIZDY2qiniRU1d6PkYaMwgIn2DP', 'Thay Vật Liệu Lọc')"
                     alt="Thời gian thay vật liệu lọc nước đầu nguồn" class="max-h-full max-w-full object-contain">
              </div>
              <div class="p-3">
                <span class="text-[10px] text-brand-600 font-semibold">Hướng dẫn kỹ thuật</span>
                <h3 class="text-xs sm:text-sm font-bold text-slate-800 mt-1 leading-snug">
                  Khi nào cần hoàn nguyên và thay thế vật liệu lọc nước đầu nguồn?
                </h3>
                <p class="text-[11px] text-slate-500 mt-1.5 leading-relaxed">
                  Hướng dẫn kiểm tra định kỳ hạt lọc đa năng ODM-2F, than hoạt tính, cát Mangan và hạt nhựa Cation để nguồn nước luôn đạt chuẩn.
                </p>
              </div>
            </div>
          </article>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== DANH MỤC CÁC ĐỐI TÁC CHIẾN LƯỢC ==================== -->
  <section id="doi-tac" class="py-3">
    <div class="flatsome-container">
      <div class="bg-white rounded-xl border border-slate-200 p-3 sm:p-5 shadow-sm">
        <div class="flatsome-section-title">
          <h2 class="text-sm sm:text-base">ĐỐI TÁC & THƯƠNG HIỆU PHÂN PHỐI</h2>
          <span class="text-xs text-slate-500">Hợp tác chính hãng</span>
        </div>
        <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2.5 text-center">
          <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center">
            <span class="text-sm font-extrabold text-brand-600 tracking-wide">KAROFI</span>
            <span class="text-[10px] text-slate-500 mt-0.5">Chuyên gia lọc nước</span>
          </div>
          <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center">
            <span class="text-sm font-extrabold text-brand-700 tracking-wide">TRIM ION</span>
            <span class="text-[10px] text-slate-500 mt-0.5">Nihon Trim Nhật Bản</span>
          </div>
          <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center">
            <span class="text-sm font-extrabold text-sky-700 tracking-wide">PENTAIR</span>
            <span class="text-[10px] text-slate-500 mt-0.5">Công nghệ lọc Mỹ</span>
          </div>
          <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center">
            <span class="text-sm font-extrabold text-brand-600 tracking-wide">DUPONT</span>
            <span class="text-[10px] text-slate-500 mt-0.5">Màng RO FilmTec USA</span>
          </div>
          <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center">
            <span class="text-sm font-extrabold text-teal-700 tracking-wide">KANGAROO</span>
            <span class="text-[10px] text-slate-500 mt-0.5">Máy lọc nước Hydrogen</span>
          </div>
          <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center">
            <span class="text-sm font-extrabold text-indigo-700 tracking-wide">CLEANSUI</span>
            <span class="text-[10px] text-slate-500 mt-0.5">Mitsubishi Nhật Bản</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== ĐƯA FANPAGE WATER 4.0 & BẢN ĐỒ GOOGLE MAP RA NGOÀI TRANG CHỦ ==================== -->
  <section id="lien-he-map" class="py-3 pb-6">
    <div class="flatsome-container">
      <div class="bg-white rounded-xl border border-slate-200 p-3 sm:p-5 shadow-sm">
        <div class="flatsome-section-title">
          <h2 class="text-sm sm:text-base">BẢN ĐỒ GOOGLE MAPS & FANPAGE TRÊN TRANG CHỦ</h2>
          <span class="text-xs text-brand-600 font-semibold">25 Cẩm Nam 6, P. Hòa Xuân, TP Đà Nẵng</span>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-4">
          
          <!-- Cột Google Maps trực tiếp ngoài trang chủ (7 cột) -->
          <div class="lg:col-span-7 flex flex-col justify-between border border-slate-200 rounded-xl overflow-hidden bg-slate-50">
            <div class="p-3 bg-white border-b border-slate-200 flex flex-wrap items-center justify-between gap-2">
              <div class="text-xs">
                <p class="font-bold text-slate-800">
                  <i class="fa-solid fa-location-dot text-brand-sale mr-1"></i>
                  TRỤ SỞ: 25 Cẩm Nam 6, Phường Hòa Xuân, TP Đà Nẵng
                </p>
                <p class="text-slate-500 text-[11px]">CÔNG TY TNHH MTV AN BÌNH DƯƠNG • Hotline: 0905.457.936</p>
              </div>
              <a href="https://www.google.com/maps/search/?api=1&query=25+C%E1%BA%A9m+Nam+6,+H%C3%B2a+Xu%C3%A2n,+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" 
                 class="px-3 py-1.5 rounded-lg bg-brand-600 hover:bg-brand-700 text-white text-xs font-semibold transition">
                <i class="fa-solid fa-diamond-turn-right mr-1"></i> Mở Google Maps
              </a>
            </div>
            <div class="w-full h-64 sm:h-72">
              <iframe 
                title="Bản đồ Công ty TNHH MTV An Bình Dương - 25 Cẩm Nam 6, Hòa Xuân, Đà Nẵng"
                src="https://maps.google.com/maps?q=25%20C%E1%BA%A9m%20Nam%206,%20H%C3%B2a%20Xu%C3%A2n,%20C%E1%BA%A9m%20L%E1%BB%87,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade">
              </iframe>
            </div>
          </div>

          <!-- Cột Fanpage Facebook Water 4.0 ngoài trang chủ (5 cột) -->
          <div class="lg:col-span-5 border border-slate-200 rounded-xl overflow-hidden bg-slate-50 flex flex-col justify-between">
            <div class="p-3 bg-white border-b border-slate-200 flex items-center justify-between gap-2">
              <div class="flex items-center gap-2">
                <i class="fa-brands fa-facebook text-blue-600 text-lg"></i>
                <div>
                  <h3 class="text-xs font-bold text-slate-800">FANPAGE FACEBOOK CHÍNH THỨC</h3>
                  <p class="text-[11px] text-slate-500">facebook.com/water4.0</p>
                </div>
              </div>
              <a href="https://www.facebook.com/water4.0" target="_blank" rel="noopener noreferrer"
                 class="px-2.5 py-1 rounded bg-blue-600 hover:bg-blue-700 text-white text-[11px] font-semibold transition">
                Theo dõi Trang
              </a>
            </div>

            <!-- Khung hiển thị Fanpage trực quan kết hợp Plugin Facebook -->
            <div class="p-3 flex-1 flex flex-col justify-between bg-white">
              <div class="rounded-lg border border-slate-200 p-3 bg-gradient-to-br from-brand-50 to-white">
                <div class="flex items-center gap-3 mb-2.5">
                  <div class="w-11 h-11 rounded-full bg-brand-600 text-white flex items-center justify-center font-extrabold text-sm shrink-0">
                    W4.0
                  </div>
                  <div>
                    <a href="https://www.facebook.com/water4.0" target="_blank" rel="noopener noreferrer" class="text-xs sm:text-sm font-bold text-brand-700 hover:underline flex items-center gap-1">
                      Water 4.0 - Lọc Nước An Bình Dương <i class="fa-solid fa-circle-check text-blue-500 text-xs"></i>
                    </a>
                    <p class="text-[11px] text-slate-500">Giải pháp Lọc tổng đầu nguồn, RO Y tế & Máy Ion kiềm Đà Nẵng</p>
                  </div>
                </div>
                <p class="text-xs text-slate-600 leading-relaxed mb-3">
                  Chuyên tư vấn, lắp đặt hệ thống lọc nước đầu nguồn Karofi, lọc nước RO bệnh viện, máy điện giải Ion kiềm chính hãng tại TP Đà Nẵng.
                </p>
                <div class="w-full overflow-hidden rounded border border-slate-200 bg-slate-50">
                  <iframe 
                    title="Fanpage Facebook Water 4.0"
                    src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fwater4.0&tabs&width=340&height=130&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true" 
                    width="100%" height="130" style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowfullscreen="true" allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                  </iframe>
                </div>
              </div>

              <div class="grid grid-cols-2 gap-2 mt-3">
                <a href="https://www.facebook.com/water4.0" target="_blank" rel="noopener noreferrer"
                   class="py-2 px-3 rounded-lg bg-blue-600 hover:bg-blue-700 text-white text-xs font-semibold text-center transition">
                  <i class="fa-brands fa-facebook-messenger mr-1"></i> Nhắn tin Fanpage
                </a>
                <a href="https://zalo.me/0905457936" target="_blank" rel="noopener noreferrer"
                   class="py-2 px-3 rounded-lg bg-sky-500 hover:bg-sky-600 text-white text-xs font-semibold text-center transition">
                  <i class="fa-solid fa-comment-dots mr-1"></i> Chat Zalo Ngay
                </a>
              </div>
            </div>
          </div>

        </div>
      </div>
    </div>
  </section>

  <!-- ==================== FOOTER CHUẨN FLATSOME GIỐNG WEB MẪU LOCNUOCDANANG.VN ==================== -->
  <footer class="bg-[#003966] text-white pt-8 pb-6 border-t-4 border-brand-accent">
    <div class="flatsome-container">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-12 gap-6 pb-6 border-b border-white/15">
        
        <!-- Cột 1: Thông tin công ty (5 cột) -->
        <div class="lg:col-span-5 space-y-2.5 text-xs sm:text-sm">
          <div class="flex items-center gap-2.5 mb-2">
            <div class="w-9 h-9 rounded-lg bg-white text-brand-600 flex items-center justify-center font-extrabold text-sm">
              ABD
            </div>
            <div>
              <h3 class="font-extrabold text-sm sm:text-base text-white">CÔNG TY TNHH MTV AN BÌNH DƯƠNG</h3>
              <p class="text-[11px] text-cyan-300">Giải Pháp Lọc Nước Thông Minh Water 4.0</p>
            </div>
          </div>
          <p class="text-sky-100 text-xs leading-relaxed">
            Chuyên phân phối, thi công lắp đặt Hệ thống lọc tổng đầu nguồn Karofi, Hệ thống lọc nước RO Y tế, Máy tạo nước Ion kiềm và Máy lọc nước gia đình chính hãng tại Đà Nẵng & Miền Trung.
          </p>
          <ul class="space-y-1.5 text-xs text-sky-100 pt-1">
            <li><i class="fa-solid fa-location-dot text-cyan-300 w-4"></i> <strong>Địa chỉ:</strong> 25 Cẩm Nam 6, Phường Hòa Xuân, TP Đà Nẵng</li>
            <li><i class="fa-solid fa-phone text-cyan-300 w-4"></i> <strong>Hotline / Zalo:</strong> <a href="tel:0905457936" class="text-white font-bold hover:underline">0905.457.936</a></li>
            <li><i class="fa-solid fa-id-card text-cyan-300 w-4"></i> <strong>Mã số thuế:</strong> 0402001807</li>
            <li><i class="fa-solid fa-globe text-cyan-300 w-4"></i> <strong>Website:</strong> <a href="https://anbinhduong.com" class="text-cyan-300 hover:underline">anbinhduong.com</a></li>
            <li><i class="fa-brands fa-facebook text-cyan-300 w-4"></i> <strong>Fanpage:</strong> <a href="https://www.facebook.com/water4.0" target="_blank" rel="noopener noreferrer" class="text-cyan-300 hover:underline">facebook.com/water4.0</a></li>
          </ul>
        </div>

        <!-- Cột 2: Danh mục sản phẩm (3 cột) -->
        <div class="lg:col-span-3 space-y-2 text-xs">
          <h4 class="text-sm font-bold uppercase tracking-wider text-cyan-300 mb-2">Danh mục sản phẩm</h4>
          <ul class="space-y-2 text-sky-100">
            <li><a href="#dm-loc-tong-karofi" class="hover:text-white transition"><i class="fa-solid fa-angle-right text-[10px] mr-1.5"></i>Lọc tổng đầu nguồn Karofi</a></li>
            <li><a href="#dm-loc-ro-y-te" class="hover:text-white transition"><i class="fa-solid fa-angle-right text-[10px] mr-1.5"></i>Hệ thống lọc nước RO Y tế</a></li>
            <li><a href="#dm-may-ion-kiem" class="hover:text-white transition"><i class="fa-solid fa-angle-right text-[10px] mr-1.5"></i>Máy tạo nước Ion kiềm</a></li>
            <li><a href="#dm-loc-nuoc-gia-dinh" class="hover:text-white transition"><i class="fa-solid fa-angle-right text-[10px] mr-1.5"></i>Máy lọc nước gia đình</a></li>
            <li><a href="#dm-vat-lieu-loc" class="hover:text-white transition"><i class="fa-solid fa-angle-right text-[10px] mr-1.5"></i>Vật liệu lọc nước chính hãng</a></li>
            <li><a href="#du-an-da-nang" class="hover:text-white transition"><i class="fa-solid fa-angle-right text-[10px] mr-1.5"></i>Dự án thi công tại Đà Nẵng</a></li>
          </ul>
        </div>

        <!-- Cột 3: Chính sách & Hướng dẫn (4 cột) -->
        <div class="lg:col-span-4 space-y-2 text-xs">
          <h4 class="text-sm font-bold uppercase tracking-wider text-cyan-300 mb-2">Hướng dẫn & Chính sách</h4>
          <ul class="space-y-2 text-sky-100">
            <li><a href="#form-bao-gia" class="hover:text-white transition"><i class="fa-solid fa-angle-right text-[10px] mr-1.5"></i>Hướng dẫn đặt hàng & khảo sát</a></li>
            <li><a href="#form-bao-gia" class="hover:text-white transition"><i class="fa-solid fa-angle-right text-[10px] mr-1.5"></i>Chính sách vận chuyển & lắp đặt miễn phí</a></li>
            <li><a href="#form-bao-gia" class="hover:text-white transition"><i class="fa-solid fa-angle-right text-[10px] mr-1.5"></i>Chính sách bảo hành & bảo trì định kỳ</a></li>
            <li><a href="#form-bao-gia" class="hover:text-white transition"><i class="fa-solid fa-angle-right text-[10px] mr-1.5"></i>Chính sách đổi trả & cam kết chính hãng</a></li>
            <li><a href="#form-bao-gia" class="hover:text-white transition"><i class="fa-solid fa-angle-right text-[10px] mr-1.5"></i>Chính sách bảo mật thông tin khách hàng</a></li>
          </ul>
        </div>

      </div>

      <div class="pt-4 flex flex-col sm:flex-row items-center justify-between text-[11px] text-sky-200 gap-2 text-center sm:text-left">
        <p>© Bản quyền thuộc về <strong>CÔNG TY TNHH MTV AN BÌNH DƯƠNG (anbinhduong.com)</strong>. Đ/c: 25 Cẩm Nam 6, P. Hòa Xuân, TP Đà Nẵng.</p>
        <p>Hotline hỗ trợ 24/7: <strong>0905.457.936</strong></p>
      </div>
    </div>
  </footer>

  <!-- ==================== CỤM NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) ==================== -->
  <!-- Tương thích hoàn hảo trên máy tính và điện thoại, nằm gọn trong khung nhìn không gây tràn viền -->
  <div class="fixed bottom-4 right-3 sm:right-4 z-50 flex flex-col items-end gap-2.5">
    
    <!-- Nút Facebook Fanpage Water 4.0 -->
    <a href="https://www.facebook.com/water4.0" target="_blank" rel="noopener noreferrer" aria-label="Facebook Water 4.0"
       class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition">
      <i class="fa-brands fa-facebook-f text-sm w-4 text-center"></i>
      <span class="text-xs font-bold">Facebook</span>
    </a>

    <!-- Nút Chat Zalo -->
    <a href="https://zalo.me/0905457936" target="_blank" rel="noopener noreferrer" aria-label="Chat Zalo 0905.457.936"
       class="flex items-center gap-2 bg-[#0068ff] hover:bg-sky-600 text-white px-3 py-2 rounded-full shadow-lg transition">
      <span class="font-extrabold text-[11px] bg-white text-[#0068ff] px-1 rounded">Zalo</span>
      <span class="text-xs font-bold">Chat Zalo</span>
    </a>

    <!-- Nút Gọi Hotline nổi bật -->
    <a href="tel:0905457936" aria-label="Gọi Hotline 0905.457.936"
       class="contact-pulse flex items-center gap-2 bg-[#d9251d] hover:bg-red-700 text-white px-3.5 py-2.5 rounded-full shadow-xl transition">
      <i class="fa-solid fa-phone-volume text-sm"></i>
      <span class="text-xs sm:text-sm font-extrabold tracking-wide">0905.457.936</span>
    </a>

  </div>

  <!-- ==================== JAVASCRIPT XỬ LÝ SLIDER, FALLBACK ẢNH DRIVE & BÁO GIÁ ==================== -->
  <script>
    // 1. Cơ chế tự động chuyển đổi link dự phòng cho 12 ảnh Google Drive để luôn hiển thị tốt nhất
    function handleDriveImgError(imgEl, fileId, fallbackText) {
      const step = parseInt(imgEl.getAttribute('data-fallback-step') || '0', 10);
      if (step === 0) {
        imgEl.setAttribute('data-fallback-step', '1');
        imgEl.src = 'https://lh3.googleusercontent.com/d/' + fileId + '=w800';
      } else if (step === 1) {
        imgEl.setAttribute('data-fallback-step', '2');
        imgEl.src = 'https://drive.google.com/uc?export=view&id=' + fileId;
      } else {
        imgEl.onerror = null;
        imgEl.src = 'https://placehold.co/500x500/f0f8ff/0066b3?text=' + encodeURIComponent(fallbackText);
      }
    }

    // 2. Xử lý đóng/mở Menu Danh mục trên Điện Thoại
    const btnMobileMenu = document.getElementById('btn-mobile-menu');
    const mobileMenuDrawer = document.getElementById('mobile-menu-drawer');

    if (btnMobileMenu && mobileMenuDrawer) {
      btnMobileMenu.addEventListener('click', function () {
        mobileMenuDrawer.classList.toggle('hidden');
      });
    }

    function closeMobileMenu() {
      if (mobileMenuDrawer) {
        mobileMenuDrawer.classList.add('hidden');
      }
    }

    // 3. Xử lý Slider 2 Ảnh Banner Tự Trượt (Auto-slide mỗi 5 giây)
    let currentSlideIndex = 0;
    const slides = document.querySelectorAll('.banner-slide');
    const dot0 = document.getElementById('dot-0');
    const dot1 = document.getElementById('dot-1');

    function showSlide(index) {
      if (!slides.length) return;
      currentSlideIndex = (index + slides.length) % slides.length;
      slides.forEach((slide, i) => {
        if (i === currentSlideIndex) {
          slide.classList.remove('hidden');
          slide.classList.add('block');
        } else {
          slide.classList.remove('block');
          slide.classList.add('hidden');
        }
      });

      if (dot0 && dot1) {
        if (currentSlideIndex === 0) {
          dot0.className = 'w-6 h-2 rounded-full bg-white transition-all';
          dot1.className = 'w-2 h-2 rounded-full bg-white/50 transition-all';
        } else {
          dot0.className = 'w-2 h-2 rounded-full bg-white/50 transition-all';
          dot1.className = 'w-6 h-2 rounded-full bg-white transition-all';
        }
      }
    }

    function nextSlide() {
      showSlide(currentSlideIndex + 1);
    }

    function prevSlide() {
      showSlide(currentSlideIndex - 1);
    }

    function goToSlide(index) {
      showSlide(index);
    }

    // Tự động trượt banner sau mỗi 5 giây
    setInterval(nextSlide, 5000);

    // 4. Chọn sản phẩm điền tự động xuống Form báo giá trang chủ
    function selectProductForQuote(productName) {
      const noteInput = document.getElementById('q-note');
      const formSection = document.getElementById('form-bao-gia');
      if (noteInput) {
        noteInput.value = 'Yêu cầu báo giá: ' + productName;
      }
      if (formSection) {
        formSection.scrollIntoView({ behavior: 'smooth' });
      }
    }

    // 5. Xử lý gửi Form Báo Giá ngay trên trang chủ
    function submitQuoteForm(event) {
      event.preventDefault();
      const msgBox = document.getElementById('quote-success-msg');
      if (msgBox) {
        msgBox.classList.remove('hidden');
      }
      document.getElementById('quote-form').reset();
    }

    // 6. Xử lý tìm kiếm nhanh sản phẩm trên trang
    function handleSearch(event) {
      event.preventDefault();
      const desktopVal = (document.getElementById('search-input')?.value || '').trim().toLowerCase();
      const mobileVal = (document.getElementById('search-input-mobile')?.value || '').trim().toLowerCase();
      const keyword = desktopVal || mobileVal;
      const firstProductSection = document.getElementById('dm-loc-tong-karofi');
      if (firstProductSection) {
        firstProductSection.scrollIntoView({ behavior: 'smooth' });
      }
      if (!keyword) return;
      const cards = document.querySelectorAll('.product-card');
      cards.forEach(card => {
        const text = card.innerText.toLowerCase();
        if (text.includes(keyword)) {
          card.classList.add('ring-2', 'ring-brand-600');
        } else {
          card.classList.remove('ring-2', 'ring-brand-600');
        }
      });
    }
  </script>
</body>
</html>
