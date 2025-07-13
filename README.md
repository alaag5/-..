<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مدارس الفتح السودان الخاصة</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f0f2f5;
            color: #333;
            line-height: 1.6;
            direction: rtl; /* Right-to-left for Arabic */
            text-align: right;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 1rem;
        }
        .header {
            background: linear-gradient(to right, #4CAF50, #8BC34A); /* Green gradient */
            color: white;
            padding: 3rem 1rem;
            text-align: center;
            border-bottom-left-radius: 2rem;
            border-bottom-right-radius: 2rem;
            position: relative;
            overflow: hidden;
        }
        .header h1 {
            font-size: 3.5rem;
            font-weight: 800;
            margin-bottom: 0.5rem;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
        }
        .header p {
            font-size: 1.5rem;
            font-weight: 600;
            margin-bottom: 1.5rem;
            color: #e0f2f7;
        }
        .header .announcement {
            background-color: #FFC107; /* Amber highlight */
            color: #333;
            padding: 0.8rem 2.5rem;
            border-radius: 9999px;
            font-weight: 700;
            font-size: 1.3rem;
            display: inline-block;
            margin-top: 1rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .section-title {
            font-size: 2.5rem;
            font-weight: 700;
            color: #4CAF50; /* Green */
            margin-bottom: 2rem;
            text-align: center;
            position: relative;
            padding-bottom: 0.5rem;
        }
        .section-title::after {
            content: '';
            position: absolute;
            bottom: 0;
            right: 50%;
            transform: translateX(50%);
            width: 80px;
            height: 4px;
            background-color: #FFC107; /* Amber underline */
            border-radius: 2px;
        }
        .card {
            background-color: #ffffff;
            border-radius: 1.5rem;
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
            padding: 2rem;
            margin-bottom: 2rem;
        }
        .feature-list li {
            display: flex;
            align-items: flex-start;
            margin-bottom: 0.75rem;
            font-size: 1.1rem;
        }
        .feature-list li svg {
            color: #4CAF50;
            margin-left: 0.75rem; /* Margin for icon in RTL */
            flex-shrink: 0;
        }
        .contact-info a {
            color: #1a73e8;
            text-decoration: none;
            font-weight: 600;
        }
        .contact-info a:hover {
            text-decoration: underline;
        }
        .image-gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1rem;
            margin-top: 2rem;
        }
        .image-gallery img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 1rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        .image-gallery img:hover {
            transform: scale(1.03);
        }
        .footer {
            background-color: #333;
            color: white;
            padding: 2rem 1rem;
            text-align: center;
            border-top-left-radius: 2rem;
            border-top-right-radius: 2rem;
            margin-top: 3rem;
        }
        .footer p {
            font-size: 1.2rem;
            font-weight: 600;
        }
        .footer .slogan-final {
            font-size: 1.8rem;
            font-weight: 800;
            color: #9CCC65; /* Lighter green */
            margin-top: 0.5rem;
        }

        /* Responsive adjustments */
        @media (max-width: 768px) {
            .header h1 {
                font-size: 2.5rem;
            }
            .header p {
                font-size: 1.2rem;
            }
            .header .announcement {
                font-size: 1rem;
                padding: 0.6rem 1.5rem;
            }
            .section-title {
                font-size: 2rem;
            }
            .card {
                padding: 1.5rem;
            }
            .feature-list li {
                font-size: 1rem;
            }
            .image-gallery {
                grid-template-columns: 1fr;
            }
        }

        @media (max-width: 480px) {
            .header {
                padding: 2rem 1rem;
            }
            .header h1 {
                font-size: 2rem;
            }
            .header p {
                font-size: 1rem;
            }
            .header .announcement {
                font-size: 0.9rem;
                padding: 0.5rem 1rem;
            }
            .section-title {
                font-size: 1.8rem;
            }
            .card {
                padding: 1rem;
            }
            .feature-list li {
                font-size: 0.9rem;
            }
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header class="header">
        <div class="container">
            <h1>مدارس الفتح السودان الخاصة</h1>
            <p>نعود لنصنع جيلاً يعرف مستقبله</p>
            <div class="announcement">
                📢 بشرى سارة! إعادة فتح أبوابنا - التسجيل للعام الدراسي الجديد
            </div>
        </div>
    </header>

    <!-- About Section -->
    <section class="py-12">
        <div class="container">
            <h2 class="section-title">نبذة عن مدارس الفتح</h2>
            <div class="card">
                <p class="text-lg mb-4">
                    وبفضل الله، ومع عودة الاستقرار، نُعلن عن بداية التسجيل للعام الدراسي الجديد ابتداءً من:
                </p>
                <div class="flex flex-col md:flex-row items-center justify-around bg-blue-50 p-4 rounded-xl mb-6 shadow-sm text-blue-800 font-bold text-xl">
                    <div class="flex items-center mb-3 md:mb-0">
                        <svg class="w-6 h-6 ml-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"></path></svg>
                        <span>السبت 12 يوليو</span>
                    </div>
                    <div class="flex items-center">
                        <svg class="w-6 h-6 ml-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.828 0L6.343 16.657a4 4 0 115.656-5.656l1.414 1.414L17.657 16.657z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M18 12v3m-4 6h4m-4-6h4"></path></svg>
                        <span>الموقع: الخرطوم – الصحافة – محطة 7</span>
                    </div>
                </div>
                <h3 class="text-2xl font-bold text-gray-800 mb-3">المراحل التعليمية:</h3>
                <ul class="list-none p-0">
                    <li class="flex items-center text-lg mb-2">
                        <svg class="w-5 h-5 ml-2 text-green-500" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
                        المرحلة الابتدائية
                    </li>
                    <li class="flex items-center text-lg mb-2">
                        <svg class="w-5 h-5 ml-2 text-green-500" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
                        المرحلة المتوسطة
                    </li>
                    <li class="flex items-center text-lg">
                        <svg class="w-5 h-5 ml-2 text-green-500" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
                        المرحلة الثانوية
                    </li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Why Choose Us Section -->
    <section class="py-12 bg-gray-50">
        <div class="container">
            <h2 class="section-title">لماذا تختار مدارس الفتح؟</h2>
            <div class="card">
                <ul class="feature-list">
                    <li>
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
                        <span>عودة قوية بطاقم تعليمي متميز وخبرة طويلة</span>
                    </li>
                    <li>
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
                        <span>بيئة تعليمية آمنة ومحفزة للطلاب</span>
                    </li>
                    <li>
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
                        <span>تركيز على الجودة الأكاديمية والتربية الأخلاقية</span>
                    </li>
                    <li>
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
                        <span>أنشطة ثقافية ورياضية لتنمية شخصية الطالب</span>
                    </li>
                    <li>
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
                        <span>متابعة يومية للطلاب وتقارير لأولياء الأمور</span>
                    </li>
                    <li>
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
                        <span>تسهيلات في رسوم الدراسة ومواصلات منظمة</span>
                    </li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="py-12">
        <div class="container">
            <h2 class="section-title">للتسجيل والاستفسار</h2>
            <div class="card text-center">
                <p class="text-xl font-bold mb-4">لا تفوتوا الفرصة لإلحاق أبنائكم بمدرسة ذات سمعة طيبة وتاريخ عريق في التعليم!</p>
                <div class="contact-info flex flex-col items-center justify-center space-y-3">
                    <a href="tel:+249115520205" class="flex items-center text-lg">
                        <svg class="w-6 h-6 ml-2 text-purple-600" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.774a11.037 11.037 0 006.103 6.103l.774-1.548a1 1 0 011.06-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z"></path></svg>
                        +249 11 552 0205
                    </a>
                    <a href="tel:+249912345502" class="flex items-center text-lg">
                        <svg class="w-6 h-6 ml-2 text-purple-600" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.774a11.037 11.037 0 006.103 6.103l.774-1.548a1 1 0 011.06-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z"></path></svg>
                        +249 912 345 502
                    </a>
                    <a href="tel:+249123096220" class="flex items-center text-lg">
                        <svg class="w-6 h-6 ml-2 text-purple-600" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.774a11.037 11.037 0 006.103 6.103l.774-1.548a1 1 0 011.06-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z"></path></svg>
                        +249 123 096 220
                    </a>
                    <a href="tel:+249123099965" class="flex items-center text-lg">
                        <svg class="w-6 h-6 ml-2 text-purple-600" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.774a11.037 11.037 0 006.103 6.103l.774-1.548a1 1 0 011.06-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z"></path></svg>
                        +249 123 099 965
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Image Gallery Section -->
    <section class="py-12 bg-gray-50">
        <div class="container">
            <h2 class="section-title">معرض الصور</h2>
            <div class="image-gallery">
                <img id="img1" src="https://placehold.co/400x300/E0F2F7/000000?text=Loading..." alt="صورة طلاب في فصل دراسي">
                <img id="img2" src="https://placehold.co/400x300/E0F2F7/000000?text=Loading..." alt="صورة معلمين">
                <img id="img3" src="https://placehold.co/400x300/E0F2F7/000000?text=Loading..." alt="صورة شعار المدرسة">
                <img id="img4" src="https://placehold.co/400x300/E0F2F7/000000?text=Loading..." alt="صورة فريق إداري">
                <img id="img5" src="https://placehold.co/400x300/E0F2F7/000000?text=Loading..." alt="صورة طلاب في فصل دراسي آخر">
            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer class="footer">
        <div class="container">
            <p>مدارس الفتح السودان الخاصة © 2024. جميع الحقوق محفوظة.</p>
            <p class="slogan-final">📚 نعود لنصنع جيلاً يعرف مستقبله</p>
        </div>
    </footer>

    <script>
        // Function to load images using contentFetchId
        function loadImage(elementId, contentFetchId) {
            const imgElement = document.getElementById(elementId);
            if (imgElement) {
                // Construct the URL using contentFetchId
                imgElement.src = `/${contentFetchId}`;
                imgElement.onerror = () => {
                    console.error(`Failed to load image: ${contentFetchId}`);
                    // Fallback to a placeholder if the actual image fails to load
                    imgElement.src = `https://placehold.co/400x300/E0F2F7/000000?text=Image+Load+Error`;
                };
            }
        }

        // Load the specific images using their contentFetchIds
        window.onload = function() {
            loadImage('img1', 'uploaded:image.png-67d3da30-b9ef-4b25-be4e-989e45049c37');
            loadImage('img2', 'uploaded:image.png-6ec972fe-99de-432c-a0c3-b4d651b81332');
            loadImage('img3', 'uploaded:image.png-f557d424-6258-4c41-ad9e-2e42cc24c867');
            loadImage('img4', 'uploaded:image.png-e4ff45bb-1340-421b-89dd-5f82eae27db1');
            loadImage('img5', 'uploaded:image.png-fdf93494-c027-4c4b-94a4-8c4128b65024');
        };
    </script>
</body>
</html>

