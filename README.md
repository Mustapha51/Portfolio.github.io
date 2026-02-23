<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مصطفى هاني - بورتفوليو أخصائى   سوشيال ميديا</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@300;400;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Cairo', 'sans-serif'],
                    },
                    colors: {
                        primary: '#2563eb', // Blue
                        secondary: '#1e40af', // Dark Blue
                        dark: '#0f172a',
                        light: '#f8fafc',
                    }
                }
            }
        }
    </script>
    <style>
        body { font-family: 'Cairo', sans-serif; }
        .glass-card {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
        .gradient-text {
            background: linear-gradient(to left, #2563eb, #06b6d4);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased selection:bg-primary selection:text-white">

    <!-- Navbar -->
    <nav class="fixed w-full z-50 transition-all duration-300 glass-card shadow-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16 items-center">
                <div class="flex-shrink-0 font-bold text-2xl text-dark">
                    مصطفى <span class="text-primary">هاني</span>
                </div>
                <div class="hidden md:flex space-x-8 space-x-reverse">
                    <a href="#about" class="text-slate-600 hover:text-primary font-semibold transition">عني</a>
                    <a href="#media-buying" class="text-slate-600 hover:text-primary font-semibold transition">إدارة الحملات</a>
                    <a href="#copywriting" class="text-slate-600 hover:text-primary font-semibold transition">كتابة المحتوى</a>
                    <a href="#experience" class="text-slate-600 hover:text-primary font-semibold transition">الخبرات</a>
                    <a href="#contact" class="text-slate-600 hover:text-primary font-semibold transition">تواصل معي</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="about" class="pt-32 pb-20 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto flex flex-col-reverse md:flex-row items-center gap-12">
        <div class="flex-1 text-center md:text-right">
            <h2 class="text-lg md:text-xl text-primary font-bold mb-2">أهلاً بك، أنا مصطفى هاني 👋</h2>
            <h1 class="text-4xl md:text-6xl font-extrabold text-dark leading-tight mb-6">
                أخصائي سوشيال ميديا <br> و<span class="gradient-text">صانع محتوي</span>
            </h1>
            <p class="text-lg text-slate-600 mb-8 max-w-2xl leading-relaxed">
                متخصص في إدارة الحملات الإعلانية (Media Buying) بميزانيات ضخمة وتحقيق أعلى عائد على الاستثمار (ROI)، بالإضافة إلى خبرة في كتابة المحتوى (Copywriting) الجذاب والقريب للجمهور المصري والعربي.
            </p>
            
            <!-- معلومات التواصل في قسم عني -->
           

            <div class="flex flex-wrap gap-4 justify-center md:justify-start">
                <a href="#media-buying" class="bg-primary hover:bg-secondary text-white px-8 py-3 rounded-full font-bold transition shadow-lg shadow-blue-500/30">
                    شاهد أرقامي <i class="fas fa-chart-line mr-2"></i>
                </a>
                <a href="#copywriting" class="bg-white border-2 border-slate-200 hover:border-primary text-slate-700 hover:text-primary px-8 py-3 rounded-full font-bold transition shadow-sm">
                    اقرأ كتاباتي <i class="fas fa-pen-nib mr-2"></i>
                </a>
            </div>
        </div>
        <div class="flex-1 relative">
            <!-- Placeholder for Profile Picture -->
            <div class="w-72 h-72 md:w-96 md:h-96 bg-gradient-to-tr from-blue-100 to-cyan-50 rounded-full mx-auto shadow-2xl overflow-hidden border-4 border-white flex items-center justify-center relative">
                <i class="fas fa-user-tie text-9xl text-slate-300"></i>
                <!-- Instructions: Replace the src below with your actual photo URL -->
                <!-- <img src="YOUR_PHOTO_URL_HERE" alt="Mustafa Hany" class="w-full h-full object-cover absolute inset-0"> -->
            </div>
        </div>
    </section>

    <!-- Stats Highlights -->
    <section class="bg-dark text-white py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
                <div>
                    <div class="text-4xl font-extrabold text-blue-400 mb-2">+373K ج.م</div>
                    <div class="text-slate-400 font-semibold">ميزانيات تمت إدارتها</div>
                </div>
                <div>
                    <div class="text-4xl font-extrabold text-blue-400 mb-2">12.72 ج.م</div>
                    <div class="text-slate-400 font-semibold">أفضل تكلفة للعميل المحتمل (CPL)</div>
                </div>
                <div>
                    <div class="text-4xl font-extrabold text-blue-400 mb-2">0.02 ج.م</div>
                    <div class="text-slate-400 font-semibold">أفضل تكلفة للتفاعل (CPE)</div>
                </div>
                <div>
                    <div class="text-4xl font-extrabold text-blue-400 mb-2">$2,800+</div>
                    <div class="text-slate-400 font-semibold">ميزانيات بحملات دولية (B2B/B2C)</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Media Buying Section -->
    <section id="media-buying" class="py-20 bg-slate-50 px-4 sm:px-6 lg:px-8">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-dark mb-4">إدارة الحملات الإعلانية (Media Buying)</h2>
                <p class="text-slate-600 max-w-2xl mx-auto">أرقام حقيقية ونتائج ملموسة. أركز على تقليل التكلفة وزيادة الجودة من خلال الاستهداف الدقيق وتحليل البيانات المستمر.</p>
            </div>

            <div class="grid md:grid-cols-3 gap-8">
                <!-- Case Study 1 -->
                <div class="bg-white rounded-2xl shadow-sm border border-slate-100 p-6 hover:shadow-xl transition duration-300">
                    <div class="w-12 h-12 bg-blue-100 text-primary rounded-lg flex items-center justify-center text-xl mb-4">
                        <i class="fas fa-bullseye"></i>
                    </div>
                    <h3 class="text-xl font-bold text-dark mb-2">حملات التفاعل (Engagement)</h3>
                    <p class="text-slate-500 mb-6 text-sm">إدارة حملات تفاعل ضخمة بأسعار تنافسية جداً لزيادة الوعي بالعلامة التجارية وبناء جمهور متفاعل.</p>
                    <div class="space-y-3">
                        <div class="flex justify-between items-center pb-2 border-b border-slate-50">
                            <span class="text-slate-600">التفاعل المحقق:</span>
                            <span class="font-bold text-dark">16,697</span>
                        </div>
                        <div class="flex justify-between items-center pb-2 border-b border-slate-50">
                            <span class="text-slate-600">تكلفة التفاعل (CPE):</span>
                            <span class="font-bold text-green-500">0.0255 ج.م</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <span class="text-slate-600">إجمالي الصرف:</span>
                            <span class="font-bold text-dark">426.21 ج.م</span>
                        </div>
                    </div>
                    <a href="https://drive.google.com/file/d/1cgW8fBZSGxTthNX2aCvTMW_RxHdZEPft/view?usp=drive_link" target="_blank" class="mt-6 flex items-center justify-center w-full bg-blue-50 text-primary hover:bg-primary hover:text-white font-bold py-2 rounded-lg transition duration-300">
                        شاهد النتائج <i class="fas fa-external-link-alt mr-2 text-sm"></i>
                    </a>
                </div>

                <!-- Case Study 2 -->
                <div class="bg-white rounded-2xl shadow-sm border border-slate-100 p-6 hover:shadow-xl transition duration-300">
                    <div class="w-12 h-12 bg-purple-100 text-purple-600 rounded-lg flex items-center justify-center text-xl mb-4">
                        <i class="fas fa-users"></i>
                    </div>
                    <h3 class="text-xl font-bold text-dark mb-2">توليد العملاء المحتملين (Lead Gen)</h3>
                    <p class="text-slate-500 mb-6 text-sm">اقتناص عملاء محتملين بجودة عالية وبتكلفة منخفضة لتغذية قسم المبيعات بفرص حقيقية.</p>
                    <div class="space-y-3">
                        <div class="flex justify-between items-center pb-2 border-b border-slate-50">
                            <span class="text-slate-600">عدد الـ Leads:</span>
                            <span class="font-bold text-dark">52</span>
                        </div>
                        <div class="flex justify-between items-center pb-2 border-b border-slate-50">
                            <span class="text-slate-600">تكلفة الـ Lead:</span>
                            <span class="font-bold text-green-500">12.72 ج.م</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <span class="text-slate-600">إجمالي الصرف:</span>
                            <span class="font-bold text-dark">661.67 ج.م</span>
                        </div>
                    </div>
                    <a href="https://drive.google.com/file/d/11gfNVUI1QoRNInfNC6SnYRgZuR04il26/view?usp=drive_link" target="_blank" class="mt-6 flex items-center justify-center w-full bg-purple-50 text-purple-600 hover:bg-purple-600 hover:text-white font-bold py-2 rounded-lg transition duration-300">
                        شاهد النتائج <i class="fas fa-external-link-alt mr-2 text-sm"></i>
                    </a>
                </div>

                <!-- Case Study 3 -->
                <div class="bg-white rounded-2xl shadow-sm border border-slate-100 p-6 hover:shadow-xl transition duration-300">
                    <div class="w-12 h-12 bg-green-100 text-green-600 rounded-lg flex items-center justify-center text-xl mb-4">
                        <i class="fas fa-globe-americas"></i>
                    </div>
                    <h3 class="text-xl font-bold text-dark mb-2">الحملات الدولية / جدولة اجتماعات</h3>
                    <p class="text-slate-500 mb-6 text-sm">العمل على حملات تستهدف أسواق خارجية بالدولار لجدولة اجتماعات عمل (B2B/High Ticket).</p>
                    <div class="space-y-3">
                        <div class="flex justify-between items-center pb-2 border-b border-slate-50">
                            <span class="text-slate-600">اجتماعات مجدولة:</span>
                            <span class="font-bold text-dark">25</span>
                        </div>
                        <div class="flex justify-between items-center pb-2 border-b border-slate-50">
                            <span class="text-slate-600">تكلفة الاجتماع:</span>
                            <span class="font-bold text-green-500">$34.50</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <span class="text-slate-600">مرات الظهور (Imp):</span>
                            <span class="font-bold text-dark">194,053</span>
                        </div>
                    </div>
                    <a href="https://drive.google.com/file/d/17XfM-JRFL01WIy8zypHgFq0JmSsNdYsv/view?usp=drive_link" target="_blank" class="mt-6 flex items-center justify-center w-full bg-green-50 text-green-600 hover:bg-green-600 hover:text-white font-bold py-2 rounded-lg transition duration-300">
                        شاهد النتائج <i class="fas fa-external-link-alt mr-2 text-sm"></i>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Copywriting Section -->
    <section id="copywriting" class="py-20 bg-white px-4 sm:px-6 lg:px-8">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-dark mb-4">كتابة المحتوى (Copywriting)</h2>
                <p class="text-slate-600 max-w-2xl mx-auto">أؤمن بقوة القصة. أكتب محتوى بأسلوب قريب للقلب، يجمع بين التحفيز، السرد القصصي (Storytelling)، والوعي، بلهجة مصرية سلسة ومؤثرة.</p>
            </div>

            <div class="grid md:grid-cols-2 gap-10">
                <!-- Post 1 -->
                <div class="bg-slate-50 rounded-2xl p-8 border border-slate-100 shadow-sm relative overflow-hidden group">
                    <div class="absolute top-0 right-0 w-2 h-full bg-blue-500"></div>
                    <div class="flex justify-between items-start mb-4">
                        <h3 class="text-xl font-bold text-dark">مقال/بوست: قصة نجاح وروحانيات</h3>
                        <span class="bg-blue-100 text-blue-800 text-xs font-semibold px-2.5 py-0.5 rounded">تحفيز / Storytelling</span>
                    </div>
                    <p class="text-slate-600 leading-relaxed mb-6 italic text-sm md:text-base">
                        "علي شاب زي اي شاب مصري مجتهد وبيحاول يطور من نفسه. نفسه يوصل للبوزشن الفولاني وعايز يقبض المرتب الفولاني عشان يحقق هدفه. بس للاسف في وسط زحمه الدنيا بيحس انه تايه. ديما كان في حاجه ناقصه... حاجه واحده بس بتهدي الدوشه اللي في دماغه دي... الصلاه. كان ديما بيهرب من مشاكله للصلاه. حلم عمره انه يسافر يصلي في الحرم..."
                    </p>
                    <a href="https://drive.google.com/file/d/1jttGoWH2wm5jlhI0xJNOPoUPyoo_Q6yP/view?usp=drive_link" target="_blank" class="text-primary font-bold hover:text-secondary transition flex items-center">
                        اقرأ المزيد <i class="fas fa-arrow-left mr-2 text-sm"></i>
                    </a>
                </div>

                <!-- Post 2 -->
                <div class="bg-slate-50 rounded-2xl p-8 border border-slate-100 shadow-sm relative overflow-hidden group">
                    <div class="absolute top-0 right-0 w-2 h-full bg-rose-500"></div>
                    <div class="flex justify-between items-start mb-4">
                        <h3 class="text-xl font-bold text-dark">مقال: حاجات لازم تعرفها قبل الجواز</h3>
                        <span class="bg-rose-100 text-rose-800 text-xs font-semibold px-2.5 py-0.5 rounded">وعي / أسلوب ساخر</span>
                    </div>
                    <p class="text-slate-600 leading-relaxed mb-6 italic text-sm md:text-base">
                        "عايز تتجوز ها ؟؟ ... حقك يا بيه ومحدش يقدر يقولك حاجه. بس فيه حاجات لازم تعرفها قبل الجواز عشان متبقاش عبيط وترجع تعيط وتبقي الاستاذ صيوحه علي سن ورمح 😂 يبنى الجواز ليه اصول. اول حاجه لازم تبقى راجل. اه والله زي ما بقولك كده. والرجوله هنا ملهاش علاقه بالذكوريه ولا الزعيق والصوت العالي وفرد العضلات..."
                    </p>
                    <a href="https://drive.google.com/file/d/11evna2acwK0N3Or5-e0xDvetrR_3Kpy1/view?usp=drive_link" target="_blank" class="text-primary font-bold hover:text-secondary transition flex items-center">
                        اقرأ المزيد <i class="fas fa-arrow-left mr-2 text-sm"></i>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Experience Section -->
    <section id="experience" class="py-20 bg-slate-50 px-4 sm:px-6 lg:px-8">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-dark mb-4">الخبرات السابقة</h2>
                <p class="text-slate-600 max-w-2xl mx-auto">أماكن وشركات ساهمت في نجاحها من خلال إدارة الحملات التسويقية وصناعة المحتوى.</p>
            </div>

            <div class="grid md:grid-cols-3 gap-8">
                <!-- Experience 1: DFA -->
                <div class="bg-white rounded-2xl shadow-sm border border-slate-100 p-8 hover:shadow-xl transition duration-300 flex flex-col items-center text-center group">
                    <div class="w-32 h-32 mb-6 rounded-2xl overflow-hidden border-2 border-slate-100 shadow-sm flex items-center justify-center bg-white group-hover:border-blue-400 transition duration-300 p-2">
                        <img src="https://drive.google.com/uc?export=view&id=1Gu9do-lxUxhu9Tm9sOtmzEIDowwGi8HK" alt="معهد DFA" class="max-w-full max-h-full object-contain">
                    </div>
                    <h3 class="text-2xl font-bold text-dark mb-2">معهد DFA</h3>
                    <p class="text-slate-500 mb-8 text-sm">شريك في النجاح وإدارة التسويق</p>
                    <div class="mt-auto w-full space-y-3">
                        <a href="https://dfa-eg.net/" target="_blank" class="flex items-center justify-center w-full bg-slate-100 hover:bg-slate-200 text-slate-700 font-bold py-2.5 rounded-lg transition duration-300">
                            <i class="fas fa-globe mr-2"></i> زيارة الموقع
                        </a>
                        <a href="https://drive.google.com/file/d/1Gu9do-lxUxhu9Tm9sOtmzEIDowwGi8HK/view?usp=sharing" target="_blank" class="flex items-center justify-center w-full bg-blue-50 text-blue-600 hover:bg-blue-600 hover:text-white font-bold py-2.5 rounded-lg transition duration-300">
                            <i class="fas fa-image mr-2"></i> عرض الصورة
                        </a>
                    </div>
                </div>

                <!-- Experience 2: Joe's Venture -->
                <div class="bg-white rounded-2xl shadow-sm border border-slate-100 p-8 hover:shadow-xl transition duration-300 flex flex-col items-center text-center group">
                    <div class="w-32 h-32 mb-6 rounded-2xl overflow-hidden border-2 border-slate-100 shadow-sm flex items-center justify-center bg-white group-hover:border-purple-400 transition duration-300 p-2">
                        <img src="https://drive.google.com/uc?export=view&id=1zDXA0xZUI34iiIOfF2RXI33ETjcQpZVv" alt="Joe's Venture" class="max-w-full max-h-full object-contain">
                    </div>
                    <h3 class="text-2xl font-bold text-dark mb-2">Joe's Venture</h3>
                    <p class="text-slate-500 mb-8 text-sm">شريك في النجاح وإدارة التسويق</p>
                    <div class="mt-auto w-full space-y-3">
                        <a href="https://joesventure.com/" target="_blank" class="flex items-center justify-center w-full bg-slate-100 hover:bg-slate-200 text-slate-700 font-bold py-2.5 rounded-lg transition duration-300">
                            <i class="fas fa-globe mr-2"></i> زيارة الموقع
                        </a>
                        <a href="https://drive.google.com/file/d/1zDXA0xZUI34iiIOfF2RXI33ETjcQpZVv/view?usp=sharing" target="_blank" class="flex items-center justify-center w-full bg-purple-50 text-purple-600 hover:bg-purple-600 hover:text-white font-bold py-2.5 rounded-lg transition duration-300">
                            <i class="fas fa-image mr-2"></i> عرض الصورة
                        </a>
                    </div>
                </div>

                <!-- Experience 3: Beach Safari -->
                <div class="bg-white rounded-2xl shadow-sm border border-slate-100 p-8 hover:shadow-xl transition duration-300 flex flex-col items-center text-center group">
                    <div class="w-32 h-32 mb-6 rounded-2xl overflow-hidden border-2 border-slate-100 shadow-sm flex items-center justify-center bg-white group-hover:border-orange-400 transition duration-300 p-2">
                        <img src="https://drive.google.com/uc?export=view&id=1j7mpUVU1-geC-U1le-lLT5uivkSxDr4E" alt="Beach Safari Resort" class="max-w-full max-h-full object-contain">
                    </div>
                    <h3 class="text-2xl font-bold text-dark mb-2">Beach Safari Resort</h3>
                    <p class="text-slate-500 mb-8 text-sm">شريك في النجاح وإدارة التسويق</p>
                    <div class="mt-auto w-full space-y-3">
                        <a href="https://www.facebook.com/Beachsafarinubianresort/" target="_blank" class="flex items-center justify-center w-full bg-slate-100 hover:bg-slate-200 text-slate-700 font-bold py-2.5 rounded-lg transition duration-300">
                            <i class="fab fa-facebook mr-2"></i> صفحة الفيسبوك
                        </a>
                        <a href="https://drive.google.com/file/d/1j7mpUVU1-geC-U1le-lLT5uivkSxDr4E/view?usp=sharing" target="_blank" class="flex items-center justify-center w-full bg-orange-50 text-orange-600 hover:bg-orange-500 hover:text-white font-bold py-2.5 rounded-lg transition duration-300">
                            <i class="fas fa-image mr-2"></i> عرض الصورة
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills & Tools -->
    <section class="py-16 bg-white border-t border-slate-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h3 class="text-2xl font-bold text-dark mb-8">أدوات ومهارات أتقنها</h3>
            <div class="flex flex-wrap justify-center gap-4">
                <span class="px-6 py-3 bg-white shadow-sm border border-slate-200 rounded-full font-semibold text-slate-700 flex items-center gap-2"><i class="fab fa-facebook text-blue-600"></i> Meta Ads Manager</span>
                <span class="px-6 py-3 bg-white shadow-sm border border-slate-200 rounded-full font-semibold text-slate-700 flex items-center gap-2"><i class="fas fa-pen-fancy text-purple-600"></i> Copywriting</span>
                <span class="px-6 py-3 bg-white shadow-sm border border-slate-200 rounded-full font-semibold text-slate-700 flex items-center gap-2"><i class="fas fa-chart-pie text-green-600"></i> Data Analysis</span>
                <span class="px-6 py-3 bg-white shadow-sm border border-slate-200 rounded-full font-semibold text-slate-700 flex items-center gap-2"><i class="fas fa-funnel-dollar text-orange-500"></i> Lead Generation</span>
                <span class="px-6 py-3 bg-white shadow-sm border border-slate-200 rounded-full font-semibold text-slate-700 flex items-center gap-2"><i class="fas fa-bullhorn text-red-500"></i> Campaign Strategy</span>
            </div>
        </div>
    </section>

    <!-- Footer / Contact -->
    <footer id="contact" class="bg-dark text-white py-12">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="text-3xl font-bold mb-6">مستعد لزيادة أرباحك ومبيعاتك؟</h2>
            <p class="text-slate-400 mb-8">سواء كنت تبحث عن إعلانات تحقق أعلى عائد، أو محتوى يبني ولاء حقيقي مع عملائك، أنا هنا لمساعدتك.</p>
            
            <div class="flex justify-center gap-6 mb-8">
                <a href="https://www.linkedin.com/in/mustafa-hany/" target="_blank" class="w-12 h-12 bg-slate-800 hover:bg-primary rounded-full flex items-center justify-center transition duration-300 text-xl">
                    <i class="fab fa-linkedin-in"></i>
                </a>
                <a href="https://wa.me/201098405820" target="_blank" class="w-12 h-12 bg-slate-800 hover:bg-green-500 rounded-full flex items-center justify-center transition duration-300 text-xl">
                    <i class="fab fa-whatsapp"></i>
                </a>
                <a href="mailto:mustafa.hany41@gmail.com" class="w-12 h-12 bg-slate-800 hover:bg-blue-400 rounded-full flex items-center justify-center transition duration-300 text-xl">
                    <i class="fas fa-envelope"></i>
                </a>
            </div>
            
            <div class="text-slate-500 text-sm">
                &copy; 2024 مصطفى هاني. جميع الحقوق محفوظة.
            </div>
        </div>
    </footer>

</body>
</html>
