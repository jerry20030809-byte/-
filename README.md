<!-- 首頁 - HARE Air Studio (繁中) Desktop v2 -->
<!DOCTYPE html>

<html lang="zh-Hant"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>HARE AIR STUDIO | 24SS COLLECTION</title>
<!-- Material Symbols -->
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<!-- Google Fonts -->
<link href="https://fonts.googleapis.com" rel="preconnect"/>
<link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/>
<link href="https://fonts.googleapis.com/css2?family=Bodoni+Moda:opsz,wght@6..96,400..900&amp;family=Hanken+Grotesk:wght@300..800&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<!-- Tailwind CSS -->
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<!-- Tailwind Config -->
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "surface-container-low": "#f3f3f3",
                        "outline-variant": "#c4c7c7",
                        "inverse-surface": "#2f3131",
                        "surface-tint": "#5f5e5e",
                        "on-tertiary-fixed": "#1a1c1c",
                        "tertiary-container": "#1a1c1c",
                        "surface-variant": "#e2e2e2",
                        "on-tertiary-container": "#838484",
                        "primary-fixed": "#e5e2e1",
                        "on-primary": "#ffffff",
                        "secondary-fixed-dim": "#b2cad7",
                        "on-primary-fixed-variant": "#474646",
                        "error-container": "#ffdad6",
                        "on-surface-variant": "#444748",
                        "primary-container": "#1c1b1b",
                        "inverse-primary": "#c8c6c5",
                        "surface-container-highest": "#e2e2e2",
                        "surface-container": "#eeeeee",
                        "outline": "#747878",
                        "primary-fixed-dim": "#c8c6c5",
                        "on-secondary-fixed": "#051e28",
                        "surface-container-lowest": "#ffffff",
                        "on-secondary-fixed-variant": "#334a54",
                        "on-surface": "#1a1c1c",
                        "on-primary-fixed": "#1c1b1b",
                        "background": "#f9f9f9",
                        "inverse-on-surface": "#f1f1f1",
                        "tertiary": "#000000",
                        "secondary-container": "#cbe3f0",
                        "primary": "#000000",
                        "surface-bright": "#f9f9f9",
                        "surface": "#f9f9f9",
                        "tertiary-fixed-dim": "#c6c6c6",
                        "surface-container-high": "#e8e8e8",
                        "on-tertiary-fixed-variant": "#454747",
                        "surface-dim": "#dadada",
                        "on-primary-container": "#858383",
                        "secondary-fixed": "#cee6f3",
                        "secondary": "#4b626d",
                        "on-secondary": "#ffffff",
                        "on-error-container": "#93000a",
                        "on-background": "#1a1c1c",
                        "error": "#ba1a1a",
                        "on-secondary-container": "#4f6671",
                        "tertiary-fixed": "#e2e2e2",
                        "on-tertiary": "#ffffff",
                        "on-error": "#ffffff"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.25rem",
                        "lg": "0.5rem",
                        "xl": "0.75rem",
                        "full": "9999px"
                    },
                    "spacing": {
                        "margin-desktop": "64px",
                        "gutter": "24px",
                        "container-max-width": "1440px",
                        "unit": "8px",
                        "section-gap": "128px",
                        "margin-mobile": "20px"
                    },
                    "fontFamily": {
                        "nav-link": ["Hanken Grotesk"],
                        "label-caps": ["Hanken Grotesk"],
                        "display-xl-mobile": ["Bodoni Moda"],
                        "headline-lg": ["Bodoni Moda"],
                        "headline-lg-mobile": ["Bodoni Moda"],
                        "body-md": ["Hanken Grotesk"],
                        "body-lg": ["Hanken Grotesk"],
                        "display-xl": ["Bodoni Moda"],
                        "headline-md": ["Bodoni Moda"]
                    },
                    "fontSize": {
                        "nav-link": ["14px", { "lineHeight": "20px", "letterSpacing": "0.05em", "fontWeight": "500" }],
                        "label-caps": ["12px", { "lineHeight": "16px", "letterSpacing": "0.1em", "fontWeight": "700" }],
                        "display-xl-mobile": ["48px", { "lineHeight": "56px", "letterSpacing": "-0.02em", "fontWeight": "600" }],
                        "headline-lg": ["40px", { "lineHeight": "48px", "fontWeight": "500" }],
                        "headline-lg-mobile": ["32px", { "lineHeight": "40px", "fontWeight": "500" }],
                        "body-md": ["16px", { "lineHeight": "24px", "fontWeight": "400" }],
                        "body-lg": ["18px", { "lineHeight": "28px", "fontWeight": "400" }],
                        "display-xl": ["72px", { "lineHeight": "80px", "letterSpacing": "-0.02em", "fontWeight": "600" }],
                        "headline-md": ["24px", { "lineHeight": "32px", "fontWeight": "500" }]
                    }
                }
            }
        }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 300, 'GRAD' 0, 'opsz' 24;
        }
        /* Blueprint Slider Logic */
        .blueprint-container:hover .blueprint-overlay {
            opacity: 1;
        }
        .blueprint-container:hover .blueprint-base {
            opacity: 0;
        }
    </style>
</head>
<body class="bg-background text-on-surface font-body-md antialiased selection:bg-primary selection:text-on-primary min-h-screen flex flex-col">
<!-- TopNavBar -->
<header class="w-full top-0 left-0 border-b border-outline-variant dark:border-on-tertiary-fixed-variant bg-background dark:bg-background z-50 sticky">
<div class="flex justify-between items-center w-full px-margin-desktop py-unit max-w-container-max-width mx-auto">
<!-- Navigation Links (Left) -->
<nav class="hidden md:flex gap-8">
<a class="font-nav-link text-nav-link uppercase tracking-widest text-on-surface-variant dark:text-on-tertiary-container hover:text-secondary dark:hover:text-secondary-fixed-dim transition-all duration-300 cursor-pointer active:opacity-70" href="#">COLLECTIONS</a>
<a class="font-nav-link text-nav-link uppercase tracking-widest text-on-surface-variant dark:text-on-tertiary-container hover:text-secondary dark:hover:text-secondary-fixed-dim transition-all duration-300 cursor-pointer active:opacity-70" href="#">STUDIO</a>
<a class="font-nav-link text-nav-link uppercase tracking-widest text-on-surface-variant dark:text-on-tertiary-container hover:text-secondary dark:hover:text-secondary-fixed-dim transition-all duration-300 cursor-pointer active:opacity-70" href="#">LOGISTICS</a>
<a class="font-nav-link text-nav-link uppercase tracking-widest text-on-surface-variant dark:text-on-tertiary-container hover:text-secondary dark:hover:text-secondary-fixed-dim transition-all duration-300 cursor-pointer active:opacity-70" href="#">ARCHIVE</a>
<a class="font-nav-link text-nav-link uppercase tracking-widest text-on-surface-variant dark:text-on-tertiary-container hover:text-secondary dark:hover:text-secondary-fixed-dim transition-all duration-300 cursor-pointer active:opacity-70" href="#">STORES</a>
</nav>
<!-- Brand Logo (Center) -->
<div class="font-display-xl text-display-xl tracking-tighter text-primary dark:text-on-background absolute left-1/2 transform -translate-x-1/2 whitespace-nowrap">
                HARE AIR STUDIO
            </div>
<!-- Trailing Icons (Right) -->
<div class="flex gap-6 items-center z-10">
<button class="text-primary dark:text-on-background hover:text-secondary transition-colors cursor-pointer active:opacity-70">
<span class="material-symbols-outlined" data-icon="search">search</span>
</button>
<button class="text-primary dark:text-on-background hover:text-secondary transition-colors cursor-pointer active:opacity-70">
<span class="material-symbols-outlined" data-icon="shopping_bag">shopping_bag</span>
</button>
</div>
</div>
</header>
<main class="flex-grow">
<!-- Hero Section: Editorial 24SS -->
<section class="max-w-container-max-width mx-auto px-margin-desktop pt-12 pb-section-gap">
<div class="relative w-full aspect-[21/9] bg-surface-variant overflow-hidden border border-outline-variant">
<div class="absolute inset-0 bg-cover bg-center" data-alt="A striking digital fashion editorial photograph featuring an avant-garde Japanese silhouette. The model is positioned against a stark, minimalist concrete wall in a high-key studio environment. Lighting is dramatic and directional, creating sharp shadows that emphasize the architectural cut of the dark garments. The overall aesthetic is austere, premium, and highly structural, utilizing a monochromatic black and white palette to highlight the studio's design philosophy." style="background-image: url('https://lh3.googleusercontent.com/aida-public/AB6AXuBGYgGI12iK29142BPUAml9zZ1pK7qSAr7rgzM7XaT2LG0XiePTCkFdh2X9ufRqu3MEuKv2SslLBhdxp-Tbj3fWuKPRq9tAX4Hm75jUYze1U-ynraszZQg9imCX-d6zsV4xI2gyyt4QNgkiZlTCUTJC0IwfIdiwTflhUFQKvF6iQtT7SXxIkzl0EoDoE4DyJPvpptW3_Ucy-eBk4lSG7XMIY0dTLEKkcqfX-AWLE1Yf-WukgiA-YqJuwKv0gfzBNzmFE-Y78h9P_Fa2');"></div>
<div class="absolute inset-0 bg-black/20"></div>
<div class="absolute bottom-12 left-12">
<h1 class="font-display-xl text-display-xl text-on-primary mb-2">24SS COLLECTION</h1>
<p class="font-nav-link text-nav-link text-on-primary uppercase tracking-widest">The Architecture of Movement.</p>
</div>
</div>
</section>
<!-- Section: 工作室藍圖 (Studio Blueprint) -->
<section class="max-w-container-max-width mx-auto px-margin-desktop py-section-gap border-t border-outline-variant">
<div class="grid grid-cols-12 gap-gutter items-center">
<div class="col-span-5 pr-12">
<h2 class="font-headline-lg text-headline-lg text-primary mb-6">工作室藍圖</h2>
<p class="font-body-lg text-body-lg text-on-surface-variant mb-8 leading-relaxed">
                        解構每一件單品的幾何結構。我們的設計過程如同建築圖紙般精密，強調立體剪裁與人體工學的完美結合。透過此透視圖，探索衣物背後的隱藏邏輯與工藝細節。
                    </p>
<a class="inline-flex items-center justify-center bg-primary text-on-primary font-label-caps text-label-caps uppercase px-8 py-4 hover:bg-secondary transition-colors duration-300" href="#">
                        探索完整藍圖
                    </a>
</div>
<div class="col-span-7 relative">
<!-- Blueprint Slider Component -->
<div class="relative w-full aspect-square border border-outline-variant blueprint-container cursor-crosshair overflow-hidden bg-surface-container-low">
<img alt="Finished garment" class="absolute inset-0 w-full h-full object-cover transition-opacity duration-500 blueprint-base" data-alt="A meticulously styled flat lay of a complex, multi-layered black technical jacket placed precisely on a pristine white surface. The lighting is extremely flat and even, typical of high-end product archival photography. The fabric texture is crisp, showcasing the technical nylon and matte finish. The composition is dead-center, emphasizing the garment's symmetrical structure and avant-garde silhouette within a minimalist context." src="https://lh3.googleusercontent.com/aida-public/AB6AXuCE651f9F8pKK4LBTwchrU64zSWwvKGXcDPg0cR3WQhafNNQ6YKMI34X0NtC0BVM0SLXn3q2MLlv0VVw5IEupMgtSUL8Je1WhWH13oWyJOxt-4yzEhkdTefMbRVVmCdM9PHrHw7BACR76nDNGHkEaFnvET-NWFdphPttShirVrGc2KpCzxpokGerWQsJYCNShCx8YEuKchz5xq2tVqmNuY5ukTNmClOK8FAtlBCXp0zP8ZYEnO4zPOC9dFM4CmC1vrOoiKB7yC-DRdL"/>
<div class="absolute inset-0 w-full h-full bg-[url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxMDAlIiBoZWlnaHQ9IjEwMCUiPjxkZWZzPjxwYXR0ZXJuIGlkPSJncmlkIiB3aWR0aD0iNDAiIGhlaWdodD0iNDAiIHBhdHRlcm5Vbml0cz0idXNlclNwYWNlT25Vc2UiPjxwYXRoIGQ9Ik0gNDAgMCBMIDAgMCAwIDQwIiBmaWxsPSJub25lIiBzdHJva2U9IiNlMmUyZTIiIHN0cm9rZS13aWR0aD0iMSIvPjwvcGF0dGVybj48L2RlZnM+PHJlY3Qgd2lkdGg9IjEwMCUiIGhlaWdodD0iMTAwJSIgZmlsbD0idXJsKCNncmlkKSIvPjwvc3ZnPg==')] opacity-0 transition-opacity duration-500 blueprint-overlay flex items-center justify-center bg-surface">
<div class="w-3/4 h-3/4 border border-outline-variant relative">
<div class="absolute top-4 left-4 font-label-caps text-label-caps text-outline">FIG. 01 // STRUCTURAL DRAFT</div>
<div class="absolute inset-0 flex items-center justify-center font-headline-lg text-outline-variant text-opacity-30 select-none">TECHNICAL SKETCH</div>
<!-- Decorative lines for blueprint feel -->
<div class="absolute top-1/2 left-0 w-full h-[1px] bg-outline-variant"></div>
<div class="absolute top-0 left-1/2 w-[1px] h-full bg-outline-variant"></div>
</div>
</div>
</div>
<div class="mt-4 flex justify-between font-label-caps text-label-caps text-on-surface-variant">
<span>ITEM: 24SS-JK-01</span>
<span>[ HOVER TO INSPECT STRUCTURE ]</span>
</div>
</div>
</div>
</section>
<!-- Section: 店員穿搭 (Staff Styling) -->
<section class="max-w-container-max-width mx-auto px-margin-desktop py-section-gap">
<div class="flex justify-between items-end mb-12">
<h2 class="font-headline-lg text-headline-lg text-primary uppercase">店員穿搭</h2>
<a class="font-nav-link text-nav-link border-b border-primary text-primary pb-1 hover:text-secondary hover:border-secondary transition-colors duration-300" href="#">VIEW ALL STYLING</a>
</div>
<div class="grid grid-cols-4 gap-gutter">
<!-- Card 1 -->
<div class="group cursor-pointer">
<div class="w-full aspect-[3/4] bg-surface-variant mb-4 overflow-hidden">
<img alt="Staff Styling" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" data-alt="A full-length fashion portrait of a stylish individual wearing a monochromatic, oversized outfit. The setting is an urban, brutalist environment featuring raw concrete textures. The lighting is overcast, providing soft, diffused shadows that complement the minimalist, structured aesthetic of the clothing. The overall mood is cool, detached, and distinctly modern, aligning with Japanese street fashion photography." src="https://lh3.googleusercontent.com/aida-public/AB6AXuDKF-F4x_dRxLDbFVhmzNGjwjM_NEZ8QGkIVHcnJYVWCSTvQUEM98NRI1rbWKIrA-PyxRvmC5B7IcuW2C292FiNJIkYE6aqRyc8IrNyibs1aUzjtUHWVqxq_YRLHs4a_ME3gior5bbLmLagEtiD_NWOOYKTae7ClfiomUEYnRXomxeDbI91zSrckcsQQEf6hU0_yljNi36v9K-srzXOPm9LUs_lv_xKjUCt9W-YGSeb7O8jCr3iXP4zltl_mGuIe4glQ-m9ENzw1gSi"/>
</div>
<div class="font-label-caps text-label-caps text-on-surface-variant mb-1">TOKYO FLAGSHIP</div>
<h3 class="font-body-md text-body-md text-primary font-bold mb-1">RYOTA / 178CM</h3>
<p class="font-body-md text-body-md text-on-surface-variant text-sm">24SS Oversized Blazer, Wide Trousers</p>
</div>
<!-- Card 2 -->
<div class="group cursor-pointer">
<div class="w-full aspect-[3/4] bg-surface-variant mb-4 overflow-hidden">
<img alt="Staff Styling" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" data-alt="A dynamic full-body shot of a fashion model wearing an avant-garde layered ensemble, primarily in stark white and deep charcoal. The background is a clean, featureless white cyclorama studio wall, focusing all attention on the architectural draping and tailoring of the garments. The lighting is bright and clinically clean, emphasizing the high-contrast, premium lookbook style of the brand." src="https://lh3.googleusercontent.com/aida-public/AB6AXuD-EdPEfaXS4-0KdWwjQg4IUpn8eIhDVVfp7ZfdiXM3TMypDsS2VQ5iq9zVh8ukI4n-vaZtHb2iB3vr_DNumvQpfUdBjRn5qByguEs_nS2NqSnUIudQ19dOxZBD7XC5eP-ILmMzmrdgdqpMTuG_CIRpblDdQNm5IuAULcV_VrFON7i3qErfyzQtSEgXEcNbVFDXMhFf0whxE3IJ2zwaGC1JYA0uFRpyXIWsbKl7UnRmqiNKLM59ie9mTXs6h6xa3SEqU4KkWyjRKwDc"/>
</div>
<div class="font-label-caps text-label-caps text-on-surface-variant mb-1">OSAKA STUDIO</div>
<h3 class="font-body-md text-body-md text-primary font-bold mb-1">YUKI / 165CM</h3>
<p class="font-body-md text-body-md text-on-surface-variant text-sm">Technical Vest, Asymmetric Skirt</p>
</div>
<!-- Card 3 -->
<div class="group cursor-pointer">
<div class="w-full aspect-[3/4] bg-surface-variant mb-4 overflow-hidden">
<img alt="Staff Styling" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" data-alt="An editorial street-style photograph capturing a subject mid-stride in an industrial setting. They are dressed in a sleek, minimalist all-black outfit featuring wide-leg pants and a structured cropped jacket. The environment includes metal fencing and concrete, shot with a slightly desaturated color grading to enhance the cool, urban architectural vibe. The composition emphasizes movement and precise tailoring." src="https://lh3.googleusercontent.com/aida-public/AB6AXuBUU6ec0eHXEIUsgWMN5EKn7sPpQ9etW2EX-28gp8kMTx9Nofw-aQw3RQvWnAfgdgbgzwnVZT_f5YTLdBLp3WesnD3XI4ecp1vnixpxgzcOnnl0OGQGLTRv3uWeNhxOaqE0MfuXC_8XUOjgHq7r-St07EQHoUZ4_2QNq7STCc-GXSaSxS75s8jvP8pj9Cf5RJrSln36WDE0Sgvq5r46TIxaAQtX7i6XEi34MpWouF9duHE9C3Wds58XsQebxtgQvcuEKpUNoWAMnQLB"/>
</div>
<div class="font-label-caps text-label-caps text-on-surface-variant mb-1">KYOTO ARCHIVE</div>
<h3 class="font-body-md text-body-md text-primary font-bold mb-1">KENJI / 182CM</h3>
<p class="font-body-md text-body-md text-on-surface-variant text-sm">Minimalist Mac Coat, Zip Trousers</p>
</div>
<!-- Card 4 -->
<div class="group cursor-pointer">
<div class="w-full aspect-[3/4] bg-surface-variant mb-4 overflow-hidden">
<img alt="Staff Styling" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" data-alt="A stylized portrait of a fashion model standing against a pale grey concrete block wall. They wear a high-concept, multi-textured grey and black outfit that plays with proportion and asymmetry. The lighting is soft and flat, minimizing shadows to draw attention to the fabric's details and the garment's unusual cut. The aesthetic is extremely clean, controlled, and distinctly high-fashion." src="https://lh3.googleusercontent.com/aida-public/AB6AXuDjRUINUpE3Mg92YhxriMFGUNcjDpqqYxBiGtAdeaqx5G-2FN74UNw-mnSGwE_dTH_GTq5ehDbKO7srpdvSaZvuDdXFqDB8n2poXqnkovvWC6DpnwFUgOCIfmE2qpcxSajrT2CwGzxHyrU7MXZpPNykssrV7HTorv316bFkJaRSu7GJSb5KaSe5wn4mXrG_VW9hvOgNqWBKWoBO8ZLbXashqMDGPXLLoN-FxOx2mqkHOUNxrz7zst7JBXKSS8lNmIAdRIjdl7k1QOPb"/>
</div>
<div class="font-label-caps text-label-caps text-on-surface-variant mb-1">TOKYO FLAGSHIP</div>
<h3 class="font-body-md text-body-md text-primary font-bold mb-1">SORA / 170CM</h3>
<p class="font-body-md text-body-md text-on-surface-variant text-sm">Deconstructed Shirt, Cargo Pants</p>
</div>
</div>
</section>
<!-- Section: 來自日本的空運直送 (Air Delivery) -->
<section class="bg-surface-container-highest border-y border-outline-variant">
<div class="max-w-container-max-width mx-auto px-margin-desktop grid grid-cols-12 gap-gutter">
<div class="col-span-6 py-section-gap flex flex-col justify-center pr-16 border-r border-outline-variant">
<div class="inline-block border border-outline-variant px-3 py-1 font-label-caps text-label-caps text-primary w-max mb-8">
                        LOGISTICS &amp; SUPPLY CHAIN
                    </div>
