# Questions-of-my-contract-sisterQuestions-Nodal-Choices-
اسئله تحليل عقدي 2
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>اختبار التحليل العقدي الشامل</title>
    <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
    <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
    
    <style>
        :root {
            --gold: #d4af37;
            --black: #0d0d0d;
            --card-bg: #1a1a1a;
            --text-white: #ffffff;
        }
        body {
            background-color: var(--black);
            color: var(--text-white);
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 10px;
            direction: rtl;
        }
        .header {
            text-align: center;
            border: 2px solid var(--gold);
            padding: 20px;
            margin-bottom: 30px;
            border-radius: 15px;
        }
        .header h1 {
            color: var(--gold);
            margin: 0;
            font-size: 1.5rem;
        }
        .lecture-title {
            background-color: var(--gold);
            color: var(--black);
            padding: 10px;
            margin: 30px 0 15px 0;
            border-radius: 5px;
            font-weight: bold;
            text-align: center;
            font-size: 1.2rem;
        }
        .section-sub {
            color: var(--gold);
            font-size: 1.1rem;
            border-bottom: 1px solid var(--gold);
            margin-bottom: 15px;
            padding-bottom: 5px;
        }
        .question-card {
            background-color: var(--card-bg);
            border-right: 4px solid var(--gold);
            padding: 15px;
            margin-bottom: 15px;
            border-radius: 8px;
        }
        .q-eng {
            display: block;
            color: var(--text-white);
            font-weight: bold;
            margin-bottom: 5px;
            direction: ltr;
            text-align: left;
        }
        .q-arb {
            display: block;
            color: var(--gold);
            font-size: 0.95rem;
            margin-bottom: 12px;
        }
        .option {
            display: block;
            background: #262626;
            padding: 10px;
            margin: 5px 0;
            border: 1px solid #444;
            border-radius: 5px;
            font-size: 0.9rem;
            direction: ltr;
            text-align: left;
        }
        .tf-options {
            display: flex;
            gap: 20px;
            margin-top: 10px;
        }
        .footer {
            text-align: center;
            color: #777;
            font-size: 0.8rem;
            margin-top: 50px;
            padding-bottom: 20px;
        }
    </style>
</head>
<body>

    <div class="header">
        <h1>MASTER QUIZ: COMPLEX ANALYSIS</h1>
        <p>60 Questions | Black & Gold Edition</p>
    </div>

    <div class="lecture-title">الملزمة 1: التكامل العقدي (Complex Integration)</div>
    
    <div class="section-sub">أولاً: الاختيارات (MCQ)</div>
    <div class="question-card">
        <span class="q-eng">1. The integral \(\int_a^b f(t) dt\) where \(f(t) = u(t) + iv(t)\) is defined as:</span>
        <span class="q-arb">1. يُعرف تكامل الدالة \(f(t) = u(t) + iv(t)\) بأنه:</span>
        <div class="option">A) \(\int u(t)dt - i \int v(t)dt\)</div>
        <div class="option">B) \(\int u(t)dt + i \int v(t)dt\)</div>
        <div class="option">C) \(\sqrt{\int u^2 + v^2}\)</div>
    </div>

    <div class="question-card">
        <span class="q-eng">2. If \(f(z)\) is analytic inside and on a simple closed contour \(C\), then \(\int_C f(z) dz =\):</span>
        <span class="q-arb">2. إذا كانت الدالة \(f(z)\) تحليلية داخل وعلى مسار مغلق بسيط، فإن قيمة التكامل تساوي:</span>
        <div class="option">A) \(2\pi i\)</div>
        <div class="option">B) \(0\)</div>
        <div class="option">C) \(f'(z)\)</div>
    </div>

    <div class="section-sub">ثانياً: صح أو خطأ (T/F)</div>
    <div class="question-card">
        <span class="q-eng">1. The value of \(\int_C e^{z^3} dz = 0\) for any closed contour \(C\).</span>
        <span class="q-arb">1. قيمة تكامل \(e^{z^3}\) لأي مسار مغلق تساوي صفراً.</span>
        <div class="tf-options"><span>( ) True</span> <span>( ) False</span></div>
    </div>

    <div class="lecture-title">الملزمة 2: المتتابعات والمتسلسلات (Sequences & Series)</div>
    
    <div class="section-sub">أولاً: الاختيارات (MCQ)</div>
    <div class="question-card">
        <span class="q-eng">1. The sequence \(z_n = \frac{i}{n} + n\) is:</span>
        <span class="q-arb">1. المتتابعة \(z_n = \frac{i}{n} + n\) هي متتابعة:</span>
        <div class="option">A) Convergent (متقاربة)</div>
        <div class="option">B) Divergent (متباعدة)</div>
        <div class="option">C) Bounded (مقيدة)</div>
    </div>

    <div class="question-card">
        <span class="q-eng">2. For the series \(\sum_{n=0}^{\infty} z^n\), it converges if:</span>
        <span class="q-arb">2. المتسلسلة \(\sum_{n=0}^{\infty} z^n\) تتقارب إذا كان:</span>
        <div class="option">A) \(|z| < 1\)</div>
        <div class="option">B) \(|z| > 1\)</div>
        <div class="option">C) \(|z| = 1\)</div>
    </div>

    <div class="lecture-title">الملزمة 3: تايلور ولورينت (Taylor & Laurent)</div>
    
    <div class="section-sub">أولاً: الاختيارات (MCQ)</div>
    <div class="question-card">
        <span class="q-eng">1. Maclaurin series is a Taylor series with center \(z_0\) equal to:</span>
        <span class="q-arb">1. متسلسلة ماكلورين هي متسلسلة تايلور بمركز \(z_0\) يساوي:</span>
        <div class="option">A) \(1\)</div>
        <div class="option">B) \(0\)</div>
        <div class="option">C) \(\infty\)</div>
    </div>

    <div class="question-card">
        <span class="q-eng">2. Laurent series is valid in an open region called:</span>
        <span class="q-arb">2. متسلسلة لورينت صالحة في منطقة مفتوحة تسمى:</span>
        <div class="option">A) Circle (دائرة)</div>
        <div class="option">B) Annulus (حلقة)</div>
        <div class="option">C) Square (مربع)</div>
    </div>

    <div class="section-sub">ثانياً: صح أو خطأ (T/F)</div>
    <div class="question-card">
        <span class="q-eng">1. The expansion of \(e^z\) as \(\sum \frac{z^n}{n!}\) is valid for all \(z\).</span>
        <span class="q-arb">1. مفكوك \(e^z\) صالح لجميع قيم \(z\).</span>
        <div class="tf-options"><span>( ) True</span> <span>( ) False</span></div>
    </div>

    <div class="footer">
        إعداد ملف المراجعة الشاملة - التحليل العقدي
    </div>

</body>
</html>
