<html lang="vi" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ - thienquy.net | Thiết Bị Cơ Khí, Vòng Bi, Dụng Cụ Công Nghiệp</title>
    <meta name="description" content="CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ (thienquy.net) - Chuyên cung cấp vòng bi công nghiệp SKF, Nachi, linh kiện IGBT, dụng cụ đồ nghề, máy hàn, phụ kiện coppha xây dựng tại 258 Trần Cao Vân, Phường Tam Kỳ, TP Đà Nẵng. Hotline: 0978.102.434">

    <!-- Open Graph / Thumbnail Logo khi gửi link trang web -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://thienquy.net/">
    <meta property="og:site_name" content="thienquy.net - CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ">
    <meta property="og:title" content="CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ - Thiết Bị Kỹ Thuật & Vật Tư Công Nghiệp">
    <meta property="og:description" content="Địa chỉ: 258 Trần Cao Vân, Phường Tam Kỳ, TP Đà Nẵng. Điện thoại: 0978.102.434. Chuyên cung cấp thiết bị cơ khí, vòng bi, dụng cụ cầm tay, máy hàn cắt, vật tư kim khí chính hãng.">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=1U-0CiTUSxu2_0XMzT-P7DiJMBhQphugl&sz=w1200">
    <meta property="og:image:alt" content="Logo Công Ty TNHH Kỹ Thuật Thiên Quý">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1U-0CiTUSxu2_0XMzT-P7DiJMBhQphugl&sz=w1200">
    <link rel="icon" href="https://drive.google.com/thumbnail?id=1U-0CiTUSxu2_0XMzT-P7DiJMBhQphugl&sz=w200">

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Google Fonts: Roboto / Inter chuẩn Flatsome Việt hóa -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        flatsome: {
                            primary: '#0f4c81',    /* Xanh kỹ thuật chủ đạo */
                            secondary: '#d9381e',  /* Đỏ cam điểm nhấn giảm giá Flatsome */
                            dark: '#1e293b',
                            light: '#f8fafc',
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền tuyệt đối trên mọi thiết bị */
        html, body {
            max-width: 100%;
            overflow-x: hidden;
            background-color: #f4f6f8;
            color: #222;
        }

        /* Chuẩn khung Container 1200px của Flatsome UX Builder */
        .ux-container {
            width: 100%;
            max-width: 1200px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }

        /* Tinh chỉnh Logo từ Google Drive cho sắc nét, nổi bật và cân đối */
        .logo-refined-box {
            background: #ffffff;
            border: 1.5px solid #e2e8f0;
            box-shadow: 0 2px 8px rgba(15, 76, 129, 0.08);
            overflow: hidden;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .logo-refined-img {
            filter: contrast(1.12) saturate(1.15) brightness(1.02);
            mix-blend-mode: multiply;
            object-fit: contain;
            transition: transform 0.3s ease;
        }
        .logo-refined-box:hover .logo-refined-img {
            transform: scale(1.04);
        }

        /* Flatsome Section Title Style (Line Center / Line Left) */
        .section-title-container {
            margin-bottom: 1.25rem;
        }
        .section-title-main {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #e2e8f0;
            padding-bottom: 0.6rem;
            position: relative;
        }
        .section-title-main::after {
            content: '';
            position: absolute;
            bottom: -2px;
            left: 0;
            width: 180px;
            height: 3px;
            background-color: #0f4c81;
        }

        /* Flatsome Product Box & Quick View ("XEM NHANH") */
        .product-small.box {
            background: #ffffff;
            border: 1px solid #e5e7eb;
            border-radius: 6px;
            overflow: hidden;
            transition: box-shadow 0.25s ease, transform 0.25s ease;
            display: flex;
            flex-direction: column;
            height: 100%;
        }
        .product-small.box:hover {
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.08);
            border-color: #cbd5e1;
        }
        .box-image {
            position: relative;
            width: 100%;
            aspect-ratio: 1 / 1;
            overflow: hidden;
            background-color: #f8fafc;
        }
        .box-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.4s ease;
        }
        .product-small.box:hover .box-image img {
            transform: scale(1.05);
        }

        /* Nút Xem Nhanh chuẩn Flatsome */
        .quick-view-bar {
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            background: rgba(15, 76, 129, 0.92);
            color: #ffffff;
            text-align: center;
            font-size: 0.75rem;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 0.04em;
            padding: 7px 4px;
            transform: translateY(100%);
            transition: transform 0.25s ease, background-color 0.2s ease;
            cursor: pointer;
            z-index: 10;
        }
        .quick-view-bar:hover {
            background: #d9381e;
        }
        .product-small.box:hover .quick-view-bar {
            transform: translateY(0);
        }
        /* Hiển thị nút xem nhanh thuận tiện trên màn hình cảm ứng điện thoại */
        @media (max-width: 768px) {
            .quick-view-bar {
                transform: translateY(0);
                background: rgba(15, 76, 129, 0.85);
                font-size: 0.68rem;
                padding: 5px 4px;
            }
        }

        /* Badge % giảm giá chuẩn Flatsome */
        .badge-container {
            position: absolute;
            top: 8px;
            left: 8px;
            z-index: 10;
        }
        .onsale-badge {
            background-color: #d9381e;
            color: #ffffff;
            font-weight: 700;
            font-size: 0.72rem;
            width: 38px;
            height: 38px;
            border-radius: 9999px;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 2px 6px rgba(217, 56, 30, 0.35);
        }

        /* Hiệu ứng nút liên hệ nổi bật Zalo, Facebook, Hotline */
        @keyframes pulse-ring {
            0% { transform: scale(0.9); opacity: 0.8; }
            70% { transform: scale(1.35); opacity: 0; }
            100% { transform: scale(1.35); opacity: 0; }
        }
        .floating-btn-pulse::before {
            content: '';
            position: absolute;
            inset: 0;
            border-radius: 9999px;
            background: inherit;
            animation: pulse-ring 1.8s infinite;
            z-index: -1;
        }

        /* Ẩn thanh cuộn ngang khi vuốt tab trên mobile */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