<h2 class="font-headline-lg text-headline-lg text-primary mb-6">來自日本的空運直送</h2>
<p class="font-body-lg text-body-lg text-on-surface-variant mb-12">
                        結合極致的物流效率與精準的追蹤系統。我們確保每一件設計作品都能以最完美的狀態，迅速跨越國界送達您的手中。這不僅是運送，更是品牌對時間與品質的承諾。
                    </p>
<div class="grid grid-cols-2 gap-8">
<div class="border-l-2 border-primary pl-4">
<div class="font-display-xl-mobile text-display-xl-mobile text-primary leading-none mb-2">03<span class="text-headline-md">Days</span></div>
<div class="font-label-caps text-label-caps text-on-surface-variant">AVERAGE TRANSIT TIME</div>
</div>
<div class="border-l-2 border-primary pl-4">
<div class="font-display-xl-mobile text-display-xl-mobile text-primary leading-none mb-2">100<span class="text-headline-md">%</span></div>
<div class="font-label-caps text-label-caps text-on-surface-variant">REAL-TIME TRACKING</div>
</div>
</div>
</div>
<div class="col-span-6 relative bg-surface-container-low" data-alt="An abstract, highly graphic photograph of stacked modern shipping containers painted in stark whites and cool greys. The composition is extremely tight, focusing on the geometric lines, barcode labels, and industrial metal textures. The lighting is harsh and bright, casting sharp diagonal shadows that enhance the architectural, precise, and logistics-focused theme of the brand's 'Air' identity." style="background-image: url('https://lh3.googleusercontent.com/aida-public/AB6AXuALGMrVrpdG8Xqjg7vlf0tH7c1jKJYt6njghnZMmCcpEG8VDRgTWWOcc-w1mOqNAzrlwD1n1uwmpsa0FykTq6oUwUUIGCSLBcYklleprH-WRgBGtaBQoI5RVviSMXUr0uKAqYMUdBYBsR4d9PKoMCXSrhj3TIa4hqEOPBZ8zbLD8MU1xSoGaOLdi6mh2a3EzvM127iHPM85nn8WrU7hogMo8FV3iluyLmf0TFVXM5yXLNP1nCbEBpYbR3iL4FxGK9eXPVY5kIXCNujz'); background-size: cover; background-position: center;">
<div class="absolute inset-0 bg-white/10 backdrop-blur-[2px]"></div>
</div>
</div>
</section>
<!-- Section: 加入工作室 (Join the Studio) -->
<section class="max-w-container-max-width mx-auto px-margin-desktop py-section-gap text-center">
<div class="max-w-2xl mx-auto border border-outline-variant p-16 bg-surface-bright">
<span class="material-symbols-outlined text-4xl mb-6 text-primary" data-icon="qr_code_scanner">qr_code_scanner</span>
<h2 class="font-headline-lg text-headline-lg text-primary mb-4">加入工作室</h2>
<p class="font-body-md text-body-md text-on-surface-variant mb-8">
                    下載 HARE AIR APP 或綁定 LINE 官方帳號，獲取最新 24SS 系列發售資訊、專屬造型建議及免運費代碼。
                </p>
<div class="flex justify-center gap-4">
<button class="bg-primary text-on-primary font-label-caps text-label-caps uppercase px-8 py-4 hover:bg-secondary transition-colors duration-300">
                        DOWNLOAD APP
                    </button>
<button class="bg-transparent border border-primary text-primary font-label-caps text-label-caps uppercase px-8 py-4 hover:bg-surface-variant transition-colors duration-300">
                        CONNECT LINE
                    </button>
</div>
</div>
</section>
</main>
<!-- Footer -->
<footer class="bg-surface-container dark:bg-tertiary-container text-primary dark:text-on-background font-body-md text-body-md w-full mt-section-gap border-t border-outline-variant grid grid-cols-12 gap-gutter px-margin-desktop py-section-gap max-w-container-max-width mx-auto">
<div class="col-span-12 md:col-span-4 mb-8 md:mb-0">
<div class="font-headline-md text-headline-md font-bold text-primary mb-4">HARE AIR STUDIO</div>
<p class="text-on-surface-variant dark:text-on-tertiary-container text-sm">
                © 2024 HARE AIR STUDIO. ALL RIGHTS RESERVED.
            </p>
</div>
<div class="col-span-6 md:col-span-4">
<ul class="flex flex-col gap-3">
<li><a class="text-on-surface-variant dark:text-on-tertiary-container hover:underline decoration-1 underline-offset-4 transition-opacity duration-200" href="#">PRIVACY POLICY</a></li>
<li><a class="text-on-surface-variant dark:text-on-tertiary-container hover:underline decoration-1 underline-offset-4 transition-opacity duration-200" href="#">TERMS OF SERVICE</a></li>
<li><a class="text-on-surface-variant dark:text-on-tertiary-container hover:underline decoration-1 underline-offset-4 transition-opacity duration-200" href="#">SHIPPING &amp; RETURNS</a></li>
</ul>
</div>
<div class="col-span-6 md:col-span-4">
<ul class="flex flex-col gap-3">
<li><a class="text-on-surface-variant dark:text-on-tertiary-container hover:underline decoration-1 underline-offset-4 transition-opacity duration-200" href="#">CONTACT</a></li>
<li><a class="text-on-surface-variant dark:text-on-tertiary-container hover:underline decoration-1 underline-offset-4 transition-opacity duration-200" href="#">INSTAGRAM</a></li>
<li><a class="text-on-surface-variant dark:text-on-tertiary-container hover:underline decoration-1 underline-offset-4 transition-opacity duration-200" href="#">TWITTER</a></li>
</ul>
</div>
</footer>
</body></html>

<!-- 選品商城 - HARE Air Studio (繁中) Desktop v2 -->
<!DOCTYPE html>

<html lang="zh-Hant"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>HARE Air Studio - Shop Collections</title>
<!-- Google Fonts -->
<link href="https://fonts.googleapis.com" rel="preconnect"/>
<link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/>
<link href="https://fonts.googleapis.com/css2?family=Bodoni+Moda:ital,opsz,wght@0,6..96,400..900;1,6..96,400..900&amp;family=Hanken+Grotesk:ital,wght@0,100..900;1,100..900&amp;display=swap" rel="stylesheet"/>
<!-- Material Symbols -->
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 300, 'GRAD' 0, 'opsz' 24;
        }
    </style>
