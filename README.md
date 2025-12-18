<!DOCTYPE html>

<html lang="id" class="scroll-smooth">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Hadiyatunnisa - Bidan, Konselor Menyusui & Founder Gentle Breastfeeding</title>

    <script src="https://cdn.tailwindcss.com"></script>

    <script src="https://unpkg.com/lucide@latest"></script>

    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700&family=Playfair+Display:ital,wght@0,400;0,700;1,400&display=swap" rel="stylesheet">

    <style>

        body {

            font-family: 'Plus Jakarta Sans', sans-serif;

        }

        h1, h2, h3, h4, .font-serif {

            font-family: 'Playfair Display', serif;

        }

        .bg-sage { background-color: #f1f4f2; }

        .text-sage-dark { color: #4a5d54; }

        .border-sage-dark { border-color: #4a5d54; }

        .btn-primary {

            background-color: #88a096;

            transition: all 0.3s ease;

        }

        .btn-primary:hover {

            background-color: #6b8278;

            transform: translateY(-2px);

        }

        .card-shadow {

            box-shadow: 0 10px 30px rgba(0,0,0,0.05);

        }

        .wa-float {

            position: fixed;

            bottom: 20px;

            right: 20px;

            background-color: #25d366;

            color: white;

            width: 60px;

            height: 60px;

            border-radius: 50px;

            text-align: center;

            font-size: 30px;

            box-shadow: 2px 2px 10px rgba(0,0,0,0.2);

            z-index: 100;

            display: flex;

            align-items: center;

            justify-content: center;

            transition: all 0.3s ease;

        }

        .wa-float:hover {

            transform: scale(1.1);

            background-color: #128c7e;

        }

    </style>

</head>

<body class="bg-white text-gray-800 relative">


    <!-- Floating WhatsApp Button -->

    <a href="https://wa.me/c/6281327319351" target="_blank" class="wa-float" title="Chat via WhatsApp">

        <i data-lucide="message-circle"></i>

    </a>


    <!-- Navigation -->

    <nav class="fixed w-full z-50 bg-white/90 backdrop-blur-md border-b border-gray-100 transition-all duration-300">

        <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">

            <a href="#home" class="text-2xl font-bold text-sage-dark tracking-tight flex items-center gap-2">

                <i data-lucide="heart-handshake" class="w-6 h-6"></i>

                <span>Hallo<span class="font-normal italic">Bunda</span></span>

            </a>

            <div class="hidden md:flex space-x-8 font-medium text-sm uppercase tracking-widest">

                <a href="#home" class="hover:text-sage-dark transition">Beranda</a>

                <a href="#about" class="hover:text-sage-dark transition">Tentang</a>

                <a href="#services" class="hover:text-sage-dark transition">Layanan</a>

                <a href="#founder" class="hover:text-sage-dark transition">Founder</a>

                <a href="#contact" class="hover:text-sage-dark transition">Kontak</a>

            </div>

            <button class="md:hidden text-sage-dark p-2" onclick="toggleMenu()">

                <i data-lucide="menu" class="w-6 h-6"></i>

            </button>

        </div>

        <!-- Mobile Menu -->

        <div id="mobile-menu" class="hidden md:hidden bg-white border-b border-gray-100 px-6 py-4 space-y-4 shadow-lg absolute w-full left-0 top-full">

            <a href="#home" class="block py-2 text-sage-dark hover:bg-sage/50 rounded px-2 transition" onclick="toggleMenu()">Beranda</a>

            <a href="#about" class="block py-2 text-sage-dark hover:bg-sage/50 rounded px-2 transition" onclick="toggleMenu()">Tentang</a>

            <a href="#services" class="block py-2 text-sage-dark hover:bg-sage/50 rounded px-2 transition" onclick="toggleMenu()">Layanan</a>

            <a href="#founder" class="block py-2 text-sage-dark hover:bg-sage/50 rounded px-2 transition" onclick="toggleMenu()">Founder</a>

            <a href="#contact" class="block py-2 text-sage-dark hover:bg-sage/50 rounded px-2 transition" onclick="toggleMenu()">Kontak</a>

        </div>

    </nav>


    <!-- Hero Section -->

    <section id="home" class="pt-32 pb-20 px-6 bg-sage overflow-hidden">

        <div class="max-w-7xl mx-auto grid md:grid-cols-2 gap-12 items-center relative z-10">

            <div class="order-2 md:order-1 fade-in-up">

                <span class="inline-block px-4 py-1 bg-white rounded-full text-xs font-semibold tracking-widest text-sage-dark mb-6 uppercase shadow-sm">

                    <i data-lucide="award" class="w-4 h-4 inline-block mr-1 mb-0.5"></i> Pengalaman 10+ Tahun

                </span>

                <h1 class="text-5xl md:text-6xl lg:text-7xl font-bold leading-tight mb-6 text-gray-900 font-serif">

                    Membersamai Ibu, Merangkul <span class="italic text-sage-dark font-normal underline decoration-sage-dark/30">Kehidupan Baru.</span>

                </h1>

                <p class="text-lg text-gray-700 mb-8 max-w-lg leading-relaxed">

                    "Assalamu'alaikum, saya Bidan Hadiyatunnisa. Lebih dari satu dekade, hati saya tertambat pada perjalanan ajaib setiap ibu. Dari detak jantung pertama dalam rahim hingga tetes ASI pertama yang penuh cinta, saya hadir untuk mendampingi dengan kelembutan, memastikan Anda merasa tenang dan berdaya di setiap langkah."

                </p>

                <div class="flex flex-wrap gap-4">

                    <a href="https://wa.me/c/6281327319351" target="_blank" class="btn-primary text-white px-8 py-4 rounded-full font-semibold flex items-center gap-2 shadow-md hover:shadow-lg">

                        <i data-lucide="message-circle" class="w-5 h-5"></i> Konsultasi via WA

                    </a>

                    <a href="#services" class="border-2 border-sage-dark text-sage-dark px-8 py-4 rounded-full font-semibold hover:bg-sage-dark hover:text-white transition flex items-center gap-2">

                        Lihat Layanan <i data-lucide="arrow-down" class="w-5 h-5"></i>

                    </a>

                </div>

            </div>

            <div class="order-1 md:order-2 relative fade-in-up animation-delay-200">

                <div class="aspect-[3/4] md:aspect-[4/5] bg-gray-200 rounded-[2rem] overflow-hidden card-shadow relative z-10 border-4 border-white">

                    <img src="1000010745.jpg" alt="Bidan Hadiyatunnisa" class="w-full h-full object-cover">

                </div>

                <div class="absolute -bottom-6 -left-6 bg-white p-6 rounded-2xl card-shadow hidden sm:block border border-gray-100 z-20 animate-bounce-slow">

                    <div class="flex items-center gap-4">

                        <div class="bg-sage p-3 rounded-full">

                            <i data-lucide="heart" class="text-sage-dark w-6 h-6"></i>

                        </div>

                        <div>

                            <p class="font-bold text-xl text-gray-900">Penuh Dedikasi</p>

                            <p class="text-sm text-gray-500">Sejak Hamil hingga Menyusui</p>

                        </div>

                    </div>

                </div>

                <!-- Decorative elements -->

                <div class="absolute top-10 right-10 w-20 h-20 bg-sage-dark/10 rounded-full -z-10 blur-2xl"></div>

                <div class="absolute bottom-10 left-10 w-32 h-32 bg-yellow-100/50 rounded-full -z-10 blur-2xl"></div>

            </div>

        </div>

        <!-- Background wave pattern SVG (optional/subtle) -->

        <div class="absolute bottom-0 left-0 w-full overflow-hidden leading-none rotate-180">

            <svg class="relative block w-[calc(130%+1.3px)] h-[100px]" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">

                <path d="M321.39,56.44c58-10.79,114.16-30.13,172-41.86,82.39-16.72,168.19-17.73,250.45-.39C823.78,31,906.67,72,985.66,92.83c70.05,18.48,146.53,26.09,214.34,3V0H0V27.35A600.21,600.21,0,0,0,321.39,56.44Z" class="fill-white"></path>

            </svg>

        </div>

    </section>


    <!-- About Section -->

    <section id="about" class="py-24 px-6 bg-white relative">

        <div class="max-w-4xl mx-auto text-center relative z-10">

            <span class="text-sage-dark font-semibold uppercase tracking-widest mb-4 block">Filosofi Saya</span>

            <h2 class="text-3xl md:text-5xl font-bold mb-8 italic font-serif text-gray-900">Lebih dari Sekadar Profesi, Ini Adalah Panggilan Hati.</h2>

            <p class="text-xl leading-relaxed text-gray-600 italic relative px-8 md:px-0">

                <span class="absolute top-0 left-0 text-6xl text-sage-dark/20 font-serif -translate-x-4 -translate-y-4">“</span>

                Melalui <span class="font-semibold text-sage-dark">Gentle Breastfeeding</span>, saya berkomitmen untuk menciptakan ruang aman bagi para ibu. Saya percaya bahwa dengan dukungan yang tepat, informasi yang valid, dan sentuhan penuh empati, setiap ibu dapat menjalani proses kehamilan dan menyusui dengan penuh percaya diri dan kebahagiaan.

                <span class="absolute bottom-0 right-0 text-6xl text-sage-dark/20 font-serif translate-x-2 translate-y-4">”</span>

            </p>

            <div class="mt-10">

                <img src="1000010745.jpg" alt="Tanda Tangan Bidan Hadiyatunnisa" class="w-24 h-24 rounded-full object-cover mx-auto border-4 border-sage shadow-sm">

                <p class="mt-4 font-bold text-lg">Bidan Hadiyatunnisa</p>

                <p class="text-sm text-gray-500">Founder Gentle Breastfeeding</p>

            </div>

        </div>

    </section>


    <!-- Services Section -->

    <section id="services" class="py-24 px-6 bg-gray-50 relative">

        <div class="max-w-7xl mx-auto relative z-10">

            <div class="mb-16 text-center md:text-left">

                <span class="text-sage-dark font-semibold uppercase tracking-widest mb-2 block">Layanan Kami</span>

                <h2 class="text-4xl font-bold mb-4 font-serif text-gray-900">Dukungan Holistik untuk Ibu & Bayi</h2>

                <p class="text-gray-600 max-w-2xl">Pendampingan profesional yang disesuaikan dengan kebutuhan unik Anda, dari masa kehamilan hingga perjalanan menyusui.</p>

            </div>


            <div class="grid md:grid-cols-3 gap-8">

                <!-- Service 1 -->

                <div class="bg-white p-10 rounded-[2rem] card-shadow transition hover:-translate-y-2 hover:shadow-lg group">

                    <div class="w-16 h-16 bg-sage rounded-2xl flex items-center justify-center mb-8 group-hover:bg-sage-dark transition-colors">

                        <i data-lucide="baby" class="text-sage-dark w-8 h-8 group-hover:text-white transition-colors"></i>

                    </div>

                    <h3 class="text-2xl font-bold mb-4 font-serif">Prenatal Care</h3>

                    <p class="text-gray-600 mb-6 leading-relaxed">Persiapan fisik dan mental menyambut buah hati dengan pendekatan gentle birth yang memberdayakan.</p>

                    <ul class="space-y-2 text-gray-500 text-sm">

                        <li class="flex items-center gap-2"><i data-lucide="check-circle" class="w-4 h-4 text-sage-dark"></i> Konseling Kehamilan Sehat</li>

                        <li class="flex items-center gap-2"><i data-lucide="check-circle" class="w-4 h-4 text-sage-dark"></i> Persiapan Persalinan Nyaman</li>

                    </ul>

                </div>


                <!-- Service 2 -->

                <div class="bg-white p-10 rounded-[2rem] card-shadow transition hover:-translate-y-2 hover:shadow-lg border-2 border-sage-dark/20 group relative overflow-hidden">

                     <div class="absolute top-0 right-0 bg-sage-dark text-white text-xs font-bold px-3 py-1 rounded-bl-lg uppercase tracking-wider">Populer</div>

                    <div class="w-16 h-16 bg-sage rounded-2xl flex items-center justify-center mb-8 group-hover:bg-sage-dark transition-colors">

                        <i data-lucide="heart-handshake" class="text-sage-dark w-8 h-8 group-hover:text-white transition-colors"></i>

                    </div>

                    <h3 class="text-2xl font-bold mb-4 font-serif">Konseling Laktasi</h3>

                    <p class="text-gray-600 mb-6 leading-relaxed">Pendampingan intensif untuk mengatasi tantangan menyusui seperti pelekatan, suplai ASI, dan relaktasi.</p>

                    <ul class="space-y-2 text-gray-500 text-sm">

                        <li class="flex items-center gap-2"><i data-lucide="check-circle" class="w-4 h-4 text-sage-dark"></i> Home Visit / Online Consultation</li>

                        <li class="flex items-center gap-2"><i data-lucide="check-circle" class="w-4 h-4 text-sage-dark"></i> Manajemen ASI Perah</li>

                    </ul>

                </div>


                <!-- Service 3 -->

                <div class="bg-white p-10 rounded-[2rem] card-shadow transition hover:-translate-y-2 hover:shadow-lg group">

                    <div class="w-16 h-16 bg-sage rounded-2xl flex items-center justify-center mb-8 group-hover:bg-sage-dark transition-colors">

                        <i data-lucide="graduation-cap" class="text-sage-dark w-8 h-8 group-hover:text-white transition-colors"></i>

                    </div>

                    <h3 class="text-2xl font-bold mb-4 font-serif">Edukasi Founder</h3>

                    <p class="text-gray-600 mb-6 leading-relaxed">Kelas dan workshop eksklusif dari Gentle Breastfeeding untuk membangun kepercayaan diri orang tua baru.</p>

                    <ul class="space-y-2 text-gray-500 text-sm">

                        <li class="flex items-center gap-2"><i data-lucide="check-circle" class="w-4 h-4 text-sage-dark"></i> Webinar Gentle Breastfeeding</li>

                        <li class="flex items-center gap-2"><i data-lucide="check-circle" class="w-4 h-4 text-sage-dark"></i> Kelas Privat & Grup</li>

                    </ul>

                </div>

            </div>

        </div>

    </section>


    <!-- Founder Section -->

    <section id="founder" class="py-24 px-6 bg-white relative overflow-hidden">

        <div class="max-w-7xl mx-auto relative z-10">

            <div class="bg-sage-dark rounded-[3rem] p-12 md:p-20 text-white relative overflow-hidden shadow-xl">

                <!-- Decorative background pattern within the card -->

                <div class="absolute inset-0 opacity-10">

                    <svg width="100%" height="100%" xmlns="http://www.w3.org/2000/svg">

                        <defs>

                            <pattern id="dots" width="20" height="20" patternUnits="userSpaceOnUse">

                                <circle cx="10" cy="10" r="2" fill="currentColor" />

                            </pattern>

                        </defs>

                        <rect width="100%" height="100%" fill="url(#dots)" />

                    </svg>

                </div>


                <div class="relative z-10 flex flex-col md:flex-row items-center gap-12">

                    <div class="md:w-2/3">

                        <span class="text-white/70 font-semibold uppercase tracking-widest mb-4 block">Tentang Komunitas</span>

                        <h2 class="text-4xl md:text-5xl font-bold mb-6 font-serif">Membangun <span class="italic">Gentle Breastfeeding</span></h2>

                        <p class="text-lg opacity-90 mb-8 leading-relaxed font-light">

                            Saya mendirikan <strong class="font-semibold">Gentle Breastfeeding</strong> sebagai wadah edukasi dan dukungan. Visi kami adalah mematahkan mitos, memberikan informasi berbasis bukti, dan merangkul setiap ibu agar dapat menikmati proses menyusui dengan tenang, nyaman, dan penuh kasih sayang.

                        </p>

                        <div class="flex flex-wrap gap-4">

                            <a href="https://www.tiktok.com/@BreastfeedTeacher" target="_blank" class="bg-white/10 hover:bg-white/20 p-4 rounded-xl flex items-center gap-3 transition group">

                                <div class="bg-black/20 p-2 rounded-lg group-hover:bg-black/30 transition"><i data-lucide="music-2" class="w-5 h-5"></i></div>

                                <span class="font-semibold">Ikuti di TikTok</span>

                            </a>

                            <a href="https://www.instagram.com/breastfeed_teacher" target="_blank" class="bg-white/10 hover:bg-white/20 p-4 rounded-xl flex items-center gap-3 transition group">

                                <div class="bg-pink-600/20 p-2 rounded-lg group-hover:bg-pink-600/30 transition"><i data-lucide="instagram" class="w-5 h-5"></i></div>

                                <span class="font-semibold">Ikuti di Instagram</span>

                            </a>

                        </div>

                    </div>

                    <div class="md:w-1/3 text-center relative">

                        <div class="inline-block p-8 border-4 border-white/20 rounded-full animate-pulse-slow relative z-10 bg-sage-dark">

                            <span class="text-6xl font-bold block font-serif">10+</span>

                            <span class="block text-sm uppercase tracking-widest mt-2">Tahun Dedikasi</span>

                        </div>

                         <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-48 h-48 bg-white/5 rounded-full -z-10 blur-2xl"></div>

                    </div>

                </div>

            </div>

        </div>

    </section>


    <!-- Contact Section -->

    <section id="contact" class="py-24 px-6 bg-gray-50 relative">

        <div class="max-w-7xl mx-auto grid md:grid-cols-2 gap-16 relative z-10">

            <div>

                <span class="text-sage-dark font-semibold uppercase tracking-widest mb-2 block">Hubungi Saya</span>

                <h2 class="text-4xl font-bold mb-6 font-serif text-gray-900">Mari Mulai Perjalanan Anda</h2>

                <p class="text-gray-600 mb-10 text-lg">Jangan ragu untuk menghubungi saya. Saya siap mendengarkan dan mendampingi Anda dalam setiap langkah kehamilan dan menyusui.</p>

                

                <div class="space-y-8">

                    <div class="flex items-start gap-4 group">

                        <div class="bg-white p-4 rounded-2xl text-sage-dark shadow-sm group-hover:shadow-md transition border border-gray-100"><i data-lucide="mail" class="w-6 h-6"></i></div>

                        <div>

                            <p class="font-bold text-lg text-gray-900">Email</p>

                            <a href="mailto:hadiyatunnisa14@gmail.com" class="text-gray-600 hover:text-sage-dark transition">hadiyatunnisa14@gmail.com</a>

                        </div>

                    </div>

                    <div class="flex items-start gap-4 group">

                        <div class="bg-white p-4 rounded-2xl text-sage-dark shadow-sm group-hover:shadow-md transition border border-gray-100"><i data-lucide="message-circle" class="w-6 h-6"></i></div>

                        <div>

                            <p class="font-bold text-lg text-gray-900">WhatsApp (Katalog)</p>

                            <a href="https://wa.me/c/6281327319351" target="_blank" class="text-gray-600 hover:text-sage-dark transition">Klik untuk Chat & Lihat Layanan</a>

                        </div>

                    </div>

                    <div class="flex items-start gap-4 group">

                        <div class="bg-white p-4 rounded-2xl text-sage-dark shadow-sm group-hover:shadow-md transition border border-gray-100"><i data-lucide="share-2" class="w-6 h-6"></i></div>

                        <div>

                            <p class="font-bold text-lg text-gray-900">Sosial Media</p>

                            <div class="flex gap-4 mt-3">

                                <a href="https://www.instagram.com/breastfeed_teacher" target="_blank" class="text-white bg-gradient-to-tr from-yellow-400 via-red-500 to-purple-500 p-2 rounded-lg hover:opacity-90 transition shadow-sm"><i data-lucide="instagram" class="w-5 h-5"></i></a>

                                <a href="https://www.tiktok.com/@BreastfeedTeacher" target="_blank" class="text-white bg-black p-2 rounded-lg hover:opacity-90 transition shadow-sm"><i data-lucide="music-2" class="w-5 h-5"></i></a>

                            </div>

                        </div>

                    </div>

                </div>

            </div>


            <div class="bg-white p-8 md:p-12 rounded-[2rem] border border-gray-100 card-shadow relative overflow-hidden">

                <div class="absolute top-0 right-0 w-32 h-32 bg-sage/50 rounded-bl-[5rem] -z-10"></div>

                <h3 class="text-2xl font-bold mb-6 font-serif text-gray-900">Kirim Pesan Cepat</h3>

                <form id="contactForm" class="space-y-6">

                    <div>

                        <label class="block text-sm font-semibold mb-2 text-gray-700">Nama Lengkap</label>

                        <div class="relative">

                            <div class="absolute inset-y-0 left-0 pl-4 flex items-center pointer-events-none text-gray-400">

                                <i data-lucide="user" class="w-5 h-5"></i>

                            </div>

                            <input type="text" id="contactName" class="w-full pl-12 pr-4 py-4 rounded-xl border border-gray-200 focus:outline-none focus:ring-2 focus:ring-sage-dark/30 focus:border-sage-dark transition bg-gray-50 focus:bg-white" placeholder="Contoh: Ibu Anisa" required>

                        </div>

                    </div>

                    <div>

                        <label class="block text-sm font-semibold mb-2 text-gray-700">Layanan yang Diminati</label>

                         <div class="relative">

                            <div class="absolute inset-y-0 left-0 pl-4 flex items-center pointer-events-none text-gray-400">

                                <i data-lucide="list" class="w-5 h-5"></i>

                            </div>

                            <select id="contactService" class="w-full pl-12 pr-10 py-4 rounded-xl border border-gray-200 focus:outline-none focus:ring-2 focus:ring-sage-dark/30 focus:border-sage-dark transition bg-gray-50 focus:bg-white appearance-none">

                                <option value="Konsultasi Menyusui">Konsultasi Menyusui</option>

                                <option value="Prenatal Care">Prenatal Care (Kehamilan)</option>

                                <option value="Kelas/Edukasi">Kelas/Edukasi Gentle Breastfeeding</option>

                                <option value="Lainnya">Lainnya</option>

                            </select>

                             <div class="absolute inset-y-0 right-0 pr-4 flex items-center pointer-events-none text-gray-400">

                                <i data-lucide="chevron-down" class="w-5 h-5"></i>

                            </div>

                        </div>

                    </div>

                    <div>

                        <label class="block text-sm font-semibold mb-2 text-gray-700">Pesan / Pertanyaan</label>

                        <div class="relative">

                            <textarea id="contactMessage" rows="4" class="w-full p-4 rounded-xl border border-gray-200 focus:outline-none focus:ring-2 focus:ring-sage-dark/30 focus:border-sage-dark transition bg-gray-50 focus:bg-white resize-none" placeholder="Tuliskan kondisi atau pertanyaan Anda di sini..."></textarea>

                        </div>

                    </div>

                    <button type="button" onclick="sendToWA()" class="w-full btn-primary text-white py-4 rounded-xl font-bold text-lg flex justify-center items-center gap-3 shadow-md hover:shadow-lg">

                         Kirim via WhatsApp <i data-lucide="send" class="w-5 h-5"></i>

                    </button>

                    <p class="text-xs text-center text-gray-500 mt-4">Anda akan diarahkan ke WhatsApp untuk mengirim pesan ini.</p>

                </form>

            </div>

        </div>

    </section>


    <!-- Footer -->

    <footer class="py-12 bg-white border-t border-gray-100 text-center relative z-10">

        <div class="max-w-7xl mx-auto px-6">

            <div class="flex flex-col items-center gap-6">

                 <a href="#home" class="text-2xl font-bold text-sage-dark tracking-tight flex items-center gap-2">

                    <i data-lucide="heart-handshake" class="w-6 h-6"></i>

                    <span>Gentle<span class="font-normal italic">Breastfeeding</span></span>

                </a>

                <p class="text-gray-600 max-w-md">Membersamai ibu dengan kelembutan, ilmu, dan kasih sayang dalam setiap perjalanan menyusui.</p>

                <div class="flex space-x-6 text-gray-400 mt-2">

                    <a href="https://www.instagram.com/breastfeed_teacher" target="_blank" class="hover:text-sage-dark transition p-2 hover:bg-sage/20 rounded-full" title="Instagram">

                        <i data-lucide="instagram" class="w-6 h-6"></i>

                    </a>

                    <a href="https://www.tiktok.com/@BreastfeedTeacher" target="_blank" class="hover:text-sage-dark transition p-2 hover:bg-sage/20 rounded-full" title="TikTok">

                        <i data-lucide="music-2" class="w-6 h-6"></i>

                    </a>

                    <a href="mailto:hadiyatunnisa14@gmail.com" class="hover:text-sage-dark transition p-2 hover:bg-sage/20 rounded-full" title="Email">

                        <i data-lucide="mail" class="w-6 h-6"></i>

                    </a>

                </div>

                <p class="text-sm text-gray-400 mt-8 border-t border-gray-100 pt-8 w-full max-w-md mx-auto">

                    &copy; 2024 Bidan Hadiyatunnisa. Hak Cipta Dilindungi. <br>Founder Gentle Breastfeeding.

                </p>

            </div>

        </div>

    </footer>


    <script>

        // Initialize Lucide Icons

        lucide.createIcons();


        // Mobile Menu Toggle

        function toggleMenu() {

            const menu = document.getElementById('mobile-menu');

            const isHidden = menu.classList.contains('hidden');

            

            if (isHidden) {

                menu.classList.remove('hidden');

                setTimeout(() => {

                     menu.classList.add('opacity-100', 'translate-y-0');

                     menu.classList.remove('opacity-0', '-translate-y-2');

                }, 10); // Small delay for transition to trigger

            } else {

                 menu.classList.add('opacity-0', '-translate-y-2');

                 menu.classList.remove('opacity-100', 'translate-y-0');

                 setTimeout(() => {

                    menu.classList.add('hidden');

                }, 300); // Match transition duration

            }

        }

        

        // Initial state for mobile menu animation

        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenu.classList.add('transition-all', 'duration-300', 'ease-in-out', 'opacity-0', '-translate-y-2');



        // WhatsApp Redirect Function with Enhanced Validation & Formatting

        function sendToWA() {

            const nameInput = document.getElementById('contactName');

            const serviceInput = document.getElementById('contactService');

            const messageInput = document.getElementById('contactMessage');

            

            const name = nameInput.value.trim();

            const service = serviceInput.value;

            const message = messageInput.value.trim();

            

            if (!name) {

                alert("Mohon isi nama lengkap Anda.");

                nameInput.focus();

                return;

            }

            

            let text = `Halo Bidan Hadiyatunnisa, perkenalkan nama saya *${name}*.\n\nSaya tertarik dengan layanan: *${service}*.\n`;

            

            if (message) {

                text += `\nPesan/Pertanyaan saya:\n${message}\n`;

            }

            

            text += `\nMohon informasinya lebih lanjut. Terima kasih.`;


            const encodedText = encodeURIComponent(text);

            

            // Redirect to the provided Catalog/Profile WA

            window.open(`https://wa.me/c/6281327319351?text=${encodedText}`, '_blank');

        }


        // Navbar Scroll Effect & Active Link Highlighter

        window.addEventListener('scroll', () => {

            const nav = document.querySelector('nav');

            if (window.scrollY > 20) {

                nav.classList.add('shadow-md', 'bg-white/95');

                nav.classList.remove('bg-white/90');

            } else {

                nav.classList.remove('shadow-md', 'bg-white/95');

                 nav.classList.add('bg-white/90');

            }


            // Highlight active section link

            const sections = document.querySelectorAll('section');

            const navLinks = document.querySelectorAll('nav .hidden.md\\:flex a');

            

            let current = '';

            sections.forEach(section => {

                const sectionTop = section.offsetTop;

                const sectionHeight = section.clientHeight;

                if (pageYOffset >= sectionTop - 150) {

                    current = section.getAttribute('id');

                }

            });


            navLinks.forEach(link => {

                link.classList.remove('text-sage-dark', 'font-bold');

                if (link.getAttribute('href').substring(1) === current) {

                    link.classList.add('text-sage-dark', 'font-bold');

                }

            });

        });


        // Simple Fade-in Animation on Scroll (Intersection Observer)

        const fadeElems = document.querySelectorAll('.fade-in-up');

        const appearOptions = {

            threshold: 0.2,

            rootMargin: "0px 0px -50px 0px"

        };


        const appearOnScroll = new IntersectionObserver(function(entries, appearOnScroll) {

            entries.forEach(entry => {

                if (!entry.isIntersecting) {

                    return;

                } else {

                    entry.target.classList.add('appear');

                    appearOnScroll.unobserve(entry.target);

                }

            });

        }, appearOptions);


        fadeElems.forEach(elem => {

            appearOnScroll.observe(elem);

        });


    </script>

    <style>

        /* Custom Animation Classes */

        .fade-in-up {

            opacity: 0;

            transform: translateY(20px);

            transition: opacity 0.6s ease-out, transform 0.6s ease-out;

        }

        .fade-in-up.appear {

            opacity: 1;

            transform: translateY(0);

        }

        .animation-delay-200 {

            transition-delay: 0.2s;

        }

        .animate-bounce-slow {

            animation: bounce 3s infinite;

        }

        @keyframes bounce {

            0%, 100% { transform: translateY(0); }

            50% { transform: translateY(-10px); }

        }

         .animate-pulse-slow {

            animation: pulse 3s cubic-bezier(0.4, 0, 0.6, 1) infinite;

        }

        @keyframes pulse {

            0%, 100% { opacity: 1; }

            50% { opacity: .8; }

        }

        /* Custom scrollbar for clearer look */

        ::-webkit-scrollbar {

            width: 10px;

        }

        ::-webkit-scrollbar-track {

            background: #f1f4f2;

        }

        ::-webkit-scrollbar-thumb {

            background: #88a096;

            border-radius: 5px;

        }

        ::-webkit-scrollbar-thumb:hover {

            background: #6b8278;

        }

    </style>

</body>

</html>
