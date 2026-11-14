<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Nha Khoa Tám Sinh - Công Ty TNHH MTV Nha Khoa Tám Sinh Đà Nẵng | nhakhoatamsinh.com</title>
    <meta name="description" content="CÔNG TY TNHH MỘT THÀNH VIÊN NHA KHOA TÁM SINH (nhakhoatamsinh.com) - Địa chỉ: 141 Tôn Đản, Phường An Khê, TP Đà Nẵng. Chuyên Thẩm mỹ Răng sứ, Dán sứ Veneer, Cấy ghép Implant, Chỉnh nha Niềng răng và Nha khoa tổng quát uy tín. Hotline: 0702.303.779.">
    <meta name="keywords" content="Nha Khoa Tám Sinh, nhakhoatamsinh.com, nha khoa Đà Nẵng, 141 Tôn Đản Đà Nẵng, bọc răng sứ Đà Nẵng, trồng răng implant Đà Nẵng, niềng răng Đà Nẵng">
    <link rel="canonical" href="https://nhakhoatamsinh.com/">

    <!-- Open Graph / Thumbnail là ảnh Logo trang web khi gửi link qua Zalo, Facebook -->
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="Nha Khoa Tám Sinh - nhakhoatamsinh.com">
    <meta property="og:title" content="CÔNG TY TNHH MTV NHA KHOA TÁM SINH | Nha Khoa Thẩm Mỹ Uy Tín Đà Nẵng">
    <meta property="og:description" content="Chuyên Răng Sứ Thẩm Mỹ, Mặt Dán Sứ Veneer, Cấy Ghép Implant, Chỉnh Nha Trong Suốt & Nha Khoa Tổng Quát. Đ/c: 141 Tôn Đản, P. An Khê, TP Đà Nẵng - ĐT: 0702.303.779">
    <meta property="og:url" content="https://nhakhoatamsinh.com/">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=1hmqBa786-74rBZhhUF1fbwNfMvoYPkGx&sz=w800">
    <meta property="og:image:alt" content="Logo Công Ty TNHH MTV Nha Khoa Tám Sinh - nhakhoatamsinh.com">

    <!-- Google Fonts: Inter & Montserrat chuẩn giao diện Flatsome -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Montserrat:wght@600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome 6 Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        dental: {
                            50: '#f0f7ff',
                            100: '#e0effe',
                            200: '#bae0fd',
                            500: '#0284c7',
                            600: '#0369a1',
                            700: '#0a4d8c',
                            800: '#083b6b',
                            900: '#062c52',
                        },
                        gold: {
                            400: '#e6c65a',
                            500: '#d4af37',
                            600: '#b89423',
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        heading: ['Montserrat', 'sans-serif'],
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền và lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
            scroll-behavior: smooth;
        }

        /* Khung chuẩn Flatsome: Rộng 95% màn hình máy tính, căn giữa chuẩn xác */
        .flatsome-container {
            width: 95%;
            max-width: 95%;
            margin-left: auto;
            margin-right: auto;
        }
        @media (max-width: 767px) {
            .flatsome-container {
                width: 94%;
                max-width: 94%;
            }
        }

        /* Danh mục trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng, không bao giờ gãy dòng tên danh mục */
        .desktop-nav-list {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: center;
            gap: 4px 6px;
        }
        .desktop-nav-item {
            white-space: nowrap;
            font-size: 12.5px;
            font-weight: 600;
            padding: 6px 10px;
            border-radius: 6px;
            transition: all 0.2s ease;
            line-height: 1.2;
        }
        @media (min-width: 1280px) {
            .desktop-nav-list {
                flex-wrap: nowrap;
                gap: 4px;
            }
            .desktop-nav-item {
                font-size: 13px;
                padding: 7px 11px;
            }
        }

        /* Nút danh mục ở trang chủ: chữ nhỏ gọn, viết liền 1 hàng không xuống dòng */
        .cat-pill-btn {
            white-space: nowrap;
            font-size: 12.5px;
            font-weight: 600;
            padding: 7px 13px;
            border-radius: 9999px;
            transition: all 0.2s ease;
            cursor: pointer;
        }

        /* Tên sản phẩm hiển thị đầy đủ 100%, tự động xuống hàng mượt, không bị cắt chữ hay tràn ra ngoài */
        .product-title-full {
            white-space: normal;
            word-wrap: break-word;
            overflow-wrap: break-word;
            hyphens: none;
            line-height: 1.4;
        }

        /* 2 Banner tự trượt kích thước bằng nhau tuyệt đối */
        .banner-wrapper {
            position: relative;
            width: 100%;
            height: 390px;
            overflow: hidden;
            border-radius: 14px;
        }
        @media (min-width: 768px) {
            .banner-wrapper {
                height: 430px;
            }
        }
        @media (min-width: 1024px) {
            .banner-wrapper {
                height: 460px;
            }
        }
        .banner-slide {
            position: absolute;
            inset: 0;
            width: 100%;
            height: 100%;
            opacity: 0;
            visibility: hidden;
            transition: opacity 0.7s ease-in-out, visibility 0.7s ease-in-out;
        }
        .banner-slide.active {
            opacity: 1;
            visibility: visible;
            z-index: 10;
        }

        /* Hiệu ứng rung nhẹ cho nút liên hệ nổi */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(2, 132, 199, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 12px rgba(2, 132, 199, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(2, 132, 199, 0); }
        }
        .floating-pulse {
            animation: pulse-ring 2s infinite;
        }

        /* Ẩn thanh cuộn ngang cho thanh danh mục trên mobile */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800">

    <!-- =====================================================================
         FLATSOME HEADER WRAPPER (Gọn gàng, Logo nhỏ gọn, Menu chuẩn, Không để nút Gọi ngay trên Header)
    ====================================================================== -->
    <header id="header" class="sticky top-0 z-50 bg-white shadow-md border-b border-slate-100">
        <!-- Top Bar thông tin công ty -->
        <div class="bg-dental-800 text-white text-xs py-1.5">
            <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
                <div class="flex items-center gap-3 overflow-hidden">
                    <span class="font-semibold text-gold-400 truncate">
                        <i class="fa-solid fa-tooth mr-1"></i>CÔNG TY TNHH MTV NHA KHOA TÁM SINH
                    </span>
                    <span class="hidden md:inline-block text-slate-300">|</span>
                    <span class="hidden md:inline-block text-slate-100 truncate">
                        <i class="fa-solid fa-location-dot text-gold-400 mr-1"></i>141 Tôn Đản, Phường An Khê, TP Đà Nẵng
                    </span>
                </div>
                <div class="flex items-center gap-4 text-slate-100">
                    <span class="hidden sm:inline-block">
                        <i class="fa-regular fa-clock text-gold-400 mr-1"></i>07:30 - 19:30 (T2 - CN)
                    </span>
                    <a href="https://www.facebook.com/profile.php?id=100063581412960&locale=vi_VN" target="_blank" rel="noopener noreferrer" class="hover:text-gold-400 transition-colors">
                        <i class="fa-brands fa-facebook mr-1"></i>Fanpage
                    </a>
                    <a href="https://share.google/KWtzB88Rl7WvcFdCW" target="_blank" rel="noopener noreferrer" class="hover:text-gold-400 transition-colors">
                        <i class="fa-solid fa-map-location-dot mr-1"></i>Chỉ đường
                    </a>
                </div>
            </div>
        </div>

        <!-- Main Header: Logo nhỏ gọn + Danh mục viết liền trên 1 hàng chữ nhỏ gọn (Không có nút gọi ngay trên Header) -->
        <div class="flatsome-container py-2.5">
            <div class="flex items-center justify-between gap-3">
                <!-- Logo Nha Khoa Tám Sinh Thiết Kế Chuyên Nghiệp - Chỉnh Gọn Nhỏ Lại -->
                <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group focus:outline-none">
                    <div class="w-10 h-10 rounded-xl bg-gradient-to-br from-dental-700 via-dental-600 to-dental-500 flex items-center justify-center shadow-sm border border-gold-400/50 shrink-0">
                        <svg class="w-6 h-6 text-white" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <!-- Biểu tượng Răng Sứ Thẩm Mỹ + Ngôi Sao Tỏa Sáng Vàng Gold -->
                            <path d="M20 12C13.5 12 9 17.5 9 25C9 33.5 13.5 41 16.5 49.5C18 53.5 21.5 54 23.5 49.5C25.5 45 28 39 32 39C36 39 38.5 45 40.5 49.5C42.5 54 46 53.5 47.5 49.5C50.5 41 55 33.5 55 25C55 17.5 50.5 12 44 12C39 12 35.5 14.5 32 14.5C28.5 14.5 25 12 20 12Z" fill="white" stroke="#E6C65A" stroke-width="2.5"/>
                            <path d="M22 23C25 26 28.5 27.5 32 27.5C35.5 27.5 39 26 42 23" stroke="#0A4D8C" stroke-width="3" stroke-linecap="round"/>
                            <circle cx="46" cy="18" r="3" fill="#E6C65A"/>
                        </svg>
                    </div>
                    <div class="leading-tight">
                        <span class="block font-heading font-extrabold text-sm sm:text-base text-dental-800 tracking-tight">
                            NHA KHOA TÁM SINH
                        </span>
                        <span class="block text-[10.5px] font-semibold text-gold-600 tracking-wider">
                            nhakhoatamsinh.com
                        </span>
                    </div>
                </a>

                <!-- Menu Danh Mục Trên Máy Tính: Chữ nhỏ gọn, viết liền trên 1 hàng hoặc xuống hàng 2 nguyên cụm, không bao giờ gãy chữ -->
                <nav class="hidden lg:block flex-1">
                    <ul class="desktop-nav-list">
                        <li>
                            <a href="#trang-chu" class="desktop-nav-item bg-dental-700 text-white">Trang chủ</a>
                        </li>
                        <li>
                            <a href="#gioi-thieu" class="desktop-nav-item text-slate-700 hover:bg-dental-50 hover:text-dental-700">Về chúng tôi</a>
                        </li>
                        <li>
                            <a href="#danh-muc-dich-vu" onclick="filterProducts('rang-su')" class="desktop-nav-item text-slate-700 hover:bg-dental-50 hover:text-dental-700">Thẩm Mỹ Răng Sứ</a>
                        </li>
                        <li>
                            <a href="#danh-muc-dich-vu" onclick="filterProducts('veneer')" class="desktop-nav-item text-slate-700 hover:bg-dental-50 hover:text-dental-700">Mặt Dán Sứ Veneer</a>
                        </li>
                        <li>
                            <a href="#danh-muc-dich-vu" onclick="filterProducts('chinh-nha')" class="desktop-nav-item text-slate-700 hover:bg-dental-50 hover:text-dental-700">Chỉnh Nha</a>
                        </li>
                        <li>
                            <a href="#danh-muc-dich-vu" onclick="filterProducts('implant')" class="desktop-nav-item text-slate-700 hover:bg-dental-50 hover:text-dental-700">Cấy Ghép Implant</a>
                        </li>
                        <li>
                            <a href="#danh-muc-dich-vu" onclick="filterProducts('tong-quat')" class="desktop-nav-item text-slate-700 hover:bg-dental-50 hover:text-dental-700">Nha Tổng Quát</a>
                        </li>
                        <li>
                            <a href="#hinh-anh-thuc-te" class="desktop-nav-item text-slate-700 hover:bg-dental-50 hover:text-dental-700">Ảnh Thực Tế</a>
                        </li>
                        <li>
                            <a href="#tin-tuc" class="desktop-nav-item text-slate-700 hover:bg-dental-50 hover:text-dental-700">Tin tức</a>
                        </li>
                        <li>
                            <a href="#bao-gia-lien-he" class="desktop-nav-item text-dental-700 bg-dental-50 hover:bg-dental-100 border border-dental-200">Báo giá & Liên hệ</a>
                        </li>
                    </ul>
                </nav>

                <!-- Nút mở Menu trên Điện Thoại / Tablet (Không để nút gọi ngay tránh tràn viền) -->
                <button id="mobile-menu-btn" onclick="toggleMobileMenu()" aria-label="Mở danh mục" class="lg:hidden inline-flex items-center gap-1.5 px-3 py-2 rounded-lg bg-dental-50 text-dental-800 border border-dental-200 font-semibold text-xs hover:bg-dental-100 transition">
                    <i class="fa-solid fa-bars text-sm"></i>
                    <span>Danh mục</span>
                </button>
            </div>

            <!-- Thanh Danh Mục Nhanh Trên Điện Thoại (Thiết kế gọn đẹp, vuốt mượt, không tràn viền) -->
            <div class="lg:hidden mt-2 pt-2 border-t border-slate-100 flex items-center gap-1.5 overflow-x-auto no-scrollbar">
                <a href="#danh-muc-dich-vu" onclick="filterProducts('all')" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded-md bg-dental-700 text-white">Tất cả dịch vụ</a>
                <a href="#danh-muc-dich-vu" onclick="filterProducts('rang-su')" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded-md bg-slate-100 text-slate-700">Thẩm Mỹ Răng Sứ</a>
                <a href="#danh-muc-dich-vu" onclick="filterProducts('veneer')" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded-md bg-slate-100 text-slate-700">Dán Sứ Veneer</a>
                <a href="#danh-muc-dich-vu" onclick="filterProducts('chinh-nha')" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded-md bg-slate-100 text-slate-700">Chỉnh Nha</a>
                <a href="#danh-muc-dich-vu" onclick="filterProducts('implant')" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded-md bg-slate-100 text-slate-700">Cấy Ghép Implant</a>
                <a href="#danh-muc-dich-vu" onclick="filterProducts('tong-quat')" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded-md bg-slate-100 text-slate-700">Nha Tổng Quát</a>
                <a href="#bao-gia-lien-he" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded-md bg-amber-50 text-amber-800 border border-amber-200">Nhận báo giá</a>
            </div>
        </div>

        <!-- Hộp Menu Mở Rộng Cho Điện Thoại -->
        <div id="mobile-drawer" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
            <div class="flatsome-container py-3 grid grid-cols-2 gap-2 text-xs font-semibold">
                <a href="#trang-chu" onclick="toggleMobileMenu()" class="p-2.5 rounded-lg bg-slate-50 text-dental-800 flex items-center gap-2">
                    <i class="fa-solid fa-house text-dental-600"></i>Trang chủ
                </a>
                <a href="#gioi-thieu" onclick="toggleMobileMenu()" class="p-2.5 rounded-lg bg-slate-50 text-dental-800 flex items-center gap-2">
                    <i class="fa-solid fa-building text-dental-600"></i>Về chúng tôi
                </a>
                <a href="#danh-muc-dich-vu" onclick="filterProducts('rang-su'); toggleMobileMenu()" class="p-2.5 rounded-lg bg-slate-50 text-dental-800 flex items-center gap-2">
                    <i class="fa-solid fa-tooth text-dental-600"></i>Thẩm Mỹ Răng Sứ
                </a>
                <a href="#danh-muc-dich-vu" onclick="filterProducts('veneer'); toggleMobileMenu()" class="p-2.5 rounded-lg bg-slate-50 text-dental-800 flex items-center gap-2">
                    <i class="fa-solid fa-wand-magic-sparkles text-dental-600"></i>Mặt Dán Sứ Veneer
                </a>
                <a href="#danh-muc-dich-vu" onclick="filterProducts('chinh-nha'); toggleMobileMenu()" class="p-2.5 rounded-lg bg-slate-50 text-dental-800 flex items-center gap-2">
                    <i class="fa-solid fa-face-smile text-dental-600"></i>Chỉnh Nha
                </a>
                <a href="#danh-muc-dich-vu" onclick="filterProducts('implant'); toggleMobileMenu()" class="p-2.5 rounded-lg bg-slate-50 text-dental-800 flex items-center gap-2">
                    <i class="fa-solid fa-screwdriver-wrench text-dental-600"></i>Cấy Ghép Implant
                </a>
                <a href="#danh-muc-dich-vu" onclick="filterProducts('tong-quat'); toggleMobileMenu()" class="p-2.5 rounded-lg bg-slate-50 text-dental-800 flex items-center gap-2">
                    <i class="fa-solid fa-user-doctor text-dental-600"></i>Nha Tổng Quát
                </a>
                <a href="#bao-gia-lien-he" onclick="toggleMobileMenu()" class="p-2.5 rounded-lg bg-dental-700 text-white flex items-center gap-2">
                    <i class="fa-solid fa-file-signature text-gold-400"></i>Báo giá & Liên hệ
                </a>
            </div>
        </div>
    </header>

    <!-- =====================================================================
         SECTION 1: FLATSOME SLIDER - 2 BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU
         Chữ và hình ảnh nằm gọn bên trong banner, cách xa viền banner, không mất chữ trên cả điện thoại và máy tính
    ====================================================================== -->
    <section id="trang-chu" class="py-3 md:py-5">
        <div class="flatsome-container">
            <div class="banner-wrapper shadow-lg border border-slate-200 bg-dental-900">

                <!-- SLIDE 1: THẨM MỸ RĂNG SỨ & DÁN SỨ VENEER CHUẨN QUỐC TẾ -->
                <div class="banner-slide active" id="slide-0">
                    <div class="w-full h-full bg-gradient-to-r from-dental-900 via-dental-800 to-dental-700 flex items-center">
                        <!-- Khoảng đệm rộng rãi cách xa viền banner (px-7 sm:px-12 md:px-16 lg:px-20) -->
                        <div class="w-full px-7 sm:px-12 md:px-16 lg:px-20 py-6 grid grid-cols-1 md:grid-cols-12 gap-5 items-center">
                            <!-- Khối chữ trong Banner 1 -->
                            <div class="md:col-span-7 text-white space-y-2.5 sm:space-y-3.5 text-left">
                                <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-white/15 border border-gold-400/50 text-gold-400 text-[11px] sm:text-xs font-semibold">
                                    <i class="fa-solid fa-certificate"></i>
                                    <span>CÔNG TY TNHH MTV NHA KHOA TÁM SINH</span>
                                </div>
                                <h1 class="font-heading font-extrabold text-lg sm:text-2xl lg:text-3xl xl:text-4xl leading-snug text-white">
                                    KIẾN TẠO NỤ CƯỜI HOÀN MỸ <br class="hidden sm:inline">
                                    <span class="text-gold-400">RĂNG SỨ & VENEER CAO CẤP</span>
                                </h1>
                                <p class="text-xs sm:text-sm lg:text-base text-slate-100 leading-relaxed max-w-xl">
                                    Chuyên Răng sứ toàn phần Countess Moonstone, Cercon HT, Lava 3M & Mặt dán sứ Veneer Emax siêu mỏng. Bảo tồn răng thật tối đa, vô trùng chuẩn quốc tế tại 141 Tôn Đản, Đà Nẵng.
                                </p>
                                <div class="pt-1 flex flex-wrap items-center gap-2.5">
                                    <a href="#bao-gia-lien-he" class="px-4 py-2 sm:px-5 sm:py-2.5 rounded-lg bg-gold-500 hover:bg-gold-400 text-slate-900 font-bold text-xs sm:text-sm shadow transition">
                                        <i class="fa-solid fa-calendar-check mr-1.5"></i>Đặt Lịch & Nhận Báo Giá
                                    </a>
                                    <a href="#danh-muc-dich-vu" class="px-4 py-2 sm:px-5 sm:py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white font-semibold text-xs sm:text-sm border border-white/30 transition">
                                        Xem Danh Mục Dịch Vụ
                                    </a>
                                </div>
                            </div>
                            <!-- Khối ảnh nằm gọn trong Banner 1 -->
                            <div class="hidden md:flex md:col-span-5 justify-center items-center">
                                <div class="relative w-full max-w-[330px] h-[250px] lg:h-[290px] rounded-2xl overflow-hidden border-2 border-gold-400/70 shadow-2xl bg-dental-800 p-2">
                                    <img src="https://drive.google.com/thumbnail?id=1hmqBa786-74rBZhhUF1fbwNfMvoYPkGx&sz=w1000"
                                         onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1hmqBa786-74rBZhhUF1fbwNfMvoYPkGx=w1000';"
                                         alt="Nha Khoa Tám Sinh Đà Nẵng - Thẩm Mỹ Răng Sứ"
                                         class="w-full h-full object-cover rounded-xl">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- SLIDE 2: CHỈNH NHA NIỀNG RĂNG & CẤY GHÉP IMPLANT CÔNG NGHỆ CAO -->
                <div class="banner-slide" id="slide-1">
                    <div class="w-full h-full bg-gradient-to-r from-slate-900 via-dental-800 to-dental-600 flex items-center">
                        <!-- Khoảng đệm rộng rãi cách xa viền banner (px-7 sm:px-12 md:px-16 lg:px-20) -->
                        <div class="w-full px-7 sm:px-12 md:px-16 lg:px-20 py-6 grid grid-cols-1 md:grid-cols-12 gap-5 items-center">
                            <!-- Khối chữ trong Banner 2 -->
                            <div class="md:col-span-7 text-white space-y-2.5 sm:space-y-3.5 text-left">
                                <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-white/15 border border-gold-400/50 text-gold-400 text-[11px] sm:text-xs font-semibold">
                                    <i class="fa-solid fa-shield-heart"></i>
                                    <span>ĐỊA CHỈ UY TÍN: 141 TÔN ĐẢN, P. AN KHÊ, ĐÀ NẴNG</span>
                                </div>
                                <h2 class="font-heading font-extrabold text-lg sm:text-2xl lg:text-3xl xl:text-4xl leading-snug text-white">
                                    CẤY GHÉP IMPLANT 4.0 & <br class="hidden sm:inline">
                                    <span class="text-gold-400">CHỈNH NHA KỸ THUẬT CAO</span>
                                </h2>
                                <p class="text-xs sm:text-sm lg:text-base text-slate-100 leading-relaxed max-w-xl">
                                    Phục hình răng mất toàn diện với trụ Implant chính hãng và Chỉnh nha khay trong suốt Invisalign, Mắc cài sứ thẩm mỹ. Thăm khám tận tâm – Chi phí minh bạch – Bảo hành dài hạn.
                                </p>
                                <div class="pt-1 flex flex-wrap items-center gap-2.5">
                                    <a href="tel:0702303779" class="px-4 py-2 sm:px-5 sm:py-2.5 rounded-lg bg-gold-500 hover:bg-gold-400 text-slate-900 font-bold text-xs sm:text-sm shadow transition">
                                        <i class="fa-solid fa-phone-volume mr-1.5"></i>Tư Vấn: 0702.303.779
                                    </a>
                                    <a href="#hinh-anh-thuc-te" class="px-4 py-2 sm:px-5 sm:py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white font-semibold text-xs sm:text-sm border border-white/30 transition">
                                        Xem Hình Ảnh Thực Tế
                                    </a>
                                </div>
                            </div>
                            <!-- Khối ảnh nằm gọn trong Banner 2 -->
                            <div class="hidden md:flex md:col-span-5 justify-center items-center">
                                <div class="relative w-full max-w-[330px] h-[250px] lg:h-[290px] rounded-2xl overflow-hidden border-2 border-gold-400/70 shadow-2xl bg-dental-800 p-2">
                                    <img src="https://drive.google.com/thumbnail?id=1Yw6U6O--bo9hTqynHl6e9jhKyMaqwG93&sz=w1000"
                                         onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1Yw6U6O--bo9hTqynHl6e9jhKyMaqwG93=w1000';"
                                         alt="Phòng Khám Nha Khoa Tám Sinh 141 Tôn Đản Đà Nẵng"
                                         class="w-full h-full object-cover rounded-xl">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng trái/phải nằm gọn bên trong mép banner -->
                <button onclick="prevBanner()" aria-label="Banner trước" class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button onclick="nextBanner()" aria-label="Banner tiếp" class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>

                <!-- Chấm chuyển slide -->
                <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button onclick="goToBanner(0)" id="dot-0" aria-label="Slide 1" class="w-6 h-2 rounded-full bg-gold-400 transition-all"></button>
                    <button onclick="goToBanner(1)" id="dot-1" aria-label="Slide 2" class="w-2.5 h-2 rounded-full bg-white/50 transition-all"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 2: CÂY DANH MỤC DỊCH VỤ & SẢN PHẨM NHA KHOA (Theo chuẩn nhakhoatintam.com)
         Thiết kế đơn giản, chữ danh mục ở trang chủ nhỏ gọn, dễ dàng dựng lại trên UX Builder Flatsome
    ====================================================================== -->
    <section id="danh-muc-dich-vu" class="py-6 md:py-10 bg-white border-y border-slate-200/80">
        <div class="flatsome-container">
            <!-- Tiêu đề Section chuẩn Flatsome -->
            <div class="text-center max-w-3xl mx-auto mb-6">
                <span class="text-xs font-bold uppercase tracking-wider text-dental-600 block mb-1">
                    NHA KHOA TÁM SINH CUNG CẤP
                </span>
                <h2 class="font-heading font-extrabold text-xl sm:text-2xl md:text-3xl text-dental-800">
                    DANH MỤC SẢN PHẨM & DỊCH VỤ KỸ THUẬT CAO
                </h2>
                <div class="w-16 h-1 bg-gold-500 mx-auto mt-2.5 rounded-full"></div>
            </div>

            <!-- Khung Danh Mục Phân Nhóm Rõ Ràng (Trên máy tính & điện thoại gọn đẹp, chữ nhỏ gọn không gãy dòng) -->
            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2.5 mb-6">
                <button onclick="filterProducts('all')" id="cat-btn-all" class="cat-filter-card p-3 rounded-xl border border-dental-600 bg-dental-700 text-white text-center shadow-sm transition hover:shadow">
                    <i class="fa-solid fa-border-all text-base mb-1 block text-gold-400"></i>
                    <span class="block text-xs font-bold whitespace-nowrap">Tất Cả Dịch Vụ</span>
                    <span class="block text-[10.5px] opacity-80">18 sản phẩm & dịch vụ</span>
                </button>
                <button onclick="filterProducts('rang-su')" id="cat-btn-rang-su" class="cat-filter-card p-3 rounded-xl border border-slate-200 bg-slate-50 text-slate-800 text-center transition hover:border-dental-500 hover:bg-dental-50">
                    <i class="fa-solid fa-tooth text-base mb-1 block text-dental-600"></i>
                    <span class="block text-xs font-bold whitespace-nowrap">Răng Sứ Toàn Phần</span>
                    <span class="block text-[10.5px] text-slate-500">Countess, Cercon, Lava</span>
                </button>
                <button onclick="filterProducts('veneer')" id="cat-btn-veneer" class="cat-filter-card p-3 rounded-xl border border-slate-200 bg-slate-50 text-slate-800 text-center transition hover:border-dental-500 hover:bg-dental-50">
                    <i class="fa-solid fa-wand-magic-sparkles text-base mb-1 block text-dental-600"></i>
                    <span class="block text-xs font-bold whitespace-nowrap">Mặt Dán Sứ Veneer</span>
                    <span class="block text-[10.5px] text-slate-500">EMax, 3D Max, Ultrathin</span>
                </button>
                <button onclick="filterProducts('chinh-nha')" id="cat-btn-chinh-nha" class="cat-filter-card p-3 rounded-xl border border-slate-200 bg-slate-50 text-slate-800 text-center transition hover:border-dental-500 hover:bg-dental-50">
                    <i class="fa-solid fa-face-smile-beam text-base mb-1 block text-dental-600"></i>
                    <span class="block text-xs font-bold whitespace-nowrap">Chỉnh Nha Niềng Răng</span>
                    <span class="block text-[10.5px] text-slate-500">Invisalign & Mắc cài</span>
                </button>
                <button onclick="filterProducts('implant')" id="cat-btn-implant" class="cat-filter-card p-3 rounded-xl border border-slate-200 bg-slate-50 text-slate-800 text-center transition hover:border-dental-500 hover:bg-dental-50">
                    <i class="fa-solid fa-screwdriver-wrench text-base mb-1 block text-dental-600"></i>
                    <span class="block text-xs font-bold whitespace-nowrap">Cấy Ghép Implant</span>
                    <span class="block text-[10.5px] text-slate-500">Định vị 4.0 & Trụ Quốc tế</span>
                </button>
                <button onclick="filterProducts('tong-quat')" id="cat-btn-tong-quat" class="cat-filter-card p-3 rounded-xl border border-slate-200 bg-slate-50 text-slate-800 text-center transition hover:border-dental-500 hover:bg-dental-50">
                    <i class="fa-solid fa-kit-medical text-base mb-1 block text-dental-600"></i>
                    <span class="block text-xs font-bold whitespace-nowrap">Nha Khoa Tổng Quát</span>
                    <span class="block text-[10.5px] text-slate-500">Tiểu phẫu, Nội nha, Tẩy trắng</span>
                </button>
            </div>

            <!-- LƯỚI SẢN PHẨM / DỊCH VỤ:
                 - Điện thoại chia đúng 2 cột (grid-cols-2), Máy tính chia 4 cột (lg:grid-cols-4)
                 - Tên sản phẩm hiển thị đầy đủ 100%, không bị cắt chữ hay tràn viền
                 - Hoàn toàn KHÔNG ĐỂ NHÃN DÁN (sticker/badge) ở trang chủ theo đúng yêu cầu -->
            <div id="product-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Danh sách sản phẩm được render tự động từ dữ liệu chuẩn bên dưới -->
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 3: GIỚI THIỆU VỀ NHA KHOA TÁM SINH & TIÊU CHUẨN VÔ TRÙNG + 6 ẢNH THỰC TẾ GOOGLE DRIVE
    ====================================================================== -->
    <section id="gioi-thieu" class="py-8 md:py-12 bg-slate-50">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-8 items-center">
                <!-- Cột Nội dung Giới thiệu -->
                <div class="lg:col-span-6 space-y-4">
                    <span class="text-xs font-bold uppercase tracking-wider text-dental-600 block">
                        GIỚI THIỆU VỀ NHA KHOA THẨM MỸ
                    </span>
                    <h2 class="font-heading font-extrabold text-xl sm:text-2xl md:text-3xl text-dental-800 leading-snug">
                        CÔNG TY TNHH MỘT THÀNH VIÊN NHA KHOA TÁM SINH
                    </h2>
                    <p class="text-sm text-slate-700 leading-relaxed">
                        <strong>Nha Khoa Tám Sinh</strong> (<span class="text-dental-700 font-semibold">nhakhoatamsinh.com</span>) tọa lạc tại <strong>141 Tôn Đản, Phường An Khê, TP Đà Nẵng</strong> luôn đặt chữ <strong>TÂM</strong> và đạo đức nghề nghiệp lên hàng đầu trong mọi hoạt động thăm khám, điều trị và thẩm mỹ nha khoa.
                    </p>
                    <p class="text-sm text-slate-700 leading-relaxed">
                        Phòng điều trị tại Nha Khoa Tám Sinh được trang bị hệ thống ghế nha khoa hiện đại, công nghệ chẩn đoán hình ảnh và quy trình khử khuẩn – vô trùng khép kín chuẩn quốc tế, ngăn ngừa lây nhiễm chéo tuyệt đối và mang lại sự an tâm trọn vẹn cho khách hàng.
                    </p>

                    <!-- 3 Cam kết vô trùng chuẩn web mẫu -->
                    <div class="space-y-2.5 pt-1">
                        <div class="flex items-start gap-3 p-3 rounded-xl bg-white border border-slate-200 shadow-sm">
                            <i class="fa-solid fa-circle-check text-dental-600 mt-0.5"></i>
                            <p class="text-xs sm:text-sm text-slate-700">
                                <strong>Vô trùng phòng điều trị:</strong> Trước khi đón khách, ghế nha khoa, thiết bị và mọi vị trí trong phòng đều được khử trùng nghiêm ngặt.
                            </p>
                        </div>
                        <div class="flex items-start gap-3 p-3 rounded-xl bg-white border border-slate-200 shadow-sm">
                            <i class="fa-solid fa-circle-check text-dental-600 mt-0.5"></i>
                            <p class="text-xs sm:text-sm text-slate-700">
                                <strong>Bộ dụng cụ riêng biệt:</strong> Mở và sử dụng bộ dụng cụ vô trùng riêng cho từng khách hàng ngay trước sự quan sát của khách hàng.
                            </p>
                        </div>
                        <div class="flex items-start gap-3 p-3 rounded-xl bg-white border border-slate-200 shadow-sm">
                            <i class="fa-solid fa-circle-check text-dental-600 mt-0.5"></i>
                            <p class="text-xs sm:text-sm text-slate-700">
                                <strong>Vật liệu nha khoa chính hãng:</strong> Phôi sứ Đức, Mỹ, Thụy Sĩ và trụ Implant có thẻ bảo hành chính hãng minh bạch.
                            </p>
                        </div>
                    </div>

                    <!-- Thống kê những con số biết nói -->
                    <div class="grid grid-cols-2 sm:grid-cols-4 gap-2.5 pt-2">
                        <div class="bg-dental-800 text-white p-3 rounded-xl text-center">
                            <span class="block font-heading font-extrabold text-lg sm:text-xl text-gold-400">1000+</span>
                            <span class="text-[11px] text-slate-200">Khách hàng / Năm</span>
                        </div>
                        <div class="bg-dental-800 text-white p-3 rounded-xl text-center">
                            <span class="block font-heading font-extrabold text-lg sm:text-xl text-gold-400">100%</span>
                            <span class="text-[11px] text-slate-200">Vật liệu chính hãng</span>
                        </div>
                        <div class="bg-dental-800 text-white p-3 rounded-xl text-center">
                            <span class="block font-heading font-extrabold text-lg sm:text-xl text-gold-400">4.9/5★</span>
                            <span class="text-[11px] text-slate-200">Đánh giá Google Map</span>
                        </div>
                        <div class="bg-dental-800 text-white p-3 rounded-xl text-center">
                            <span class="block font-heading font-extrabold text-lg sm:text-xl text-gold-400">700+</span>
                            <span class="text-[11px] text-slate-200">Nụ cười hoàn mỹ</span>
                        </div>
                    </div>
                </div>

                <!-- Cột Bộ Sưu Tập 6 Hình Ảnh Thực Tế Từ Google Drive -->
                <div id="hinh-anh-thuc-te" class="lg:col-span-6">
                    <div class="bg-white p-4 sm:p-5 rounded-2xl border border-slate-200 shadow-sm">
                        <div class="flex items-center justify-between mb-3">
                            <div>
                                <h3 class="font-heading font-bold text-sm sm:text-base text-dental-800">
                                    HÌNH ẢNH THỰC TẾ TẠI NHA KHOA TÁM SINH
                                </h3>
                                <p class="text-xs text-slate-500">Không gian phòng khám, trang thiết bị & điều trị thực tế tại 141 Tôn Đản</p>
                            </div>
                        </div>

                        <!-- Chia 2 cột trên điện thoại và 3 cột trên máy tính cho 6 ảnh Google Drive -->
                        <div class="grid grid-cols-2 sm:grid-cols-3 gap-2.5">
                            <!-- Ảnh thực tế 1 -->
                            <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-100">
                                <div class="aspect-[4/3] overflow-hidden">
                                    <img src="https://drive.google.com/thumbnail?id=1hmqBa786-74rBZhhUF1fbwNfMvoYPkGx&sz=w1000"
                                         onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1hmqBa786-74rBZhhUF1fbwNfMvoYPkGx=w1000';"
                                         alt="Hình ảnh thực tế Nha Khoa Tám Sinh 1"
                                         class="w-full h-full object-cover hover:scale-105 transition duration-300">
                                </div>
                                <div class="p-2 text-center bg-white">
                                    <p class="text-[11px] font-semibold text-slate-700 product-title-full">Cơ sở Nha Khoa Tám Sinh</p>
                                </div>
                            </div>

                            <!-- Ảnh thực tế 2 -->
                            <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-100">
                                <div class="aspect-[4/3] overflow-hidden">
                                    <img src="https://drive.google.com/thumbnail?id=1Yw6U6O--bo9hTqynHl6e9jhKyMaqwG93&sz=w1000"
                                         onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1Yw6U6O--bo9hTqynHl6e9jhKyMaqwG93=w1000';"
                                         alt="Hình ảnh thực tế Nha Khoa Tám Sinh 2"
                                         class="w-full h-full object-cover hover:scale-105 transition duration-300">
                                </div>
                                <div class="p-2 text-center bg-white">
                                    <p class="text-[11px] font-semibold text-slate-700 product-title-full">Phòng điều trị vô trùng</p>
                                </div>
                            </div>

                            <!-- Ảnh thực tế 3 -->
                            <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-100">
                                <div class="aspect-[4/3] overflow-hidden">
                                    <img src="https://drive.google.com/thumbnail?id=1-i7406ON_fiq7mKj2h2-FisAIPGKeVzX&sz=w1000"
                                         onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1-i7406ON_fiq7mKj2h2-FisAIPGKeVzX=w1000';"
                                         alt="Hình ảnh thực tế Nha Khoa Tám Sinh 3"
                                         class="w-full h-full object-cover hover:scale-105 transition duration-300">
                                </div>
                                <div class="p-2 text-center bg-white">
                                    <p class="text-[11px] font-semibold text-slate-700 product-title-full">Thẩm mỹ răng sứ cao cấp</p>
                                </div>
                            </div>

                            <!-- Ảnh thực tế 4 -->
                            <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-100">
                                <div class="aspect-[4/3] overflow-hidden">
                                    <img src="https://drive.google.com/thumbnail?id=1FKZlEMIt_pKmoYREznxpBKXSmVeYxG3i&sz=w1000"
                                         onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1FKZlEMIt_pKmoYREznxpBKXSmVeYxG3i=w1000';"
                                         alt="Hình ảnh thực tế Nha Khoa Tám Sinh 4"
                                         class="w-full h-full object-cover hover:scale-105 transition duration-300">
                                </div>
                                <div class="p-2 text-center bg-white">
                                    <p class="text-[11px] font-semibold text-slate-700 product-title-full">Trang thiết bị nha khoa</p>
                                </div>
                            </div>

                            <!-- Ảnh thực tế 5 -->
                            <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-100">
                                <div class="aspect-[4/3] overflow-hidden">
                                    <img src="https://drive.google.com/thumbnail?id=1WXNRxBXsn1_mxSbMQFJ6FSZJL8v3ML_V&sz=w1000"
                                         onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1WXNRxBXsn1_mxSbMQFJ6FSZJL8v3ML_V=w1000';"
                                         alt="Hình ảnh thực tế Nha Khoa Tám Sinh 5"
                                         class="w-full h-full object-cover hover:scale-105 transition duration-300">
                                </div>
                                <div class="p-2 text-center bg-white">
                                    <p class="text-[11px] font-semibold text-slate-700 product-title-full">Khách hàng thăm khám</p>
                                </div>
                            </div>

                            <!-- Ảnh thực tế 6 -->
                            <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-100">
                                <div class="aspect-[4/3] overflow-hidden">
                                    <img src="https://drive.google.com/thumbnail?id=1Z7PJvc1zvTxXAm-evcvGfxrKXEdCY5bW&sz=w1000"
                                         onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1Z7PJvc1zvTxXAm-evcvGfxrKXEdCY5bW=w1000';"
                                         alt="Hình ảnh thực tế Nha Khoa Tám Sinh 6"
                                         class="w-full h-full object-cover hover:scale-105 transition duration-300">
                                </div>
                                <div class="p-2 text-center bg-white">
                                    <p class="text-[11px] font-semibold text-slate-700 product-title-full">Chăm sóc nụ cười toàn diện</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 4: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ + FANPAGE FACEBOOK + BẢN ĐỒ GOOGLE MAP TRANG CHỦ
    ====================================================================== -->
    <section id="bao-gia-lien-he" class="py-8 md:py-12 bg-white border-t border-slate-200">
        <div class="flatsome-container">
            <div class="text-center max-w-3xl mx-auto mb-7">
                <span class="text-xs font-bold uppercase tracking-wider text-dental-600 block mb-1">
                    KẾT NỐI TRỰC TIẾP VỚI NHA KHOA TÁM SINH
                </span>
                <h2 class="font-heading font-extrabold text-xl sm:text-2xl md:text-3xl text-dental-800">
                    ĐĂNG KÝ NHẬN BÁO GIÁ, FANPAGE & BẢN ĐỒ ĐƯỜNG ĐI
                </h2>
                <div class="w-16 h-1 bg-gold-500 mx-auto mt-2.5 rounded-full"></div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6">
                <!-- Cột 1 (5/12): FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ -->
                <div class="lg:col-span-5 bg-slate-50 p-5 sm:p-6 rounded-2xl border border-slate-200 shadow-sm">
                    <div class="flex items-center gap-3 mb-4">
                        <div class="w-10 h-10 rounded-xl bg-dental-700 text-gold-400 flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-file-invoice-dollar text-lg"></i>
                        </div>
                        <div>
                            <h3 class="font-heading font-bold text-base sm:text-lg text-dental-800">
                                FORM YÊU CẦU & NHẬN BÁO GIÁ
                            </h3>
                            <p class="text-xs text-slate-500">Bác sĩ chuyên khoa phản hồi báo giá chi tiết sau 5 phút</p>
                        </div>
                    </div>

                    <form id="quote-form" onsubmit="submitQuoteForm(event)" class="space-y-3.5">
                        <div>
                            <label class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên khách hàng *</label>
                            <input type="text" id="cust-name" required placeholder="Nhập họ và tên của bạn..."
                                   class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-dental-600 bg-white">
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo nhận báo giá *</label>
                            <input type="tel" id="cust-phone" required placeholder="Ví dụ: 0702303779"
                                   class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-dental-600 bg-white">
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-slate-700 mb-1">Danh mục dịch vụ cần báo giá *</label>
                            <select id="cust-service" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-dental-600 bg-white">
                                <option value="Thẩm Mỹ Răng Sứ Toàn Phần Cao Cấp">Thẩm Mỹ Răng Sứ Toàn Phần Cao Cấp</option>
                                <option value="Mặt Dán Sứ Veneer Laminate">Mặt Dán Sứ Veneer Laminate (Emax, 3D Max, Ultrathin)</option>
                                <option value="Chỉnh Nha Trong Suốt Invisalign">Chỉnh Nha Trong Suốt Invisalign</option>
                                <option value="Chỉnh Nha Mắc Cài Sứ / Kim Loại">Chỉnh Nha Mắc Cài Sứ / Kim Loại</option>
                                <option value="Cấy Ghép Implant Định Vị 4.0">Cấy Ghép Implant Định Vị 4.0</option>
                                <option value="Nha Khoa Tổng Quát (Trám, Tẩy trắng, Nhổ răng, Nội nha)">Nha Khoa Tổng Quát (Trám, Tẩy trắng, Nhổ răng, Nội nha)</option>
                            </select>
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-slate-700 mb-1">Tình trạng răng hoặc yêu cầu cụ thể</label>
                            <textarea id="cust-note" rows="3" placeholder="Mô tả số lượng răng cần làm hoặc thời gian bạn muốn đặt lịch hẹn..."
                                      class="w-full px-3.5 py-2 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-dental-600 bg-white"></textarea>
                        </div>
                        <button type="submit" class="w-full py-3 rounded-xl bg-dental-700 hover:bg-dental-800 text-white font-bold text-sm shadow transition flex items-center justify-center gap-2">
                            <i class="fa-solid fa-paper-plane text-gold-400"></i>
                            <span>GỬI YÊU CẦU TƯ VẤN & BÁO GIÁ NGAY</span>
                        </button>
                    </form>

                    <!-- Hộp thông báo gửi thành công -->
                    <div id="quote-success" class="hidden mt-3 p-3.5 rounded-xl bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs leading-relaxed"></div>
                </div>

                <!-- Cột 2 (7/12): ĐƯA FANPAGE FACEBOOK & GOOGLE MAP RA NGOÀI TRANG CHỦ -->
                <div class="lg:col-span-7 grid grid-cols-1 md:grid-cols-2 gap-5">

                    <!-- Khối Fanpage Facebook Ngoài Trang Chủ -->
                    <div class="bg-slate-50 p-4 sm:p-5 rounded-2xl border border-slate-200 shadow-sm flex flex-col justify-between">
                        <div>
                            <div class="flex items-center justify-between mb-3">
                                <h3 class="font-heading font-bold text-sm sm:text-base text-dental-800 flex items-center gap-2">
                                    <i class="fa-brands fa-facebook text-blue-600 text-lg"></i>
                                    <span>FANPAGE CHÍNH THỨC</span>
                                </h3>
                                <span class="text-[11px] font-semibold text-blue-600 bg-blue-50 px-2 py-0.5 rounded">Đang hoạt động</span>
                            </div>

                            <!-- Thẻ nhận diện trực quan Fanpage + Iframe Facebook Plugin -->
                            <div class="rounded-xl overflow-hidden border border-slate-200 bg-white mb-3">
                                <div class="relative h-28 bg-gradient-to-r from-dental-800 to-dental-600 overflow-hidden">
                                    <img src="https://drive.google.com/thumbnail?id=1hmqBa786-74rBZhhUF1fbwNfMvoYPkGx&sz=w1000"
                                         onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1hmqBa786-74rBZhhUF1fbwNfMvoYPkGx=w1000';"
                                         alt="Bìa Fanpage Nha Khoa Tám Sinh"
                                         class="w-full h-full object-cover opacity-55">
                                    <div class="absolute inset-0 bg-gradient-to-t from-black/75 via-black/30 to-transparent flex items-end p-3">
                                        <div class="flex items-center gap-2.5 text-white">
                                            <div class="w-11 h-11 rounded-full bg-dental-700 border-2 border-white flex items-center justify-center shrink-0 font-bold text-gold-400">
                                                <i class="fa-solid fa-tooth text-lg"></i>
                                            </div>
                                            <div>
                                                <p class="font-bold text-xs sm:text-sm leading-tight">Nha Khoa Tám Sinh Đà Nẵng</p>
                                                <p class="text-[11px] text-slate-200">141 Tôn Đản, P. An Khê • 0702.303.779</p>
                                            </div>
                                        </div>
                                    </div>
                                </div>

                                <!-- Nhúng Facebook Page Plugin chuẩn -->
                                <div class="p-2 bg-white flex justify-center overflow-hidden">
                                    <iframe
                                        title="Fanpage Nha Khoa Tám Sinh"
                                        src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D100063581412960&tabs=timeline&width=320&height=180&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true"
                                        width="320" height="180" style="border:none;overflow:hidden;max-width:100%;" scrolling="no" frameborder="0" allowfullscreen="true" allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                                    </iframe>
                                </div>
                            </div>
                        </div>

                        <a href="https://www.facebook.com/profile.php?id=100063581412960&locale=vi_VN" target="_blank" rel="noopener noreferrer"
                           class="w-full py-2.5 px-4 rounded-xl bg-blue-600 hover:bg-blue-700 text-white font-bold text-xs sm:text-sm text-center transition flex items-center justify-center gap-2">
                            <i class="fa-brands fa-facebook-messenger"></i>
                            <span>Truy Cập & Nhắn Tin Fanpage</span>
                        </a>
                    </div>

                    <!-- Khối Bản Đồ Google Map Ngoài Trang Chủ -->
                    <div class="bg-slate-50 p-4 sm:p-5 rounded-2xl border border-slate-200 shadow-sm flex flex-col justify-between">
                        <div>
                            <div class="flex items-center justify-between mb-3">
                                <h3 class="font-heading font-bold text-sm sm:text-base text-dental-800 flex items-center gap-2">
                                    <i class="fa-solid fa-map-location-dot text-red-600 text-lg"></i>
                                    <span>BẢN ĐỒ GOOGLE MAPS</span>
                                </h3>
                                <span class="text-[11px] font-semibold text-amber-700 bg-amber-50 px-2 py-0.5 rounded">4.9★ (48 đánh giá)</span>
                            </div>

                            <p class="text-xs text-slate-600 mb-2.5">
                                <i class="fa-solid fa-location-dot text-red-500 mr-1"></i>
                                <strong>Địa chỉ:</strong> 141 Tôn Đản, Phường An Khê, TP Đà Nẵng
                            </p>

                            <!-- Bản đồ Google Maps trực tiếp ngoài trang chủ -->
                            <div class="rounded-xl overflow-hidden border border-slate-300 bg-slate-200 h-[245px] mb-3">
                                <iframe
                                    title="Bản đồ Nha Khoa Tám Sinh 141 Tôn Đản Đà Nẵng"
                                    src="https://maps.google.com/maps?q=141%20T%C3%B4n%20%C4%90%E1%BA%A3n,%20An%20Kh%C3%AA,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                                    width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade">
                                </iframe>
                            </div>
                        </div>

                        <a href="https://share.google/KWtzB88Rl7WvcFdCW" target="_blank" rel="noopener noreferrer"
                           class="w-full py-2.5 px-4 rounded-xl bg-emerald-600 hover:bg-emerald-700 text-white font-bold text-xs sm:text-sm text-center transition flex items-center justify-center gap-2">
                            <i class="fa-solid fa-diamond-turn-right"></i>
                            <span>Mở Chỉ Đường Trên Google Maps</span>
                        </a>
                    </div>

                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 5: DANH MỤC BÀI VIẾT / TIN TỨC NHA KHOA TRANG CHỦ (Chuẩn nhakhoatintam.com)
    ====================================================================== -->
    <section id="tin-tuc" class="py-8 md:py-12 bg-slate-50 border-t border-slate-200">
        <div class="flatsome-container">
            <div class="text-center max-w-3xl mx-auto mb-7">
                <span class="text-xs font-bold uppercase tracking-wider text-dental-600 block mb-1">
                    THÔNG TIN & CẨM NANG CHĂM SÓC RĂNG MIỆNG
                </span>
                <h2 class="font-heading font-extrabold text-xl sm:text-2xl md:text-3xl text-dental-800">
                    TIN TỨC NHA KHOA MỚI NHẤT
                </h2>
                <div class="w-16 h-1 bg-gold-500 mx-auto mt-2.5 rounded-full"></div>
            </div>

            <!-- Chia 2 cột trên điện thoại và 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3.5 sm:gap-5">
                <!-- Bài viết 1 -->
                <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between">
                    <div>
                        <div class="aspect-[16/10] overflow-hidden bg-slate-100">
                            <img src="https://drive.google.com/thumbnail?id=1-i7406ON_fiq7mKj2h2-FisAIPGKeVzX&sz=w1000"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1-i7406ON_fiq7mKj2h2-FisAIPGKeVzX=w1000';"
                                 alt="Khi Nào Cần Ghép Xương Trong Trồng Răng Implant?"
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-3 sm:p-4">
                            <span class="text-[11px] text-dental-600 font-semibold block mb-1">Cấy Ghép Implant</span>
                            <h3 class="font-bold text-xs sm:text-sm text-slate-800 product-title-full mb-1.5">
                                Khi Nào Cần Ghép Xương Trong Trồng Răng Implant?
                            </h3>
                            <p class="text-[11.5px] text-slate-600 line-clamp-3">
                                Ghép xương răng implant là gì và khi nào cần ghép xương khi trồng răng implant? Nha Khoa Tám Sinh Đà Nẵng giải đáp chi tiết về kỹ thuật phục hồi tiêu xương hàm an toàn.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 sm:px-4 pb-3 pt-1">
                        <button onclick="openArticleModal(0)" class="text-xs font-bold text-dental-700 hover:text-dental-500 inline-flex items-center gap-1">
                            <span>Xem chi tiết</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </button>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between">
                    <div>
                        <div class="aspect-[16/10] overflow-hidden bg-slate-100">
                            <img src="https://drive.google.com/thumbnail?id=1FKZlEMIt_pKmoYREznxpBKXSmVeYxG3i&sz=w1000"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1FKZlEMIt_pKmoYREznxpBKXSmVeYxG3i=w1000';"
                                 alt="So Sánh Bọc Răng Sứ Toàn Phần Và Dán Sứ Veneer Siêu Mỏng"
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-3 sm:p-4">
                            <span class="text-[11px] text-dental-600 font-semibold block mb-1">Thẩm Mỹ Răng Sứ</span>
                            <h3 class="font-bold text-xs sm:text-sm text-slate-800 product-title-full mb-1.5">
                                So Sánh Bọc Răng Sứ Toàn Phần Và Dán Sứ Veneer Emax
                            </h3>
                            <p class="text-[11.5px] text-slate-600 line-clamp-3">
                                Tìm hiểu sự khác biệt giữa bọc răng sứ toàn phần Cercon HT, Lava 3M và mặt dán sứ Veneer siêu mỏng để lựa chọn giải pháp thẩm mỹ tối ưu cho nụ cười của bạn.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 sm:px-4 pb-3 pt-1">
                        <button onclick="openArticleModal(1)" class="text-xs font-bold text-dental-700 hover:text-dental-500 inline-flex items-center gap-1">
                            <span>Xem chi tiết</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </button>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between">
                    <div>
                        <div class="aspect-[16/10] overflow-hidden bg-slate-100">
                            <img src="https://drive.google.com/thumbnail?id=1WXNRxBXsn1_mxSbMQFJ6FSZJL8v3ML_V&sz=w1000"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1WXNRxBXsn1_mxSbMQFJ6FSZJL8v3ML_V=w1000';"
                                 alt="Giải Quyết Tật Nghiến Răng Khi Ngủ Và Bảo Vệ Men Răng"
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-3 sm:p-4">
                            <span class="text-[11px] text-dental-600 font-semibold block mb-1">Nha Khoa Tổng Quát</span>
                            <h3 class="font-bold text-xs sm:text-sm text-slate-800 product-title-full mb-1.5">
                                Giải Quyết Tật Nghiến Răng Khi Ngủ & Bảo Vệ Men Răng
                            </h3>
                            <p class="text-[11.5px] text-slate-600 line-clamp-3">
                                Bạn hoặc người thân đang đối mặt với tật nghiến răng gây mòn cổ răng và mỏi khớp thái dương hàm? Xem ngay hướng dẫn khắc phục hiệu quả từ bác sĩ chuyên khoa.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 sm:px-4 pb-3 pt-1">
                        <button onclick="openArticleModal(2)" class="text-xs font-bold text-dental-700 hover:text-dental-500 inline-flex items-center gap-1">
                            <span>Xem chi tiết</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </button>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between">
                    <div>
                        <div class="aspect-[16/10] overflow-hidden bg-slate-100">
                            <img src="https://drive.google.com/thumbnail?id=1Z7PJvc1zvTxXAm-evcvGfxrKXEdCY5bW&sz=w1000"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1Z7PJvc1zvTxXAm-evcvGfxrKXEdCY5bW=w1000';"
                                 alt="Ưu Điểm Của Chỉnh Nha Khay Trong Suốt Và Mắc Cài Sứ"
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-3 sm:p-4">
                            <span class="text-[11px] text-dental-600 font-semibold block mb-1">Chỉnh Nha Niềng Răng</span>
                            <h3 class="font-bold text-xs sm:text-sm text-slate-800 product-title-full mb-1.5">
                                Ưu Điểm Của Chỉnh Nha Trong Suốt Invisalign & Mắc Cài Sứ
                            </h3>
                            <p class="text-[11.5px] text-slate-600 line-clamp-3">
                                Chỉnh nha hiện đại giúp sắp đều hàm răng lệch lạc, hô móm nhẹ nhàng, thẩm mỹ cao và rút ngắn thời gian đeo niềng tại Nha Khoa Tám Sinh.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 sm:px-4 pb-3 pt-1">
                        <button onclick="openArticleModal(3)" class="text-xs font-bold text-dental-700 hover:text-dental-500 inline-flex items-center gap-1">
                            <span>Xem chi tiết</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </button>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 6: DANH MỤC CÁC ĐỐI TÁC & THƯƠNG HIỆU VẬT LIỆU NHA KHOA CHÍNH HÃNG
    ====================================================================== -->
    <section id="doi-tac" class="py-8 md:py-10 bg-white border-t border-slate-200">
        <div class="flatsome-container">
            <div class="text-center max-w-3xl mx-auto mb-6">
                <span class="text-xs font-bold uppercase tracking-wider text-dental-600 block mb-1">
                    HỢP TÁC QUỐC TẾ CHÍNH HÃNG
                </span>
                <h2 class="font-heading font-extrabold text-lg sm:text-2xl text-dental-800">
                    ĐỐI TÁC VẬT LIỆU & CÔNG NGHỆ NHA KHOA
                </h2>
                <div class="w-14 h-1 bg-gold-500 mx-auto mt-2 rounded-full"></div>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2.5 sm:gap-3">
                <div class="p-3 rounded-xl border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center hover:border-dental-500 transition">
                    <span class="font-heading font-extrabold text-sm text-dental-800">3M LAVA™</span>
                    <span class="text-[10.5px] text-slate-500">Răng sứ Hoa Kỳ</span>
                </div>
                <div class="p-3 rounded-xl border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center hover:border-dental-500 transition">
                    <span class="font-heading font-extrabold text-sm text-dental-800">STRAUMANN®</span>
                    <span class="text-[10.5px] text-slate-500">Implant Thụy Sĩ</span>
                </div>
                <div class="p-3 rounded-xl border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center hover:border-dental-500 transition">
                    <span class="font-heading font-extrabold text-sm text-dental-800">INVISALIGN®</span>
                    <span class="text-[10.5px] text-slate-500">Khay niềng Mỹ</span>
                </div>
                <div class="p-3 rounded-xl border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center hover:border-dental-500 transition">
                    <span class="font-heading font-extrabold text-sm text-dental-800">DENTSPLY</span>
                    <span class="text-[10.5px] text-slate-500">Cercon HT Đức</span>
                </div>
                <div class="p-3 rounded-xl border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center hover:border-dental-500 transition">
                    <span class="font-heading font-extrabold text-sm text-dental-800">IVOCLAR</span>
                    <span class="text-[10.5px] text-slate-500">Emax Press Đức</span>
                </div>
                <div class="p-3 rounded-xl border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center hover:border-dental-500 transition">
                    <span class="font-heading font-extrabold text-sm text-dental-800">OSSTEM®</span>
                    <span class="text-[10.5px] text-slate-500">Implant Hàn Quốc</span>
                </div>
                <div class="p-3 rounded-xl border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center hover:border-dental-500 transition">
                    <span class="font-heading font-extrabold text-sm text-dental-800">NACERA®</span>
                    <span class="text-[10.5px] text-slate-500">DOCERAM Đức</span>
                </div>
                <div class="p-3 rounded-xl border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center hover:border-dental-500 transition">
                    <span class="font-heading font-extrabold text-sm text-dental-800">ORODENT®</span>
                    <span class="text-[10.5px] text-slate-500">Răng sứ Italia</span>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         FOOTER CHUẨN FLATSOME
    ====================================================================== -->
    <footer class="bg-dental-900 text-slate-200 pt-10 pb-20 md:pb-10 border-t-4 border-gold-500">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-7 pb-8 border-b border-white/10">
                <!-- Thông tin pháp lý công ty -->
                <div class="lg:col-span-5 space-y-3">
                    <div class="flex items-center gap-2.5">
                        <div class="w-10 h-10 rounded-xl bg-dental-700 border border-gold-400 flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-tooth text-gold-400 text-lg"></i>
                        </div>
                        <div>
                            <h3 class="font-heading font-extrabold text-base text-white">
                                CÔNG TY TNHH MTV NHA KHOA TÁM SINH
                            </h3>
                            <p class="text-xs text-gold-400 font-semibold">Website chính thức: nhakhoatamsinh.com</p>
                        </div>
                    </div>
                    <p class="text-xs text-slate-300 leading-relaxed">
                        Nha Khoa Tám Sinh đặt chữ TÂM là yếu tố đầu tiên trong quá trình phát triển. Chúng tôi cam kết mang lại nụ cười khỏe đẹp, an toàn và chuẩn y khoa cho mọi khách hàng tại Đà Nẵng.
                    </p>
                    <ul class="space-y-1.5 text-xs text-slate-200">
                        <li><i class="fa-solid fa-location-dot text-gold-400 w-5"></i><strong>Địa chỉ:</strong> 141 Tôn Đản, Phường An Khê, TP Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone text-gold-400 w-5"></i><strong>Hotline / Zalo:</strong> <a href="tel:0702303779" class="text-gold-400 font-bold hover:underline">0702.303.779</a></li>
                        <li><i class="fa-solid fa-id-card text-gold-400 w-5"></i><strong>Mã số thuế:</strong> 0402356165</li>
                        <li><i class="fa-solid fa-globe text-gold-400 w-5"></i><strong>Website:</strong> https://nhakhoatamsinh.com</li>
                    </ul>
                </div>

                <!-- Danh mục Dịch vụ chính -->
                <div class="lg:col-span-4 space-y-2.5">
                    <h4 class="font-heading font-bold text-sm text-white uppercase tracking-wider border-b border-white/15 pb-2">
                        DANH MỤC SẢN PHẨM & DỊCH VỤ
                    </h4>
                    <ul class="grid grid-cols-1 sm:grid-cols-2 gap-1.5 text-xs text-slate-300">
                        <li><a href="#danh-muc-dich-vu" onclick="filterProducts('rang-su')" class="hover:text-gold-400">• Răng sứ Countess Moonstone</a></li>
                        <li><a href="#danh-muc-dich-vu" onclick="filterProducts('rang-su')" class="hover:text-gold-400">• Răng sứ Empress Diamond</a></li>
                        <li><a href="#danh-muc-dich-vu" onclick="filterProducts('rang-su')" class="hover:text-gold-400">• Răng sứ Cercon HT Đức</a></li>
                        <li><a href="#danh-muc-dich-vu" onclick="filterProducts('rang-su')" class="hover:text-gold-400">• Răng sứ HT Smile & Nacera Q3</a></li>
                        <li><a href="#danh-muc-dich-vu" onclick="filterProducts('veneer')" class="hover:text-gold-400">• Mặt dán sứ Veneer EMax</a></li>
                        <li><a href="#danh-muc-dich-vu" onclick="filterProducts('veneer')" class="hover:text-gold-400">• Mặt dán sứ Veneer 3D Max</a></li>
                        <li><a href="#danh-muc-dich-vu" onclick="filterProducts('chinh-nha')" class="hover:text-gold-400">• Chỉnh nha khay Invisalign</a></li>
                        <li><a href="#danh-muc-dich-vu" onclick="filterProducts('chinh-nha')" class="hover:text-gold-400">• Chỉnh nha mắc cài sứ / kim loại</a></li>
                        <li><a href="#danh-muc-dich-vu" onclick="filterProducts('implant')" class="hover:text-gold-400">• Cấy ghép Implant Định vị 4.0</a></li>
                        <li><a href="#danh-muc-dich-vu" onclick="filterProducts('tong-quat')" class="hover:text-gold-400">• Nhổ răng, Nội nha, Tẩy trắng</a></li>
                    </ul>
                </div>

                <!-- Kết nối nhanh -->
                <div class="lg:col-span-3 space-y-3">
                    <h4 class="font-heading font-bold text-sm text-white uppercase tracking-wider border-b border-white/15 pb-2">
                        LIÊN KẾT NHANH
                    </h4>
                    <div class="flex flex-col gap-2 text-xs">
                        <a href="https://www.facebook.com/profile.php?id=100063581412960&locale=vi_VN" target="_blank" rel="noopener noreferrer"
                           class="p-2.5 rounded-lg bg-white/10 hover:bg-white/20 flex items-center gap-2.5 text-white transition">
                            <i class="fa-brands fa-facebook text-blue-400 text-base"></i>
                            <span>Fanpage Nha Khoa Tám Sinh</span>
                        </a>
                        <a href="https://share.google/KWtzB88Rl7WvcFdCW" target="_blank" rel="noopener noreferrer"
                           class="p-2.5 rounded-lg bg-white/10 hover:bg-white/20 flex items-center gap-2.5 text-white transition">
                            <i class="fa-solid fa-map-location-dot text-emerald-400 text-base"></i>
                            <span>Bản đồ: 141 Tôn Đản, Đà Nẵng</span>
                        </a>
                        <a href="https://zalo.me/0702303779" target="_blank" rel="noopener noreferrer"
                           class="p-2.5 rounded-lg bg-white/10 hover:bg-white/20 flex items-center gap-2.5 text-white transition">
                            <i class="fa-solid fa-comment-dots text-sky-400 text-base"></i>
                            <span>Chat Zalo: 0702.303.779</span>
                        </a>
                    </div>
                </div>
            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between text-xs text-slate-400 gap-2 text-center">
                <p>Copyright 2026 © <strong>CÔNG TY TNHH MỘT THÀNH VIÊN NHA KHOA TÁM SINH</strong> (nhakhoatamsinh.com).</p>
                <p>Địa chỉ: 141 Tôn Đản, Phường An Khê, TP Đà Nẵng | ĐT: 0702.303.779</p>
            </div>
        </div>
    </footer>

    <!-- =====================================================================
         CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI
    ====================================================================== -->
    <div class="fixed left-3 bottom-4 z-50 flex flex-col gap-2.5">
        <!-- Nút Facebook Fanpage -->
        <a href="https://www.facebook.com/profile.php?id=100063581412960&locale=vi_VN" target="_blank" rel="noopener noreferrer"
           aria-label="Facebook Fanpage Nha Khoa Tám Sinh"
           class="flex items-center gap-2 px-3 py-2 rounded-full bg-blue-600 hover:bg-blue-700 text-white shadow-lg transition transform hover:-translate-y-0.5">
            <span class="w-7 h-7 rounded-full bg-white text-blue-600 flex items-center justify-center font-bold shrink-0">
                <i class="fa-brands fa-facebook-f text-sm"></i>
            </span>
            <span class="text-xs font-bold pr-1 hidden sm:inline">Fanpage</span>
        </a>

        <!-- Nút Chat Zalo -->
        <a href="https://zalo.me/0702303779" target="_blank" rel="noopener noreferrer"
           aria-label="Chat Zalo 0702.303.779"
           class="flex items-center gap-2 px-3 py-2 rounded-full bg-sky-500 hover:bg-sky-600 text-white shadow-lg transition transform hover:-translate-y-0.5">
            <span class="w-7 h-7 rounded-full bg-white text-sky-600 flex items-center justify-center font-extrabold text-[10px] shrink-0">
                Zalo
            </span>
            <span class="text-xs font-bold pr-1 hidden sm:inline">Chat Zalo</span>
        </a>

        <!-- Nút Hotline Nổi Bật -->
        <a href="tel:0702303779"
           aria-label="Gọi Hotline 0702.303.779"
           class="floating-pulse flex items-center gap-2 px-3.5 py-2 rounded-full bg-red-600 hover:bg-red-700 text-white shadow-xl transition">
            <span class="w-7 h-7 rounded-full bg-white text-red-600 flex items-center justify-center shrink-0">
                <i class="fa-solid fa-phone-volume text-xs"></i>
            </span>
            <span class="text-xs font-extrabold pr-1">0702.303.779</span>
        </a>
    </div>

    <!-- =====================================================================
         MODAL XEM CHI TIẾT BÀI VIẾT / ĐẶT TƯ VẤN NHANH (KHÔNG DÙNG ALERT)
    ====================================================================== -->
    <div id="info-modal" class="fixed inset-0 z-50 hidden bg-black/60 backdrop-blur-sm flex items-center justify-center p-4">
        <div class="bg-white rounded-2xl max-w-lg w-full p-5 sm:p-6 shadow-2xl border border-slate-200 relative max-h-[90vh] overflow-y-auto">
            <button onclick="closeModal()" aria-label="Đóng" class="absolute top-3.5 right-3.5 w-8 h-8 rounded-full bg-slate-100 hover:bg-slate-200 text-slate-700 flex items-center justify-center">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div id="modal-content"></div>
        </div>
    </div>

    <!-- =====================================================================
         JAVASCRIPT XỬ LÝ SLIDER 2 BANNER, LỌC DANH MỤC SẢN PHẨM & FORM BÁO GIÁ
    ====================================================================== -->
    <script>
        /* Danh sách 6 ảnh thực tế Google Drive của Nha Khoa Tám Sinh */
        const driveImages = [
            "https://drive.google.com/thumbnail?id=1hmqBa786-74rBZhhUF1fbwNfMvoYPkGx&sz=w1000",
            "https://drive.google.com/thumbnail?id=1Yw6U6O--bo9hTqynHl6e9jhKyMaqwG93&sz=w1000",
            "https://drive.google.com/thumbnail?id=1-i7406ON_fiq7mKj2h2-FisAIPGKeVzX&sz=w1000",
            "https://drive.google.com/thumbnail?id=1FKZlEMIt_pKmoYREznxpBKXSmVeYxG3i&sz=w1000",
            "https://drive.google.com/thumbnail?id=1WXNRxBXsn1_mxSbMQFJ6FSZJL8v3ML_V&sz=w1000",
            "https://drive.google.com/thumbnail?id=1Z7PJvc1zvTxXAm-evcvGfxrKXEdCY5bW&sz=w1000"
        ];

        /* Danh sách toàn bộ Sản phẩm & Dịch vụ lấy chuẩn từ web mẫu nhakhoatintam.com */
        const dentalProducts = [
            // 1. THẨM MỸ RĂNG SỨ TOÀN PHẦN CAO CẤP
            {
                id: 1,
                cat: "rang-su",
                catName: "Răng Sứ Toàn Phần Cao Cấp",
                name: "Răng sứ Countess Moonstone",
                desc: "Dòng răng sứ toàn phần cao cấp độ trong mờ tự nhiên như răng thật, chịu lực gấp 5 lần răng thật.",
                img: driveImages[2]
            },
            {
                id: 2,
                cat: "rang-su",
                catName: "Răng Sứ Toàn Phần Cao Cấp",
                name: "Răng sứ Empress Diamond",
                desc: "Phôi sứ tinh thể kim cương nhân tạo sang trọng, chống bám màu tuyệt đối và tương thích sinh học cao.",
                img: driveImages[0]
            },
            {
                id: 3,
                cat: "rang-su",
                catName: "Răng Sứ Toàn Phần Cao Cấp",
                name: "Răng sứ Cercon HT Chính Hãng Đức",
                desc: "Sứ toàn phần Cercon HT Đức thiết kế CAD/CAM chuẩn xác, không đen viền nướu, độ bền trên 20 năm.",
                img: driveImages[3]
            },
            {
                id: 4,
                cat: "rang-su",
                catName: "Răng Sứ Toàn Phần",
                name: "Răng sứ Lava Esthetic 3M Mỹ",
                desc: "Răng sứ cao cấp tập đoàn 3M Hoa Kỳ phát huỳnh quang tự nhiên, bảo hành chính hãng dài hạn.",
                img: driveImages[1]
            },
            {
                id: 5,
                cat: "rang-su",
                catName: "Răng Sứ Toàn Phần",
                name: "Răng sứ HT Smile Cao Cấp Đức",
                desc: "Dòng sứ toàn phần H.C.Starck CHLB Đức thấu quang tốt, màu sắc trắng trong tự nhiên.",
                img: driveImages[4]
            },
            {
                id: 6,
                cat: "rang-su",
                catName: "Răng Sứ Toàn Phần",
                name: "Răng sứ Nacera Q3 & Răng sứ Zirconia",
                desc: "Phục hình răng sứ thẩm mỹ chịu lực nhai lớn, phù hợp cả răng cửa thẩm mỹ và răng hàm.",
                img: driveImages[5]
            },

            // 2. MẶT DÁN SỨ VENEER LAMINATE
            {
                id: 7,
                cat: "veneer",
                catName: "Mặt Dán Sứ Veneer Laminate",
                name: "Mặt dán sứ Veneer EMax Press",
                desc: "Mặt dán sứ thủy tinh Lithium Disilicate siêu mỏng 0.3mm, bảo tồn tối đa mô răng thật tự nhiên.",
                img: driveImages[2]
            },
            {
                id: 8,
                cat: "veneer",
                catName: "Mặt Dán Sứ Veneer Laminate",
                name: "Mặt dán sứ Veneer 3D Max",
                desc: "Thiết kế nụ cười kỹ thuật số 3D tinh xảo, khắc phục răng thưa, xỉn màu nhẹ nhàng không ê buốt.",
                img: driveImages[0]
            },
            {
                id: 9,
                cat: "veneer",
                catName: "Mặt Dán Sứ Veneer Laminate",
                name: "Mặt dán sứ Veneer Ultrathin",
                desc: "Công nghệ dán sứ siêu mỏng hạn chế mài răng tối đa, giữ trọn cảm giác ăn nhai chân thật.",
                img: driveImages[4]
            },
            {
                id: 10,
                cat: "veneer",
                catName: "Mặt Dán Sứ Veneer Laminate",
                name: "Mặt dán sứ Veneer JDT Cao Cấp",
                desc: "Độ bóng tự nhiên, kháng mảng bám thực phẩm và kiến tạo đường cười hài hòa khuôn mặt.",
                img: driveImages[5]
            },

            // 3. CHỈNH NHA NIỀNG RĂNG
            {
                id: 11,
                cat: "chinh-nha",
                catName: "Chỉnh Nha Trong Suốt",
                name: "Chỉnh nha khay trong suốt Invisalign Mỹ",
                desc: "Niềng răng khay trong suốt vô hình tháo lắp linh hoạt, biết trước kết quả dịch chuyển răng 3D.",
                img: driveImages[1]
            },
            {
                id: 12,
                cat: "chinh-nha",
                catName: "Chỉnh Nha Có Mắc Cài",
                name: "Chỉnh nha mắc cài sứ thẩm mỹ",
                desc: "Mắc cài sứ trùng màu răng tự nhiên, lực kéo ổn định giúp nắn chỉnh răng hô, móm, khấp khểnh.",
                img: driveImages[3]
            },
            {
                id: 13,
                cat: "chinh-nha",
                catName: "Chỉnh Nha Có Mắc Cài",
                name: "Chỉnh nha mắc cài kim loại tự đóng",
                desc: "Hệ thống nắp trượt tự động giảm ma sát, rút ngắn thời gian chỉnh nha và giảm số lần tái khám.",
                img: driveImages[4]
            },

            // 4. CẤY GHÉP IMPLANT
            {
                id: 14,
                cat: "implant",
                catName: "Trồng Răng Implant",
                name: "Cấy ghép Implant Định vị 4.0",
                desc: "Trồng răng Implant kỹ thuật cao tích hợp xương nhanh, khôi phục chân răng độc lập bền vững trọn đời.",
                img: driveImages[3]
            },
            {
                id: 15,
                cat: "implant",
                catName: "Trồng Răng Implant",
                name: "Trồng răng Implant Hàn Quốc & Thụy Sĩ",
                desc: "Sử dụng trụ Implant Osstem, Dentium, Straumann chính hãng, ngăn ngừa tiêu xương hàm hiệu quả.",
                img: driveImages[1]
            },

            // 5. NHA KHOA TỔNG QUÁT, TIỂU PHẪU & NỘI NHA
            {
                id: 16,
                cat: "tong-quat",
                catName: "Tiểu Phẫu Nha Khoa",
                name: "Nhổ răng khôn không đau công nghệ siêu âm",
                desc: "Tiểu phẫu nhổ răng khôn mọc lệch, mọc ngầm nhẹ nhàng, lành thương nhanh và an toàn vô trùng.",
                img: driveImages[5]
            },
            {
                id: 17,
                cat: "tong-quat",
                catName: "Nội Nha Chuyên Sâu",
                name: "Điều trị tủy & Điều trị tủy lại",
                desc: "Làm sạch và trám bít ống tủy bằng thiết bị định vị chóp hiện đại, chấm dứt cơn đau nhức răng.",
                img: driveImages[0]
            },
            {
                id: 18,
                cat: "tong-quat",
                catName: "Nha Khoa Tổng Quát",
                name: "Trám răng thẩm mỹ, Lấy cao răng & Tẩy trắng răng",
                desc: "Chăm sóc răng miệng toàn diện: Cạo vôi răng siêu âm, trám răng Composite và tẩy trắng Laser.",
                img: driveImages[2]
            }
        ];

        /* Render danh sách sản phẩm (Chia 2 cột trên điện thoại, tên đầy đủ không cắt chữ, KHÔNG để nhãn dán) */
        function renderProducts(filterKey = 'all') {
            const grid = document.getElementById('product-grid');
            const filtered = filterKey === 'all'
                ? dentalProducts
                : dentalProducts.filter(item => item.cat === filterKey);

            grid.innerHTML = filtered.map(item => `
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between">
                    <div>
                        <div class="aspect-[4/3] overflow-hidden bg-slate-100">
                            <img src="${item.img}"
                                 alt="${item.name}"
                                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-3 sm:p-4">
                            <span class="block text-[10.5px] sm:text-xs font-semibold text-dental-600 mb-1">
                                ${item.catName}
                            </span>
                            <h3 class="font-bold text-xs sm:text-sm md:text-base text-slate-800 product-title-full mb-1.5">
                                ${item.name}
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                ${item.desc}
                            </p>
                        </div>
                    </div>
                    <div class="px-3 sm:px-4 pb-3.5 pt-1">
                        <button onclick="selectServiceForQuote('${item.name.replace(/'/g, "\\'")}')"
                                class="w-full py-2 px-2.5 rounded-lg bg-dental-50 hover:bg-dental-700 text-dental-800 hover:text-white font-bold text-[11.5px] sm:text-xs border border-dental-200 transition flex items-center justify-center gap-1.5">
                            <i class="fa-solid fa-calculator"></i>
                            <span>Nhận Báo Giá</span>
                        </button>
                    </div>
                </div>
            `).join('');
        }

        /* Lọc danh mục sản phẩm */
        function filterProducts(catKey) {
            renderProducts(catKey);
            const buttons = document.querySelectorAll('.cat-filter-card');
            buttons.forEach(btn => {
                btn.className = "cat-filter-card p-3 rounded-xl border border-slate-200 bg-slate-50 text-slate-800 text-center transition hover:border-dental-500 hover:bg-dental-50";
            });
            const activeBtn = document.getElementById('cat-btn-' + catKey);
            if (activeBtn) {
                activeBtn.className = "cat-filter-card p-3 rounded-xl border border-dental-600 bg-dental-700 text-white text-center shadow-sm transition";
            }
        }

        /* Chọn sản phẩm điền thẳng xuống Form Yêu Cầu & Báo Giá */
        function selectServiceForQuote(serviceName) {
            const formSection = document.getElementById('bao-gia-lien-he');
            const noteInput = document.getElementById('cust-note');
            if (noteInput) {
                noteInput.value = "Tôi muốn tư vấn và nhận báo giá dịch vụ: " + serviceName;
            }
            if (formSection) {
                formSection.scrollIntoView({ behavior: 'smooth' });
            }
        }

        /* Điều khiển Slider 2 Banner Tự Trượt */
        let currentBanner = 0;
        const totalBanners = 2;
        let bannerInterval;

        function showBanner(index) {
            for (let i = 0; i < totalBanners; i++) {
                const slide = document.getElementById('slide-' + i);
                const dot = document.getElementById('dot-' + i);
                if (i === index) {
                    slide.classList.add('active');
                    dot.className = "w-6 h-2 rounded-full bg-gold-400 transition-all";
                } else {
                    slide.classList.remove('active');
                    dot.className = "w-2.5 h-2 rounded-full bg-white/50 transition-all";
                }
            }
            currentBanner = index;
        }

        function nextBanner() {
            const next = (currentBanner + 1) % totalBanners;
            showBanner(next);
            resetBannerTimer();
        }

        function prevBanner() {
            const prev = (currentBanner - 1 + totalBanners) % totalBanners;
            showBanner(prev);
            resetBannerTimer();
        }

        function goToBanner(index) {
            showBanner(index);
            resetBannerTimer();
        }

        function resetBannerTimer() {
            clearInterval(bannerInterval);
            bannerInterval = setInterval(() => {
                const next = (currentBanner + 1) % totalBanners;
                showBanner(next);
            }, 5500);
        }

        /* Menu Mobile */
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobile-drawer');
            drawer.classList.toggle('hidden');
        }

        /* Xử lý gửi Form Yêu Cầu & Báo Giá */
        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('cust-name').value.trim();
            const phone = document.getElementById('cust-phone').value.trim();
            const service = document.getElementById('cust-service').value;
            const successBox = document.getElementById('quote-success');

            successBox.classList.remove('hidden');
            successBox.innerHTML = `
                <div class="font-bold text-sm mb-1"><i class="fa-solid fa-circle-check mr-1"></i>Đã tiếp nhận yêu cầu báo giá!</div>
                <p>Cảm ơn <strong>${name}</strong> (${phone}). Bộ phận Tư vấn Chuyên môn <strong>Nha Khoa Tám Sinh</strong> sẽ liên hệ gửi bảng báo giá chi tiết cho dịch vụ <strong>${service}</strong> ngay trong ít phút. Cần hỗ trợ gấp xin gọi <a href="tel:0702303779" class="font-bold underline">0702.303.779</a>.</p>
            `;
            document.getElementById('quote-form').reset();
        }

        /* Chi tiết bài viết tin tức */
        const articlesData = [
            {
                title: "Khi Nào Cần Ghép Xương Trong Trồng Răng Implant?",
                category: "Cấy Ghép Implant",
                content: "Khi mất răng lâu ngày, xương ổ răng tại vị trí đó sẽ bị tiêu hõm đi. Để trụ Implant đứng vững chắc và tích hợp xương toàn diện, bác sĩ tại Nha Khoa Tám Sinh (141 Tôn Đản, Đà Nẵng) sẽ thăm khám mật độ xương và chỉ định bổ sung xương nhân tạo an toàn khi cần thiết, giúp răng Implant bền chắc trọn đời."
            },
            {
                title: "So Sánh Bọc Răng Sứ Toàn Phần Và Dán Sứ Veneer Emax",
                category: "Thẩm Mỹ Răng Sứ",
                content: "Mặt dán sứ Veneer Emax siêu mỏng (0.3 - 0.5mm) phù hợp cho răng thưa nhẹ, mẻ nhẹ hoặc xỉn màu muốn giữ tối đa răng gốc. Trong khi đó, bọc răng sứ toàn phần (Countess Moonstone, Cercon HT, Lava 3M) vừa tái tạo thẩm mỹ vừa bảo vệ hoàn hảo các răng đã điều trị tủy hoặc vỡ lớn."
            },
            {
                title: "Giải Quyết Tật Nghiến Răng Khi Ngủ & Bảo Vệ Men Răng",
                category: "Nha Khoa Tổng Quát",
                content: "Tật nghiến răng ban đêm tạo lực siết mạnh làm mòn rìa cắn, ê buốt và đau khớp thái dương hàm. Sử dụng máng chống nghiến cá nhân hóa tại Nha Khoa Tám Sinh giúp bảo vệ men răng thật cũng như răng sứ thẩm mỹ an toàn khi ngủ."
            },
            {
                title: "Ưu Điểm Của Chỉnh Nha Trong Suốt Invisalign & Mắc Cài Sứ",
                category: "Chỉnh Nha Niềng Răng",
                content: "Chỉnh nha khay trong suốt Invisalign và Mắc cài sứ thẩm mỹ giúp khách hàng giao tiếp tự tin trong suốt quá trình niềng răng. Phác đồ điều trị được bác sĩ tính toán lực kéo nhẹ nhàng, chuẩn khớp cắn và hài hòa đường cười."
            }
        ];

        function openArticleModal(idx) {
            const art = articlesData[idx];
            const modal = document.getElementById('info-modal');
            const content = document.getElementById('modal-content');
            content.innerHTML = `
                <span class="text-xs font-bold text-dental-600 uppercase">${art.category}</span>
                <h3 class="font-heading font-bold text-lg text-dental-800 mt-1 mb-3">${art.title}</h3>
                <p class="text-sm text-slate-700 leading-relaxed mb-4">${art.content}</p>
                <div class="p-3.5 rounded-xl bg-dental-50 border border-dental-100 text-xs text-slate-700 space-y-1">
                    <p class="font-bold text-dental-800">CÔNG TY TNHH MTV NHA KHOA TÁM SINH</p>
                    <p>Địa chỉ: 141 Tôn Đản, Phường An Khê, TP Đà Nẵng</p>
                    <p>Hotline tư vấn miễn phí: <strong>0702.303.779</strong></p>
                </div>
            `;
            modal.classList.remove('hidden');
        }

        function closeModal() {
            document.getElementById('info-modal').classList.add('hidden');
        }

        window.onload = function () {
            renderProducts('all');
            resetBannerTimer();
        };
    </script>
</body>
</html>