<!-- Tailwind Config -->
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "surface-container-low": "#f3f3f3",
                        "outline-variant": "#c4c7c7",
                        "inverse-surface": "#2f3131",
                        "surface-tint": "#5f5e5e",
                        "on-tertiary-fixed": "#1a1c1c",
                        "tertiary-container": "#1a1c1c",
                        "surface-variant": "#e2e2e2",
                        "on-tertiary-container": "#838484",
                        "primary-fixed": "#e5e2e1",
                        "on-primary": "#ffffff",
                        "secondary-fixed-dim": "#b2cad7",
                        "on-primary-fixed-variant": "#474646",
                        "error-container": "#ffdad6",
                        "on-surface-variant": "#444748",
                        "primary-container": "#1c1b1b",
                        "inverse-primary": "#c8c6c5",
                        "surface-container-highest": "#e2e2e2",
                        "surface-container": "#eeeeee",
                        "outline": "#747878",
                        "primary-fixed-dim": "#c8c6c5",
                        "on-secondary-fixed": "#051e28",
                        "surface-container-lowest": "#ffffff",
                        "on-secondary-fixed-variant": "#334a54",
                        "on-surface": "#1a1c1c",
                        "on-primary-fixed": "#1c1b1b",
                        "background": "#f9f9f9",
                        "inverse-on-surface": "#f1f1f1",
                        "tertiary": "#000000",
                        "secondary-container": "#cbe3f0",
                        "primary": "#000000",
                        "surface-bright": "#f9f9f9",
                        "surface": "#f9f9f9",
                        "tertiary-fixed-dim": "#c6c6c6",
                        "surface-container-high": "#e8e8e8",
                        "on-tertiary-fixed-variant": "#454747",
                        "surface-dim": "#dadada",
                        "on-primary-container": "#858383",
                        "secondary-fixed": "#cee6f3",
                        "secondary": "#4b626d",
                        "on-secondary": "#ffffff",
                        "on-error-container": "#93000a",
                        "on-background": "#1a1c1c",
                        "error": "#ba1a1a",
                        "on-secondary-container": "#4f6671",
                        "tertiary-fixed": "#e2e2e2",
                        "on-tertiary": "#ffffff",
                        "on-error": "#ffffff"
                    },
                    "borderRadius": {
                        "DEFAULT": "0px", /* Enforcing architectural sharp edges */
                        "lg": "0px",
                        "xl": "0px",
                        "full": "0px"
                    },
                    "spacing": {
                        "margin-desktop": "64px",
                        "gutter": "24px",
                        "container-max-width": "1440px",
                        "unit": "8px",
                        "section-gap": "128px",
                        "margin-mobile": "20px"
                    },
                    "fontFamily": {
                        "nav-link": ["Hanken Grotesk", "sans-serif"],
                        "label-caps": ["Hanken Grotesk", "sans-serif"],
                        "display-xl-mobile": ["Bodoni Moda", "serif"],
                        "headline-lg": ["Bodoni Moda", "serif"],
                        "headline-lg-mobile": ["Bodoni Moda", "serif"],
                        "body-md": ["Hanken Grotesk", "sans-serif"],
                        "body-lg": ["Hanken Grotesk", "sans-serif"],
                        "display-xl": ["Bodoni Moda", "serif"],
                        "headline-md": ["Bodoni Moda", "serif"]
                    },
                    "fontSize": {
                        "nav-link": ["14px", { "lineHeight": "20px", "letterSpacing": "0.05em", "fontWeight": "500" }],
                        "label-caps": ["12px", { "lineHeight": "16px", "letterSpacing": "0.1em", "fontWeight": "700" }],
                        "display-xl-mobile": ["48px", { "lineHeight": "56px", "letterSpacing": "-0.02em", "fontWeight": "600" }],
                        "headline-lg": ["40px", { "lineHeight": "48px", "fontWeight": "500" }],
                        "headline-lg-mobile": ["32px", { "lineHeight": "40px", "fontWeight": "500" }],
                        "body-md": ["16px", { "lineHeight": "24px", "fontWeight": "400" }],
                        "body-lg": ["18px", { "lineHeight": "28px", "fontWeight": "400" }],
                        "display-xl": ["72px", { "lineHeight": "80px", "letterSpacing": "-0.02em", "fontWeight": "600" }],
                        "headline-md": ["24px", { "lineHeight": "32px", "fontWeight": "500" }]
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-background text-on-background font-body-md antialiased selection:bg-primary selection:text-on-primary">
<!-- TopNavBar Shared Component -->
<nav class="w-full top-0 left-0 bg-background border-b border-outline-variant z-50 sticky">
<div class="flex justify-between items-center w-full px-margin-desktop py-unit max-w-container-max-width mx-auto">
<!-- Navigation Links (Left) -->
<div class="flex items-center gap-6">
<a class="font-nav-link text-nav-link uppercase tracking-widest text-primary border-b-2 border-primary pb-1 cursor-pointer active:opacity-70 transition-colors" href="#">COLLECTIONS</a>
<a class="font-nav-link text-nav-link uppercase tracking-widest text-on-surface-variant hover:text-primary transition-colors cursor-pointer active:opacity-70 transition-all duration-300" href="#">STUDIO</a>
<a class="font-nav-link text-nav-link uppercase tracking-widest text-on-surface-variant hover:text-primary transition-colors cursor-pointer active:opacity-70 transition-all duration-300" href="#">LOGISTICS</a>
<a class="font-nav-link text-nav-link uppercase tracking-widest text-on-surface-variant hover:text-primary transition-colors cursor-pointer active:opacity-70 transition-all duration-300" href="#">ARCHIVE</a>
<a class="font-nav-link text-nav-link uppercase tracking-widest text-on-surface-variant hover:text-primary transition-colors cursor-pointer active:opacity-70 transition-all duration-300" href="#">STORES</a>
</div>
<!-- Brand Logo (Center) -->
<div class="absolute left-1/2 transform -translate-x-1/2">
<a class="font-display-xl text-display-xl tracking-tighter text-primary" href="#">HARE AIR STUDIO</a>
</div>
<!-- Trailing Icons (Right) -->
<div class="flex items-center gap-4">
<button class="text-on-surface-variant hover:text-primary transition-colors cursor-pointer active:opacity-70">
<span class="material-symbols-outlined" data-icon="search">search</span>
</button>
<button class="text-on-surface-variant hover:text-primary transition-colors cursor-pointer active:opacity-70">
<span class="material-symbols-outlined" data-icon="shopping_bag">shopping_bag</span>
</button>
</div>
</div>
</nav>
<!-- Main Content -->
<main class="max-w-container-max-width mx-auto px-margin-desktop pb-section-gap">
<!-- Header -->
<header class="mt-24 mb-16 text-center">
<h1 class="font-display-xl text-display-xl text-primary">SHOP COLLECTIONS</h1>
</header>
<div class="grid grid-cols-12 gap-gutter">
<!-- Left Sidebar Filters -->
<aside class="col-span-3 hidden md:block">
<div class="sticky top-32 space-y-12">
<!-- Filter Group: Gender -->
<div class="border-b border-outline-variant pb-6">
<h3 class="font-label-caps text-label-caps uppercase text-outline mb-4">性別 GENDER</h3>
<ul class="space-y-3 font-body-md text-body-md">
<li><label class="flex items-center gap-3 cursor-pointer group"><input class="form-checkbox text-primary border-outline-variant focus:ring-primary rounded-none" type="checkbox"/><span class="group-hover:text-primary transition-colors">男裝 Menswear</span></label></li>
<li><label class="flex items-center gap-3 cursor-pointer group"><input checked="" class="form-checkbox text-primary border-outline-variant focus:ring-primary rounded-none" type="checkbox"/><span class="text-primary border-b border-primary">女裝 Womenswear</span></label></li>
<li><label class="flex items-center gap-3 cursor-pointer group"><input class="form-checkbox text-primary border-outline-variant focus:ring-primary rounded-none" type="checkbox"/><span class="group-hover:text-primary transition-colors">中性 Unisex</span></label></li>
</ul>
</div>
<!-- Filter Group: Material -->
<div class="border-b border-outline-variant pb-6">
<h3 class="font-label-caps text-label-caps uppercase text-outline mb-4">材質 MATERIAL</h3>
<ul class="space-y-3 font-body-md text-body-md">
<li><label class="flex items-center gap-3 cursor-pointer group"><input class="form-checkbox text-primary border-outline-variant focus:ring-primary rounded-none" type="checkbox"/><span class="group-hover:text-primary transition-colors">重磅純棉 Heavy Cotton</span></label></li>
<li><label class="flex items-center gap-3 cursor-pointer group"><input class="form-checkbox text-primary border-outline-variant focus:ring-primary rounded-none" type="checkbox"/><span class="group-hover:text-primary transition-colors">科技纖維 Tech Fabric</span></label></li>
<li><label class="flex items-center gap-3 cursor-pointer group"><input class="form-checkbox text-primary border-outline-variant focus:ring-primary rounded-none" type="checkbox"/><span class="group-hover:text-primary transition-colors">初剪羊毛 Virgin Wool</span></label></li>
</ul>
</div>
<!-- Filter Group: Construction -->
<div class="border-b border-outline-variant pb-6">
<h3 class="font-label-caps text-label-caps uppercase text-outline mb-4">結構 CONSTRUCTION</h3>
<ul class="space-y-3 font-body-md text-body-md">
<li><label class="flex items-center gap-3 cursor-pointer group"><input class="form-checkbox text-primary border-outline-variant focus:ring-primary rounded-none" type="checkbox"/><span class="group-hover:text-primary transition-colors">不對稱 Asymmetric</span></label></li>
<li><label class="flex items-center gap-3 cursor-pointer group"><input class="form-checkbox text-primary border-outline-variant focus:ring-primary rounded-none" type="checkbox"/><span class="group-hover:text-primary transition-colors">解構 Deconstructed</span></label></li>
<li><label class="flex items-center gap-3 cursor-pointer group"><input class="form-checkbox text-primary border-outline-variant focus:ring-primary rounded-none" type="checkbox"/><span class="group-hover:text-primary transition-colors">立體剪裁 3D Tailoring</span></label></li>
</ul>
</div>
</div>
</aside>
<!-- Main Product Grid Area -->
<div class="col-span-12 md:col-span-9">
<!-- Section 1: Signature Cuts -->
<div class="mb-section-gap">
<h2 class="font-headline-lg text-headline-lg text-primary mb-8 border-b border-outline-variant pb-4">經典剪裁 <span class="font-body-md text-outline ml-4 uppercase tracking-widest text-sm">Signature Cuts</span></h2>
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-x-gutter gap-y-16">
<!-- Product Card 1 -->
<article class="group cursor-pointer">
<div class="w-full aspect-[3/4] bg-surface-container-low mb-4 overflow-hidden relative">
<img alt="Model wearing a minimalist structural blazer" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" data-alt="High-contrast studio photography of a model wearing a stark black, avant-garde architectural blazer. The garment features sharp, geometric shoulders and a tailored waist. The background is a flat, pristine off-white (#f9f9f9) creating a dramatic, premium lookbook aesthetic. The lighting is harsh and directional, emphasizing the texture and precise cut of the fabric." src="https://lh3.googleusercontent.com/aida-public/AB6AXuA7zNW-miu4nlHvfoqhRN1EIo_Zi9NAg9Xu03O7usNUZD_htt1-xRxtvAGS9k6yjepX2HNuBAXIsqPMahVIVvh7H_WosTl2uxUb9y5pcAwlvgG_2l8jfoLKgz2FMMC5GcTTQN4A33_UDB789--nRdR60Vj03LfD8qDoiVb2wZP7KEaJW1Q25f7HVtjxLRVlItPXdDxCAFfyPbhCBiFXb7Oc9oT7lehsUqShYgXwWO3Gx8oSxs6pIZk6YzCTW6OnWCap5hLICvMAzIDd"/>
<div class="absolute top-4 left-4 border border-outline px-2 py-1 bg-background">
<span class="font-label-caps text-label-caps text-primary">STUDIO PICK</span>
</div>
</div>
<h3 class="font-body-lg text-body-lg text-primary mb-1">HARE 建築感西裝外套</h3>
<p class="font-body-md text-body-md text-outline">TWD 18,500</p>
</article>
<!-- Product Card 2 -->
<article class="group cursor-pointer">
<div class="w-full aspect-[3/4] bg-surface-container-low mb-4 overflow-hidden">
<img alt="Folded shirt with intricate pleats" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105 filter grayscale" data-alt="A close-up, monochromatic fashion shot focusing on an innovative white shirt with complex, origami-like pleating and folding details. The shirt hangs fluidly against a stark grey studio backdrop. The lighting highlights the crisp ridges and deep shadows of the folds, conveying a sense of meticulous craftsmanship and modern minimalism." src="https://lh3.googleusercontent.com/aida-public/AB6AXuAnROvGIi3txG2hkTL02AerAcyuxA0wtn-S8bhuJRAAq-MrSrTTariiTvJ3BUMfJzlYQrUEoGemSzNzAK1wv_3OtcNIggVdVc1-hPOczYED73TC5jDEmU4cC_wFY2X6UpErJ-8OjWcbs19WnGnaeSlirRnhUbKB_EhP6fsikWmsvw0toWNh400VWjEesxnSzin1uy9VflLhVuWrj8p4fcPBcy8MdJDnp1UeEhrRGCKbZUXCmnqPqbqhwk425cGH25OmNEVVINcjKaOU"/>
</div>
<h3 class="font-body-lg text-body-lg text-primary mb-1">AIR 摺縐概念襯衫</h3>
<p class="font-body-md text-body-md text-outline">TWD 8,200</p>
</article>
<!-- Product Card 3 -->
<article class="group cursor-pointer">
<div class="w-full aspect-[3/4] bg-surface-container-low mb-4 overflow-hidden">
<img alt="Wide leg structural trousers" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" data-alt="Full body shot of a model walking purposefully, wearing extremely wide-leg, structural black trousers made of heavy cotton. The movement captures the architectural drape of the pants. Shot in a minimalist concrete studio setting with a clean, high-fashion editorial vibe. The monochromatic color palette emphasizes form over color." src="https://lh3.googleusercontent.com/aida-public/AB6AXuCqrqN-khDt-lSyZuiNaJMnDX38WoF1olW_TWynGK-tAsx9TxGJfnfz4t0iEQhGwZRufCkl7TpwyMBNO7g4HDYx7tzc-l4ieOuflIlFf3Z_K1PKsLm43_4k5s4l8qF_tdEXaC2klT1A05vKsPU6EyU8r671UX3OKulLsd7XoSQeKbXB4wLrV66gJUDnh6OEzlTFPBOtMjj6IqdFCnKJ4f7vl861iLQZ5i0vDsOzABeBMADaOmLZadoyjfGEn3bY7mH3NootUnrf6u11"/>
</div>
<h3 class="font-body-lg text-body-lg text-primary mb-1">解構寬版休閒褲</h3>
<p class="font-body-md text-body-md text-outline">TWD 12,000</p>
</article>
</div>
</div>
</div>
</div>
</main>
<!-- Mid-page Banner -->
<section class="w-full bg-primary text-on-primary py-24 my-section-gap relative overflow-hidden">
<div class="max-w-container-max-width mx-auto px-margin-desktop flex flex-col md:flex-row justify-between items-center relative z-10">
<div class="md:w-1/2">
<h2 class="font-display-xl text-display-xl mb-4 tracking-tighter">AIR SPEED DELIVERY.</h2>
<p class="font-body-lg text-body-lg max-w-md text-outline-variant">全球物流網絡同步啟動。享受精準、迅速的極致配送服務，將 HARE 建築美學零時差送達。</p>
</div>
<div class="mt-8 md:mt-0 flex gap-4">
<button class="border border-on-primary text-on-primary px-8 py-4 font-nav-link text-nav-link uppercase tracking-widest hover:bg-on-primary hover:text-primary transition-colors">了解更多</button>
</div>
</div>
<!-- Decorative geometric background element for the banner -->
<div class="absolute right-0 top-0 w-1/2 h-full opacity-10 flex items-center justify-end pointer-events-none">
<span class="material-symbols-outlined text-[400px] leading-none" data-icon="deployed_code">deployed_code</span>
</div>
</section>
<!-- Section 2: Men's Trend (Asymmetric Bento Grid) -->
<main class="max-w-container-max-width mx-auto px-margin-desktop pb-section-gap">
<div class="grid grid-cols-12 gap-gutter">
<div class="col-span-12 md:col-start-4 md:col-span-9">
<h2 class="font-headline-lg text-headline-lg text-primary mb-8 border-b border-outline-variant pb-4">男裝趨勢 <span class="font-body-md text-outline ml-4 uppercase tracking-widest text-sm">Men's Trend</span></h2>
<div class="grid grid-cols-12 gap-gutter">
<!-- Feature Large Image -->
<article class="col-span-12 md:col-span-8 group cursor-pointer relative">
<div class="w-full aspect-[4/3] bg-surface-container-low mb-4 overflow-hidden">
<img alt="Men's oversized trench coat" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" data-alt="A striking editorial fashion photograph of a male model wearing an oversized, technical fabric trench coat in deep charcoal. The coat features utilitarian details and an asymmetrical collar. Shot from a low angle to emphasize authority and structure. The background is a stark, textured concrete wall, reflecting an industrial, avant-garde design ethos." src="https://lh3.googleusercontent.com/aida-public/AB6AXuBoNlcNH27kPso5TMn7OF27mn5CeCzN0FMPHICCx4eY0HE3nOZHBmvl_IEFg1QZIN8B7Ou8wkRXEjoiB6T4XrYOav3rrGhVNqkVNlWbJ8K3rS3UkLI29qoYrC2lkmU-HJbMJJLbXzcaIdNUdenbWf7YxAj2nIrA1XFEoYeKsjTXsfwAhIh5PES7wexDL9VPzLUUNnd9IIAeWdktDFPLoOb0SVvUP7PlPZ-8HbUiNoo0z2xedGUe13aG1Lo6YMixjZdyGGyYB2TPdC03"/>
</div>
<div class="flex justify-between items-start">
<div>
<h3 class="font-body-lg text-body-lg text-primary mb-1">機能防風大衣 (實驗室系列)</h3>
<p class="font-body-md text-body-md text-outline">TWD 24,800</p>
</div>
<span class="border border-primary px-3 py-1 font-label-caps text-label-caps">NEW ARRIVAL</span>
</div>
</article>
<!-- Two smaller stacked items -->
<div class="col-span-12 md:col-span-4 flex flex-col gap-gutter">
<article class="group cursor-pointer">
<div class="w-full aspect-square bg-surface-container-low mb-4 overflow-hidden">
<img alt="Minimalist men's t-shirt" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105 filter grayscale" data-alt="Detail shot of a men's heavy cotton t-shirt with a structured, raised neckline. The fabric texture is clearly visible under sharp, high-key studio lighting. The image is strictly black and white, focusing on the geometry of the collar and the precise stitching. Minimalist and stark." src="https://lh3.googleusercontent.com/aida-public/AB6AXuB8uy442Vel1DgGQnDbPCyBOEY_uuOYLuJkiNBJ8VCL6cTwl-tHyUANAGeyJ9_n57Pl8x_YRk1dNLbw9FN0idnd6QQ-4hnglEUXQ-FWBAkmbtHOz4hHOR2QYMkJ0wJTU1wRJxgdb-90EGAcUeGuQxzQv08ZQ1xI3Gj7RaghLRScNWcwYqk3NsrBInQakfZf2hIK1JncDMx1HKXwOJUWyS2zjanP8npifWD5KfKCSP6kciRFhiD8m-8xGpYv2-CmVql5nH4NpGizJ2_X"/>
</div>
<h3 class="font-body-lg text-body-lg text-primary mb-1">立領重磅短T</h3>
<p class="font-body-md text-body-md text-outline">TWD 4,500</p>
</article>
<article class="group cursor-pointer">
<div class="w-full aspect-square bg-surface-container-low mb-4 overflow-hidden flex items-center justify-center border border-outline-variant p-6">
<!-- Simulated technical drawing/accessory placeholder -->
<div class="text-center">
<span class="material-symbols-outlined text-4xl text-outline mb-2 block" data-icon="architecture">architecture</span>
<h3 class="font-body-md text-body-md text-primary mb-1">查看結構圖紙</h3>
<p class="font-label-caps text-label-caps text-outline border-b border-outline inline-block">VIEW BLUEPRINTS</p>
</div>
</div>
</article>
</div>
</div>
</div>
</div>
</main>
<!-- Footer Shared Component -->
<footer class="w-full mt-section-gap bg-surface-container border-t border-outline-variant">
<div class="grid grid-cols-12 gap-gutter px-margin-desktop py-section-gap max-w-container-max-width mx-auto">
<!-- Brand Logo Area -->
<div class="col-span-12 md:col-span-4 mb-8 md:mb-0">
<span class="font-headline-md text-headline-md font-bold text-primary block mb-4">HARE AIR STUDIO</span>
<p class="font-body-md text-body-md text-on-surface-variant max-w-xs">Intersecting avant-garde fashion with precise logistical execution.</p>
</div>
<!-- Links Area -->
<div class="col-span-12 md:col-span-8 grid grid-cols-2 md:grid-cols-3 gap-8">
<div class="flex flex-col gap-4">
<a class="font-body-md text-body-md text-on-surface-variant hover:underline decoration-1 underline-offset-4 transition-opacity duration-200" href="#">PRIVACY POLICY</a>
<a class="font-body-md text-body-md text-on-surface-variant hover:underline decoration-1 underline-offset-4 transition-opacity duration-200" href="#">TERMS OF SERVICE</a>
</div>
<div class="flex flex-col gap-4">
<a class="font-body-md text-body-md text-on-surface-variant hover:underline decoration-1 underline-offset-4 transition-opacity duration-200" href="#">SHIPPING &amp; RETURNS</a>
<a class="font-body-md text-body-md text-on-surface-variant hover:underline decoration-1 underline-offset-4 transition-opacity duration-200" href="#">CONTACT</a>
</div>
<div class="flex flex-col gap-4">
<a class="font-body-md text-body-md text-on-surface-variant hover:underline decoration-1 underline-offset-4 transition-opacity duration-200" href="#">INSTAGRAM</a>
<a class="font-body-md text-body-md text-on-surface-variant hover:underline decoration-1 underline-offset-4 transition-opacity duration-200" href="#">TWITTER</a>
</div>
</div>
<!-- Copyright -->
<div class="col-span-12 border-t border-outline-variant mt-16 pt-8">
<p class="font-body-md text-body-md text-on-surface-variant">© 2024 HARE AIR STUDIO. ALL RIGHTS RESERVED.</p>
</div>
</div>
</footer>
</body></html>

<!-- 穿搭工作室 - HARE Air Studio (繁中) Desktop v2 -->
<!DOCTYPE html>

<html lang="zh-TW"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>HARE AIR STUDIO - 工作室教學</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Bodoni+Moda:ital,opsz,wght@0,6..96,400..900;1,6..96,400..900&amp;family=Hanken+Grotesk:ital,wght@0,100..900;1,100..900&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "surface-container-low": "#f3f3f3",
                        "outline-variant": "#c4c7c7",
                        "inverse-surface": "#2f3131",
                        "surface-tint": "#5f5e5e",
                        "on-tertiary-fixed": "#1a1c1c",
                        "tertiary-container": "#1a1c1c",
                        "surface-variant": "#e2e2e2",
                        "on-tertiary-container": "#838484",
                        "primary-fixed": "#e5e2e1",
                        "on-primary": "#ffffff",
                        "secondary-fixed-dim": "#b2cad7",
                        "on-primary-fixed-variant": "#474646",
                        "error-container": "#ffdad6",
                        "on-surface-variant": "#444748",
                        "primary-container": "#1c1b1b",
                        "inverse-primary": "#c8c6c5",
                        "surface-container-highest": "#e2e2e2",
                        "surface-container": "#eeeeee",
                        "outline": "#747878",
                        "primary-fixed-dim": "#c8c6c5",
                        "on-secondary-fixed": "#051e28",
                        "surface-container-lowest": "#ffffff",
                        "on-secondary-fixed-variant": "#334a54",
                        "on-surface": "#1a1c1c",
                        "on-primary-fixed": "#1c1b1b",
                        "background": "#f9f9f9",
                        "inverse-on-surface": "#f1f1f1",
                        "tertiary": "#000000",
                        "secondary-container": "#cbe3f0",
                        "primary": "#000000",
                        "surface-bright": "#f9f9f9",
                        "surface": "#f9f9f9",
                        "tertiary-fixed-dim": "#c6c6c6",
                        "surface-container-high": "#e8e8e8",
                        "on-tertiary-fixed-variant": "#454747",
                        "surface-dim": "#dadada",
                        "on-primary-container": "#858383",
                        "secondary-fixed": "#cee6f3",
                        "secondary": "#4b626d",
                        "on-secondary": "#ffffff",
                        "on-error-container": "#93000a",
                        "on-background": "#1a1c1c",
                        "error": "#ba1a1a",
                        "on-secondary-container": "#4f6671",
                        "tertiary-fixed": "#e2e2e2",
                        "on-tertiary": "#ffffff",
                        "on-error": "#ffffff"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.25rem",
                        "lg": "0.5rem",
                        "xl": "0.75rem",
                        "full": "9999px"
                    },
                    "spacing": {
                        "margin-desktop": "64px",
                        "gutter": "24px",
                        "container-max-width": "1440px",
                        "unit": "8px",
                        "section-gap": "128px",
                        "margin-mobile": "20px"
                    },
                    "fontFamily": {
                        "nav-link": ["Hanken Grotesk"],
                        "label-caps": ["Hanken Grotesk"],
                        "display-xl-mobile": ["Bodoni Moda"],
                        "headline-lg": ["Bodoni Moda"],
                        "headline-lg-mobile": ["Bodoni Moda"],
                        "body-md": ["Hanken Grotesk"],
                        "body-lg": ["Hanken Grotesk"],
                        "display-xl": ["Bodoni Moda"],
                        "headline-md": ["Bodoni Moda"]
                    },
                    "fontSize": {
                        "nav-link": ["14px", { "lineHeight": "20px", "letterSpacing": "0.05em", "fontWeight": "500" }],
                        "label-caps": ["12px", { "lineHeight": "16px", "letterSpacing": "0.1em", "fontWeight": "700" }],
                        "display-xl-mobile": ["48px", { "lineHeight": "56px", "letterSpacing": "-0.02em", "fontWeight": "600" }],
                        "headline-lg": ["40px", { "lineHeight": "48px", "fontWeight": "500" }],
                        "headline-lg-mobile": ["32px", { "lineHeight": "40px", "fontWeight": "500" }],
                        "body-md": ["16px", { "lineHeight": "24px", "fontWeight": "400" }],
                        "body-lg": ["18px", { "lineHeight": "28px", "fontWeight": "400" }],
                        "display-xl": ["72px", { "lineHeight": "80px", "letterSpacing": "-0.02em", "fontWeight": "600" }],
                        "headline-md": ["24px", { "lineHeight": "32px", "fontWeight": "500" }]
                    }
                }
            }
        }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        .slider-overlay {
            clip-path: inset(0 50% 0 0);
            transition: clip-path 0.1s ease-out;
        }
    </style>
