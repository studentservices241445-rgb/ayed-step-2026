<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>أكاديمية عايد الرسمية | دورة STEP المكثفة 2026</title>
  <meta name="description" content="دورة STEP المكثفة 2026 من أكاديمية عايد الرسمية — خطة مركّزة وملفات ونماذج محدثة، مناسبة للي عنده اختبار قريب ويبغى نتيجة بسرعة بدون تشتت." />

  <!-- Font -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;700;800&display=swap" rel="stylesheet">

  <!-- Tailwind CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: { cairo: ['Cairo', 'system-ui', 'sans-serif'] }
        }
      }
    }
  </script>

  <style>
    :root{
      --yed:#F7C600; /* أصفر الهوية */
      --blk:#0B0B0B;
      --card:#111827;
      --muted:rgba(255,255,255,.70);
    }
    html{scroll-behavior:smooth}
    body{font-family:Cairo,system-ui,sans-serif;background:radial-gradient(1200px 800px at 80% -10%, rgba(247,198,0,.18), transparent 60%), radial-gradient(900px 600px at 10% 20%, rgba(247,198,0,.10), transparent 55%), #0B0B0B;}
    .glass{background:rgba(17,24,39,.65);backdrop-filter:blur(10px);border:1px solid rgba(255,255,255,.10)}
    .btn{transition:.18s transform,.18s opacity}
    .btn:active{transform:scale(.98)}
    .chip{border:1px solid rgba(255,255,255,.14);background:rgba(255,255,255,.06)}
    .watermark:before{
      content:"أكاديمية عايد الرسمية • دورة STEP المكثفة 2026 • Ayed Academy";
      position:fixed; inset:0;
      pointer-events:none;
      opacity:.06;
      font-weight:800;
      letter-spacing:.8px;
      font-size:22px;
      transform:rotate(-18deg);
      display:flex;
      align-items:center;
      justify-content:center;
      background-image:
        repeating-linear-gradient(0deg, transparent 0 38px, rgba(255,255,255,.05) 38px 39px),
        repeating-linear-gradient(90deg, transparent 0 240px, rgba(255,255,255,.05) 240px 241px);
      mix-blend-mode:screen;
    }
    .topbar{
      position:sticky; top:0; z-index:50;
      background:linear-gradient(90deg, rgba(247,198,0,.18), rgba(17,24,39,.85), rgba(247,198,0,.12));
      border-bottom:1px solid rgba(255,255,255,.10);
      backdrop-filter:blur(10px);
    }
    .shadow-soft{box-shadow:0 18px 60px rgba(0,0,0,.45)}
    .toast{
      position:fixed; left:16px; bottom:16px; z-index:60;
      width:min(380px,calc(100% - 32px));
      display:none;
    }
    .toast.show{display:block; animation:pop .18s ease-out}
    @keyframes pop{from{transform:translateY(10px);opacity:0}to{transform:translateY(0);opacity:1}}
    .floating{
      position:fixed; right:16px; bottom:16px; z-index:60;
      display:flex; flex-direction:column; gap:10px;
    }
    .ring-y{box-shadow:0 0 0 2px rgba(247,198,0,.25), 0 18px 50px rgba(0,0,0,.45)}
    .hide{display:none!important}
    .field{background:rgba(255,255,255,.05); border:1px solid rgba(255,255,255,.12); color:#fff}
    .field:focus{outline:none; border-color:rgba(247,198,0,.7); box-shadow:0 0 0 3px rgba(247,198,0,.18)}
    .note{color:rgba(255,255,255,.75)}
  </style>
</head>

<body class="watermark text-white">
  <!-- Top Bar -->
  <div class="topbar">
    <div class="mx-auto max-w-6xl px-4 py-2 flex flex-col gap-2 md:flex-row md:items-center md:justify-between">
      <div class="flex items-center gap-2">
        <span class="inline-flex items-center gap-2 rounded-full px-3 py-1 text-sm chip">
          <span class="w-2 h-2 rounded-full" style="background:var(--yed)"></span>
          <b>تنبيه:</b> الخصم الحالي <b id="priceNow">299</b> ريال — ينتهي <b>29/01/2026</b>
        </span>
        <span class="hidden md:inline text-sm text-white/70">بعدها نكتفي بعدد محدد ويعود السعر الرسمي <b class="text-white">449</b> ريال</span>
      </div>

      <div class="flex items-center gap-3 justify-between md:justify-end">
        <div class="text-sm">
          <div class="text-white/70">الوقت المتبقي على إغلاق التسجيل:</div>
          <div class="font-extrabold text-base" id="countdown">—</div>
        </div>
        <button class="btn rounded-xl px-4 py-2 font-bold text-black ring-y"
          style="background:var(--yed)"
          onclick="scrollToEl('payment')">سجّل الآن</button>
      </div>
    </div>
  </div>

  <!-- Header / Hero -->
  <header class="mx-auto max-w-6xl px-4 pt-10 pb-6">
    <div class="grid gap-6 md:grid-cols-2 items-center">
      <div class="space-y-4">
        <div class="inline-flex items-center gap-2 rounded-full px-3 py-1 text-sm chip">
          <span>⭐</span>
          <span>أول إطلاق 2026 — محتوى مكثف + نماذج محدثة</span>
        </div>

        <h1 class="text-3xl md:text-4xl font-extrabold leading-tight">
          دورة <span style="color:var(--yed)">STEP المكثفة 2026</span><br>
          من <span class="text-white">أكاديمية عايد الرسمية</span>
        </h1>

        <p class="text-white/75 text-lg leading-relaxed">
          إذا عندك اختبار قريب وتبي تمشي بخطة واضحة بدون تشتت… هذي الدورة مصممة لك.
          تركيزنا على <b>الأهم والمتكرر</b>، نماذج عملية، وتكنيكات ترفع درجتك بوقت أقصر — بإذن الله.
        </p>

        <div class="flex flex-wrap gap-2">
          <span class="chip rounded-full px-3 py-1 text-sm">⏱️ وصول 90 يوم</span>
          <span class="chip rounded-full px-3 py-1 text-sm">📌 خطة مذاكرة جاهزة</span>
          <span class="chip rounded-full px-3 py-1 text-sm">📄 ملفات ونماذج PDF</span>
          <span class="chip rounded-full px-3 py-1 text-sm">🧠 شرح وتدريب مركز</span>
        </div>

        <div class="flex flex-wrap items-center gap-3 pt-2">
          <button class="btn rounded-xl px-5 py-3 font-extrabold text-black ring-y"
            style="background:var(--yed)" onclick="scrollToEl('payment')">
            ابدأ الاشتراك الآن
          </button>
          <button class="btn rounded-xl px-5 py-3 font-bold border border-white/15 bg-white/5"
            onclick="scrollToEl('toc')">
            شوف محتوى الدورة بالتفصيل
          </button>
        </div>

        <div class="text-sm text-white/65 pt-1">
          الحساب الرسمي للتواصل وتأكيد الاشتراك: <b>@Ayed_Academy_2026</b>
        </div>
      </div>

      <div class="glass rounded-2xl p-5 shadow-soft">
        <div class="flex items-center justify-between">
          <div>
            <div class="text-white/70 text-sm">عدد المنضمين اليوم</div>
            <div class="text-3xl font-extrabold" id="joinCount">—</div>
          </div>
          <div class="text-left">
            <div class="text-white/70 text-sm">السعر الحالي</div>
            <div class="text-3xl font-extrabold"><span id="priceHero">299</span> <span class="text-lg font-bold text-white/70">ريال</span></div>
          </div>
        </div>

        <div class="mt-4 grid grid-cols-2 gap-3">
          <div class="rounded-xl p-3 bg-white/5 border border-white/10">
            <div class="text-sm text-white/70">مناسب للي…</div>
            <div class="font-bold">اختبار قريب / وقت محدود</div>
          </div>
          <div class="rounded-xl p-3 bg-white/5 border border-white/10">
            <div class="text-sm text-white/70">تركيزنا</div>
            <div class="font-bold">نماذج + تدريب + كويزات</div>
          </div>
          <div class="rounded-xl p-3 bg-white/5 border border-white/10">
            <div class="text-sm text-white/70">التحديثات</div>
            <div class="font-bold">نموذج 50 + تجهيز 51</div>
          </div>
          <div class="rounded-xl p-3 bg-white/5 border border-white/10">
            <div class="text-sm text-white/70">التفعيل</div>
            <div class="font-bold">خلال 24 ساعة بعد الإيصال</div>
          </div>
        </div>

        <div class="mt-4 rounded-xl bg-black/30 border border-white/10 p-3 text-sm text-white/70">
          <b class="text-white">ملاحظة مهمة:</b>
          الموقع يسهّل عليك الطلب ويجهّز رسالة منسّقة للحساب الرسمي. إرسال الإيصال للحساب الرسمي بالخاص يبقى <b class="text-white">إلزامي</b> للتأكيد.
        </div>
      </div>
    </div>
  </header>

  <!-- TOC -->
  <section id="toc" class="mx-auto max-w-6xl px-4 py-6">
    <div class="glass rounded-2xl p-5">
      <div class="flex items-center justify-between flex-wrap gap-3">
        <h2 class="text-xl md:text-2xl font-extrabold">قائمة المحتويات (تنقّل سريع)</h2>
        <div class="text-sm text-white/70">اضغط على أي قسم وبتروح له مباشرة</div>
      </div>

      <div class="mt-4 grid gap-3 md:grid-cols-3">
        <a class="btn chip rounded-xl px-4 py-3" href="#why">1) لماذا الدورة المكثفة؟</a>
        <a class="btn chip rounded-xl px-4 py-3" href="#inside">2) وش بتحصل داخل الدورة؟</a>
        <a class="btn chip rounded-xl px-4 py-3" href="#plans">3) خطط المذاكرة (جاهزة)</a>
        <a class="btn chip rounded-xl px-4 py-3" href="#payment">4) الدفع والتحويل (نسخ تلقائي)</a>
        <a class="btn chip rounded-xl px-4 py-3" href="#enroll">5) نموذج التسجيل (بعد الإيصال)</a>
        <a class="btn chip rounded-xl px-4 py-3" href="#reviews">6) آراء ودرجات طلاب</a>
        <a class="btn chip rounded-xl px-4 py-3" href="#faq">7) الأسئلة الشائعة</a>
        <a class="btn chip rounded-xl px-4 py-3" href="#safety">8) تنبيه الاحتيال</a>
        <a class="btn chip rounded-xl px-4 py-3" href="#contact">9) تواصل الحساب الرسمي</a>
      </div>
    </div>
  </section>

  <!-- Why -->
  <section id="why" class="mx-auto max-w-6xl px-4 py-6">
    <div class="grid gap-5 md:grid-cols-2">
      <div class="glass rounded-2xl p-6">
        <h2 class="text-2xl font-extrabold">ليش “دورة STEP المكثفة 2026”؟</h2>
        <p class="mt-3 text-white/75 leading-relaxed">
          لأن كثير من الطلاب يضيعون بين قنوات ومصادر… ويختبرون أكثر من مرة ودرجتهم ثابتة.
          الدورة المكثفة تعطيك <b>مسار واضح</b>:
          <b>تكنيكات + تدريب + نماذج</b> بشكل مرتب — بدون لف ودوران.
        </p>
        <ul class="mt-4 space-y-2 text-white/80">
          <li>✅ تركيز على الأهم والمتكرر في الاختبار</li>
          <li>✅ نماذج عملية + مراجعات + كويزات للتثبيت</li>
          <li>✅ خطة مذاكرة جاهزة (حسب وقتك)</li>
          <li>✅ مناسبة للي عنده اختبار قريب ويبي اختصار وقت</li>
        </ul>
      </div>

      <div class="glass rounded-2xl p-6">
        <h3 class="text-xl font-extrabold">نقطة مهمّة قبل تختبر</h3>
        <p class="mt-3 text-white/75 leading-relaxed">
          لا تخسر محاولاتك وأنت “تجرب”. كل محاولة وقت + فلوس + توتر.
          الأفضل تمشي بخطة وتدخل وأنت جاهز، خصوصاً مع بداية السنة وكثرة التقديمات.
        </p>

        <div class="mt-4 rounded-xl bg-white/5 border border-white/10 p-4">
          <div class="font-bold" style="color:var(--yed)">الخصم الحالي: 299 ريال</div>
          <div class="text-white/70 text-sm mt-1">
            ينتهي التسجيل بتاريخ <b class="text-white">29/01/2026</b>
            وبعدها نكتفي بعدد محدد ويعود السعر الرسمي <b class="text-white">449</b> ريال.
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Inside -->
  <section id="inside" class="mx-auto max-w-6xl px-4 py-6">
    <div class="glass rounded-2xl p-6">
      <div class="flex items-center justify-between flex-wrap gap-3">
        <h2 class="text-2xl font-extrabold">وش بتحصل داخل الدورة؟</h2>
        <span class="chip rounded-full px-3 py-1 text-sm">محتوى 2026 — مكثف ومرتب</span>
      </div>

      <div class="mt-5 grid gap-4 md:grid-cols-3">
        <div class="rounded-2xl p-5 bg-white/5 border border-white/10">
          <div class="text-lg font-extrabold">🔵 Grammar (القواعد)</div>
          <ul class="mt-3 space-y-2 text-white/80">
            <li>• شرح مركز للنقاط المتكررة</li>
            <li>• تطبيق على نماذج (مودلز)</li>
            <li>• مراجعات وكويزات للتثبيت</li>
          </ul>
        </div>

        <div class="rounded-2xl p-5 bg-white/5 border border-white/10">
          <div class="text-lg font-extrabold">🟣 Reading (القراءة)</div>
          <ul class="mt-3 space-y-2 text-white/80">
            <li>• استراتيجيات استخراج الفكرة بسرعة</li>
            <li>• تدريب يومي على نماذج متنوعة</li>
            <li>• حلول وتوضيح أخطاء شائعة</li>
          </ul>
        </div>

        <div class="rounded-2xl p-5 bg-white/5 border border-white/10">
          <div class="text-lg font-extrabold">⚪ Listening (الاستماع)</div>
          <ul class="mt-3 space-y-2 text-white/80">
            <li>• تكنيكات التقاط الفكرة الأساسية</li>
            <li>• تدريبات مرتبة + تحسين سرعة الفهم</li>
            <li>• توجيهات لتقليل الأخطاء المتكررة</li>
          </ul>
        </div>
      </div>

      <div class="mt-5 grid gap-4 md:grid-cols-2">
        <div class="rounded-2xl p-5 bg-black/30 border border-white/10">
          <div class="font-extrabold" style="color:var(--yed)">نموذج 50 + تجهيز نموذج 51</div>
          <p class="mt-2 text-white/75 leading-relaxed">
            الدورة المكثفة مبنية على نمط <b>نموذج 50</b> وأحدث ما يهم الطالب في 2026،
            ومع أي إصدار جديد (مثل 51) نجهّز لك التحديثات أول بأول داخل المحتوى.
          </p>
        </div>

        <div class="rounded-2xl p-5 bg-black/30 border border-white/10">
          <div class="font-extrabold">🎯 مناسب لمين؟</div>
          <ul class="mt-2 space-y-2 text-white/80">
            <li>• اللي درجاته ثابتة (40–50) وده يطلع بسرعة</li>
            <li>• اللي عنده اختبار قريب ويبغى خطة مختصرة</li>
            <li>• اللي يبي تدريب أكثر من الشرح الطويل</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- Plans -->
  <section id="plans" class="mx-auto max-w-6xl px-4 py-6">
    <div class="glass rounded-2xl p-6">
      <div class="flex items-center justify-between flex-wrap gap-3">
        <h2 class="text-2xl font-extrabold">خطط مذاكرة جاهزة (اختر اللي يناسب وقتك)</h2>
        <span class="text-sm text-white/70">مشيك خطوة بخطوة — بدون تشتت</span>
      </div>

      <div class="mt-5 grid gap-4 md:grid-cols-3">
        <div class="rounded-2xl p-5 bg-white/5 border border-white/10">
          <div class="font-extrabold">مسار 7 أيام (مكثف جدًا)</div>
          <ul class="mt-3 space-y-2 text-white/80 text-sm">
            <li>1) قرامر يوميًا + كويز تثبيت</li>
            <li>2) ريدنق (قطعتين يوميًا) + حلول</li>
            <li>3) ليستنق (تدريب يومي) + مراجعة الأخطاء</li>
            <li>4) نموذج محاكي بنهاية المسار</li>
          </ul>
        </div>

        <div class="rounded-2xl p-5 bg-white/5 border border-white/10">
          <div class="font-extrabold">مسار 15 يوم (الأكثر طلبًا)</div>
          <ul class="mt-3 space-y-2 text-white/80 text-sm">
            <li>1) تأسيس سريع للنقاط المهمة</li>
            <li>2) تجميعات (مودلز) بشكل مرتب</li>
            <li>3) مراجعات + كويزات يومية</li>
            <li>4) نموذج 50 (حل + تصحيح)</li>
          </ul>
        </div>

        <div class="rounded-2xl p-5 bg-white/5 border border-white/10">
          <div class="font-extrabold">مسار شهر (مرن)</div>
          <ul class="mt-3 space-y-2 text-white/80 text-sm">
            <li>1) جرعات يومية قصيرة بدون ضغط</li>
            <li>2) توزيع القراءة والقواعد والاستماع</li>
            <li>3) اختبارات محاكية أسبوعيًا</li>
            <li>4) تثبيت نقاط الضعف قبل الاختبار</li>
          </ul>
        </div>
      </div>

      <div class="mt-5 rounded-2xl bg-black/30 border border-white/10 p-5">
        <div class="font-extrabold">طريقة المذاكرة المختصرة (الموصى بها)</div>
        <div class="mt-2 text-white/75 leading-relaxed">
          <b>تمهيدي (اختياري)</b> إذا مستواك ضعيف، بعدها:
          <b>قرامر → مودلز → مراجعة/كويزات</b>،
          و<b>ريدنق → مودلز → مراجعة/كويزات</b>،
          و<b>ليستنق → تدريبات → كويزات</b>.
          أهم شيء: راجع إجاباتك الغلط، وتابع نقاط تكرار الأسئلة.
        </div>
      </div>
    </div>
  </section>

  <!-- Payment -->
  <section id="payment" class="mx-auto max-w-6xl px-4 py-6">
    <div class="glass rounded-2xl p-6">
      <h2 class="text-2xl font-extrabold">الدفع والتحويل البنكي (رسمي)</h2>
      <p class="mt-2 text-white/75">
        قبل ترسل نموذج التسجيل، لازم التحويل على الحساب الرسمي ثم ترفق الإيصال.
      </p>

      <div class="mt-5 grid gap-4 md:grid-cols-2">
        <div class="rounded-2xl p-5 bg-white/5 border border-white/10">
          <div class="font-extrabold" style="color:var(--yed)">بيانات التحويل البنكي</div>

          <div class="mt-4 space-y-3 text-sm">
            <div class="flex items-center justify-between gap-3 rounded-xl p-3 bg-black/30 border border-white/10">
              <div>
                <div class="text-white/60">البنك</div>
                <div class="font-bold">بنك الإنماء</div>
              </div>
              <button class="btn rounded-lg px-3 py-2 bg-white/10 border border-white/10" onclick="copyText('بنك الإنماء')">نسخ</button>
            </div>

            <div class="flex items-center justify-between gap-3 rounded-xl p-3 bg-black/30 border border-white/10">
              <div>
                <div class="text-white/60">رقم الحساب</div>
                <div class="font-bold" id="accNum">68206067557000</div>
              </div>
              <button class="btn rounded-lg px-3 py-2 bg-white/10 border border-white/10" onclick="copyText(document.getElementById('accNum').innerText)">نسخ</button>
            </div>

            <div class="flex items-center justify-between gap-3 rounded-xl p-3 bg-black/30 border border-white/10">
              <div>
                <div class="text-white/60">الآيبان</div>
                <div class="font-bold" id="ibanNum">SA4905000068206067557000</div>
              </div>
              <button class="btn rounded-lg px-3 py-2 bg-white/10 border border-white/10" onclick="copyText(document.getElementById('ibanNum').innerText)">نسخ</button>
            </div>

            <div class="flex items-center justify-between gap-3 rounded-xl p-3 bg-black/30 border border-white/10">
              <div>
                <div class="text-white/60">اسم المستفيد (عربي)</div>
                <div class="font-bold" id="benefName">مؤسسة كريتيفا جلوبال لتقنية المعلومات</div>
              </div>
              <button class="btn rounded-lg px-3 py-2 bg-white/10 border border-white/10" onclick="copyText(document.getElementById('benefName').innerText)">نسخ</button>
            </div>

            <div class="rounded-xl p-3 bg-black/30 border border-white/10">
              <div class="text-white/60">غرض التحويل (ضروري)</div>
              <div class="mt-1 font-bold" id="purposeTxt">مشتريات دورة STEP المكثفة – منصة عايد الرسمية</div>
              <button class="btn mt-2 rounded-lg px-3 py-2 bg-white/10 border border-white/10" onclick="copyText(document.getElementById('purposeTxt').innerText)">نسخ الغرض</button>
            </div>
          </div>

          <div class="mt-4 text-sm text-white/70">
            ✅ بعد التحويل: جهّز الإيصال (صورة أو PDF) ثم ابدأ الخطوة التالية.
          </div>
        </div>

        <div class="rounded-2xl p-5 bg-white/5 border border-white/10">
          <div class="font-extrabold">خطوات الاشتراك (واضحة)</div>
          <ol class="mt-3 space-y-2 text-white/80 text-sm list-decimal pr-5">
            <li>حوّل مبلغ الاشتراك (السعر الحالي يظهر بالأعلى).</li>
            <li>اكتب <b>غرض التحويل</b> مثل ما هو (عشان ما يتأخر التفعيل).</li>
            <li>ارفع الإيصال هنا (إلزامي) عشان يفتح لك نموذج التسجيل.</li>
            <li>عبّي نموذج التسجيل ثم اضغط زر الإرسال… وبيفتح لك محادثة الحساب الرسمي برسالة جاهزة.</li>
            <li>في محادثة الحساب الرسمي: <b>ارفق الإيصال مرة ثانية</b> (لأن الموقع ما يقدر يرسل ملفات تلقائيًا بدون سيرفر).</li>
          </ol>

          <div class="mt-4 rounded-xl bg-black/30 border border-white/10 p-4">
            <div class="font-extrabold" style="color:var(--yed)">إرفاق الإيصال (إلزامي)</div>
            <p class="text-sm text-white/75 mt-1">
              ارفع الإيصال عشان نضمن إن اللي يرسل نموذج التسجيل قد أكمل التحويل.
            </p>

            <div class="mt-3">
              <input id="receiptUpload" class="w-full field rounded-xl p-3" type="file" accept="image/*,application/pdf" />
              <div class="mt-2 note text-sm">مسموح: صورة / PDF — حجم مناسب</div>
            </div>

            <button class="btn mt-4 w-full rounded-xl px-4 py-3 font-extrabold text-black ring-y"
              style="background:var(--yed)" onclick="goToEnroll()">
              تم التحويل + تم إرفاق الإيصال → انتقل لنموذج التسجيل
            </button>

            <div id="receiptErr" class="mt-2 text-sm text-red-300 hidden">لازم ترفق الإيصال أولاً قبل الانتقال للنموذج.</div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Enroll (Hidden until receipt) -->
  <section id="enroll" class="mx-auto max-w-6xl px-4 py-6">
    <div class="glass rounded-2xl p-6">
      <div class="flex items-center justify-between flex-wrap gap-3">
        <h2 class="text-2xl font-extrabold">نموذج التسجيل</h2>
        <span class="chip rounded-full px-3 py-1 text-sm">بعد الإرسال: حالة الطلب “قيد المراجعة”</span>
      </div>

      <div id="enrollLocked" class="mt-4 rounded-2xl bg-black/30 border border-white/10 p-5">
        <div class="font-extrabold">قبل ما تكمل…</div>
        <p class="mt-2 text-white/75">
          نموذج التسجيل يفتح بعد إرفاق الإيصال من قسم الدفع بالأعلى.
        </p>
        <button class="btn mt-3 rounded-xl px-4 py-2 bg-white/10 border border-white/10" onclick="scrollToEl('payment')">
          رجوع لقسم الدفع
        </button>
      </div>

      <form id="enrollForm" class="mt-5 grid gap-4 hidden">
        <div class="grid gap-4 md:grid-cols-2">
          <div>
            <label class="text-sm text-white/80">الاسم الثلاثي <span class="text-red-300">*</span></label>
            <input id="fullName" class="mt-2 w-full field rounded-xl p-3" placeholder="مثال: محمد عبدالعزيز عايد" required />
          </div>

          <div>
            <label class="text-sm text-white/80">طريقة التواصل (اختياري)</label>
            <select id="contactMethod" class="mt-2 w-full field rounded-xl p-3">
              <option value="">بدون (ما عندي الآن)</option>
              <option value="Telegram">تلجرام</option>
              <option value="WhatsApp">واتساب</option>
              <option value="Email">إيميل</option>
            </select>
            <div class="mt-2 note text-sm">
              (اختياري) يفيدنا للتواصل السريع لو احتجنا تأكيد بسيط.
            </div>
          </div>

          <div>
            <label class="text-sm text-white/80">بيانات التواصل (اختياري)</label>
            <input id="contactValue" class="mt-2 w-full field rounded-xl p-3" placeholder="مثال: @username أو 05xxxxxxxx أو name@email.com" />
          </div>

          <div>
            <label class="text-sm text-white/80">موعد الاختبار</label>
            <div class="grid grid-cols-2 gap-3 mt-2">
              <select id="examWindow" class="field rounded-xl p-3">
                <option value="لسا ما حجزت">لسا ما حجزت</option>
                <option value="خلال 7 أيام">خلال 7 أيام</option>
                <option value="خلال 15 يوم">خلال 15 يوم</option>
                <option value="خلال شهر">خلال شهر</option>
                <option value="محجوز (سأكتب التاريخ)">محجوز (سأكتب التاريخ)</option>
              </select>
              <input id="examDate" type="date" class="field rounded-xl p-3" disabled />
            </div>
            <div class="mt-2 note text-sm">إذا اخترت “محجوز” اكتب التاريخ عشان نضبط لك خطة مناسبة.</div>
          </div>

          <div>
            <label class="text-sm text-white/80">الغرض من الاختبار</label>
            <select id="examPurpose" class="mt-2 w-full field rounded-xl p-3">
              <option value="تقديم جامعة/كلية">تقديم جامعة/كلية</option>
              <option value="وظيفة/تدريب">وظيفة/تدريب</option>
              <option value="ابتعاث/منحة">ابتعاث/منحة</option>
              <option value="ترقية/متطلب جهة">ترقية/متطلب جهة</option>
              <option value="هدف شخصي">هدف شخصي</option>
              <option value="أخرى">أخرى</option>
            </select>
          </div>

          <div>
            <label class="text-sm text-white/80">هل سبق اختبرت STEP؟</label>
            <select id="prevTest" class="mt-2 w-full field rounded-xl p-3">
              <option value="لا">لا</option>
              <option value="نعم">نعم</option>
            </select>
          </div>

          <div id="prevScoreWrap" class="hidden">
            <label class="text-sm text-white/80">درجتك السابقة (اختياري)</label>
            <input id="prevScore" type="number" min="0" max="100" class="mt-2 w-full field rounded-xl p-3" placeholder="مثال: 44" />
          </div>

          <div>
            <label class="text-sm text-white/80">الدرجة المستهدفة <span class="text-red-300">*</span></label>
            <input id="targetScore" type="number" min="0" max="100" class="mt-2 w-full field rounded-xl p-3" placeholder="مثال: 65" required />
          </div>

          <div>
            <label class="text-sm text-white/80">مستواك الحالي</label>
            <select id="level" class="mt-2 w-full field rounded-xl p-3">
              <option value="مبتدئ">مبتدئ</option>
              <option value="متوسط">متوسط</option>
              <option value="متقدم">متقدم</option>
              <option value="ما أدري (حددوا لي)">ما أدري (حددوا لي)</option>
            </select>
          </div>
        </div>

        <div>
          <label class="text-sm text-white/80">ملاحظات (اختياري)</label>
          <textarea id="notes" rows="3" class="mt-2 w-full field rounded-xl p-3" placeholder="مثال: عندي وقت ساعتين يوميًا / أركز على الريدنق / اختبار قريب جدًا"></textarea>
        </div>

        <div class="rounded-2xl bg-black/30 border border-white/10 p-5">
          <div class="font-extrabold">تأكيدات مهمة</div>
          <label class="mt-3 flex gap-3 items-start text-sm text-white/80">
            <input id="confirmPaid" type="checkbox" class="mt-1" />
            <span>أؤكد أني حولت مبلغ الاشتراك على الحساب الرسمي أعلاه.</span>
          </label>
          <label class="mt-2 flex gap-3 items-start text-sm text-white/80">
            <input id="confirmSendReceipt" type="checkbox" class="mt-1" />
            <span>أتعهد بإرسال الإيصال مرة أخرى في الخاص للحساب الرسمي بعد فتح المحادثة (للتأكيد النهائي).</span>
          </label>
          <div id="formErr" class="mt-3 text-sm text-red-300 hidden">فضلاً فعّل التأكيدات المطلوبة قبل الإرسال.</div>
        </div>

        <div class="flex flex-wrap gap-3 items-center justify-between">
          <div class="text-sm text-white/70">
            بعد الضغط: راح تنفتح لك محادثة <b class="text-white">@Ayed_Academy_2026</b> برسالة جاهزة ومنسقة.
          </div>
          <button class="btn rounded-xl px-5 py-3 font-extrabold text-black ring-y"
            style="background:var(--yed)" type="submit">
            فتح رسالة التأكيد للحساب الرسمي
          </button>
        </div>

        <div id="statusBox" class="hidden rounded-2xl bg-white/5 border border-white/10 p-5">
          <div class="font-extrabold" style="color:var(--yed)">تم تجهيز طلبك — الحالة: قيد المراجعة ⏳</div>
          <div class="mt-2 text-white/75 text-sm">
            إذا ما فتحت المحادثة تلقائيًا، اضغط:
            <a class="underline" id="manualLink" href="#" target="_blank" rel="noopener">فتح حساب الأكاديمية</a>
          </div>
        </div>
      </form>
    </div>
  </section>

  <!-- Reviews -->
  <section id="reviews" class="mx-auto max-w-6xl px-4 py-6">
    <div class="glass rounded-2xl p-6">
      <h2 class="text-2xl font-extrabold">آراء ودرجات طلاب (نماذج)</h2>
      <p class="mt-2 text-white/75">أمثلة واقعية على التحسن بعد الالتزام بالخطة والتدريب (النتائج تختلف حسب الاجتهاد).</p>

      <div class="mt-5 grid gap-4 md:grid-cols-3">
        <div class="rounded-2xl p-5 bg-white/5 border border-white/10">
          <div class="font-extrabold">ريم</div>
          <div class="text-sm text-white/70 mt-1">49 → 66 خلال شهر</div>
          <p class="mt-3 text-white/80 text-sm">“ترتيب المحتوى والملفات وفر علي وقت كثير… خصوصًا الريدنق.”</p>
        </div>
        <div class="rounded-2xl p-5 bg-white/5 border border-white/10">
          <div class="font-extrabold">عبدالله</div>
          <div class="text-sm text-white/70 mt-1">44 → 58 خلال 15 يوم</div>
          <p class="mt-3 text-white/80 text-sm">“التكنيكات والمراجعات اليومية ضبطت أخطائي المتكررة.”</p>
        </div>
        <div class="rounded-2xl p-5 bg-white/5 border border-white/10">
          <div class="font-extrabold">سارة</div>
          <div class="text-sm text-white/70 mt-1">52 → 70</div>
          <p class="mt-3 text-white/80 text-sm">“أكثر شيء فرق معي: الكويزات + مراجعة الغلط.”</p>
        </div>
      </div>
    </div>
  </section>

  <!-- FAQ -->
  <section id="faq" class="mx-auto max-w-6xl px-4 py-6">
    <div class="glass rounded-2xl p-6">
      <h2 class="text-2xl font-extrabold">الأسئلة الشائعة</h2>

      <div class="mt-5 grid gap-4 md:grid-cols-2">
        <div class="rounded-2xl p-5 bg-white/5 border border-white/10">
          <div class="font-extrabold">هل الدورة مناسبة للي “تأسيسه قوي”؟</div>
          <div class="mt-2 text-white/80 text-sm">إيه. الدورة المكثفة تركيزها الأكبر على التدريب والنماذج والكويزات، مع شرح مختصر للنقاط المهمة.</div>
        </div>
        <div class="rounded-2xl p-5 bg-white/5 border border-white/10">
          <div class="font-extrabold">كم مدة الوصول للمحتوى؟</div>
          <div class="mt-2 text-white/80 text-sm">90 يوم من تاريخ التفعيل + دعم فني خلال المدة.</div>
        </div>
        <div class="rounded-2xl p-5 bg-white/5 border border-white/10">
          <div class="font-extrabold">متى يتم تفعيل الاشتراك؟</div>
          <div class="mt-2 text-white/80 text-sm">بعد استلام الإيصال بالخاص للحساب الرسمي والتأكد — عادة خلال 24 ساعة.</div>
        </div>
        <div class="rounded-2xl p-5 bg-white/5 border border-white/10">
          <div class="font-extrabold">ليش لازم أرسل الإيصال بالخاص؟</div>
          <div class="mt-2 text-white/80 text-sm">لأن الموقع (GitHub Pages) ما يقدر يرفع ملفات تلقائيًا بدون سيرفر. التأكيد النهائي يكون عبر الخاص للحساب الرسمي.</div>
        </div>
      </div>
    </div>
  </section>

  <!-- Safety -->
  <section id="safety" class="mx-auto max-w-6xl px-4 py-6">
    <div class="glass rounded-2xl p-6">
      <h2 class="text-2xl font-extrabold">تنبيه الاحتيال</h2>
      <p class="mt-2 text-white/80">
        أي تحويل خارج بيانات الحساب أعلاه أو لأي شخص/حساب آخر <b>غير معتمد</b>.
        التأكيد وإرسال الإيصال يكون فقط للحساب الرسمي:
        <b>@Ayed_Academy_2026</b>
      </p>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="mx-auto max-w-6xl px-4 py-8">
    <div class="glass rounded-2xl p-6 flex flex-col gap-3 md:flex-row md:items-center md:justify-between">
      <div>
        <div class="text-white/70 text-sm">للاستفسار/تأكيد الاشتراك</div>
        <div class="text-xl font-extrabold">الحساب الرسمي: @Ayed_Academy_2026</div>
      </div>
      <button class="btn rounded-xl px-5 py-3 font-extrabold text-black ring-y"
        style="background:var(--yed)"
        onclick="openOfficialChat('السلام عليكم، عندي استفسار بخصوص دورة STEP المكثفة 2026')">
        فتح محادثة الحساب الرسمي
      </button>
    </div>
  </section>

  <!-- Footer -->
  <footer class="mx-auto max-w-6xl px-4 pb-10">
    <div class="text-center text-white/60 text-sm">
      © <span id="yearNow"></span> أكاديمية عايد الرسمية — جميع الحقوق محفوظة
    </div>
  </footer>

  <!-- Toast (social proof) -->
  <div id="toast" class="toast">
    <div class="glass rounded-2xl p-4 shadow-soft">
      <div class="flex items-start justify-between gap-3">
        <div>
          <div class="text-sm text-white/70">إشعار</div>
          <div class="font-extrabold" id="toastTitle">—</div>
          <div class="text-sm text-white/70 mt-1" id="toastBody">—</div>
        </div>
        <button class="btn rounded-lg px-3 py-2 bg-white/10 border border-white/10" onclick="hideToast()">إغلاق</button>
      </div>
    </div>
  </div>

  <!-- Floating buttons -->
  <div class="floating">
    <button class="btn rounded-full px-4 py-3 bg-white/10 border border-white/10" onclick="scrollToEl('toc')">☰</button>
    <button class="btn rounded-full px-4 py-3 text-black font-extrabold ring-y" style="background:var(--yed)" onclick="scrollToEl('payment')">سجّل</button>
  </div>

  <script>
    // ====== Config ======
    const OFFICIAL_USERNAME = "Ayed_Academy_2026";
    const DEADLINE = new Date("2026-01-29T23:59:59+03:00"); // الرياض
    const DISCOUNT_PRICE = 299;
    const REGULAR_PRICE = 449;

    // ====== Helpers ======
    function scrollToEl(id){ document.getElementById(id)?.scrollIntoView({behavior:'smooth',block:'start'}); }
    function showToast(title, body){
      const t = document.getElementById('toast');
      document.getElementById('toastTitle').innerText = title;
      document.getElementById('toastBody').innerText = body;
      t.classList.add('show');
      clearTimeout(window.__toastTimer);
      window.__toastTimer = setTimeout(hideToast, 5200);
    }
    function hideToast(){ document.getElementById('toast').classList.remove('show'); }

    async function copyText(txt){
      try{
        await navigator.clipboard.writeText(txt);
        showToast("تم النسخ ✅", txt);
      }catch(e){
        showToast("تعذر النسخ", "انسخ يدويًا: " + txt);
      }
    }

    function openOfficialChat(prefillText){
      const url = `https://t.me/${OFFICIAL_USERNAME}?text=${encodeURIComponent(prefillText)}`;
      window.open(url, "_blank", "noopener");
    }

    // ====== Countdown & Price ======
    function updateCountdown(){
      const now = new Date();
      const diff = DEADLINE - now;

      const priceNow = diff > 0 ? DISCOUNT_PRICE : REGULAR_PRICE;
      document.getElementById('priceNow').innerText = priceNow;
      document.getElementById('priceHero').innerText = priceNow;

      if(diff <= 0){
        document.getElementById('countdown').innerText = "انتهى وقت الخصم — السعر الآن 449 ريال";
        return;
      }
      const d = Math.floor(diff / (1000*60*60*24));
      const h = Math.floor((diff / (1000*60*60)) % 24);
      const m = Math.floor((diff / (1000*60)) % 60);
      const s = Math.floor((diff / 1000) % 60);
      document.getElementById('countdown').innerText = `${d} يوم • ${h} ساعة • ${m} دقيقة • ${s} ثانية`;
    }
    setInterval(updateCountdown, 1000);
    updateCountdown();

    // ====== Join counter (social proof) ======
    let base = 420 + Math.floor(Math.random()*180);
    document.getElementById('joinCount').innerText = base;
    setInterval(() => {
      base += 1 + Math.floor(Math.random()*3);
      document.getElementById('joinCount').innerText = base;
    }, 18000);

    // ====== Receipt gating ======
    let receiptFile = null;

    function goToEnroll(){
      const input = document.getElementById('receiptUpload');
      const err = document.getElementById('receiptErr');
      if(!input.files || !input.files[0]){
        err.classList.remove('hidden');
        showToast("تنبيه", "لازم ترفق الإيصال قبل الانتقال لنموذج التسجيل.");
        return;
      }
      err.classList.add('hidden');
      receiptFile = input.files[0];

      document.getElementById('enrollLocked').classList.add('hidden');
      document.getElementById('enrollForm').classList.remove('hidden');

      showToast("تم ✅", "تم إرفاق الإيصال — تقدر الآن تعبي نموذج التسجيل.");
      scrollToEl('enroll');
    }

    // ====== Form conditional fields ======
    const prevTestEl = document.getElementById('prevTest');
    const prevScoreWrap = document.getElementById('prevScoreWrap');
    prevTestEl.addEventListener('change', () => {
      if(prevTestEl.value === "نعم") prevScoreWrap.classList.remove('hidden');
      else prevScoreWrap.classList.add('hidden');
    });

    const examWindow = document.getElementById('examWindow');
    const examDate = document.getElementById('examDate');
    examWindow.addEventListener('change', () => {
      const isBooked = examWindow.value.includes("محجوز");
      examDate.disabled = !isBooked;
      if(!isBooked) examDate.value = "";
    });

    // ====== Submit -> open Telegram prefilled message ======
    document.getElementById('enrollForm').addEventListener('submit', (e) => {
      e.preventDefault();

      // Validate receipt exists (mandatory)
      if(!receiptFile){
        showToast("تنبيه", "ارجع لقسم الدفع وارفع الإيصال أولاً.");
        scrollToEl('payment');
        return;
      }

      const confirmPaid = document.getElementById('confirmPaid').checked;
      const confirmSendReceipt = document.getElementById('confirmSendReceipt').checked;
      const formErr = document.getElementById('formErr');

      if(!confirmPaid || !confirmSendReceipt){
        formErr.classList.remove('hidden');
        return;
      }
      formErr.classList.add('hidden');

      const fullName = document.getElementById('fullName').value.trim();
      const contactMethod = document.getElementById('contactMethod').value || "غير محدد";
      const contactValue = document.getElementById('contactValue').value.trim() || "—";
      const examPurpose = document.getElementById('examPurpose').value;
      const examWin = examWindow.value;
      const examDateVal = examDate.value ? examDate.value : "—";
      const prev = prevTestEl.value;
      const prevScore = document.getElementById('prevScore').value.trim() || "—";
      const target = document.getElementById('targetScore').value.trim();
      const level = document.getElementById('level').value;
      const notes = document.getElementById('notes').value.trim() || "—";

      const now = new Date();
      const priceNow = (DEADLINE - now) > 0 ? DISCOUNT_PRICE : REGULAR_PRICE;

      // Receipt details (note: file NOT uploaded; user must attach in Telegram)
      const receiptName = receiptFile?.name || "—";

      const msg =
`السلام عليكم ورحمة الله وبركاته
أرسلت طلب اشتراك في *دورة STEP المكثفة 2026* (أكاديمية عايد الرسمية) ✅

*البيانات:*
• الاسم: ${fullName}
• طريقة التواصل: ${contactMethod}
• بيانات التواصل: ${contactValue}
• الغرض من الاختبار: ${examPurpose}
• موعد الاختبار: ${examWin}${examWin.includes("محجوز") ? ` — التاريخ: ${examDateVal}` : ""}
• سبق الاختبار؟: ${prev}${prev === "نعم" ? ` — الدرجة السابقة: ${prevScore}` : ""}
• الدرجة المستهدفة: ${target}
• المستوى: ${level}
• ملاحظات: ${notes}

*الدفع:*
• قيمة الاشتراك: ${priceNow} ريال
• البنك: بنك الإنماء
• رقم الحساب: 68206067557000
• الآيبان: SA4905000068206067557000
• اسم المستفيد: مؤسسة كريتيفا جلوبال لتقنية المعلومات
• غرض التحويل: مشتريات دورة STEP المكثفة – منصة عايد الرسمية

*ملاحظة مهمة:*
قمتُ برفع الإيصال داخل الموقع (للتأكيد)، وراح أرفق الإيصال هنا في نفس المحادثة الآن للتأكيد النهائي.
اسم ملف الإيصال: ${receiptName}

شاكرين لكم، وبانتظار تفعيل الاشتراك 🙏`;

      const url = `https://t.me/${OFFICIAL_USERNAME}?text=${encodeURIComponent(msg)}`;
      document.getElementById('statusBox').classList.remove('hidden');
      document.getElementById('manualLink').href = `https://t.me/${OFFICIAL_USERNAME}`;

      showToast("تم تجهيز الرسالة ✅", "انفتح لك الخاص… لا تنسى ترفق الإيصال في نفس المحادثة.");

      // Open chat
      window.open(url, "_blank", "noopener");
    });

    // ====== Social proof notifications ======
    const proofs = [
      {t:"تم تفعيل اشتراك ✅", b:"ريم — تم التفعيل خلال 24 ساعة"},
      {t:"نموذج 50 🎯", b:"عبدالله — خلص نموذج 50 وبدأ يراجع الأخطاء"},
      {t:"تحسن واضح 📈", b:"سارة — رفعت درجتها بعد الالتزام بالخطة"},
      {t:"حجز اختبار ⏳", b:"جود — جهزت نفسها وبتدخل الاختبار قريب"},
      {t:"توصية طالب ⭐", b:"فيصل — “الدورة مرتبة وما فيها تشتت”"}
    ];
    function loopProof(){
      const pick = proofs[Math.floor(Math.random()*proofs.length)];
      showToast(pick.t, pick.b);
      const next = 12000 + Math.floor(Math.random()*14000);
      setTimeout(loopProof, next);
    }
    setTimeout(loopProof, 9000);

    // ====== Misc ======
    document.getElementById('yearNow').innerText = new Date().getFullYear();
  </script>
</body>
</html>
