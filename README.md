<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
  <title>CÔNG TY TNHH SẢN XUẤT VÀ THƯƠNG MẠI HIẾU LINH - Tổng Kho Bu Lông Ốc Vít Đà Nẵng | hieulinh.com</title>
  <meta name="description" content="CÔNG TY TNHH SẢN XUẤT VÀ THƯƠNG MẠI HIẾU LINH (hieulinh.com) - Chuyên sản xuất, gia công và phân phối Bu lông Inox, Bu lông cường độ cao, Bu lông neo móng, Ốc vít, Thanh ren, Cáp thép tại 47 Đội Cung, Cẩm Lệ, Đà Nẵng. Hotline: 0905.767.337">
  
  <!-- Open Graph Thumbnail là Logo trang web khi gửi link chia sẻ -->
  <meta property="og:type" content="website">
  <meta property="og:title" content="CÔNG TY TNHH SẢN XUẤT VÀ THƯƠNG MẠI HIẾU LINH | hieulinh.com">
  <meta property="og:description" content="Chuyên sản xuất & phân phối Bu lông, Ốc vít, Thanh ren, Vật tư liên kết và Thiết bị công nghiệp uy tín tại Đà Nẵng - ĐT: 0905.767.337">
  <meta property="og:url" content="https://hieulinh.com">
  <meta property="og:image" content="https://lh3.googleusercontent.com/d/17oD64Vcth1K3-lQutkMkY-VmQkMAO_yN">
  <meta property="og:image:alt" content="Logo Công Ty TNHH Sản Xuất Và Thương Mại Hiếu Linh">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/17oD64Vcth1K3-lQutkMkY-VmQkMAO_yN">
  <link rel="icon" href="https://lh3.googleusercontent.com/d/17oD64Vcth1K3-lQutkMkY-VmQkMAO_yN">

  <!-- Tailwind CSS & Font Awesome & Google Fonts (Inter / Roboto chuẩn Flatsome) -->
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

  <style>
    /* Reset chống tràn viền và chống lệch phải tuyệt đối */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      margin: 0;
      padding: 0;
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
      background-color: #f4f6f9;
      color: #222222;
      -webkit-text-size-adjust: 100%;
    }

    /* Tông màu theo Logo Hiếu Linh & Bulong Hoàng Hà (Xanh Công Nghiệp Đậm & Đỏ Cam Điểm Nhấn) */
    :root {
      --primary-blue: #0b3b69;
      --secondary-blue: #145388;
      --accent-red: #d9251d;
      --accent-orange: #e65100;
      --light-bg: #f4f6f9;
    }

    /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình */
    .flatsome-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 10px;
      padding-right: 10px;
    }
    @media (min-width: 1024px) {
      .flatsome-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Menu danh mục trên máy tính: tên danh mục viết liền trên 1 hàng, chữ nhỏ gọn, tự xuống hàng 2 nếu hết chỗ, không gãy dòng chữ trong 1 danh mục */
    .desktop-cat-nav {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: flex-start;
      gap: 4px 6px;
    }
    .desktop-cat-link {
      white-space: nowrap;
      font-size: 12.5px;
      font-weight: 600;
      padding: 6px 10px;
      border-radius: 4px;
      color: #ffffff;
      transition: all 0.2s ease;
      display: inline-flex;
      align-items: center;
      gap: 4px;
      line-height: 1.2;
    }
    .desktop-cat-link:hover, .desktop-cat-link.active {
      background-color: rgba(255, 255, 255, 0.18);
      color: #ffd54f;
    }

    /* Dropdown danh mục con trên máy tính */
    .cat-dropdown-parent {
      position: relative;
    }
    .cat-dropdown-menu {
      display: none;
      position: absolute;
      top: 100%;
      left: 0;
      min-width: 220px;
      background: #ffffff;
      box-shadow: 0 8px 24px rgba(0,0,0,0.16);
      border-top: 3px solid var(--accent-red);
      border-radius: 0 0 6px 6px;
      z-index: 100;
      padding: 6px 0;
    }
    .cat-dropdown-parent:hover .cat-dropdown-menu {
      display: block;
    }
    .cat-dropdown-item {
      display: block;
      padding: 7px 14px;
      font-size: 12.5px;
      color: #1f2937;
      white-space: nowrap;
      font-weight: 500;
      border-bottom: 1px solid #f1f5f9;
      transition: background 0.15s ease, color 0.15s ease;
    }
    .cat-dropdown-item:last-child {
      border-bottom: none;
    }
    .cat-dropdown-item:hover {
      background-color: #f0f7ff;
      color: var(--primary-blue);
      padding-left: 18px;
    }

    /* Thẻ danh mục ở trang chủ: chữ nhỏ gọn, không xuống dòng sai, tối ưu máy tính & điện thoại */
    .home-cat-card {
      background: #ffffff;
      border: 1px solid #e2e8f0;
      border-radius: 6px;
      transition: all 0.2s ease;
      overflow: hidden;
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
      padding: 8px 6px;
      cursor: pointer;
    }
    .home-cat-card:hover {
      border-color: var(--primary-blue);
      box-shadow: 0 4px 12px rgba(11, 59, 105, 0.12);
      transform: translateY(-2px);
    }
    .home-cat-title {
      font-size: 11.5px;
      font-weight: 600;
      color: #1e293b;
      line-height: 1.3;
      margin-top: 6px;
      width: 100%;
      word-break: keep-all;
    }
    @media (min-width: 1024px) {
      .home-cat-title {
        font-size: 12px;
        white-space: nowrap;
      }
    }

    /* Product Box chuẩn Flatsome: Tên sản phẩm hiển thị đầy đủ, không bị cắt chữ hoặc tràn viền */
    .product-small.box {
      background: #ffffff;
      border: 1px solid #e5e7eb;
      border-radius: 6px;
      overflow: hidden;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      height: 100%;
      position: relative;
      transition: box-shadow 0.2s ease, border-color 0.2s ease;
    }
    .product-small.box:hover {
      border-color: #0b3b69;
      box-shadow: 0 6px 16px rgba(11, 59, 105, 0.12);
    }
    .product-title-full {
      font-size: 12.5px;
      font-weight: 600;
      color: #1e293b;
      line-height: 1.38;
      white-space: normal;
      word-wrap: break-word;
      overflow-wrap: break-word;
      display: block;
      margin-bottom: 6px;
    }
    @media (min-width: 768px) {
      .product-title-full {
        font-size: 13.5px;
      }
    }

    /* Nhãn % giảm giá góc trên bên trái chuẩn Flatsome */
    .flatsome-sale-badge {
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
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      box-shadow: 0 2px 6px rgba(217, 37, 29, 0.35);
      line-height: 1;
    }

    /* Tiêu đề Section chuẩn UX Builder Flatsome (section-title-container) */
    .section-title-container {
      margin-bottom: 14px;
      border-bottom: 2px solid #0b3b69;
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: space-between;
      background: #ffffff;
      border-radius: 6px 6px 0 0;
      overflow: hidden;
    }
    .section-title-main {
      background-color: #0b3b69;
      color: #ffffff;
      padding: 9px 16px;
      font-size: 14px;
      font-weight: 700;
      text-transform: uppercase;
      display: inline-flex;
      align-items: center;
      gap: 8px;
      position: relative;
    }
    @media (min-width: 768px) {
      .section-title-main {
        font-size: 15px;
        padding: 10px 20px;
      }
    }

    /* Slider 2 Banner kích thước bằng nhau tuyệt đối */
    .banner-slider-viewport {
      position: relative;
      width: 100%;
      overflow: hidden;
      border-radius: 8px;
    }
    .banner-slides-track {
      display: flex;
      width: 200%;
      transition: transform 0.55s cubic-bezier(0.25, 0.8, 0.25, 1);
    }
    .banner-slide-item {
      width: 50%;
      flex-shrink: 0;
    }
    /* Chiều cao cố định bằng nhau cho 2 banner trên máy tính và trên điện thoại */
    .desktop-banner-box {
      height: 310px;
      width: 100%;
      position: relative;
      overflow: hidden;
    }
    .mobile-banner-box {
      height: 215px;
      width: 100%;
      position: relative;
      overflow: hidden;
    }

    /* Nút liên hệ nổi bật Zalo, Facebook, Hotline */
    .floating-contact-wrap {
      position: fixed;
      bottom: 16px;
      left: 12px;
      z-index: 999;
      display: flex;
      flex-direction: column;
      gap: 10px;
    }
    .floating-btn {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      border-radius: 999px;
      padding: 7px 13px 7px 8px;
      color: #ffffff;
      font-weight: 700;
      font-size: 12.5px;
      box-shadow: 0 4px 14px rgba(0, 0, 0, 0.25);
      transition: transform 0.2s ease;
      text-decoration: none;
    }
    .floating-btn:hover {
      transform: scale(1.04);
    }
    .floating-icon-circle {
      width: 32px;
      height: 32px;
      border-radius: 50%;
      background: rgba(255,255,255,0.2);
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 15px;
      flex-shrink: 0;
    }
    @keyframes pulseRing {
      0% { box-shadow: 0 0 0 0 rgba(217, 37, 29, 0.6); }
      70% { box-shadow: 0 0 0 10px rgba(217, 37, 29, 0); }
      100% { box-shadow: 0 0 0 0 rgba(217, 37, 29, 0); }
    }
    .pulse-hotline {
      animation: pulseRing 2s infinite;
    }
  </style>
</head>
<body>

  <!-- ================= TOP BAR (Chuẩn Flatsome #top-bar) ================= -->
  <div id="top-bar" class="bg-[#072849] text-white text-xs py-1.5 border-b border-white/10">
    <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
      <div class="flex items-center gap-2 truncate">
        <i class="fa-solid fa-certificate text-amber-400"></i>
        <span class="truncate">Chuyên Sản Xuất & Phân Phối Bu Lông Inox, Ốc Vít, Thanh Ren, Cáp Thép, Thiết Bị Công Nghiệp Giá Sỉ Tốt Nhất!</span>
      </div>
      <div class="hidden md:flex items-center gap-4 shrink-0 text-[11.5px]">
        <span><i class="fa-solid fa-location-dot text-amber-400 mr-1"></i>47 Đội Cung, Phường Cẩm Lệ, TP Đà Nẵng</span>
        <span>|</span>
        <a href="https://www.facebook.com/linh.hieu.161" target="_blank" rel="noopener" class="hover:text-amber-300">
          <i class="fa-brands fa-facebook mr-1"></i>Facebook Hiếu Linh
        </a>
        <span>|</span>
        <span class="font-semibold text-amber-300">Website: hieulinh.com</span>
      </div>
    </div>
  </div>

  <!-- ================= HEADER MAIN (Chuẩn Flatsome #header-main - Không để nút Gọi ngay để tránh tràn viền) ================= -->
  <header id="header" class="bg-white shadow-sm sticky top-0 z-50">
    <div class="flatsome-container py-2.5">
      <div class="flex items-center justify-between gap-2 md:gap-5">
        
        <!-- Nút mở Menu Danh mục trên Điện thoại -->
        <button type="button" onclick="toggleMobileDrawer()" class="lg:hidden p-2 rounded border border-slate-200 text-[#0b3b69] hover:bg-slate-100 shrink-0" aria-label="Mở danh mục">
          <i class="fa-solid fa-bars text-lg"></i>
        </button>

        <!-- Logo chỉnh gọn nhỏ lại + Tên công ty -->
        <a href="#trang-chu" class="flex items-center gap-2.5 min-w-0 shrink">
          <img 
            src="https://lh3.googleusercontent.com/d/17oD64Vcth1K3-lQutkMkY-VmQkMAO_yN" 
            data-fileid="17oD64Vcth1K3-lQutkMkY-VmQkMAO_yN"
            onerror="handleDriveImageFallback(this, 'HIẾU LINH')"
            alt="Logo Công Ty TNHH Sản Xuất Và Thương Mại Hiếu Linh" 
            class="h-10 md:h-12 w-auto object-contain rounded border border-slate-100 p-0.5 bg-white shrink-0"
          >
          <div class="min-w-0">
            <div class="text-[11px] md:text-[13px] font-extrabold text-[#0b3b69] leading-tight uppercase truncate">
              CÔNG TY TNHH SX & TM HIẾU LINH
            </div>
            <div class="text-[10px] md:text-[11.5px] text-slate-600 font-medium truncate">
              Tổng Kho Bu Lông - Ốc Vít - Vật Tư Kim Khí Đà Nẵng
            </div>
          </div>
        </a>

        <!-- Ô Tìm Kiếm Sản Phẩm (Desktop) -->
        <div class="hidden md:flex flex-1 max-w-md mx-2">
          <div class="flex w-full border-2 border-[#0b3b69] rounded overflow-hidden bg-white">
            <input 
              id="desktopSearchInput" 
              type="text" 
              oninput="filterProductsBySearch(this.value)"
              placeholder="Tìm bu lông inox, tắc kê nở, thanh ren, ốc vít..." 
              class="w-full px-3 py-1.5 text-xs focus:outline-none text-slate-800"
            >
            <button type="button" onclick="filterProductsBySearch(document.getElementById('desktopSearchInput').value)" class="bg-[#0b3b69] text-white px-3.5 text-xs font-semibold hover:bg-[#145388] shrink-0">
              <i class="fa-solid fa-magnifying-glass"></i>
            </button>
          </div>
        </div>

        <!-- Thông tin cam kết gọn nhẹ trên Desktop (Không để nút Gọi ngay trên Header) -->
        <div class="hidden xl:flex items-center gap-4 shrink-0 text-xs">
          <div class="flex items-center gap-2">
            <div class="w-8 h-8 rounded-full bg-blue-50 text-[#0b3b69] flex items-center justify-center font-bold">
              <i class="fa-solid fa-truck-fast"></i>
            </div>
            <div class="leading-tight">
              <div class="font-bold text-[#0b3b69] text-[11.5px]">Giao Hàng Toàn Quốc</div>
              <div class="text-[10.5px] text-slate-500">Nhanh chóng - Đúng hẹn</div>
            </div>
          </div>
          <div class="flex items-center gap-2">
            <div class="w-8 h-8 rounded-full bg-red-50 text-[#d9251d] flex items-center justify-center font-bold">
              <i class="fa-solid fa-shield-halved"></i>
            </div>
            <div class="leading-tight">
              <div class="font-bold text-[#0b3b69] text-[11.5px]">Chuẩn DIN / JIS / ASTM</div>
              <div class="text-[10.5px] text-slate-500">Đầy đủ CO - CQ xuất xưởng</div>
            </div>
          </div>
        </div>

      </div>

      <!-- Thanh tìm kiếm gọn trên Điện thoại -->
      <div class="mt-2 md:hidden">
        <div class="flex w-full border border-[#0b3b69] rounded overflow-hidden bg-white">
          <input 
            id="mobileSearchInput" 
            type="text" 
            oninput="filterProductsBySearch(this.value)"
            placeholder="Nhập tên bu lông, ốc vít cần tìm..." 
            class="w-full px-2.5 py-1.5 text-xs focus:outline-none"
          >
          <button type="button" onclick="filterProductsBySearch(document.getElementById('mobileSearchInput').value)" class="bg-[#0b3b69] text-white px-3 text-xs">
            <i class="fa-solid fa-magnifying-glass"></i>
          </button>
        </div>
      </div>
    </div>

    <!-- ================= THANH DANH MỤC TRÊN MÁY TÍNH (#wide-nav Flatsome) ================= -->
    <!-- Tên danh mục viết liền trên 1 hàng chữ nhỏ lại để nằm trên cùng 1 hàng hoặc xuống hàng 2, không xuống dòng tên danh mục -->
    <nav class="hidden lg:block bg-[#0b3b69] border-t border-white/15 py-1.5">
      <div class="flatsome-container">
        <div class="desktop-cat-nav">
          <a href="#trang-chu" onclick="filterByCategory('all')" class="desktop-cat-link active">
            <i class="fa-solid fa-house"></i> Trang chủ
          </a>
          <a href="#danh-muc-hieulinh" onclick="filterByCategory('all')" class="desktop-cat-link bg-[#d9251d]">
            <i class="fa-solid fa-globe"></i> hieulinh.com
          </a>
          <a href="#gioi-thieu-cong-ty" class="desktop-cat-link">
            Giới thiệu
          </a>

          <!-- Dropdown Bu Lông giống bulonghoangha.com -->
          <div class="cat-dropdown-parent">
            <a href="#sec-bulong" onclick="filterByCategory('Bu Lông')" class="desktop-cat-link">
              Bu Lông <i class="fa-solid fa-angle-down text-[10px]"></i>
            </a>
            <div class="cat-dropdown-menu">
              <a href="#sec-bulong" onclick="filterByCategory('Bu lông inox')" class="cat-dropdown-item">Bu lông inox (201 / 304 / 316)</a>
              <a href="#sec-bulong" onclick="filterByCategory('Bu lông nở – Tắc kê nở')" class="cat-dropdown-item">Bu lông nở – Tắc kê nở</a>
              <a href="#sec-bulong" onclick="filterByCategory('Bu lông hóa chất')" class="cat-dropdown-item">Bu lông hóa chất</a>
              <a href="#sec-bulong" onclick="filterByCategory('Bu lông cường độ cao')" class="cat-dropdown-item">Bu lông cường độ cao (8.8 / 10.9)</a>
              <a href="#sec-bulong" onclick="filterByCategory('Bu lông tự cắt')" class="cat-dropdown-item">Bu lông tự cắt S10T</a>
              <a href="#sec-bulong" onclick="filterByCategory('Bu lông neo móng')" class="cat-dropdown-item">Bu lông neo móng (J, L, I, U)</a>
              <a href="#sec-bulong" onclick="filterByCategory('Bu lông đồng')" class="cat-dropdown-item">Bu lông đồng</a>
            </div>
          </div>

          <!-- Dropdown Ốc Vít giống bulonghoangha.com -->
          <div class="cat-dropdown-parent">
            <a href="#sec-ocvit" onclick="filterByCategory('Ốc Vít')" class="desktop-cat-link">
              Ốc vít <i class="fa-solid fa-angle-down text-[10px]"></i>
            </a>
            <div class="cat-dropdown-menu">
              <a href="#sec-ocvit" onclick="filterByCategory('Vít inox')" class="cat-dropdown-item">Vít inox các loại</a>
              <a href="#sec-ocvit" onclick="filterByCategory('Vít bắn tôn')" class="cat-dropdown-item">Vít bắn tôn</a>
              <a href="#sec-ocvit" onclick="filterByCategory('Vít tự khoan')" class="cat-dropdown-item">Vít tự khoan</a>
              <a href="#sec-ocvit" onclick="filterByCategory('Ốc vít Bake (pake)')" class="cat-dropdown-item">Ốc vít Bake (pake)</a>
              <a href="#sec-ocvit" onclick="filterByCategory('Vít bắn gỗ')" class="cat-dropdown-item">Vít bắn gỗ</a>
              <a href="#sec-ocvit" onclick="filterByCategory('Vít trí')" class="cat-dropdown-item">Vít trí lục giác chìm</a>
            </div>
          </div>

          <!-- Các danh mục sản phẩm khác hiển thị trực tiếp, tên danh mục viết liền trên 1 hàng -->
          <a href="#sec-sanphamkhac" onclick="filterByCategory('Đai ốc inox (Êcu inox)')" class="desktop-cat-link">Đai ốc inox (Êcu inox)</a>
          <a href="#sec-sanphamkhac" onclick="filterByCategory('Vòng đệm các loại')" class="desktop-cat-link">Vòng đệm các loại</a>
          <a href="#sec-sanphamkhac" onclick="filterByCategory('Thanh ren – ty ren inox')" class="desktop-cat-link">Thanh ren – Ty ren inox</a>
          <a href="#sec-sanphamkhac" onclick="filterByCategory('Ubolt inox')" class="desktop-cat-link">Ubolt inox</a>
          <a href="#sec-sanphamkhac" onclick="filterByCategory('Cáp thép')" class="desktop-cat-link">Cáp thép</a>
          <a href="#sec-sanphamkhac" onclick="filterByCategory('Dây xích inox')" class="desktop-cat-link">Dây xích inox</a>
          <a href="#sec-sanphamkhac" onclick="filterByCategory('Tăng Đơ – Mã ní')" class="desktop-cat-link">Tăng Đơ – Mã ní</a>
          <a href="#sec-sanphamkhac" onclick="filterByCategory('Đai treo ống – đai xiết inox')" class="desktop-cat-link">Đai treo ống – Đai xiết</a>
          <a href="#sec-sanphamkhac" onclick="filterByCategory('Móc treo đá – bát treo đá')" class="desktop-cat-link">Móc treo đá</a>
          <a href="#sec-sanphamkhac" onclick="filterByCategory('Đinh rút - Đinh hàn - Đinh tán')" class="desktop-cat-link">Đinh rút – Đinh hàn</a>
          <a href="#form-bao-gia" class="desktop-cat-link">Báo giá</a>
          <a href="#tin-tuc-trang-chu" class="desktop-cat-link">Tin tức</a>
          <a href="#ban-do-lien-he" class="desktop-cat-link">Liên hệ</a>
        </div>
      </div>
    </nav>
  </header>

  <!-- ================= MENU DRAWER TRÊN ĐIỆN THOẠI ================= -->
  <div id="mobileMenuDrawer" class="fixed inset-0 z-50 hidden">
    <div class="absolute inset-0 bg-black/60" onclick="toggleMobileDrawer()"></div>
    <div class="relative w-72 max-w-[82vw] h-full bg-white shadow-2xl flex flex-col overflow-y-auto">
      <div class="p-3 bg-[#0b3b69] text-white flex items-center justify-between">
        <span class="font-bold text-xs uppercase tracking-wide">DANH MỤC HIEULINH.COM</span>
        <button type="button" onclick="toggleMobileDrawer()" class="text-white p-1">
          <i class="fa-solid fa-xmark text-lg"></i>
        </button>
      </div>
      <div class="divide-y divide-slate-100 text-xs font-semibold text-slate-700">
        <a href="#trang-chu" onclick="filterByCategory('all'); toggleMobileDrawer();" class="block px-4 py-2.5 text-[#0b3b69] bg-blue-50/50"><i class="fa-solid fa-house mr-2"></i>Trang chủ hieulinh.com</a>
        <a href="#sec-bulong" onclick="filterByCategory('Bu lông inox'); toggleMobileDrawer();" class="block px-4 py-2.5">1. Bu lông Inox (201 / 304 / 316)</a>
        <a href="#sec-bulong" onclick="filterByCategory('Bu lông nở – Tắc kê nở'); toggleMobileDrawer();" class="block px-4 py-2.5">2. Bu lông nở – Tắc kê nở</a>
        <a href="#sec-bulong" onclick="filterByCategory('Bu lông hóa chất'); toggleMobileDrawer();" class="block px-4 py-2.5">3. Bu lông hóa chất</a>
        <a href="#sec-bulong" onclick="filterByCategory('Bu lông cường độ cao'); toggleMobileDrawer();" class="block px-4 py-2.5">4. Bu lông cường độ cao 8.8 / 10.9</a>
        <a href="#sec-bulong" onclick="filterByCategory('Bu lông neo móng'); toggleMobileDrawer();" class="block px-4 py-2.5">5. Bu lông neo móng (J, L, I, U)</a>
        <a href="#sec-ocvit" onclick="filterByCategory('Vít inox'); toggleMobileDrawer();" class="block px-4 py-2.5">6. Ốc vít Inox các loại</a>
        <a href="#sec-ocvit" onclick="filterByCategory('Vít tự khoan'); toggleMobileDrawer();" class="block px-4 py-2.5">7. Vít bắn tôn – Vít tự khoan</a>
        <a href="#sec-sanphamkhac" onclick="filterByCategory('Đai ốc inox (Êcu inox)'); toggleMobileDrawer();" class="block px-4 py-2.5">8. Đai ốc Inox (Êcu Inox)</a>
        <a href="#sec-sanphamkhac" onclick="filterByCategory('Vòng đệm các loại'); toggleMobileDrawer();" class="block px-4 py-2.5">9. Vòng đệm (Long đền) các loại</a>
        <a href="#sec-sanphamkhac" onclick="filterByCategory('Thanh ren – ty ren inox'); toggleMobileDrawer();" class="block px-4 py-2.5">10. Thanh ren – Ty ren Inox</a>
        <a href="#sec-sanphamkhac" onclick="filterByCategory('Ubolt inox'); toggleMobileDrawer();" class="block px-4 py-2.5">11. Ubolt Inox – Đai treo ống</a>
        <a href="#sec-sanphamkhac" onclick="filterByCategory('Tăng Đơ – Mã ní'); toggleMobileDrawer();" class="block px-4 py-2.5">12. Cáp thép – Tăng đơ – Mã ní</a>
        <a href="#gioi-thieu-cong-ty" onclick="toggleMobileDrawer();" class="block px-4 py-2.5 text-[#0b3b69]">Hình ảnh thực tế Công ty Hiếu Linh</a>
        <a href="#form-bao-gia" onclick="toggleMobileDrawer();" class="block px-4 py-2.5 text-[#d9251d]">Gửi yêu cầu báo giá nhanh</a>
        <a href="#ban-do-lien-he" onclick="toggleMobileDrawer();" class="block px-4 py-2.5">Bản đồ & Liên hệ (0905.767.337)</a>
      </div>
    </div>
  </div>

  <!-- ================= MAIN CONTENT (Bố cục UX Builder Flatsome) ================= -->
  <main id="trang-chu" class="flatsome-container py-3 space-y-5">

    <!-- ================= 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU ================= -->
    <!-- Thiết kế mới ảnh banner điện thoại khác với ảnh banner máy tính để tối ưu chữ bên trong ảnh, chữ nhỏ gọn nằm hết trong ảnh banner, không tràn viền -->
    <section aria-label="Banner chính">
      <div class="banner-slider-viewport shadow-sm border border-slate-200 bg-[#0b3b69]">
        <div id="bannerTrack" class="banner-slides-track">
          
          <!-- ================= SLIDE 1 ================= -->
          <div class="banner-slide-item">
            <!-- BANNER MÁY TÍNH SLIDE 1 (Chỉ hiện trên màn hình md trở lên) -->
            <div class="hidden md:block desktop-banner-box bg-gradient-to-r from-[#072849] via-[#0b3b69] to-[#145388]">
              <div class="w-full h-full grid grid-cols-12 items-center px-10 py-6 gap-6">
                <div class="col-span-7 text-white space-y-2.5 pr-2">
                  <div class="inline-block bg-amber-400 text-[#072849] font-extrabold text-[11px] px-2.5 py-0.5 rounded uppercase tracking-wider">
                    TỔNG KHO BU LÔNG ỐC VÍT ĐÀ NẴNG - HIEULINH.COM
                  </div>
                  <h1 class="text-xl lg:text-2xl font-extrabold leading-snug text-white">
                    CÔNG TY TNHH SẢN XUẤT VÀ THƯƠNG MẠI HIẾU LINH
                  </h1>
                  <p class="text-xs lg:text-[13px] text-blue-100 leading-relaxed max-w-xl">
                    Chuyên sản xuất, gia công và nhập khẩu trực tiếp: Bu lông Inox 201/304/316, Bu lông cường độ cao 8.8 - 10.9, Bu lông neo móng, Ốc vít, Thanh ren, Đai ốc, Vòng đệm chuẩn DIN / JIS / ASTM.
                  </p>
                  <div class="pt-1 flex flex-wrap items-center gap-3 text-xs">
                    <span class="bg-white/15 border border-white/25 px-3 py-1.5 rounded font-semibold">
                      <i class="fa-solid fa-phone-volume text-amber-400 mr-1"></i>Hotline: 0905.767.337
                    </span>
                    <span class="bg-white/15 border border-white/25 px-3 py-1.5 rounded font-semibold">
                      <i class="fa-solid fa-location-dot text-amber-400 mr-1"></i>47 Đội Cung, Cẩm Lệ, TP Đà Nẵng
                    </span>
                  </div>
                </div>
                <div class="col-span-5 grid grid-cols-2 gap-2.5 h-full items-center">
                  <div class="bg-white p-1.5 rounded-lg shadow-md h-52 flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/1UQbGPe6AD77GJD1078uMJnKsIpXv7NZw" data-fileid="1UQbGPe6AD77GJD1078uMJnKsIpXv7NZw" onerror="handleDriveImageFallback(this, 'Bu Lông Inox')" alt="Bu lông Inox Hiếu Linh" class="w-full h-40 object-cover rounded">
                    <span class="text-[11px] font-bold text-[#0b3b69] text-center mt-1 truncate">Bu Lông Inox 304/316</span>
                  </div>
                  <div class="bg-white p-1.5 rounded-lg shadow-md h-52 flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/1Ni8LciD0bmwlg_eUju2eR0HHTjfPLsdy" data-fileid="1Ni8LciD0bmwlg_eUju2eR0HHTjfPLsdy" onerror="handleDriveImageFallback(this, 'Kho Hiếu Linh')" alt="Kho hàng Công ty Hiếu Linh" class="w-full h-40 object-cover rounded">
                    <span class="text-[11px] font-bold text-[#0b3b69] text-center mt-1 truncate">Tổng Kho Sẵn Hàng Lớn</span>
                  </div>
                </div>
              </div>
            </div>

            <!-- BANNER ĐIỆN THOẠI SLIDE 1 (Thiết kế riêng cho điện thoại, chữ nhỏ gọn nằm hoàn toàn trong khung) -->
            <div class="block md:hidden mobile-banner-box bg-gradient-to-br from-[#072849] to-[#0b3b69] p-3">
              <div class="w-full h-full border border-white/20 rounded-md p-2.5 flex items-center justify-between gap-2.5 bg-[#0b3b69]/50">
                <div class="w-[62%] text-white space-y-1">
                  <span class="inline-block bg-amber-400 text-[#072849] font-bold text-[9px] px-1.5 py-0.5 rounded uppercase">
                    HIEULINH.COM - ĐÀ NẴNG
                  </span>
                  <h2 class="text-[12px] font-extrabold leading-tight text-white">
                    CÔNG TY TNHH SX & TM HIẾU LINH
                  </h2>
                  <p class="text-[10px] text-blue-100 leading-snug">
                    Tổng kho Bu lông Inox, Bu lông neo, Ốc vít, Thanh ren, Đai ốc giá sỉ.
                  </p>
                  <div class="text-[10px] font-bold text-amber-300 pt-0.5">
                    ĐT: 0905.767.337 | 47 Đội Cung
                  </div>
                </div>
                <div class="w-[38%] h-full flex items-center justify-center">
                  <div class="bg-white p-1 rounded shadow w-full h-36 flex flex-col justify-between">
                    <img src="https://lh3.googleusercontent.com/d/1UQbGPe6AD77GJD1078uMJnKsIpXv7NZw" data-fileid="1UQbGPe6AD77GJD1078uMJnKsIpXv7NZw" onerror="handleDriveImageFallback(this, 'Bu Lông')" alt="Bu lông Hiếu Linh" class="w-full h-28 object-cover rounded">
                    <span class="text-[9px] font-bold text-[#0b3b69] text-center truncate">Bu Lông - Ốc Vít</span>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- ================= SLIDE 2 (Kích thước bằng đúng Slide 1) ================= -->
          <div class="banner-slide-item">
            <!-- BANNER MÁY TÍNH SLIDE 2 -->
            <div class="hidden md:block desktop-banner-box bg-gradient-to-r from-[#10375c] via-[#0b3b69] to-[#1e5f99]">
              <div class="w-full h-full grid grid-cols-12 items-center px-10 py-6 gap-6">
                <div class="col-span-7 text-white space-y-2.5 pr-2">
                  <div class="inline-block bg-[#d9251d] text-white font-extrabold text-[11px] px-2.5 py-0.5 rounded uppercase tracking-wider">
                    SẢN XUẤT & GIA CÔNG THEO BẢN VẼ KỸ THUẬT
                  </div>
                  <h2 class="text-xl lg:text-2xl font-extrabold leading-snug text-white">
                    GIA CÔNG BU LÔNG NEO MÓNG - VẬT TƯ LIÊN KẾT CÔNG TRÌNH
                  </h2>
                  <p class="text-xs lg:text-[13px] text-blue-100 leading-relaxed max-w-xl">
                    Đáp ứng nhanh mọi đơn hàng Bu lông neo chữ J, L, I, U, Thanh ren, Bản mã, Ubolt, Cáp thép, Tăng đơ cho dự án nhà xưởng, cầu đường, cơ điện M&E trên toàn quốc.
                  </p>
                  <div class="pt-1 flex flex-wrap items-center gap-3 text-xs">
                    <span class="bg-amber-400 text-[#072849] px-3 py-1.5 rounded font-bold">
                      <i class="fa-solid fa-check-circle mr-1"></i>Chiết Khấu Cao Cho Dự Án & Đại Lý
                    </span>
                    <span class="bg-white/15 border border-white/25 px-3 py-1.5 rounded font-semibold">
                      <i class="fa-solid fa-bolt text-amber-400 mr-1"></i>Báo Giá Nhanh Trong 5 Phút
                    </span>
                  </div>
                </div>
                <div class="col-span-5 grid grid-cols-2 gap-2.5 h-full items-center">
                  <div class="bg-white p-1.5 rounded-lg shadow-md h-52 flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/1tQdlh3702DBaLcPsGnEcFI2mpGWFztp1" data-fileid="1tQdlh3702DBaLcPsGnEcFI2mpGWFztp1" onerror="handleDriveImageFallback(this, 'Bu Lông Neo')" alt="Gia công bu lông neo móng" class="w-full h-40 object-cover rounded">
                    <span class="text-[11px] font-bold text-[#0b3b69] text-center mt-1 truncate">Bu Lông Neo Móng J, L, U</span>
                  </div>
                  <div class="bg-white p-1.5 rounded-lg shadow-md h-52 flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/1-o2Q-i8PT8ZrXSAkhNFtZPLF6OdgS-64" data-fileid="1-o2Q-i8PT8ZrXSAkhNFtZPLF6OdgS-64" onerror="handleDriveImageFallback(this, 'Xưởng Sản Xuất')" alt="Xưởng cơ khí Hiếu Linh" class="w-full h-40 object-cover rounded">
                    <span class="text-[11px] font-bold text-[#0b3b69] text-center mt-1 truncate">Xưởng Gia Công Cơ Khí</span>
                  </div>
                </div>
              </div>
            </div>

            <!-- BANNER ĐIỆN THOẠI SLIDE 2 (Thiết kế riêng cho điện thoại, chữ nhỏ gọn không tràn viền) -->
            <div class="block md:hidden mobile-banner-box bg-gradient-to-br from-[#10375c] to-[#0b3b69] p-3">
              <div class="w-full h-full border border-white/20 rounded-md p-2.5 flex items-center justify-between gap-2.5 bg-[#0b3b69]/50">
                <div class="w-[62%] text-white space-y-1">
                  <span class="inline-block bg-[#d9251d] text-white font-bold text-[9px] px-1.5 py-0.5 rounded uppercase">
                    GIA CÔNG THEO BẢN VẼ
                  </span>
                  <h2 class="text-[12px] font-extrabold leading-tight text-white">
                    BU LÔNG NEO MÓNG & CƠ KHÍ CÔNG NGHIỆP
                  </h2>
                  <p class="text-[10px] text-blue-100 leading-snug">
                    Cung ứng vật tư liên kết chuẩn CO-CQ, giao hàng tận chân công trình.
                  </p>
                  <div class="text-[10px] font-bold text-amber-300 pt-0.5">
                    Hotline/Zalo: 0905.767.337
                  </div>
                </div>
                <div class="w-[38%] h-full flex items-center justify-center">
                  <div class="bg-white p-1 rounded shadow w-full h-36 flex flex-col justify-between">
                    <img src="https://lh3.googleusercontent.com/d/1tQdlh3702DBaLcPsGnEcFI2mpGWFztp1" data-fileid="1tQdlh3702DBaLcPsGnEcFI2mpGWFztp1" onerror="handleDriveImageFallback(this, 'Bu Lông Neo')" alt="Bu lông neo Hiếu Linh" class="w-full h-28 object-cover rounded">
                    <span class="text-[9px] font-bold text-[#0b3b69] text-center truncate">Gia Công Chuẩn Xác</span>
                  </div>
                </div>
              </div>
            </div>
          </div>

        </div>

        <!-- Nút chuyển Slide trái/phải & chấm tròn chỉ báo -->
        <button type="button" onclick="prevBannerSlide()" class="absolute left-2 top-1/2 -translate-y-1/2 w-7 h-7 rounded-full bg-black/40 text-white hover:bg-black/70 flex items-center justify-center text-xs" aria-label="Slide trước">
          <i class="fa-solid fa-chevron-left"></i>
        </button>
        <button type="button" onclick="nextBannerSlide()" class="absolute right-2 top-1/2 -translate-y-1/2 w-7 h-7 rounded-full bg-black/40 text-white hover:bg-black/70 flex items-center justify-center text-xs" aria-label="Slide tiếp">
          <i class="fa-solid fa-chevron-right"></i>
        </button>
        <div class="absolute bottom-2 left-1/2 -translate-x-1/2 flex items-center gap-2">
          <button type="button" id="dotSlide0" onclick="goToBannerSlide(0)" class="w-2.5 h-2.5 rounded-full bg-amber-400" aria-label="Banner 1"></button>
          <button type="button" id="dotSlide1" onclick="goToBannerSlide(1)" class="w-2.5 h-2.5 rounded-full bg-white/50" aria-label="Banner 2"></button>
        </div>
      </div>
    </section>

    <!-- ================= DANH MỤC SẢN PHẨM TRANG CHỦ (Chữ nhỏ gọn, đẹp trên cả máy tính & điện thoại) ================= -->
    <section id="danh-muc-hieulinh" class="bg-white p-3 md:p-4 rounded-lg shadow-sm border border-slate-200">
      <div class="flex flex-wrap items-center justify-between gap-2 pb-2.5 mb-3 border-b border-slate-200">
        <div class="flex items-center gap-2">
          <span class="w-1.5 h-5 bg-[#0b3b69] rounded-full"></span>
          <h2 class="text-xs md:text-sm font-extrabold uppercase text-[#0b3b69]">
            DANH MỤC SẢN PHẨM HIEULINH.COM
          </h2>
        </div>
        <button type="button" onclick="filterByCategory('all')" class="text-[11.5px] font-semibold text-[#0b3b69] hover:text-[#d9251d]">
          Xem tất cả sản phẩm <i class="fa-solid fa-angles-right text-[10px]"></i>
        </button>
      </div>

      <!-- Lưới danh mục sản phẩm nhỏ gọn (2 cột/3 cột trên mobile, 6-8 cột trên desktop) -->
      <div class="grid grid-cols-3 sm:grid-cols-4 md:grid-cols-6 lg:grid-cols-8 gap-2">
        
        <div onclick="filterByCategory('Bu lông inox')" class="home-cat-card">
          <img src="https://lh3.googleusercontent.com/d/1UQbGPe6AD77GJD1078uMJnKsIpXv7NZw" data-fileid="1UQbGPe6AD77GJD1078uMJnKsIpXv7NZw" onerror="handleDriveImageFallback(this, 'Bu Lông Inox')" alt="Bu lông inox" class="w-12 h-12 md:w-14 md:h-14 object-cover rounded">
          <div class="home-cat-title">Bu lông inox</div>
        </div>

        <div onclick="filterByCategory('Bu lông cường độ cao')" class="home-cat-card">
          <img src="https://lh3.googleusercontent.com/d/1PIIAgUNcV8xjH5wYlM7YXQ1rSMbFdrKy" data-fileid="1PIIAgUNcV8xjH5wYlM7YXQ1rSMbFdrKy" onerror="handleDriveImageFallback(this, 'Bu Lông 8.8')" alt="Bu lông cường độ cao" class="w-12 h-12 md:w-14 md:h-14 object-cover rounded">
          <div class="home-cat-title">Bu lông CĐC 8.8</div>
        </div>

        <div onclick="filterByCategory('Bu lông neo móng')" class="home-cat-card">
          <img src="https://lh3.googleusercontent.com/d/1tQdlh3702DBaLcPsGnEcFI2mpGWFztp1" data-fileid="1tQdlh3702DBaLcPsGnEcFI2mpGWFztp1" onerror="handleDriveImageFallback(this, 'Bu Lông Neo')" alt="Bu lông neo móng" class="w-12 h-12 md:w-14 md:h-14 object-cover rounded">
          <div class="home-cat-title">Bu lông neo móng</div>
        </div>

        <div onclick="filterByCategory('Bu lông nở – Tắc kê nở')" class="home-cat-card">
          <img src="https://lh3.googleusercontent.com/d/1KzBEj6UpOEQSvUEaIe5_P6gCMXKy-oWz" data-fileid="1KzBEj6UpOEQSvUEaIe5_P6gCMXKy-oWz" onerror="handleDriveImageFallback(this, 'Tắc Kê Nở')" alt="Bu lông nở tắc kê nở" class="w-12 h-12 md:w-14 md:h-14 object-cover rounded">
          <div class="home-cat-title">Tắc kê – Nở inox</div>
        </div>

        <div onclick="filterByCategory('Bu lông hóa chất')" class="home-cat-card">
          <img src="https://lh3.googleusercontent.com/d/1PQ5IuGPl334qx7xJMlpdS7MEXJ99UnZI" data-fileid="1PQ5IuGPl334qx7xJMlpdS7MEXJ99UnZI" onerror="handleDriveImageFallback(this, 'BL Hóa Chất')" alt="Bu lông hóa chất" class="w-12 h-12 md:w-14 md:h-14 object-cover rounded">
          <div class="home-cat-title">Bu lông hóa chất</div>
        </div>

        <div onclick="filterByCategory('Vít inox')" class="home-cat-card">
          <img src="https://lh3.googleusercontent.com/d/1nhwPipzoC55rZekP9fXLsSEbQUlwo3DA" data-fileid="1nhwPipzoC55rZekP9fXLsSEbQUlwo3DA" onerror="handleDriveImageFallback(this, 'Ốc Vít Inox')" alt="Vít inox" class="w-12 h-12 md:w-14 md:h-14 object-cover rounded">
          <div class="home-cat-title">Ốc vít inox</div>
        </div>

        <div onclick="filterByCategory('Vít tự khoan')" class="home-cat-card">
          <img src="https://lh3.googleusercontent.com/d/1mRn0UrG88BagKsONZ36xSLQb02yMxzlN" data-fileid="1mRn0UrG88BagKsONZ36xSLQb02yMxzlN" onerror="handleDriveImageFallback(this, 'Vít Tự Khoan')" alt="Vít tự khoan bắn tôn" class="w-12 h-12 md:w-14 md:h-14 object-cover rounded">
          <div class="home-cat-title">Vít tự khoan</div>
        </div>

        <div onclick="filterByCategory('Đai ốc inox (Êcu inox)')" class="home-cat-card">
          <img src="https://lh3.googleusercontent.com/d/1QdRgIyTTlAarxei5zzHUXchTYAaZUqaL" data-fileid="1QdRgIyTTlAarxei5zzHUXchTYAaZUqaL" onerror="handleDriveImageFallback(this, 'Đai Ốc Inox')" alt="Đai ốc inox Êcu" class="w-12 h-12 md:w-14 md:h-14 object-cover rounded">
          <div class="home-cat-title">Đai ốc (Êcu inox)</div>
        </div>

        <div onclick="filterByCategory('Vòng đệm các loại')" class="home-cat-card">
          <img src="https://lh3.googleusercontent.com/d/1W6ZUjncrWu9x407Za3ayLagjAjjtCz3O" data-fileid="1W6ZUjncrWu9x407Za3ayLagjAjjtCz3O" onerror="handleDriveImageFallback(this, 'Vòng Đệm')" alt="Vòng đệm long đền" class="w-12 h-12 md:w-14 md:h-14 object-cover rounded">
          <div class="home-cat-title">Vòng đệm – Long đền</div>
        </div>

        <div onclick="filterByCategory('Thanh ren – ty ren inox')" class="home-cat-card">
          <img src="https://lh3.googleusercontent.com/d/1SaRc8DH-jK6fvjB1C8bS5VFokGfrgYMi" data-fileid="1SaRc8DH-jK6fvjB1C8bS5VFokGfrgYMi" onerror="handleDriveImageFallback(this, 'Thanh Ren')" alt="Thanh ren ty ren" class="w-12 h-12 md:w-14 md:h-14 object-cover rounded">
          <div class="home-cat-title">Thanh ren – Ty ren</div>
        </div>

        <div onclick="filterByCategory('Ubolt inox')" class="home-cat-card">
          <img src="https://lh3.googleusercontent.com/d/1yQ-1BXbkJ8iT5xYO61_rEh3WeCAkcF3x" data-fileid="1yQ-1BXbkJ8iT5xYO61_rEh3WeCAkcF3x" onerror="handleDriveImageFallback(this, 'Ubolt Inox')" alt="Ubolt đai treo ống" class="w-12 h-12 md:w-14 md:h-14 object-cover rounded">
          <div class="home-cat-title">Ubolt – Đai treo</div>
        </div>

        <div onclick="filterByCategory('Tăng Đơ – Mã ní')" class="home-cat-card">
          <img src="https://lh3.googleusercontent.com/d/1q_X4xdvhbCPRHty-SX0EtfiUvRZVDhZd" data-fileid="1q_X4xdvhbCPRHty-SX0EtfiUvRZVDhZd" onerror="handleDriveImageFallback(this, 'Tăng Đơ Cáp')" alt="Tăng đơ mã ní cáp thép" class="w-12 h-12 md:w-14 md:h-14 object-cover rounded">
          <div class="home-cat-title">Cáp thép – Tăng đơ</div>
        </div>

        <div onclick="filterByCategory('Bu lông tự cắt')" class="home-cat-card">
          <img src="https://lh3.googleusercontent.com/d/1PIIAgUNcV8xjH5wYlM7YXQ1rSMbFdrKy" data-fileid="1PIIAgUNcV8xjH5wYlM7YXQ1rSMbFdrKy" onerror="handleDriveImageFallback(this, 'BL Tự Cắt')" alt="Bu lông tự cắt" class="w-12 h-12 md:w-14 md:h-14 object-cover rounded">
          <div class="home-cat-title">Bu lông tự cắt</div>
        </div>

        <div onclick="filterByCategory('Vít bắn gỗ')" class="home-cat-card">
          <img src="https://lh3.googleusercontent.com/d/1nhwPipzoC55rZekP9fXLsSEbQUlwo3DA" data-fileid="1nhwPipzoC55rZekP9fXLsSEbQUlwo3DA" onerror="handleDriveImageFallback(this, 'Vít Bắn Gỗ')" alt="Vít bắn gỗ" class="w-12 h-12 md:w-14 md:h-14 object-cover rounded">
          <div class="home-cat-title">Vít gỗ – Vít trí</div>
        </div>

        <div onclick="filterByCategory('Dây xích inox')" class="home-cat-card">
          <img src="https://lh3.googleusercontent.com/d/1q_X4xdvhbCPRHty-SX0EtfiUvRZVDhZd" data-fileid="1q_X4xdvhbCPRHty-SX0EtfiUvRZVDhZd" onerror="handleDriveImageFallback(this, 'Xích Inox')" alt="Dây xích inox" class="w-12 h-12 md:w-14 md:h-14 object-cover rounded">
          <div class="home-cat-title">Dây xích inox</div>
        </div>

        <div onclick="filterByCategory('all')" class="home-cat-card bg-blue-50/60">
          <img src="https://lh3.googleusercontent.com/d/17oD64Vcth1K3-lQutkMkY-VmQkMAO_yN" data-fileid="17oD64Vcth1K3-lQutkMkY-VmQkMAO_yN" onerror="handleDriveImageFallback(this, 'Hiếu Linh')" alt="Danh mục hieulinh.com" class="w-12 h-12 md:w-14 md:h-14 object-contain rounded bg-white p-1">
          <div class="home-cat-title text-[#0b3b69]">hieulinh.com</div>
        </div>

      </div>

      <!-- Thanh thông báo trạng thái lọc danh mục (ẩn mặc định, hiện khi bấm lọc) -->
      <div id="activeFilterNotice" class="hidden mt-3 px-3 py-2 bg-blue-50 border border-blue-200 rounded flex items-center justify-between text-xs">
        <span>Đang lọc theo danh mục: <strong id="activeFilterName" class="text-[#0b3b69]">Tất cả</strong></span>
        <button type="button" onclick="filterByCategory('all')" class="text-[#d9251d] font-bold hover:underline">
          <i class="fa-solid fa-rotate-left mr-1"></i>Hiển thị tất cả
        </button>
      </div>
    </section>

    <!-- ================= SECTION 1: BU LÔNG CÁC LOẠI (Chia 2 cột trên điện thoại, 4 cột trên máy tính) ================= -->
    <section id="sec-bulong">
      <div class="section-title-container">
        <div class="section-title-main">
          <i class="fa-solid fa-screwdriver-wrench"></i>
          <span>BU LÔNG CÁC LOẠI</span>
        </div>
        <div class="hidden md:flex items-center gap-3 px-3 text-xs font-medium text-slate-600">
          <button type="button" onclick="filterByCategory('Bu lông inox')" class="hover:text-[#0b3b69]">Bu lông inox</button>
          <span>•</span>
          <button type="button" onclick="filterByCategory('Bu lông nở – Tắc kê nở')" class="hover:text-[#0b3b69]">Bu lông nở – Tắc kê nở</button>
          <span>•</span>
          <button type="button" onclick="filterByCategory('Bu lông hóa chất')" class="hover:text-[#0b3b69]">Bu lông hóa chất</button>
          <span>•</span>
          <button type="button" onclick="filterByCategory('Bu lông cường độ cao')" class="hover:text-[#0b3b69]">Bu lông cường độ cao</button>
          <span>•</span>
          <button type="button" onclick="filterByCategory('Bu lông neo móng')" class="hover:text-[#0b3b69]">Bu lông neo móng</button>
        </div>
      </div>

      <!-- Lưới sản phẩm: 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4) -->
      <div id="grid-bulong" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 md:gap-4"></div>
    </section>

    <!-- ================= SECTION 2: ỐC VÍT CÁC LOẠI (Chia 2 cột trên điện thoại, 4 cột trên máy tính) ================= -->
    <section id="sec-ocvit">
      <div class="section-title-container">
        <div class="section-title-main">
          <i class="fa-solid fa-gears"></i>
          <span>ỐC VÍT & ĐAI ỐC - VÒNG ĐỆM</span>
        </div>
        <div class="hidden md:flex items-center gap-3 px-3 text-xs font-medium text-slate-600">
          <button type="button" onclick="filterByCategory('Vít inox')" class="hover:text-[#0b3b69]">Vít inox</button>
          <span>•</span>
          <button type="button" onclick="filterByCategory('Vít bắn tôn')" class="hover:text-[#0b3b69]">Vít bắn tôn</button>
          <span>•</span>
          <button type="button" onclick="filterByCategory('Vít tự khoan')" class="hover:text-[#0b3b69]">Vít tự khoan</button>
          <span>•</span>
          <button type="button" onclick="filterByCategory('Đai ốc inox (Êcu inox)')" class="hover:text-[#0b3b69]">Đai ốc inox (Êcu)</button>
          <span>•</span>
          <button type="button" onclick="filterByCategory('Vòng đệm các loại')" class="hover:text-[#0b3b69]">Vòng đệm các loại</button>
        </div>
      </div>

      <div id="grid-ocvit" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 md:gap-4"></div>
    </section>

    <!-- ================= SECTION 3: THANH REN, CÁP THÉP & VẬT TƯ LIÊN KẾT KHÁC ================= -->
    <section id="sec-sanphamkhac">
      <div class="section-title-container">
        <div class="section-title-main">
          <i class="fa-solid fa-layer-group"></i>
          <span>THANH REN - UBALT - CÁP THÉP - PHỤ KIỆN LIÊN KẾT</span>
        </div>
        <div class="hidden md:flex items-center gap-3 px-3 text-xs font-medium text-slate-600">
          <button type="button" onclick="filterByCategory('Thanh ren – ty ren inox')" class="hover:text-[#0b3b69]">Thanh ren – Ty ren</button>
          <span>•</span>
          <button type="button" onclick="filterByCategory('Ubolt inox')" class="hover:text-[#0b3b69]">Ubolt inox</button>
          <span>•</span>
          <button type="button" onclick="filterByCategory('Tăng Đơ – Mã ní')" class="hover:text-[#0b3b69]">Tăng Đơ – Mã ní</button>
          <span>•</span>
          <button type="button" onclick="filterByCategory('Cáp thép')" class="hover:text-[#0b3b69]">Cáp thép – Xích inox</button>
        </div>
      </div>

      <div id="grid-khac" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 md:gap-4"></div>
    </section>

    <!-- ================= SECTION 4: TẠI SAO CHỌN HIẾU LINH & HÌNH ẢNH THỰC TẾ CÔNG TY (6 ảnh thực tế) ================= -->
    <section id="gioi-thieu-cong-ty" class="bg-white p-3.5 md:p-5 rounded-lg shadow-sm border border-slate-200">
      <div class="section-title-container">
        <div class="section-title-main">
          <i class="fa-solid fa-building-shield"></i>
          <span>NĂNG LỰC SẢN XUẤT & HÌNH ẢNH THỰC TẾ CÔNG TY HIẾU LINH</span>
        </div>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-4 items-start">
        <!-- Giới thiệu & 3 lý do chọn Hiếu Linh (Giống cấu trúc bulonghoangha.com) -->
        <div class="lg:col-span-5 space-y-3 text-xs md:text-[13px] text-slate-700 leading-relaxed">
          <div class="p-3 bg-blue-50/70 border-l-4 border-[#0b3b69] rounded-r">
            <h3 class="font-extrabold text-[#0b3b69] text-sm uppercase mb-1">
              CÔNG TY TNHH SẢN XUẤT VÀ THƯƠNG MẠI HIẾU LINH
            </h3>
            <p>
              <strong>Mã số thuế:</strong> 0401377003 — Đơn vị uy tín hàng đầu tại TP Đà Nẵng và khu vực Miền Trung chuyên sản xuất máy móc, thiết bị công nghiệp, gia công và phân phối sỉ lẻ các dòng <strong>Bu lông, Ốc vít, Đai ốc, Vòng đệm, Thanh ren, Cáp thép</strong> đạt tiêu chuẩn quốc tế.
            </p>
          </div>

          <div class="space-y-2.5">
            <div class="flex items-start gap-2.5">
              <span class="w-6 h-6 rounded-full bg-[#0b3b69] text-white font-bold text-xs flex items-center justify-center shrink-0 mt-0.5">1</span>
              <div>
                <h4 class="font-bold text-slate-900">Luôn đặt lợi ích và tiến độ của khách hàng lên hàng đầu</h4>
                <p class="text-slate-600 text-xs">Kho hàng quy mô lớn tại Đà Nẵng luôn sẵn số lượng lớn các chủng loại bu lông inox, bu lông cường độ cao, ốc vít... đáp ứng giao ngay cho công trình.</p>
              </div>
            </div>
            <div class="flex items-start gap-2.5">
              <span class="w-6 h-6 rounded-full bg-[#0b3b69] text-white font-bold text-xs flex items-center justify-center shrink-0 mt-0.5">2</span>
              <div>
                <h4 class="font-bold text-slate-900">Gia công theo bản vẽ kỹ thuật chính xác, nhanh chóng</h4>
                <p class="text-slate-600 text-xs">Nhận tiện ren, uốn gia công bu lông neo móng (J, L, I, U), bản mã, thanh ren phi tiêu chuẩn theo đúng bản vẽ thiết kế của từng dự án.</p>
              </div>
            </div>
            <div class="flex items-start gap-2.5">
              <span class="w-6 h-6 rounded-full bg-[#0b3b69] text-white font-bold text-xs flex items-center justify-center shrink-0 mt-0.5">3</span>
              <div>
                <h4 class="font-bold text-slate-900">Giá gốc tận xưởng – Cam kết chất lượng 100%</h4>
                <p class="text-slate-600 text-xs">Nhập khẩu và sản xuất trực tiếp không qua trung gian, đầy đủ chứng chỉ chất lượng CO, CQ, chiết khấu cao cho nhà thầu xây dựng và đại lý.</p>
              </div>
            </div>
          </div>
        </div>

        <!-- 6 Ảnh thực tế Công ty TNHH SX & TM Hiếu Linh từ Google Drive -->
        <div class="lg:col-span-7 grid grid-cols-2 sm:grid-cols-3 gap-2.5">
          <div class="border border-slate-200 rounded overflow-hidden bg-slate-50">
            <img src="https://lh3.googleusercontent.com/d/1Ni8LciD0bmwlg_eUju2eR0HHTjfPLsdy" data-fileid="1Ni8LciD0bmwlg_eUju2eR0HHTjfPLsdy" onerror="handleDriveImageFallback(this, 'Cơ Sở Hiếu Linh')" alt="Hình ảnh thực tế Công ty Hiếu Linh 1" class="w-full h-32 md:h-36 object-cover">
            <div class="p-1.5 text-[11px] font-semibold text-center text-slate-700">Cơ sở & Kho hàng Hiếu Linh</div>
          </div>
          <div class="border border-slate-200 rounded overflow-hidden bg-slate-50">
            <img src="https://lh3.googleusercontent.com/d/19pSPBtFEBrASWbsDTW5bLQfhppQ3iWiE" data-fileid="19pSPBtFEBrASWbsDTW5bLQfhppQ3iWiE" onerror="handleDriveImageFallback(this, 'Kho Bu Lông')" alt="Hình ảnh thực tế Công ty Hiếu Linh 2" class="w-full h-32 md:h-36 object-cover">
            <div class="p-1.5 text-[11px] font-semibold text-center text-slate-700">Kệ kho Bu lông – Ốc vít</div>
          </div>
          <div class="border border-slate-200 rounded overflow-hidden bg-slate-50">
            <img src="https://lh3.googleusercontent.com/d/1-o2Q-i8PT8ZrXSAkhNFtZPLF6OdgS-64" data-fileid="1-o2Q-i8PT8ZrXSAkhNFtZPLF6OdgS-64" onerror="handleDriveImageFallback(this, 'Xưởng Sản Xuất')" alt="Hình ảnh thực tế Công ty Hiếu Linh 3" class="w-full h-32 md:h-36 object-cover">
            <div class="p-1.5 text-[11px] font-semibold text-center text-slate-700">Xưởng sản xuất & Gia công</div>
          </div>
          <div class="border border-slate-200 rounded overflow-hidden bg-slate-50">
            <img src="https://lh3.googleusercontent.com/d/1UnsDmjeF_4yTHf3cLAvO_CwbVZnY2ro1" data-fileid="1UnsDmjeF_4yTHf3cLAvO_CwbVZnY2ro1" onerror="handleDriveImageFallback(this, 'Vật Tư Sẵn Kho')" alt="Hình ảnh thực tế Công ty Hiếu Linh 4" class="w-full h-32 md:h-36 object-cover">
            <div class="p-1.5 text-[11px] font-semibold text-center text-slate-700">Vật tư phân loại theo DIN</div>
          </div>
          <div class="border border-slate-200 rounded overflow-hidden bg-slate-50">
            <img src="https://lh3.googleusercontent.com/d/1r4PQZaD0Xu5hdgKWld0fhZWU3kf5H4sG" data-fileid="1r4PQZaD0Xu5hdgKWld0fhZWU3kf5H4sG" onerror="handleDriveImageFallback(this, 'Máy Móc Thiết Bị')" alt="Hình ảnh thực tế Công ty Hiếu Linh 5" class="w-full h-32 md:h-36 object-cover">
            <div class="p-1.5 text-[11px] font-semibold text-center text-slate-700">Thiết bị & Kiểm định</div>
          </div>
          <div class="border border-slate-200 rounded overflow-hidden bg-slate-50">
            <img src="https://lh3.googleusercontent.com/d/14ofsjDJ8MA8KNkcIOU-Pe6Z__XzKdK1r" data-fileid="14ofsjDJ8MA8KNkcIOU-Pe6Z__XzKdK1r" onerror="handleDriveImageFallback(this, 'Xuất Kho Giao Hàng')" alt="Hình ảnh thực tế Công ty Hiếu Linh 6" class="w-full h-32 md:h-36 object-cover">
            <div class="p-1.5 text-[11px] font-semibold text-center text-slate-700">Đóng gói & Giao công trình</div>
          </div>
        </div>
      </div>
    </section>

    <!-- ================= SECTION 5: FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ ================= -->
    <section id="form-bao-gia" class="bg-white p-3.5 md:p-5 rounded-lg shadow-sm border border-slate-200">
      <div class="section-title-container">
        <div class="section-title-main">
          <i class="fa-solid fa-file-invoice-dollar"></i>
          <span>ĐĂNG KÝ YÊU CẦU TƯ VẤN & NHẬN BÁO GIÁ SỈ NHANH</span>
        </div>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-center">
        <div class="lg:col-span-5 bg-gradient-to-br from-[#0b3b69] to-[#145388] text-white p-4 md:p-5 rounded-lg space-y-3">
          <h3 class="text-base md:text-lg font-extrabold uppercase text-amber-300">
            NHẬN BẢNG GIÁ BU LÔNG ỐC VÍT CHIẾT KHẤU CAO
          </h3>
          <p class="text-xs leading-relaxed text-blue-100">
            Quý khách hàng, nhà thầu xây dựng, xưởng cơ khí cần báo giá số lượng lớn hoặc đặt gia công theo bản vẽ vui lòng điền thông tin bên cạnh. Bộ phận kinh doanh của <strong>Hiếu Linh</strong> sẽ liên hệ gửi báo giá chi tiết ngay lập tức!
          </p>
          <div class="space-y-2 pt-1 text-xs">
            <div class="flex items-center gap-2.5">
              <i class="fa-solid fa-phone-volume text-amber-400 w-4"></i>
              <span><strong>Hotline / Zalo báo giá:</strong> 0905.767.337</span>
            </div>
            <div class="flex items-center gap-2.5">
              <i class="fa-solid fa-location-dot text-amber-400 w-4"></i>
              <span><strong>Địa chỉ:</strong> 47 Đội Cung, Phường Cẩm Lệ, TP Đà Nẵng</span>
            </div>
            <div class="flex items-center gap-2.5">
              <i class="fa-brands fa-facebook text-amber-400 w-4"></i>
              <span><strong>Facebook:</strong> fb.com/linh.hieu.161</span>
            </div>
          </div>
        </div>

        <div class="lg:col-span-7">
          <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="grid grid-cols-1 sm:grid-cols-2 gap-3 text-xs">
            <div>
              <label class="block font-semibold text-slate-700 mb-1">Họ và tên / Tên đơn vị *</label>
              <input id="qName" type="text" required placeholder="Nhập họ tên hoặc tên công ty..." class="w-full px-3 py-2 border border-slate-300 rounded focus:outline-none focus:border-[#0b3b69]">
            </div>
            <div>
              <label class="block font-semibold text-slate-700 mb-1">Số điện thoại / Zalo nhận báo giá *</label>
              <input id="qPhone" type="tel" required placeholder="Ví dụ: 0905767337" class="w-full px-3 py-2 border border-slate-300 rounded focus:outline-none focus:border-[#0b3b69]">
            </div>
            <div>
              <label class="block font-semibold text-slate-700 mb-1">Danh mục sản phẩm quan tâm</label>
              <select id="qCategory" class="w-full px-3 py-2 border border-slate-300 rounded focus:outline-none focus:border-[#0b3b69] bg-white">
                <option value="Bu lông Inox 201 / 304 / 316">Bu lông Inox 201 / 304 / 316</option>
                <option value="Bu lông cường độ cao 8.8 / 10.9">Bu lông cường độ cao 8.8 / 10.9</option>
                <option value="Bu lông neo móng (J, L, I, U)">Bu lông neo móng (J, L, I, U)</option>
                <option value="Bu lông nở - Tắc kê nở - Hóa chất">Bu lông nở - Tắc kê nở - Hóa chất</option>
                <option value="Ốc vít Inox / Vít bắn tôn / Vít tự khoan">Ốc vít Inox / Vít bắn tôn / Vít tự khoan</option>
                <option value="Đai ốc (Êcu) - Vòng đệm (Long đền)">Đai ốc (Êcu) - Vòng đệm (Long đền)</option>
                <option value="Thanh ren - Ubolt - Cáp thép - Tăng đơ">Thanh ren - Ubolt - Cáp thép - Tăng đơ</option>
                <option value="Gia công cơ khí theo bản vẽ">Gia công cơ khí theo bản vẽ</option>
              </select>
            </div>
            <div>
              <label class="block font-semibold text-slate-700 mb-1">Quy cách & Số lượng dự kiến</label>
              <input id="qQuantity" type="text" placeholder="VD: M12x50 Inox 304 - 2.000 bộ" class="w-full px-3 py-2 border border-slate-300 rounded focus:outline-none focus:border-[#0b3b69]">
            </div>
            <div class="sm:col-span-2">
              <label class="block font-semibold text-slate-700 mb-1">Nội dung yêu cầu chi tiết</label>
              <textarea id="qNote" rows="2" placeholder="Nhập thêm quy cách, tiêu chuẩn DIN/JIS hoặc địa điểm giao hàng..." class="w-full px-3 py-2 border border-slate-300 rounded focus:outline-none focus:border-[#0b3b69]"></textarea>
            </div>
            <div class="sm:col-span-2 flex flex-wrap items-center gap-3">
              <button type="submit" class="bg-[#d9251d] hover:bg-red-700 text-white font-bold px-5 py-2.5 rounded shadow transition text-xs uppercase">
                <i class="fa-solid fa-paper-plane mr-1.5"></i>Gửi Yêu Cầu Báo Giá Ngay
              </button>
              <span id="quoteSuccessMsg" class="hidden text-emerald-700 font-semibold text-xs">
                <i class="fa-solid fa-circle-check mr-1"></i>Đã ghi nhận yêu cầu! Chúng tôi sẽ liên hệ SĐT của quý khách ngay.
              </span>
            </div>
          </form>
        </div>
      </div>
    </section>

    <!-- ================= SECTION 6: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (Kinh nghiệm hay & Tin tức kỹ thuật) ================= -->
    <section id="tin-tuc-trang-chu" class="bg-white p-3.5 md:p-5 rounded-lg shadow-sm border border-slate-200">
      <div class="section-title-container">
        <div class="section-title-main">
          <i class="fa-solid fa-newspaper"></i>
          <span>DANH MỤC BÀI VIẾT - KINH NGHIỆM KỸ THUẬT & BẢNG TRA TIÊU CHUẨN</span>
        </div>
      </div>

      <!-- Các tab danh mục bài viết -->
      <div class="flex flex-wrap items-center gap-2 mb-3.5 text-xs">
        <button type="button" onclick="filterPosts('all')" class="post-cat-btn px-3 py-1 rounded bg-[#0b3b69] text-white font-semibold">Tất cả bài viết</button>
        <button type="button" onclick="filterPosts('Tiêu chuẩn bu lông')" class="post-cat-btn px-3 py-1 rounded bg-slate-100 text-slate-700 hover:bg-slate-200 font-semibold">Bảng tra tiêu chuẩn bu lông</button>
        <button type="button" onclick="filterPosts('Kinh nghiệm thi công')" class="post-cat-btn px-3 py-1 rounded bg-slate-100 text-slate-700 hover:bg-slate-200 font-semibold">Kinh nghiệm thi công</button>
        <button type="button" onclick="filterPosts('Báo giá kim khí')" class="post-cat-btn px-3 py-1 rounded bg-slate-100 text-slate-700 hover:bg-slate-200 font-semibold">Tin tức & Báo giá</button>
      </div>

      <div id="blogPostsGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-3.5">
        <!-- Bài viết 1 -->
        <article data-postcat="Kinh nghiệm thi công" class="border border-slate-200 rounded-lg overflow-hidden flex flex-col justify-between bg-white hover:shadow-md transition">
          <div>
            <img src="https://lh3.googleusercontent.com/d/1tQdlh3702DBaLcPsGnEcFI2mpGWFztp1" data-fileid="1tQdlh3702DBaLcPsGnEcFI2mpGWFztp1" onerror="handleDriveImageFallback(this, 'Bu Lông Neo')" alt="Bu lông neo móng chữ J và chữ L" class="w-full h-36 object-cover">
            <div class="p-3">
              <div class="text-[10.5px] font-semibold text-[#0b3b69] uppercase mb-1">Kinh nghiệm thi công</div>
              <h3 class="text-xs md:text-[13px] font-bold text-slate-800 leading-snug mb-1.5">
                Bu lông neo móng chữ J và chữ L: Khác nhau khi sử dụng trong kết cấu bê tông thế nào?
              </h3>
              <p class="text-[11.5px] text-slate-600 leading-relaxed">
                Trong thi công nhà thép tiền chế và trạm biến áp, việc chọn đúng bu lông neo chữ J hay chữ L quyết định khả năng chịu lực nhổ và độ bền móng...
              </p>
            </div>
          </div>
          <div class="px-3 pb-2.5 text-[11px] font-semibold text-[#d9251d] flex items-center justify-between border-t border-slate-100 pt-2">
            <span><i class="fa-regular fa-calendar mr-1"></i>hieulinh.com</span>
            <a href="#form-bao-gia" class="hover:underline">Tư vấn kỹ thuật <i class="fa-solid fa-arrow-right"></i></a>
          </div>
        </article>

        <!-- Bài viết 2 -->
        <article data-postcat="Tiêu chuẩn bu lông" class="border border-slate-200 rounded-lg overflow-hidden flex flex-col justify-between bg-white hover:shadow-md transition">
          <div>
            <img src="https://lh3.googleusercontent.com/d/1PIIAgUNcV8xjH5wYlM7YXQ1rSMbFdrKy" data-fileid="1PIIAgUNcV8xjH5wYlM7YXQ1rSMbFdrKy" onerror="handleDriveImageFallback(this, 'Cấp Bền 8.8 10.9')" alt="So sánh bu lông cấp bền 8.8 và 10.9" class="w-full h-36 object-cover">
            <div class="p-3">
              <div class="text-[10.5px] font-semibold text-[#0b3b69] uppercase mb-1">Tiêu chuẩn bu lông</div>
              <h3 class="text-xs md:text-[13px] font-bold text-slate-800 leading-snug mb-1.5">
                Nên dùng bu lông cấp bền 8.8 hay 10.9 cho kết cấu thép và chế tạo máy công nghiệp?
              </h3>
              <p class="text-[11.5px] text-slate-600 leading-relaxed">
                Bảng tra chi tiết giới hạn bền kéo, giới hạn chảy và lực xiết tiêu chuẩn DIN 931 / DIN 933 của bu lông cường độ cao 8.8 và 10.9...
              </p>
            </div>
          </div>
          <div class="px-3 pb-2.5 text-[11px] font-semibold text-[#d9251d] flex items-center justify-between border-t border-slate-100 pt-2">
            <span><i class="fa-regular fa-calendar mr-1"></i>hieulinh.com</span>
            <a href="#form-bao-gia" class="hover:underline">Tư vấn kỹ thuật <i class="fa-solid fa-arrow-right"></i></a>
          </div>
        </article>

        <!-- Bài viết 3 -->
        <article data-postcat="Kinh nghiệm thi công" class="border border-slate-200 rounded-lg overflow-hidden flex flex-col justify-between bg-white hover:shadow-md transition">
          <div>
            <img src="https://lh3.googleusercontent.com/d/1KzBEj6UpOEQSvUEaIe5_P6gCMXKy-oWz" data-fileid="1KzBEj6UpOEQSvUEaIe5_P6gCMXKy-oWz" onerror="handleDriveImageFallback(this, 'Tắc Kê Nở')" alt="Nguyên nhân tắc kê nở bị tuột" class="w-full h-36 object-cover">
            <div class="p-3">
              <div class="text-[10.5px] font-semibold text-[#0b3b69] uppercase mb-1">Kinh nghiệm thi công</div>
              <h3 class="text-xs md:text-[13px] font-bold text-slate-800 leading-snug mb-1.5">
                Bu lông nở (Tắc kê nở) bị tuột khỏi bê tông: 6 nguyên nhân thường gặp và cách khắc phục
              </h3>
              <p class="text-[11.5px] text-slate-600 leading-relaxed">
                Hướng dẫn chọn đường kính mũi khoan chuẩn xác và quy trình đóng tắc kê nở inox 304, bu lông hóa chất đảm bảo tải trọng an toàn...
              </p>
            </div>
          </div>
          <div class="px-3 pb-2.5 text-[11px] font-semibold text-[#d9251d] flex items-center justify-between border-t border-slate-100 pt-2">
            <span><i class="fa-regular fa-calendar mr-1"></i>hieulinh.com</span>
            <a href="#form-bao-gia" class="hover:underline">Tư vấn kỹ thuật <i class="fa-solid fa-arrow-right"></i></a>
          </div>
        </article>

        <!-- Bài viết 4 -->
        <article data-postcat="Báo giá kim khí" class="border border-slate-200 rounded-lg overflow-hidden flex flex-col justify-between bg-white hover:shadow-md transition">
          <div>
            <img src="https://lh3.googleusercontent.com/d/1UQbGPe6AD77GJD1078uMJnKsIpXv7NZw" data-fileid="1UQbGPe6AD77GJD1078uMJnKsIpXv7NZw" onerror="handleDriveImageFallback(this, 'Inox 201 304 316')" alt="Phân biệt bu lông Inox 201 304 316" class="w-full h-36 object-cover">
            <div class="p-3">
              <div class="text-[10.5px] font-semibold text-[#0b3b69] uppercase mb-1">Báo giá kim khí</div>
              <h3 class="text-xs md:text-[13px] font-bold text-slate-800 leading-snug mb-1.5">
                Cách phân biệt Bu lông Inox 201, Inox 304 và Inox 316 chuẩn xác cho công trình ven biển
              </h3>
              <p class="text-[11.5px] text-slate-600 leading-relaxed">
                Tại khu vực Đà Nẵng và ven biển miền Trung, lựa chọn mác thép không gỉ SUS 304 hay SUS 316 giúp chống ăn mòn muối biển tối ưu nhất...
              </p>
            </div>
          </div>
          <div class="px-3 pb-2.5 text-[11px] font-semibold text-[#d9251d] flex items-center justify-between border-t border-slate-100 pt-2">
            <span><i class="fa-regular fa-calendar mr-1"></i>hieulinh.com</span>
            <a href="#form-bao-gia" class="hover:underline">Nhận bảng giá <i class="fa-solid fa-arrow-right"></i></a>
          </div>
        </article>
      </div>
    </section>

    <!-- ================= SECTION 7: ĐƯA FACEBOOK VÀ ẢNH GOOGLE MAP RA NGOÀI TRANG CHỦ ================= -->
    <section id="ban-do-lien-he" class="bg-white p-3.5 md:p-5 rounded-lg shadow-sm border border-slate-200">
      <div class="section-title-container">
        <div class="section-title-main">
          <i class="fa-solid fa-map-location-dot"></i>
          <span>BẢN ĐỒ GOOGLE MAPS & KẾT NỐI FACEBOOK TRANG CHỦ</span>
        </div>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-4 items-stretch">
        
        <!-- Cột trái: Đưa Facebook https://www.facebook.com/linh.hieu.161 ra ngoài trang chủ -->
        <div class="lg:col-span-5 border border-slate-200 rounded-lg p-3.5 bg-slate-50 flex flex-col justify-between space-y-3">
          <div class="space-y-2.5">
            <div class="flex items-center gap-3 pb-2.5 border-b border-slate-200">
              <img 
                src="https://lh3.googleusercontent.com/d/17oD64Vcth1K3-lQutkMkY-VmQkMAO_yN" 
                data-fileid="17oD64Vcth1K3-lQutkMkY-VmQkMAO_yN"
                onerror="handleDriveImageFallback(this, 'HIẾU LINH')"
                alt="Logo Hiếu Linh" 
                class="w-12 h-12 object-contain rounded border border-slate-200 bg-white p-1 shrink-0"
              >
              <div class="min-w-0">
                <h3 class="text-xs md:text-sm font-extrabold text-[#0b3b69] truncate">
                  KẾT NỐI FACEBOOK HIẾU LINH
                </h3>
                <a href="https://www.facebook.com/linh.hieu.161" target="_blank" rel="noopener" class="text-[11.5px] text-blue-600 hover:underline break-all">
                  https://www.facebook.com/linh.hieu.161
                </a>
              </div>
            </div>

            <div class="grid grid-cols-2 gap-2">
              <img src="https://lh3.googleusercontent.com/d/1Ni8LciD0bmwlg_eUju2eR0HHTjfPLsdy" data-fileid="1Ni8LciD0bmwlg_eUju2eR0HHTjfPLsdy" onerror="handleDriveImageFallback(this, 'Hiếu Linh')" alt="Ảnh hoạt động Hiếu Linh" class="w-full h-24 object-cover rounded border border-slate-200">
              <img src="https://lh3.googleusercontent.com/d/19pSPBtFEBrASWbsDTW5bLQfhppQ3iWiE" data-fileid="19pSPBtFEBrASWbsDTW5bLQfhppQ3iWiE" onerror="handleDriveImageFallback(this, 'Kho Hàng')" alt="Ảnh kho hàng Hiếu Linh" class="w-full h-24 object-cover rounded border border-slate-200">
            </div>

            <div class="text-xs text-slate-700 space-y-1 pt-1">
              <div><i class="fa-solid fa-building text-[#0b3b69] w-4"></i> <strong>Đơn vị:</strong> CÔNG TY TNHH SX & TM HIẾU LINH</div>
              <div><i class="fa-solid fa-location-dot text-[#d9251d] w-4"></i> <strong>Địa chỉ:</strong> 47 Đội Cung, Phường Cẩm Lệ, TP Đà Nẵng</div>
              <div><i class="fa-solid fa-phone text-emerald-600 w-4"></i> <strong>Điện thoại / Zalo:</strong> <a href="tel:0905767337" class="font-bold text-[#d9251d]">0905.767.337</a></div>
            </div>
          </div>

          <div class="flex flex-wrap gap-2 pt-2">
            <a href="https://www.facebook.com/linh.hieu.161" target="_blank" rel="noopener" class="flex-1 bg-[#1877F2] hover:bg-blue-700 text-white text-center py-2 px-3 rounded font-bold text-xs">
              <i class="fa-brands fa-facebook-f mr-1.5"></i>Truy Cập Facebook Hiếu Linh
            </a>
            <a href="https://zalo.me/0905767337" target="_blank" rel="noopener" class="bg-[#0068ff] hover:bg-blue-600 text-white text-center py-2 px-3 rounded font-bold text-xs">
              Chat Zalo Ngay
            </a>
          </div>
        </div>

        <!-- Cột phải: Đưa ảnh Google Map & Bản đồ tương tác 47 Đội Cung, Phường Cẩm Lệ, TP Đà Nẵng ra ngoài trang chủ -->
        <div class="lg:col-span-7 border border-slate-200 rounded-lg overflow-hidden flex flex-col justify-between bg-slate-50">
          <div class="p-2.5 bg-white border-b border-slate-200 flex flex-wrap items-center justify-between gap-2">
            <div class="text-xs font-bold text-[#0b3b69]">
              <i class="fa-solid fa-location-crosshairs text-[#d9251d] mr-1"></i>
              Bản đồ chỉ đường: 47 Đội Cung, Phường Cẩm Lệ, TP Đà Nẵng
            </div>
            <a href="https://share.google/ISuPLKoyYY5jOiivg" target="_blank" rel="noopener" class="bg-[#0b3b69] hover:bg-[#145388] text-white text-[11px] font-bold px-2.5 py-1 rounded">
              <i class="fa-solid fa-diamond-turn-right mr-1"></i>Mở Google Maps Chỉ Đường
            </a>
          </div>

          <!-- Khung Google Map trực tiếp ngoài trang chủ -->
          <div class="w-full h-64 md:h-72 relative bg-slate-200">
            <iframe 
              title="Bản đồ Công ty TNHH Sản xuất và Thương mại Hiếu Linh - 47 Đội Cung, Phường Cẩm Lệ, TP Đà Nẵng"
              src="https://maps.google.com/maps?q=47%20%C4%90%E1%BB%99i%20Cung,%20C%E1%BA%A9m%20L%E1%BB%87,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
              class="w-full h-full border-0"
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade">
            </iframe>
          </div>

          <div class="p-2.5 bg-white border-t border-slate-200 flex flex-wrap items-center justify-between gap-2 text-[11.5px] text-slate-600">
            <span>Link Google Map chính thức: <a href="https://share.google/ISuPLKoyYY5jOiivg" target="_blank" rel="noopener" class="text-blue-600 font-semibold hover:underline">https://share.google/ISuPLKoyYY5jOiivg</a></span>
            <span class="font-semibold text-[#0b3b69]">Hotline chỉ đường: 0905.767.337</span>
          </div>
        </div>

      </div>
    </section>

  </main>

  <!-- ================= FOOTER (Chuẩn 4 Cột Flatsome) ================= -->
  <footer class="bg-[#072849] text-white mt-6 border-t-4 border-[#d9251d]">
    <div class="flatsome-container py-8">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6 text-xs leading-relaxed">
        
        <!-- Cột 1: Thông tin công ty -->
        <div class="lg:col-span-4 space-y-2.5">
          <div class="flex items-center gap-2.5">
            <img 
              src="https://lh3.googleusercontent.com/d/17oD64Vcth1K3-lQutkMkY-VmQkMAO_yN" 
              data-fileid="17oD64Vcth1K3-lQutkMkY-VmQkMAO_yN"
              onerror="handleDriveImageFallback(this, 'HIẾU LINH')"
              alt="Logo Công ty Hiếu Linh" 
              class="h-10 w-auto object-contain bg-white p-1 rounded"
            >
            <h3 class="font-extrabold text-sm text-amber-300 uppercase leading-snug">
              CÔNG TY TNHH SẢN XUẤT VÀ THƯƠNG MẠI HIẾU LINH
            </h3>
          </div>
          <p class="text-blue-100">
            Chuyên sản xuất, gia công và phân phối sỉ lẻ Bu lông Inox, Bu lông cường độ cao, Bu lông neo móng, Ốc vít, Thanh ren, Đai ốc, Vòng đệm, Cáp thép và Thiết bị công nghiệp chất lượng cao trên toàn quốc.
          </p>
          <ul class="space-y-1 text-blue-100">
            <li><i class="fa-solid fa-location-dot text-amber-400 w-4"></i> <strong>Địa chỉ:</strong> 47 Đội Cung, Phường Cẩm Lệ, TP Đà Nẵng</li>
            <li><i class="fa-solid fa-phone-volume text-amber-400 w-4"></i> <strong>Hotline / Zalo:</strong> 0905.767.337</li>
            <li><i class="fa-solid fa-id-card text-amber-400 w-4"></i> <strong>Mã số thuế:</strong> 0401377003</li>
            <li><i class="fa-solid fa-globe text-amber-400 w-4"></i> <strong>Website:</strong> hieulinh.com</li>
          </ul>
        </div>

        <!-- Cột 2: Danh mục sản phẩm chủ lực -->
        <div class="lg:col-span-3 space-y-2">
          <h4 class="font-bold text-sm uppercase text-amber-300 border-b border-white/15 pb-1.5">
            SẢN PHẨM CHỦ LỰC
          </h4>
          <ul class="space-y-1.5 text-blue-100">
            <li><a href="#sec-bulong" onclick="filterByCategory('Bu lông inox')" class="hover:text-amber-300"><i class="fa-solid fa-angle-right mr-1.5"></i>Bu lông Inox 201 / 304 / 316</a></li>
            <li><a href="#sec-bulong" onclick="filterByCategory('Bu lông cường độ cao')" class="hover:text-amber-300"><i class="fa-solid fa-angle-right mr-1.5"></i>Bu lông cường độ cao 8.8 / 10.9</a></li>
            <li><a href="#sec-bulong" onclick="filterByCategory('Bu lông neo móng')" class="hover:text-amber-300"><i class="fa-solid fa-angle-right mr-1.5"></i>Bu lông neo móng chữ J, L, I, U</a></li>
            <li><a href="#sec-bulong" onclick="filterByCategory('Bu lông nở – Tắc kê nở')" class="hover:text-amber-300"><i class="fa-solid fa-angle-right mr-1.5"></i>Bu lông nở – Tắc kê nở – Hóa chất</a></li>
            <li><a href="#sec-ocvit" onclick="filterByCategory('Vít inox')" class="hover:text-amber-300"><i class="fa-solid fa-angle-right mr-1.5"></i>Ốc vít Inox – Vít tự khoan – Vít tôn</a></li>
            <li><a href="#sec-sanphamkhac" onclick="filterByCategory('Thanh ren – ty ren inox')" class="hover:text-amber-300"><i class="fa-solid fa-angle-right mr-1.5"></i>Thanh ren – Ty ren – Ubolt – Cáp thép</a></li>
          </ul>
        </div>

        <!-- Cột 3: Hỗ trợ khách hàng -->
        <div class="lg:col-span-2 space-y-2">
          <h4 class="font-bold text-sm uppercase text-amber-300 border-b border-white/15 pb-1.5">
            HỖ TRỢ KHÁCH HÀNG
          </h4>
          <ul class="space-y-1.5 text-blue-100">
            <li><a href="#form-bao-gia" class="hover:text-amber-300">1. Hướng dẫn đặt hàng & Báo giá</a></li>
            <li><a href="#form-bao-gia" class="hover:text-amber-300">2. Chính sách vận chuyển toàn quốc</a></li>
            <li><a href="#form-bao-gia" class="hover:text-amber-300">3. Chính sách bảo hành & Đổi trả</a></li>
            <li><a href="#tin-tuc-trang-chu" class="hover:text-amber-300">4. Bảng tra tiêu chuẩn Bu lông</a></li>
            <li><a href="https://www.facebook.com/linh.hieu.161" target="_blank" rel="noopener" class="hover:text-amber-300">5. Fanpage Facebook Hiếu Linh</a></li>
            <li><a href="https://share.google/ISuPLKoyYY5jOiivg" target="_blank" rel="noopener" class="hover:text-amber-300">6. Chỉ đường Google Maps</a></li>
          </ul>
        </div>

        <!-- Cột 4: Kết nối nhanh -->
        <div class="lg:col-span-3 space-y-2.5">
          <h4 class="font-bold text-sm uppercase text-amber-300 border-b border-white/15 pb-1.5">
            LIÊN HỆ ĐẶT HÀNG NHANH
          </h4>
          <p class="text-blue-100">
            Cam kết hàng chuẩn chất lượng, giá sỉ cạnh tranh nhất thị trường, giao hàng nhanh đến tận chân công trình.
          </p>
          <div class="p-3 rounded bg-white/10 border border-white/15 space-y-1.5">
            <div class="text-[11px] text-amber-300 font-semibold uppercase">Hotline Tư Vấn 24/7:</div>
            <a href="tel:0905767337" class="block text-lg font-extrabold text-white hover:text-amber-300">
              0905.767.337
            </a>
            <div class="flex gap-2 pt-1">
              <a href="https://zalo.me/0905767337" target="_blank" rel="noopener" class="bg-[#0068ff] px-2.5 py-1 rounded text-[11px] font-bold text-white">Zalo: 0905.767.337</a>
              <a href="https://www.facebook.com/linh.hieu.161" target="_blank" rel="noopener" class="bg-[#1877F2] px-2.5 py-1 rounded text-[11px] font-bold text-white">Facebook</a>
            </div>
          </div>
        </div>

      </div>
    </div>

    <div class="bg-[#041a30] py-3 text-center text-[11.5px] text-blue-200 border-t border-white/10">
      <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
        <span>© Bản quyền thuộc về <strong>CÔNG TY TNHH SẢN XUẤT VÀ THƯƠNG MẠI HIẾU LINH</strong> (hieulinh.com)</span>
        <span>Địa chỉ: 47 Đội Cung, Phường Cẩm Lệ, TP Đà Nẵng | ĐT: 0905.767.337</span>
      </div>
    </div>
  </footer>

  <!-- ================= NÚT LIÊN HỆ NỔI BẬT ZALO, FACEBOOK, HOTLINE (Tương thích Máy tính & Điện thoại) ================= -->
  <div class="floating-contact-wrap" aria-label="Liên hệ nhanh">
    <!-- Nút Zalo -->
    <a href="https://zalo.me/0905767337" target="_blank" rel="noopener" class="floating-btn bg-[#0068ff]">
      <span class="floating-icon-circle font-extrabold text-xs">Zalo</span>
      <span>Chat Zalo</span>
    </a>

    <!-- Nút Facebook -->
    <a href="https://www.facebook.com/linh.hieu.161" target="_blank" rel="noopener" class="floating-btn bg-[#1877F2]">
      <span class="floating-icon-circle"><i class="fa-brands fa-facebook-f"></i></span>
      <span>Facebook</span>
    </a>

    <!-- Nút Hotline -->
    <a href="tel:0905767337" class="floating-btn bg-[#d9251d] pulse-hotline">
      <span class="floating-icon-circle"><i class="fa-solid fa-phone-volume"></i></span>
      <span>0905.767.337</span>
    </a>
  </div>

  <!-- ================= JAVASCRIPT XỬ LÝ SẢN PHẨM, SLIDER, BỘ LỌC & FALLBACK ẢNH GOOGLE DRIVE ================= -->
  <script>
    // Cơ chế tự động chuyển đổi link dự phòng khi tải ảnh từ Google Drive để đảm bảo hiển thị 100%
    function handleDriveImageFallback(imgEl, labelText) {
      const fileId = imgEl.getAttribute('data-fileid');
      const step = parseInt(imgEl.getAttribute('data-fallback-step') || '0', 10);
      if (fileId && step === 0) {
        imgEl.setAttribute('data-fallback-step', '1');
        imgEl.src = 'https://drive.google.com/thumbnail?id=' + fileId + '&sz=w1000';
      } else if (fileId && step === 1) {
        imgEl.setAttribute('data-fallback-step', '2');
        imgEl.src = 'https://drive.google.com/uc?export=view&id=' + fileId;
      } else {
        imgEl.onerror = null;
        imgEl.src = 'https://placehold.co/600x600/0b3b69/ffffff?text=' + encodeURIComponent(labelText || 'HIEULINH.COM');
      }
    }

    // Danh sách sản phẩm thực tế sử dụng toàn bộ 13 link ảnh sản phẩm Google Drive và phân vào đúng danh mục chuẩn bulonghoangha.com
    const productsData = [
      // --- NHÓM 1: BU LÔNG CÁC LOẠI ---
      {
        id: 1,
        section: 'bulong',
        name: 'Bu lông Inox 304 Lục Giác Ngoài Ren Suốt DIN 933 (Đủ kích thước M6 - M30)',
        category: 'Bu lông inox',
        fileId: '1UQbGPe6AD77GJD1078uMJnKsIpXv7NZw',
        oldPrice: '3.500đ',
        newPrice: '2.800đ',
        discount: '-20%',
        unit: '/ bộ'
      },
      {
        id: 2,
        section: 'bulong',
        name: 'Bu lông Cường Độ Cao Cấp Bền 8.8 / 10.9 Đen & Mạ Kẽm DIN 931',
        category: 'Bu lông cường độ cao',
        fileId: '1PIIAgUNcV8xjH5wYlM7YXQ1rSMbFdrKy',
        oldPrice: '6.200đ',
        newPrice: '5.100đ',
        discount: '-18%',
        unit: '/ con'
      },
      {
        id: 3,
        section: 'bulong',
        name: 'Bu lông Neo Móng Chữ J, L, I, U Gia Công Theo Bản Vẽ Kỹ Thuật (M12 - M56)',
        category: 'Bu lông neo móng',
        fileId: '1tQdlh3702DBaLcPsGnEcFI2mpGWFztp1',
        oldPrice: '28.000đ',
        newPrice: '22.500đ',
        discount: '-20%',
        unit: '/ bộ'
      },
      {
        id: 4,
        section: 'bulong',
        name: 'Bu lông Nở Inox 304 – Tắc Kê Nở Rút & Nở Đạn Chịu Tải Cao',
        category: 'Bu lông nở – Tắc kê nở',
        fileId: '1KzBEj6UpOEQSvUEaIe5_P6gCMXKy-oWz',
        oldPrice: '5.500đ',
        newPrice: '4.500đ',
        discount: '-18%',
        unit: '/ con'
      },
      {
        id: 5,
        section: 'bulong',
        name: 'Bu lông Hóa Chất & Thanh Ren Hóa Chất Kèm Keo Cấy Thép Chính Hãng',
        category: 'Bu lông hóa chất',
        fileId: '1PQ5IuGPl334qx7xJMlpdS7MEXJ99UnZI',
        oldPrice: '18.000đ',
        newPrice: '14.500đ',
        discount: '-19%',
        unit: '/ cây'
      },
      {
        id: 6,
        section: 'bulong',
        name: 'Bu lông Lục Giác Chìm Đầu Trụ DIN 912 Inox 304 & Thép Cường Độ Cao 12.9',
        category: 'Bu lông inox',
        fileId: '1UQbGPe6AD77GJD1078uMJnKsIpXv7NZw',
        oldPrice: '4.200đ',
        newPrice: '3.400đ',
        discount: '-19%',
        unit: '/ con'
      },
      {
        id: 7,
        section: 'bulong',
        name: 'Bu lông Tự Cắt S10T / F10T Chuyên Dụng Cho Kết Cấu Thép Cầu Đường & Nhà Xưởng',
        category: 'Bu lông tự cắt',
        fileId: '1PIIAgUNcV8xjH5wYlM7YXQ1rSMbFdrKy',
        oldPrice: '15.000đ',
        newPrice: '12.500đ',
        discount: '-17%',
        unit: '/ bộ'
      },
      {
        id: 8,
        section: 'bulong',
        name: 'Bu lông Neo Móng Mạ Kẽm Nhúng Nóng Chống Gỉ Sét Công Trình Điện Gió & Nhà Máy',
        category: 'Bu lông neo móng',
        fileId: '1tQdlh3702DBaLcPsGnEcFI2mpGWFztp1',
        oldPrice: '35.000đ',
        newPrice: '28.500đ',
        discount: '-19%',
        unit: '/ bộ'
      },

      // --- NHÓM 2: ỐC VÍT, ĐAI ỐC & VÒNG ĐỆM ---
      {
        id: 9,
        section: 'ocvit',
        name: 'Vít Tự Khoan Inox 410 / 304 Đầu Dù, Đầu Bằng & Đầu Lục Giác Bắn Kim Loại',
        category: 'Vít tự khoan',
        fileId: '1mRn0UrG88BagKsONZ36xSLQb02yMxzlN',
        oldPrice: '850đ',
        newPrice: '680đ',
        discount: '-20%',
        unit: '/ con'
      },
      {
        id: 10,
        section: 'ocvit',
        name: 'Ốc Vít Inox 304 Đầu Cầu / Đầu Bằng Bake (Pake) DIN 7985 & DIN 965',
        category: 'Vít inox',
        fileId: '1nhwPipzoC55rZekP9fXLsSEbQUlwo3DA',
        oldPrice: '750đ',
        newPrice: '600đ',
        discount: '-20%',
        unit: '/ con'
      },
      {
        id: 11,
        section: 'ocvit',
        name: 'Đai Ốc Inox 304 (Êcu Lục Giác DIN 934, Êcu Khóa Nhựa, Êcu Mũ, Êcu Tai Hồng)',
        category: 'Đai ốc inox (Êcu inox)',
        fileId: '1QdRgIyTTlAarxei5zzHUXchTYAaZUqaL',
        oldPrice: '1.200đ',
        newPrice: '950đ',
        discount: '-21%',
        unit: '/ cái'
      },
      {
        id: 12,
        section: 'ocvit',
        name: 'Vòng Đệm Phẳng & Vòng Đệm Vênh Inox 304 / Mạ Kẽm (Long Đền DIN 125 / DIN 127)',
        category: 'Vòng đệm các loại',
        fileId: '1W6ZUjncrWu9x407Za3ayLagjAjjtCz3O',
        oldPrice: '600đ',
        newPrice: '480đ',
        discount: '-20%',
        unit: '/ cái'
      },
      {
        id: 13,
        section: 'ocvit',
        name: 'Vít Bắn Tôn Inox & Mạ Kẽm Có Long Đền Cao Su Chống Thấm Dột Mái Nhà Xưởng',
        category: 'Vít bắn tôn',
        fileId: '1mRn0UrG88BagKsONZ36xSLQb02yMxzlN',
        oldPrice: '950đ',
        newPrice: '750đ',
        discount: '-21%',
        unit: '/ con'
      },
      {
        id: 14,
        section: 'ocvit',
        name: 'Vít Bắn Gỗ Đầu Bằng & Vít Trí Lục Giác Chìm Inox 304 Đủ Quy Cách',
        category: 'Vít bắn gỗ',
        fileId: '1nhwPipzoC55rZekP9fXLsSEbQUlwo3DA',
        oldPrice: '700đ',
        newPrice: '550đ',
        discount: '-21%',
        unit: '/ con'
      },
      {
        id: 15,
        section: 'ocvit',
        name: 'Đai Ốc Cường Độ Cao Cấp Bền 8.8 / 10.9 Đen & Xi Kẽm Chuẩn DIN 934',
        category: 'Đai ốc inox (Êcu inox)',
        fileId: '1QdRgIyTTlAarxei5zzHUXchTYAaZUqaL',
        oldPrice: '1.500đ',
        newPrice: '1.200đ',
        discount: '-20%',
        unit: '/ cái'
      },
      {
        id: 16,
        section: 'ocvit',
        name: 'Long Đền Bản Rộng & Vòng Đệm Chống Xoay Kết Cấu Thép Công Nghiệp',
        category: 'Vòng đệm các loại',
        fileId: '1W6ZUjncrWu9x407Za3ayLagjAjjtCz3O',
        oldPrice: '800đ',
        newPrice: '650đ',
        discount: '-19%',
        unit: '/ cái'
      },

      // --- NHÓM 3: THANH REN, UBALT, CÁP THÉP & VẬT TƯ KHÁC ---
      {
        id: 17,
        section: 'khac',
        name: 'Thanh Ren – Ty Ren Inox 304 & Ty Ren Mạ Kẽm Treo Trần Cơ Điện M&E (M6 - M30)',
        category: 'Thanh ren – ty ren inox',
        fileId: '1SaRc8DH-jK6fvjB1C8bS5VFokGfrgYMi',
        oldPrice: '26.000đ',
        newPrice: '21.000đ',
        discount: '-19%',
        unit: '/ cây 1m'
      },
      {
        id: 18,
        section: 'khac',
        name: 'Ubolt Inox 304 (Cùm U Ôm Ống) & Đai Treo Ống Công Nghiệp Kèm Êcu Long Đền',
        category: 'Ubolt inox',
        fileId: '1yQ-1BXbkJ8iT5xYO61_rEh3WeCAkcF3x',
        oldPrice: '14.000đ',
        newPrice: '11.200đ',
        discount: '-20%',
        unit: '/ bộ'
      },
      {
        id: 19,
        section: 'khac',
        name: 'Tăng Đơ Inox 304 – Mã Ní Chốt Vặn – Khóa Cáp (Ốc Siết Cáp) Đủ Size',
        category: 'Tăng Đơ – Mã ní',
        fileId: '1q_X4xdvhbCPRHty-SX0EtfiUvRZVDhZd',
        oldPrice: '32.000đ',
        newPrice: '26.000đ',
        discount: '-19%',
        unit: '/ cái'
      },
      {
        id: 20,
        section: 'khac',
        name: 'Cáp Thép Mạ Kẽm, Cáp Inox 304 & Dây Xích Inox Chịu Lực Công Nghiệp',
        category: 'Cáp thép',
        fileId: '1q_X4xdvhbCPRHty-SX0EtfiUvRZVDhZd',
        oldPrice: '19.500đ',
        newPrice: '15.800đ',
        discount: '-19%',
        unit: '/ mét'
      }
    ];

    // Hàm tạo HTML thẻ sản phẩm chuẩn Flatsome (Giá giảm giá + % giảm giá góc trên bên trái, tên sản phẩm đầy đủ không cắt chữ)
    function createProductCardHTML(item) {
      return `
        <div class="product-small box" data-category="${item.category}" data-name="${item.name.toLowerCase()}">
          <div class="relative w-full aspect-square bg-slate-100 overflow-hidden border-b border-slate-100">
            <!-- Nhãn % giảm giá góc trên bên trái giống Flatsome -->
            <div class="flatsome-sale-badge">${item.discount}</div>
            <img 
              src="https://lh3.googleusercontent.com/d/${item.fileId}" 
              data-fileid="${item.fileId}"
              onerror="handleDriveImageFallback(this, '${item.category}')"
              alt="${item.name}" 
              class="w-full h-full object-cover hover:scale-105 transition duration-300"
              loading="lazy"
            >
          </div>

          <div class="p-2.5 md:p-3 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[10.5px] font-semibold text-slate-500 uppercase mb-0.5">${item.category}</div>
              <!-- Tên sản phẩm hiển thị đầy đủ 100%, không bị tràn ra ngoài hoặc thiếu chữ -->
              <h3 class="product-title-full">${item.name}</h3>
            </div>

            <div class="pt-1.5 border-t border-slate-100 mt-1">
              <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                <del class="text-[11px] text-slate-400">${item.oldPrice}</del>
                <ins class="text-xs md:text-sm font-extrabold text-[#d9251d] no-underline">${item.newPrice}</ins>
                <span class="text-[10.5px] text-slate-500">${item.unit}</span>
              </div>

              <div class="grid grid-cols-2 gap-1.5">
                <a href="tel:0905767337" class="bg-[#0b3b69] hover:bg-[#145388] text-white text-center py-1.5 px-1 rounded text-[11px] font-bold transition">
                  0905.767.337
                </a>
                <a href="#form-bao-gia" onclick="prefillQuoteProduct('${item.name.replace(/'/g, "\\'")}')" class="bg-amber-400 hover:bg-amber-500 text-[#072849] text-center py-1.5 px-1 rounded text-[11px] font-bold transition">
                  Báo giá sỉ
                </a>
              </div>
            </div>
          </div>
        </div>
      `;
    }

    function renderAllProducts(filterCategory = 'all', searchKeyword = '') {
      const kw = searchKeyword.trim().toLowerCase();
      const matchItem = (p) => {
        const catOk = filterCategory === 'all' || 
          p.category.toLowerCase().includes(filterCategory.toLowerCase()) ||
          (filterCategory === 'Bu Lông' && p.section === 'bulong') ||
          (filterCategory === 'Ốc Vít' && p.section === 'ocvit');
        const kwOk = !kw || p.name.toLowerCase().includes(kw) || p.category.toLowerCase().includes(kw);
        return catOk && kwOk;
      };

      const bulongList = productsData.filter(p => p.section === 'bulong' && matchItem(p));
      const ocvitList = productsData.filter(p => p.section === 'ocvit' && matchItem(p));
      const khacList = productsData.filter(p => p.section === 'khac' && matchItem(p));

      document.getElementById('grid-bulong').innerHTML = bulongList.length
        ? bulongList.map(createProductCardHTML).join('')
        : '<div class="col-span-full text-xs text-slate-500 py-4 text-center">Không có sản phẩm khớp trong nhóm này.</div>';

      document.getElementById('grid-ocvit').innerHTML = ocvitList.length
        ? ocvitList.map(createProductCardHTML).join('')
        : '<div class="col-span-full text-xs text-slate-500 py-4 text-center">Không có sản phẩm khớp trong nhóm này.</div>';

      document.getElementById('grid-khac').innerHTML = khacList.length
        ? khacList.map(createProductCardHTML).join('')
        : '<div class="col-span-full text-xs text-slate-500 py-4 text-center">Không có sản phẩm khớp trong nhóm này.</div>';
    }

    function filterByCategory(catName) {
      const notice = document.getElementById('activeFilterNotice');
      const nameSpan = document.getElementById('activeFilterName');
      if (catName === 'all') {
        notice.classList.add('hidden');
      } else {
        notice.classList.remove('hidden');
        nameSpan.textContent = catName;
      }
      renderAllProducts(catName, '');
    }

    function filterProductsBySearch(keyword) {
      renderAllProducts('all', keyword);
    }

    function prefillQuoteProduct(productName) {
      const noteEl = document.getElementById('qNote');
      if (noteEl) {
        noteEl.value = 'Yêu cầu báo giá sản phẩm: ' + productName;
      }
    }

    function submitQuoteForm(e) {
      e.preventDefault();
      const msg = document.getElementById('quoteSuccessMsg');
      msg.classList.remove('hidden');
      setTimeout(() => {
        msg.classList.add('hidden');
      }, 6000);
      e.target.reset();
    }

    function filterPosts(cat) {
      const articles = document.querySelectorAll('#blogPostsGrid article');
      articles.forEach(art => {
        if (cat === 'all' || art.getAttribute('data-postcat') === cat) {
          art.classList.remove('hidden');
        } else {
          art.classList.add('hidden');
        }
      });
    }

    function toggleMobileDrawer() {
      const drawer = document.getElementById('mobileMenuDrawer');
      drawer.classList.toggle('hidden');
    }

    // ================= SLIDER 2 BANNER TỰ TRƯỢT =================
    let currentBannerIndex = 0;
    let bannerInterval = null;

    function updateBannerCarousel() {
      const track = document.getElementById('bannerTrack');
      const dot0 = document.getElementById('dotSlide0');
      const dot1 = document.getElementById('dotSlide1');
      if (!track) return;
      track.style.transform = `translateX(-${currentBannerIndex * 50}%)`;
      if (currentBannerIndex === 0) {
        dot0.className = 'w-2.5 h-2.5 rounded-full bg-amber-400';
        dot1.className = 'w-2.5 h-2.5 rounded-full bg-white/50';
      } else {
        dot0.className = 'w-2.5 h-2.5 rounded-full bg-white/50';
        dot1.className = 'w-2.5 h-2.5 rounded-full bg-amber-400';
      }
    }

    function nextBannerSlide() {
      currentBannerIndex = (currentBannerIndex + 1) % 2;
      updateBannerCarousel();
    }

    function prevBannerSlide() {
      currentBannerIndex = (currentBannerIndex - 1 + 2) % 2;
      updateBannerCarousel();
    }

    function goToBannerSlide(idx) {
      currentBannerIndex = idx;
      updateBannerCarousel();
    }

    window.addEventListener('DOMContentLoaded', () => {
      renderAllProducts('all', '');
      bannerInterval = setInterval(nextBannerSlide, 4500);
    });
  </script>
</body>
</html>