</head>
<body class="bg-background text-on-background antialiased selection:bg-primary selection:text-on-primary">
<!-- TopNavBar -->
<header class="w-full top-0 left-0 border-b border-outline-variant bg-background z-50 sticky">
<div class="flex justify-between items-center w-full px-margin-desktop py-unit max-w-container-max-width mx-auto">
<div class="flex-1 flex gap-8 items-center hidden md:flex">
<a class="font-nav-link text-nav-link text-on-surface-variant hover:text-secondary transition-colors cursor-pointer active:opacity-70 uppercase tracking-widest" href="#">COLLECTIONS</a>
<a class="font-nav-link text-nav-link text-primary border-b-2 border-primary pb-1 hover:text-secondary transition-colors cursor-pointer active:opacity-70 uppercase tracking-widest" href="#">STUDIO</a>
<a class="font-nav-link text-nav-link text-on-surface-variant hover:text-secondary transition-colors cursor-pointer active:opacity-70 uppercase tracking-widest" href="#">LOGISTICS</a>
<a class="font-nav-link text-nav-link text-on-surface-variant hover:text-secondary transition-colors cursor-pointer active:opacity-70 uppercase tracking-widest" href="#">ARCHIVE</a>
<a class="font-nav-link text-nav-link text-on-surface-variant hover:text-secondary transition-colors cursor-pointer active:opacity-70 uppercase tracking-widest" href="#">STORES</a>
</div>
<a class="font-display-xl text-headline-md tracking-tighter text-primary whitespace-nowrap" href="/">HARE AIR STUDIO</a>
<div class="flex-1 flex justify-end items-center gap-4">
<button class="text-on-surface-variant hover:text-primary transition-colors">
<span class="material-symbols-outlined">search</span>
</button>
<button class="text-on-surface-variant hover:text-primary transition-colors">
<span class="material-symbols-outlined">shopping_bag</span>
</button>
</div>
</div>
</header>
<main>
<!-- Hero Section -->
<section class="relative w-full h-[819px] bg-surface-container flex items-center justify-center overflow-hidden">
<img alt="工作室教學" class="absolute inset-0 w-full h-full object-cover opacity-60 mix-blend-multiply grayscale" data-alt="A high-contrast, minimalist fashion studio setting. Stark white background with architectural lighting. A single model in avant-garde black garments stands in the distance. The mood is precise, professional, and slightly sterile, evoking a digital luxury lookbook aesthetic. High-key lighting emphasizes sharp silhouettes." src="https://lh3.googleusercontent.com/aida-public/AB6AXuDZF3KJQEu8Tl0r9TSSc8KPlOFH6fEwSgTas3K4KOe_LXEVavBlFQUshz7_AKkDiD_V6tajIGWEWWAOQPuVVSBqrSeXZc2UgdS4j4aY8hl62GRHbeq96Q_5Fzf4ab9rnuuQi8d5RNBRKNR2Z7-UHKs96OyxtVJ1gu14bz9gfhz_GVae0q3CqwVDWiURRnPBdM7oVbDKvhESf098Q-cO6rRTdnpLfFQuJkBI6FDxggrz4C51EE7NSMrMg8egsuH5wbo98bLHoIf6xx7n"/>
<div class="relative z-10 text-center px-margin-desktop">
<h1 class="font-display-xl text-display-xl text-primary mb-6">工作室教學</h1>
<p class="font-body-lg text-body-lg text-on-surface-variant max-w-2xl mx-auto mb-10">探索我們對於高級服裝結構、比例與造型的獨到見解。精準、結構化、純粹。</p>
<button class="bg-primary text-on-primary font-label-caps text-label-caps px-8 py-4 uppercase tracking-widest hover:bg-secondary transition-colors rounded-none">
                    預約虛擬諮詢
                </button>
</div>
</section>
<!-- Lesson Modules Grid -->
<section class="max-w-container-max-width mx-auto px-margin-desktop py-section-gap">
<div class="grid grid-cols-1 md:grid-cols-12 gap-gutter">
<!-- Module 1 -->
<div class="md:col-span-4 group cursor-pointer">
<div class="aspect-[3/4] mb-6 overflow-hidden bg-surface-container relative border border-outline-variant">
<img alt="01 理解比例" class="w-full h-full object-cover grayscale group-hover:grayscale-0 transition-all duration-500" data-alt="Close-up of avant-garde fashion garments showing complex structural proportions. Minimalist white background, stark studio lighting highlighting the texture of black wool and stiff cotton. The composition is highly structured and architectural." src="https://lh3.googleusercontent.com/aida-public/AB6AXuBpPogkkZtKmgESps2BT3Q3X3Wb0cQIhgcYe6UaG7neXXs9eHNlGL8TschLV4Dr6UqQdGPrBZHfZeiqRlSqsRinmU7S75VXMtPwkgnR2Mz_8iVlMbk2QVIgRuc_K-O1u-ewS9rVnqnW6bC_QAH56OeOjuYes6U3JzDWxAkCKCUpO3Ta2K5GaG5cqHUJ1cbGV2xYA_6GvEjKt7QT3bmhThmL5miXT4NocSLM9S726tHJIwph642wGgEzBeuaZ8ffNaZVPoRnAG_AkQhy"/>
</div>
<h3 class="font-headline-md text-headline-md text-primary mb-2">01 理解比例</h3>
<p class="font-body-md text-body-md text-on-surface-variant">探討服裝剪裁與人體結構的對話，建立強烈的視覺平衡。</p>
</div>
<!-- Module 2 -->
<div class="md:col-span-4 group cursor-pointer md:mt-16">
<div class="aspect-[3/4] mb-6 overflow-hidden bg-surface-container relative border border-outline-variant">
<img alt="02 質地的並置" class="w-full h-full object-cover grayscale group-hover:grayscale-0 transition-all duration-500" data-alt="Macro photography of contrasting fabric textures. Smooth silk placed next to rough, heavy tweed. Strict monochrome palette with harsh directional lighting creating sharp shadows. Minimalist and technical aesthetic." src="https://lh3.googleusercontent.com/aida-public/AB6AXuDPk8uEfHjyivywSQkEiv1v-8mnsYueYEiU6e0NQk8st0uyh_Aamxtdch0BmbUfyq2tkELQ6zpF4iYL8Wc2ifYVgwS-VTtrX9bbRSYVvol_56hjeWku4W0plZzAp_diH8AjY53RyW3Cw6QXykSK0qF_ie2lbFdwBU1mNDvqb5KrHqNI7Sds6xdcnwTo-nvMO90QSvJj82CeyaePmTk8DcZ-MNV5Lh20yclqHYityS3i4W13SzfTHl6Pn4DFZ9EnU2bgWYj7baL2iYXo"/>
</div>
<h3 class="font-headline-md text-headline-md text-primary mb-2">02 質地的並置</h3>
<p class="font-body-md text-body-md text-on-surface-variant">學習如何在單一造型中，透過對比面料創造深度與情緒。</p>
</div>
<!-- Module 3 -->
<div class="md:col-span-4 group cursor-pointer">
<div class="aspect-[3/4] mb-6 overflow-hidden bg-surface-container relative border border-outline-variant">
<img alt="03 鞋履整合" class="w-full h-full object-cover grayscale group-hover:grayscale-0 transition-all duration-500" data-alt="Avant-garde black leather boots shot against a stark, minimalist concrete floor and white background. High-contrast lighting, technical framing, emphasizing the structural design of the footwear in a luxury fashion context." src="https://lh3.googleusercontent.com/aida-public/AB6AXuA14onDuSwn_lmZUhelFk95PfNPkGLeI0uCYqDiR-DDunnL0m94KXZEtxw9rE9Kp87Vmy6vFOdfRTc3NGLGBm21VFmv971lkkUl2R0lTBJXMQJnvSPWLkGq8Eat8cam839bzzrLPmD3YO4ijKRCV5cp-3hNXfrcZXLYFVKyntZitBq4HksiZJnKKCMHFVGLc5v4_I1j374fI0CmU5kQKmPiCtBAFoSxlEOfuoMMPC-qi0zN3p3ooUyLYsxwqlAHblutY2eIdeiz5pKY"/>
</div>
<h3 class="font-headline-md text-headline-md text-primary mb-2">03 鞋履整合</h3>
<p class="font-body-md text-body-md text-on-surface-variant">將鞋履視為造型的建築基礎，錨定整體的視覺重量。</p>
</div>
</div>
</section>
<!-- Feature Sections -->
<section class="border-t border-outline-variant">
<div class="max-w-container-max-width mx-auto px-margin-desktop py-section-gap">
<!-- Feature 1: Menswear -->
<div class="grid grid-cols-1 md:grid-cols-12 gap-gutter items-center mb-section-gap">
<div class="md:col-span-5 order-2 md:order-1">
<span class="inline-block border border-outline px-3 py-1 font-label-caps text-label-caps mb-6 uppercase tracking-widest text-on-surface-variant">Studio Pick</span>
<h2 class="font-headline-lg text-headline-lg text-primary mb-6">男裝：趨勢報告</h2>
<p class="font-body-lg text-body-lg text-on-surface-variant mb-8">解構當季剪裁輪廓。我們分析了機能性與傳統西裝的融合，提供精準的實用主義穿搭指南。拒絕多餘，專注本質。</p>
<button class="bg-transparent border border-primary text-primary font-label-caps text-label-caps px-6 py-3 uppercase tracking-widest hover:bg-surface-container-low transition-colors rounded-none">
                            閱讀報告
                        </button>
</div>
<div class="md:col-span-6 md:col-start-7 order-1 md:order-2 mb-10 md:mb-0">
<div class="aspect-[4/3] bg-surface-container border border-outline-variant">
<img alt="男裝趨勢" class="w-full h-full object-cover grayscale" data-alt="Editorial shot of a male model wearing structured, oversized black tailoring. Minimalist concrete and steel environment. Cold, crisp lighting emphasizing sharp lines and architectural silhouettes. The mood is austere and highly professional." src="https://lh3.googleusercontent.com/aida-public/AB6AXuCPF0FaZP94r3lsSl_gvdl7fEhzu_EhhziFtIf5Tr4jDdFId0rssuIDPxzYSO76qMcUd5yakoL_s1BhODt84HlFVTV5L8SaS7vFzZ9XlfpIQiP3g45DXys7qQ65IrVCf99Zjq1TACNlkYan9BOM7tvFDVVsSfYeRTiVwpT0jORDnvdPLBkEfp6Rt-8DC18jByu2wfs4OqIPWWT9-BSLPzo3nJi_1EBnEs4dGZBbHYaer5ytb8yGNqieIeEcudPutBxBddTsufpv6tPd"/>
</div>
</div>
</div>
<!-- Feature 2: Womenswear -->
<div class="grid grid-cols-1 md:grid-cols-12 gap-gutter items-center">
<div class="md:col-span-6 mb-10 md:mb-0">
<div class="aspect-[4/3] bg-surface-container border border-outline-variant">
<img alt="女裝精髓" class="w-full h-full object-cover grayscale" data-alt="Editorial photography of a female model in draped, asymmetrical minimalist garments. Stark white studio background with dramatic, high-contrast shadows. The styling is avant-garde, emphasizing volume and precise, clean cuts." src="https://lh3.googleusercontent.com/aida-public/AB6AXuCxQ0aOHoaPXJERrp3_IX0vYtxdrT1xKH_e4ZQHhFhk-oQf5IrJe3kkfPoBu_V8H6FInSZAJy6n9bxTFRQJmRtlwmy6Nm7Q_KPaGJg3DK_jpA4MYHo8Kq1vf67dR324_5NRXks4yvB1w0W74fpy1AXdU5saehq8h9evM9gEnEMQFrLU5CTOTy07WY14O7Uw9X35cFQbkGSx82HJt3WXc-5aY_xMT66JKWhxynyE6etJVXSJonlFLqJRN7ZWBYMFZrVMAC-VC7Ogd6gP"/>
</div>
</div>
<div class="md:col-span-5 md:col-start-8">
<span class="inline-block border border-outline px-3 py-1 font-label-caps text-label-caps mb-6 uppercase tracking-widest text-on-surface-variant">Editorial</span>
<h2 class="font-headline-lg text-headline-lg text-primary mb-6">女裝：法式精髓</h2>
<p class="font-body-lg text-body-lg text-on-surface-variant mb-8">重新定義毫不費力的優雅。透過建築般的幾何線條與高級面料的垂墜感，我們呈現一種極簡而具備力量的現代女性形象。</p>
<button class="bg-transparent border border-primary text-primary font-label-caps text-label-caps px-6 py-3 uppercase tracking-widest hover:bg-surface-container-low transition-colors rounded-none">
                            探索特輯
                        </button>
</div>
</div>
</div>
</section>
<!-- Technical Blueprint Slider Section -->
<section class="bg-primary text-on-primary py-section-gap">
<div class="max-w-container-max-width mx-auto px-margin-desktop text-center mb-16">
<h2 class="font-headline-lg text-headline-lg mb-4">藍圖滑塊</h2>
<p class="font-body-md text-body-md text-on-primary-container max-w-xl mx-auto">從概念草圖到最終成衣。拖曳滑桿以檢視服裝的內部建築結構與技術細節。</p>
</div>
<div class="max-w-4xl mx-auto px-margin-desktop">
<div class="relative aspect-video bg-surface-container-lowest border border-outline-variant select-none overflow-hidden" id="blueprint-container">
<!-- Base Image (Technical Drawing) -->
<img alt="Technical Drawing" class="absolute inset-0 w-full h-full object-cover pointer-events-none filter sepia hue-rotate-180 brightness-50" data-alt="Technical architectural blueprint style drawing of a complex garment pattern. White lines on a dark blue/grey background. Precise technical aesthetic, grid lines, measurements, and structural notations. Highly detailed and sterile." src="https://lh3.googleusercontent.com/aida-public/AB6AXuDFASvuvebKrT65SQt6L2wIgyg-qSAX8JCU4UKLAdxGhwUYoyrfs-_FD1LPHHdenMtP4pdpWmVLvU8yIQ45yc5h1Sbbqr-rOGJ4RbzfpYR0uVRcWcR6goBK2YuQAS2SVxSntOQOggMTB-KWbRlLdEsFyraR9t7hFOMqKbKvXDIA8L5s5jXsC2sPaoZkamcy4YoJm6XFhcwxSdL19goMwkTFrlmGj1KMusOy1_Hqf7PnJs1ts-fmqR5a68GAYKbtmWPvlFLdmrNouTcm"/>
<!-- Overlay Image (Final Photography) -->
<img alt="Final Garment" class="absolute inset-0 w-full h-full object-cover pointer-events-none slider-overlay grayscale" data-alt="Final editorial photography of the garment constructed from the blueprint. A sharp, minimalist winter coat shown against a clean studio background. High-end fashion aesthetic, stark black and white composition." id="blueprint-overlay" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCrdRUktX6ei2aYiNgD_E9uiI2UtOsX2BLyqPu-8mUPVWXNnj8CViTEmmTZy6exKRcy270JPT5CuTcm-0CN0SFiLXnMhEBVe0l0wYSVItIMbzbS5J-7p5uSSegcnHWf3iSXPvDYvtpQRTd1VJF5vKiruc5EAiAVAEHYrP2yNR_0-_-7o9XTP1Mbd-1CrMD34-iB7uvCI1Y52fHz0u9ce1yoC41jXPOxZ20lpGqQ3g4aEhzgcrTcUejBfNhPV1X-ctsakTaM5qkaUiyz"/>
<!-- Slider Control -->
<input class="absolute inset-0 w-full h-full opacity-0 cursor-ew-resize z-20" id="blueprint-slider" max="100" min="0" type="range" value="50"/>
<!-- Slider Visual Handle -->
<div class="absolute top-0 bottom-0 w-px bg-on-primary z-10 pointer-events-none left-1/2 flex items-center justify-center -ml-px" id="blueprint-handle">
<div class="w-8 h-8 rounded-full border-2 border-on-primary bg-primary flex items-center justify-center">
<span class="material-symbols-outlined text-[16px]">code</span>
</div>
</div>
</div>
</div>
</section>
</main>
<!-- Footer -->
<footer class="w-full mt-section-gap border-t border-outline-variant bg-surface-container">
<div class="grid grid-cols-1 md:grid-cols-12 gap-gutter px-margin-desktop py-section-gap max-w-container-max-width mx-auto">
<div class="md:col-span-4 flex flex-col justify-between mb-10 md:mb-0">
<a class="font-headline-md text-headline-md font-bold text-primary mb-6 block" href="/">HARE AIR STUDIO</a>
<p class="font-body-md text-body-md text-on-surface-variant uppercase text-xs tracking-widest mt-auto">© 2024 HARE AIR STUDIO. ALL RIGHTS RESERVED.</p>
</div>
<div class="md:col-span-2 md:col-start-7">
<ul class="flex flex-col gap-4 font-body-md text-body-md">
<li><a class="text-on-surface-variant hover:underline decoration-1 underline-offset-4 transition-opacity duration-200" href="#">PRIVACY POLICY</a></li>
<li><a class="text-on-surface-variant hover:underline decoration-1 underline-offset-4 transition-opacity duration-200" href="#">TERMS OF SERVICE</a></li>
<li><a class="text-on-surface-variant hover:underline decoration-1 underline-offset-4 transition-opacity duration-200" href="#">SHIPPING &amp; RETURNS</a></li>
</ul>
</div>
<div class="md:col-span-2 md:col-start-10">
<ul class="flex flex-col gap-4 font-body-md text-body-md">
<li><a class="text-on-surface-variant hover:underline decoration-1 underline-offset-4 transition-opacity duration-200" href="#">CONTACT</a></li>
<li><a class="text-on-surface-variant hover:underline decoration-1 underline-offset-4 transition-opacity duration-200" href="#">INSTAGRAM</a></li>
<li><a class="text-on-surface-variant hover:underline decoration-1 underline-offset-4 transition-opacity duration-200" href="#">TWITTER</a></li>
</ul>
</div>
</div>
</footer>
<script>
        // Blueprint Slider Logic
        document.addEventListener('DOMContentLoaded', () => {
            const slider = document.getElementById('blueprint-slider');
            const overlay = document.getElementById('blueprint-overlay');
            const handle = document.getElementById('blueprint-handle');

            if(slider && overlay && handle) {
                slider.addEventListener('input', (e) => {
                    const value = e.target.value;
                    overlay.style.clipPath = `inset(0 ${100 - value}% 0 0)`;
                    handle.style.left = `${value}%`;
                });
            }
        });
    </script>
