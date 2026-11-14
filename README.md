<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Yến Sào Trần Hào | Tinh Hoa Yến Sào Hội An - Đà Nẵng (yensaotranhao.com)</title>
    <meta name="description" content="Yến Sào Trần Hào (yensaotranhao.com) - Chuyên Yến Tươi Chưng Nóng, Set Quà Biếu Sức Khỏe, Yến Hũ Chưng Sẵn, Yến Tổ Tinh Chế & Yến Thô nguyên chất tại 92 Nguyễn Du, Hội An, Đà Nẵng. Hotline: 0967.664.079">

    <!-- Open Graph Thumbnail là Logo Trang Web khi chia sẻ link -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://yensaotranhao.com/">
    <meta property="og:title" content="Yến Sào Trần Hào - Tinh Hoa Yến Sào Hội An | yensaotranhao.com">
    <meta property="og:description" content="Chuyên Yến Tươi Chưng Nóng, Set Quà Biếu Thượng Hạng, Yến Hũ Chưng Sẵn & Yến Tổ Tinh Chế Nguyên Chất. Đ/c: 92 Nguyễn Du, Hội An, Đà Nẵng - ĐT: 0967.664.079">
    <meta property="og:image" id="og-logo-meta" content="https://yensaotranhao.com/logo-yen-sao-tran-hao.png">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Yến Sào Trần Hào | yensaotranhao.com">
    <meta name="twitter:image" id="twitter-logo-meta" content="https://yensaotranhao.com/logo-yen-sao-tran-hao.png">

    <!-- Tailwind CSS & Google Fonts -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Be+Vietnam+Pro:ital,wght@0,400;0,500;0,600;0,700;1,400&family=Playfair+Display:wght@600;700;800&display=swap" rel="stylesheet">
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            DEFAULT: '#7A1215', /* Đỏ rượu vang cung đình theo màu logo */
                            dark: '#580B0E',
                            light: '#9B1B1F',
                            cream: '#FDFBF7',
                            soft: '#F7F1E5',
                            gold: '#D4AF37',
                            goldLight: '#F3DF99',
                            goldDark: '#AA8213'
                        }
                    },
                    fontFamily: {
                        sans: ['"Be Vietnam Pro"', 'sans-serif'],
                        serif: ['"Playfair Display"', 'serif']
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền & chống lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            background-color: #FDFBF7;
            color: #2B2118;
            font-family: 'Be Vietnam Pro', sans-serif;
            scroll-behavior: smooth;
            -webkit-text-size-adjust: 100%;
        }

        /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính */
        .fs-container {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 10px;
            padding-right: 10px;
        }
        @media (min-width: 1024px) {
            .fs-container {
                width: 95% !important;
                max-width: 95% !important;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Danh mục trên máy tính & điện thoại: viết liền trên 1 hàng chữ nhỏ gọn, tuyệt đối không xuống dòng trong 1 tên danh mục */
        .cat-nav-item {
            white-space: nowrap !important;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            font-size: 12.5px;
            line-height: 1.2;
            font-weight: 600;
            padding: 6px 11px;
            border-radius: 6px;
            transition: all 0.2s ease;
            flex-shrink: 0;
        }
        @media (min-width: 1024px) {
            .cat-nav-item {
                font-size: 12.5px;
                padding: 6px 10px;
            }
        }

        /* Danh mục sản phẩm ở trang chủ nhỏ gọn, không gãy dòng tên danh mục */
        .home-cat-pill {
            white-space: nowrap !important;
            font-size: 12px;
            line-height: 1.25;
            font-weight: 600;
            padding: 7px 12px;
            border-radius: 9999px;
            transition: all 0.2s ease;
            display: inline-flex;
            align-items: center;
            gap: 6px;
        }

        /* Banner Slider 2 ảnh kích thước bằng nhau tuyệt đối */
        .banner-slider-wrap {
            position: relative;
            width: 100%;
            overflow: hidden;
            border-radius: 12px;
            height: 250px;
        }
        @media (min-width: 640px) {
            .banner-slider-wrap {
                height: 310px;
            }
        }
        @media (min-width: 1024px) {
            .banner-slider-wrap {
                height: 380px;
            }
        }
        .banner-slide {
            position: absolute;
            inset: 0;
            width: 100%;
            height: 100%;
            opacity: 0;
            visibility: hidden;
            transition: opacity 0.65s ease-in-out, visibility 0.65s ease-in-out;
        }
        .banner-slide.active {
            opacity: 1;
            visibility: visible;
            z-index: 2;
        }

        /* Flatsome Badge giảm giá góc trên bên trái */
        .fs-sale-badge {
            position: absolute;
            top: 8px;
            left: 8px;
            z-index: 10;
            background: linear-gradient(135deg, #D91C24 0%, #9E0B12 100%);
            color: #FFFFFF;
            font-weight: 700;
            font-size: 11px;
            line-height: 1;
            padding: 6px 8px;
            border-radius: 999px;
            box-shadow: 0 2px 6px rgba(122, 18, 21, 0.35);
            border: 1px solid rgba(255, 255, 255, 0.35);
            letter-spacing: -0.01em;
        }

        /* Tên sản phẩm hiển thị đầy đủ, không bị cắt chữ hay tràn ra ngoài */
        .fs-product-title {
            font-size: 13px;
            line-height: 1.4;
            font-weight: 600;
            color: #2B2118;
            word-wrap: break-word;
            overflow-wrap: break-word;
            white-space: normal;
            display: block;
            margin-bottom: 6px;
        }
        @media (min-width: 768px) {
            .fs-product-title {
                font-size: 14px;
            }
        }

        /* Nút nổi Zalo / Facebook / Hotline */
        @keyframes pulseRing {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(212, 175, 55, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(212, 175, 55, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(212, 175, 55, 0); }
        }
        .float-btn-pulse {
            animation: pulseRing 2s infinite;
        }
    </style>
</head>
<body class="bg-brand-cream text-stone-800 antialiased">

    <!-- ================= TOP BAR FLATSOME ĐƠN GIẢN ================= -->
    <div class="bg-brand-dark text-brand-goldLight text-[11.5px] py-1.5 border-b border-brand-gold/25">
        <div class="fs-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-3 truncate">
                <span class="font-medium text-white"><i class="fa-solid fa-crown text-brand-gold mr-1"></i>YẾN SÀO TRẦN HÀO - yensaotranhao.com</span>
                <span class="hidden md:inline text-brand-gold/50">|</span>
                <span class="hidden md:inline text-stone-200"><i class="fa-solid fa-location-dot text-brand-gold mr-1"></i>92 Nguyễn Du, Hội An, Đà Nẵng</span>
            </div>
            <div class="flex items-center gap-3 ml-auto">
                <a href="https://www.facebook.com/yen.sao.tran.hao" target="_blank" rel="noopener" class="hover:text-white transition flex items-center gap-1">
                    <i class="fa-brands fa-facebook"></i> <span>Fanpage Yến Sào Trần Hào</span>
                </a>
                <span class="text-brand-gold/40">|</span>
                <span class="text-white font-semibold">ĐT: 0967.664.079</span>
            </div>
        </div>
    </div>

    <!-- ================= HEADER FLATSOME (KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN) ================= -->
    <header class="bg-brand text-white sticky top-0 z-40 shadow-md border-b border-brand-gold/30">
        <div class="fs-container py-2">
            <div class="flex items-center justify-between gap-2">
                <!-- Logo Mới Chuyên Nghiệp - Chỉnh Gọn Nhỏ Lại -->
                <a href="#top" class="flex items-center gap-2 shrink-0 group focus:outline-none">
                    <div class="w-9 h-9 md:w-10 md:h-10 rounded-full bg-gradient-to-br from-brand-goldLight via-brand-gold to-brand-goldDark p-[1.5px] shadow shrink-0">
                        <div class="w-full h-full rounded-full bg-brand-dark flex items-center justify-center">
                            <!-- Biểu tượng Chim Yến Hoàng Gia -->
                            <svg class="w-6 h-6 md:w-6 md:h-6" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <circle cx="32" cy="32" r="29" stroke="#D4AF37" stroke-width="1.5" stroke-dasharray="3 2"/>
                                <path d="M14 36C21 33 27 26 32 16C35 24 41 31 50 34C41 35 36 39 32 48C29 40 23 37 14 36Z" fill="url(#goldGrad)"/>
                                <path d="M20 26C26 28 30 27 32 22C34 27 38 28 44 26" stroke="#FFF4CC" stroke-width="1.6" stroke-linecap="round"/>
                                <path d="M22 44C26 47 38 47 42 44" stroke="#D4AF37" stroke-width="1.8" stroke-linecap="round"/>
                                <defs>
                                    <linearGradient id="goldGrad" x1="14" y1="16" x2="50" y2="48" gradientUnits="userSpaceOnUse">
                                        <stop stop-color="#FFF2B2"/>
                                        <stop offset="0.5" stop-color="#D4AF37"/>
                                        <stop offset="1" stop-color="#9A7010"/>
                                    </linearGradient>
                                </defs>
                            </svg>
                        </div>
                    </div>
                    <div class="leading-tight">
                        <span class="block font-serif font-bold text-sm md:text-base tracking-wide text-brand-goldLight">YẾN SÀO TRẦN HÀO</span>
                        <span class="block text-[9.5px] md:text-[10px] text-stone-200 tracking-wider uppercase">yensaotranhao.com • Hội An</span>
                    </div>
                </a>

                <!-- Menu Danh Mục Trên Máy Tính: Viết liền trên 1 hàng chữ nhỏ gọn, có thể xuống hàng 2 nhưng không gãy tên danh mục -->
                <nav class="hidden lg:flex flex-wrap items-center justify-center gap-x-1 gap-y-1 flex-1 px-2">
                    <a href="#top" class="cat-nav-item bg-brand-dark/50 text-brand-goldLight border border-brand-gold/40">Trang Chủ</a>
                    <a href="#cat-yen-tuoi" class="cat-nav-item text-white hover:bg-brand-dark/50 hover:text-brand-goldLight">Yến Tươi Chưng Nóng</a>
                    <a href="#cat-set-qua" class="cat-nav-item text-white hover:bg-brand-dark/50 hover:text-brand-goldLight">Set Quà Biếu Sức Khỏe</a>
                    <a href="#cat-yen-hu" class="cat-nav-item text-white hover:bg-brand-dark/50 hover:text-brand-goldLight">Yến Hũ Chưng Sẵn</a>
                    <a href="#cat-yen-tinh-che" class="cat-nav-item text-white hover:bg-brand-dark/50 hover:text-brand-goldLight">Yến Tổ Tinh Chế</a>
                    <a href="#cat-yen-tho" class="cat-nav-item text-white hover:bg-brand-dark/50 hover:text-brand-goldLight">Yến Thô Hội An</a>
                    <a href="#section-baiviet" class="cat-nav-item text-white hover:bg-brand-dark/50 hover:text-brand-goldLight">Cẩm Nang Yến</a>
                    <a href="#section-doitac" class="cat-nav-item text-white hover:bg-brand-dark/50 hover:text-brand-goldLight">Đối Tác</a>
                    <a href="#section-baogia" class="cat-nav-item text-white hover:bg-brand-dark/50 hover:text-brand-goldLight">Báo Giá</a>
                    <a href="#section-bando" class="cat-nav-item text-white hover:bg-brand-dark/50 hover:text-brand-goldLight">Bản Đồ & Fanpage</a>
                </nav>

                <!-- Cụm nút bên phải nhỏ gọn (Không có nút Gọi Ngay trên Header) -->
                <div class="flex items-center gap-1.5 shrink-0">
                    <a href="#section-baogia" class="text-[11.5px] font-semibold bg-brand-gold text-brand-dark px-2.5 py-1.5 rounded hover:bg-brand-goldLight transition whitespace-nowrap">
                        <i class="fa-solid fa-file-signature mr-1"></i>Nhận Báo Giá
                    </a>
                    <button id="mobile-menu-btn" type="button" aria-label="Mở danh mục" class="lg:hidden w-8 h-8 rounded bg-brand-dark border border-brand-gold/40 flex items-center justify-center text-brand-goldLight">
                        <i class="fa-solid fa-bars text-sm"></i>
                    </button>
                </div>
            </div>

            <!-- Thanh Danh Mục Hiển Thị Trên Điện Thoại & Máy Tính Bảng (Nhỏ gọn, viết liền 1 dòng mỗi mục) -->
            <div id="mobile-cat-drawer" class="lg:hidden mt-2 pt-2 border-t border-brand-gold/25">
                <div class="flex flex-wrap items-center gap-1.5">
                    <a href="#cat-yen-tuoi" class="cat-nav-item bg-brand-dark/60 text-brand-goldLight border border-brand-gold/25 text-[11px] px-2.5 py-1">Yến Tươi Chưng Nóng</a>
                    <a href="#cat-set-qua" class="cat-nav-item bg-brand-dark/60 text-brand-goldLight border border-brand-gold/25 text-[11px] px-2.5 py-1">Set Quà Biếu Sức Khỏe</a>
                    <a href="#cat-yen-hu" class="cat-nav-item bg-brand-dark/60 text-brand-goldLight border border-brand-gold/25 text-[11px] px-2.5 py-1">Yến Hũ Chưng Sẵn</a>
                    <a href="#cat-yen-tinh-che" class="cat-nav-item bg-brand-dark/60 text-brand-goldLight border border-brand-gold/25 text-[11px] px-2.5 py-1">Yến Tổ Tinh Chế</a>
                    <a href="#cat-yen-tho" class="cat-nav-item bg-brand-dark/60 text-brand-goldLight border border-brand-gold/25 text-[11px] px-2.5 py-1">Yến Thô Hội An</a>
                    <a href="#section-baiviet" class="cat-nav-item bg-brand-dark/60 text-white border border-brand-gold/20 text-[11px] px-2.5 py-1">Bài Viết</a>
                    <a href="#section-doitac" class="cat-nav-item bg-brand-dark/60 text-white border border-brand-gold/20 text-[11px] px-2.5 py-1">Đối Tác</a>
                    <a href="#section-bando" class="cat-nav-item bg-brand-dark/60 text-white border border-brand-gold/20 text-[11px] px-2.5 py-1">Bản Đồ</a>
                </div>
            </div>
        </div>
    </header>

    <!-- ================= 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU ================= -->
    <!-- Chữ và hình ảnh nằm gọn bên trong banner, cách xa viền ảnh banner, không bị thiếu chữ trên điện thoại & máy tính -->
    <section id="top" class="py-3 md:py-4">
        <div class="fs-container">
            <div class="banner-slider-wrap shadow-md border border-brand-gold/35">
                
                <!-- SLIDE 1 -->
                <div class="banner-slide active bg-gradient-to-r from-[#580B0E] via-[#7A1215] to-[#4A080B]" data-slide="0">
                    <div class="w-full h-full flex items-center justify-between px-6 sm:px-12 md:px-16 lg:px-20 py-5 md:py-8">
                        <div class="w-[62%] sm:w-[60%] md:w-[58%] pr-2 sm:pr-6 text-left">
                            <p class="text-brand-goldLight text-[10px] sm:text-xs md:text-sm font-semibold uppercase tracking-widest mb-1">
                                Tinh Hoa Yến Sào Xứ Quảng • Hội An
                            </p>
                            <h1 class="font-serif font-bold text-white text-base sm:text-2xl md:text-3xl lg:text-4xl leading-snug mb-2">
                                Yến Sào Trần Hào Nguyên Chất 100%
                            </h1>
                            <p class="text-stone-200 text-[11px] sm:text-xs md:text-sm leading-relaxed mb-3">
                                Yến tươi chưng nóng thố sứ, yến hũ chưng sẵn, tổ yến tinh chế & set quà biếu thượng hạng. Tuyển chọn sợi yến già nguyên chất.
                            </p>
                            <div class="flex flex-wrap items-center gap-2">
                                <a href="#danh-muc-san-pham" class="bg-brand-gold text-brand-dark font-bold text-[11px] sm:text-xs md:text-sm px-3.5 py-1.5 sm:px-4 sm:py-2 rounded hover:bg-brand-goldLight transition">
                                    Xem Sản Phẩm
                                </a>
                                <span class="text-brand-goldLight text-[11px] sm:text-xs font-medium">
                                    92 Nguyễn Du, Hội An • 0967.664.079
                                </span>
                            </div>
                        </div>
                        <div class="w-[36%] sm:w-[38%] md:w-[38%] h-full flex items-center justify-center p-2">
                            <div class="w-32 h-32 sm:w-48 sm:h-48 md:w-64 md:h-64 rounded-xl overflow-hidden border-2 border-brand-gold/60 shadow-lg bg-brand-dark/50 shrink-0">
                                <img src="https://lh3.googleusercontent.com/d/1MQbtm7_sVbVRzPfoGrg-Od-J5JRyu0Qt=w1000"
                                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1MQbtm7_sVbVRzPfoGrg-Od-J5JRyu0Qt&sz=w1000';"
                                     alt="Yến Sào Trần Hào Hội An"
                                     class="w-full h-full object-cover">
                            </div>
                        </div>
                    </div>
                </div>

                <!-- SLIDE 2 (Kích thước bằng nhau tuyệt đối với Slide 1) -->
                <div class="banner-slide bg-gradient-to-r from-[#4A080B] via-[#7A1215] to-[#580B0E]" data-slide="1">
                    <div class="w-full h-full flex items-center justify-between px-6 sm:px-12 md:px-16 lg:px-20 py-5 md:py-8">
                        <div class="w-[62%] sm:w-[60%] md:w-[58%] pr-2 sm:pr-6 text-left">
                            <p class="text-brand-goldLight text-[10px] sm:text-xs md:text-sm font-semibold uppercase tracking-widest mb-1">
                                Món Quà Sức Khỏe Thượng Hạng
                            </p>
                            <h2 class="font-serif font-bold text-white text-base sm:text-2xl md:text-3xl lg:text-4xl leading-snug mb-2">
                                Set Quà Biếu & Yến Chưng Nóng Giao Nhanh
                            </h2>
                            <p class="text-stone-200 text-[11px] sm:text-xs md:text-sm leading-relaxed mb-3">
                                Hộp quà sang trọng tặng cha mẹ, đối tác, khách quý. Cam kết yến thật 100% không chất bảo quản, giữ trọn dưỡng chất tự nhiên.
                            </p>
                            <div class="flex flex-wrap items-center gap-2">
                                <a href="#section-baogia" class="bg-brand-gold text-brand-dark font-bold text-[11px] sm:text-xs md:text-sm px-3.5 py-1.5 sm:px-4 sm:py-2 rounded hover:bg-brand-goldLight transition">
                                    Đặt Hàng & Báo Giá
                                </a>
                                <span class="text-brand-goldLight text-[11px] sm:text-xs font-medium">
                                    Website: yensaotranhao.com
                                </span>
                            </div>
                        </div>
                        <div class="w-[36%] sm:w-[38%] md:w-[38%] h-full flex items-center justify-center p-2">
                            <div class="w-32 h-32 sm:w-48 sm:h-48 md:w-64 md:h-64 rounded-xl overflow-hidden border-2 border-brand-gold/60 shadow-lg bg-brand-dark/50 shrink-0">
                                <img src="https://lh3.googleusercontent.com/d/1hQQX1CDdZ9Aje0099or4N0-TXjAUpRPA=w1000"
                                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1hQQX1CDdZ9Aje0099or4N0-TXjAUpRPA&sz=w1000';"
                                     alt="Set Quà Yến Sào Trần Hào"
                                     class="w-full h-full object-cover">
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng Banner -->
                <button type="button" onclick="changeSlide(-1)" aria-label="Slide trước" class="absolute left-1.5 sm:left-3 top-1/2 -translate-y-1/2 z-10 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/35 text-white hover:bg-brand-gold hover:text-brand-dark flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button type="button" onclick="changeSlide(1)" aria-label="Slide tiếp" class="absolute right-1.5 sm:right-3 top-1/2 -translate-y-1/2 z-10 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/35 text-white hover:bg-brand-gold hover:text-brand-dark flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>

                <!-- Chấm tròn báo vị trí Banner -->
                <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-10 flex items-center gap-2">
                    <button type="button" onclick="goToSlide(0)" id="dot-0" class="w-5 h-2 rounded-full bg-brand-gold transition-all"></button>
                    <button type="button" onclick="goToSlide(1)" id="dot-1" class="w-2 h-2 rounded-full bg-white/50 transition-all"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= DANH MỤC SẢN PHẨM TRANG CHỦ (CHỮ NHỎ GỌN, LẤY TỪ WEB MẪU YENHAMI.COM) ================= -->
    <section id="danh-muc-san-pham" class="py-4">
        <div class="fs-container">
            <div class="bg-white rounded-xl p-3.5 md:p-5 border border-stone-200 shadow-sm">
                <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 pb-3 mb-3 border-b border-stone-100">
                    <div>
                        <h2 class="font-serif font-bold text-base md:text-lg text-brand">DANH MỤC SẢN PHẨM YẾN SÀO TRẦN HÀO</h2>
                        <p class="text-xs text-stone-500">Chọn nhanh dòng sản phẩm theo nhu cầu bồi bổ & biếu tặng</p>
                    </div>
                    <!-- Thanh lọc nhanh chữ nhỏ gọn, viết liền 1 hàng không gãy chữ -->
                    <div class="flex flex-wrap items-center gap-1.5">
                        <a href="#cat-yen-tuoi" class="home-cat-pill bg-brand text-white hover:bg-brand-dark">
                            <i class="fa-solid fa-bowl-food text-brand-goldLight"></i> Yến Tươi Chưng Nóng
                        </a>
                        <a href="#cat-set-qua" class="home-cat-pill bg-brand-soft text-brand border border-brand/20 hover:bg-brand hover:text-white">
                            <i class="fa-solid fa-gift"></i> Set Quà Biếu Sức Khỏe
                        </a>
                        <a href="#cat-yen-hu" class="home-cat-pill bg-brand-soft text-brand border border-brand/20 hover:bg-brand hover:text-white">
                            <i class="fa-solid fa-jar"></i> Yến Hũ Chưng Sẵn
                        </a>
                        <a href="#cat-yen-tinh-che" class="home-cat-pill bg-brand-soft text-brand border border-brand/20 hover:bg-brand hover:text-white">
                            <i class="fa-solid fa-feather-pointed"></i> Yến Tổ Tinh Chế
                        </a>
                        <a href="#cat-yen-tho" class="home-cat-pill bg-brand-soft text-brand border border-brand/20 hover:bg-brand hover:text-white">
                            <i class="fa-solid fa-award"></i> Yến Thô Hội An
                        </a>
                    </div>
                </div>

                <!-- 5 Ô Danh Mục Hình Ảnh Nhỏ Gọn Đẹp Trên Máy Tính & Điện Thoại -->
                <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-2.5 md:gap-3.5">
                    <a href="#cat-yen-tuoi" class="group flex items-center gap-2.5 p-2 rounded-lg border border-stone-200 hover:border-brand bg-brand-cream/60 transition">
                        <img src="https://lh3.googleusercontent.com/d/1MQbtm7_sVbVRzPfoGrg-Od-J5JRyu0Qt=w400"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1MQbtm7_sVbVRzPfoGrg-Od-J5JRyu0Qt&sz=w400';"
                             alt="Yến Tươi Chưng Nóng" class="w-11 h-11 rounded-lg object-cover shrink-0 border border-brand-gold/40">
                        <div class="min-w-0">
                            <div class="text-xs font-bold text-brand whitespace-nowrap overflow-hidden text-ellipsis">Yến Tươi Chưng Nóng</div>
                            <div class="text-[11px] text-stone-500">Thố sứ • Giao nóng</div>
                        </div>
                    </a>

                    <a href="#cat-set-qua" class="group flex items-center gap-2.5 p-2 rounded-lg border border-stone-200 hover:border-brand bg-brand-cream/60 transition">
                        <img src="https://lh3.googleusercontent.com/d/1hQQX1CDdZ9Aje0099or4N0-TXjAUpRPA=w400"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1hQQX1CDdZ9Aje0099or4N0-TXjAUpRPA&sz=w400';"
                             alt="Set Quà Biếu Sức Khỏe" class="w-11 h-11 rounded-lg object-cover shrink-0 border border-brand-gold/40">
                        <div class="min-w-0">
                            <div class="text-xs font-bold text-brand whitespace-nowrap overflow-hidden text-ellipsis">Set Quà Biếu Sức Khỏe</div>
                            <div class="text-[11px] text-stone-500">Hộp quà sang trọng</div>
                        </div>
                    </a>

                    <a href="#cat-yen-hu" class="group flex items-center gap-2.5 p-2 rounded-lg border border-stone-200 hover:border-brand bg-brand-cream/60 transition">
                        <img src="https://lh3.googleusercontent.com/d/1NsD0ROe-MimOggWG3GKw0D4V6LhM4fDL=w400"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1NsD0ROe-MimOggWG3GKw0D4V6LhM4fDL&sz=w400';"
                             alt="Yến Hũ Chưng Sẵn" class="w-11 h-11 rounded-lg object-cover shrink-0 border border-brand-gold/40">
                        <div class="min-w-0">
                            <div class="text-xs font-bold text-brand whitespace-nowrap overflow-hidden text-ellipsis">Yến Hũ Chưng Sẵn</div>
                            <div class="text-[11px] text-stone-500">Hũ 70ml & 100ml</div>
                        </div>
                    </a>

                    <a href="#cat-yen-tinh-che" class="group flex items-center gap-2.5 p-2 rounded-lg border border-stone-200 hover:border-brand bg-brand-cream/60 transition">
                        <img src="https://lh3.googleusercontent.com/d/1-1anJ3LJypKafzR-A087uq-eVmOEaj70=w400"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1-1anJ3LJypKafzR-A087uq-eVmOEaj70&sz=w400';"
                             alt="Yến Tổ Tinh Chế" class="w-11 h-11 rounded-lg object-cover shrink-0 border border-brand-gold/40">
                        <div class="min-w-0">
                            <div class="text-xs font-bold text-brand whitespace-nowrap overflow-hidden text-ellipsis">Yến Tổ Tinh Chế</div>
                            <div class="text-[11px] text-stone-500">Sạch lông 100%</div>
                        </div>
                    </a>

                    <a href="#cat-yen-tho" class="col-span-2 sm:col-span-1 group flex items-center gap-2.5 p-2 rounded-lg border border-stone-200 hover:border-brand bg-brand-cream/60 transition">
                        <img src="https://lh3.googleusercontent.com/d/1Incr94Nvy0B-AS6dMRpl-DseNiEJQOBO=w400"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Incr94Nvy0B-AS6dMRpl-DseNiEJQOBO&sz=w400';"
                             alt="Yến Thô Hội An" class="w-11 h-11 rounded-lg object-cover shrink-0 border border-brand-gold/40">
                        <div class="min-w-0">
                            <div class="text-xs font-bold text-brand whitespace-nowrap overflow-hidden text-ellipsis">Yến Thô Hội An</div>
                            <div class="text-[11px] text-stone-500">Nguyên tổ tự nhiên</div>
                        </div>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= DANH MỤC 1: YẾN TƯƠI CHƯNG NÓNG (THỐ SỨ) ================= -->
    <section id="cat-yen-tuoi" class="py-4">
        <div class="fs-container">
            <div class="flex items-center justify-between border-b-2 border-brand pb-2 mb-4">
                <h2 class="font-serif font-bold text-base sm:text-lg md:text-xl text-brand uppercase">
                    1. Yến Tươi Chưng Nóng (Thố Sứ Giao Nhanh)
                </h2>
                <a href="#section-baogia" class="text-xs font-semibold text-brand hover:underline whitespace-nowrap">Đặt chưng nóng →</a>
            </div>

            <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính (Chuẩn Flatsome Product Box) -->
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">
                <!-- SP 1 (Drive ID 1) -->
                <div class="bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-square bg-stone-100 overflow-hidden">
                        <span class="fs-sale-badge">-14%</span>
                        <img src="https://lh3.googleusercontent.com/d/1MQbtm7_sVbVRzPfoGrg-Od-J5JRyu0Qt=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1MQbtm7_sVbVRzPfoGrg-Od-J5JRyu0Qt&sz=w800';"
                             alt="Thượng Yến Nguyên Vị Chưng Nóng Thố Sứ 200ml"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] text-stone-500 mb-0.5">Yến Tươi Chưng Nóng</div>
                            <h3 class="fs-product-title">Thượng Yến Nguyên Vị Thố Sứ 200ml (35g Yến Tươi Sợi Dài)</h3>
                        </div>
                        <div class="pt-1 border-t border-stone-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                                <del class="text-[11px] text-stone-400">330.000đ</del>
                                <span class="text-xs sm:text-sm font-bold text-brand">285.000đ</span>
                            </div>
                            <button type="button" onclick="selectProductForQuote('Thượng Yến Nguyên Vị Thố Sứ 200ml - 285.000đ')" class="w-full py-1.5 px-2 rounded bg-brand text-white text-[11.5px] font-semibold hover:bg-brand-dark transition">
                                Đặt Mua / Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- SP 2 (Drive ID 2) -->
                <div class="bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-square bg-stone-100 overflow-hidden">
                        <span class="fs-sale-badge">-15%</span>
                        <img src="https://lh3.googleusercontent.com/d/1hQQX1CDdZ9Aje0099or4N0-TXjAUpRPA=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1hQQX1CDdZ9Aje0099or4N0-TXjAUpRPA&sz=w800';"
                             alt="Thượng Yến Tứ Quý Hạt Sen Táo Đỏ Kỷ Tử Thố Sứ 200ml"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] text-stone-500 mb-0.5">Yến Tươi Chưng Nóng</div>
                            <h3 class="fs-product-title">Thượng Yến Tứ Quý (Hạt Sen, Táo Đỏ, Kỷ Tử) Thố Sứ 200ml</h3>
                        </div>
                        <div class="pt-1 border-t border-stone-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                                <del class="text-[11px] text-stone-400">350.000đ</del>
                                <span class="text-xs sm:text-sm font-bold text-brand">295.000đ</span>
                            </div>
                            <button type="button" onclick="selectProductForQuote('Thượng Yến Tứ Quý Thố Sứ 200ml - 295.000đ')" class="w-full py-1.5 px-2 rounded bg-brand text-white text-[11.5px] font-semibold hover:bg-brand-dark transition">
                                Đặt Mua / Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- SP 3 (Drive ID 3) -->
                <div class="bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-square bg-stone-100 overflow-hidden">
                        <span class="fs-sale-badge">-16%</span>
                        <img src="https://lh3.googleusercontent.com/d/1NsD0ROe-MimOggWG3GKw0D4V6LhM4fDL=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1NsD0ROe-MimOggWG3GKw0D4V6LhM4fDL&sz=w800';"
                             alt="Thượng Yến Đông Trùng Hạ Thảo Chưng Nóng Thố Sứ 200ml"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] text-stone-500 mb-0.5">Yến Tươi Chưng Nóng</div>
                            <h3 class="fs-product-title">Thượng Yến Đông Trùng Hạ Thảo Chưng Nóng Thố Sứ 200ml</h3>
                        </div>
                        <div class="pt-1 border-t border-stone-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                                <del class="text-[11px] text-stone-400">380.000đ</del>
                                <span class="text-xs sm:text-sm font-bold text-brand">320.000đ</span>
                            </div>
                            <button type="button" onclick="selectProductForQuote('Thượng Yến Đông Trùng Hạ Thảo Thố Sứ 200ml - 320.000đ')" class="w-full py-1.5 px-2 rounded bg-brand text-white text-[11.5px] font-semibold hover:bg-brand-dark transition">
                                Đặt Mua / Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- SP 4 (Drive ID 4) -->
                <div class="bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-square bg-stone-100 overflow-hidden">
                        <span class="fs-sale-badge">-15%</span>
                        <img src="https://lh3.googleusercontent.com/d/1-1anJ3LJypKafzR-A087uq-eVmOEaj70=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1-1anJ3LJypKafzR-A087uq-eVmOEaj70&sz=w800';"
                             alt="Combo 2 Thố Yến Tươi Chưng Nóng 200ml Kèm Hộp Giữ Nhiệt"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] text-stone-500 mb-0.5">Yến Tươi Chưng Nóng</div>
                            <h3 class="fs-product-title">Combo 2 Thố Yến Tươi Chưng Nóng 200ml Kèm Túi Giữ Ấm</h3>
                        </div>
                        <div class="pt-1 border-t border-stone-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                                <del class="text-[11px] text-stone-400">680.000đ</del>
                                <span class="text-xs sm:text-sm font-bold text-brand">580.000đ</span>
                            </div>
                            <button type="button" onclick="selectProductForQuote('Combo 2 Thố Yến Tươi Chưng Nóng 200ml - 580.000đ')" class="w-full py-1.5 px-2 rounded bg-brand text-white text-[11.5px] font-semibold hover:bg-brand-dark transition">
                                Đặt Mua / Báo Giá
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= DANH MỤC 2: SET QUÀ BIẾU SỨC KHỎE & YẾN HŨ CHƯNG SẴN ================= -->
    <section id="cat-set-qua" class="py-4">
        <div class="fs-container">
            <div class="flex items-center justify-between border-b-2 border-brand pb-2 mb-4">
                <h2 class="font-serif font-bold text-base sm:text-lg md:text-xl text-brand uppercase">
                    2. Set Quà Biếu Sức Khỏe & Yến Hũ Chưng Sẵn Trần Hào
                </h2>
                <a href="#section-baogia" class="text-xs font-semibold text-brand hover:underline whitespace-nowrap">Nhận báo giá sỉ/lẻ →</a>
            </div>

            <div id="cat-yen-hu" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">
                <!-- SP 5 (Drive ID 5) -->
                <div class="bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-square bg-stone-100 overflow-hidden">
                        <span class="fs-sale-badge">-18%</span>
                        <img src="https://lh3.googleusercontent.com/d/1Incr94Nvy0B-AS6dMRpl-DseNiEJQOBO=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Incr94Nvy0B-AS6dMRpl-DseNiEJQOBO&sz=w800';"
                             alt="Set Quà Yến Sào Trần Hào Thượng Hạng 6 Hũ Phối Vị"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] text-stone-500 mb-0.5">Set Quà Biếu Sức Khỏe</div>
                            <h3 class="fs-product-title">Set Quà Yến Sào Trần Hào Thượng Hạng (Hộp 6 Hũ Chưng Sẵn)</h3>
                        </div>
                        <div class="pt-1 border-t border-stone-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                                <del class="text-[11px] text-stone-400">550.000đ</del>
                                <span class="text-xs sm:text-sm font-bold text-brand">450.000đ</span>
                            </div>
                            <button type="button" onclick="selectProductForQuote('Set Quà Yến Sào Trần Hào Thượng Hạng 6 Hũ - 450.000đ')" class="w-full py-1.5 px-2 rounded bg-brand text-white text-[11.5px] font-semibold hover:bg-brand-dark transition">
                                Đặt Mua / Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- SP 6 (Drive ID 6) -->
                <div class="bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-square bg-stone-100 overflow-hidden">
                        <span class="fs-sale-badge">-17%</span>
                        <img src="https://lh3.googleusercontent.com/d/1uvxXPFOpgz6CgG8Iso_12PluYwpGX4vH=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1uvxXPFOpgz6CgG8Iso_12PluYwpGX4vH&sz=w800';"
                             alt="Set Quà Hoàng Gia Yến Sào Trần Hào Hộp Quà Biếu Cao Cấp"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] text-stone-500 mb-0.5">Set Quà Biếu Sức Khỏe</div>
                            <h3 class="fs-product-title">Set Quà Hoàng Gia Yến Sào Trần Hào (Hộp Quà Biếu Đối Tác)</h3>
                        </div>
                        <div class="pt-1 border-t border-stone-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                                <del class="text-[11px] text-stone-400">780.000đ</del>
                                <span class="text-xs sm:text-sm font-bold text-brand">650.000đ</span>
                            </div>
                            <button type="button" onclick="selectProductForQuote('Set Quà Hoàng Gia Yến Sào Trần Hào - 650.000đ')" class="w-full py-1.5 px-2 rounded bg-brand text-white text-[11.5px] font-semibold hover:bg-brand-dark transition">
                                Đặt Mua / Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- SP 7 (Drive ID 7) -->
                <div class="bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-square bg-stone-100 overflow-hidden">
                        <span class="fs-sale-badge">-16%</span>
                        <img src="https://lh3.googleusercontent.com/d/1mwMy2vk27M5jiXUxgKcC9hEPyv2SQzkJ=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1mwMy2vk27M5jiXUxgKcC9hEPyv2SQzkJ&sz=w800';"
                             alt="Yến Hũ Chưng Sẵn Đường Phèn Nguyên Chất Hũ 70ml"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] text-stone-500 mb-0.5">Yến Hũ Chưng Sẵn</div>
                            <h3 class="fs-product-title">Yến Hũ Chưng Sẵn Nguyên Chất Vị Đường Phèn / Táo Đỏ (70ml)</h3>
                        </div>
                        <div class="pt-1 border-t border-stone-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                                <del class="text-[11px] text-stone-400">85.000đ</del>
                                <span class="text-xs sm:text-sm font-bold text-brand">70.000đ</span>
                            </div>
                            <button type="button" onclick="selectProductForQuote('Yến Hũ Chưng Sẵn Nguyên Chất 70ml - 70.000đ')" class="w-full py-1.5 px-2 rounded bg-brand text-white text-[11.5px] font-semibold hover:bg-brand-dark transition">
                                Đặt Mua / Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- SP 8 (Drive ID 8) -->
                <div class="bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-square bg-stone-100 overflow-hidden">
                        <span class="fs-sale-badge">-15%</span>
                        <img src="https://lh3.googleusercontent.com/d/1QmvYzUpCXRXAPwzB72uYqm6ApNdXJhqp=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1QmvYzUpCXRXAPwzB72uYqm6ApNdXJhqp&sz=w800';"
                             alt="Lốc 6 Hũ Yến Chưng Sẵn Đông Trùng Hạ Thảo & Tam Vị 100ml"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] text-stone-500 mb-0.5">Yến Hũ Chưng Sẵn</div>
                            <h3 class="fs-product-title">Hộp 6 Hũ Yến Chưng Sẵn Đông Trùng & Tứ Vị Cao Cấp (100ml)</h3>
                        </div>
                        <div class="pt-1 border-t border-stone-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                                <del class="text-[11px] text-stone-400">690.000đ</del>
                                <span class="text-xs sm:text-sm font-bold text-brand">585.000đ</span>
                            </div>
                            <button type="button" onclick="selectProductForQuote('Hộp 6 Hũ Yến Chưng Sẵn 100ml - 585.000đ')" class="w-full py-1.5 px-2 rounded bg-brand text-white text-[11.5px] font-semibold hover:bg-brand-dark transition">
                                Đặt Mua / Báo Giá
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= DANH MỤC 3: YẾN TỔ TINH CHẾ & YẾN THÔ HỘI AN ================= -->
    <section id="cat-yen-tinh-che" class="py-4">
        <div class="fs-container">
            <div class="flex items-center justify-between border-b-2 border-brand pb-2 mb-4">
                <h2 class="font-serif font-bold text-base sm:text-lg md:text-xl text-brand uppercase">
                    3. Yến Tổ Tinh Chế Thượng Hạng & Yến Thô Hội An (100g / 50g)
                </h2>
                <a href="#section-baogia" class="text-xs font-semibold text-brand hover:underline whitespace-nowrap">Tư vấn chọn tổ yến →</a>
            </div>

            <div id="cat-yen-tho" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">
                <!-- SP 9 (Drive ID 9) -->
                <div class="bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-square bg-stone-100 overflow-hidden">
                        <span class="fs-sale-badge">-12%</span>
                        <img src="https://lh3.googleusercontent.com/d/1lsNd7ZXx7hbpIElmQKS2PvsgeuOZhBrg=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1lsNd7ZXx7hbpIElmQKS2PvsgeuOZhBrg&sz=w800';"
                             alt="Yến Tổ Tinh Chế Cao Cấp Loại 1 Hộp 100g Tặng Đường Phèn Táo Đỏ"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] text-stone-500 mb-0.5">Yến Tổ Tinh Chế</div>
                            <h3 class="fs-product-title">Yến Sào Tinh Chế Siêu Sợi Loại 1 Hộp 100g (Kèm Táo Đỏ & Đường Phèn)</h3>
                        </div>
                        <div class="pt-1 border-t border-stone-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                                <del class="text-[11px] text-stone-400">3.900.000đ</del>
                                <span class="text-xs sm:text-sm font-bold text-brand">3.450.000đ</span>
                            </div>
                            <button type="button" onclick="selectProductForQuote('Yến Sào Tinh Chế Siêu Sợi Loại 1 (100g) - 3.450.000đ')" class="w-full py-1.5 px-2 rounded bg-brand text-white text-[11.5px] font-semibold hover:bg-brand-dark transition">
                                Đặt Mua / Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- SP 10 (Drive ID 10) -->
                <div class="bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-square bg-stone-100 overflow-hidden">
                        <span class="fs-sale-badge">-14%</span>
                        <img src="https://lh3.googleusercontent.com/d/1_a80RkTaepTjvTEbLM9mNgkilAELQzPM=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1_a80RkTaepTjvTEbLM9mNgkilAELQzPM&sz=w800';"
                             alt="Yến Rút Lông Nguyên Tổ Định Hình Xuất Khẩu Hộp Quà 100g"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] text-stone-500 mb-0.5">Yến Tổ Tinh Chế</div>
                            <h3 class="fs-product-title">Yến Rút Lông Nguyên Tổ Thượng Hạng Xuất Khẩu (Hộp Quà 100g)</h3>
                        </div>
                        <div class="pt-1 border-t border-stone-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                                <del class="text-[11px] text-stone-400">4.900.000đ</del>
                                <span class="text-xs sm:text-sm font-bold text-brand">4.200.000đ</span>
                            </div>
                            <button type="button" onclick="selectProductForQuote('Yến Rút Lông Nguyên Tổ Thượng Hạng (100g) - 4.200.000đ')" class="w-full py-1.5 px-2 rounded bg-brand text-white text-[11.5px] font-semibold hover:bg-brand-dark transition">
                                Đặt Mua / Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- SP 11 (Drive ID 11) -->
                <div class="bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-square bg-stone-100 overflow-hidden">
                        <span class="fs-sale-badge">-11%</span>
                        <img src="https://lh3.googleusercontent.com/d/1dw824cLrARGSN6IUM2u2JYLQiUs4asHF=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1dw824cLrARGSN6IUM2u2JYLQiUs4asHF&sz=w800';"
                             alt="Tổ Yến Thô Hội An Nguyên Chất Chọn Lọc Loại Già Tổ 100g"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] text-stone-500 mb-0.5">Yến Thô Hội An</div>
                            <h3 class="fs-product-title">Tổ Yến Thô Hội An Nguyên Chất Già Tổ Ít Lông (Hộp 100g)</h3>
                        </div>
                        <div class="pt-1 border-t border-stone-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                                <del class="text-[11px] text-stone-400">3.150.000đ</del>
                                <span class="text-xs sm:text-sm font-bold text-brand">2.800.000đ</span>
                            </div>
                            <button type="button" onclick="selectProductForQuote('Tổ Yến Thô Hội An Nguyên Chất (100g) - 2.800.000đ')" class="w-full py-1.5 px-2 rounded bg-brand text-white text-[11.5px] font-semibold hover:bg-brand-dark transition">
                                Đặt Mua / Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- SP 12 (Hộp 50g dùng thử - Ảnh thực tế Drive) -->
                <div class="bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-square bg-stone-100 overflow-hidden">
                        <span class="fs-sale-badge">-13%</span>
                        <img src="https://lh3.googleusercontent.com/d/1lsNd7ZXx7hbpIElmQKS2PvsgeuOZhBrg=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1lsNd7ZXx7hbpIElmQKS2PvsgeuOZhBrg&sz=w800';"
                             alt="Yến Sào Tinh Chế Hộp 50g Tiết Kiệm Tặng Táo Đỏ Đường Phèn"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] text-stone-500 mb-0.5">Yến Tổ Tinh Chế</div>
                            <h3 class="fs-product-title">Yến Sào Tinh Chế Nguyên Tổ Hộp 50g (Tặng Táo Đỏ & Đường Phèn)</h3>
                        </div>
                        <div class="pt-1 border-t border-stone-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                                <del class="text-[11px] text-stone-400">2.050.000đ</del>
                                <span class="text-xs sm:text-sm font-bold text-brand">1.780.000đ</span>
                            </div>
                            <button type="button" onclick="selectProductForQuote('Yến Sào Tinh Chế Nguyên Tổ (50g) - 1.780.000đ')" class="w-full py-1.5 px-2 rounded bg-brand text-white text-[11.5px] font-semibold hover:bg-brand-dark transition">
                                Đặt Mua / Báo Giá
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ ================= -->
    <section id="section-baogia" class="py-5">
        <div class="fs-container">
            <div class="bg-gradient-to-br from-brand-dark via-brand to-brand-dark text-white rounded-xl p-4 sm:p-6 md:p-8 border border-brand-gold/40 shadow-md">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                    <div class="lg:col-span-5">
                        <h2 class="font-serif font-bold text-lg sm:text-xl md:text-2xl text-brand-goldLight mb-2">
                            ĐĂNG KÝ YÊU CẦU TƯ VẤN & NHẬN BÁO GIÁ
                        </h2>
                        <p class="text-xs sm:text-sm text-stone-200 leading-relaxed mb-4">
                            Quý khách cần đặt <strong>Yến tươi chưng nóng giao tận nơi</strong>, đặt <strong>Set quà biếu doanh nghiệp</strong> hoặc nhận <strong>bảng giá sỉ/lẻ tổ yến tinh chế, yến thô Hội An</strong> vui lòng để lại thông tin. Yến Sào Trần Hào sẽ liên hệ ngay trong 5 phút!
                        </p>
                        <div class="space-y-2 text-xs sm:text-sm text-brand-goldLight">
                            <div><i class="fa-solid fa-check-circle mr-2"></i>Cam kết 100% tổ yến thật nguyên chất tại Hội An - Đà Nẵng</div>
                            <div><i class="fa-solid fa-check-circle mr-2"></i>Hoàn tiền 200% nếu phát hiện yến pha trộn, kém chất lượng</div>
                            <div><i class="fa-solid fa-phone-volume mr-2"></i>Hotline / Zalo hỗ trợ 24/7: <strong>0967.664.079</strong></div>
                        </div>
                    </div>

                    <div class="lg:col-span-7">
                        <form id="quote-form" onsubmit="submitQuoteForm(event)" class="bg-white text-stone-800 rounded-lg p-4 sm:p-5 shadow">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 mb-3">
                                <div>
                                    <label class="block text-xs font-semibold text-stone-700 mb-1">Họ và tên quý khách *</label>
                                    <input type="text" id="q-name" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 text-xs sm:text-sm border border-stone-300 rounded focus:outline-none focus:border-brand">
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold text-stone-700 mb-1">Số điện thoại / Zalo *</label>
                                    <input type="tel" id="q-phone" required placeholder="Ví dụ: 0967.664.079" class="w-full px-3 py-2 text-xs sm:text-sm border border-stone-300 rounded focus:outline-none focus:border-brand">
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 mb-3">
                                <div>
                                    <label class="block text-xs font-semibold text-stone-700 mb-1">Danh mục sản phẩm quan tâm</label>
                                    <select id="q-product" class="w-full px-3 py-2 text-xs sm:text-sm border border-stone-300 rounded focus:outline-none focus:border-brand bg-white">
                                        <option value="Yến Tươi Chưng Nóng Thố Sứ 200ml">Yến Tươi Chưng Nóng Thố Sứ 200ml</option>
                                        <option value="Set Quà Biếu Sức Khỏe Thượng Hạng">Set Quà Biếu Sức Khỏe Thượng Hạng</option>
                                        <option value="Yến Hũ Chưng Sẵn 70ml & 100ml">Yến Hũ Chưng Sẵn 70ml & 100ml</option>
                                        <option value="Yến Tổ Tinh Chế Cao Cấp (50g / 100g)">Yến Tổ Tinh Chế Cao Cấp (50g / 100g)</option>
                                        <option value="Tổ Yến Thô Hội An Nguyên Chất">Tổ Yến Thô Hội An Nguyên Chất</option>
                                        <option value="Báo Giá Sỉ Đại Lý / Quà Doanh Nghiệp">Báo Giá Sỉ Đại Lý / Quà Doanh Nghiệp</option>
                                    </select>
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold text-stone-700 mb-1">Số lượng / Nhu cầu</label>
                                    <input type="text" id="q-qty" placeholder="Ví dụ: 2 thố / 1 hộp 100g / 10 set quà" class="w-full px-3 py-2 text-xs sm:text-sm border border-stone-300 rounded focus:outline-none focus:border-brand">
                                </div>
                            </div>

                            <div class="mb-3">
                                <label class="block text-xs font-semibold text-stone-700 mb-1">Ghi chú thêm (Địa chỉ nhận hàng, ghi thiệp biếu tặng...)</label>
                                <textarea id="q-note" rows="2" placeholder="Nhập lời nhắn hoặc yêu cầu chưng ít đường, ăn kiêng..." class="w-full px-3 py-2 text-xs sm:text-sm border border-stone-300 rounded focus:outline-none focus:border-brand"></textarea>
                            </div>

                            <button type="submit" class="w-full py-2.5 px-4 rounded bg-brand text-brand-goldLight font-bold text-xs sm:text-sm hover:bg-brand-dark transition uppercase tracking-wide">
                                <i class="fa-solid fa-paper-plane mr-1.5"></i>Gửi Yêu Cầu Tư Vấn & Nhận Báo Giá Ngay
                            </button>

                            <div id="quote-success-msg" class="hidden mt-3 p-3 rounded bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs"></div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= DANH MỤC CÁC BÀI VIẾT TRANG CHỦ ================= -->
    <section id="section-baiviet" class="py-4">
        <div class="fs-container">
            <div class="flex items-center justify-between border-b-2 border-brand pb-2 mb-4">
                <h2 class="font-serif font-bold text-base sm:text-lg md:text-xl text-brand uppercase">
                    Cẩm Nang Dinh Dưỡng & Bài Viết Mới Nhất
                </h2>
                <span class="text-xs text-stone-500 hidden sm:inline">Kiến thức yến sào chuẩn từ Yến Sào Trần Hào</span>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
                <!-- Bài viết 1 -->
                <article class="bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm flex flex-col">
                    <div class="h-44 bg-stone-100 overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/1MQbtm7_sVbVRzPfoGrg-Od-J5JRyu0Qt=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1MQbtm7_sVbVRzPfoGrg-Od-J5JRyu0Qt&sz=w800';"
                             alt="Tại sao người sành yến ưu tiên yến tươi chưng nóng thố sứ"
                             class="w-full h-full object-cover">
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] font-semibold text-brand mb-1">KHOA HỌC DINH DƯỠNG</div>
                            <h3 class="font-bold text-sm text-stone-800 mb-1.5 leading-snug">
                                Tại Sao Người Sành Yến Ưu Tiên Yến Tươi Chưng Nóng Thố Sứ Thay Vì Yến Công Nghiệp?
                            </h3>
                            <p class="text-xs text-stone-600 leading-relaxed">
                                Mỗi thố yến chưng thủ công từ 35g yến tươi nguyên chất cùng táo đỏ, hạt sen, đông trùng hạ thảo giúp giữ trọn 18 loại axit amin và độ dai giòn tự nhiên của sợi yến...
                            </p>
                        </div>
                        <div class="mt-3 pt-2 border-t border-stone-100 flex items-center justify-between text-[11px] text-stone-500">
                            <span>Yến Sào Trần Hào</span>
                            <a href="#section-baogia" class="text-brand font-semibold hover:underline">Tư vấn đặt món →</a>
                        </div>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm flex flex-col">
                    <div class="h-44 bg-stone-100 overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/1Incr94Nvy0B-AS6dMRpl-DseNiEJQOBO=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Incr94Nvy0B-AS6dMRpl-DseNiEJQOBO&sz=w800';"
                             alt="Nghệ thuật chọn quà biếu sức khỏe tại Hội An Đà Nẵng"
                             class="w-full h-full object-cover">
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] font-semibold text-brand mb-1">NGHỆ THUẬT QUÀ BIẾU</div>
                            <h3 class="font-bold text-sm text-stone-800 mb-1.5 leading-snug">
                                Nghệ Thuật Chọn Quà Biếu Sức Khỏe Tại Hội An & Đà Nẵng: Trao Trọn Tâm Ý Tặng Người Thân
                            </h3>
                            <p class="text-xs text-stone-600 leading-relaxed">
                                Gợi ý 3 lựa chọn quà biếu tinh tế: Thố yến tươi chưng nóng thăm người bệnh, Set quà yến chưng 6 vị sang trọng và Hộp quà Tổ yến rút lông thượng hạng...
                            </p>
                        </div>
                        <div class="mt-3 pt-2 border-t border-stone-100 flex items-center justify-between text-[11px] text-stone-500">
                            <span>Yến Sào Trần Hào</span>
                            <a href="#cat-set-qua" class="text-brand font-semibold hover:underline">Xem Set Quà →</a>
                        </div>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm flex flex-col">
                    <div class="h-44 bg-stone-100 overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/1dw824cLrARGSN6IUM2u2JYLQiUs4asHF=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1dw824cLrARGSN6IUM2u2JYLQiUs4asHF&sz=w800';"
                             alt="Cách chưng tổ yến tinh chế và thời điểm vàng ăn yến"
                             class="w-full h-full object-cover">
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] font-semibold text-brand mb-1">CẨM NANG CHƯNG YẾN</div>
                            <h3 class="font-bold text-sm text-stone-800 mb-1.5 leading-snug">
                                Hướng Dẫn Chưng Yến Cách Thủy Đúng Chuẩn & Khung Giờ Vàng Giúp Hấp Thu 100% Dưỡng Chất
                            </h3>
                            <p class="text-xs text-stone-600 leading-relaxed">
                                Chưng cách thủy ở nhiệt độ vừa phải từ 20–25 phút và dùng vào buổi sáng sớm hoặc buổi tối trước khi ngủ 30–45 phút giúp cơ thể hấp thu trọn vẹn vi chất...
                            </p>
                        </div>
                        <div class="mt-3 pt-2 border-t border-stone-100 flex items-center justify-between text-[11px] text-stone-500">
                            <span>Yến Sào Trần Hào</span>
                            <a href="#cat-yen-tinh-che" class="text-brand font-semibold hover:underline">Xem Yến Tổ →</a>
                        </div>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- ================= DANH MỤC CÁC ĐỐI TÁC ================= -->
    <section id="section-doitac" class="py-4">
        <div class="fs-container">
            <div class="bg-white rounded-xl p-4 sm:p-5 border border-stone-200 shadow-sm">
                <div class="flex items-center justify-between border-b border-stone-200 pb-2.5 mb-4">
                    <div>
                        <h2 class="font-serif font-bold text-base sm:text-lg text-brand uppercase">
                            Danh Mục Các Đối Tác & Khách Hàng Đồng Hành
                        </h2>
                        <p class="text-xs text-stone-500">Đối tác kiểm định chất lượng, nhà hàng - khách sạn & doanh nghiệp tại Hội An - Đà Nẵng</p>
                    </div>
                </div>

                <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2.5 sm:gap-3">
                    <div class="p-3 rounded-lg bg-brand-cream border border-brand-gold/30 text-center flex flex-col items-center justify-center">
                        <i class="fa-solid fa-shield-halved text-brand text-lg mb-1"></i>
                        <div class="text-xs font-bold text-brand">QUATEST 2</div>
                        <div class="text-[10.5px] text-stone-500">Kiểm định chất lượng</div>
                    </div>
                    <div class="p-3 rounded-lg bg-brand-cream border border-brand-gold/30 text-center flex flex-col items-center justify-center">
                        <i class="fa-solid fa-certificate text-brand text-lg mb-1"></i>
                        <div class="text-xs font-bold text-brand">CHỨNG NHẬN ATTP</div>
                        <div class="text-[10.5px] text-stone-500">An toàn thực phẩm</div>
                    </div>
                    <div class="p-3 rounded-lg bg-brand-cream border border-brand-gold/30 text-center flex flex-col items-center justify-center">
                        <i class="fa-solid fa-hotel text-brand text-lg mb-1"></i>
                        <div class="text-xs font-bold text-brand">HỘI AN RESORTS</div>
                        <div class="text-[10.5px] text-stone-500">Đối tác quà tặng VIP</div>
                    </div>
                    <div class="p-3 rounded-lg bg-brand-cream border border-brand-gold/30 text-center flex flex-col items-center justify-center">
                        <i class="fa-solid fa-building-columns text-brand text-lg mb-1"></i>
                        <div class="text-xs font-bold text-brand">KHỐI NGÂN HÀNG</div>
                        <div class="text-[10.5px] text-stone-500">Quà biếu tri ân</div>
                    </div>
                    <div class="p-3 rounded-lg bg-brand-cream border border-brand-gold/30 text-center flex flex-col items-center justify-center">
                        <i class="fa-solid fa-plane-departure text-brand text-lg mb-1"></i>
                        <div class="text-xs font-bold text-brand">LỮ HÀNH ĐÀ NẴNG</div>
                        <div class="text-[10.5px] text-stone-500">Đặc sản quà Hội An</div>
                    </div>
                    <div class="p-3 rounded-lg bg-brand-cream border border-brand-gold/30 text-center flex flex-col items-center justify-center">
                        <i class="fa-solid fa-truck-fast text-brand text-lg mb-1"></i>
                        <div class="text-xs font-bold text-brand">GIAO HỎA TỐC 2H</div>
                        <div class="text-[10.5px] text-stone-500">Hội An & Đà Nẵng</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= ĐƯA GOOGLE MAP & FANPAGE RA NGOÀI TRANG CHỦ ================= -->
    <section id="section-bando" class="py-4">
        <div class="fs-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-4">
                
                <!-- Cột Google Maps Trang Chủ (7/12) -->
                <div class="lg:col-span-7 bg-white rounded-xl p-4 border border-stone-200 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="flex flex-wrap items-center justify-between gap-2 pb-2.5 mb-3 border-b border-stone-100">
                            <div>
                                <h2 class="font-serif font-bold text-base sm:text-lg text-brand uppercase">
                                    <i class="fa-solid fa-map-location-dot mr-1.5"></i>Bản Đồ Cửa Hàng Yến Sào Trần Hào
                                </h2>
                                <p class="text-xs text-stone-600 mt-0.5">
                                    Địa chỉ: <strong>92 Nguyễn Du, Hội An, Đà Nẵng</strong> • Điện thoại: <strong>0967.664.079</strong>
                                </p>
                            </div>
                            <a href="https://www.google.com/maps/search/?api=1&query=92+Nguy%E1%BB%85n+Du,+H%E1%BB%99i+An" target="_blank" rel="noopener" class="text-xs font-semibold bg-brand text-white px-3 py-1.5 rounded hover:bg-brand-dark transition whitespace-nowrap">
                                <i class="fa-solid fa-diamond-turn-right mr-1"></i>Mở Chỉ Đường
                            </a>
                        </div>

                        <!-- Google Maps Nhúng Trực Tiếp Ngoài Trang Chủ -->
                        <div class="w-full h-64 sm:h-72 rounded-lg overflow-hidden border border-stone-200 bg-stone-100">
                            <iframe
                                title="Bản đồ Yến Sào Trần Hào 92 Nguyễn Du, Hội An, Đà Nẵng"
                                src="https://maps.google.com/maps?q=92%20Nguy%E1%BB%85n%20Du,%20H%E1%BB%99i%20An&t=&z=16&ie=UTF8&iwloc=&output=embed"
                                class="w-full h-full border-0"
                                loading="lazy"
                                referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                        </div>
                    </div>
                    <div class="mt-3 pt-2.5 border-t border-stone-100 flex flex-wrap items-center justify-between gap-2 text-xs text-stone-600">
                        <span><i class="fa-solid fa-clock text-brand mr-1"></i>Giờ mở cửa: 07:30 – 21:30 (Tất cả các ngày trong tuần)</span>
                        <span class="font-semibold text-brand">Website: yensaotranhao.com</span>
                    </div>
                </div>

                <!-- Cột Fanpage Facebook Ngoài Trang Chủ (5/12) -->
                <div class="lg:col-span-5 bg-white rounded-xl p-4 border border-stone-200 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between gap-2 pb-2.5 mb-3 border-b border-stone-100">
                            <div>
                                <h2 class="font-serif font-bold text-base sm:text-lg text-brand uppercase">
                                    <i class="fa-brands fa-facebook text-[#1877F2] mr-1.5"></i>Fanpage Yến Sào Trần Hào
                                </h2>
                                <p class="text-xs text-stone-600 mt-0.5">Kết nối trực tiếp qua Facebook chính thức</p>
                            </div>
                            <a href="https://www.facebook.com/yen.sao.tran.hao" target="_blank" rel="noopener" class="text-xs font-semibold bg-[#1877F2] text-white px-3 py-1.5 rounded hover:opacity-90 transition whitespace-nowrap">
                                Theo Dõi Trang
                            </a>
                        </div>

                        <!-- Khung hiển thị Fanpage trực quan + Plugin Facebook -->
                        <div class="rounded-lg border border-stone-200 overflow-hidden bg-stone-50 p-3">
                            <div class="flex items-center gap-3 pb-3 mb-3 border-b border-stone-200">
                                <img src="https://lh3.googleusercontent.com/d/1MQbtm7_sVbVRzPfoGrg-Od-J5JRyu0Qt=w300"
                                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1MQbtm7_sVbVRzPfoGrg-Od-J5JRyu0Qt&sz=w300';"
                                     alt="Fanpage Yến Sào Trần Hào"
                                     class="w-12 h-12 rounded-full object-cover border-2 border-brand-gold shrink-0">
                                <div class="min-w-0">
                                    <a href="https://www.facebook.com/yen.sao.tran.hao" target="_blank" rel="noopener" class="font-bold text-sm text-[#1877F2] hover:underline block truncate">
                                        Yến Sào Trần Hào - Hội An
                                    </a>
                                    <div class="text-[11px] text-stone-500">facebook.com/yen.sao.tran.hao</div>
                                    <div class="text-[11px] text-emerald-700 font-medium mt-0.5">● Đang hoạt động • Tư vấn nhanh 24/7</div>
                                </div>
                            </div>

                            <!-- Facebook Page Plugin Iframe -->
                            <div class="w-full overflow-hidden rounded border border-stone-200 bg-white flex justify-center">
                                <iframe
                                    title="Facebook Fanpage Yến Sào Trần Hào"
                                    src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fyen.sao.tran.hao&tabs=timeline&width=340&height=180&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true"
                                    width="340"
                                    height="180"
                                    style="border:none;overflow:hidden;max-width:100%;"
                                    scrolling="no"
                                    frameborder="0"
                                    allowfullscreen="true"
                                    allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                                </iframe>
                            </div>

                            <div class="mt-3 flex flex-wrap gap-2">
                                <a href="https://www.facebook.com/yen.sao.tran.hao" target="_blank" rel="noopener" class="flex-1 text-center py-2 px-3 rounded bg-[#1877F2] text-white text-xs font-semibold hover:opacity-95 transition">
                                    <i class="fa-brands fa-facebook-messenger mr-1"></i>Nhắn Tin Fanpage
                                </a>
                                <a href="https://zalo.me/0967664079" target="_blank" rel="noopener" class="flex-1 text-center py-2 px-3 rounded bg-brand text-brand-goldLight text-xs font-semibold hover:bg-brand-dark transition">
                                    <i class="fa-solid fa-comment-dots mr-1"></i>Chat Zalo: 0967.664.079
                                </a>
                            </div>
                        </div>
                    </div>

                    <div class="mt-3 pt-2.5 border-t border-stone-100 text-xs text-stone-600 flex items-center justify-between">
                        <span>Chuyên Yến Sào Hội An - Đà Nẵng</span>
                        <a href="https://www.facebook.com/yen.sao.tran.hao" target="_blank" rel="noopener" class="text-[#1877F2] font-semibold hover:underline">Xem bài đăng mới →</a>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ================= FOOTER CHUẨN FLATSOME ================= -->
    <footer class="bg-brand-dark text-stone-200 pt-8 pb-6 mt-4 border-t-2 border-brand-gold">
        <div class="fs-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 pb-6 border-b border-brand-gold/20">
                <!-- Cột 1: Thương hiệu -->
                <div>
                    <div class="flex items-center gap-2.5 mb-3">
                        <div class="w-9 h-9 rounded-full bg-brand-gold p-[1.5px] shrink-0">
                            <div class="w-full h-full rounded-full bg-brand-dark flex items-center justify-center">
                                <i class="fa-solid fa-feather-pointed text-brand-gold text-sm"></i>
                            </div>
                        </div>
                        <div>
                            <div class="font-serif font-bold text-base text-brand-goldLight">YẾN SÀO TRẦN HÀO</div>
                            <div class="text-[10.5px] text-stone-300">Website: yensaotranhao.com</div>
                        </div>
                    </div>
                    <p class="text-xs text-stone-300 leading-relaxed mb-3">
                        Chuyên cung cấp Yến Tươi Chưng Nóng, Set Quà Biếu Sức Khỏe Thượng Hạng, Yến Hũ Chưng Sẵn, Tổ Yến Tinh Chế và Yến Thô Hội An nguyên chất 100%.
                    </p>
                    <div class="text-xs text-brand-goldLight space-y-1">
                        <div><i class="fa-solid fa-location-dot mr-1.5"></i>Địa chỉ: 92 Nguyễn Du, Hội An, Đà Nẵng</div>
                        <div><i class="fa-solid fa-phone mr-1.5"></i>Hotline / Zalo: 0967.664.079</div>
                        <div><i class="fa-solid fa-globe mr-1.5"></i>Website: yensaotranhao.com</div>
                    </div>
                </div>

                <!-- Cột 2: Danh mục sản phẩm -->
                <div>
                    <h3 class="font-serif font-bold text-sm text-brand-goldLight uppercase mb-3">Danh Mục Sản Phẩm</h3>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#cat-yen-tuoi" class="hover:text-brand-goldLight transition">• Yến Tươi Chưng Nóng (Thố sứ 200ml)</a></li>
                        <li><a href="#cat-set-qua" class="hover:text-brand-goldLight transition">• Set Quà Biếu Sức Khỏe Thượng Hạng</a></li>
                        <li><a href="#cat-yen-hu" class="hover:text-brand-goldLight transition">• Yến Hũ Chưng Sẵn 70ml & 100ml</a></li>
                        <li><a href="#cat-yen-tinh-che" class="hover:text-brand-goldLight transition">• Yến Tổ Tinh Chế Nguyên Tổ 100g</a></li>
                        <li><a href="#cat-yen-tho" class="hover:text-brand-goldLight transition">• Tổ Yến Thô Hội An Tự Nhiên</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Chính sách khách hàng -->
                <div>
                    <h3 class="font-serif font-bold text-sm text-brand-goldLight uppercase mb-3">Chính Sách & Cam Kết</h3>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#section-baogia" class="hover:text-brand-goldLight transition">• Chính sách giao nóng 2H Hội An - Đà Nẵng</a></li>
                        <li><a href="#section-baogia" class="hover:text-brand-goldLight transition">• Cam kết 100% yến thật không pha trộn</a></li>
                        <li><a href="#section-baogia" class="hover:text-brand-goldLight transition">• Chính sách chiết khấu sỉ & quà doanh nghiệp</a></li>
                        <li><a href="#section-baogia" class="hover:text-brand-goldLight transition">• Hướng dẫn kiểm tra & bảo quản tổ yến</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Kết nối nhanh -->
                <div>
                    <h3 class="font-serif font-bold text-sm text-brand-goldLight uppercase mb-3">Liên Hệ Nhanh</h3>
                    <p class="text-xs text-stone-300 mb-3">
                        Đặt yến chưng nóng hoặc tư vấn quà biếu sức khỏe nhanh chóng qua Hotline/Zalo hoặc Fanpage:
                    </p>
                    <div class="flex flex-col gap-2">
                        <a href="tel:0967664079" class="py-2 px-3 rounded bg-brand-gold text-brand-dark font-bold text-xs text-center hover:bg-brand-goldLight transition">
                            <i class="fa-solid fa-phone-volume mr-1.5"></i>Gọi Hotline: 0967.664.079
                        </a>
                        <a href="https://www.facebook.com/yen.sao.tran.hao" target="_blank" rel="noopener" class="py-2 px-3 rounded bg-[#1877F2] text-white font-semibold text-xs text-center hover:opacity-95 transition">
                            <i class="fa-brands fa-facebook mr-1.5"></i>Fanpage Yến Sào Trần Hào
                        </a>
                    </div>
                </div>
            </div>

            <div class="pt-4 text-center text-[11.5px] text-stone-400">
                © 2026 <strong class="text-brand-goldLight">YẾN SÀO TRẦN HÀO (yensaotranhao.com)</strong> • Địa chỉ: 92 Nguyễn Du, Hội An, Đà Nẵng • ĐT/Zalo: 0967.664.079
            </div>
        </div>
    </footer>

    <!-- ================= CÁC NÚT LIÊN HỆ NỔI BẬT ZALO, FACEBOOK, HOTLINE (TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI) ================= -->
    <div class="fixed right-3 bottom-4 z-50 flex flex-col items-end gap-2.5">
        <!-- Nút Zalo nổi bật -->
        <a href="https://zalo.me/0967664079" target="_blank" rel="noopener" aria-label="Chat Zalo 0967.664.079"
           class="float-btn-pulse flex items-center gap-2 bg-[#0068FF] text-white pl-3 pr-3.5 py-2 rounded-full shadow-lg border border-white/40 hover:scale-105 transition">
            <span class="w-6 h-6 rounded-full bg-white text-[#0068FF] font-extrabold text-[10px] flex items-center justify-center shrink-0">Zalo</span>
            <span class="text-xs font-bold whitespace-nowrap">Zalo: 0967.664.079</span>
        </a>

        <!-- Nút Facebook Fanpage nổi bật -->
        <a href="https://www.facebook.com/yen.sao.tran.hao" target="_blank" rel="noopener" aria-label="Fanpage Yến Sào Trần Hào"
           class="flex items-center gap-2 bg-[#1877F2] text-white pl-3 pr-3.5 py-2 rounded-full shadow-lg border border-white/40 hover:scale-105 transition">
            <span class="w-6 h-6 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
                <i class="fa-brands fa-facebook-f text-xs"></i>
            </span>
            <span class="text-xs font-bold whitespace-nowrap">Facebook Trần Hào</span>
        </a>

        <!-- Nút Hotline nổi bật -->
        <a href="tel:0967664079" aria-label="Gọi 0967.664.079"
           class="float-btn-pulse flex items-center gap-2 bg-brand text-brand-goldLight pl-3 pr-3.5 py-2 rounded-full shadow-lg border border-brand-gold hover:scale-105 transition">
            <span class="w-6 h-6 rounded-full bg-brand-gold text-brand-dark flex items-center justify-center shrink-0">
                <i class="fa-solid fa-phone-volume text-xs"></i>
            </span>
            <span class="text-xs font-bold whitespace-nowrap">0967.664.079</span>
        </a>
    </div>

    <!-- ================= JAVASCRIPT XỬ LÝ BANNER TỰ TRƯỢT, FORM BÁO GIÁ & THUMBNAIL LOGO ================= -->
    <script>
        // 1. Tự động trượt 2 Banner kích thước bằng nhau
        let currentSlide = 0;
        const slides = document.querySelectorAll('.banner-slide');
        const totalSlides = slides.length;
        let slideTimer = null;

        function updateSlides() {
            slides.forEach((slide, index) => {
                if (index === currentSlide) {
                    slide.classList.add('active');
                } else {
                    slide.classList.remove('active');
                }
            });
            const dot0 = document.getElementById('dot-0');
            const dot1 = document.getElementById('dot-1');
            if (dot0 && dot1) {
                dot0.className = currentSlide === 0 ? 'w-5 h-2 rounded-full bg-brand-gold transition-all' : 'w-2 h-2 rounded-full bg-white/50 transition-all';
                dot1.className = currentSlide === 1 ? 'w-5 h-2 rounded-full bg-brand-gold transition-all' : 'w-2 h-2 rounded-full bg-white/50 transition-all';
            }
        }

        function changeSlide(direction) {
            currentSlide = (currentSlide + direction + totalSlides) % totalSlides;
            updateSlides();
            resetSlideTimer();
        }

        function goToSlide(index) {
            currentSlide = index;
            updateSlides();
            resetSlideTimer();
        }

        function resetSlideTimer() {
            if (slideTimer) clearInterval(slideTimer);
            slideTimer = setInterval(() => {
                currentSlide = (currentSlide + 1) % totalSlides;
                updateSlides();
            }, 4500);
        }

        // 2. Nút đóng/mở thanh danh mục trên điện thoại
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileCatDrawer = document.getElementById('mobile-cat-drawer');
        if (mobileMenuBtn && mobileCatDrawer) {
            mobileMenuBtn.addEventListener('click', () => {
                mobileCatDrawer.classList.toggle('hidden');
            });
        }

        // 3. Chọn sản phẩm điền tự động vào Form Yêu Cầu & Báo Giá
        function selectProductForQuote(productName) {
            const selectEl = document.getElementById('q-product');
            const noteEl = document.getElementById('q-note');
            if (selectEl) {
                let matched = false;
                for (let i = 0; i < selectEl.options.length; i++) {
                    if (productName.toLowerCase().includes(selectEl.options[i].value.toLowerCase().slice(0, 12))) {
                        selectEl.selectedIndex = i;
                        matched = true;
                        break;
                    }
                }
                if (!matched) {
                    const customOpt = document.createElement('option');
                    customOpt.value = productName;
                    customOpt.textContent = productName;
                    selectEl.appendChild(customOpt);
                    selectEl.value = productName;
                }
            }
            if (noteEl) {
                noteEl.value = 'Tôi muốn đặt mua / nhận báo giá sản phẩm: ' + productName;
            }
            const formSection = document.getElementById('section-baogia');
            if (formSection) {
                formSection.scrollIntoView({ behavior: 'smooth' });
            }
        }

        // 4. Xử lý gửi Form Báo Giá ngay trên trang chủ
        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('q-name').value.trim();
            const phone = document.getElementById('q-phone').value.trim();
            const product = document.getElementById('q-product').value;
            const qty = document.getElementById('q-qty').value.trim() || '1';
            const msgBox = document.getElementById('quote-success-msg');

            if (msgBox) {
                msgBox.classList.remove('hidden');
                msgBox.innerHTML = '<strong>Đã gửi yêu cầu thành công!</strong> Cảm ơn <strong>' + name + '</strong> (' + phone + '). Yến Sào Trần Hào đã ghi nhận yêu cầu báo giá <strong>' + product + ' (SL: ' + qty + ')</strong> và sẽ liên hệ lại ngay qua SĐT/Zalo <strong>0967.664.079</strong>.';
            }
        }

        // 5. Khởi tạo ảnh Thumbnail Open Graph là Logo Yến Sào Trần Hào khi gửi link trang web
        window.onload = function () {
            resetSlideTimer();
            try {
                const canvas = document.createElement('canvas');
                canvas.width = 1200;
                canvas.height = 630;
                const ctx = canvas.getContext('2d');
                if (ctx) {
                    const grad = ctx.createLinearGradient(0, 0, 1200, 630);
                    grad.addColorStop(0, '#580B0E');
                    grad.addColorStop(0.5, '#7A1215');
                    grad.addColorStop(1, '#4A080B');
                    ctx.fillStyle = grad;
                    ctx.fillRect(0, 0, 1200, 630);

                    ctx.strokeStyle = '#D4AF37';
                    ctx.lineWidth = 6;
                    ctx.strokeRect(36, 36, 1128, 558);

                    ctx.fillStyle = '#F3DF99';
                    ctx.font = 'bold 64px Georgia, serif';
                    ctx.textAlign = 'center';
                    ctx.fillText('YẾN SÀO TRẦN HÀO', 600, 310);

                    ctx.fillStyle = '#FFFFFF';
                    ctx.font = '32px sans-serif';
                    ctx.fillText('yensaotranhao.com • 92 Nguyễn Du, Hội An, Đà Nẵng • 0967.664.079', 600, 385);

                    const dataUrl = canvas.toDataURL('image/png');
                    const ogMeta = document.getElementById('og-logo-meta');
                    const twMeta = document.getElementById('twitter-logo-meta');
                    if (ogMeta) ogMeta.setAttribute('content', dataUrl);
                    if (twMeta) twMeta.setAttribute('content', dataUrl);
                }
            } catch (err) {
                // Giữ nguyên meta mặc định nếu trình duyệt hạn chế canvas
            }
        };
    </script>
</body>
</html>
