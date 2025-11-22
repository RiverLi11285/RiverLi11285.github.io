---
permalink: /
title: "Stellar Ascent Technology"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>星跃科技 - 未来飞行器与探空火箭创新引领者</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdn.jsdelivr.net/npm/font-awesome@4.7.0/css/font-awesome.min.css" rel="stylesheet">
    <script>
        // Tailwind 配置：强化科技感商业风格
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        dark: '#0F172A',
                        light: '#F8FAFC',
                        accent: '#06B6D4', // 科技蓝主色
                        secondary: '#3B82F6', // 辅助蓝
                        neutral: '#1E293B',
                        rocket: '#F97316', // 火箭系列主题色（橙色）
                    },
                    fontFamily: {
                        sans: ['Inter', 'Microsoft YaHei', 'sans-serif'],
                        tech: ['Orbitron', 'sans-serif'], // 科技感标题字体
                    },
                    animation: {
                        'float': 'float 6s ease-in-out infinite',
                        'fade-in': 'fadeIn 1.2s ease-out forwards',
                        'slide-up': 'slideUp 1.2s ease-out forwards',
                        'pulse-slow': 'pulse 3s cubic-bezier(0.4, 0, 0.6, 1) infinite',
                        'glow': 'glow 2s ease-in-out infinite alternate',
                        'zoom-in': 'zoomIn 15s ease-in-out infinite alternate',
                        'rocket-launch': 'rocketLaunch 8s ease-in-out infinite',
                    },
                    keyframes: {
                        float: {
                            '0%, 100%': { transform: 'translateY(0)' },
                            '50%': { transform: 'translateY(-15px)' },
                        },
                        fadeIn: {
                            '0%': { opacity: '0', transform: 'translateY(20px)' },
                            '100%': { opacity: '1', transform: 'translateY(0)' },
                        },
                        slideUp: {
                            '0%': { opacity: '0', transform: 'translateY(40px)' },
                            '100%': { opacity: '1', transform: 'translateY(0)' },
                        },
                        glow: {
                            '0%': { boxShadow: '0 0 12px rgba(6, 182, 212, 0.3)' },
                            '100%': { boxShadow: '0 0 20px rgba(6, 182, 212, 0.6), 0 0 30px rgba(6, 182, 212, 0.3)' },
                        },
                        zoomIn: {
                            '0%': { transform: 'scale(1)' },
                            '100%': { transform: 'scale(1.08)' },
                        },
                        rocketLaunch: {
                            '0%, 100%': { transform: 'translateY(0) rotate(0deg)' },
                            '50%': { transform: 'translateY(-20px) rotate(1deg)' },
                        }
                    }
                },
            }
        }
    </script>
    <style type="text/tailwindcss">
        @layer utilities {
            .text-shadow-tech {
                text-shadow: 0 2px 8px rgba(6, 182, 212, 0.2);
            }
            .text-shadow-rocket {
                text-shadow: 0 2px 8px rgba(249, 115, 22, 0.2);
            }
            .bg-grid-tech {
                background-image: linear-gradient(rgba(6, 182, 212, 0.05) 1px, transparent 1px),
                                  linear-gradient(90deg, rgba(6, 182, 212, 0.05) 1px, transparent 1px);
                background-size: 25px 25px;
                background-attachment: fixed;
            }
            .border-glow-tech {
                box-shadow: 0 0 15px rgba(6, 182, 212, 0.2);
            }
            .border-glow-rocket {
                box-shadow: 0 0 15px rgba(249, 115, 22, 0.2);
            }
            .hover-3d-tech {
                transition: all 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            }
            .hover-3d-tech:hover {
                transform: translateY(-8px) scale(1.02);
                box-shadow: 0 15px 30px rgba(6, 182, 212, 0.15);
            }
            .hover-3d-rocket {
                transition: all 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            }
            .hover-3d-rocket:hover {
                transform: translateY(-8px) scale(1.02);
                box-shadow: 0 15px 30px rgba(249, 115, 22, 0.15);
            }
            .clip-path-slate {
                clip-path: polygon(0 0, 100% 0, 100% 95%, 0 100%);
            }
            .scrollbar-tech::-webkit-scrollbar {
                width: 8px;
            }
            .scrollbar-tech::-webkit-scrollbar-track {
                background: rgba(6, 182, 212, 0.05);
            }
            .scrollbar-tech::-webkit-scrollbar-thumb {
                background: rgba(6, 182, 212, 0.4);
                border-radius: 4px;
            }
            .image-overlay {
                background: linear-gradient(to bottom, rgba(15, 23, 42, 0) 0%, rgba(15, 23, 42, 0.7) 70%, rgba(15, 23, 42, 1) 100%);
            }
            .image-overlay-rocket {
                background: linear-gradient(to bottom, rgba(15, 23, 42, 0) 0%, rgba(249, 115, 22, 0.1) 50%, rgba(15, 23, 42, 1) 100%);
            }
        }
    </style>
    <!-- 引入科技感字体 -->
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500;600;700&display=swap" rel="stylesheet">
</head>
<body class="bg-dark text-light font-sans antialiased scrollbar-tech">
    <!-- 导航栏 - 商业科技风 -->
    <nav id="navbar" class="fixed w-full z-50 transition-all duration-500 bg-dark/98 backdrop-blur-lg border-b border-accent/20">
        <div class="container mx-auto px-4 md:px-8 py-4 flex justify-between items-center">
            <a href="#" class="flex items-center gap-2 group">
                <span class="text-2xl font-tech font-bold tracking-wide text-white group-hover:text-accent transition-colors duration-300">星跃科技</span>
                <span class="text-accent text-sm font-tech">AEROSPACE INNOVATION</span>
            </a>
            <div class="hidden md:flex items-center gap-8">
                <a href="#home" class="text-white hover:text-accent transition-colors duration-300 font-medium">简介</a>
                <a href="#products" class="text-white hover:text-accent transition-colors duration-300 font-medium">产品中心</a>
                <a href="#team" class="text-white hover:text-accent transition-colors duration-300 font-medium">核心团队</a>
            </div>
            <div class="flex items-center gap-4">
                <button id="menuBtn" class="md:hidden text-white text-xl hover:text-accent transition-colors">
                    <i class="fa fa-bars"></i>
                </button>
            </div>
        </div>
        <!-- 移动端菜单 -->
        <div id="mobileMenu" class="hidden md:hidden bg-neutral border-b border-accent/20 animate-fade-in">
            <div class="container mx-auto px-4 py-3 flex flex-col gap-3">
                <a href="#home" class="py-2 text-white hover:text-accent transition-colors font-medium">简介</a>
                <a href="#products" class="py-2 text-white hover:text-accent transition-colors font-medium">产品中心</a>
                <a href="#team" class="py-2 text-white hover:text-accent transition-colors font-medium">核心团队</a>
            </div>
        </div>
    </nav>

    <!-- 英雄区 - 简介 -->
    <section id="home" class="min-h-screen flex items-center justify-center bg-grid-tech pt-20 relative overflow-hidden">
        <!-- 动态科技背景 -->
        <div class="absolute inset-0 z-0">
            <div class="absolute top-1/4 left-1/5 w-72 h-72 bg-accent/10 rounded-full blur-3xl animate-pulse-slow"></div>
            <div class="absolute bottom-1/3 right-1/5 w-80 h-80 bg-secondary/10 rounded-full blur-3xl animate-pulse-slow" style="animation-delay: 1s"></div>
            <div class="absolute top-1/3 right-1/4 w-64 h-64 bg-rocket/10 rounded-full blur-3xl animate-pulse-slow" style="animation-delay: 2s"></div>
            <div class="absolute inset-0 bg-[radial-gradient(circle_at_center,rgba(6,182,212,0.08)_0%,transparent_75%)]"></div>
        </div>
        <div class="container mx-auto px-4 md:px-8 py-16 md:py-24 relative z-10">
            <div class="max-w-4xl">
                <h1 class="text-[clamp(2.5rem,5vw,4rem)] font-tech font-bold leading-tight mb-6 animate-fade-in text-white text-shadow-tech">
                    重新定义 <span class="text-accent">智能飞行</span> 与 <span class="text-rocket">探空科技</span>
                </h1>
                <p class="text-[clamp(1rem,2vw,1.25rem)] text-white/80 mb-10 max-w-2xl animate-fade-in" style="animation-delay: 0.3s">
                    星跃科技专注于高端智能飞行器与轻型探空火箭研发制造，由培侨书院与培侨信义学校的优秀学生组成创新团队，汇聚航空航天、自动化、计算机、机械工程等多领域青年才俊。我们以突破性技术打造高效、安全、智能的飞行与探空解决方案，涵盖商业通勤、工业货运、应急救援及科研探测等多场景，致力于成为未来航空航天领域创新引领者。
                </p>
                <div class="flex flex-col sm:flex-row gap-4 animate-fade-in" style="animation-delay: 0.6s">
                    <a href="#products" class="px-8 py-3 bg-accent text-dark font-medium rounded-sm hover:bg-accent/90 transition-colors duration-300 animate-glow">
                        探索产品
                    </a>
                    <a href="#team" class="px-8 py-3 bg-transparent border border-accent text-white font-medium rounded-sm hover:border-accent/80 transition-colors duration-300">
                        认识团队
                    </a>
                </div>
            </div>
            <!-- 飞行器与火箭展示区 -->
            <div class="mt-16 md:mt-20 grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="relative w-full max-w-2xl h-64 md:h-80 mx-auto bg-black/40 rounded-sm overflow-hidden border border-accent/30 hover:border-glow-tech transition-all duration-500">
                    <img src="https://picsum.photos/id/1071/1600/900" alt="星跃科技智能飞行器" class="w-full h-full object-cover animate-zoom-in">
                    <div class="absolute inset-0 image-overlay"></div>
                    <div class="absolute bottom-6 left-6 text-white z-10">
                        <span class="bg-accent/80 text-dark px-3 py-1 rounded-full text-sm font-medium mb-2 inline-block">AeroCommute X1</span>
                        <h3 class="text-xl font-bold">商业通勤飞行器</h3>
                    </div>
                </div>
                <div class="relative w-full max-w-2xl h-64 md:h-80 mx-auto bg-black/40 rounded-sm overflow-hidden border border-rocket/30 hover:border-glow-rocket transition-all duration-500">
                    <img src="https://picsum.photos/id/1059/1600/900" alt="扶摇系列轻型探空火箭" class="w-full h-full object-cover animate-rocket-launch">
                    <div class="absolute inset-0 image-overlay-rocket"></div>
                    <div class="absolute bottom-6 left-6 text-white z-10">
                        <span class="bg-rocket/80 text-dark px-3 py-1 rounded-full text-sm font-medium mb-2 inline-block">扶摇-1 探空火箭</span>
                        <h3 class="text-xl font-bold">轻型科研探测火箭</h3>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 产品中心 -->
    <section id="products" class="py-24 bg-dark clip-path-slate">
        <div class="container mx-auto px-4 md:px-8">
            <div class="text-center mb-16">
                <h2 class="text-[clamp(1.8rem,3vw,2.5rem)] font-tech font-bold mb-4 text-white">智能飞行器与探空火箭产品系列</h2>
                <p class="text-white/70 max-w-2xl mx-auto">针对不同场景需求，打造全系列智能飞行与探空解决方案，兼具性能与可靠性</p>
                <div class="w-24 h-1 bg-accent mx-auto mt-6 rounded-full"></div>
            </div>

            <!-- 产品分类标签 -->
            <div class="flex flex-wrap justify-center gap-4 mb-12">
                <button class="px-6 py-2 bg-accent text-dark font-medium rounded-sm" id="allProducts">全部产品</button>
                <button class="px-6 py-2 bg-neutral text-white font-medium rounded-sm hover:bg-accent hover:text-dark transition-colors" id="aircraftProducts">智能飞行器</button>
                <button class="px-6 py-2 bg-neutral text-white font-medium rounded-sm hover:bg-rocket hover:text-dark transition-colors" id="rocketProducts">探空火箭</button>
            </div>

            <!-- 产品卡片网格 -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- 飞行器产品 -->
                <!-- 产品1：商业通勤版 -->
                <div class="bg-neutral border border-accent/20 rounded-sm overflow-hidden hover-3d-tech product-card opacity-0" data-animation-delay="0.1s" data-category="aircraft">
                    <div class="h-60 overflow-hidden relative group">
                        <img src="https://picsum.photos/id/1059/800/600" alt="商业通勤飞行器-正面" class="w-full h-full object-cover transition-opacity duration-500 group-hover:opacity-0">
                        <img src="https://picsum.photos/id/1071/800/600" alt="商业通勤飞行器-侧面" class="w-full h-full object-cover absolute top-0 left-0 opacity-0 transition-opacity duration-500 group-hover:opacity-100">
                        <div class="absolute top-4 left-4 bg-accent text-dark px-3 py-1 rounded-full text-sm font-medium z-10">
                            商业通勤
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-3 text-white">AeroCommute X1</h3>
                        <p class="text-white/70 mb-6">
                            针对城市短途通勤场景设计，电动垂直起降技术，零排放低噪音，可搭载2名乘客，最大续航150km，适用于高端商务出行。
                        </p>
                        <div class="grid grid-cols-2 gap-4 mb-6">
                            <div class="flex flex-col">
                                <span class="text-white/50 text-sm">最大速度</span>
                                <span class="text-lg font-medium text-white">200 km/h</span>
                            </div>
                            <div class="flex flex-col">
                                <span class="text-white/50 text-sm">续航里程</span>
                                <span class="text-lg font-medium text-white">150 km</span>
                            </div>
                            <div class="flex flex-col">
                                <span class="text-white/50 text-sm">载人数</span>
                                <span class="text-lg font-medium text-white">2 人</span>
                            </div>
                            <div class="flex flex-col">
                                <span class="text-white/50 text-sm">充电时间</span>
                                <span class="text-lg font-medium text-white">1.2 h</span>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- 产品2：工业货运版 -->
                <div class="bg-neutral border border-accent/20 rounded-sm overflow-hidden hover-3d-tech product-card opacity-0" data-animation-delay="0.3s" data-category="aircraft">
                    <div class="h-60 overflow-hidden relative group">
                        <img src="https://picsum.photos/id/1060/800/600" alt="工业货运飞行器-正面" class="w-full h-full object-cover transition-opacity duration-500 group-hover:opacity-0">
                        <img src="https://picsum.photos/id/1058/800/600" alt="工业货运飞行器-装载" class="w-full h-full object-cover absolute top-0 left-0 opacity-0 transition-opacity duration-500 group-hover:opacity-100">
                        <div class="absolute top-4 left-4 bg-accent text-dark px-3 py-1 rounded-full text-sm font-medium z-10">
                            工业货运
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-3 text-white">AeroCargo X2</h3>
                        <p class="text-white/70 mb-6">
                            工业级重载货运飞行器，最大载重800kg，支持自动装卸货，适配复杂工业环境，为仓储物流、偏远地区运输提供高效解决方案。
                        </p>
                        <div class="grid grid-cols-2 gap-4 mb-6">
                            <div class="flex flex-col">
                                <span class="text-white/50 text-sm">最大速度</span>
                                <span class="text-lg font-medium text-white">180 km/h</span>
                            </div>
                            <div class="flex flex-col">
                                <span class="text-white/50 text-sm">续航里程</span>
                                <span class="text-lg font-medium text-white">220 km</span>
                            </div>
                            <div class="flex flex-col">
                                <span class="text-white/50 text-sm">最大载重</span>
                                <span class="text-lg font-medium text-white">800 kg</span>
                            </div>
                            <div class="flex flex-col">
                                <span class="text-white/50 text-sm">操控方式</span>
                                <span class="text-lg font-medium text-white">自动/手动</span>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- 产品3：应急救援版 -->
                <div class="bg-neutral border border-accent/20 rounded-sm overflow-hidden hover-3d-tech product-card opacity-0" data-animation-delay="0.5s" data-category="aircraft">
                    <div class="h-60 overflow-hidden relative group">
                        <img src="https://picsum.photos/id/1054/800/600" alt="应急救援飞行器-正面" class="w-full h-full object-cover transition-opacity duration-500 group-hover:opacity-0">
                        <img src="https://picsum.photos/id/1067/800/600" alt="应急救援飞行器-医疗舱" class="w-full h-full object-cover absolute top-0 left-0 opacity-0 transition-opacity duration-500 group-hover:opacity-100">
                        <div class="absolute top-4 left-4 bg-accent text-dark px-3 py-1 rounded-full text-sm font-medium z-10">
                            应急救援
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-3 text-white">AeroRescue X3</h3>
                        <p class="text-white/70 mb-6">
                            专业应急救援飞行器，配备完整医疗舱和生命支持系统，适应复杂地形和恶劣天气，为紧急救援提供快速响应能力。
                        </p>
                        <div class="grid grid-cols-2 gap-4 mb-6">
                            <div class="flex flex-col">
                                <span class="text-white/50 text-sm">最大速度</span>
                                <span class="text-lg font-medium text-white">240 km/h</span>
                            </div>
                            <div class="flex flex-col">
                                <span class="text-white/50 text-sm">续航里程</span>
                                <span class="text-lg font-medium text-white">350 km</span>
                            </div>
                            <div class="flex flex-col">
                                <span class="text-white/50 text-sm">医疗配置</span>
                                <span class="text-lg font-medium text-white">完整急救系统</span>
                            </div>
                            <div class="flex flex-col">
                                <span class="text-white/50 text-sm">适应环境</span>
                                <span class="text-lg font-medium text-white">全地形/全天候</span>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- 扶摇系列探空火箭产品（新增4款） -->
                <!-- 火箭1：基础科研版 -->
                <div class="bg-neutral border border-rocket/20 rounded-sm overflow-hidden hover-3d-rocket product-card opacity-0" data-animation-delay="0.7s" data-category="rocket">
                    <div class="h-60 overflow-hidden relative group">
                        <img src="https://picsum.photos/id/1059/800/600" alt="扶摇-1探空火箭-正面" class="w-full h-full object-cover transition-opacity duration-500 group-hover:opacity-0">
                        <img src="https://picsum.photos/id/1061/800/600" alt="扶摇-1探空火箭-发射" class="w-full h-full object-cover absolute top-0 left-0 opacity-0 transition-opacity duration-500 group-hover:opacity-100">
                        <div class="absolute top-4 left-4 bg-rocket text-dark px-3 py-1 rounded-full text-sm font-medium z-10">
                            基础科研
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-3 text-white text-shadow-rocket">扶摇-1 (FY-1)</h3>
                        <p class="text-white/70 mb-6">
                            入门级轻型探空火箭，专为科研教学设计，最大升限15km，可搭载小型气象探测设备，操作简单，适合高校科研项目与航天科普教育。
                        </p>
                        <div class="grid grid-cols-2 gap-4 mb-6">
                            <div class="flex flex-col">
                                <span class="text-white/50 text-sm">最大升限</span>
                                <span class="text-lg font-medium text-white">15 km</span>
                            </div>
                            <div class="flex flex-col">
                                <span class="text-white/50 text-sm">有效载荷</span>
                                <span class="text-lg font-medium text-white">3 kg</span>
                            </div>
                            <div class="flex flex-col">
                                <span class="text-white/50 text-sm">箭体长度</span>
                                <span class="text-lg font-medium text-white">3.2 m</span>
                            </div>
                            <div class="flex flex-col">
                                <span class="text-white/50 text-sm">回收方式</span>
                                <span class="text-lg font-medium text-white">降落伞回收</span>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- 火箭2：高精度探测版 -->
                <div class="bg-neutral border border-rocket/20 rounded-sm overflow-hidden hover-3d-rocket product-card opacity-0" data-animation-delay="0.9s" data-category="rocket">
                    <div class="h-60 overflow-hidden relative group">
                        <img src="https://picsum.photos/id/1062/800/600" alt="扶摇-2探空火箭-正面" class="w-full h-full object-cover transition-opacity duration-500 group-hover:opacity-0">
                        <img src="https://picsum.photos/id/1063/800/600" alt="扶摇-2探空火箭-载荷舱" class="w-full h-full object-cover absolute top-0 left-0 opacity-0 transition-opacity duration-500 group-hover:opacity-100">
                        <div class="absolute top-4 left-4 bg-rocket text-dark px-3 py-1 rounded-full text-sm font-medium z-10">
                            高精度探测
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-3 text-white text-shadow-rocket">扶摇-2 (FY-2)</h3>
                        <p class="text-white/70 mb-6">
                            高精度气象探测火箭，最大升限30km，搭载多参数传感器，数据传输精度达0.1%，适用于大气物理研究、气象观测等专业场景。
                        </p>
                        <div class="grid grid-cols-2 gap-4 mb-6">
                            <div class="flex flex-col">
                                <span class="text-white/50 text-sm">最大升限</span>
                                <span class="text-lg font-medium text-white">30 km</span>
                            </div>
                            <div class="flex flex-col">
                                <span class="text-white/50 text-sm">有效载荷</span>
                                <span class="text-lg font-medium text-white">8 kg</span>
                            </div>
                            <div class="flex flex-col">
                                <span class="text-white/50 text-sm">数据精度</span>
                                <span class="text-lg font-medium text-white">±0.1%</span>
                            </div>
                            <div class="flex flex-col">
                                <span class="text-white/50 text-sm">续航时间</span>
                                <span class="text-lg font-medium text-white">120 s</span>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- 火箭3：载荷试验版 -->
                <div class="bg-neutral border border-rocket/20 rounded-sm overflow-hidden hover-3d-rocket product-card opacity-0" data-animation-delay="1.1s" data-category="rocket">
                    <div class="h-60 overflow-hidden relative group">
                        <img src="https://picsum.photos/id/1064/800/600" alt="扶摇-3探空火箭-正面" class="w-full h-full object-cover transition-opacity duration-500 group-hover:opacity-0">
                        <img src="https://picsum.photos/id/1065/800/600" alt="扶摇-3探空火箭-试验" class="w-full h-full object-cover absolute top-0 left-0 opacity-0 transition-opacity duration-500 group-hover:opacity-100">
                        <div class="absolute top-4 left-4 bg-rocket text-dark px-3 py-1 rounded-full text-sm font-medium z-10">
                            载荷试验
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-3 text-white text-shadow-rocket">扶摇-3 (FY-3)</h3>
                        <p class="text-white/70 mb-6">
                            重型载荷试验火箭，最大载荷25kg，升限25km，配备可重复使用载荷舱，适用于小型卫星搭载试验、新材料高空环境测试等场景。
                        </p>
                        <div class="grid grid-cols-2 gap-4 mb-6">
                            <div class="flex flex-col">
                                <span class="text-white/50 text-sm">最大升限</span>
                                <span class="text-lg font-medium text-white">25 km</span>
                            </div>
                            <div class="flex flex-col">
                                <span class="text-white/50 text-sm">最大载荷</span>
                                <span class="text-lg font-medium text-white">25 kg</span>
                            </div>
                            <div class="flex flex-col">
                                <span class="text-white/50 text-sm">箭体直径</span>
                                <span class="text-lg font-medium text-white">35 cm</span>
                            </div>
                            <div class="flex flex-col">
                                <span class="text-white/50 text-sm">重复使用</span>
                                <span class="text-lg font-medium text-white">载荷舱可回收</span>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- 火箭4：长航时观测版 -->
                <div class="bg-neutral border border-rocket/20 rounded-sm overflow-hidden hover-3d-rocket product-card opacity-0" data-animation-delay="1.3s" data-category="rocket">
                    <div class="h-60 overflow-hidden relative group">
                        <img src="https://picsum.photos/id/1066/800/600" alt="扶摇-4探空火箭-正面" class="w-full h-full object-cover transition-opacity duration-500 group-hover:opacity-0">
                        <img src="https://picsum.photos/id/1068/800/600" alt="扶摇-4探空火箭-观测" class="w-full h-full object-cover absolute top-0 left-0 opacity-0 transition-opacity duration-500 group-hover:opacity-100">
                        <div class="absolute top-4 left-4 bg-rocket text-dark px-3 py-1 rounded-full text-sm font-medium z-10">
                            长航时观测
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-3 text-white text-shadow-rocket">扶摇-4 (FY-4)</h3>
                        <p class="text-white/70 mb-6">
                            长航时高空观测火箭，升限40km，搭载滞空型载荷舱，可在平流层停留30分钟以上，支持持续气象监测、天文观测等长时间任务。
                        </p>
                        <div class="grid grid-cols-2 gap-4 mb-6">
                            <div class="flex flex-col">
                                <span class="text-white/50 text-sm">最大升限</span>
                                <span class="text-lg font-medium text-white">40 km</span>
                            </div>
                            <div class="flex flex-col">
                                <span class="text-white/50 text-sm">滞空时间</span>
                                <span class="text-lg font-medium text-white">30+ min</span>
                            </div>
                            <div class="flex flex-col">
                                <span class="text-white/50 text-sm">有效载荷</span>
                                <span class="text-lg font-medium text-white">15 kg</span>
                            </div>
                            <div class="flex flex-col">
                                <span class="text-white/50 text-sm">通信方式</span>
                                <span class="text-lg font-medium text-white">卫星+地面双链路</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- 产品特性 -->
            <div class="mt-20 grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-neutral/50 border border-accent/10 p-6 rounded-sm hover:border-accent/30 transition-colors duration-300 opacity-0" data-animation-delay="1.5s">
                    <div class="w-12 h-12 bg-accent/20 flex items-center justify-center mb-4">
                        <i class="fa fa-bolt text-xl text-accent"></i>
                    </div>
                    <h3 class="text-lg font-bold mb-3 text-white">高效能源系统</h3>
                    <p class="text-white/70">
                        采用先进锂电池技术与能量回收系统，能量转换效率达92%，支持快速充电和长续航，降低运营成本。
                    </p>
                </div>
                <div class="bg-neutral/50 border border-accent/10 p-6 rounded-sm hover:border-accent/30 transition-colors duration-300 opacity-0" data-animation-delay="1.7s">
                    <div class="w-12 h-12 bg-accent/20 flex items-center justify-center mb-4">
                        <i class="fa fa-shield text-xl text-accent"></i>
                    </div>
                    <h3 class="text-lg font-bold mb-3 text-white">多重安全保障</h3>
                    <p class="text-white/70">
                        搭载AI避障系统、多重备份动力、应急着陆模式等安全配置，确保飞行过程零事故，全方位保障人员与货物安全。
                    </p>
                </div>
                <div class="bg-neutral/50 border border-rocket/10 p-6 rounded-sm hover:border-rocket/30 transition-colors duration-300 opacity-0" data-animation-delay="1.9s">
                    <div class="w-12 h-12 bg-rocket/20 flex items-center justify-center mb-4">
                        <i class="fa fa-satellite text-xl text-rocket"></i>
                    </div>
                    <h3 class="text-lg font-bold mb-3 text-white">精准探测技术</h3>
                    <p class="text-white/70">
                        探空火箭搭载高精度传感器与数据传输系统，测量精度达行业领先水平，支持多参数同步采集与实时传输。
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- 核心团队区 - 成员介绍 -->
    <section id="team" class="py-24 bg-dark">
        <div class="container mx-auto px-4 md:px-8">
            <div class="text-center mb-16">
                <h2 class="text-[clamp(1.8rem,3vw,2.5rem)] font-tech font-bold mb-4 text-white">核心团队</h2>
                <p class="text-white/70 max-w-2xl mx-auto">由培侨书院与培侨信义学校优秀学生组成的创新团队，汇聚航空航天、自动化、计算机等多领域青年才俊</p>
                <div class="w-24 h-1 bg-accent mx-auto mt-6 rounded-full"></div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- 团队成员卡片1 -->
                <div class="bg-neutral border border-accent/20 rounded-sm overflow-hidden hover-3d-tech team-card opacity-0" data-animation-delay="0.1s">
                    <div class="h-64 overflow-hidden relative group">
                        <img src="https://picsum.photos/id/1005/600/600" alt="团队成员" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110">
                        <div class="absolute inset-0 bg-gradient-to-t from-neutral to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-500 flex items-end justify-center pb-6">
                            <div class="text-center">
                                <p class="text-white text-sm mb-2">培侨书院 航空航天工程方向</p>
                                <div class="flex justify-center gap-3">
                                    <a href="#" class="w-8 h-8 bg-accent/80 rounded-full flex items-center justify-center text-dark hover:bg-accent transition-colors">
                                        <i class="fa fa-linkedin"></i>
                                    </a>
                                    <a href="#" class="w-8 h-8 bg-accent/80 rounded-full flex items-center justify-center text-dark hover:bg-accent transition-colors">
                                        <i class="fa fa-github"></i>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="p-6 text-center">
                        <h3 class="text-xl font-bold mb-2 text-white">陈宇航</h3>
                        <p class="text-accent mb-3 font-medium">创始人 / 首席架构师</p>
                        <p class="text-white/70 text-sm mb-1">培侨书院 高中</p>
                        <p class="text-white/50 text-xs mb-4">国家级大学生创新项目负责人</p>
                        <p class="text-white/70 text-sm mb-4">
                            主导飞行器与探空火箭整体架构设计，拥有多项专利技术，曾获国际大学生航空设计大赛金奖。
                        </p>
                    </div>
                </div>

                <!-- 团队成员卡片2 -->
                <div class="bg-neutral border border-accent/20 rounded-sm overflow-hidden hover-3d-tech team-card opacity-0" data-animation-delay="0.3s">
                    <div class="h-64 overflow-hidden relative group">
                        <img src="https://picsum.photos/id/1006/600/600" alt="团队成员" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110">
                        <div class="absolute inset-0 bg-gradient-to-t from-neutral to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-500 flex items-end justify-center pb-6">
                            <div class="text-center">
                                <p class="text-white text-sm mb-2">培侨信义学校 自动化方向</p>
                                <div class="flex justify-center gap-3">
                                    <a href="#" class="w-8 h-8 bg-accent/80 rounded-full flex items-center justify-center text-dark hover:bg-accent transition-colors">
                                        <i class="fa fa-linkedin"></i>
                                    </a>
                                    <a href="#" class="w-8 h-8 bg-accent/80 rounded-full flex items-center justify-center text-dark hover:bg-accent transition-colors">
                                        <i class="fa fa-github"></i>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="p-6 text-center">
                        <h3 class="text-xl font-bold mb-2 text-white">林晚晴</h3>
                        <p class="text-accent mb-3 font-medium">技术总监</p>
                        <p class="text-white/70 text-sm mb-1">培侨信义学校 高中</p>
                        <p class="text-white/50 text-xs mb-4">AI控制算法专家</p>
                        <p class="text-white/70 text-sm mb-4">
                            负责飞控系统和火箭导航算法研发，曾在顶级学术期刊发表多篇论文，技术实力雄厚。
                        </p>
                    </div>
                </div>

                <!-- 团队成员卡片3 -->
                <div class="bg-neutral border border-accent/20 rounded-sm overflow-hidden hover-3d-tech team-card opacity-0" data-animation-delay="0.5s">
                    <div class="h-64 overflow-hidden relative group">
                        <img src="https://picsum.photos/id/1012/600/600" alt="团队成员" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110">
                        <div class="absolute inset-0 bg-gradient-to-t from-neutral to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-500 flex items-end justify-center pb-6">
                            <div class="text-center">
                                <p class="text-white text-sm mb-2">培侨书院 机械工程方向</p>
                                <div class="flex justify-center gap-3">
                                    <a href="#" class="w-8 h-8 bg-accent/80 rounded-full flex items-center justify-center text-dark hover:bg-accent transition-colors">
                                        <i class="fa fa-linkedin"></i>
                                    </a>
                                    <a href="#" class="w-8 h-8 bg-accent/80 rounded-full flex items-center justify-center text-dark hover:bg-accent transition-colors">
                                        <i class="fa fa-github"></i>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="p-6 text-center">
                        <h3 class="text-xl font-bold mb-2 text-white">王思远</h3>
                        <p class="text-accent mb-3 font-medium">结构设计负责人</p>
                        <p class="text-white/70 text-sm mb-1">培侨书院 高中</p>
                        <p class="text-white/50 text-xs mb-4">轻量化结构专家</p>
                        <p class="text-white/70 text-sm mb-4">
                            专注于飞行器与火箭结构设计与优化，主导多项核心产品结构研发，在材料选型与减重设计方面经验丰富。
                        </p>
                    </div>
                </div>

                <!-- 团队成员卡片4 -->
                <div class="bg-neutral border border-accent/20 rounded-sm overflow-hidden hover-3d-tech team-card opacity-0" data-animation-delay="0.7s">
                    <div class="h-64 overflow-hidden relative group">
                        <img src="https://picsum.photos/id/1025/600/600" alt="团队成员" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110">
                        <div class="absolute inset-0 bg-gradient-to-t from-neutral to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-500 flex items-end justify-center pb-6">
                            <div class="text-center">
                                <p class="text-white text-sm mb-2">培侨信义学校 工业设计方向</p>
                                <div class="flex justify-center gap-3">
                                    <a href="#" class="w-8 h-8 bg-accent/80 rounded-full flex items-center justify-center text-dark hover:bg-accent transition-colors">
                                        <i class="fa fa-linkedin"></i>
                                    </a>
                                    <a href="#" class="w-8 h-8 bg-accent/80 rounded-full flex items-center justify-center text-dark hover:bg-accent transition-colors">
                                        <i class="fa fa-github"></i>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="p-6 text-center">
                        <h3 class="text-xl font-bold mb-2 text-white">赵宇辰</h3>
                        <p class="text-accent mb-3 font-medium">产品经理</p>
                        <p class="text-white/70 text-sm mb-1">培侨信义学校 高中</p>
                        <p class="text-white/50 text-xs mb-4">用户体验专家</p>
                        <p class="text-white/70 text-sm mb-4">
                            负责飞行器与探空火箭产品规划与用户体验设计，擅长将技术与市场需求完美结合，推动产品落地。
                        </p>
                    </div>
                </div>
            </div>

            <!-- 团队活动图片展示 -->
            <div class="mt-16">
                <h3 class="text-xl font-tech font-bold mb-8 text-center text-white">团队风采</h3>
                <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
                    <div class="overflow-hidden rounded-sm hover-3d-tech">
                        <img src="https://picsum.photos/id/1048/600/400" alt="团队活动" class="w-full h-48 object-cover transition-transform duration-500 hover:scale-110">
                    </div>
                    <div class="overflow-hidden rounded-sm hover-3d-tech">
                        <img src="https://picsum.photos/id/1049/600/400" alt="团队活动" class="w-full h-48 object-cover transition-transform duration-500 hover:scale-110">
                    </div>
                    <div class="overflow-hidden rounded-sm hover-3d-tech">
                        <img src="https://picsum.photos/id/1050/600/400" alt="团队活动" class="w-full h-48 object-cover transition-transform duration-500 hover:scale-110">
                    </div>
                    <div class="overflow-hidden rounded-sm hover-3d-tech">
                        <img src="https://picsum.photos/id/1051/600/400" alt="团队活动" class="w-full h-48 object-cover transition-transform duration-500 hover:scale-110">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 底部 -->
    <footer class="bg-neutral py-12 border-t border-accent/20">
        <div class="container mx-auto px-4 md:px-8">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="mb-6 md:mb-0">
                    <div class="flex items-center gap-2 mb-4">
                        <span class="text-2xl font-tech font-bold tracking-wide text-white">星跃科技</span>
                        <span class="text-accent text-sm font-tech">AEROSPACE INNOVATION</span>
                    </div>
                    <p class="text-white/50 text-sm max-w-md">
                        专注高端智能飞行器与探空火箭研发，用科技改变飞行与探测体验
                    </p>
                </div>
                <div class="flex gap-6">
                    <a href="#" class="w-10 h-10 bg-dark rounded-full flex items-center justify-center text-white hover:bg-accent hover:text-dark transition-colors duration-300">
                        <i class="fa fa-weixin"></i>
                    </a>
                    <a href="#" class="w-10 h-10 bg-dark rounded-full flex items-center justify-center text-white hover:bg-accent hover:text-dark transition-colors duration-300">
                        <i class="fa fa-weibo"></i>
                    </a>
                    <a href="#" class="w-10 h-10 bg-dark rounded-full flex items-center justify-center text-white hover:bg-accent hover:text-dark transition-colors duration-300">
                        <i class="fa fa-linkedin"></i>
                    </a>
                    <a href="#" class="w-10 h-10 bg-dark rounded-full flex items-center justify-center text-white hover:bg-accent hover:text-dark transition-colors duration-300">
                        <i class="fa fa-github"></i>
                    </a>
                </div>
            </div>
            <div class="mt-8 pt-8 border-t border-white/10 text-center text-white/50 text-sm">
                <p>© 2025 星跃科技 All Rights Reserved. 京ICP备12345678号</p>
            </div>
        </div>
    </footer>

    <!-- JavaScript -->
    <script>
        // 移动端菜单切换
        document.getElementById('menuBtn').addEventListener('click', function() {
            const mobileMenu = document.getElementById('mobileMenu');
            mobileMenu.classList.toggle('hidden');
        });

        // 导航栏滚动效果
        window.addEventListener('scroll', function() {
            const navbar = document.getElementById('navbar');
            if (window.scrollY > 50) {
                navbar.classList.add('py-2', 'shadow-lg');
                navbar.classList.remove('py-4');
            } else {
                navbar.classList.add('py-4');
                navbar.classList.remove('py-2', 'shadow-lg');
            }
        });

        // 平滑滚动
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                    // 关闭移动端菜单
                    document.getElementById('mobileMenu').classList.add('hidden');
                }
            });
        });

        // 元素滚动动画
        function animateOnScroll() {
            const elements = document.querySelectorAll('.product-card, .team-card, .tech-card');
            
            elements.forEach(element => {
                const elementTop = element.getBoundingClientRect().top;
                const elementVisible = 150;
                
                if (elementTop < window.innerHeight - elementVisible) {
                    const delay = element.getAttribute('data-animation-delay');
                    element.style.animation = `fadeIn 1.2s ease-out forwards ${delay}`;
                }
            });
        }

        // 产品分类筛选功能
        function initProductFilter() {
            const allBtn = document.getElementById('allProducts');
            const aircraftBtn = document.getElementById('aircraftProducts');
            const rocketBtn = document.getElementById('rocketProducts');
            const allProducts = document.querySelectorAll('.product-card');
            
            // 全部产品
            allBtn.addEventListener('click', function() {
                allProducts.forEach(product => {
                    product.style.display = 'block';
                });
                // 更新按钮样式
                resetButtonStyles();
                this.classList.add('bg-accent', 'text-dark');
                this.classList.remove('bg-neutral', 'text-white');
            });
            
            // 飞行器产品
            aircraftBtn.addEventListener('click', function() {
                allProducts.forEach(product => {
                    if (product.getAttribute('data-category') === 'aircraft') {
                        product.style.display = 'block';
                    } else {
                        product.style.display = 'none';
                    }
                });
                // 更新按钮样式
                resetButtonStyles();
                this.classList.add('bg-accent', 'text-dark');
                this.classList.remove('bg-neutral', 'text-white');
            });
            
            // 探空火箭产品
            rocketBtn.addEventListener('click', function() {
                allProducts.forEach(product => {
                    if (product.getAttribute('data-category') === 'rocket') {
                        product.style.display = 'block';
                    } else {
                        product.style.display = 'none';
                    }
                });
                // 更新按钮样式
                resetButtonStyles();
                this.classList.add('bg-rocket', 'text-dark');
                this.classList.remove('bg-neutral', 'text-white');
            });
            
            // 重置按钮样式
            function resetButtonStyles() {
                [allBtn, aircraftBtn, rocketBtn].forEach(btn => {
                    btn.classList.remove('bg-accent', 'bg-rocket', 'text-dark');
                    btn.classList.add('bg-neutral', 'text-white');
                });
            }
        }

        // 初始加载时执行
        window.addEventListener('load', function() {
            animateOnScroll();
            initProductFilter();
        });
        // 滚动时执行
        window.addEventListener('scroll', animateOnScroll);
    </script>
</body>
</html>