</body></html>

<!-- 穿搭工作室 - HARE Air Studio (繁中) Mobile v2 -->
<!DOCTYPE html>

<html class="light" lang="zh-Hant"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Hanken+Grotesk:wght@400;500;700&amp;family=Bodoni+Moda:ital,wght@0,400;0,500;0,600;1,400&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            "colors": {
                    "tertiary": "#000000",
                    "surface-dim": "#dadada",
                    "outline-variant": "#c4c7c7",
                    "outline": "#747878",
                    "on-surface-variant": "#444748",
                    "on-primary-container": "#858383",
                    "inverse-on-surface": "#f1f1f1",
                    "inverse-primary": "#c8c6c5",
                    "on-primary-fixed": "#1c1b1b",
                    "surface-bright": "#f9f9f9",
                    "on-tertiary-fixed-variant": "#454747",
                    "on-secondary-container": "#4f6671",
                    "primary-fixed-dim": "#c8c6c5",
                    "on-primary": "#ffffff",
                    "on-error-container": "#93000a",
                    "surface-container-lowest": "#ffffff",
                    "on-surface": "#1a1c1c",
                    "secondary-container": "#cbe3f0",
                    "on-secondary-fixed": "#051e28",
                    "tertiary-fixed-dim": "#c6c6c6",
                    "on-tertiary-container": "#838484",
                    "on-tertiary-fixed": "#1a1c1c",
                    "inverse-surface": "#2f3131",
                    "on-secondary": "#ffffff",
                    "on-secondary-fixed-variant": "#334a54",
                    "surface-variant": "#e2e2e2",
                    "on-tertiary": "#ffffff",
                    "error-container": "#ffdad6",
                    "surface-container-high": "#e8e8e8",
                    "surface": "#f9f9f9",
                    "surface-container-highest": "#e2e2e2",
                    "secondary-fixed-dim": "#b2cad7",
                    "background": "#f9f9f9",
                    "error": "#ba1a1a",
                    "tertiary-fixed": "#e2e2e2",
                    "primary-fixed": "#e5e2e1",
                    "tertiary-container": "#1a1c1c",
                    "surface-container": "#eeeeee",
                    "surface-container-low": "#f3f3f3",
                    "secondary": "#4b626d",
                    "primary-container": "#1c1b1b",
                    "on-background": "#1a1c1c",
                    "surface-tint": "#5f5e5e",
                    "primary": "#000000",
                    "on-error": "#ffffff",
                    "on-primary-fixed-variant": "#474646",
                    "secondary-fixed": "#cee6f3"
            },
            "borderRadius": {
                    "DEFAULT": "0.25rem",
                    "lg": "0.5rem",
                    "xl": "0.75rem",
                    "full": "9999px"
            },
            "spacing": {
                    "margin-desktop": "64px",
                    "section-gap": "128px",
                    "container-max-width": "1440px",
                    "gutter": "24px",
                    "unit": "8px",
                    "margin-mobile": "20px"
            },
            "fontFamily": {
                    "label-caps": ["Hanken Grotesk"],
                    "headline-md": ["Bodoni Moda"],
                    "body-lg": ["Hanken Grotesk"],
                    "display-xl-mobile": ["Bodoni Moda"],
                    "display-xl": ["Bodoni Moda"],
                    "headline-lg": ["Bodoni Moda"],
                    "body-md": ["Hanken Grotesk"],
                    "nav-link": ["Hanken Grotesk"],
                    "headline-lg-mobile": ["Bodoni Moda"]
            },
            "fontSize": {
                    "label-caps": ["12px", {"lineHeight": "16px", "letterSpacing": "0.1em", "fontWeight": "700"}],
                    "headline-md": ["24px", {"lineHeight": "32px", "fontWeight": "500"}],
                    "body-lg": ["18px", {"lineHeight": "28px", "fontWeight": "400"}],
                    "display-xl-mobile": ["48px", {"lineHeight": "56px", "letterSpacing": "-0.02em", "fontWeight": "600"}],
                    "display-xl": ["72px", {"lineHeight": "80px", "letterSpacing": "-0.02em", "fontWeight": "600"}],
                    "headline-lg": ["40px", {"lineHeight": "48px", "fontWeight": "500"}],
                    "body-md": ["16px", {"lineHeight": "24px", "fontWeight": "400"}],
                    "nav-link": ["14px", {"lineHeight": "20px", "letterSpacing": "0.05em", "fontWeight": "500"}],
                    "headline-lg-mobile": ["32px", {"lineHeight": "40px", "fontWeight": "500"}]
            }
          },
        },
      }
    </script>
<style>
        body {
            background-color: #f9f9f9;
            color: #1a1c1c;
            -webkit-font-smoothing: antialiased;
        }
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 300, 'GRAD' 0, 'opsz' 24;
        }
        .blueprint-grid {
            background-image: 
                linear-gradient(to right, #e2e2e2 1px, transparent 1px),
                linear-gradient(to bottom, #e2e2e2 1px, transparent 1px);
            background-size: 40px 40px;
        }
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
</head>
<body class="font-body-md text-body-md overflow-x-hidden">
<!-- TopAppBar -->
<header class="fixed top-0 z-[60] w-full bg-surface dark:bg-tertiary flex justify-between items-center px-margin-mobile md:px-margin-desktop h-16 border-b border-outline-variant dark:border-on-surface-variant">
<div class="flex items-center gap-4">
<button class="text-primary dark:text-on-primary hover:opacity-80 transition-opacity Active: scale-95 transition-transform duration-200">
<span class="material-symbols-outlined">menu</span>
</button>
<h1 class="font-headline-md text-headline-md font-bold tracking-tighter text-primary dark:text-on-primary">HARE AIR STUDIO</h1>
</div>
<div class="flex items-center gap-6">
<nav class="hidden md:flex gap-8">
<a class="font-label-caps text-label-caps text-outline hover:text-primary transition-colors" href="#">系列收藏</a>
<a class="font-label-caps text-label-caps text-primary border-b border-primary" href="#">工作室</a>
<a class="font-label-caps text-label-caps text-outline hover:text-primary transition-colors" href="#">物流</a>
</nav>
<button class="text-primary dark:text-on-primary hover:opacity-80 transition-opacity Active: scale-95 transition-transform duration-200">
<span class="material-symbols-outlined">shopping_bag</span>
</button>
</div>
</header>
<main class="pt-16 pb-24 md:pb-0">
<!-- Hero: STUDIO TUTORIALS -->
<section class="relative w-full border-b border-outline-variant overflow-hidden">
<div class="flex flex-col md:flex-row min-h-[618px]">
<!-- Video/Image Container -->
<div class="relative w-full md:w-2/3 h-[400px] md:h-auto overflow-hidden group">
<img class="w-full h-full object-cover" data-alt="A high-end cinematic still from a professional fashion styling tutorial in a minimalist white studio. A stylist is adjusting architectural curved denim jeans on a model." src="https://lh3.googleusercontent.com/aida-public/AB6AXuCJ0lLA3WoJN6dN-udtT6j7Djk3TA1ebaj0y5LjgDYUMye_G5vomBPaW3NtqR33IF_AZZixvF09VHCN0e3vRrCvuKVqWq8Twjg4P2u7w1h8xD-9B9Uju2G_o0aE1VsfYvJzdQOZ1KlRwl2oyYGOQJNBeSB0-V4be63s-C5r6i7DMiQB3OokpqxYLMNOJmw9DCBeoIenpfGA5Ekrmua1rH12N76mVWg4mCq6Zd0lO7KpqjIRW_BEk5aCGnrGYCLi8P4QNEp-p3h3W15T"/>
<div class="absolute inset-0 bg-black/10 group-hover:bg-black/0 transition-colors duration-500"></div>
<div class="absolute inset-0 flex items-center justify-center">
<button class="w-20 h-20 bg-white/90 rounded-none flex items-center justify-center shadow-lg hover:scale-105 transition-transform group/play">
<span class="material-symbols-outlined text-primary text-4xl" style="font-variation-settings: 'FILL' 1;">play_arrow</span>
</button>
</div>
<div class="absolute bottom-6 left-6">
<span class="inline-block bg-primary text-on-primary px-3 py-1 font-label-caps text-label-caps mb-2">現場直播中</span>
</div>
</div>
<!-- Content Sidebar -->
<div class="w-full md:w-1/3 p-margin-mobile md:p-12 flex flex-col justify-center bg-surface-container-low blueprint-grid border-l border-outline-variant">
<h2 class="font-label-caps text-label-caps text-outline mb-4">第 04 卷 / 第 01 課</h2>
<h3 class="font-display-xl-mobile md:font-display-xl text-display-xl-mobile md:text-display-xl text-primary leading-none mb-6">工作室教學</h3>
<p class="font-body-lg text-body-lg text-on-surface-variant mb-8 max-w-md">掌握輪廓：深入探討如何搭配建築感曲線牛仔褲以發揮最大影響力的工作坊。</p>
<div class="space-y-4">
<div class="flex items-center gap-4 py-3 border-b border-outline-variant">
<span class="font-label-caps text-label-caps text-primary">01</span>
<span class="font-body-md text-body-md">理解比例</span>
</div>
<div class="flex items-center gap-4 py-3 border-b border-outline-variant">
<span class="font-label-caps text-label-caps text-primary">02</span>
<span class="font-body-md text-body-md">質地的並置</span>
</div>
<div class="flex items-center gap-4 py-3 border-b border-outline-variant">
<span class="font-label-caps text-label-caps text-primary">03</span>
<span class="font-body-md text-body-md">鞋履整合</span>
</div>
</div>
</div>
</div>
</section>
<!-- Interactive Consultation CTA -->
<section class="bg-primary text-on-primary py-12 px-margin-mobile md:px-margin-desktop overflow-hidden relative">
<div class="max-w-container-max-width mx-auto flex flex-col md:flex-row justify-between items-center gap-8 relative z-10">
<div class="text-center md:text-left">
<h4 class="font-headline-md text-headline-md italic mb-2">精煉您的視野。</h4>
<p class="font-body-md text-body-md opacity-80 uppercase tracking-widest">透過數位鏡頭打造的個人化造型</p>
</div>
<button class="bg-on-primary text-primary px-10 py-5 font-label-caps text-label-caps hover:bg-surface-dim transition-colors flex items-center gap-3">
                    預約虛擬諮詢
                    <span class="material-symbols-outlined">calendar_today</span>
</button>
</div>
<!-- Decorative Background Element -->
<div class="absolute right-0 top-0 h-full w-1/3 opacity-10 flex items-center">
<span class="font-display-xl text-display-xl whitespace-nowrap">CONSULTATION</span>
</div>
</section>
<!-- Trend Reports Section -->
<section class="py-section-gap px-margin-mobile md:px-margin-desktop max-w-container-max-width mx-auto">
<div class="grid grid-cols-1 md:grid-cols-12 gap-gutter">
<!-- Men: The Trend Report -->
<div class="md:col-span-7 flex flex-col group">
<div class="mb-8 border-l-4 border-primary pl-6">
<h2 class="font-headline-lg-mobile md:font-headline-lg text-headline-lg-mobile md:text-headline-lg leading-tight uppercase">男裝：趨勢報告</h2>
<p class="font-label-caps text-label-caps text-outline tracking-[0.2em] mt-2">大膽、寬鬆剪裁與結構化層次</p>
</div>
<div class="relative overflow-hidden aspect-[4/5] md:aspect-[16/9]">
<img class="w-full h-full object-cover grayscale hover:grayscale-0 transition-all duration-700" data-alt="A fashion editorial shot featuring a male model wearing an oversized, structural black wool coat." src="https://lh3.googleusercontent.com/aida-public/AB6AXuCR7Fb0GKmK66wpJqrxo-lmiZtWYh1cSmO9ggIPILL3NyjZpCjGh7hkisZFTrYPf-KcAJJ8QxdeXQe_gUHrBcu3GlN1YmGmBpzWdGlC8hE5zTScMSI6Wqgdujw32SVePOlxynMSZOYohQ8E5INWLvgQ9YLGoTYCTbxUteQRIG1EE0SEgzYy_C3lBh-QVc6ZLIJ2-kbr0pKLJuoFfg67WSPktueDoNxOOAlNZ1LAIgf0Osiav8iN6cjBvxrvCCS7epqIUmPxDqDF3xW0"/>
<div class="absolute inset-0 border-[20px] border-white/0 group-hover:border-white/10 transition-all duration-500"></div>
<button class="absolute bottom-8 right-8 bg-white text-primary p-6 hover:bg-primary hover:text-white transition-colors">
<span class="material-symbols-outlined">north_east</span>
</button>
</div>
<div class="mt-6 flex justify-between items-start">
<div class="max-w-md">
<p class="font-body-md text-body-md text-on-surface-variant">探索防護與自我表達之間的界限。重量級織物與誇張廓形在 Winter Studio 系列中相遇。</p>
</div>
<div class="text-right">
<span class="font-label-caps text-label-caps border-b border-primary pb-1">工作室精選</span>
</div>
</div>
</div>
<!-- Women: French Essence -->
<div class="md:col-span-5 flex flex-col md:mt-32 group">
<div class="mb-8 border-r-4 border-primary pr-6 text-right order-first md:order-none">
<h2 class="font-headline-lg-mobile md:font-headline-lg text-headline-lg-mobile md:text-headline-lg leading-tight uppercase italic">女裝：法式精髓</h2>
<p class="font-label-caps text-label-caps text-outline tracking-[0.2em] mt-2">精緻、優雅的輪廓</p>
</div>
<div class="relative overflow-hidden aspect-[3/4]">
<img class="w-full h-full object-cover hover:scale-105 transition-transform duration-1000" data-alt="A sophisticated fashion portrait of a woman in a refined, cream-colored silk blouse." src="https://lh3.googleusercontent.com/aida-public/AB6AXuAavIRxlKCp0-jaDF2B4TSoLcpTRdi9PFyd5wgEJwAER57tWjIsgFRdeJa-tRfKy42QoilSIB-AmV_6KvQIpXoF9DnMi4vTXLgDOI9gzDH-jEIz9u8eB4lJMSe9jSEJlhKi-ZlPXe4FwhL3GdgM9cd2nJw_iMIbcXmLJlSRqPznYY8BQhvft91RwR-T-Z5WSVlr3j9uK2Ic_F6tlol17K2AEPB3qtssIesK82t3zKIyIv-QNxhLYnRUi4aWGI3Ft6pcPvVt6F0W5cNe"/>
<div class="absolute inset-0 bg-primary/5 opacity-0 group-hover:opacity-100 transition-opacity"></div>
</div>
<div class="mt-6">
<p class="font-body-md text-body-md text-on-surface-variant mb-6">不費吹灰之力的優雅策展。高領口、垂墜絲綢，以及 Studio 傳承的精確剪裁。</p>
<a class="font-label-caps text-label-caps text-primary border-b border-primary hover:opacity-70 transition-opacity" href="#">探索剪裁</a>
</div>
</div>
</div>
</section>
<!-- Blueprint Slider Placeholder / Custom Component -->
<section class="bg-surface-container-highest py-section-gap border-t border-outline-variant">
<div class="max-w-container-max-width mx-auto px-margin-mobile md:px-margin-desktop">
<div class="flex flex-col md:flex-row justify-between items-end mb-16 gap-4">
<div>
<h5 class="font-label-caps text-label-caps text-outline mb-2">結構洞察</h5>
<h2 class="font-headline-lg text-headline-lg">藍圖滑塊</h2>
</div>
<div class="flex gap-4">
<button class="px-6 py-2 border border-primary font-label-caps text-label-caps text-primary hover:bg-primary hover:text-white transition-all" id="blueprint-toggle">查看示意圖</button>
</div>
</div>
<div class="relative w-full aspect-video md:aspect-[21/9] overflow-hidden bg-white border border-outline-variant">
<div class="absolute inset-0 transition-opacity duration-500 opacity-100" id="blueprint-img">
<img class="w-full h-full object-contain" data-alt="A tailored jacket laid flat on a white surface." src="https://lh3.googleusercontent.com/aida-public/AB6AXuDRYyyvpLc17-jhdcrzhbdM3yLRhmTMFOA4LXCK52YSjPrnW6X_uCcW1FleSH9TtIt83f1_58pBL-hJwQZEB0DHVidCZwOzpxiQNsQpgWpVsUCaqKqGXuzC3AErzbbJ23Oc2_sXU2xkW52em_H78Wb_AV-jrR3AKtNSWnLyLf1gcPwxhYyf0f9clXL8b-TXAKMRdHrF0etU7Eqn7oF8QURgJR7gp4pRX9t4LIJzy7JYx6lrEu-6AqIgWqhWipLwaIJL8ZYLoS2k2FwR"/>
</div>
<div class="absolute inset-0 transition-opacity duration-500 opacity-0 blueprint-grid flex items-center justify-center p-12" id="blueprint-schematic">
<div class="w-full h-full border border-primary/20 flex items-center justify-center relative">
<span class="font-label-caps text-primary/40 absolute top-4 left-4">TECHNICAL DRAWING_V2.0</span>
<img class="w-full h-full object-contain mix-blend-multiply opacity-60" data-alt="A professional technical fashion flat sketch or blueprint of a jacket." src="https://lh3.googleusercontent.com/aida-public/AB6AXuDWZ0y12v5kDE3rxpE7zSy3P-2GtRQuwoolAxVq5FnNS8nz56jawIl3vlqRAhSU74s0AwkApMjB3HSD4RMuvQlvTLm0NDfzfW0SRCenO8gK4_7uqWVpyJ1Rha3zEpKTYvEgu3aJf4BySXjOrG5clpSKG5Dw4Eg6L8T6ZdfMxWkwkkQBw1JeKPISg6nY30Gdg6uWzUoTQK04_LW5lfq9_cTF178YsXWA1KnXcQOrSM4MT3ws4bEPG4X-8UcaMIDKDXZg9IV_5vfHXJvT"/>
</div>
</div>
</div>
</div>
</section>
<!-- Footer / Bottom Space -->
<footer class="py-12 border-t border-outline-variant px-margin-mobile md:px-margin-desktop text-center">
<p class="font-label-caps text-label-caps text-outline">© HARE AIR STUDIO 2024 — 精準物流，前衛設計。</p>
</footer>
</main>
<!-- BottomNavBar (Mobile Only) -->
<nav class="md:hidden fixed bottom-0 left-0 w-full bg-surface dark:bg-tertiary flex justify-around items-center px-4 pb-safe h-20 border-t border-outline-variant dark:border-on-surface-variant z-50">
<a class="flex flex-col items-center justify-center text-outline dark:text-outline-variant pt-2 hover:text-primary transition-colors" href="#">
<span class="material-symbols-outlined">home</span>
<span class="font-label-caps text-[10px]">首頁</span>
</a>
<a class="flex flex-col items-center justify-center text-outline dark:text-outline-variant pt-2 hover:text-primary transition-colors" href="#">
<span class="material-symbols-outlined">grid_view</span>
<span class="font-label-caps text-[10px]">商城</span>
</a>
<a class="flex flex-col items-center justify-center text-primary dark:text-on-primary border-t-2 border-primary dark:border-on-primary pt-2 translate-y-[-2px] transition-transform" href="#">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">play_circle</span>
<span class="font-label-caps text-[10px]">工作室</span>
</a>
<a class="flex flex-col items-center justify-center text-outline dark:text-outline-variant pt-2 hover:text-primary transition-colors" href="#">
<span class="material-symbols-outlined">person</span>
<span class="font-label-caps text-[10px]">帳戶</span>
</a>
</nav>
<script>
        // Blueprint Slider Toggle Logic
        const toggleBtn = document.getElementById('blueprint-toggle');
        const img = document.getElementById('blueprint-img');
        const schematic = document.getElementById('blueprint-schematic');
        let isSchematic = false;

        toggleBtn.addEventListener('click', () => {
            isSchematic = !isSchematic;
            if (isSchematic) {
                img.classList.replace('opacity-100', 'opacity-0');
                schematic.classList.replace('opacity-0', 'opacity-100');
                toggleBtn.textContent = '查看產品';
                toggleBtn.classList.add('bg-primary', 'text-white');
            } else {
                img.classList.replace('opacity-0', 'opacity-100');
                schematic.classList.replace('opacity-100', 'opacity-0');
                toggleBtn.textContent = '查看示意圖';
                toggleBtn.classList.remove('bg-primary', 'text-white');
            }
        });

        // Simple scroll reveal effect for editorial sections
        const observerOptions = {
            threshold: 0.1
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('opacity-100', 'translate-y-0');
                    entry.target.classList.remove('opacity-0', 'translate-y-10');
                }
            });
        }, observerOptions);

        document.querySelectorAll('section').forEach(section => {
            section.classList.add('transition-all', 'duration-1000', 'opacity-0', 'translate-y-10');
            observer.observe(section);
        });
    </script>