</head>
<body class="font-sans antialiased">

    <!-- ==========================================
         TOP BAR ĐƠN GIẢN (Không chứa tùy chọn UX Builder)
         ========================================== -->
    <div class="bg-flatsome-primary text-white text-xs py-2 border-b border-blue-900">
        <div class="ux-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-2 truncate">
                <span class="font-semibold tracking-wide">CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ</span>
                <span class="hidden sm:inline text-blue-200">|</span>
                <span class="hidden sm:inline text-blue-100"><i class="fa-solid fa-globe mr-1"></i>thienquy.net</span>
            </div>
            <div class="flex items-center gap-4 text-blue-100 truncate">
                <span class="truncate"><i class="fa-solid fa-location-dot mr-1 text-amber-300"></i>258 Trần Cao Vân, Phường Tam Kỳ, TP Đà Nẵng</span>
                <a href="https://www.facebook.com/ctthienquy" target="_blank" rel="noopener" class="hidden md:inline-flex items-center gap-1 hover:text-white transition">
                    <i class="fa-brands fa-facebook"></i> Fanpage Thiên Quý
                </a>
            </div>
        </div>
    </div>

    <!-- ==========================================
         HEADER CHÍNH (Không để nút Gọi Ngay trên Header để tránh tràn viền)
         ========================================== -->
    <header id="header" class="bg-white sticky top-0 z-40 shadow-sm border-b border-slate-200">
        <div class="ux-container py-2.5 md:py-3.5">
            <div class="flex items-center justify-between gap-2 sm:gap-4">
                
                <!-- Nút mở Danh mục trên Điện Thoại -->
                <button onclick="toggleMobileDrawer()" aria-label="Mở danh mục" class="lg:hidden p-2.5 rounded-md border border-slate-200 text-slate-700 hover:bg-slate-100 flex-shrink-0">
                    <i class="fa-solid fa-bars text-lg"></i>
                </button>

                <!-- Logo đã tinh chỉnh sắc nét & Tên Công ty -->
                <a href="#" class="flex items-center gap-2.5 sm:gap-3 min-w-0 flex-1 lg:flex-initial">
                    <div class="logo-refined-box w-12 h-12 sm:w-14 sm:h-14 rounded-lg p-1 flex-shrink-0">
                        <img src="https://drive.google.com/thumbnail?id=1U-0CiTUSxu2_0XMzT-P7DiJMBhQphugl&sz=w600"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1U-0CiTUSxu2_0XMzT-P7DiJMBhQphugl';"
                             alt="Logo Công Ty TNHH Kỹ Thuật Thiên Quý"
                             class="logo-refined-img w-full h-full">
                    </div>
                    <div class="min-w-0">
                        <div class="text-[11px] sm:text-xs font-bold text-flatsome-secondary uppercase tracking-wider truncate">thienquy.net</div>
                        <h1 class="text-sm sm:text-base md:text-lg font-extrabold text-flatsome-primary leading-tight truncate">
                            KỸ THUẬT THIÊN QUÝ
                        </h1>
                        <p class="text-[11px] text-slate-500 hidden sm:block truncate">Vòng Bi - Cơ Khí - Dụng Cụ - Điện Công Nghiệp</p>
                    </div>
                </a>

                <!-- Ô Tìm Kiếm Sản Phẩm (Desktop) -->
                <div class="hidden md:flex flex-1 max-w-md mx-2">
                    <div class="relative flex w-full">
                        <input id="desktopSearchInput" type="text" placeholder="Tìm vòng bi SKF, máy hàn, dụng cụ, IGBT, ty ren..."
                               oninput="handleSearchProducts(this.value)"
                               class="w-full pl-3.5 pr-10 py-2 text-sm border border-slate-300 rounded-l-md focus:outline-none focus:border-flatsome-primary">
                        <button onclick="scrollToSection('products-section')" class="bg-flatsome-primary hover:bg-blue-900 text-white px-4 rounded-r-md transition">
                            <i class="fa-solid fa-magnifying-glass text-sm"></i>
                        </button>
                    </div>
                </div>

                <!-- Điều hướng nhanh gọn (Không đặt nút Gọi Ngay để tránh tràn viền) -->
                <nav class="hidden xl:flex items-center gap-5 text-sm font-semibold text-slate-700">
                    <a href="#top" class="hover:text-flatsome-primary transition">Trang chủ</a>
                    <a href="#categories-section" class="hover:text-flatsome-primary transition">Danh mục</a>
                    <a href="#products-section" class="hover:text-flatsome-primary transition">Sản phẩm</a>
                    <a href="#quote-form-section" class="hover:text-flatsome-primary transition">Báo giá</a>
                    <a href="#blog-section" class="hover:text-flatsome-primary transition">Bài viết</a>
                    <a href="#map-fanpage-section" class="hover:text-flatsome-primary transition">Bản đồ</a>
                </nav>

                <!-- Nút Yêu Cầu Báo Giá Nhanh gọn (Icon trên mobile) -->
                <div class="flex items-center gap-1.5 flex-shrink-0">
                    <a href="#quote-form-section" class="inline-flex items-center gap-1.5 bg-slate-100 hover:bg-flatsome-primary hover:text-white text-slate-700 text-xs sm:text-sm font-semibold px-2.5 sm:px-3.5 py-2 rounded-md border border-slate-200 transition">
                        <i class="fa-solid fa-file-invoice text-flatsome-secondary"></i>
                        <span class="hidden sm:inline">Báo giá</span>
                    </a>
                </div>
            </div>

            <!-- Thanh Tìm Kiếm trên Điện thoại (Gọn gàng bên dưới, không gây tràn ngang) -->
            <div class="mt-2 md:hidden">
                <div class="relative flex w-full">
                    <input id="mobileSearchInput" type="text" placeholder="Tìm sản phẩm: Vòng bi, máy hàn, IGBT, dụng cụ..."
                           oninput="handleSearchProducts(this.value)"
                           class="w-full pl-3 pr-9 py-1.5 text-xs border border-slate-300 rounded-l-md focus:outline-none focus:border-flatsome-primary">
                    <button onclick="scrollToSection('products-section')" class="bg-flatsome-primary text-white px-3 rounded-r-md">
                        <i class="fa-solid fa-magnifying-glass text-xs"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Thanh Menu Ngang chuẩn Flatsome Header Bottom (Desktop) -->
        <div class="hidden lg:block bg-slate-800 text-white text-sm">
            <div class="ux-container flex items-center justify-between">
                <div class="flex items-center">
                    <a href="#categories-section" class="bg-flatsome-secondary px-4 py-2.5 font-bold uppercase tracking-wide flex items-center gap-2">
                        <i class="fa-solid fa-list-ul"></i> Danh Mục Sản Phẩm
                    </a>
                    <div class="flex items-center divide-x divide-slate-700 text-xs font-medium">
                        <button onclick="filterCategory('all')" class="px-3.5 py-2.5 hover:bg-slate-700 transition">Tất cả sản phẩm</button>
                        <button onclick="filterCategory('vong-bi-igbt')" class="px-3.5 py-2.5 hover:bg-slate-700 transition">Vòng Bi & IGBT</button>
                        <button onclick="filterCategory('dung-cu-cam-tay')" class="px-3.5 py-2.5 hover:bg-slate-700 transition">Dụng Cụ Cầm Tay</button>
                        <button onclick="filterCategory('may-han-cat')" class="px-3.5 py-2.5 hover:bg-slate-700 transition">Máy Hàn & Cắt Plasma</button>
                        <button onclick="filterCategory('da-cat-mui-khoan')" class="px-3.5 py-2.5 hover:bg-slate-700 transition">Đá Cắt, Mũi Khoan, Nhám</button>
                        <button onclick="filterCategory('coppha-tyren')" class="px-3.5 py-2.5 hover:bg-slate-700 transition">Ty Ren, Coppha & Nâng Hạ</button>
                    </div>
                </div>
                <div class="text-xs text-slate-300 truncate">
                    <span>Đ/c: 258 Trần Cao Vân, P. Tam Kỳ, TP Đà Nẵng</span>
                </div>
            </div>
        </div>
    </header>

    <!-- ==========================================
         KHỐI HERO: DANH MỤC TRÊN MÁY TÍNH + 2 BANNER TỰ TRƯỢT
         (Bố cục UX Builder Row 3 cột + 9 cột)
         ========================================== -->
    <section id="top" class="py-3 md:py-5">
        <div class="ux-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-4 items-stretch">
                
                <!-- Cột Danh Mục Sản Phẩm trên Máy Tính (3/12 cột - Thiết kế chuẩn Flatsome Mega Sidebar) -->
                <div class="hidden lg:flex lg:col-span-3 bg-white rounded-md border border-slate-200 shadow-sm flex-col justify-between overflow-hidden">
                    <div class="divide-y divide-slate-100 text-[13px]">
                        <button onclick="filterCategory('vong-bi-igbt')" class="w-full px-3.5 py-2.5 text-left hover:bg-blue-50 hover:text-flatsome-primary flex items-center justify-between group transition">
                            <span class="flex items-center gap-2.5 font-medium truncate">
                                <i class="fa-solid fa-gear text-flatsome-primary w-4 text-center"></i>
                                Vòng Bi SKF, Nachi, Koyo, NSK
                            </span>
                            <i class="fa-solid fa-angle-right text-xs text-slate-400 group-hover:text-flatsome-primary"></i>
                        </button>
                        <button onclick="filterCategory('vong-bi-igbt')" class="w-full px-3.5 py-2.5 text-left hover:bg-blue-50 hover:text-flatsome-primary flex items-center justify-between group transition">
                            <span class="flex items-center gap-2.5 font-medium truncate">
                                <i class="fa-solid fa-microchip text-flatsome-primary w-4 text-center"></i>
                                Mô-đun IGBT & Điện Công Nghiệp
                            </span>
                            <i class="fa-solid fa-angle-right text-xs text-slate-400 group-hover:text-flatsome-primary"></i>
                        </button>
                        <button onclick="filterCategory('coppha-tyren')" class="w-full px-3.5 py-2.5 text-left hover:bg-blue-50 hover:text-flatsome-primary flex items-center justify-between group transition">
                            <span class="flex items-center gap-2.5 font-medium truncate">
                                <i class="fa-solid fa-screwdriver-wrench text-flatsome-primary w-4 text-center"></i>
                                Ty Ren, Bulong, Đai Treo, Lưới XD
                            </span>
                            <i class="fa-solid fa-angle-right text-xs text-slate-400 group-hover:text-flatsome-primary"></i>
                        </button>
                        <button onclick="filterCategory('dung-cu-do-nghe')" class="w-full px-3.5 py-2.5 text-left hover:bg-blue-50 hover:text-flatsome-primary flex items-center justify-between group transition">
                            <span class="flex items-center gap-2.5 font-medium truncate">
                                <i class="fa-solid fa-toolbox text-flatsome-primary w-4 text-center"></i>
                                Dụng Cụ Đồ Nghề (Asaki, Harkcaput)
                            </span>
                            <i class="fa-solid fa-angle-right text-xs text-slate-400 group-hover:text-flatsome-primary"></i>
                        </button>
                        <button onclick="filterCategory('dung-cu-cam-tay')" class="w-full px-3.5 py-2.5 text-left hover:bg-blue-50 hover:text-flatsome-primary flex items-center justify-between group transition">
                            <span class="flex items-center gap-2.5 font-medium truncate">
                                <i class="fa-solid fa-hammer text-flatsome-primary w-4 text-center"></i>
                                Dụng Cụ Cầm Tay (Bosch, Makita, Ken)
                            </span>
                            <i class="fa-solid fa-angle-right text-xs text-slate-400 group-hover:text-flatsome-primary"></i>
                        </button>
                        <button onclick="filterCategory('may-han-cat')" class="w-full px-3.5 py-2.5 text-left hover:bg-blue-50 hover:text-flatsome-primary flex items-center justify-between group transition">
                            <span class="flex items-center gap-2.5 font-medium truncate">
                                <i class="fa-solid fa-fire-flame-curved text-flatsome-primary w-4 text-center"></i>
                                Máy Hàn, Rùa Cắt, Máy Cắt Plasma
                            </span>
                            <i class="fa-solid fa-angle-right text-xs text-slate-400 group-hover:text-flatsome-primary"></i>
                        </button>
                        <button onclick="filterCategory('coppha-tyren')" class="w-full px-3.5 py-2.5 text-left hover:bg-blue-50 hover:text-flatsome-primary flex items-center justify-between group transition">
                            <span class="flex items-center gap-2.5 font-medium truncate">
                                <i class="fa-solid fa-layer-group text-flatsome-primary w-4 text-center"></i>
                                Coppha Dàn Giáo, Phụ Kiện Coppha
                            </span>
                            <i class="fa-solid fa-angle-right text-xs text-slate-400 group-hover:text-flatsome-primary"></i>
                        </button>
                        <button onclick="filterCategory('banh-xe-ke-thang')" class="w-full px-3.5 py-2.5 text-left hover:bg-blue-50 hover:text-flatsome-primary flex items-center justify-between group transition">
                            <span class="flex items-center gap-2.5 font-medium truncate">
                                <i class="fa-solid fa-dolly text-flatsome-primary w-4 text-center"></i>
                                Bánh Xe, Xe Đẩy, Kệ & Thang Nhôm
                            </span>
                            <i class="fa-solid fa-angle-right text-xs text-slate-400 group-hover:text-flatsome-primary"></i>
                        </button>
                        <button onclick="filterCategory('da-cat-mui-khoan')" class="w-full px-3.5 py-2.5 text-left hover:bg-blue-50 hover:text-flatsome-primary flex items-center justify-between group transition">
                            <span class="flex items-center gap-2.5 font-medium truncate">
                                <i class="fa-solid fa-compact-disc text-flatsome-primary w-4 text-center"></i>
                                Đá Cắt, Đá Mài, Que Hàn, Lưỡi Cắt
                            </span>
                            <i class="fa-solid fa-angle-right text-xs text-slate-400 group-hover:text-flatsome-primary"></i>
                        </button>
                        <button onclick="filterCategory('da-cat-mui-khoan')" class="w-full px-3.5 py-2.5 text-left hover:bg-blue-50 hover:text-flatsome-primary flex items-center justify-between group transition">
                            <span class="flex items-center gap-2.5 font-medium truncate">
                                <i class="fa-solid fa-screwdriver text-flatsome-primary w-4 text-center"></i>
                                Mũi Khoan, Mũi Đục, Nhám Xếp
                            </span>
                            <i class="fa-solid fa-angle-right text-xs text-slate-400 group-hover:text-flatsome-primary"></i>
                        </button>
                        <button onclick="filterCategory('coppha-tyren')" class="w-full px-3.5 py-2.5 text-left hover:bg-blue-50 hover:text-flatsome-primary flex items-center justify-between group transition">
                            <span class="flex items-center gap-2.5 font-medium truncate">
                                <i class="fa-solid fa-anchor text-flatsome-primary w-4 text-center"></i>
                                Dây Cáp, Xích, Dụng Cụ Nâng Hạ
                            </span>
                            <i class="fa-solid fa-angle-right text-xs text-slate-400 group-hover:text-flatsome-primary"></i>
                        </button>
                    </div>
                </div>

                <!-- Cột Slider 2 Ảnh Banner Tự Trượt (9/12 cột - Chỉ dùng ảnh thực tế từ Google Drive) -->
                <div class="lg:col-span-9">
                    <div class="relative w-full h-[230px] sm:h-[320px] md:h-[390px] lg:h-full min-h-[230px] rounded-md overflow-hidden bg-slate-900 shadow-sm border border-slate-200">
                        
                        <!-- Slide 1 -->
                        <div id="banner-slide-0" class="banner-slide absolute inset-0 transition-opacity duration-700 opacity-100 z-10">
                            <div class="grid grid-cols-12 h-full">
                                <div class="col-span-7 sm:col-span-6 p-4 sm:p-8 md:p-10 flex flex-col justify-center bg-gradient-to-r from-slate-900 via-slate-900/95 to-slate-900/40 z-10">
                                    <p class="text-amber-400 text-xs sm:text-sm font-bold uppercase tracking-wider mb-1">thienquy.net</p>
                                    <h2 class="text-white text-base sm:text-2xl md:text-3xl font-extrabold leading-tight mb-2 sm:mb-3">
                                        CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ
                                    </h2>
                                    <p class="text-slate-200 text-xs sm:text-sm mb-3 sm:mb-5 line-clamp-3">
                                        Chuyên cung cấp Vòng bi công nghiệp SKF, Nachi, Koyo, NSK, Mô-đun công suất IGBT, Máy móc cơ khí & Dụng cụ công nghiệp tại Tam Kỳ - Đà Nẵng.
                                    </p>
                                    <div class="flex flex-wrap gap-2">
                                        <a href="#products-section" class="bg-flatsome-secondary hover:bg-red-700 text-white text-xs sm:text-sm font-bold px-3.5 py-2 rounded transition">
                                            Xem sản phẩm
                                        </a>
                                        <a href="#quote-form-section" class="bg-white/15 hover:bg-white/25 text-white text-xs sm:text-sm font-semibold px-3.5 py-2 rounded border border-white/30 transition">
                                            Nhận báo giá
                                        </a>
                                    </div>
                                </div>
                                <div class="col-span-5 sm:col-span-6 relative h-full">
                                    <!-- Ghép ảnh thực tế từ Google Drive trên Banner 1 -->
                                    <div class="grid grid-cols-1 sm:grid-cols-2 h-full gap-1 p-1 sm:p-2 bg-slate-800">
                                        <img src="https://drive.google.com/thumbnail?id=1yg6XvqnwKtMjBC2ZxtTEZo0xD1a-Eo0m&sz=w1000"
                                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1yg6XvqnwKtMjBC2ZxtTEZo0xD1a-Eo0m';"
                                             alt="Thiết bị Kỹ Thuật Thiên Quý 1"
                                             class="w-full h-full object-cover rounded">
                                        <img src="https://drive.google.com/thumbnail?id=1eVutGgveAAS1eJARWXUfmd7rwvfp_j5N&sz=w1000"
                                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1eVutGgveAAS1eJARWXUfmd7rwvfp_j5N';"
                                             alt="Thiết bị Kỹ Thuật Thiên Quý 2"
                                             class="hidden sm:block w-full h-full object-cover rounded">
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- Slide 2 -->
                        <div id="banner-slide-1" class="banner-slide absolute inset-0 transition-opacity duration-700 opacity-0 z-0 pointer-events-none">
                            <div class="grid grid-cols-12 h-full">
                                <div class="col-span-7 sm:col-span-6 p-4 sm:p-8 md:p-10 flex flex-col justify-center bg-gradient-to-r from-flatsome-primary via-flatsome-primary/95 to-slate-900/50 z-10">
                                    <p class="text-amber-300 text-xs sm:text-sm font-bold uppercase tracking-wider mb-1">Vật Tư Cơ Khí & Xây Dựng</p>
                                    <h2 class="text-white text-base sm:text-2xl md:text-3xl font-extrabold leading-tight mb-2 sm:mb-3">
                                        DỤNG CỤ ĐỒ NGHỀ - MÁY HÀN - VẬT TƯ KIM KHÍ
                                    </h2>
                                    <p class="text-blue-100 text-xs sm:text-sm mb-3 sm:mb-5 line-clamp-3">
                                        Đầy đủ dụng cụ cầm tay, đá cắt, đá mài, mũi khoan, phụ kiện coppha dàn giáo. Giao hàng nhanh chóng - Tư vấn kỹ thuật tận tâm: 0978.102.434
                                    </p>
                                    <div class="flex flex-wrap gap-2">
                                        <a href="#quote-form-section" class="bg-amber-400 hover:bg-amber-500 text-slate-900 text-xs sm:text-sm font-bold px-3.5 py-2 rounded transition">
                                            Gửi yêu cầu báo giá
                                        </a>
                                        <a href="#map-fanpage-section" class="bg-white/15 hover:bg-white/25 text-white text-xs sm:text-sm font-semibold px-3.5 py-2 rounded border border-white/30 transition">
                                            258 Trần Cao Vân
                                        </a>
                                    </div>
                                </div>
                                <div class="col-span-5 sm:col-span-6 relative h-full">
                                    <!-- Ghép ảnh thực tế từ Google Drive trên Banner 2 -->
                                    <div class="grid grid-cols-1 sm:grid-cols-2 h-full gap-1 p-1 sm:p-2 bg-slate-800">
                                        <img src="https://drive.google.com/thumbnail?id=17Og6NDOXnrYWgR68UU0NOY-q6JpbdtgD&sz=w1000"
                                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/17Og6NDOXnrYWgR68UU0NOY-q6JpbdtgD';"
                                             alt="Vật tư công nghiệp Thiên Quý 3"
                                             class="w-full h-full object-cover rounded">
                                        <img src="https://drive.google.com/thumbnail?id=1uj0yENXnY0WE8aWyT-Wx9LZFddvmCGQx&sz=w1000"
                                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1uj0yENXnY0WE8aWyT-Wx9LZFddvmCGQx';"
                                             alt="Vật tư công nghiệp Thiên Quý 4"
                                             class="hidden sm:block w-full h-full object-cover rounded">
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- Nút điều hướng 2 Banner tự trượt -->
                        <button onclick="prevBannerSlide()" aria-label="Slide trước" class="absolute left-2 top-1/2 -translate-y-1/2 z-20 w-8 h-8 rounded-full bg-black/40 hover:bg-black/70 text-white flex items-center justify-center transition">
                            <i class="fa-solid fa-chevron-left text-xs"></i>
                        </button>
                        <button onclick="nextBannerSlide()" aria-label="Slide tiếp" class="absolute right-2 top-1/2 -translate-y-1/2 z-20 w-8 h-8 rounded-full bg-black/40 hover:bg-black/70 text-white flex items-center justify-center transition">
                            <i class="fa-solid fa-chevron-right text-xs"></i>
                        </button>

                        <!-- Dấu chấm chỉ báo Banner -->
                        <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                            <button onclick="goToBannerSlide(0)" id="banner-dot-0" class="w-6 h-2 rounded-full bg-amber-400 transition-all"></button>
                            <button onclick="goToBannerSlide(1)" id="banner-dot-1" class="w-2.5 h-2 rounded-full bg-white/60 transition-all"></button>
                        </div>

                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC SẢN PHẨM TRỰC QUAN (Đẹp, rõ ràng trên cả Máy Tính & Điện Thoại)
         ========================================== -->
    <section id="categories-section" class="py-4 md:py-6">
        <div class="ux-container">
            <div class="bg-white rounded-md border border-slate-200 p-3.5 sm:p-5 shadow-sm">
                <div class="section-title-container">
                    <div class="section-title-main">
                        <h2 class="text-base sm:text-lg font-extrabold text-flatsome-primary uppercase tracking-wide">
                            Danh Mục Sản Phẩm
                        </h2>
                        <button onclick="filterCategory('all')" class="text-xs sm:text-sm font-semibold text-flatsome-primary hover:underline">
                            Xem tất cả <i class="fa-solid fa-caret-right ml-0.5"></i>
                        </button>
                    </div>
                </div>

                <!-- Lưới danh mục tối ưu: 2 cột trên điện thoại, 4 cột trên tablet, 6 cột trên máy tính -->
                <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-2.5 sm:gap-3">
                    
                    <button onclick="filterCategory('vong-bi-igbt')" class="group p-2.5 rounded-md border border-slate-200 hover:border-flatsome-primary hover:bg-blue-50/40 transition flex flex-col items-center text-center">
                        <div class="w-14 h-14 sm:w-16 sm:h-16 rounded-md overflow-hidden mb-2 border border-slate-100 bg-slate-50">
                            <img src="https://drive.google.com/thumbnail?id=1yg6XvqnwKtMjBC2ZxtTEZo0xD1a-Eo0m&sz=w400"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1yg6XvqnwKtMjBC2ZxtTEZo0xD1a-Eo0m';"
                                 alt="Vòng bi & Linh kiện IGBT" class="w-full h-full object-cover group-hover:scale-105 transition">
                        </div>
                        <span class="text-xs sm:text-[13px] font-bold text-slate-800 group-hover:text-flatsome-primary line-clamp-2">Vòng Bi SKF, Nachi & IGBT</span>
                        <span class="text-[11px] text-slate-500 mt-0.5">Bạc đạn & Bán dẫn</span>
                    </button>

                    <button onclick="filterCategory('dung-cu-do-nghe')" class="group p-2.5 rounded-md border border-slate-200 hover:border-flatsome-primary hover:bg-blue-50/40 transition flex flex-col items-center text-center">
                        <div class="w-14 h-14 sm:w-16 sm:h-16 rounded-md overflow-hidden mb-2 border border-slate-100 bg-slate-50">
                            <img src="https://drive.google.com/thumbnail?id=1DjIRF9GbXvPzqhLASIkc65g_25l1Yh7Q&sz=w400"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1DjIRF9GbXvPzqhLASIkc65g_25l1Yh7Q';"
                                 alt="Dụng cụ đồ nghề" class="w-full h-full object-cover group-hover:scale-105 transition">
                        </div>
                        <span class="text-xs sm:text-[13px] font-bold text-slate-800 group-hover:text-flatsome-primary line-clamp-2">Dụng Cụ Đồ Nghề</span>
                        <span class="text-[11px] text-slate-500 mt-0.5">Asaki, Halboshi, Harkcaput</span>
                    </button>

                    <button onclick="filterCategory('dung-cu-cam-tay')" class="group p-2.5 rounded-md border border-slate-200 hover:border-flatsome-primary hover:bg-blue-50/40 transition flex flex-col items-center text-center">
                        <div class="w-14 h-14 sm:w-16 sm:h-16 rounded-md overflow-hidden mb-2 border border-slate-100 bg-slate-50">
                            <img src="https://drive.google.com/thumbnail?id=1VSKFmUEiiYZYaqixWRtRQJJndSgmZ2VZ&sz=w400"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1VSKFmUEiiYZYaqixWRtRQJJndSgmZ2VZ';"
                                 alt="Dụng cụ cầm tay" class="w-full h-full object-cover group-hover:scale-105 transition">
                        </div>
                        <span class="text-xs sm:text-[13px] font-bold text-slate-800 group-hover:text-flatsome-primary line-clamp-2">Dụng Cụ Cầm Tay</span>
                        <span class="text-[11px] text-slate-500 mt-0.5">Bosch, Makita, Hitachi, Ken</span>
                    </button>

                    <button onclick="filterCategory('may-han-cat')" class="group p-2.5 rounded-md border border-slate-200 hover:border-flatsome-primary hover:bg-blue-50/40 transition flex flex-col items-center text-center">
                        <div class="w-14 h-14 sm:w-16 sm:h-16 rounded-md overflow-hidden mb-2 border border-slate-100 bg-slate-50">
                            <img src="https://drive.google.com/thumbnail?id=1HwjU6a4rEHSnW_i5KgAf8rEd_bzHgEpL&sz=w400"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1HwjU6a4rEHSnW_i5KgAf8rEd_bzHgEpL';"
                                 alt="Máy hàn cắt Plasma" class="w-full h-full object-cover group-hover:scale-105 transition">
                        </div>
                        <span class="text-xs sm:text-[13px] font-bold text-slate-800 group-hover:text-flatsome-primary line-clamp-2">Máy Hàn, Rùa Cắt, Plasma</span>
                        <span class="text-[11px] text-slate-500 mt-0.5">Jasic, Weldcom, Huawei</span>
                    </button>

                    <button onclick="filterCategory('da-cat-mui-khoan')" class="group p-2.5 rounded-md border border-slate-200 hover:border-flatsome-primary hover:bg-blue-50/40 transition flex flex-col items-center text-center">
                        <div class="w-14 h-14 sm:w-16 sm:h-16 rounded-md overflow-hidden mb-2 border border-slate-100 bg-slate-50">
                            <img src="https://drive.google.com/thumbnail?id=1bfBtK7uR9Mt9sJoJCHVkrPSebdF-sNUL&sz=w400"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1bfBtK7uR9Mt9sJoJCHVkrPSebdF-sNUL';"
                                 alt="Đá cắt đá mài mũi khoan" class="w-full h-full object-cover group-hover:scale-105 transition">
                        </div>
                        <span class="text-xs sm:text-[13px] font-bold text-slate-800 group-hover:text-flatsome-primary line-clamp-2">Đá Cắt, Mũi Khoan, Nhám</span>
                        <span class="text-[11px] text-slate-500 mt-0.5">Que hàn, Lưỡi cắt bê tông</span>
                    </button>

                    <button onclick="filterCategory('coppha-tyren')" class="group p-2.5 rounded-md border border-slate-200 hover:border-flatsome-primary hover:bg-blue-50/40 transition flex flex-col items-center text-center">
                        <div class="w-14 h-14 sm:w-16 sm:h-16 rounded-md overflow-hidden mb-2 border border-slate-100 bg-slate-50">
                            <img src="https://drive.google.com/thumbnail?id=1OuSlLHE7UF2lr-y-JIxyJ53PbGtu-yHn&sz=w400"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1OuSlLHE7UF2lr-y-JIxyJ53PbGtu-yHn';"
                                 alt="Coppha Ty ren Nâng hạ" class="w-full h-full object-cover group-hover:scale-105 transition">
                        </div>
                        <span class="text-xs sm:text-[13px] font-bold text-slate-800 group-hover:text-flatsome-primary line-clamp-2">Ty Ren, Coppha & Nâng Hạ</span>
                        <span class="text-[11px] text-slate-500 mt-0.5">Bánh xe, Xe đẩy, Cáp xích</span>
                    </button>

                </div>

                <!-- Dải danh mục phụ đầy đủ từ web mẫu để dễ chuyển sang UX Builder -->
                <div class="mt-3 pt-3 border-t border-slate-100 flex flex-wrap items-center gap-1.5 sm:gap-2">
                    <span class="text-xs font-bold text-slate-500 mr-1">Chuyên mục chi tiết:</span>
                    <button onclick="filterCategory('all')" class="cat-pill active-pill text-xs px-2.5 py-1 rounded bg-flatsome-primary text-white font-medium transition">Tất cả (16)</button>
                    <button onclick="filterCategory('vong-bi-igbt')" class="cat-pill text-xs px-2.5 py-1 rounded bg-slate-100 hover:bg-slate-200 text-slate-700 font-medium transition">Vòng Bi & IGBT</button>
                    <button onclick="filterCategory('dung-cu-do-nghe')" class="cat-pill text-xs px-2.5 py-1 rounded bg-slate-100 hover:bg-slate-200 text-slate-700 font-medium transition">Dụng Cụ Đồ Nghề</button>
                    <button onclick="filterCategory('dung-cu-cam-tay')" class="cat-pill text-xs px-2.5 py-1 rounded bg-slate-100 hover:bg-slate-200 text-slate-700 font-medium transition">Dụng Cụ Cầm Tay</button>
                    <button onclick="filterCategory('may-han-cat')" class="cat-pill text-xs px-2.5 py-1 rounded bg-slate-100 hover:bg-slate-200 text-slate-700 font-medium transition">Máy Hàn & Cắt Plasma</button>
                    <button onclick="filterCategory('da-cat-mui-khoan')" class="cat-pill text-xs px-2.5 py-1 rounded bg-slate-100 hover:bg-slate-200 text-slate-700 font-medium transition">Đá Cắt, Đá Mài, Mũi Khoan, Nhám</button>
                    <button onclick="filterCategory('coppha-tyren')" class="cat-pill text-xs px-2.5 py-1 rounded bg-slate-100 hover:bg-slate-200 text-slate-700 font-medium transition">Ty Ren, Coppha, Cáp Xích</button>
                    <button onclick="filterCategory('banh-xe-ke-thang')" class="cat-pill text-xs px-2.5 py-1 rounded bg-slate-100 hover:bg-slate-200 text-slate-700 font-medium transition">Bánh Xe, Xe Đẩy, Thang Nhôm</button>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH SÁCH SẢN PHẨM FLATSOME
         - Sử dụng toàn bộ 16 ảnh thực tế từ Google Drive
         - Chia đúng 2 cột trên giao diện điện thoại (grid-cols-2) và 4 cột trên máy tính (lg:grid-cols-4)
         - Có % giảm giá, giá gốc gạch ngang, giá giảm và nút XEM NHANH chuẩn Flatsome
         ========================================== -->
    <section id="products-section" class="py-3 md:py-5">
        <div class="ux-container">
            <div class="bg-white rounded-md border border-slate-200 p-3.5 sm:p-5 shadow-sm">
                
                <div class="section-title-container">
                    <div class="section-title-main flex-wrap gap-2">
                        <h2 id="currentCategoryTitle" class="text-base sm:text-lg font-extrabold text-flatsome-primary uppercase tracking-wide">
                            Sản Phẩm Thực Tế Tại Kỹ Thuật Thiên Quý
                        </h2>
                        <span id="productCountLabel" class="text-xs text-slate-500 font-medium">Hiển thị 16 sản phẩm</span>
                    </div>
                </div>

                <!-- LƯỚI SẢN PHẨM: 2 cột trên Điện Thoại (grid-cols-2), 3 cột trên Tablet, 4 cột trên Máy Tính -->
                <div id="productsGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">
                    <!-- Sản phẩm được render tự động từ mảng 16 ảnh thực tế Google Drive bên dưới -->
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ
         (Thiết kế chuẩn cột UX Builder đơn giản, dễ chỉnh sửa)
         ========================================== -->
    <section id="quote-form-section" class="py-4 md:py-6">
        <div class="ux-container">
            <div class="bg-white rounded-md border border-slate-200 p-4 sm:p-6 shadow-sm">
                <div class="section-title-container">
                    <div class="section-title-main">
                        <h2 class="text-base sm:text-lg font-extrabold text-flatsome-primary uppercase tracking-wide">
                            Form Yêu Cầu Tư Vấn & Báo Giá Nhanh
                        </h2>
                        <span class="text-xs font-semibold text-flatsome-secondary">Phản hồi nhanh qua SĐT / Zalo: 0978.102.434</span>
                    </div>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-start">
                    
                    <!-- Thông tin liên hệ trực tiếp (5 cột) -->
                    <div class="lg:col-span-5 bg-slate-50 rounded-md p-4 sm:p-5 border border-slate-200">
                        <h3 class="text-sm sm:text-base font-extrabold text-flatsome-primary mb-2">
                            CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ
                        </h3>
                        <p class="text-xs sm:text-sm text-slate-600 mb-4 leading-relaxed">
                            Quý khách hàng, nhà thầu, xưởng cơ khí cần báo giá sỉ & lẻ Vòng bi công nghiệp, Linh kiện IGBT, Máy hàn cắt, Dụng cụ đồ nghề hoặc Vật tư phụ kiện xây dựng vui lòng điền thông tin bên cạnh.
                        </p>
                        <ul class="space-y-2.5 text-xs sm:text-sm text-slate-700">
                            <li class="flex items-start gap-2.5">
                                <i class="fa-solid fa-location-dot text-flatsome-secondary mt-1 w-4 text-center"></i>
                                <span><strong>Địa chỉ:</strong> 258 Trần Cao Vân, Phường Tam Kỳ, TP Đà Nẵng</span>
                            </li>
                            <li class="flex items-center gap-2.5">
                                <i class="fa-solid fa-phone-volume text-flatsome-secondary w-4 text-center"></i>
                                <span><strong>Hotline / Zalo:</strong> <a href="tel:0978102434" class="text-flatsome-primary font-bold hover:underline">0978.102.434</a></span>
                            </li>
                            <li class="flex items-center gap-2.5">
                                <i class="fa-solid fa-envelope text-flatsome-secondary w-4 text-center"></i>
                                <span><strong>Email:</strong> thienquytm@gmail.com</span>
                            </li>
                            <li class="flex items-center gap-2.5">
                                <i class="fa-solid fa-globe text-flatsome-secondary w-4 text-center"></i>
                                <span><strong>Website:</strong> thienquy.net</span>
                            </li>
                        </ul>

                        <!-- Ảnh thực tế kho hàng / sản phẩm đính kèm -->
                        <div class="grid grid-cols-3 gap-2 mt-4 pt-4 border-t border-slate-200">
                            <img src="https://drive.google.com/thumbnail?id=18iRse5KupLoIllKmpLt0ON3QlUSLAxuc&sz=w400"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/18iRse5KupLoIllKmpLt0ON3QlUSLAxuc';"
                                 alt="Thực tế Thiên Quý" class="w-full h-16 object-cover rounded border border-slate-200">
                            <img src="https://drive.google.com/thumbnail?id=1q5QWr9EaK6tLB8CX7UthGZSguBpdCdrz&sz=w400"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1q5QWr9EaK6tLB8CX7UthGZSguBpdCdrz';"
                                 alt="Thực tế Thiên Quý" class="w-full h-16 object-cover rounded border border-slate-200">
                            <img src="https://drive.google.com/thumbnail?id=1N7ZouNs_zi40NPsfoZ2A2juIy3zgAYAp&sz=w400"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1N7ZouNs_zi40NPsfoZ2A2juIy3zgAYAp';"
                                 alt="Thực tế Thiên Quý" class="w-full h-16 object-cover rounded border border-slate-200">
                        </div>
                    </div>

                    <!-- Form nhập yêu cầu & báo giá (7 cột) -->
                    <div class="lg:col-span-7">
                        <form id="homepageQuoteForm" onsubmit="submitQuoteForm(event)" class="space-y-3.5">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 uppercase mb-1">Họ và tên / Tên đơn vị *</label>
                                    <input id="quoteName" type="text" required placeholder="Nhập họ tên hoặc tên công ty..."
                                           class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded focus:outline-none focus:border-flatsome-primary">
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 uppercase mb-1">Số điện thoại / Zalo *</label>
                                    <input id="quotePhone" type="tel" required placeholder="Ví dụ: 0978102434"
                                           class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded focus:outline-none focus:border-flatsome-primary">
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 uppercase mb-1">Danh mục cần báo giá</label>
                                    <select id="quoteCategory" class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded bg-white focus:outline-none focus:border-flatsome-primary">
                                        <option value="Vòng bi công nghiệp (SKF, Nachi, Koyo, NSK)">Vòng bi công nghiệp (SKF, Nachi, Koyo, NSK)</option>
                                        <option value="Linh kiện bán dẫn / Mô-đun IGBT công suất">Linh kiện bán dẫn / Mô-đun IGBT công suất</option>
                                        <option value="Dụng cụ đồ nghề & Dụng cụ cầm tay">Dụng cụ đồ nghề & Dụng cụ cầm tay</option>
                                        <option value="Máy hàn, Rùa cắt, Máy cắt Plasma">Máy hàn, Rùa cắt, Máy cắt Plasma</option>
                                        <option value="Ty ren, Bulong, Phụ kiện Coppha Dàn giáo">Ty ren, Bulong, Phụ kiện Coppha Dàn giáo</option>
                                        <option value="Đá cắt, Đá mài, Mũi khoan, Nhám xếp">Đá cắt, Đá mài, Mũi khoan, Nhám xếp</option>
                                        <option value="Bánh xe, Xe đẩy, Thang nhôm, Dụng cụ nâng hạ">Bánh xe, Xe đẩy, Thang nhôm, Dụng cụ nâng hạ</option>
                                    </select>
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 uppercase mb-1">Địa chỉ nhận hàng (Tùy chọn)</label>
                                    <input id="quoteAddress" type="text" placeholder="Tam Kỳ, Đà Nẵng hoặc tỉnh thành khác..."
                                           class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded focus:outline-none focus:border-flatsome-primary">
                                </div>
                            </div>

                            <div>
                                <label class="block text-xs font-bold text-slate-700 uppercase mb-1">Nội dung chi tiết mã hàng & số lượng cần báo giá *</label>
                                <textarea id="quoteMessage" rows="3" required placeholder="Nhập tên sản phẩm, mã vòng bi, thông số kỹ thuật hoặc số lượng cần báo giá..."
                                          class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded focus:outline-none focus:border-flatsome-primary"></textarea>
                            </div>

                            <div class="flex flex-wrap items-center justify-between gap-3 pt-1">
                                <button type="submit" class="bg-flatsome-primary hover:bg-blue-900 text-white font-bold text-sm px-6 py-2.5 rounded shadow-sm transition flex items-center gap-2">
                                    <i class="fa-solid fa-paper-plane"></i> GỬI YÊU CẦU BÁO GIÁ
                                </button>
                                <a href="https://zalo.me/0978102434" target="_blank" rel="noopener" class="text-xs sm:text-sm font-semibold text-flatsome-primary hover:underline flex items-center gap-1.5">
                                    <i class="fa-solid fa-comment-dots text-blue-600"></i> Gửi danh sách vật tư qua Zalo 0978.102.434
                                </a>
                            </div>

                            <!-- Thông báo gửi thành công -->
                            <div id="quoteSuccessAlert" class="hidden p-3.5 rounded bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs sm:text-sm">
                                <div class="font-bold mb-1"><i class="fa-solid fa-circle-check mr-1"></i> Đã ghi nhận yêu cầu báo giá thành công!</div>
                                <p id="quoteSuccessDetail"></p>
                            </div>
                        </form>
                    </div>

                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & KỸ THUẬT)
         - Sử dụng ảnh thực tế từ Google Drive
         ========================================== -->
    <section id="blog-section" class="py-4 md:py-6">
        <div class="ux-container">
            <div class="bg-white rounded-md border border-slate-200 p-3.5 sm:p-5 shadow-sm">
                
                <div class="section-title-container">
                    <div class="section-title-main flex-wrap gap-2">
                        <h2 class="text-base sm:text-lg font-extrabold text-flatsome-primary uppercase tracking-wide">
                            Danh Mục Bài Viết & Tư Vấn Kỹ Thuật
                        </h2>
                        <!-- Các nút lọc danh mục bài viết trang chủ -->
                        <div class="flex items-center gap-1.5 overflow-x-auto no-scrollbar py-0.5">
                            <button onclick="filterBlog('all')" class="blog-tab-btn bg-flatsome-primary text-white text-xs font-semibold px-2.5 py-1 rounded transition">Tất cả bài viết</button>
                            <button onclick="filterBlog('vong-bi')" class="blog-tab-btn bg-slate-100 hover:bg-slate-200 text-slate-700 text-xs font-semibold px-2.5 py-1 rounded transition">Kỹ thuật Vòng Bi</button>
                            <button onclick="filterBlog('dien-igbt')" class="blog-tab-btn bg-slate-100 hover:bg-slate-200 text-slate-700 text-xs font-semibold px-2.5 py-1 rounded transition">Linh kiện IGBT</button>
                            <button onclick="filterBlog('dung-cu-may')" class="blog-tab-btn bg-slate-100 hover:bg-slate-200 text-slate-700 text-xs font-semibold px-2.5 py-1 rounded transition">Kinh nghiệm Dụng cụ & Máy</button>
                        </div>
                    </div>
                </div>

                <!-- Lưới 4 bài viết chuẩn Flatsome Blog Posts Element -->
                <div id="blogPostsGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
                    <!-- Render từ dữ liệu bài viết sử dụng ảnh Google Drive -->
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         ĐƯA FANPAGE FACEBOOK & ẢNH BẢN ĐỒ GOOGLE MAP RA NGOÀI TRANG CHỦ
         - Địa chỉ: 258 Trần Cao Vân, Phường Tam Kỳ, TP Đà Nẵng
         - Map link: https://maps.app.goo.gl/MntnW3VdYEXvnTsd8
         - Fanpage: https://www.facebook.com/ctthienquy
         ========================================== -->
    <section id="map-fanpage-section" class="py-4 md:py-6">
        <div class="ux-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-4">
                
                <!-- CỘT 1: BẢN ĐỒ GOOGLE MAP TRÊN TRANG CHỦ (7/12 cột) -->
                <div class="lg:col-span-7 bg-white rounded-md border border-slate-200 p-3.5 sm:p-5 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="section-title-container">
                            <div class="section-title-main">
                                <h2 class="text-base sm:text-lg font-extrabold text-flatsome-primary uppercase tracking-wide">
                                    Bản Đồ Đường Đi - Kỹ Thuật Thiên Quý
                                </h2>
                                <a href="https://maps.app.goo.gl/MntnW3VdYEXvnTsd8" target="_blank" rel="noopener"
                                   class="text-xs font-bold text-flatsome-secondary hover:underline flex items-center gap-1">
                                    <i class="fa-solid fa-diamond-turn-right"></i> Mở Google Maps
                                </a>
                            </div>
                        </div>

                        <div class="mb-3 flex flex-wrap items-center justify-between gap-2 bg-slate-50 p-3 rounded border border-slate-200 text-xs sm:text-sm">
                            <div>
                                <div class="font-bold text-slate-800">
                                    <i class="fa-solid fa-location-dot text-flatsome-secondary mr-1"></i>
                                    258 Trần Cao Vân, Phường Tam Kỳ, TP Đà Nẵng
                                </div>
                                <div class="text-slate-500 text-xs mt-0.5">Điện thoại chỉ đường: <strong class="text-flatsome-primary">0978.102.434</strong></div>
                            </div>
                            <a href="https://maps.app.goo.gl/MntnW3VdYEXvnTsd8" target="_blank" rel="noopener"
                               class="bg-flatsome-primary hover:bg-blue-900 text-white text-xs font-bold px-3 py-2 rounded transition inline-flex items-center gap-1.5">
                                <i class="fa-solid fa-map-location-dot"></i> Xem vị trí trên Google Map
                            </a>
                        </div>
                    </div>

                    <!-- Khung Bản Đồ Google Map trực tiếp ngoài trang chủ -->
                    <div class="relative w-full h-[270px] sm:h-[320px] rounded overflow-hidden border border-slate-300 bg-slate-100">
                        <iframe
                            title="Bản đồ Công Ty TNHH Kỹ Thuật Thiên Quý - 258 Trần Cao Vân, Phường Tam Kỳ, TP Đà Nẵng"
                            src="https://maps.google.com/maps?q=258%20Tr%E1%BA%A7n%20Cao%20V%C3%A2n,%20Tam%20K%E1%BB%B3&t=&z=16&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full border-0"
                            allowfullscreen=""
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>
                </div>

                <!-- CỘT 2: FANPAGE FACEBOOK TRÊN TRANG CHỦ (5/12 cột) -->
                <div class="lg:col-span-5 bg-white rounded-md border border-slate-200 p-3.5 sm:p-5 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="section-title-container">
                            <div class="section-title-main">
                                <h2 class="text-base sm:text-lg font-extrabold text-flatsome-primary uppercase tracking-wide">
                                    Fanpage Facebook Chính Thức
                                </h2>
                                <a href="https://www.facebook.com/ctthienquy" target="_blank" rel="noopener"
                                   class="text-xs font-bold text-blue-600 hover:underline">
                                    fb.com/ctthienquy
                                </a>
                            </div>
                        </div>

                        <!-- Khung hiển thị Fanpage Công Ty TNHH Kỹ Thuật Thiên Quý ngoài trang chủ -->
                        <div class="border border-slate-200 rounded-md overflow-hidden bg-slate-50">
                            <!-- Ảnh bìa thực tế & Avatar Logo đã tinh chỉnh -->
                            <div class="relative h-32 bg-slate-800 overflow-hidden">
                                <img src="https://drive.google.com/thumbnail?id=1GXepKE86d13FhQ6qgBE7zBw214hidDYG&sz=w800"
                                     onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1GXepKE86d13FhQ6qgBE7zBw214hidDYG';"
                                     alt="Fanpage Kỹ Thuật Thiên Quý" class="w-full h-full object-cover opacity-80">
                                <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
                                <div class="absolute bottom-2.5 left-3 right-3 flex items-center gap-3">
                                    <div class="logo-refined-box w-12 h-12 rounded-md p-1 bg-white flex-shrink-0">
                                        <img src="https://drive.google.com/thumbnail?id=1U-0CiTUSxu2_0XMzT-P7DiJMBhQphugl&sz=w300"
                                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1U-0CiTUSxu2_0XMzT-P7DiJMBhQphugl';"
                                             alt="Logo Thiên Quý" class="logo-refined-img w-full h-full">
                                    </div>
                                    <div class="text-white min-w-0">
                                        <a href="https://www.facebook.com/ctthienquy" target="_blank" rel="noopener" class="font-bold text-sm sm:text-base hover:underline block truncate">
                                            CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ
                                        </a>
                                        <span class="text-xs text-slate-200 block truncate">@ctthienquy • Thiết bị cơ khí & Vật tư công nghiệp</span>
                                    </div>
                                </div>
                            </div>

                            <!-- Nhúng Facebook Page Plugin kết hợp hình thực tế -->
                            <div class="p-3 space-y-3">
                                <div class="w-full overflow-hidden rounded border border-slate-200 bg-white flex justify-center">
                                    <iframe
                                        title="Fanpage Công Ty TNHH Kỹ Thuật Thiên Quý"
                                        src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fctthienquy&tabs=timeline&width=340&height=180&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true"
                                        width="340"
                                        height="180"
                                        style="border:none;overflow:hidden;max-width:100%;"
                                        scrolling="no"
                                        frameborder="0"
                                        allowfullscreen="true"
                                        allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                                    </iframe>
                                </div>

                                <div class="flex items-center justify-between gap-2 pt-1">
                                    <a href="https://www.facebook.com/ctthienquy" target="_blank" rel="noopener"
                                       class="flex-1 bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold py-2.5 px-3 rounded text-center transition">
                                        <i class="fa-brands fa-facebook-f mr-1"></i> Theo Dõi Fanpage
                                    </a>
                                    <a href="https://www.facebook.com/ctthienquy" target="_blank" rel="noopener"
                                       class="flex-1 bg-slate-200 hover:bg-slate-300 text-slate-800 text-xs font-bold py-2.5 px-3 rounded text-center transition">
                                        <i class="fa-brands fa-facebook-messenger mr-1 text-blue-600"></i> Nhắn Tin Ngay
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         FOOTER CHUẨN FLATSOME (4 CỘT ĐƠN GIẢN, DỄ CHỈNH SỬA TRÊN UX BUILDER)
         ========================================== -->
    <footer class="bg-slate-900 text-slate-300 pt-8 pb-6 mt-4 border-t-4 border-flatsome-primary">
        <div class="ux-container">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-12 gap-6 pb-6 border-b border-slate-800">
                
                <!-- Cột 1: Thông tin công ty (4/12) -->
                <div class="lg:col-span-4 space-y-3">
                    <div class="flex items-center gap-3">
                        <div class="logo-refined-box w-12 h-12 rounded-md p-1 bg-white flex-shrink-0">
                            <img src="https://drive.google.com/thumbnail?id=1U-0CiTUSxu2_0XMzT-P7DiJMBhQphugl&sz=w300"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1U-0CiTUSxu2_0XMzT-P7DiJMBhQphugl';"
                                 alt="Logo Công Ty TNHH Kỹ Thuật Thiên Quý" class="logo-refined-img w-full h-full">
                        </div>
                        <div>
                            <h3 class="text-white font-extrabold text-sm sm:text-base leading-snug">
                                CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ
                            </h3>
                            <span class="text-xs text-amber-400 font-semibold">Website: thienquy.net</span>
                        </div>
                    </div>
                    <p class="text-xs text-slate-400 leading-relaxed">
                        Chuyên cung cấp Vòng bi công nghiệp (SKF, Nachi, Koyo, NSK), Mô-đun công suất IGBT, Dụng cụ đồ nghề, Dụng cụ cầm tay, Máy hàn cắt Plasma, Ty ren & Phụ kiện coppha xây dựng.
                    </p>
                    <ul class="text-xs space-y-1.5 text-slate-300">
                        <li><i class="fa-solid fa-location-dot text-amber-400 mr-1.5"></i><strong>Địa chỉ:</strong> 258 Trần Cao Vân, Phường Tam Kỳ, TP Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone text-amber-400 mr-1.5"></i><strong>Hotline:</strong> <a href="tel:0978102434" class="text-white font-bold hover:underline">0978.102.434</a></li>
                        <li><i class="fa-solid fa-envelope text-amber-400 mr-1.5"></i><strong>Email:</strong> thienquytm@gmail.com</li>
                        <li><i class="fa-solid fa-hashtag text-amber-400 mr-1.5"></i><strong>MST:</strong> 4001249332</li>
                    </ul>
                </div>

                <!-- Cột 2: Danh mục sản phẩm chính (3/12) -->
                <div class="lg:col-span-3">
                    <h4 class="text-white font-bold text-sm uppercase tracking-wider mb-3 pb-1.5 border-b border-slate-800">
                        Danh Mục Sản Phẩm
                    </h4>
                    <ul class="space-y-2 text-xs">
                        <li><button onclick="filterCategory('vong-bi-igbt')" class="hover:text-white transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Vòng Bi SKF, Nachi, Koyo, NSK</button></li>
                        <li><button onclick="filterCategory('vong-bi-igbt')" class="hover:text-white transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Linh Kiện Bán Dẫn & Mô-đun IGBT</button></li>
                        <li><button onclick="filterCategory('dung-cu-do-nghe')" class="hover:text-white transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Dụng Cụ Đồ Nghề (Asaki, Harkcaput)</button></li>
                        <li><button onclick="filterCategory('dung-cu-cam-tay')" class="hover:text-white transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Dụng Cụ Cầm Tay (Bosch, Makita, Ken)</button></li>
                        <li><button onclick="filterCategory('may-han-cat')" class="hover:text-white transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Máy Hàn, Rùa Cắt, Máy Cắt Plasma</button></li>
                        <li><button onclick="filterCategory('coppha-tyren')" class="hover:text-white transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Ty Ren, Coppha Dàn Giáo, Cáp Xích</button></li>
                    </ul>
                </div>

                <!-- Cột 3: Chính sách & Hỗ trợ khách hàng (2/12) -->
                <div class="lg:col-span-2">
                    <h4 class="text-white font-bold text-sm uppercase tracking-wider mb-3 pb-1.5 border-b border-slate-800">
                        Hỗ Trợ Khách Hàng
                    </h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#quote-form-section" class="hover:text-white transition">Yêu cầu báo giá sỉ/lẻ</a></li>
                        <li><a href="#products-section" class="hover:text-white transition">Tra cứu mã sản phẩm</a></li>
                        <li><a href="#blog-section" class="hover:text-white transition">Tư vấn kỹ thuật cơ khí</a></li>
                        <li><a href="https://maps.app.goo.gl/MntnW3VdYEXvnTsd8" target="_blank" rel="noopener" class="hover:text-white transition">Chỉ đường Google Maps</a></li>
                        <li><a href="https://www.facebook.com/ctthienquy" target="_blank" rel="noopener" class="hover:text-white transition">Fanpage Thiên Quý</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Kết nối nhanh (3/12) -->
                <div class="lg:col-span-3">
                    <h4 class="text-white font-bold text-sm uppercase tracking-wider mb-3 pb-1.5 border-b border-slate-800">
                        Liên Hệ Trực Tiếp
                    </h4>
                    <p class="text-xs text-slate-400 mb-3">
                        Hỗ trợ kỹ thuật và báo giá nhanh qua điện thoại hoặc Zalo:
                    </p>
                    <div class="space-y-2">
                        <a href="tel:0978102434" class="w-full bg-flatsome-secondary hover:bg-red-700 text-white text-xs font-bold py-2.5 px-3 rounded flex items-center justify-center gap-2 transition">
                            <i class="fa-solid fa-phone-volume"></i> HOTLINE: 0978.102.434
                        </a>
                        <a href="https://zalo.me/0978102434" target="_blank" rel="noopener" class="w-full bg-blue-600 hover:bg-blue-700 text-white text-xs font-bold py-2.5 px-3 rounded flex items-center justify-center gap-2 transition">
                            <i class="fa-solid fa-comment-dots"></i> CHAT ZALO: 0978.102.434
                        </a>
                    </div>
                </div>

            </div>

            <div class="pt-4 flex flex-col sm:flex-row items-center justify-between text-xs text-slate-500 gap-2">
                <p>© Bản quyền thuộc về <strong class="text-slate-300">CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ (thienquy.net)</strong>.</p>
                <p>258 Trần Cao Vân, Phường Tam Kỳ, TP Đà Nẵng - ĐT: 0978.102.434</p>
            </div>
        </div>
    </footer>

    <!-- ==========================================
         CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE
         ========================================== -->
    <div class="fixed bottom-4 left-3 sm:left-4 z-50 flex flex-col gap-2.5">
        
        <!-- Nút Zalo nổi bật -->
        <a href="https://zalo.me/0978102434" target="_blank" rel="noopener"
           aria-label="Chat Zalo 0978.102.434"
           class="group flex items-center gap-2 bg-[#0068ff] hover:bg-blue-700 text-white rounded-full p-1.5 pr-3.5 shadow-lg transition">
            <span class="relative w-9 h-9 rounded-full bg-white text-[#0068ff] font-extrabold text-xs flex items-center justify-center flex-shrink-0 floating-btn-pulse">
                Zalo
            </span>
            <span class="text-xs font-bold tracking-wide">Chat Zalo</span>
        </a>

        <!-- Nút Facebook Fanpage nổi bật -->
        <a href="https://www.facebook.com/ctthienquy" target="_blank" rel="noopener"
           aria-label="Facebook Công Ty TNHH Kỹ Thuật Thiên Quý"
           class="group flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white rounded-full p-1.5 pr-3.5 shadow-lg transition">
            <span class="relative w-9 h-9 rounded-full bg-white text-[#1877F2] flex items-center justify-center flex-shrink-0 floating-btn-pulse">
                <i class="fa-brands fa-facebook-f text-base"></i>
            </span>
            <span class="text-xs font-bold tracking-wide">Facebook</span>
        </a>

        <!-- Nút Hotline nổi bật -->
        <a href="tel:0978102434"
           aria-label="Gọi Hotline 0978.102.434"
           class="group flex items-center gap-2 bg-flatsome-secondary hover:bg-red-700 text-white rounded-full p-1.5 pr-3.5 shadow-lg transition">
            <span class="relative w-9 h-9 rounded-full bg-white text-flatsome-secondary flex items-center justify-center flex-shrink-0 floating-btn-pulse">
                <i class="fa-solid fa-phone-volume text-sm"></i>
            </span>
            <span class="text-xs font-extrabold tracking-wide">0978.102.434</span>
        </a>

    </div>

    <!-- ==========================================
         MENU DANH MỤC TRƯỢT TRÊN ĐIỆN THOẠI (FLATSOME OFF-CANVAS MENU)
         ========================================== -->
    <div id="mobileDrawerBackdrop" onclick="toggleMobileDrawer()" class="fixed inset-0 bg-black/60 z-50 hidden"></div>
    <aside id="mobileDrawer" class="fixed top-0 left-0 bottom-0 w-[280px] max-w-[85vw] bg-white z-50 -translate-x-full transition-transform duration-300 flex flex-col shadow-2xl">
        <div class="p-3.5 bg-flatsome-primary text-white flex items-center justify-between">
            <div class="flex items-center gap-2">
                <div class="w-8 h-8 rounded bg-white p-0.5 flex items-center justify-center">
                    <img src="https://drive.google.com/thumbnail?id=1U-0CiTUSxu2_0XMzT-P7DiJMBhQphugl&sz=w200"
                         onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1U-0CiTUSxu2_0XMzT-P7DiJMBhQphugl';"
                         alt="Logo" class="w-full h-full object-contain">
                </div>
                <span class="font-bold text-xs uppercase tracking-wider">Danh Mục Thiên Quý</span>
            </div>
            <button onclick="toggleMobileDrawer()" class="w-7 h-7 rounded bg-white/10 flex items-center justify-center text-white">
                <i class="fa-solid fa-xmark"></i>
            </button>
        </div>

        <div class="p-3 overflow-y-auto flex-1 divide-y divide-slate-100 text-xs font-semibold text-slate-700">
            <button onclick="filterCategoryMobile('all')" class="w-full py-2.5 text-left flex items-center justify-between hover:text-flatsome-primary">
                <span><i class="fa-solid fa-border-all w-5 text-flatsome-primary"></i> Tất Cả Sản Phẩm (16)</span>
                <i class="fa-solid fa-angle-right text-slate-400"></i>
            </button>
            <button onclick="filterCategoryMobile('vong-bi-igbt')" class="w-full py-2.5 text-left flex items-center justify-between hover:text-flatsome-primary">
                <span><i class="fa-solid fa-gear w-5 text-flatsome-primary"></i> Vòng Bi SKF, Nachi, Koyo, NSK</span>
                <i class="fa-solid fa-angle-right text-slate-400"></i>
            </button>
            <button onclick="filterCategoryMobile('vong-bi-igbt')" class="w-full py-2.5 text-left flex items-center justify-between hover:text-flatsome-primary">
                <span><i class="fa-solid fa-microchip w-5 text-flatsome-primary"></i> Linh Kiện Bán Dẫn & Mô-đun IGBT</span>
                <i class="fa-solid fa-angle-right text-slate-400"></i>
            </button>
            <button onclick="filterCategoryMobile('dung-cu-do-nghe')" class="w-full py-2.5 text-left flex items-center justify-between hover:text-flatsome-primary">
                <span><i class="fa-solid fa-toolbox w-5 text-flatsome-primary"></i> Dụng Cụ Đồ Nghề (Asaki, Harkcaput)</span>
                <i class="fa-solid fa-angle-right text-slate-400"></i>
            </button>
            <button onclick="filterCategoryMobile('dung-cu-cam-tay')" class="w-full py-2.5 text-left flex items-center justify-between hover:text-flatsome-primary">
                <span><i class="fa-solid fa-hammer w-5 text-flatsome-primary"></i> Dụng Cụ Cầm Tay (Bosch, Makita)</span>
                <i class="fa-solid fa-angle-right text-slate-400"></i>
            </button>
            <button onclick="filterCategoryMobile('may-han-cat')" class="w-full py-2.5 text-left flex items-center justify-between hover:text-flatsome-primary">
                <span><i class="fa-solid fa-fire-flame-curved w-5 text-flatsome-primary"></i> Máy Hàn, Rùa Cắt, Máy Cắt Plasma</span>
                <i class="fa-solid fa-angle-right text-slate-400"></i>
            </button>
            <button onclick="filterCategoryMobile('da-cat-mui-khoan')" class="w-full py-2.5 text-left flex items-center justify-between hover:text-flatsome-primary">
                <span><i class="fa-solid fa-compact-disc w-5 text-flatsome-primary"></i> Đá Cắt, Đá Mài, Mũi Khoan, Nhám</span>
                <i class="fa-solid fa-angle-right text-slate-400"></i>
            </button>
            <button onclick="filterCategoryMobile('coppha-tyren')" class="w-full py-2.5 text-left flex items-center justify-between hover:text-flatsome-primary">
                <span><i class="fa-solid fa-layer-group w-5 text-flatsome-primary"></i> Ty Ren, Phụ Kiện Coppha, Cáp Xích</span>
                <i class="fa-solid fa-angle-right text-slate-400"></i>
            </button>
            <button onclick="filterCategoryMobile('banh-xe-ke-thang')" class="w-full py-2.5 text-left flex items-center justify-between hover:text-flatsome-primary">
                <span><i class="fa-solid fa-dolly w-5 text-flatsome-primary"></i> Bánh Xe, Xe Đẩy, Kệ & Thang Nhôm</span>
                <i class="fa-solid fa-angle-right text-slate-400"></i>
            </button>
        </div>

        <div class="p-3.5 bg-slate-50 border-t border-slate-200 text-xs space-y-1.5">
            <div class="font-bold text-flatsome-primary">CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ</div>
            <div class="text-slate-600">258 Trần Cao Vân, P. Tam Kỳ, TP Đà Nẵng</div>
            <div class="font-bold text-flatsome-secondary">SĐT: 0978.102.434</div>
        </div>
    </aside>

    <!-- ==========================================
         MODAL XEM NHANH SẢN PHẨM (QUICK VIEW LIGHTBOX GIỐNG FLATSOME)
         ========================================== -->
    <div id="quickViewModal" class="fixed inset-0 bg-black/70 z-50 hidden items-center justify-center p-3">
        <div class="bg-white rounded-md max-w-3xl w-full overflow-hidden shadow-2xl relative max-h-[90vh] overflow-y-auto">
            <button onclick="closeQuickView()" aria-label="Đóng xem nhanh" class="absolute top-3 right-3 z-20 w-8 h-8 rounded-full bg-slate-200 hover:bg-slate-300 text-slate-800 flex items-center justify-center">
                <i class="fa-solid fa-xmark"></i>
            </button>

            <div class="grid grid-cols-1 md:grid-cols-12">
                <!-- Cột ảnh thực tế sản phẩm -->
                <div class="md:col-span-6 bg-slate-100 relative aspect-square">
                    <span id="qvDiscountBadge" class="onsale-badge absolute top-3 left-3 z-10">-15%</span>
                    <img id="qvImage" src="" alt="Ảnh sản phẩm thực tế" class="w-full h-full object-cover">
                </div>

                <!-- Cột thông tin chi tiết Xem Nhanh chuẩn Flatsome -->
                <div class="md:col-span-6 p-4 sm:p-6 flex flex-col justify-between">
                    <div>
                        <span id="qvCategory" class="text-xs font-bold uppercase text-flatsome-primary tracking-wider"></span>
                        <h3 id="qvTitle" class="text-base sm:text-xl font-extrabold text-slate-800 mt-1 mb-2"></h3>
                        <div class="w-10 h-1 bg-slate-200 mb-3"></div>

                        <!-- Giá gốc & Giá giảm Flatsome -->
                        <div class="flex items-baseline gap-2.5 mb-3">
                            <del id="qvOldPrice" class="text-sm text-slate-400 font-medium"></del>
                            <ins id="qvSalePrice" class="text-lg sm:text-xl font-extrabold text-flatsome-secondary no-underline"></ins>
                        </div>

                        <p id="qvDesc" class="text-xs sm:text-sm text-slate-600 leading-relaxed mb-4"></p>

                        <div class="text-xs bg-slate-50 p-3 rounded border border-slate-200 space-y-1 text-slate-700 mb-4">
                            <div><strong>Đơn vị cung cấp:</strong> CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ</div>
                            <div><strong>Địa chỉ kho:</strong> 258 Trần Cao Vân, Phường Tam Kỳ, TP Đà Nẵng</div>
                            <div><strong>Tình trạng:</strong> <span class="text-emerald-600 font-bold">Sẵn hàng thực tế tại kho</span></div>
                        </div>
                    </div>

                    <div class="space-y-2">
                        <button onclick="selectProductForQuote()" class="w-full bg-flatsome-secondary hover:bg-red-700 text-white font-bold text-xs sm:text-sm py-2.5 px-4 rounded transition flex items-center justify-center gap-2">
                            <i class="fa-solid fa-file-signature"></i> YÊU CẦU BÁO GIÁ SẢN PHẨM NÀY
                        </button>
                        <div class="grid grid-cols-2 gap-2">
                            <a href="tel:0978102434" class="bg-flatsome-primary hover:bg-blue-900 text-white font-bold text-xs py-2 px-3 rounded text-center transition">
                                <i class="fa-solid fa-phone mr-1"></i> 0978.102.434
                            </a>
                            <a href="https://zalo.me/0978102434" target="_blank" rel="noopener" class="bg-blue-600 hover:bg-blue-700 text-white font-bold text-xs py-2 px-3 rounded text-center transition">
                                <i class="fa-solid fa-comment-dots mr-1"></i> Nhắn Zalo
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- ==========================================
         MODAL ĐỌC BÀI VIẾT KỸ THUẬT
         ========================================== -->
    <div id="blogModal" class="fixed inset-0 bg-black/70 z-50 hidden items-center justify-center p-3">
        <div class="bg-white rounded-md max-w-2xl w-full overflow-hidden shadow-2xl relative max-h-[90vh] overflow-y-auto p-4 sm:p-6">
            <button onclick="closeBlogModal()" class="absolute top-3 right-3 w-8 h-8 rounded-full bg-slate-200 hover:bg-slate-300 text-slate-800 flex items-center justify-center">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <span id="bmCategory" class="text-xs font-bold uppercase text-flatsome-primary"></span>
            <h3 id="bmTitle" class="text-lg sm:text-xl font-extrabold text-slate-800 mt-1 mb-3"></h3>
            <img id="bmImage" src="" alt="Ảnh bài viết" class="w-full h-56 sm:h-64 object-cover rounded mb-4 border border-slate-200">
            <div id="bmContent" class="text-xs sm:text-sm text-slate-700 space-y-2.5 leading-relaxed"></div>
            <div class="mt-5 pt-4 border-t border-slate-200 flex items-center justify-between text-xs text-slate-500">
                <span>CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ - 0978.102.434</span>
                <button onclick="closeBlogModal()" class="bg-slate-800 text-white px-4 py-1.5 rounded font-semibold">Đóng</button>
            </div>
        </div>
    </div>

    <!-- ==========================================
         JAVASCRIPT XỬ LÝ DỮ LIỆU THỰC TẾ & TƯƠNG TÁC FLATSOME
         ========================================== -->
    <script>
        /* Danh sách toàn bộ 16 ảnh thực tế từ Google Drive của Công Ty TNHH Kỹ Thuật Thiên Quý */
        const productsData = [
            {
                id: 1,
                driveId: '1yg6XvqnwKtMjBC2ZxtTEZo0xD1a-Eo0m',
                title: 'Vòng Bi Công Nghiệp Chính Hãng SKF / Nachi Chịu Tải Cao',
                categorySlug: 'vong-bi-igbt',
                categoryName: 'Vòng Bi & IGBT',
                oldPrice: '380.000₫',
                salePrice: '320.000₫',
                discount: '-16%',
                desc: 'Vòng bi - bạc đạn công nghiệp chính hãng SKF, Nachi, Koyo, NSK chuyên dùng cho động cơ điện, máy cơ khí và dây chuyền sản xuất tại Kỹ Thuật Thiên Quý.'
            },
            {
                id: 2,
                driveId: '1eVutGgveAAS1eJARWXUfmd7rwvfp_j5N',
                title: 'Mô-đun Công Suất Bán Dẫn IGBT ESM200SH60FA 200A 600V',
                categorySlug: 'vong-bi-igbt',
                categoryName: 'Vòng Bi & IGBT',
                oldPrice: '1.450.000₫',
                salePrice: '1.250.000₫',
                discount: '-14%',
                desc: 'Linh kiện bán dẫn / Mô-đun công suất IGBT chuyên dụng cho biến tần, máy hàn công nghiệp, tủ điều khiển điện công suất lớn.'
            },
            {
                id: 3,
                driveId: '17Og6NDOXnrYWgR68UU0NOY-q6JpbdtgD',
                title: 'Bộ Vòng Bi Bạc Đạn & Gối Đỡ Công Nghiệp Koyo / NSK',
                categorySlug: 'vong-bi-igbt',
                categoryName: 'Vòng Bi & IGBT',
                oldPrice: '520.000₫',
                salePrice: '440.000₫',
                discount: '-15%',
                desc: 'Cung cấp đầy đủ mã vòng bi cầu, vòng bi đũa, vòng bi côn và gối đỡ phục vụ bảo trì nhà máy, xưởng cơ khí.'
            },
            {
                id: 4,
                driveId: '1uj0yENXnY0WE8aWyT-Wx9LZFddvmCGQx',
                title: 'Thiết Bị Điện & Phụ Tùng Cơ Khí Bảo Trì Máy Móc',
                categorySlug: 'vong-bi-igbt',
                categoryName: 'Vòng Bi & IGBT',
                oldPrice: '650.000₫',
                salePrice: '540.000₫',
                discount: '-17%',
                desc: 'Phụ tùng kỹ thuật chính xác phục vụ lắp đặt, sửa chữa và bảo trì hệ thống cơ điện công nghiệp.'
            },
            {
                id: 5,
                driveId: '1DjIRF9GbXvPzqhLASIkc65g_25l1Yh7Q',
                title: 'Bộ Dụng Cụ Đồ Nghề Sửa Chữa Cơ Khí Đa Năng Asaki',
                categorySlug: 'dung-cu-do-nghe',
                categoryName: 'Dụng Cụ Đồ Nghề',
                oldPrice: '980.000₫',
                salePrice: '820.000₫',
                discount: '-16%',
                desc: 'Bộ dụng cụ đồ nghề chuyên nghiệp gồm cờ lê, mỏ lết, kìm cắt, đầu khẩu thép hợp kim siêu bền cho thợ kỹ thuật.'
            },
            {
                id: 6,
                driveId: '18iRse5KupLoIllKmpLt0ON3QlUSLAxuc',
                title: 'Kìm Bấm Cos, Kìm Cắt Cáp & Dụng Cụ Đồ Nghề Harkcaput',
                categorySlug: 'dung-cu-do-nghe',
                categoryName: 'Dụng Cụ Đồ Nghề',
                oldPrice: '290.000₫',
                salePrice: '245.000₫',
                discount: '-15%',
                desc: 'Dụng cụ cầm tay cơ khí chính hãng Asaki, Halboshi, Harkcaput độ bền cao, thao tác chính xác.'
            },
            {
                id: 7,
                driveId: '1VSKFmUEiiYZYaqixWRtRQJJndSgmZ2VZ',
                title: 'Máy Mài Góc & Máy Khoan Cầm Tay Công Suất Cao',
                categorySlug: 'dung-cu-cam-tay',
                categoryName: 'Dụng Cụ Cầm Tay',
                oldPrice: '1.390.000₫',
                salePrice: '1.150.000₫',
                discount: '-17%',
                desc: 'Dụng cụ điện cầm tay chuyên dụng cho công trình xây dựng và xưởng gia công cơ khí sắt thép.'
            },
            {
                id: 8,
                driveId: '1q5QWr9EaK6tLB8CX7UthGZSguBpdCdrz',
                title: 'Máy Khoan Rút Lõi Bê Tông & Máy Cắt Sắt Công Nghiệp',
                categorySlug: 'dung-cu-cam-tay',
                categoryName: 'Dụng Cụ Cầm Tay',
                oldPrice: '2.650.000₫',
                salePrice: '2.250.000₫',
                discount: '-15%',
                desc: 'Động cơ dây đồng mạnh mẽ, vận hành bền bỉ, phù hợp thi công cơ điện lạnh và xây dựng công trình.'
            },
            {
                id: 9,
                driveId: '1HwjU6a4rEHSnW_i5KgAf8rEd_bzHgEpL',
                title: 'Máy Hàn Điện Tử IGBT & Máy Cắt Kim Loại Plasma',
                categorySlug: 'may-han-cat',
                categoryName: 'Máy Hàn & Cắt Plasma',
                oldPrice: '3.400.000₫',
                salePrice: '2.890.000₫',
                discount: '-15%',
                desc: 'Ứng dụng công nghệ biến tần IGBT tiết kiệm điện, hồ quang ổn định, mối hàn ngấu đẹp.'
            },
            {
                id: 10,
                driveId: '1N7ZouNs_zi40NPsfoZ2A2juIy3zgAYAp',
                title: 'Rùa Cắt Gió Đá Xách Tay & Phụ Kiện Hàn Cắt Công Nghiệp',
                categorySlug: 'may-han-cat',
                categoryName: 'Máy Hàn & Cắt Plasma',
                oldPrice: '1.950.000₫',
                salePrice: '1.650.000₫',
                discount: '-15%',
                desc: 'Thiết bị cắt kim loại tự động và bán tự động, phụ kiện mỏ hàn, đồng hồ khí, bép cắt chính hãng.'
            },
            {
                id: 11,
                driveId: '1GXepKE86d13FhQ6qgBE7zBw214hidDYG',
                title: 'Bộ Ty Ren, Bát Chuồn, Bulong Đai Ốc & Đai Treo Ống',
                categorySlug: 'coppha-tyren',
                categoryName: 'Ty Ren & Phụ Kiện Coppha',
                oldPrice: '180.000₫',
                salePrice: '150.000₫',
                discount: '-17%',
                desc: 'Vật tư phụ kiện cơ điện M&E: Ty ren mạ kẽm, kẹp treo, Ubolt, bulong cường độ cao, lưới xây dựng.'
            },
            {
                id: 12,
                driveId: '1aqW4YkymcQEjg092JNmc7JyKRqlZv2QY',
                title: 'Cùm Xoay, Cùm Tĩnh, Kích Tăng & Phụ Kiện Dàn Giáo',
                categorySlug: 'coppha-tyren',
                categoryName: 'Ty Ren & Phụ Kiện Coppha',
                oldPrice: '420.000₫',
                salePrice: '350.000₫',
                discount: '-17%',
                desc: 'Phụ kiện coppha dàn giáo tiêu chuẩn xây dựng, đinh chống cắt, đinh hàn chịu lực an toàn cao.'
            },
            {
                id: 13,
                driveId: '1bfBtK7uR9Mt9sJoJCHVkrPSebdF-sNUL',
                title: 'Đá Cắt Inox, Đá Mài Kim Loại & Que Hàn Điện Chịu Lực',
                categorySlug: 'da-cat-mui-khoan',
                categoryName: 'Đá Cắt, Mũi Khoan, Nhám',
                oldPrice: '260.000₫',
                salePrice: '215.000₫',
                discount: '-17%',
                desc: 'Đá cắt bén ngọt, ít hao mòn, an toàn tốc độ vòng quay cao, chuyên dùng cho xưởng sắt và inox.'
            },
            {
                id: 14,
                driveId: '167K9BLAJbX0N0JdqFDGT9epQ_83P-OH_',
                title: 'Mũi Khoan Bê Tông, Mũi Khoan Inox Nachi & Lưỡi Cắt Gạch Đá',
                categorySlug: 'da-cat-mui-khoan',
                categoryName: 'Đá Cắt, Mũi Khoan, Nhám',
                oldPrice: '310.000₫',
                salePrice: '260.000₫',
                discount: '-16%',
                desc: 'Đầy đủ kích cỡ mũi khoan thép gió, mũi khoan inox, mũi khoét kính, lưỡi cắt bê tông và đá granite.'
            },
            {
                id: 15,
                driveId: '1OuSlLHE7UF2lr-y-JIxyJ53PbGtu-yHn',
                title: 'Nhám Xếp, Bánh Vải, Chổi Đánh Rỉ & Vật Tư Đánh Bóng Inox',
                categorySlug: 'da-cat-mui-khoan',
                categoryName: 'Đá Cắt, Mũi Khoan, Nhám',
                oldPrice: '220.000₫',
                salePrice: '185.000₫',
                discount: '-16%',
                desc: 'Vật tư mài mòn & đánh bóng bề mặt kim loại: nhám xếp, nỉ trắng lông cừu, bánh xơ dừa, sáp đánh bóng.'
            },
            {
                id: 16,
                driveId: '1kErVKOWfq5UhE2F56T2VaXVg6Ve8qmOO',
                title: 'Bánh Xe Công Nghiệp Chịu Tải, Xe Đẩy Hàng & Dụng Cụ Nâng Hạ',
                categorySlug: 'banh-xe-ke-thang',
                categoryName: 'Bánh Xe, Xe Đẩy & Nâng Hạ',
                oldPrice: '890.000₫',
                salePrice: '750.000₫',
                discount: '-16%',
                desc: 'Bánh xe dàn giáo có khóa, càng bánh xe tải nặng, xe đẩy hàng nhà xưởng, dây cáp thép và xích nâng hạ.'
            }
        ];

        /* Dữ liệu Danh mục Bài viết Trang chủ (Sử dụng ảnh thực tế từ Google Drive) */
        const blogPostsData = [
            {
                id: 101,
                categorySlug: 'vong-bi',
                categoryName: 'Kỹ Thuật Vòng Bi',
                date: '15/10/2026',
                driveId: '1yg6XvqnwKtMjBC2ZxtTEZo0xD1a-Eo0m',
                title: '3 Dấu hiệu vòng bi cần thay thế và địa chỉ mua SKF, Nachi, Koyo, NSK uy tín',
                excerpt: 'Nhận biết sớm tiếng ồn bất thường, nhiệt độ tăng cao và độ rung lắc trên cụm ổ trục giúp bảo vệ máy móc tránh hư hỏng nặng...',
                content: `
                    <p><strong>1. Tiếng ồn bất thường khi vận hành:</strong> Khi vòng bi xuất hiện tiếng rít hoặc lạo xạo kim loại, đó là dấu hiệu rãnh lăn hoặc viên bi đã bị mài mòn, tróc rỗ hoặc thiếu mỡ bôi trơn chuyên dụng.</p>
                    <p><strong>2. Nhiệt độ cụm ổ đỡ tăng cao:</strong> Nhiệt độ vượt ngưỡng cho phép thường xuất phát từ việc lắp sai khe hở, quá tải hoặc vòng bi đã xuống cấp.</p>
                    <p><strong>3. Độ rung động lớn:</strong> Độ rơ dọc trục và hướng kính tăng làm giảm độ chính xác gia công của máy cơ khí.</p>
                    <p>Tại <strong>CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ (258 Trần Cao Vân, Phường Tam Kỳ, TP Đà Nẵng - SĐT: 0978.102.434)</strong>, chúng tôi cung cấp đầy đủ các dòng vòng bi SKF, Nachi, Koyo, NSK chính hãng cùng dịch vụ tư vấn chọn mã chuẩn xác.</p>
                `
            },
            {
                id: 102,
                categorySlug: 'dien-igbt',
                categoryName: 'Linh Kiện IGBT',
                date: '10/10/2026',
                driveId: '1eVutGgveAAS1eJARWXUfmd7rwvfp_j5N',
                title: 'Kinh nghiệm kiểm tra và chọn Mô-đun công suất IGBT 200A 600V cho biến tần & máy hàn',
                excerpt: 'Hướng dẫn thông số kỹ thuật mô-đun bán dẫn công suất ESM200SH60FA và lưu ý tản nhiệt khi lắp đặt trong tủ điện công nghiệp...',
                content: `
                    <p>Mô-đun công suất IGBT đóng vai trò đóng cắt tần số cao trong các bộ biến tần công nghiệp, máy hàn công suất lớn và bộ nguồn xung.</p>
                    <p>Khi thay thế IGBT, kỹ thuật viên cần lưu ý kiểm tra kỹ mạch kích Gate (Driver), làm sạch bề mặt tản nhiệt và bôi keo tản nhiệt đều trước khi siết lực bulong theo đúng tiêu chuẩn.</p>
                    <p>Liên hệ <strong>Kỹ Thuật Thiên Quý (0978.102.434)</strong> để được cung cấp linh kiện bán dẫn và mô-đun công suất chất lượng cao.</p>
                `
            },
            {
                id: 103,
                categorySlug: 'dung-cu-may',
                categoryName: 'Kinh Nghiệm Dụng Cụ & Máy',
                date: '05/10/2026',
                driveId: '1VSKFmUEiiYZYaqixWRtRQJJndSgmZ2VZ',
                title: 'Các vấn đề cần lưu ý khi chọn mua máy khoan, máy mài cầm tay và đá cắt an toàn',
                excerpt: 'Lựa chọn đúng công suất máy cầm tay, tốc độ vòng quay của đá cắt và mũi khoan giúp tăng hiệu suất thi công tại công trình...',
                content: `
                    <p>Việc chọn đúng dòng máy khoan, máy mài góc phù hợp với cường độ làm việc tại xưởng cơ khí hoặc công trình xây dựng giúp nâng cao tuổi thọ thiết bị và đảm bảo an toàn lao động.</p>
                    <p>Luôn kiểm tra thông số tốc độ tối đa trên đá cắt, đá mài và sử dụng chụp bảo vệ đầy đủ trong suốt quá trình vận hành.</p>
                `
            },
            {
                id: 104,
                categorySlug: 'dung-cu-may',
                categoryName: 'Kinh Nghiệm Dụng Cụ & Máy',
                date: '28/09/2026',
                driveId: '1GXepKE86d13FhQ6qgBE7zBw214hidDYG',
                title: 'Bảng quy cách Ty ren, Bát chuồn, Bulong đai ốc và Phụ kiện Coppha xây dựng',
                excerpt: 'Tổng hợp kích thước ty ren M8, M10, M12, ty ren vuông bát chuồn và phụ kiện cùm dàn giáo thông dụng trong thi công...',
                content: `
                    <p>Trong thi công hệ thống cơ điện (M&E) và lắp dựng coppha công trình, việc chọn đúng cấp bền của bulong, ty ren và đai treo ống quyết định trực tiếp đến độ an toàn chịu lực.</p>
                    <p>Quý khách hàng cần bảng báo giá vật tư kim khí, phụ kiện coppha tổng hợp vui lòng liên hệ trực tiếp Hotline/Zalo: <strong>0978.102.434</strong>.</p>
                `
            }
        ];

        let activeQuickViewProduct = null;

        /* Hàm tạo đường dẫn ảnh Google Drive chuẩn kèm fallback */
        function getDriveThumb(driveId, size = 'w800') {
            return `https://drive.google.com/thumbnail?id=${driveId}&sz=${size}`;
        }
        function getDriveFallback(driveId) {
            return `https://lh3.googleusercontent.com/d/${driveId}`;
        }

        /* Render danh sách sản phẩm chuẩn Flatsome (2 cột trên điện thoại, có % giảm giá và nút XEM NHANH) */
        function renderProducts(list) {
            const grid = document.getElementById('productsGrid');
            const countLabel = document.getElementById('productCountLabel');
            countLabel.textContent = `Hiển thị ${list.length} sản phẩm`;

            if (list.length === 0) {
                grid.innerHTML = `
                    <div class="col-span-full py-10 text-center text-slate-500 text-sm">
                        Không tìm thấy sản phẩm phù hợp. Vui lòng thử từ khóa khác hoặc gọi <strong class="text-flatsome-primary">0978.102.434</strong>.
                    </div>
                `;
                return;
            }

            grid.innerHTML = list.map(item => `
                <div class="product-small box">
                    <div class="box-image">
                        <!-- Nhãn % giảm giá giống Flatsome -->
                        <div class="badge-container">
                            <div class="onsale-badge">${item.discount}</div>
                        </div>

                        <img src="${getDriveThumb(item.driveId, 'w800')}"
                             onerror="this.onerror=null;this.src='${getDriveFallback(item.driveId)}';"
                             alt="${item.title}"
                             loading="lazy"
                             onclick="openQuickView(${item.id})"
                             class="cursor-pointer">

                        <!-- Nút Xem Nhanh sản phẩm giống Flatsome -->
                        <button type="button" onclick="openQuickView(${item.id})" class="quick-view-bar">
                            <i class="fa-solid fa-eye mr-1"></i> XEM NHANH
                        </button>
                    </div>

                    <div class="box-text p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between text-center">
                        <div>
                            <p class="text-[10px] sm:text-[11px] uppercase tracking-wider text-slate-400 font-semibold truncate mb-0.5">
                                ${item.categoryName}
                            </p>
                            <h3 onclick="openQuickView(${item.id})" class="text-xs sm:text-sm font-bold text-slate-800 hover:text-flatsome-primary cursor-pointer line-clamp-2 min-h-[2.4rem] leading-snug">
                                ${item.title}
                            </h3>
                        </div>

                        <div class="mt-2 pt-2 border-t border-slate-100">
                            <!-- Giá gốc và Giá giảm chuẩn Flatsome -->
                            <div class="flex items-center justify-center gap-1.5 flex-wrap">
                                <del class="text-[11px] sm:text-xs text-slate-400">${item.oldPrice}</del>
                                <ins class="text-xs sm:text-sm font-extrabold text-flatsome-secondary no-underline">${item.salePrice}</ins>
                            </div>
                        </div>
                    </div>
                </div>
            `).join('');
        }

        /* Lọc sản phẩm theo Danh mục */
        function filterCategory(slug) {
            const titleEl = document.getElementById('currentCategoryTitle');
            const categoryNames = {
                'all': 'Sản Phẩm Thực Tế Tại Kỹ Thuật Thiên Quý',
                'vong-bi-igbt': 'Vòng Bi Công Nghiệp & Mô-đun Bán Dẫn IGBT',
                'dung-cu-do-nghe': 'Dụng Cụ Đồ Nghề (Asaki, Halboshi, Harkcaput)',
                'dung-cu-cam-tay': 'Dụng Cụ Cầm Tay (Bosch, Makita, Hitachi, Ken)',
                'may-han-cat': 'Máy Hàn, Rùa Cắt, Máy Cắt Plasma',
                'da-cat-mui-khoan': 'Đá Cắt, Đá Mài, Mũi Khoan, Nhám Xếp',
                'coppha-tyren': 'Ty Ren, Phụ Kiện Coppha Dàn Giáo & Nâng Hạ',
                'banh-xe-ke-thang': 'Bánh Xe, Xe Đẩy, Kệ Đa Năng & Thang Nhôm'
            };

            titleEl.textContent = categoryNames[slug] || 'Danh Sách Sản Phẩm';

            const filtered = slug === 'all'
                ? productsData
                : productsData.filter(p => p.categorySlug === slug);

            renderProducts(filtered);
            scrollToSection('products-section');
        }

        function filterCategoryMobile(slug) {
            toggleMobileDrawer();
            filterCategory(slug);
        }

        /* Tìm kiếm sản phẩm trực tiếp */
        function handleSearchProducts(keyword) {
            const q = keyword.trim().toLowerCase();
            if (!q) {
                renderProducts(productsData);
                return;
            }
            const filtered = productsData.filter(p =>
                p.title.toLowerCase().includes(q) ||
                p.categoryName.toLowerCase().includes(q) ||
                p.desc.toLowerCase().includes(q)
            );
            renderProducts(filtered);
        }

        /* Mở / Đóng Modal Xem Nhanh (Quick View Flatsome) */
        function openQuickView(productId) {
            const product = productsData.find(p => p.id === productId);
            if (!product) return;
            activeQuickViewProduct = product;

            const imgEl = document.getElementById('qvImage');
            imgEl.src = getDriveThumb(product.driveId, 'w1000');
            imgEl.onerror = function() {
                this.onerror = null;
                this.src = getDriveFallback(product.driveId);
            };

            document.getElementById('qvDiscountBadge').textContent = product.discount;
            document.getElementById('qvCategory').textContent = product.categoryName;
            document.getElementById('qvTitle').textContent = product.title;
            document.getElementById('qvOldPrice').textContent = product.oldPrice;
            document.getElementById('qvSalePrice').textContent = product.salePrice;
            document.getElementById('qvDesc').textContent = product.desc;

            const modal = document.getElementById('quickViewModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeQuickView() {
            const modal = document.getElementById('quickViewModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        function selectProductForQuote() {
            if (activeQuickViewProduct) {
                const msgEl = document.getElementById('quoteMessage');
                msgEl.value = `Tôi cần báo giá sản phẩm: ${activeQuickViewProduct.title} (Giá niêm yết: ${activeQuickViewProduct.salePrice}). Số lượng: `;
            }
            closeQuickView();
            scrollToSection('quote-form-section');
            setTimeout(() => {
                document.getElementById('quoteName').focus();
            }, 400);
        }

        /* Render Danh mục Bài viết Trang chủ */
        function renderBlogPosts(list) {
            const grid = document.getElementById('blogPostsGrid');
            grid.innerHTML = list.map(post => `
                <article onclick="openBlogModal(${post.id})" class="bg-white rounded border border-slate-200 overflow-hidden hover:shadow-md transition cursor-pointer flex flex-col justify-between group">
                    <div>
                        <div class="relative h-44 bg-slate-100 overflow-hidden">
                            <img src="${getDriveThumb(post.driveId, 'w800')}"
                                 onerror="this.onerror=null;this.src='${getDriveFallback(post.driveId)}';"
                                 alt="${post.title}"
                                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                            <span class="absolute top-2.5 left-2.5 bg-flatsome-primary text-white text-[10px] font-bold uppercase px-2 py-0.5 rounded">
                                ${post.categoryName}
                            </span>
                        </div>
                        <div class="p-3.5">
                            <div class="text-[11px] text-slate-400 mb-1"><i class="fa-regular fa-calendar mr-1"></i>${post.date}</div>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-flatsome-primary line-clamp-2 mb-1.5 leading-snug">
                                ${post.title}
                            </h3>
                            <p class="text-xs text-slate-500 line-clamp-2 leading-relaxed">
                                ${post.excerpt}
                            </p>
                        </div>
                    </div>
                    <div class="px-3.5 pb-3 pt-1">
                        <span class="text-xs font-bold text-flatsome-primary group-hover:underline">
                            Đọc tiếp <i class="fa-solid fa-arrow-right-long ml-1"></i>
                        </span>
                    </div>
                </article>
            `).join('');
        }

        function filterBlog(slug) {
            const filtered = slug === 'all'
                ? blogPostsData
                : blogPostsData.filter(b => b.categorySlug === slug);
            renderBlogPosts(filtered);
        }

        function openBlogModal(postId) {
            const post = blogPostsData.find(b => b.id === postId);
            if (!post) return;
            document.getElementById('bmCategory').textContent = `${post.categoryName} • ${post.date}`;
            document.getElementById('bmTitle').textContent = post.title;
            const img = document.getElementById('bmImage');
            img.src = getDriveThumb(post.driveId, 'w1000');
            img.onerror = function() {
                this.onerror = null;
                this.src = getDriveFallback(post.driveId);
            };
            document.getElementById('bmContent').innerHTML = post.content;

            const modal = document.getElementById('blogModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeBlogModal() {
            const modal = document.getElementById('blogModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        /* Xử lý Form Yêu cầu & Báo giá Trang chủ */
        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('quoteName').value.trim();
            const phone = document.getElementById('quotePhone').value.trim();
            const category = document.getElementById('quoteCategory').value;
            const message = document.getElementById('quoteMessage').value.trim();

            const alertBox = document.getElementById('quoteSuccessAlert');
            const detailEl = document.getElementById('quoteSuccessDetail');
            detailEl.textContent = `Cảm ơn ${name} (${phone}). Yêu cầu báo giá mục "${category}" với nội dung "${message}" đã được ghi nhận. Bộ phận kinh doanh CÔNG TY TNHH KỸ THUẬT THIÊN QUÝ (0978.102.434) sẽ liên hệ ngay!`;
            alertBox.classList.remove('hidden');
            e.target.reset();
        }

        /* Xử lý 2 Banner Tự Trượt (Auto Slider) */
        let currentBannerIndex = 0;
        const totalBanners = 2;
        let bannerInterval = null;

        function showBannerSlide(index) {
            for (let i = 0; i < totalBanners; i++) {
                const slide = document.getElementById(`banner-slide-${i}`);
                const dot = document.getElementById(`banner-dot-${i}`);
                if (i === index) {
                    slide.classList.remove('opacity-0', 'z-0', 'pointer-events-none');
                    slide.classList.add('opacity-100', 'z-10');
                    dot.className = 'w-6 h-2 rounded-full bg-amber-400 transition-all';
                } else {
                    slide.classList.remove('opacity-100', 'z-10');
                    slide.classList.add('opacity-0', 'z-0', 'pointer-events-none');
                    dot.className = 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
                }
            }
            currentBannerIndex = index;
        }

        function nextBannerSlide() {
            const next = (currentBannerIndex + 1) % totalBanners;
            showBannerSlide(next);
            resetBannerTimer();
        }

        function prevBannerSlide() {
            const prev = (currentBannerIndex - 1 + totalBanners) % totalBanners;
            showBannerSlide(prev);
            resetBannerTimer();
        }

        function goToBannerSlide(index) {
            showBannerSlide(index);
            resetBannerTimer();
        }

        function resetBannerTimer() {
            if (bannerInterval) clearInterval(bannerInterval);
            bannerInterval = setInterval(() => {
                const next = (currentBannerIndex + 1) % totalBanners;
                showBannerSlide(next);
            }, 4500);
        }

        /* Đóng/Mở Menu Danh Mục trên Điện Thoại */
        function toggleMobileDrawer() {
            const drawer = document.getElementById('mobileDrawer');
            const backdrop = document.getElementById('mobileDrawerBackdrop');
            const isOpen = !drawer.classList.contains('-translate-x-full');
            if (isOpen) {
                drawer.classList.add('-translate-x-full');
                backdrop.classList.add('hidden');
            } else {
                drawer.classList.remove('-translate-x-full');
                backdrop.classList.remove('hidden');
            }
        }

        function scrollToSection(id) {
            const el = document.getElementById(id);
            if (el) {
                el.scrollIntoView({ behavior: 'smooth', block: 'start' });
            }
        }

        /* Khởi tạo khi tải trang */
        window.onload = function() {
            renderProducts(productsData);
            renderBlogPosts(blogPostsData);
            resetBannerTimer();
        };
    </script>
</body>
</html>
