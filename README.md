<!DOCTYPE html>
<html lang="ar" dir="rtl" class="scroll-smooth">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>برنامج الأشبال | الاستثمار الأذكى لعام 2026 لصناعة قادة المستقبل</title>
  
  <!-- Fonts: Cairo & Readex Pro -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;700;800;900&family=Readex+Pro:wght@400;500;600;700&display=swap" rel="stylesheet">
  
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  
  <!-- Lucide Icons CDN -->
  <script src="https://unpkg.com/lucide@latest"></script>

  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            brand: {
              navy: '#0F1E36',
              deep: '#0A1322',
              card: '#162544',
              coral: '#F43F5E',
              gold: '#EAB308',
              accent: '#3B82F6',
              light: '#F8FAFC'
            }
          },
          fontFamily: {
            cairo: ['Cairo', 'sans-serif'],
            readex: ['Readex Pro', 'sans-serif']
          }
        }
      }
    }
  </script>

  <style>
    body {
      font-family: 'Readex Pro', 'Cairo', sans-serif;
      background-color: #0A1322;
      color: #F8FAFC;
    }
    .gold-gradient-border {
      background: linear-gradient(135deg, #F59E0B, #FBBF24, #D97706);
    }
    .text-gold-gradient {
      background: linear-gradient(135deg, #FDE68A 0%, #F59E0B 50%, #D97706 100%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
    .glass-nav {
      background: rgba(10, 19, 34, 0.85);
      backdrop-filter: blur(12px);
      border-bottom: 1px solid rgba(255, 255, 255, 0.08);
    }
  </style>
</head>
<body class="antialiased selection:bg-rose-500 selection:text-white">

  <!-- NAVBAR -->
  <header class="fixed top-0 left-0 right-0 z-50 glass-nav transition-all duration-300">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex items-center justify-between h-20">
        
        <!-- Brand Identity / Official Logo -->
        <a href="#" class="flex items-center gap-3 group">
          <div class="w-12 h-12 rounded-xl bg-gradient-to-br from-rose-500 to-indigo-600 p-0.5 shadow-lg shadow-rose-500/20">
            <div class="w-full h-full bg-brand-deep rounded-[10px] flex items-center justify-center">
              <!-- Replicating the Cubs Gavel Toastmasters Logo -->
              <svg class="w-7 h-7 text-rose-500 group-hover:scale-110 transition-transform" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                <!-- Crown -->
                <path d="m2 4 3 12h14l3-12-6 7-4-7-4 7-6-7zm3 16h14" />
                <!-- Speaker Podium Base -->
                <circle cx="12" cy="11" r="2" />
                <path d="M7 21h10M12 13v8" />
              </svg>
            </div>
          </div>
          <div class="flex flex-col">
            <span class="text-xl font-black font-cairo tracking-wide text-white flex items-center gap-1.5">
              الأشبال <span class="text-xs px-2 py-0.5 rounded-full bg-rose-500/20 text-rose-400 font-normal">CUBS</span>
            </span>
            <span class="text-[11px] text-slate-400">قافل توستماسترز • نُمكّن القادة</span>
          </div>
        </a>

        <!-- Desktop Navigation -->
        <nav class="hidden md:flex items-center gap-8 text-sm font-medium text-slate-300">
          <a href="#about" class="hover:text-amber-400 transition-colors">عن البرنامج</a>
          <a href="#methodology" class="hover:text-amber-400 transition-colors">منهجية العمل</a>
          <a href="#roadmap" class="hover:text-amber-400 transition-colors">مسار التطوير</a>
          <a href="#pillars" class="hover:text-amber-400 transition-colors">المحاور العملية</a>
          <a href="#coach" class="hover:text-amber-400 transition-colors">المدرب</a>
          <a href="#guarantee" class="hover:text-amber-400 transition-colors">الضمان الذهبي</a>
        </nav>

        <!-- CTA Action -->
        <div class="hidden sm:flex items-center gap-4">
          <a href="#register" class="relative inline-flex items-center justify-center p-0.5 overflow-hidden text-sm font-bold text-white rounded-xl group bg-gradient-to-br from-amber-400 via-rose-500 to-indigo-600 group-hover:from-amber-400 group-hover:to-rose-600 shadow-lg shadow-rose-500/25 active:scale-95 transition-all">
            <span class="relative px-6 py-2.5 transition-all ease-in duration-75 bg-brand-deep rounded-[10px] group-hover:bg-opacity-0">
              سجل الآن لعام 2026
            </span>
          </a>
        </div>

        <!-- Mobile Menu Toggle -->
        <button id="mobileMenuBtn" class="md:hidden text-slate-300 hover:text-white focus:outline-none" aria-label="القائمة">
          <i data-lucide="menu" class="w-7 h-7"></i>
        </button>
      </div>
    </div>

    <!-- Mobile Drawer -->
    <div id="mobileMenu" class="hidden md:hidden bg-brand-navy/95 border-b border-white/10 px-6 py-6 transition-all">
      <div class="flex flex-col space-y-4 text-base">
        <a href="#about" class="text-slate-300 hover:text-amber-400 py-1">عن البرنامج</a>
        <a href="#methodology" class="text-slate-300 hover:text-amber-400 py-1">منهجية العمل</a>
        <a href="#roadmap" class="text-slate-300 hover:text-amber-400 py-1">مسار التطوير</a>
        <a href="#pillars" class="text-slate-300 hover:text-amber-400 py-1">المحاور العملية</a>
        <a href="#coach" class="text-slate-300 hover:text-amber-400 py-1">المدرب راكان النادر</a>
        <a href="#guarantee" class="text-slate-300 hover:text-amber-400 py-1">الضمان الذهبي</a>
        <a href="#register" class="mt-2 text-center py-3 bg-gradient-to-r from-rose-500 to-amber-500 text-white rounded-xl font-bold">
          احجز مقعد ابنك الآن
        </a>
      </div>
    </div>
  </header>

  <!-- HERO SECTION -->
  <section class="relative pt-32 pb-20 md:pt-40 md:pb-28 overflow-hidden">
    <!-- Atmospheric Background Glows -->
    <div class="absolute top-1/4 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[600px] h-[600px] bg-rose-500/10 rounded-full blur-[140px] pointer-events-none"></div>
    <div class="absolute top-1/3 right-10 w-96 h-96 bg-amber-500/10 rounded-full blur-[120px] pointer-events-none"></div>

    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
        
        <!-- Right Column: Content -->
        <div class="lg:col-span-7 text-center lg:text-right space-y-6">
          <div class="inline-flex items-center gap-2 px-4 py-2 rounded-full bg-slate-800/80 border border-slate-700/80 shadow-inner">
            <span class="flex h-2.5 w-2.5 rounded-full bg-rose-500 animate-pulse"></span>
            <span class="text-xs md:text-sm font-semibold text-amber-300">الاستثمار الأذكى لعام 2026 للأعمار من 7 حتى 18 سنة</span>
          </div>

          <h1 class="text-3xl sm:text-4xl lg:text-5xl xl:text-6xl font-black font-cairo leading-tight tracking-tight">
            لأن النخبة لا تُصنع بالصدفة..<br>
            <span class="text-gold-gradient">بل تُصنع بالمهارات القيادية</span>
          </h1>

          <p class="text-slate-300 text-base sm:text-lg lg:text-xl font-normal leading-relaxed max-w-2xl mx-auto lg:mx-0">
            برنامج تطويري نوعي ومكثف يحوّل طفلك أو يافعك من مجرد متلقٍ خجول إلى متحدث فصيح وقائد واثق يُبهر من حوله، عبر تدريب شخصي فردي (1:1) وورش تطبيقية حية لا تتجاوز 5 مشاركين.
          </p>

          <!-- CTAs -->
          <div class="flex flex-col sm:flex-row items-center justify-center lg:justify-start gap-4 pt-2">
            <a href="#register" class="w-full sm:w-auto px-8 py-4 bg-gradient-to-r from-rose-600 via-rose-500 to-amber-500 hover:from-rose-500 hover:to-amber-400 text-white font-bold rounded-2xl shadow-xl shadow-rose-600/30 transition-all transform hover:-translate-y-0.5 text-center flex items-center justify-center gap-2">
              <span>احجز مقعد ابنك الآن</span>
              <i data-lucide="arrow-left" class="w-5 h-5"></i>
            </a>
            <a href="#methodology" class="w-full sm:w-auto px-8 py-4 bg-slate-800/80 hover:bg-slate-700/80 border border-slate-700 text-slate-200 font-semibold rounded-2xl transition-all text-center flex items-center justify-center gap-2">
              <i data-lucide="play-circle" class="w-5 h-5 text-amber-400"></i>
              <span>استكشف المنهجية التطبيقية</span>
            </a>
          </div>

          <!-- Trust Badges & Accreditation Proof -->
          <div class="pt-6 border-t border-slate-800/80 grid grid-cols-2 sm:grid-cols-3 gap-4">
            <div class="flex items-center gap-3 bg-brand-navy/60 p-3 rounded-xl border border-slate-800">
              <div class="w-10 h-10 rounded-lg bg-emerald-500/10 flex items-center justify-center text-emerald-400 shrink-0">
                <i data-lucide="shield-check" class="w-5 h-5"></i>
              </div>
              <div class="text-right">
                <div class="text-xs font-bold text-white">ترخيص رسمي (هاوي)</div>
                <div class="text-[11px] text-slate-400">رقم الفسح 942240102959</div>
              </div>
            </div>

            <div class="flex items-center gap-3 bg-brand-navy/60 p-3 rounded-xl border border-slate-800">
              <div class="w-10 h-10 rounded-lg bg-amber-500/10 flex items-center justify-center text-amber-400 shrink-0">
                <i data-lucide="users" class="w-5 h-5"></i>
              </div>
              <div class="text-right">
                <div class="text-xs font-bold text-white">حد أقصى 5 مقاعد</div>
                <div class="text-[11px] text-slate-400">تركيز فائق وشخصي 1:1</div>
              </div>
            </div>

            <div class="col-span-2 sm:col-span-1 flex items-center gap-3 bg-brand-navy/60 p-3 rounded-xl border border-slate-800">
              <div class="w-10 h-10 rounded-lg bg-rose-500/10 flex items-center justify-center text-rose-400 shrink-0">
                <i data-lucide="award" class="w-5 h-5"></i>
              </div>
              <div class="text-right">
                <div class="text-xs font-bold text-white">الضمان الذهبي 100%</div>
                <div class="text-[11px] text-slate-400">استرداد كامل بدون شروط</div>
              </div>
            </div>
          </div>
        </div>

        <!-- Left Column: Hero Interactive Visual & Certificate Showcase -->
        <div class="lg:col-span-5 relative">
          <div class="relative mx-auto max-w-md lg:max-w-none">
            
            <!-- Main Hero Image Frame -->
            <div class="relative rounded-3xl overflow-hidden border-2 border-slate-700/60 shadow-2xl shadow-indigo-950/50 group">
              <img src="https://images.unsplash.com/photo-1577896851231-70ef18881754?auto=format&fit=crop&w=1200&q=80" 
                   alt="تدريب الخطابة والقيادة للشباب في نادي الأشبال" 
                   class="w-full h-[420px] object-cover group-hover:scale-105 transition-transform duration-700">
              <div class="absolute inset-0 bg-gradient-to-t from-brand-deep via-brand-deep/30 to-transparent"></div>
              
              <!-- Tag on image -->
              <div class="absolute bottom-6 right-6 left-6 p-4 rounded-2xl bg-brand-navy/90 border border-slate-700/80 backdrop-blur-md">
                <div class="flex items-center justify-between">
                  <div class="flex items-center gap-3">
                    <div class="w-10 h-10 rounded-full bg-rose-500/20 text-rose-400 flex items-center justify-center font-bold">
                      <i data-lucide="mic" class="w-5 h-5"></i>
                    </div>
                    <div>
                      <h4 class="text-sm font-bold text-white">لقاءات جافل توستماسترز الحية</h4>
                      <p class="text-xs text-slate-400">تطبيق حقيقي للمنصة والتأثير المباشر</p>
                    </div>
                  </div>
                  <span class="text-xs bg-emerald-500/20 text-emerald-400 px-2.5 py-1 rounded-full font-medium">معتمد</span>
                </div>
              </div>
            </div>

            <!-- Floating Card 1: Official Hawi Club Accreditation -->
            <div class="absolute -top-6 -right-6 bg-brand-card/95 border border-amber-500/30 p-3.5 rounded-2xl shadow-xl backdrop-blur-md flex items-center gap-3">
              <div class="w-11 h-11 rounded-xl bg-amber-500/20 flex items-center justify-center text-amber-400">
                <i data-lucide="file-badge" class="w-6 h-6"></i>
              </div>
              <div>
                <div class="text-[11px] text-amber-300 font-bold">رؤية المملكة 2030</div>
                <div class="text-xs font-black text-white">برنامج جودة الحياة (هاوي)</div>
              </div>
            </div>

            <!-- Floating Card 2: Diagnostic Impact Tracking -->
            <div class="absolute -bottom-6 -left-6 bg-brand-card/95 border border-slate-700 p-3.5 rounded-2xl shadow-xl backdrop-blur-md flex items-center gap-3">
              <div class="w-11 h-11 rounded-xl bg-rose-500/20 flex items-center justify-center text-rose-400">
                <i data-lucide="clipboard-check" class="w-6 h-6"></i>
              </div>
              <div>
                <div class="text-xs font-bold text-white">تقرير الأثر اليومي 10/10</div>
                <div class="text-[11px] text-slate-400">تشخيص دقيق لكل جلسة لولي الأمر</div>
              </div>
            </div>

          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- SECTION 2: WHY ASHBAL? (COMPARISON MATRIX) -->
  <section id="about" class="py-20 bg-brand-navy/40 border-y border-slate-800/80">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      
      <div class="text-center max-w-3xl mx-auto space-y-4 mb-16">
        <h2 class="text-xs uppercase tracking-widest text-amber-400 font-black">التميز والفارق الحقيقي</h2>
        <p class="text-3xl sm:text-4xl font-black font-cairo text-white">لماذا يختار الآباء الواعون "برنامج الأشبال"؟</p>
        <p class="text-slate-400 text-sm sm:text-base">
          لا نؤمن بالدورات الجماهيرية السطحية التي تُنسى بعد يومين. إليك الفارق الجوهري بين ما هو تقليدي وما نصنعه مع كل شبل:
        </p>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-8 max-w-5xl mx-auto">
        
        <!-- Standard/Traditional courses -->
        <div class="rounded-3xl p-8 bg-slate-900/60 border border-slate-800 space-y-6">
          <div class="flex items-center gap-3">
            <div class="w-10 h-10 rounded-xl bg-rose-500/10 text-rose-400 flex items-center justify-center">
              <i data-lucide="x-circle" class="w-6 h-6"></i>
            </div>
            <div>
              <h3 class="text-lg font-bold text-slate-200">الدورات والمراكز الجماعية التقليدية</h3>
              <p class="text-xs text-slate-500">منهج محفوظ ومتلقٍ سلبي</p>
            </div>
          </div>

          <ul class="space-y-4 text-sm text-slate-400">
            <li class="flex items-start gap-3">
              <i data-lucide="x" class="w-5 h-5 text-rose-500/70 shrink-0 mt-0.5"></i>
              <span>قاعات ممتلئة بـ 25 إلى 40 طالباً دون فرصة حقيقية للحديث والممارسة.</span>
            </li>
            <li class="flex items-start gap-3">
              <i data-lucide="x" class="w-5 h-5 text-rose-500/70 shrink-0 mt-0.5"></i>
              <span>منهج نظري صلب (قوالب جاهزة) يتجاهل الفروق الفردية وطبيعة شخصية الطفل.</span>
            </li>
            <li class="flex items-start gap-3">
              <i data-lucide="x" class="w-5 h-5 text-rose-500/70 shrink-0 mt-0.5"></i>
              <span>غياب المتابعة المستمرة وتقارير التشخيص المعيارية بعد انتهاء الحصة.</span>
            </li>
            <li class="flex items-start gap-3">
              <i data-lucide="x" class="w-5 h-5 text-rose-500/70 shrink-0 mt-0.5"></i>
              <span>مجرد شهادة حضور كرتونية دون أثر واقعي على سلوكه وجرأته.</span>
            </li>
          </ul>
        </div>

        <!-- The Ashbal Experience -->
        <div class="relative rounded-3xl p-8 bg-gradient-to-b from-brand-card to-slate-900 border-2 border-amber-500/40 shadow-2xl shadow-amber-500/5 space-y-6">
          <div class="absolute -top-3.5 left-8 bg-gradient-to-r from-amber-500 to-rose-500 text-brand-deep text-[11px] font-black px-3.5 py-1 rounded-full uppercase tracking-wider">
            المعيار الأثري لعام 2026
          </div>

          <div class="flex items-center gap-3">
            <div class="w-10 h-10 rounded-xl bg-amber-500/20 text-amber-400 flex items-center justify-center">
              <i data-lucide="check-circle" class="w-6 h-6"></i>
            </div>
            <div>
              <h3 class="text-lg font-bold text-white">منهجية برنامج الأشبال (Cubs)</h3>
              <p class="text-xs text-amber-300">تدريب شخصي، تشخيص، وممارسة قيادية كاملة</p>
            </div>
          </div>

          <ul class="space-y-4 text-sm text-slate-200">
            <li class="flex items-start gap-3">
              <i data-lucide="check" class="w-5 h-5 text-amber-400 shrink-0 mt-0.5"></i>
              <span><strong>إرشاد فردي 1:1</strong> وورش تفاعلية مصغرة بحد أقصى 5 مشاركين لكل مجموعة.</span>
            </li>
            <li class="flex items-start gap-3">
              <i data-lucide="check" class="w-5 h-5 text-amber-400 shrink-0 mt-0.5"></i>
              <span><strong>حلقة الإتقان العملي:</strong> (تعلّم ➔ طبّق ➔ جرّب ➔ توجيه وتصويب ➔ إعادة) حتى تصبح عادة.</span>
            </li>
            <li class="flex items-start gap-3">
              <i data-lucide="check" class="w-5 h-5 text-amber-400 shrink-0 mt-0.5"></i>
              <span><strong>تقرير الأثر اليومي (10 أقسام):</strong> تشخيص فوري لنقاط القوة وتوصيات الجلسة القادمة تُرسل لولي الأمر.</span>
            </li>
            <li class="flex items-start gap-3">
              <i data-lucide="check" class="w-5 h-5 text-amber-400 shrink-0 mt-0.5"></i>
              <span><strong>منصة توستماسترز حقيقية:</strong> نزول للميدان ومواجهة الجمهور وبناء الكاريزما القيادية.</span>
            </li>
          </ul>
        </div>

      </div>

      <!-- Real Program Photos Grid -->
      <div class="mt-16 pt-12 border-t border-slate-800">
        <div class="text-center mb-8">
          <span class="text-xs font-bold text-slate-400 uppercase tracking-wider">من الميدان • لقطات حية من تدريبات ولقاءات أشبالنا</span>
        </div>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
          <div class="rounded-2xl overflow-hidden border border-slate-800 group relative">
            <img src="https://images.unsplash.com/photo-1524178232363-1fb2b075b655?auto=format&fit=crop&w=800&q=80" alt="ورشة الإلقاء والخطابة للأشبال" class="w-full h-56 object-cover group-hover:scale-105 transition-transform duration-500">
            <div class="absolute inset-0 bg-gradient-to-t from-brand-deep via-transparent to-transparent flex items-end p-4">
              <span class="text-xs font-bold text-white">تمارين كسر حاجز الخوف والوقوف على المنصة</span>
            </div>
          </div>
          <div class="rounded-2xl overflow-hidden border border-slate-800 group relative">
            <img src="https://images.unsplash.com/photo-1511632765486-a01980e01a18?auto=format&fit=crop&w=800&q=80" alt="المعسكرات القيادية والتطويرية" class="w-full h-56 object-cover group-hover:scale-105 transition-transform duration-500">
            <div class="absolute inset-0 bg-gradient-to-t from-brand-deep via-transparent to-transparent flex items-end p-4">
              <span class="text-xs font-bold text-white">ورش العمل التفاعلية المصغرة (حد أقصى 5 أشبال)</span>
            </div>
          </div>
          <div class="rounded-2xl overflow-hidden border border-slate-800 group relative sm:col-span-2 lg:col-span-1">
            <img src="https://images.unsplash.com/photo-1544717305-2782549b5136?auto=format&fit=crop&w=800&q=80" alt="تدريب المحاكاة الإعلامية وصناعة المحتوى" class="w-full h-56 object-cover group-hover:scale-105 transition-transform duration-500">
            <div class="absolute inset-0 bg-gradient-to-t from-brand-deep via-transparent to-transparent flex items-end p-4">
              <span class="text-xs font-bold text-white">محاكاة المؤتمرات والتقديم الإعلامي والخطابي</span>
            </div>
          </div>
        </div>
      </div>

    </div>
  </section>

  <!-- SECTION 3: THE 3-TIER ROADMAP (INTERACTIVE TABS) -->
  <section id="roadmap" class="py-20 relative">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      
      <div class="text-center max-w-3xl mx-auto space-y-4 mb-16">
        <h2 class="text-xs uppercase tracking-widest text-rose-400 font-black">منهجية العمل الأثرية</h2>
        <p class="text-3xl sm:text-4xl font-black font-cairo text-white">خارطة الطريق لبناء القائد المؤثر (3 مستويات)</p>
        <p class="text-slate-400 text-sm sm:text-base">
          تدرج تدريبي مدروس بعناية ينقل الشبل تدريجياً عبر 3 محطات محورية تصنع الفارق في شخصيته وفكره وسلوكه:
        </p>
      </div>

      <!-- Roadmap Tab Triggers -->
      <div class="flex flex-wrap justify-center gap-3 mb-10">
        <button onclick="switchStage(1)" id="stageBtn1" class="stage-btn active px-6 py-3.5 rounded-2xl font-bold text-sm transition-all flex items-center gap-3 bg-gradient-to-r from-rose-600 to-rose-500 text-white shadow-lg shadow-rose-600/30">
          <span class="w-6 h-6 rounded-full bg-white/20 flex items-center justify-center text-xs">1</span>
          <span>المستوى الأول: مرحلة التمكين</span>
        </button>
        <button onclick="switchStage(2)" id="stageBtn2" class="stage-btn px-6 py-3.5 rounded-2xl font-bold text-sm transition-all flex items-center gap-3 bg-slate-800 text-slate-300 hover:bg-slate-700">
          <span class="w-6 h-6 rounded-full bg-white/10 flex items-center justify-center text-xs">2</span>
          <span>المستوى الثاني: مرحلة التأثير</span>
        </button>
        <button onclick="switchStage(3)" id="stageBtn3" class="stage-btn px-6 py-3.5 rounded-2xl font-bold text-sm transition-all flex items-center gap-3 bg-slate-800 text-slate-300 hover:bg-slate-700">
          <span class="w-6 h-6 rounded-full bg-white/10 flex items-center justify-center text-xs">3</span>
          <span>المستوى الثالث: مرحلة القيادة</span>
        </button>
      </div>

      <!-- Stage 1 Content -->
      <div id="stageCard1" class="stage-card block bg-brand-card/70 border border-slate-700/80 rounded-3xl p-8 lg:p-12 transition-all">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
          <div class="lg:col-span-7 space-y-6 text-right">
            <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-rose-500/10 border border-rose-500/30 text-rose-400 text-xs font-bold">
              <span>المبتدئون • التأسيس وكسر الحواجز النفسية</span>
            </div>
            <h3 class="text-2xl sm:text-3xl font-black font-cairo text-white">مرحلة التمكين (Empowerment Stage)</h3>
            <p class="text-slate-300 leading-relaxed text-sm sm:text-base">
              التركيز على تفكيك مشاعر الرهبة والخوف من التحدث أمام المجموعة، وغرس تقدير الذات العالي، وتعليم الشبل كيف يعبر عن مشاعره ورأيه الخاص بأريحية تامة ودون تردد.
            </p>
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 pt-2">
              <div class="p-4 rounded-xl bg-brand-deep/80 border border-slate-800 flex items-start gap-3">
                <i data-lucide="smile" class="w-5 h-5 text-rose-400 mt-1 shrink-0"></i>
                <div>
                  <h4 class="font-bold text-white text-sm">تحطيم رهاب الجمهور</h4>
                  <p class="text-xs text-slate-400">تقنيات التنفس السليم، التحكم بنبرة الصوت، والوقوف المتزن.</p>
                </div>
              </div>
              <div class="p-4 rounded-xl bg-brand-deep/80 border border-slate-800 flex items-start gap-3">
                <i data-lucide="message-circle" class="w-5 h-5 text-rose-400 mt-1 shrink-0"></i>
                <div>
                  <h4 class="font-bold text-white text-sm">التعبير الصادق عن الذات</h4>
                  <p class="text-xs text-slate-400">تحويل الخجل إلى طلاقة عفوية في التواصل اليومي والمدرسي.</p>
                </div>
              </div>
            </div>
          </div>
          <div class="lg:col-span-5">
            <div class="bg-gradient-to-br from-rose-500/20 to-indigo-900/30 p-6 rounded-2xl border border-rose-500/30 space-y-4">
              <span class="text-xs font-bold text-rose-300">مخرجات المستوى الأول:</span>
              <ul class="space-y-3 text-sm text-slate-200">
                <li class="flex items-center gap-2">
                  <i data-lucide="check" class="w-4 h-4 text-rose-400"></i>
                  <span>القدرة على التعريف بالنفس بجرأة أمام جمع غير مألوف.</span>
                </li>
                <li class="flex items-center gap-2">
                  <i data-lucide="check" class="w-4 h-4 text-rose-400"></i>
                  <span>سلامة لغة الجسد الأولية والتواصل البصري المباشر.</span>
                </li>
                <li class="flex items-center gap-2">
                  <i data-lucide="check" class="w-4 h-4 text-rose-400"></i>
                  <span>بناء الثقة الداخلية وإيقاف جلد الذات عند الخطأ.</span>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>

      <!-- Stage 2 Content -->
      <div id="stageCard2" class="stage-card hidden bg-brand-card/70 border border-slate-700/80 rounded-3xl p-8 lg:p-12 transition-all">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
          <div class="lg:col-span-7 space-y-6 text-right">
            <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-amber-500/10 border border-amber-500/30 text-amber-400 text-xs font-bold">
              <span>المبادرون • الإقناع وفنون العرض المسرحي</span>
            </div>
            <h3 class="text-2xl sm:text-3xl font-black font-cairo text-white">مرحلة التأثير (Impact Stage)</h3>
            <p class="text-slate-300 leading-relaxed text-sm sm:text-base">
              الانتقال من مجرد الكلام إلى الإقناع، وسحر السرد القصصي (Storytelling)، والتحكم الذكي بلغة الجسد واستخدام نبرات الصوت الدرامية لجذب انتباه المستمعين.
            </p>
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 pt-2">
              <div class="p-4 rounded-xl bg-brand-deep/80 border border-slate-800 flex items-start gap-3">
                <i data-lucide="sparkles" class="w-5 h-5 text-amber-400 mt-1 shrink-0"></i>
                <div>
                  <h4 class="font-bold text-white text-sm">السرد القصصي المؤثر</h4>
                  <p class="text-xs text-slate-400">بناء حكاية مشوقة ذات بداية وذروة وهدف أخلاقي وقيادي واضح.</p>
                </div>
              </div>
              <div class="p-4 rounded-xl bg-brand-deep/80 border border-slate-800 flex items-start gap-3">
                <i data-lucide="activity" class="w-5 h-5 text-amber-400 mt-1 shrink-0"></i>
                <div>
                  <h4 class="font-bold text-white text-sm">الذكاء العاطفي ولغة الجسد</h4>
                  <p class="text-xs text-slate-400">قراءة تعابير الآخرين والتفاعل مع مزاج القاعة بمرونة.</p>
                </div>
              </div>
            </div>
          </div>
          <div class="lg:col-span-5">
            <div class="bg-gradient-to-br from-amber-500/20 to-indigo-900/30 p-6 rounded-2xl border border-amber-500/30 space-y-4">
              <span class="text-xs font-bold text-amber-300">مخرجات المستوى الثاني:</span>
              <ul class="space-y-3 text-sm text-slate-200">
                <li class="flex items-center gap-2">
                  <i data-lucide="check" class="w-4 h-4 text-amber-400"></i>
                  <span>تقديم خطبة قصيرة مقنعة تجذب الانتباه لمدة 3 إلى 5 دقائق.</span>
                </li>
                <li class="flex items-center gap-2">
                  <i data-lucide="check" class="w-4 h-4 text-amber-400"></i>
                  <span>المشاركة في مناظرات فكرية بأسلوب حضاري يحترم وجهات النظر.</span>
                </li>
                <li class="flex items-center gap-2">
                  <i data-lucide="check" class="w-4 h-4 text-amber-400"></i>
                  <span>مهارة الحضور الذهني والرد السريع اللبق (سلاسة البديهة).</span>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>

      <!-- Stage 3 Content -->
      <div id="stageCard3" class="stage-card hidden bg-brand-card/70 border border-slate-700/80 rounded-3xl p-8 lg:p-12 transition-all">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
          <div class="lg:col-span-7 space-y-6 text-right">
            <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-emerald-500/10 border border-emerald-500/30 text-emerald-400 text-xs font-bold">
              <span>النخبة • التفكير الاستراتيجي والهوية القيادية</span>
            </div>
            <h3 class="text-2xl sm:text-3xl font-black font-cairo text-white">مرحلة القيادة (Leadership Stage)</h3>
            <p class="text-slate-300 leading-relaxed text-sm sm:text-base">
              المستوى المتقدم لإعداد القادة: قيادة الفرق الميدانية، حل المشكلات المعقدة، إدارة الأزمات، والجاهزية التامة للمقابلات التلفزيونية والبودكاست وصناعة الهوية الشخصية.
            </p>
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 pt-2">
              <div class="p-4 rounded-xl bg-brand-deep/80 border border-slate-800 flex items-start gap-3">
                <i data-lucide="compass" class="w-5 h-5 text-emerald-400 mt-1 shrink-0"></i>
                <div>
                  <h4 class="font-bold text-white text-sm">التفكير الاستراتيجي</h4>
                  <p class="text-xs text-slate-400">تفكيك التحديات إلى خطوات تنفيذية وتوجيه فرق العمل بنجاح.</p>
                </div>
              </div>
              <div class="p-4 rounded-xl bg-brand-deep/80 border border-slate-800 flex items-start gap-3">
                <i data-lucide="video" class="w-5 h-5 text-emerald-400 mt-1 shrink-0"></i>
                <div>
                  <h4 class="font-bold text-white text-sm">الظهور الإعلامي وصناعة الهوية</h4>
                  <p class="text-xs text-slate-400">إتقان الحديث أمام الكاميرا، والبودكاست، وصياغة المحتوى الهادف.</p>
                </div>
              </div>
            </div>
          </div>
          <div class="lg:col-span-5">
            <div class="bg-gradient-to-br from-emerald-500/20 to-indigo-900/30 p-6 rounded-2xl border border-emerald-500/30 space-y-4">
              <span class="text-xs font-bold text-emerald-300">مخرجات المستوى الثالث:</span>
              <ul class="space-y-3 text-sm text-slate-200">
                <li class="flex items-center gap-2">
                  <i data-lucide="check" class="w-4 h-4 text-emerald-400"></i>
                  <span>إدارة وإطلاق مشروع جماعي من الفكرة حتى العرض الختامي.</span>
                </li>
                <li class="flex items-center gap-2">
                  <i data-lucide="check" class="w-4 h-4 text-emerald-400"></i>
                  <span>جاهزية التحدث في المحافل الرسمية والمؤتمرات المدرسية.</span>
                </li>
                <li class="flex items-center gap-2">
                  <i data-lucide="check" class="w-4 h-4 text-emerald-400"></i>
                  <span>شخصية متزنة تمتلك حس المسؤولية والقدرة على توجيه الأقران.</span>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>

    </div>
  </section>

  <!-- SECTION 4: CORE PILLARS & FEATURES GRID -->
  <section id="pillars" class="py-20 bg-brand-navy/30 border-y border-slate-800">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      
      <div class="text-center max-w-3xl mx-auto space-y-4 mb-16">
        <h2 class="text-xs uppercase tracking-widest text-amber-400 font-black">أركان البرنامج الخمسة</h2>
        <p class="text-3xl sm:text-4xl font-black font-cairo text-white">منظومة تدريبية متكاملة لصقل الشخصية</p>
        <p class="text-slate-400 text-sm sm:text-base">
          تغطي برامجنا التطويرية كافة الجوانب التعبيرية، المعرفية، والسلوكية للشبل لضمان تميزه المستمر:
        </p>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        
        <!-- Pillar 1 -->
        <div class="bg-brand-card/60 hover:bg-brand-card transition-all p-8 rounded-3xl border border-slate-800 hover:border-slate-700 space-y-5">
          <div class="w-14 h-14 rounded-2xl bg-rose-500/10 text-rose-400 flex items-center justify-center">
            <i data-lucide="mic" class="w-7 h-7"></i>
          </div>
          <h3 class="text-xl font-bold font-cairo text-white">الخطابة والإلقاء والتوستماسترز</h3>
          <p class="text-slate-400 text-sm leading-relaxed">
            محاكاة رسمية لأندية (Cubs Toastmasters) العالمية. يتعلم الشبل الارتجال السريع، صياغة المقدمات الجاذبة، واستخدام نبرات الصوت ولغة الجسد للسيطرة على المسرح بكل أريحية.
          </p>
        </div>

        <!-- Pillar 2 -->
        <div class="bg-brand-card/60 hover:bg-brand-card transition-all p-8 rounded-3xl border border-slate-800 hover:border-slate-700 space-y-5">
          <div class="w-14 h-14 rounded-2xl bg-amber-500/10 text-amber-400 flex items-center justify-center">
            <i data-lucide="shield" class="w-7 h-7"></i>
          </div>
          <h3 class="text-xl font-bold font-cairo text-white">القيادة، الشخصية والاستقلالية</h3>
          <p class="text-slate-400 text-sm leading-relaxed">
            تدريب حي على إدارة الوقت، الاعتماد على النفس في شؤون الحياة اليومية، اتخاذ القرار عند الأزمات، والتفاعل الإيجابي مع فريق العمل بروح المبادرة.
          </p>
        </div>

        <!-- Pillar 3 -->
        <div class="bg-brand-card/60 hover:bg-brand-card transition-all p-8 rounded-3xl border border-slate-800 hover:border-slate-700 space-y-5">
          <div class="w-14 h-14 rounded-2xl bg-blue-500/10 text-blue-400 flex items-center justify-center">
            <i data-lucide="video" class="w-7 h-7"></i>
          </div>
          <h3 class="text-xl font-bold font-cairo text-white">الإعلام والتعبير الإبداعي</h3>
          <p class="text-slate-400 text-sm leading-relaxed">
            تجارب حية أمام العدسات وأجهزة الصوت لكسر رهبة الكاميرا، وإعداد المحتوى الإيجابي، والتمثيل المسرحي التعبيري الذي يعزز من مرونة الشبل الفكرية.
          </p>
        </div>

        <!-- Pillar 4 -->
        <div class="bg-brand-card/60 hover:bg-brand-card transition-all p-8 rounded-3xl border border-slate-800 hover:border-slate-700 space-y-5">
          <div class="w-14 h-14 rounded-2xl bg-emerald-500/10 text-emerald-400 flex items-center justify-center">
            <i data-lucide="languages" class="w-7 h-7"></i>
          </div>
          <h3 class="text-xl font-bold font-cairo text-white">طلاقة اللغة الإنجليزية التفاعلية</h3>
          <p class="text-slate-400 text-sm leading-relaxed">
            بالشراكة مع معاهد ومختصين: ممارسة التحدث بالإنجليزية عبر القصص والمناظرات والعروض التقديمية دون حفظ قواعد جاف، بل كممارسة حياتية واثقة.
          </p>
        </div>

        <!-- Pillar 5 -->
        <div class="bg-brand-card/60 hover:bg-brand-card transition-all p-8 rounded-3xl border border-slate-800 hover:border-slate-700 space-y-5">
          <div class="w-14 h-14 rounded-2xl bg-purple-500/10 text-purple-400 flex items-center justify-center">
            <i data-lucide="tent" class="w-7 h-7"></i>
          </div>
          <h3 class="text-xl font-bold font-cairo text-white">الأنشطة والمعسكرات الهادفة</h3>
          <p class="text-slate-400 text-sm leading-relaxed">
            لقاءات خارجية وزيارات تفاعلية ومحاكاة مواقف حقيقية تحت إشراف تربوي متخصص لتطبيق كل ما تعلمه الشبل في سياق واقعي ممتع ومحفز.
          </p>
        </div>

        <!-- Pillar 6 (Unique Diagnostic Feature) -->
        <div class="bg-brand-card/60 hover:bg-brand-card transition-all p-8 rounded-3xl border border-slate-800 hover:border-slate-700 space-y-5">
          <div class="w-14 h-14 rounded-2xl bg-rose-500/10 text-rose-400 flex items-center justify-center">
            <i data-lucide="file-text" class="w-7 h-7"></i>
          </div>
          <h3 class="text-xl font-bold font-cairo text-white">تقرير الأثر الفردي التراكمي</h3>
          <p class="text-slate-400 text-sm leading-relaxed">
            استمارة تشخيصية معتمدة لكل جلسة تحلل 10 محاور دقيقة (الجرأة، التواصل البصري، نبرة الصوت، التفاعل، وغيرها) وتصل لولي الأمر بانتظام.
          </p>
        </div>

      </div>
    </div>
  </section>

  <!-- SECTION 5: THE GOLDEN GUARANTEE -->
  <section id="guarantee" class="py-16 relative">
    <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8">
      
      <div class="relative rounded-3xl overflow-hidden p-8 sm:p-12 gold-gradient-border shadow-2xl shadow-amber-500/20">
        <div class="bg-brand-deep rounded-[22px] p-8 sm:p-12 relative z-10 flex flex-col md:flex-row items-center gap-8">
          
          <div class="w-28 h-28 sm:w-36 sm:h-36 rounded-2xl bg-gradient-to-br from-amber-400 to-amber-600 p-1 shrink-0 flex items-center justify-center shadow-xl shadow-amber-500/30">
            <div class="w-full h-full bg-brand-deep rounded-[14px] flex flex-col items-center justify-center text-center p-2">
              <i data-lucide="award" class="w-10 h-10 text-amber-400 mb-1"></i>
              <span class="text-xs font-black text-amber-300">الضمان الذهبي</span>
              <span class="text-base font-black text-white">100%</span>
            </div>
          </div>

          <div class="space-y-4 text-center md:text-right">
            <span class="text-xs font-extrabold uppercase tracking-widest text-amber-400 bg-amber-400/10 px-3 py-1 rounded-full">استثمار خالٍ تماماً من أي مخاطرة</span>
            <h3 class="text-2xl sm:text-3xl font-black font-cairo text-white">
              عهدنا معك: إذا لم تلمس تحولاً حقيقياً في شخصية وجرأة ابنك، استرد كامل رسومك فوراً
            </h3>
            <p class="text-slate-300 text-sm sm:text-base leading-relaxed">
              ثقتنا بمنهجية العمل الأثرية وبخبرة مدربينا تجعلنا نقدم هذا الضمان الاستثنائي لجميع أولياء الأمور دون شروط معقدة. مقاعدنا محدودة جداً لضمان أعلى مستويات الإشراف والجودة لكل شبل.
            </p>
          </div>

        </div>
      </div>

    </div>
  </section>

  <!-- SECTION 6: LEAD COACH SPOTLIGHT -->
  <section id="coach" class="py-20 bg-brand-navy/40 border-y border-slate-800">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
        
        <!-- Coach Image Frame -->
        <div class="lg:col-span-5 relative order-2 lg:order-1">
          <div class="relative mx-auto max-w-sm rounded-3xl overflow-hidden border-2 border-slate-700 shadow-2xl">
            <img src="https://images.unsplash.com/photo-1534528741775-53994a69daeb?auto=format&fit=crop&w=800&q=80" 
                 alt="الأستاذ راكان النادر - رئيس نادي الأشبال للخطابة والإلقاء" 
                 class="w-full h-[450px] object-cover">
            <div class="absolute inset-0 bg-gradient-to-t from-brand-deep via-transparent to-transparent"></div>
            <div class="absolute bottom-6 right-6 left-6 text-center bg-brand-navy/90 border border-slate-700/80 p-4 rounded-2xl backdrop-blur-md">
              <h4 class="text-lg font-bold text-white">أ. راكان النادر</h4>
              <p class="text-xs text-amber-300 font-semibold">رئيس نادي الأشبال لهواية الخطابة والإلقاء</p>
            </div>
          </div>
        </div>

        <!-- Coach Bio & Philosophy -->
        <div class="lg:col-span-7 space-y-6 text-center lg:text-right order-1 lg:order-2">
          <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-slate-800 text-amber-400 text-xs font-bold border border-slate-700">
            <i data-lucide="user-check" class="w-4 h-4"></i>
            <span>إشراف وتدريب قيادي مباشر</span>
          </div>

          <h2 class="text-3xl sm:text-4xl font-black font-cairo text-white">
            الأستاذ راكان النادر
            <span class="block text-xl sm:text-2xl text-slate-400 font-normal mt-2">خبير صقل المهارات القيادية والخطابية للناشئة</span>
          </h2>

          <p class="text-slate-300 text-base leading-relaxed">
            يتبنى الأستاذ راكان منهجاً تطويرياً فريداً يجمع بين المعايير المعتمدة لنوادي التوستماسترز الدولية، وتطبيقات علم النفس التربوي المعاصر، مع الحرص التام على التشخيص الفردي لكل متدرب وتتبع مسار تحوله خطوة بخطوة.
          </p>

          <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 text-right pt-2">
            <div class="p-4 rounded-2xl bg-brand-deep/60 border border-slate-800 space-y-2">
              <div class="flex items-center gap-2 text-white font-bold text-sm">
                <i data-lucide="check-circle-2" class="w-4 h-4 text-emerald-400"></i>
                <span>ترخيص رسمي معتمد</span>
              </div>
              <p class="text-xs text-slate-400">قيادة النادي المعتمد من البوابة الوطنية لأندية الهواة (هاوي) برقم 942240102959.</p>
            </div>

            <div class="p-4 rounded-2xl bg-brand-deep/60 border border-slate-800 space-y-2">
              <div class="flex items-center gap-2 text-white font-bold text-sm">
                <i data-lucide="check-circle-2" class="w-4 h-4 text-emerald-400"></i>
                <span>متابعة أثر دقيقة</span>
              </div>
              <p class="text-xs text-slate-400">إشراف شخصي مباشر على كل شبل مع توفير توصيات دورية لولي الأمر لضمان استدامة الأثر في المنزل والمدرسة.</p>
            </div>
          </div>

          <blockquote class="p-4 rounded-xl bg-slate-800/40 border-r-4 border-amber-500 text-slate-300 text-sm italic">
            "كل جلسة خطوة.. وكل خطوة تصنع أثراً. هدفنا ليس مجرد تخريج متحدثين، بل غرس هوية القائد الذي يثق بقيمته ويؤثر بحكمته."
          </blockquote>
        </div>

      </div>

    </div>
  </section>

  <!-- SECTION 7: REGISTRATION / LEAD CAPTURE FORM -->
  <section id="register" class="py-20 relative">
    <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
      
      <div class="bg-gradient-to-b from-brand-card to-brand-deep rounded-3xl border border-slate-700/80 p-8 sm:p-12 shadow-2xl shadow-black/50">
        
        <div class="text-center space-y-3 mb-10">
          <span class="px-3 py-1 bg-rose-500/20 text-rose-400 rounded-full text-xs font-bold">التسجيل المبكر لعام 2026</span>
          <h2 class="text-2xl sm:text-4xl font-black font-cairo text-white">احجز مقعد ابنك الآن في برنامج الأشبال</h2>
          <p class="text-slate-400 text-xs sm:text-sm max-w-xl mx-auto">
            نظراً لحرصنا على تقديم تدريب شخصي استثنائي، فإن المقاعد محدودة جداً وتُغلق فور اكتمال المجموعة. املأ البيانات وسيتواصل معك المستشار التربوي لتحديد موعد الجلسة التشخيصية.
          </p>
        </div>

        <form id="leadForm" onsubmit="handleFormSubmit(event)" class="space-y-6">
          
          <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
            <!-- Parent Name -->
            <div class="space-y-2 text-right">
              <label for="parentName" class="block text-xs font-bold text-slate-300">اسم ولي الأمر الثلاثي <span class="text-rose-500">*</span></label>
              <div class="relative">
                <input type="text" id="parentName" required placeholder="مثال: خالد محمد السالم" 
                       class="w-full px-4 py-3.5 bg-slate-900/80 border border-slate-700 rounded-xl text-white text-sm focus:outline-none focus:border-amber-400 transition-colors">
              </div>
            </div>

            <!-- Phone Number -->
            <div class="space-y-2 text-right">
              <label for="phone" class="block text-xs font-bold text-slate-300">رقم الجوال / واتساب <span class="text-rose-500">*</span></label>
              <input type="tel" id="phone" required placeholder="05xxxxxxxx" dir="ltr"
                     class="w-full px-4 py-3.5 bg-slate-900/80 border border-slate-700 rounded-xl text-white text-sm focus:outline-none focus:border-amber-400 transition-colors text-right">
            </div>
          </div>

          <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
            <!-- Child Age -->
            <div class="space-y-2 text-right">
              <label for="childAge" class="block text-xs font-bold text-slate-300">عمر الشبل / الشبلة (7 إلى 18 سنة) <span class="text-rose-500">*</span></label>
              <select id="childAge" required class="w-full px-4 py-3.5 bg-slate-900/80 border border-slate-700 rounded-xl text-white text-sm focus:outline-none focus:border-amber-400 transition-colors">
                <option value="" disabled selected>اختر الفئة العمرية</option>
                <option value="7-9">7 إلى 9 سنوات (المرحلة التأسيسية)</option>
                <option value="10-12">10 إلى 12 سنة (مرحلة التمكين)</option>
                <option value="13-15">13 إلى 15 سنة (مرحلة التأثير واليافعين)</option>
                <option value="16-18">16 إلى 18 سنة (مرحلة إعداد القادة والجامعة)</option>
              </select>
            </div>

            <!-- City -->
            <div class="space-y-2 text-right">
              <label for="city" class="block text-xs font-bold text-slate-300">المدينة / الحي <span class="text-rose-500">*</span></label>
              <input type="text" id="city" required placeholder="مثال: الرياض - حي الملقا" 
                     class="w-full px-4 py-3.5 bg-slate-900/80 border border-slate-700 rounded-xl text-white text-sm focus:outline-none focus:border-amber-400 transition-colors">
            </div>
          </div>

          <!-- Goal / Development Needs -->
          <div class="space-y-2 text-right">
            <label for="goals" class="block text-xs font-bold text-slate-300">ما أهم التحديات أو المهارات التي ترغب بتطويرها لدى ابنك؟</label>
            <textarea id="goals" rows="3" placeholder="مثال: التغلب على الخجل في المدرسة، الرغبة في التحدث بطلاقة وإتقان الإلقاء والمشاريع، تعزيز الثقة بالنفس..."
                      class="w-full px-4 py-3 bg-slate-900/80 border border-slate-700 rounded-xl text-white text-sm focus:outline-none focus:border-amber-400 transition-colors"></textarea>
          </div>

          <!-- Submit Button -->
          <button type="submit" id="submitBtn" class="w-full py-4 bg-gradient-to-r from-rose-600 via-rose-500 to-amber-500 hover:from-rose-500 hover:to-amber-400 text-white font-black text-base rounded-2xl shadow-xl shadow-rose-600/30 transition-all transform active:scale-98 flex items-center justify-center gap-2">
            <span>تأكيد طلب حجز المقعد واستشارة التشخيص المجانية</span>
            <i data-lucide="send" class="w-5 h-5"></i>
          </button>

          <!-- Feedback Alert -->
          <div id="formSuccess" class="hidden p-4 rounded-2xl bg-emerald-500/20 border border-emerald-500/40 text-center space-y-2">
            <div class="flex items-center justify-center gap-2 text-emerald-400 font-bold text-sm">
              <i data-lucide="check-circle-2" class="w-5 h-5"></i>
              <span>تم استلام طلبكم بنجاح!</span>
            </div>
            <p class="text-xs text-slate-300">سيتواصل معكم فريق القبول والتسجيل أو الكوتش راكان النادر خلال ساعات العمل لترتيب موعد المقابلة التشخيصية.</p>
          </div>

          <div class="flex items-center justify-center gap-6 pt-2 text-xs text-slate-400">
            <span class="flex items-center gap-1.5">
              <i data-lucide="lock" class="w-3.5 h-3.5 text-amber-400"></i>
              <span>بياناتكم سرية ومحمية تماماً</span>
            </span>
            <span class="flex items-center gap-1.5">
              <i data-lucide="phone-call" class="w-3.5 h-3.5 text-rose-400"></i>
              <span>استفسارات مباشرة: 0533877100</span>
            </span>
          </div>

        </form>

      </div>

    </div>
  </section>

  <!-- FOOTER -->
  <footer class="bg-brand-deep border-t border-slate-800/80 py-12 text-slate-400 text-sm">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="grid grid-cols-1 md:grid-cols-4 gap-8 mb-8 text-right">
        
        <!-- Col 1: Brand Info -->
        <div class="space-y-4 md:col-span-2">
          <div class="flex items-center gap-3">
            <div class="w-10 h-10 rounded-xl bg-rose-500/20 flex items-center justify-center text-rose-500">
              <i data-lucide="crown" class="w-5 h-5"></i>
            </div>
            <span class="text-lg font-black font-cairo text-white">برنامج الأشبال (Cubs Toastmasters)</span>
          </div>
          <p class="text-xs text-slate-400 leading-relaxed max-w-md">
            النادي الرائد لتطوير مهارات الإلقاء، القيادة، وبناء الشخصية للناشئة والأشبال في المملكة العربية السعودية، مسجل بجمعية أندية الهواة (هاوي) برقم 942240102959 بإشراف المدرب راكان النادر.
          </p>
        </div>

        <!-- Col 2: Quick Links -->
        <div class="space-y-2">
          <h4 class="text-xs font-bold text-white uppercase tracking-wider">روابط سريعة</h4>
          <ul class="space-y-2 text-xs">
            <li><a href="#about" class="hover:text-amber-400 transition-colors">عن النادي والمنهجية</a></li>
            <li><a href="#roadmap" class="hover:text-amber-400 transition-colors">مستويات التدريب الثلاثة</a></li>
            <li><a href="#guarantee" class="hover:text-amber-400 transition-colors">الضمان الذهبي 100%</a></li>
            <li><a href="#coach" class="hover:text-amber-400 transition-colors">المدرب راكان النادر</a></li>
          </ul>
        </div>

        <!-- Col 3: Contact & Support -->
        <div class="space-y-2">
          <h4 class="text-xs font-bold text-white uppercase tracking-wider">التواصل المباشر</h4>
          <ul class="space-y-2 text-xs">
            <li class="flex items-center gap-2">
              <i data-lucide="phone" class="w-3.5 h-3.5 text-amber-400"></i>
              <span dir="ltr">0533877100</span>
            </li>
            <li class="flex items-center gap-2">
              <i data-lucide="map-pin" class="w-3.5 h-3.5 text-rose-400"></i>
              <span>المملكة العربية السعودية - الرياض</span>
            </li>
            <li class="flex items-center gap-2">
              <i data-lucide="award" class="w-3.5 h-3.5 text-emerald-400"></i>
              <span>ترخيص هاوي رقم 942240102959</span>
            </li>
          </ul>
        </div>

      </div>

      <div class="pt-8 border-t border-slate-800/80 flex flex-col sm:flex-row items-center justify-between text-xs text-slate-500 gap-4">
        <div>جميع الحقوق محفوظة © 2026 برنامج الأشبال (Cubs). رعاية قيادية مستدامة.</div>
        <div class="flex gap-4">
          <a href="#" class="hover:text-slate-300">الشروط والأحكام</a>
          <span>•</span>
          <a href="#" class="hover:text-slate-300">سياسة الخصوصية</a>
        </div>
      </div>
    </div>
  </footer>

  <!-- SCRIPT: INTERACTION & LOGIC -->
  <script>
    // Initialize Lucide Icons
    lucide.createIcons();

    // Mobile Menu Toggle
    const mobileBtn = document.getElementById('mobileMenuBtn');
    const mobileMenu = document.getElementById('mobileMenu');
    mobileBtn.addEventListener('click', () => {
      mobileMenu.classList.toggle('hidden');
    });

    // Close mobile menu when a navigation anchor is clicked
    mobileMenu.querySelectorAll('a').forEach(anchor => {
      anchor.addEventListener('click', () => {
        mobileMenu.classList.add('hidden');
      });
    });

    // Roadmap Tabs Switcher
    function switchStage(stageNum) {
      // Hide all cards
      document.querySelectorAll('.stage-card').forEach(card => card.classList.add('hidden'));
      document.getElementById(`stageCard${stageNum}`).classList.remove('hidden');

      // Update button styling
      const buttons = [document.getElementById('stageBtn1'), document.getElementById('stageBtn2'), document.getElementById('stageBtn3')];
      buttons.forEach((btn, index) => {
        if (index + 1 === stageNum) {
          btn.className = "stage-btn active px-6 py-3.5 rounded-2xl font-bold text-sm transition-all flex items-center gap-3 bg-gradient-to-r from-rose-600 to-rose-500 text-white shadow-lg shadow-rose-600/30";
        } else {
          btn.className = "stage-btn px-6 py-3.5 rounded-2xl font-bold text-sm transition-all flex items-center gap-3 bg-slate-800 text-slate-300 hover:bg-slate-700";
        }
      });
    }

    // Lead Form Handler with visual feedback
    function handleFormSubmit(e) {
      e.preventDefault();
      const submitBtn = document.getElementById('submitBtn');
      const feedback = document.getElementById('formSuccess');

      submitBtn.disabled = true;
      submitBtn.innerHTML = `<span>جاري إرسال الطلب...</span>`;

      setTimeout(() => {
        submitBtn.classList.add('hidden');
        feedback.classList.remove('hidden');
      }, 1000);
    }
  </script>
</body>
</html>