</body></html>

<!-- 選品商城 - HARE Air Studio (繁中) Mobile v2 -->
<!DOCTYPE html>

<html class="light" lang="zh-Hant"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>HARE AIR STUDIO | 購物</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Bodoni+Moda:ital,wght@0,400..900;1,400..900&amp;family=Hanken+Grotesk:ital,wght@0,100..900;1,100..900&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 300, 'GRAD' 0, 'opsz' 24;
            vertical-align: middle;
        }
        .hide-scrollbar::-webkit-scrollbar { display: none; }
        .hide-scrollbar { -ms-overflow-style: none; scrollbar-width: none; }
        
        .blueprint-overlay {
            clip-path: inset(0 100% 0 0);
            transition: clip-path 0.6s cubic-bezier(0.19, 1, 0.22, 1);
        }
        .card-container:hover .blueprint-overlay {
            clip-path: inset(0 0 0 0);
        }
    </style>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "tertiary": "#000000",
                        "surface-dim": "#dadada",
                        "outline-variant": "#c4c7c7",
                        "outline": "#747878",
                        "on-surface-variant": "#444748",
                        "on-primary-container": "#858383",
                        "inverse-on-surface": "#f1f1f1",
                        "inverse-primary": "#c8c6c5",
                        "on-primary-fixed": "#1c1b1b",
                        "surface-bright": "#f9f9f9",
                        "on-tertiary-fixed-variant": "#454747",
                        "on-secondary-container": "#4f6671",
                        "primary-fixed-dim": "#c8c6c5",
                        "on-primary": "#ffffff",
                        "on-error-container": "#93000a",
                        "surface-container-lowest": "#ffffff",
                        "on-surface": "#1a1c1c",
                        "secondary-container": "#cbe3f0",
                        "on-secondary-fixed": "#051e28",
                        "tertiary-fixed-dim": "#c6c6c6",
                        "on-tertiary-container": "#838484",
                        "on-tertiary-fixed": "#1a1c1c",
                        "inverse-surface": "#2f3131",
                        "on-secondary": "#ffffff",
                        "on-secondary-fixed-variant": "#334a54",
                        "surface-variant": "#e2e2e2",
                        "on-tertiary": "#ffffff",
                        "error-container": "#ffdad6",
                        "surface-container-high": "#e8e8e8",
                        "surface": "#f9f9f9",
                        "surface-container-highest": "#e2e2e2",
                        "secondary-fixed-dim": "#b2cad7",
                        "background": "#f9f9f9",
                        "error": "#ba1a1a",
                        "tertiary-fixed": "#e2e2e2",
                        "primary-fixed": "#e5e2e1",
                        "tertiary-container": "#1a1c1c",
                        "surface-container": "#eeeeee",
                        "surface-container-low": "#f3f3f3",
                        "secondary": "#4b626d",
                        "primary-container": "#1c1b1b",
                        "on-background": "#1a1c1c",
                        "surface-tint": "#5f5e5e",
                        "primary": "#000000",
                        "on-error": "#ffffff",
                        "on-primary-fixed-variant": "#474646",
                        "secondary-fixed": "#cee6f3"
                    },
                    "borderRadius": {
                        "DEFAULT": "0px",
                        "lg": "0px",
                        "xl": "0px",
                        "full": "9999px"
                    },
                    "spacing": {
                        "margin-desktop": "64px",
                        "section-gap": "128px",
                        "container-max-width": "1440px",
                        "gutter": "24px",
                        "unit": "8px",
                        "margin-mobile": "20px"
                    },
                    "fontFamily": {
                        "label-caps": ["Hanken Grotesk"],
                        "headline-md": ["Bodoni Moda"],
                        "body-lg": ["Hanken Grotesk"],
                        "display-xl-mobile": ["Bodoni Moda"],
                        "display-xl": ["Bodoni Moda"],
                        "headline-lg": ["Bodoni Moda"],
                        "body-md": ["Hanken Grotesk"],
                        "nav-link": ["Hanken Grotesk"],
                        "headline-lg-mobile": ["Bodoni Moda"]
                    },
                    "fontSize": {
                        "label-caps": ["12px", {"lineHeight": "16px", "letterSpacing": "0.1em", "fontWeight": "700"}],
                        "headline-md": ["24px", {"lineHeight": "32px", "fontWeight": "500"}],
                        "body-lg": ["18px", {"lineHeight": "28px", "fontWeight": "400"}],
                        "display-xl-mobile": ["48px", {"lineHeight": "56px", "letterSpacing": "-0.02em", "fontWeight": "600"}],
                        "display-xl": ["72px", {"lineHeight": "80px", "letterSpacing": "-0.02em", "fontWeight": "600"}],
                        "headline-lg": ["40px", {"lineHeight": "48px", "fontWeight": "500"}],
                        "body-md": ["16px", {"lineHeight": "24px", "fontWeight": "400"}],
                        "nav-link": ["14px", {"lineHeight": "20px", "letterSpacing": "0.05em", "fontWeight": "500"}],
                        "headline-lg-mobile": ["32px", {"lineHeight": "40px", "fontWeight": "500"}]
                    }
                },
            },
        }
    </script>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
</head>
<body class="bg-background text-on-background selection:bg-primary selection:text-on-primary">
<!-- TopAppBar -->
<header class="fixed top-0 left-0 w-full z-[100] border-b border-outline-variant bg-surface flex justify-between items-center px-margin-mobile md:px-margin-desktop h-16">
<div class="flex items-center gap-4">
<button class="hover:opacity-80 transition-opacity active:scale-95 transition-transform duration-200">
<span class="material-symbols-outlined text-primary">menu</span>
</button>
</div>
<h1 class="font-headline-md text-headline-md font-bold tracking-tighter text-primary">HARE AIR STUDIO</h1>
<div class="flex items-center gap-4">
<button class="hover:opacity-80 transition-opacity active:scale-95 transition-transform duration-200">
<span class="material-symbols-outlined text-primary">shopping_bag</span>
</button>
</div>
</header>
<main class="pt-24 pb-32 max-w-[1440px] mx-auto">
<!-- Hero Section & Category Select -->
<section class="px-margin-mobile md:px-margin-desktop mb-16">
<div class="flex flex-col md:flex-row md:items-end justify-between gap-8">
<div class="max-w-2xl">
<span class="font-label-caps text-label-caps text-outline block mb-4">建築美學服飾</span>
<h2 class="font-display-xl-mobile md:font-display-xl text-display-xl-mobile md:text-display-xl text-primary leading-none uppercase">經典剪裁</h2>
</div>
<div class="flex gap-4 border-b border-outline-variant pb-2">
<button class="font-label-caps text-label-caps text-primary border-b-2 border-primary pb-2 px-2">全部商品</button>
<button class="font-label-caps text-label-caps text-outline hover:text-primary transition-colors pb-2 px-2">男裝趨勢</button>
<button class="font-label-caps text-label-caps text-outline hover:text-primary transition-colors pb-2 px-2">女裝風格</button>
</div>
</div>
</section>
<!-- Quick Filters -->
<div class="px-margin-mobile md:px-margin-desktop mb-12 sticky top-16 bg-background/80 backdrop-blur-md z-40 py-4 flex gap-4 overflow-x-auto hide-scrollbar">
<div class="flex items-center gap-2 px-4 py-2 border border-outline-variant hover:border-primary transition-colors cursor-pointer whitespace-nowrap">
<span class="font-label-caps text-label-caps">性別</span>
<span class="material-symbols-outlined text-sm">expand_more</span>
</div>
<div class="flex items-center gap-2 px-4 py-2 border border-outline-variant hover:border-primary transition-colors cursor-pointer whitespace-nowrap">
<span class="font-label-caps text-label-caps">材質</span>
<span class="material-symbols-outlined text-sm">expand_more</span>
</div>
<div class="flex items-center gap-2 px-4 py-2 border border-outline-variant hover:border-primary transition-colors cursor-pointer whitespace-nowrap">
<span class="font-label-caps text-label-caps">結構</span>
<span class="material-symbols-outlined text-sm">expand_more</span>
</div>
<div class="ml-auto flex items-center gap-2 text-outline">
<span class="font-label-caps text-label-caps">24 件商品</span>
</div>
</div>
<!-- Product Grid -->
<section class="px-margin-mobile md:px-margin-desktop grid grid-cols-1 md:grid-cols-12 gap-gutter">
<!-- Featured Card - Wide -->
<div class="md:col-span-8 group cursor-pointer card-container relative">
<div class="aspect-[16/9] overflow-hidden bg-white border border-outline-variant relative">
<img class="w-full h-full object-cover grayscale group-hover:grayscale-0 transition-all duration-700" data-alt="A cinematic close-up of premium heavy suit trousers in deep charcoal wool, draped artistically over a minimalist white concrete block. The lighting is harsh and editorial, creating strong architectural shadows that emphasize the sharp creases and precision stitching. The overall aesthetic is high-end Japanese minimalism with a focus on textile integrity and structural design." src="https://lh3.googleusercontent.com/aida-public/AB6AXuC4CUjbQtUOs74JDdhf1T6_eAyhvvS2CcF9DogcmntdTAmh565vtsu3cDr0OiVIDQsHYD5p4ACGFJk1eiKQMzv9lXlgBz-EVX0YlCsJ9-ctc97cSP5zIt1bEbrKQdKxPQ0B-6B35T1vNI5Xrn-oyWu3YVAskj6meeYgjFGZg_UkXFUkVLUhNlb9KXEl0UdKhGvoT4jXYtRUw3F4SfXMlVx0PtDTP7wxplaHN8ZMfJK7E4QgLAG21zc9MoYxKrOJ2_LpH8tThNnt6pgr"/>
<!-- Blueprint Overlay (Unique Component) -->
<div class="blueprint-overlay absolute inset-0 bg-primary/90 flex items-center justify-center p-12 overflow-hidden pointer-events-none">
<div class="w-full h-full border border-white/20 relative">
<div class="absolute top-4 left-4 font-label-caps text-[10px] text-white/60">TECH_SPEC_04: 厚磅西裝長褲</div>
<div class="absolute inset-0 flex items-center justify-center opacity-40">
<span class="material-symbols-outlined text-[200px] text-white font-thin">architecture</span>
</div>
</div>
</div>
</div>
<div class="mt-6 flex justify-between items-start">
<div>
<h3 class="font-headline-md text-headline-md text-primary">厚磅西裝長褲 [V2]</h3>
<p class="font-body-md text-body-md text-outline mt-1 italic font-light">450gsm 羊毛打造的建築感廓形</p>
</div>
<div class="text-right">
<span class="font-label-caps text-label-caps text-primary">$340.00</span>
<div class="mt-2 flex gap-1 justify-end">
<span class="w-2 h-2 rounded-full bg-primary"></span>
<span class="w-2 h-2 rounded-full bg-outline-variant"></span>
</div>
</div>
</div>
</div>
<!-- Standard Card -->
<div class="md:col-span-4 group cursor-pointer">
<div class="aspect-[3/4] overflow-hidden bg-white border border-outline-variant">
<img class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" data-alt="A detailed macro shot of premium Japanese selvedge denim fabric, highlighting the rich indigo dye and the unique 'slubby' texture of the weave. The shot is framed in a clean, clinical studio setting with soft top-down lighting to reveal every fiber. The aesthetic is sophisticated, focusing on the craftsmanship and material quality of the garment." src="https://lh3.googleusercontent.com/aida-public/AB6AXuB9zitDygAtFKL0PTuplVGpEhSI21Nm0Qb5WEjSylJKtIWq88n9JNuSKVxv-x22MduOqyJdcTl95c29Nzt-e4UDOwXGTLCLI1wgsABbxyhH0jVIVDUQsFAKhnOM7ej41POmahOM06OXKwUuh2QPy50UrLjXxEp-uV6UFosF5w46q2LXkdQMiRTApcjhNqr11f2ReW1xCS_Hzy11iLBYh8zBl0dcCJ1zkJkBSExbUzsL8waKAb6oMg57rp-9zdF8QzkjPOr9PFMpuuuh"/>
</div>
<div class="mt-6">
<div class="flex justify-between items-center">
<h3 class="font-headline-md text-headline-md text-primary uppercase">彎刀牛仔褲</h3>
<span class="font-label-caps text-label-caps text-primary">$280.00</span>
</div>
<p class="font-body-md text-body-md text-outline mt-1">14oz 赤耳丹寧，標誌性彎刀剪裁</p>
<div class="mt-4">
<span class="px-2 py-1 border border-primary text-[10px] font-label-caps">工作室精選</span>
</div>
</div>
</div>
<!-- Small Detail Grid Section -->
<div class="md:col-span-12 mt-section-gap mb-12">
<h2 class="font-headline-lg text-headline-lg border-b border-primary pb-4 mb-8">男裝趨勢</h2>
<div class="grid grid-cols-1 md:grid-cols-4 gap-gutter">
<!-- Item 1 -->
<div class="group cursor-pointer">
<div class="aspect-square bg-white border border-outline-variant overflow-hidden">
<img class="w-full h-full object-cover grayscale group-hover:grayscale-0 transition-all" data-alt="Minimalist studio shot of a black oversized structural blazer. The garment is captured from a low angle against a sterile white background, emphasizing its sharp, boxy shoulders and avant-garde cut. The lighting is high-contrast, bringing out the matte texture of the premium gabardine fabric. Modern, professional, and uncompromisingly clean." src="https://lh3.googleusercontent.com/aida-public/AB6AXuAA7d1hxtQ7zsTpc9qonMNcyeNq_Od-wyiguVo0d7IQrj6eYD6mDqXjnLiEMBQLbNxQeSUcKLvES4KYE2Ri-OdrQPNqIq7-RYK6VIJZX73FvjW7L9B9GXFXhOwMxwTFdtIBf5_1AEX9k0cWfqc4HfWn0hfwEevIdwhlS75HX-PGAOdFkZBCiVZnRqbU0trqy6TcpNGbY42BWUiqNRLLrv2Vx_UAIoYPpAfwX1ND9lOpq5yEmUm3-gjPCnvZNKr0FYmcXm0BQIH-CrwJ"/>
</div>
<div class="py-4">
<div class="flex justify-between">
<span class="font-label-caps text-label-caps">箱型西裝外套</span>
<span class="font-label-caps text-label-caps">$420</span>
</div>
</div>
</div>
<!-- Item 2 -->
<div class="group cursor-pointer">
<div class="aspect-square bg-white border border-outline-variant overflow-hidden">
<img class="w-full h-full object-cover grayscale group-hover:grayscale-0 transition-all" data-alt="Professional studio photography of a stack of crisp white heavy cotton t-shirts. The focus is on the thick ribbed collar and the density of the fabric weave. The scene is bright and airy, representing the 'Air' part of the brand identity, with cool blue-toned shadows and a precise, rhythmic composition." src="https://lh3.googleusercontent.com/aida-public/AB6AXuDBuhtvPdNKwWvRKLmiTYea54_dYI9vZGQh6qTI02bLg1oNWG0aG5adZxWIRzaaF3sSKk2_GDUsW-6RcGyvYbbtZDtUjEfzXvgF5MKUnoIL4H1NF-prI_l-FJuqtV2sBPQxmNG7EkFSfn63NReZZFzcPQwqlRHhPFK9HaIWCe0VlAAQJ4LhMhluCNN7szG81Zby5LImGFRX_-BFTJjNcWcVv1gWxBBhd3StVu0MMrMPLva5ZV7OGKb6-L4XJogngKmahDqNKdUK3EsQ"/>
</div>
<div class="py-4">
<div class="flex justify-between">
<span class="font-label-caps text-label-caps">AIR TEE [三件組]</span>
<span class="font-label-caps text-label-caps">$120</span>
</div>
</div>
</div>
<!-- Item 3 -->
<div class="group cursor-pointer">
<div class="aspect-square bg-white border border-outline-variant overflow-hidden">
<img class="w-full h-full object-cover grayscale group-hover:grayscale-0 transition-all" data-alt="High-fashion macro shot of a sleek black leather jacket with polished silver hardware. The focus is on the grain of the premium calfskin leather and the architectural design of the zipper line. Set against a minimalist backdrop with dramatic side lighting that creates a high-gloss, exclusive feel typical of luxury streetwear." src="https://lh3.googleusercontent.com/aida-public/AB6AXuD9iY7Pu4CkJPh-GWIDLOaYVFmqeHtw01Za0FaWYmrjdzdhWXi9TGeltwbP8fNJ7moGWZKeEOZ-EPCCWTId_5-YV56OaPWs4B2jVbziK6HVYGGPqqdf0U1SR7STscIfi7QgSBAjE3C8DXmBE_Qm7iaunEfEew63I1cmfH4YjD6uHU2ExPc4UkaOTMhJfyVKCBjbiAQibW8lNf6Ru_33zETePox_IOyAhUJAemURfDakguPpJ3noR69ngtwnTqUVGWzw783bvenotYkl"/>
</div>
<div class="py-4">
<div class="flex justify-between">
<span class="font-label-caps text-label-caps">工作室皮革外套</span>
<span class="font-label-caps text-label-caps">$890</span>
</div>
</div>
</div>
<!-- Item 4 -->
<div class="group cursor-pointer">
<div class="aspect-square bg-white border border-outline-variant overflow-hidden">
<img class="w-full h-full object-cover grayscale group-hover:grayscale-0 transition-all" data-alt="A pristine white dress shirt captured in a high-key studio environment. The shirt features a unique asymmetrical hidden button placket and an extra-long cuff design. The image is bright, minimalist, and emphasizes the structural 'Studio' expertise. The lighting is soft but directed, highlighting the crispness of the cotton poplin fabric." src="https://lh3.googleusercontent.com/aida-public/AB6AXuCgvkbZwS3M95mD7baUa517_2ye7o7XXxopekQRkkEaPshjy8ArXjkqirj8w-rj3K19E9DMbEsvl2wxvoMIEwuRLgdPUjC_zjA9U5FQGYZ20rJ-HGjHtSXDqcOu9_Y7069XS3nUNSOsLzcMkf0yVGxDThMYRgPwk9jhj3TeW45B5CDh2G1q3i8hGX-Z462ICBe5oJO9VpdJ0dRUjHLTPzzPFBOZisgJvBony9pNLEmg7-FRxCZQfhFuQpgJz5zbmc9Iu2zbsivzGvN_"/>
</div>
<div class="py-4">
<div class="flex justify-between">
<span class="font-label-caps text-label-caps">修身廓形襯衫</span>
<span class="font-label-caps text-label-caps">$195</span>
</div>
</div>
</div>
</div>
</div>
<!-- Promotional Banner (Bento Style) -->
<div class="md:col-span-12 mt-section-gap grid grid-cols-1 md:grid-cols-12 gap-gutter h-auto md:h-[600px]">
<div class="md:col-span-7 bg-tertiary text-on-primary p-12 flex flex-col justify-center relative overflow-hidden">
<div class="relative z-10">
<h2 class="font-display-xl-mobile md:font-display-xl text-display-xl-mobile md:text-display-xl leading-none mb-8">面料檔案室</h2>
<p class="font-body-lg text-body-lg max-w-md mb-12 opacity-80">探索我們「AIR」系列面料的技術規格。為運動而研發，為工作室而設計。</p>
<button class="px-8 py-4 bg-white text-primary font-label-caps text-label-caps hover:bg-secondary-fixed transition-colors">探索工作室</button>
</div>
<div class="absolute -right-20 -bottom-20 opacity-20 transform rotate-12">
<span class="material-symbols-outlined text-[400px] font-thin">architecture</span>
</div>
</div>
<div class="md:col-span-5 bg-surface border border-outline-variant relative overflow-hidden">
<img class="w-full h-full object-cover opacity-50 grayscale" data-alt="A rhythmic, architectural view of a high-end designer boutique interior. Rows of perfectly aligned black garments hang on brushed steel rails against a backdrop of raw concrete walls. The lighting is clinical and bright, creating an atmosphere of precision and exclusive luxury. The aesthetic is focused on the 'Studio' curation and logistical perfection." src="https://lh3.googleusercontent.com/aida-public/AB6AXuAl1OditY8A6brPZUxifVB9ymzV-7wPk1KJnHnYDKyiElGW_coy-JHrLfjle3sBUy2IwRENGYx8GjjKCE5CUgZWPFf91v6A2WMGWm0oLZAyCBLL0e-KFgXL3iewN9x_RefX5teqlyhm0W-pX_hvh0_hr0UwTIjoOkrK2rcW7ENs0JNY6mdz2E-ZSY8bmKdbDH-y1EVh7Jk8Au7nfPCiZ4cFQEc46cCNngOfJC7oV31W0p31oYbyges0X7MYZVOb-0xl_TyF0xRc_s_c"/>
</div>
</div>
</section>
<!-- Women's Chic Teaser -->
<section class="px-margin-mobile md:px-margin-desktop mt-section-gap">
<div class="mb-12">
<span class="font-label-caps text-label-caps text-outline block mb-4">SEASON_02</span>
<h2 class="font-headline-lg text-headline-lg text-primary">女裝風格</h2>
</div>
<div class="grid grid-cols-1 md:grid-cols-3 gap-gutter">
<div class="group cursor-pointer">
<div class="aspect-[4/5] bg-white border border-outline-variant overflow-hidden">
<img class="w-full h-full object-cover transition-all duration-700 group-hover:scale-105" data-alt="A minimalist fashion editorial shot featuring a woman in a structured white oversized coat. The background is a monochromatic grey concrete wall, creating a sharp contrast with the fabric. The lighting is diffused but directional, highlighting the garment's unique proportions and high-end tailoring. The mood is sophisticated and avant-garde." src="https://lh3.googleusercontent.com/aida-public/AB6AXuBZ2Rm7uWtY9m9Is8QrUgvku00XJxAt-xxAII33Eq5kVp_a6Z7pUVU-ScNUXNorp7dczcLvjKh68xKsFdC_wuEXKOC4VBP_yUta17mJu_4zYjY9qkD7H9R-R7rGYYoB8VvsVq889T5zaAFkKMLfV4HTp4F6Ko-LQfj6N1JCS1u6gwX2qgU1NkXESPIgP23d3w_XKCSkU_WlfIZq2BF9qsvquNCE8qKMe-I1kedk6CPnYFaGVu28dC2rbN9QckwcPnsbYINWAwBgcWLv"/>
</div>
<div class="mt-4">
<h4 class="font-label-caps text-label-caps">結構感外套</h4>
<p class="font-body-md text-body-md text-outline">$580</p>
</div>
</div>
<div class="group cursor-pointer">
<div class="aspect-[4/5] bg-white border border-outline-variant overflow-hidden">
<img class="w-full h-full object-cover transition-all duration-700 group-hover:scale-105" data-alt="High-detail shot of an asymmetrical pleated black skirt against a stark white studio background. The pleats are sharp and precise, captured in motion to show the fluidity of the high-tech synthetic fabric. The lighting creates deep shadows within the folds, emphasizing the architectural complexity of the design." src="https://lh3.googleusercontent.com/aida-public/AB6AXuA4sS4ngCfILfScC1Keg6Cg29fmPe3DDDLqWBSsH9aTT3YP55Li0Y5Hhd4qk9xfWYseIqDOPbggKtzrleOOIr-EEB1mJaQaBXX964kuDZjPWFZUMrs91MARpuE1FYM4NK2xODmyprgV_6tb7LY59G28FaqvjysxncgQME3cte9L3okmo_c6SogTmCj80-rtVah2mH4_3BH72jnImZcp4uyQyVFcXf60elEXu5y_1zvkYJc36MWW5E4e7LWmUJYhqkLpSnhfJrElNHqj"/>
</div>
<div class="mt-4">
<h4 class="font-label-caps text-label-caps">不對稱百褶裙</h4>
<p class="font-body-md text-body-md text-outline">$295</p>
</div>
</div>
<div class="group cursor-pointer">
<div class="aspect-[4/5] bg-white border border-outline-variant overflow-hidden">
<img class="w-full h-full object-cover transition-all duration-700 group-hover:scale-105" data-alt="A high-key fashion shot of a minimalist silk blouse in a soft bone-white color. The blouse features a dramatic high collar and unique cuff details. The lighting is bright and even, giving the image a clean, clinical, and luxurious feel that aligns with the HARE Air Studio aesthetic of precision and light." src="https://lh3.googleusercontent.com/aida-public/AB6AXuDNkXgNLtdlEhZU07vUAFE1kz9IVM6AsWjOFkh8gZZo39Xdu7npmpstblEDN118haCaBdi3jroVeAOxAbGo1jFduK1mxVJ0GhxhdbBGo4etONibwZnbXgIJsoVNQ_AlfI0qRBNPncTpT--czmw3dAM-HZXwcZfPZyApWfsbkXMabz67f7D6l1_q1haTTXPoGRSR6NKunaBFFz5pjoKjg7ZFAITXqVuBH2iB_lya50ceAOtKqvt2j6Lx_qa7dbV0kr9uxvzijW_fmETx"/>
</div>
<div class="mt-4">
<h4 class="font-label-caps text-label-caps">AIR 絲綢罩衫</h4>
<p class="font-body-md text-body-md text-outline">$240</p>
</div>
</div>
</div>
</section>
<!-- Footer / Load More -->
<div class="mt-section-gap flex flex-col items-center px-margin-mobile">
<button class="font-label-caps text-label-caps border border-primary px-12 py-4 hover:bg-primary hover:text-on-primary transition-all duration-300">
                查看所有系列
            </button>
<div class="mt-24 w-full border-t border-outline-variant pt-12 grid grid-cols-2 md:grid-cols-4 gap-gutter text-outline font-label-caps text-[10px]">
<div class="flex flex-col gap-2">
<span class="text-primary font-bold">HARE AIR STUDIO</span>
<span>© 2024 TOKYO / LONDON</span>
</div>
<div class="flex flex-col gap-2">
<span>INSTAGRAM</span>
<span>TWITTER / X</span>
</div>
<div class="flex flex-col gap-2">
<span>隱私政策</span>
<span>運送與退換貨</span>
</div>
<div class="flex flex-col gap-2 text-right">
<span class="text-primary">ZH-TW / TWD</span>
</div>
</div>
</div>
</main>
<!-- BottomNavBar -->
<nav class="fixed bottom-0 left-0 w-full bg-surface border-t border-outline-variant flex justify-around items-center px-4 pb-safe h-20 z-[100] md:hidden">
<a class="flex flex-col items-center justify-center text-outline pt-2" href="#">
<span class="material-symbols-outlined">home</span>
<span class="font-label-caps text-[10px] mt-1">首頁</span>
</a>
<a class="flex flex-col items-center justify-center text-primary border-t-2 border-primary pt-2 translate-y-[-2px] transition-transform" href="#">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">grid_view</span>
<span class="font-label-caps text-[10px] mt-1">商城</span>
</a>
<a class="flex flex-col items-center justify-center text-outline pt-2" href="#">
<span class="material-symbols-outlined">play_circle</span>
<span class="font-label-caps text-[10px] mt-1">工作室</span>
</a>
<a class="flex flex-col items-center justify-center text-outline pt-2" href="#">
<span class="material-symbols-outlined">person</span>
<span class="font-label-caps text-[10px] mt-1">帳戶</span>
</a>
</nav>
<!-- Desktop Side Navigation (Hidden on mobile) -->
<div class="hidden md:flex fixed right-margin-desktop top-1/2 -translate-y-1/2 flex-col gap-8 z-50">
<div class="w-[1px] h-32 bg-outline-variant relative mx-auto">
<div class="absolute top-0 left-0 w-full h-12 bg-primary"></div>
</div>
<div class="flex flex-col gap-4 text-right">
<span class="font-label-caps text-label-caps text-primary cursor-pointer hover:underline uppercase">SIGNATURE</span>
<span class="font-label-caps text-label-caps text-outline cursor-pointer hover:text-primary transition-colors">MEN'S</span>
<span class="font-label-caps text-label-caps text-outline cursor-pointer hover:text-primary transition-colors">WOMEN'S</span>
<span class="font-label-caps text-label-caps text-outline cursor-pointer hover:text-primary transition-colors">ARCHIVE</span>
</div>
</div>
<script>
        document.querySelectorAll('.card-container').forEach(card => {
            card.addEventListener('mouseenter', () => {
                // Future interaction
            });
        });
    </script>
</body></html>

<!-- 首頁 - HARE Air Studio (繁中) Mobile v2 -->
<!DOCTYPE html>

<html class="light" lang="zh-Hant"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>HARE AIR STUDIO | 24SS 系列</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Bodoni+Moda:ital,wght@0,400..900;1,400..900&amp;family=Hanken+Grotesk:ital,wght@0,100..900;1,100..900&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<style>
    .material-symbols-outlined {
      font-variation-settings: 'FILL' 0, 'wght' 300, 'GRAD' 0, 'opsz' 24;
    }
    /* Blueprint Slider specific transitions */
    .blueprint-transition {
      transition: opacity 0.6s cubic-bezier(0.4, 0, 0.2, 1);
    }
    /* Hide scrollbar for staff styling */
    .no-scrollbar::-webkit-scrollbar { display: none; }
    .no-scrollbar { -ms-overflow-style: none; scrollbar-width: none; }
  </style>
<script id="tailwind-config">
    tailwind.config = {
      darkMode: "class",
      theme: {
        extend: {
          "colors": {
            "tertiary": "#000000",
            "surface-dim": "#dadada",
            "outline-variant": "#c4c7c7",
            "outline": "#747878",
            "on-surface-variant": "#444748",
            "on-primary-container": "#858383",
            "inverse-on-surface": "#f1f1f1",
            "inverse-primary": "#c8c6c5",
            "on-primary-fixed": "#1c1b1b",
            "surface-bright": "#f9f9f9",
            "on-tertiary-fixed-variant": "#454747",
            "on-secondary-container": "#4f6671",
            "primary-fixed-dim": "#c8c6c5",
            "on-primary": "#ffffff",
            "on-error-container": "#93000a",
            "surface-container-lowest": "#ffffff",
            "on-surface": "#1a1c1c",
            "secondary-container": "#cbe3f0",
            "on-secondary-fixed": "#051e28",
            "tertiary-fixed-dim": "#c6c6c6",
            "on-tertiary-container": "#838484",
            "on-tertiary-fixed": "#1a1c1c",
            "inverse-surface": "#2f3131",
            "on-secondary": "#ffffff",
            "on-secondary-fixed-variant": "#334a54",
            "surface-variant": "#e2e2e2",
            "on-tertiary": "#ffffff",
            "error-container": "#ffdad6",
            "surface-container-high": "#e8e8e8",
            "surface": "#f9f9f9",
            "surface-container-highest": "#e2e2e2",
            "secondary-fixed-dim": "#b2cad7",
            "background": "#f9f9f9",
            "error": "#ba1a1a",
            "tertiary-fixed": "#e2e2e2",
            "primary-fixed": "#e5e2e1",
            "tertiary-container": "#1a1c1c",
            "surface-container": "#eeeeee",
            "surface-container-low": "#f3f3f3",
            "secondary": "#4b626d",
            "primary-container": "#1c1b1b",
            "on-background": "#1a1c1c",
            "surface-tint": "#5f5e5e",
            "primary": "#000000",
            "on-error": "#ffffff",
            "on-primary-fixed-variant": "#474646",
            "secondary-fixed": "#cee6f3"
          },
          "borderRadius": {
            "DEFAULT": "0px",
            "lg": "0px",
            "xl": "0px",
            "full": "9999px"
          },
          "spacing": {
            "margin-desktop": "64px",
            "section-gap": "128px",
            "container-max-width": "1440px",
            "gutter": "24px",
            "unit": "8px",
            "margin-mobile": "20px"
          },
          "fontFamily": {
            "label-caps": ["Hanken Grotesk"],
            "headline-md": ["Bodoni Moda"],
            "body-lg": ["Hanken Grotesk"],
            "display-xl-mobile": ["Bodoni Moda"],
            "display-xl": ["Bodoni Moda"],
            "headline-lg": ["Bodoni Moda"],
            "body-md": ["Hanken Grotesk"],
            "nav-link": ["Hanken Grotesk"],
            "headline-lg-mobile": ["Bodoni Moda"]
          },
          "fontSize": {
            "label-caps": ["12px", {"lineHeight": "16px", "letterSpacing": "0.1em", "fontWeight": "700"}],
            "headline-md": ["24px", {"lineHeight": "32px", "fontWeight": "500"}],
            "body-lg": ["18px", {"lineHeight": "28px", "fontWeight": "400"}],
            "display-xl-mobile": ["48px", {"lineHeight": "56px", "letterSpacing": "-0.02em", "fontWeight": "600"}],
            "display-xl": ["72px", {"lineHeight": "80px", "letterSpacing": "-0.02em", "fontWeight": "600"}],
            "headline-lg": ["40px", {"lineHeight": "48px", "fontWeight": "500"}],
            "body-md": ["16px", {"lineHeight": "24px", "fontWeight": "400"}],
            "nav-link": ["14px", {"lineHeight": "20px", "letterSpacing": "0.05em", "fontWeight": "500"}],
            "headline-lg-mobile": ["32px", {"lineHeight": "40px", "fontWeight": "500"}]
          }
        },
      },
    }
  </script>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
</head>
<body class="bg-background text-on-background font-body-md selection:bg-primary selection:text-on-primary">
<!-- TopAppBar -->
<nav class="fixed top-0 left-0 w-full z-[100] bg-surface border-b border-outline-variant flex justify-between items-center px-margin-mobile md:px-margin-desktop h-16">
<div class="flex items-center gap-4">
<button class="hover:opacity-80 transition-opacity active:scale-95 duration-200">
<span class="material-symbols-outlined text-primary">menu</span>
</button>
</div>
<div class="font-headline-md text-headline-md font-bold tracking-tighter text-primary">HARE AIR STUDIO</div>
<div class="flex items-center gap-4">
<button class="hover:opacity-80 transition-opacity active:scale-95 duration-200">
<span class="material-symbols-outlined text-primary">shopping_bag</span>
</button>
</div>
</nav>
<main class="pt-16 pb-24">
<!-- Hero Section -->
<section class="relative w-full h-[795px] flex flex-col justify-end overflow-hidden group">
<img class="absolute inset-0 w-full h-full object-cover" data-alt="A high-fashion editorial photograph of a male and female model standing back-to-back in a minimalist concrete architectural space. The male model wears architectural heavyweight suit trousers in charcoal grey, while the female model wears avant-garde curved seam jeans in indigo. The lighting is high-contrast with sharp shadows, emphasizing the geometric structure of the garments. The overall aesthetic is clean, sophisticated, and Japanese-minimalist." src="https://lh3.googleusercontent.com/aida-public/AB6AXuCcidGaOXVFcOCJHjcnRXEnog9FLxT111Je5CeoSItAT47Q9ZPc-Ytg1xYLSdUfT8w2KdExts6kzKHOXhqY4er0SD310kglCZCfnyXRuMcu4wY_FN2mJIFlLXmgasUj9PupUlBVhWhEk9twJWXuV_YQV7SN30pfrQdcdGXCuTWIwPi0NUQbdVGzKiRdvvk1XwcoDd0ZQIhPjMO7pKz9N5co8q5a1t6dqyiDOohDF2l8VRwG_O_xzi9vawPf3EmLICaxwlV8bvlhgVNG"/>
<div class="absolute inset-0 bg-gradient-to-t from-black/60 via-transparent to-transparent"></div>
<div class="relative z-10 px-margin-mobile md:px-margin-desktop pb-section-gap">
<h1 class="font-display-xl-mobile md:font-display-xl text-display-xl-mobile md:text-display-xl text-on-primary max-w-4xl leading-tight">
          HARE AIR STUDIO <br/> 24SS 系列
        </h1>
<div class="mt-8">
<button class="bg-primary text-on-primary px-12 py-4 font-label-caps text-label-caps hover:bg-secondary transition-colors duration-300">
            探索企劃
          </button>
</div>
</div>
</section>
<!-- Staff Styling Section -->
<section class="mt-section-gap px-margin-mobile md:px-margin-desktop">
<div class="flex justify-between items-end mb-12 border-b border-primary pb-4">
<h2 class="font-headline-lg-mobile md:font-headline-lg text-headline-lg-mobile md:text-headline-lg">店員穿搭</h2>
<a class="font-label-caps text-label-caps underline hover:opacity-70 transition-opacity" href="#">查看全部</a>
</div>
<div class="flex gap-gutter overflow-x-auto no-scrollbar pb-8 -mx-margin-mobile px-margin-mobile md:mx-0 md:px-0">
<!-- Staff Card 1 -->
<div class="min-w-[300px] md:min-w-[400px] group cursor-pointer">
<div class="aspect-[3/4] overflow-hidden mb-6 relative">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" data-alt="Full-length portrait of a male fashion stylist in an avant-garde Japanese streetwear outfit. He is wearing oversized layered linen shirts and wide-leg pleated trousers in monochromatic tones of off-white and grey. The background is a clean, minimalist urban setting with soft, diffused daylight. The style is architectural and calm." src="https://lh3.googleusercontent.com/aida-public/AB6AXuBu-ICyr6ZQ-Al3MZNj8es0hWdiVqKRNiZ_QieaKNYUBV8G6RlKY8NQZs3sq4KW09-chLeD1Iw8lBAXEkJrrpRm-c2n5DhCV4NRY1qZn6DDlSWCOnCGCWWlrJpxLjD8HdI0nWhbXlSJg7jAs5k5837XkVxACMukIze7Js6fj0gJ8MS9_3LMLltH0xN4nH8NDaaty9BQ69QqqD1ErFpn7U0msJqr2AXa4eLB2zDexhDfE2gQ7e36VGS2B9WC8sa0Md5WqvY2bwRh_CGw"/>
<div class="absolute bottom-4 left-4">
<span class="bg-white text-black px-3 py-1 font-label-caps text-[10px] tracking-widest border border-black">工作室精選</span>
</div>
</div>
<div class="flex flex-col gap-1">
<p class="font-label-caps text-label-caps text-outline">東京 / 182CM</p>
<h3 class="font-body-lg text-body-lg uppercase font-bold">結構輪廓穿搭</h3>
<button class="mt-4 text-left font-label-caps text-label-caps underline underline-offset-4 hover:opacity-50 transition-opacity">購買此造型</button>
</div>
</div>
<!-- Staff Card 2 -->
<div class="min-w-[300px] md:min-w-[400px] group cursor-pointer">
<div class="aspect-[3/4] overflow-hidden mb-6 relative">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" data-alt="A portrait of a female stylist in a high-concept fashion studio. She wears a tailored black blazer with unconventional cut-outs and high-waisted wide-leg trousers. The color palette is monochromatic black and white. Lighting is dramatic and directional, creating a premium editorial vibe. The composition is clean and centered." src="https://lh3.googleusercontent.com/aida-public/AB6AXuAnv_qlvDkeOS0O0AfPwgmQBL7JN2JfE90nfyIBBPMYsGg12tK-_6W5X9ACOZvoagqcrbJeozoWojscR03ZKL8BmpzVRf9tNzJ6LiBDzlasVmSNtWKKS9Hq9DVFlS4HQ8DrkS8oFHD7vd8YWKDmoLMulsT9NpitaTUpllF7zqHgL8RSfbUndt7vz1Oyw9ClamQ76qQziqwmJxRx4HVHjP16z5w1d9xcEtvRiDXQGaRSmtq2TimS5mATVsuEfKeRANqU1NQyt6DSPsSr"/>
</div>
<div class="flex flex-col gap-1">
<p class="font-label-caps text-label-caps text-outline">大阪 / 165CM</p>
<h3 class="font-body-lg text-body-lg uppercase font-bold">極簡剪裁套裝</h3>
<button class="mt-4 text-left font-label-caps text-label-caps underline underline-offset-4 hover:opacity-50 transition-opacity">購買此造型</button>
</div>
</div>
<!-- Staff Card 3 -->
<div class="min-w-[300px] md:min-w-[400px] group cursor-pointer">
<div class="aspect-[3/4] overflow-hidden mb-6 relative">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" data-alt="Styling portrait of a man wearing a deconstructed knit sweater and cropped trousers. He stands in a bright, white-walled gallery space. The mood is artistic and serene. The lighting is natural and highlights the intricate texture of the knitwear. The palette is neutral earth tones. High-end lifestyle aesthetic." src="https://lh3.googleusercontent.com/aida-public/AB6AXuCXgjSMQdyYYqUV5r2aukhXFQuiRYWmlTaiYZ5NhnVGt25oKs8kXv0ft4K3NXAojfe-iTkFCYxi_tFIYBSqQ3lOHscVPkL4cx-PhYcDBCibeX5ko25KxY7E4rGGR_w5a6I-9QnvvnfWS_lJV0zHfsM6oF5GBmyalyaGOYWMyQKEkKwqu-Y829gLmwXltAqpx94zJYwiFW8CMquZG9c3q4HRFobEUPthTljQQritk5U_Zr9VS-Bqsf6JbEsrBFgRwsIK2o3SQTNpffaJ"/>
</div>
<div class="flex flex-col gap-1">
<p class="font-label-caps text-label-caps text-outline">澀谷 / 178CM</p>
<h3 class="font-body-lg text-body-lg uppercase font-bold">解構紋理系列</h3>
<button class="mt-4 text-left font-label-caps text-label-caps underline underline-offset-4 hover:opacity-50 transition-opacity">購買此造型</button>
</div>
</div>
</div>
</section>
<!-- Air Delivery Section -->
<section class="mt-section-gap px-margin-mobile md:px-margin-desktop">
<div class="bg-tertiary text-on-primary grid md:grid-cols-2 gap-0 overflow-hidden">
<div class="p-12 flex flex-col justify-center items-start border-r border-outline-variant/20">
<div class="flex items-center gap-4 mb-8">
<span class="material-symbols-outlined text-4xl" style="font-variation-settings: 'FILL' 1;">flight_takeoff</span>
<span class="font-label-caps text-label-caps tracking-[0.4em]">物流精確度</span>
</div>
<h2 class="font-headline-lg text-headline-lg mb-6 leading-tight">來自日本的 <br/> 空運直送</h2>
<p class="font-body-lg text-body-lg text-on-primary-container max-w-md mb-10">
            體驗品牌名稱中的「Air」精神。我們從東京工作室直郵，3 個工作日內送達。零阻礙、全透明物流。
          </p>
<div class="grid grid-cols-2 gap-8 w-full">
<div>
<p class="font-display-xl-mobile text-display-xl-mobile font-bold">03</p>
<p class="font-label-caps text-[10px] tracking-widest text-outline">天數送達</p>
</div>
<div>
<p class="font-display-xl-mobile text-display-xl-mobile font-bold">100%</p>
<p class="font-label-caps text-[10px] tracking-widest text-outline">單一費率追蹤</p>
</div>
</div>
</div>
<div class="relative min-h-[400px]">
<img class="w-full h-full object-cover" data-alt="A cinematic close-up of a high-tech logistics center. Clean white packaging with the 'HARE AIR STUDIO' logo is moving along a sleek, automated conveyor belt. The lighting is cool-toned and futuristic, with cyan and white highlights. The environment is impeccably clean, symbolizing speed and precision. Minimalist and corporate-modern aesthetic." src="https://lh3.googleusercontent.com/aida-public/AB6AXuBReWxoILrBzKxyVH6woJCG7u4auNBc6FvNJVW7Zr9GNkoefSQEV288sm28n809yBXelcI5_xJK8whVGDovinI_O0mBgxWuIgSpNP-lPPJd0XNHOS598DuAm6XvoTQAgYMI3iHWWBW5lpEm7HcbFEoaFUTZrcui2xJqQ8Xsl5VjjNxdHOPCTPFWYPfAILWeTwvOTWbtLLNqO4cYU5rF4uu4tOW9zr5u5txyY2NU2uO0Rd1cQkgvYtp9W1PIyZhTshsX0SlC7yIEaAG8"/>
<div class="absolute inset-0 bg-primary/20 mix-blend-multiply"></div>
</div>
</div>
</section>
<!-- Blueprint Slider (Unique Component) -->
<section class="mt-section-gap px-margin-mobile md:px-margin-desktop">
<div class="max-w-container-max-width mx-auto">
<div class="mb-12">
<h2 class="font-headline-lg text-headline-lg">工作室藍圖</h2>
<p class="font-body-md text-body-md text-outline mt-2">窺探弧形接縫丹寧褲的製作細節。</p>
</div>
<div class="relative w-full aspect-video md:aspect-[21/9] bg-surface-container overflow-hidden">
<div class="absolute inset-0 blueprint-transition" id="photo-layer">
<img class="w-full h-full object-cover" data-alt="Close-up photograph of high-quality indigo denim fabric showing the unique curved architectural seams and white contrast stitching. The lighting is natural and highlights the heavy texture of the cotton. The image is crisp and professional, focusing on the craftsmanship of the garment construction." src="https://lh3.googleusercontent.com/aida-public/AB6AXuADfad02QRUnXd9L1ITsO6iUfGQvTs-kx1bmrmjR6PfBog3DX_wOv9Eeo5c6p9IFbUBQdNYyDwMva0uihm-CaBpyA0W34w6bMGabJlhwmelaeUh-grfvVMoDnfe1LXikVwM_i8EjIbm8MX6W54yMsK13gabK9LOxCM6BsutVKTJdA_LARxuUc6fbjiIaf_CMerhhm7WMPqZUwECDKp2hHW8sgzD4xtxlL6QMf7-ayLVGqvH2ivavGLBsJcvZ6008SeS8e-fKmvim3RR"/>
</div>
<div class="absolute inset-0 opacity-0 blueprint-transition bg-white p-8 md:p-16 flex items-center justify-center" id="blueprint-layer">
<!-- Simulated Blueprint SVG Pattern -->
<div class="w-full h-full border border-blue-200 relative opacity-60">
<div class="absolute top-0 left-1/2 h-full w-[1px] bg-blue-100"></div>
<div class="absolute top-1/2 left-0 w-full h-[1px] bg-blue-100"></div>
<div class="absolute inset-0 flex items-center justify-center">
<svg class="max-h-full" fill="none" height="600" stroke="#2563eb" stroke-width="1" viewbox="0 0 400 600" width="400">
<path d="M100,50 L300,50 L350,550 L50,550 Z" stroke-dasharray="5,5"></path>
<path d="M100,50 Q150,150 100,550"></path>
<path d="M300,50 Q250,150 300,550"></path>
<circle cx="200" cy="50" r="10"></circle>
<text fill="#2563eb" font-family="Hanken Grotesk" font-size="12" text-anchor="middle" x="200" y="300">PATTERN_V2_CURVED_LEG</text>
</svg>
</div>
</div>
</div>
<div class="absolute bottom-8 right-8 z-20 flex gap-4">
<button class="bg-primary text-on-primary w-12 h-12 flex items-center justify-center transition-all" id="btn-photo" onclick="toggleBlueprint(false)">
<span class="material-symbols-outlined">image</span>
</button>
<button class="bg-surface text-primary border border-primary w-12 h-12 flex items-center justify-center transition-all" id="btn-blueprint" onclick="toggleBlueprint(true)">
<span class="material-symbols-outlined">architecture</span>
</button>
</div>
</div>
</div>
</section>
<!-- Join the Studio -->
<section class="mt-section-gap px-margin-mobile md:px-margin-desktop mb-12">
<div class="border border-outline-variant p-8 md:p-16 text-center">
<h2 class="font-headline-lg text-headline-lg mb-4">加入工作室</h2>
<p class="font-body-lg text-body-lg text-outline max-w-2xl mx-auto mb-12">
          解鎖專屬會員福利，包括 24SS 系列搶先購買與個人化穿搭建議。
        </p>
<div class="flex flex-col md:flex-row justify-center gap-gutter">
<button class="flex-1 max-w-sm border border-primary p-8 flex flex-col items-center group hover:bg-primary transition-all duration-300">
<span class="material-symbols-outlined text-4xl mb-4 group-hover:text-on-primary">smartphone</span>
<span class="font-label-caps text-label-caps group-hover:text-on-primary">下載 APP</span>
<div class="mt-6 flex items-center gap-2 bg-surface-container group-hover:bg-on-primary-container p-3 rounded-full">
<span class="material-symbols-outlined text-lg">confirmation_number</span>
<span class="font-label-caps text-[10px]">10% 折扣券</span>
</div>
</button>
<button class="flex-1 max-w-sm border border-primary p-8 flex flex-col items-center group hover:bg-primary transition-all duration-300">
<span class="material-symbols-outlined text-4xl mb-4 group-hover:text-on-primary">chat_bubble</span>
<span class="font-label-caps text-label-caps group-hover:text-on-primary">LINE 綁定</span>
<div class="mt-6 flex items-center gap-2 bg-surface-container group-hover:bg-on-primary-container p-3 rounded-full">
<span class="material-symbols-outlined text-lg">local_shipping</span>
<span class="font-label-caps text-[10px]">免運優惠券</span>
</div>
</button>
</div>
</div>
</section>
</main>
<!-- BottomNavBar -->
<nav class="fixed bottom-0 left-0 w-full bg-surface border-t border-outline-variant flex justify-around items-center px-4 pb-safe h-20 z-50">
<a class="flex flex-col items-center justify-center text-primary border-t-2 border-primary pt-2 translate-y-[-2px] transition-transform" href="#">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">home</span>
<span class="font-label-caps text-label-caps mt-1">首頁</span>
</a>
<a class="flex flex-col items-center justify-center text-outline pt-2 hover:text-primary transition-colors" href="#">
<span class="material-symbols-outlined">grid_view</span>
<span class="font-label-caps text-label-caps mt-1">商城</span>
</a>
<a class="flex flex-col items-center justify-center text-outline pt-2 hover:text-primary transition-colors" href="#">
<span class="material-symbols-outlined">play_circle</span>
<span class="font-label-caps text-label-caps mt-1">工作室</span>
</a>
<a class="flex flex-col items-center justify-center text-outline pt-2 hover:text-primary transition-colors" href="#">
<span class="material-symbols-outlined">person</span>
<span class="font-label-caps text-label-caps mt-1">帳戶</span>
</a>
</nav>
<script>
    function toggleBlueprint(isBlueprint) {
      const photoLayer = document.getElementById('photo-layer');
      const blueprintLayer = document.getElementById('blueprint-layer');
      const btnPhoto = document.getElementById('btn-photo');
      const btnBlueprint = document.getElementById('btn-blueprint');

      if (isBlueprint) {
        photoLayer.classList.add('opacity-0');
        blueprintLayer.classList.remove('opacity-0');
        
        btnBlueprint.classList.add('bg-primary', 'text-on-primary');
        btnBlueprint.classList.remove('bg-surface', 'text-primary');
        
        btnPhoto.classList.remove('bg-primary', 'text-on-primary');
        btnPhoto.classList.add('bg-surface', 'text-primary');
      } else {
        photoLayer.classList.remove('opacity-0');
        blueprintLayer.classList.add('opacity-0');
        
        btnPhoto.classList.add('bg-primary', 'text-on-primary');
        btnPhoto.classList.remove('bg-surface', 'text-primary');
        
        btnBlueprint.classList.remove('bg-primary', 'text-on-primary');
        btnBlueprint.classList.add('bg-surface', 'text-primary');
      }
    }
    
    // Intersection Observer for scroll animations
    const observerOptions = {
      threshold: 0.1
    };
    
    const observer = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add('opacity-100', 'translate-y-0');
          entry.target.classList.remove('opacity-0', 'translate-y-8');
        }
      });
    }, observerOptions);

    document.querySelectorAll('section').forEach(section => {
      section.classList.add('transition-all', 'duration-1000', 'opacity-0', 'translate-y-8');
      observer.observe(section);
    });
  </script>
</body></html>
