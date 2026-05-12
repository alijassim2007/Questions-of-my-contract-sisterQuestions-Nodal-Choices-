<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>60 سؤال في التحليل العقدي</title>
    <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
    <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
    
    <style>
        :root {
            --gold: #d4af37;
            --black: #0d0d0d;
            --card-bg: #1a1a1a;
            --white: #ffffff;
        }
        body {
            background-color: var(--black);
            color: var(--white);
            font-family: 'Segoe UI', Tahoma, sans-serif;
            margin: 0;
            padding: 10px;
        }
        .container { max-width: 800px; margin: auto; }
        .header {
            text-align: center;
            border: 2px solid var(--gold);
            padding: 20px;
            margin-bottom: 30px;
            border-radius: 15px;
            background: linear-gradient(45deg, #1a1a1a, #000);
        }
        .header h1 { color: var(--gold); font-size: 1.4rem; margin: 0; }
        .lec-box {
            background: var(--gold);
            color: black;
            padding: 10px;
            margin: 40px 0 20px 0;
            font-weight: bold;
            text-align: center;
            border-radius: 5px;
        }
        .type-title {
            color: var(--gold);
            border-bottom: 1px solid var(--gold);
            display: inline-block;
            margin-bottom: 15px;
        }
        .q-card {
            background: var(--card-bg);
            border-right: 4px solid var(--gold);
            padding: 15px;
            margin-bottom: 15px;
            border-radius: 8px;
        }
        .eng { display: block; direction: ltr; text-align: left; font-weight: bold; margin-bottom: 5px; }
        .arb { display: block; color: var(--gold); font-size: 0.9rem; margin-bottom: 10px; }
        .opt {
            display: block;
            background: #262626;
            padding: 8px;
            margin: 4px 0;
            border: 1px solid #444;
            border-radius: 4px;
            font-size: 0.85rem;
            direction: ltr; text-align: left;
        }
        .tf-area { display: flex; gap: 20px; margin-top: 5px; font-weight: bold; }
        .footer { text-align: center; color: #555; padding: 30px; }
    </style>
</head>
<body>
<div class="container">

    <div class="header">
        <h1>الاختبار الشامل (60 سؤالاً)</h1>
        <p>Complex Analysis Master Quiz</p>
    </div>

    <div class="lec-box">LECTURE 1: COMPLEX INTEGRATION</div>
    <h3 class="type-title">Multiple Choice (10 Questions)</h3>
    
    <div class="q-card">
        <span class="eng">1. If f(t) = u(t) + i v(t), then \(\int_a^b f(t) dt\) equals:</span>
        <span class="arb">1. إذا كانت الدالة عقدية، فإن التكامل يساوي:</span>
        <div class="opt">A) \(\int u dt + i \int v dt\)</div>
        <div class="opt">B) \(\int u dt - i \int v dt\)</div>
    </div>
    <div class="q-card">
        <span class="eng">2. The value of \(\int_0^{\pi/6} e^{2it} dt\) involves:</span>
        <span class="arb">2. حساب تكامل \(e^{2it}\) يتطلب استخدام:</span>
        <div class="opt">A) Euler's Formula</div>
        <div class="opt">B) Cauchy's Inequality</div>
    </div>
    <div class="q-card">
        <span class="eng">3. Cauchy-Goursat theorem states \(\int_C f(z) dz = 0\) if f is:</span>
        <span class="arb">3. تكون قيمة التكامل صفراً إذا كانت الدالة:</span>
        <div class="opt">A) Analytic (تحليلية)</div>
        <div class="opt">B) Constant only</div>
    </div>
    <div class="q-card">
        <span class="eng">4. Green's theorem relates line integrals to:</span>
        <span class="arb">4. تربط نظرية غرين بين التكامل الخطي و:</span>
        <div class="opt">A) Double integrals (التكاملات الثنائية)</div>
        <div class="opt">B) Derivatives</div>
    </div>
    <div class="q-card">
        <span class="eng">5. Goursat removed the condition of continuity for:</span>
        <span class="arb">5. قام غورسات بإلغاء شرط الاستمرارية لـ:</span>
        <div class="opt">A) \(f'(z)\)</div>
        <div class="opt">B) \(f(z)\)</div>
    </div>
    <div class="q-card">
        <span class="eng">6. \(\int_C e^{z^3} dz\) over a closed contour is:</span>
        <span class="arb">6. تكامل الدالة الأسية على مسار مغلق هو:</span>
        <div class="opt">A) 0</div>
        <div class="opt">B) 1</div>
    </div>
    <div class="q-card">
        <span class="eng">7. If C is a simple closed contour, the region it encloses is:</span>
        <span class="arb">7. المنطقة التي يحيط بها الكانتور البسيط تسمى:</span>
        <div class="opt">A) Simply connected</div>
        <div class="opt">B) Multiply connected</div>
    </div>
    <div class="q-card">
        <span class="eng">8. The real variable t in f(t) is:</span>
        <span class="arb">8. المتغير t في الدالة f(t) هو متغير:</span>
        <div class="opt">A) Real (حقيقي)</div>
        <div class="opt">B) Complex</div>
    </div>
    <div class="q-card">
        <span class="eng">9. To calculate \(\int_C \bar{z} dz\), we use:</span>
        <span class="arb">9. لحساب تكامل مرافق z نستخدم:</span>
        <div class="opt">A) Parameterization of C</div>
        <div class="opt">B) Cauchy Theorem directly</div>
    </div>
    <div class="q-card">
        <span class="eng">10. Cauchy's original result was obtained in the:</span>
        <span class="arb">10. حصل كوشي على نتيجته الأصلية في القرن:</span>
        <div class="opt">A) 19th Century</div>
        <div class="opt">B) 20th Century</div>
    </div>

    <h3 class="type-title">True or False (10 Questions)</h3>
    <div class="q-card">
        <span class="eng">11. Every continuous function is analytic.</span>
        <span class="arb">11. كل دالة مستمرة هي دالة تحليلية.</span>
        <div class="tf-area"><span>( ) T</span> <span>( ) F</span></div>
    </div>
    <div class="q-card">
        <span class="eng">12. Goursat was the first to prove continuity of f' is not required.</span>
        <span class="arb">12. غورسات أول من برهن عدم اشتراط استمرارية المشتقة.</span>
        <div class="tf-area"><span>( ) T</span> <span>( ) F</span></div>
    </div>
    <div class="q-card">
        <span class="eng">13. \(\int_C f(z) dz\) depends on the path if f is analytic.</span>
        <span class="arb">13. يعتمد التكامل على المسار إذا كانت الدالة تحليلية.</span>
        <div class="tf-area"><span>( ) T</span> <span>( ) F</span></div>
    </div>
    <div class="q-card">
        <span class="eng">14. A contour is a set of smooth arcs.</span>
        <span class="arb">14. الكانتور هو مجموعة من الأقواس الناعمة.</span>
        <div class="tf-area"><span>( ) T</span> <span>( ) F</span></div>
    </div>
    <div class="q-card">
        <span class="eng">15. Cauchy-Riemann equations must be satisfied for analyticity.</span>
        <span class="arb">15. يجب تحقق معادلات كوشي-ريه لكي تكون الدالة تحليلية.</span>
        <div class="tf-area"><span>( ) T</span> <span>( ) F</span></div>
    </div>
    <div class="q-card">
        <span class="eng">16. The integral of 1/z over the unit circle is 0.</span>
        <span class="arb">16. تكامل 1/z على دائرة الوحدة يساوي صفر.</span>
        <div class="tf-area"><span>( ) T</span> <span>( ) F</span></div>
    </div>
    <div class="q-card">
        <span class="eng">17. Integration is a linear operator in complex analysis.</span>
        <span class="arb">17. التكامل عملية خطية في التحليل العقدي.</span>
        <div class="tf-area"><span>( ) T</span> <span>( ) F</span></div>
    </div>
    <div class="q-card">
        <span class="eng">18. Green's theorem requires the functions P and Q to have continuous partials.</span>
        <span class="arb">18. تتطلب نظرية غرين مشتقات جزئية مستمرة.</span>
        <div class="tf-area"><span>( ) T</span> <span>( ) F</span></div>
    </div>
    <div class="q-card">
        <span class="eng">19. The length of a path does not affect the integral value.</span>
        <span class="arb">19. طول المسار لا يؤثر على قيمة التكامل.</span>
        <div class="tf-area"><span>( ) T</span> <span>( ) F</span></div>
    </div>
    <div class="q-card">
        <span class="eng">20. Complex integration is defined only on lines.</span>
        <span class="arb">20. التكامل العقدي يُعرف فقط على الخطوط المستقيمة.</span>
        <div class="tf-area"><span>( ) T</span> <span>( ) F</span></div>
    </div>

    <div class="lec-box">LECTURE 2: SEQUENCES & SERIES</div>
    <h3 class="type-title">Multiple Choice (10 Questions)</h3>
    <div class="q-card">
        <span class="eng">21. A sequence {z_n} converges to L if \(\lim_{n \to \infty} z_n =\):</span>
        <span class="arb">21. تتقارب المتتابعة إذا كانت غايتها تساوي:</span>
        <div class="opt">A) L</div>
        <div class="opt">B) 0 always</div>
    </div>
    <div class="q-card">
        <span class="eng">22. The sequence \(z_n = \frac{i}{n} + n\) is:</span>
        <span class="arb">22. المتتابعة المذكورة هي:</span>
        <div class="opt">A) Divergent (متباعدة)</div>
        <div class="opt">B) Convergent</div>
    </div>
    <div class="q-card">
        <span class="eng">23. In the Ratio Test, the series converges if the limit is:</span>
        <span class="arb">23. في اختبار النسبة، تتقارب المتسلسلة إذا كانت الغاية:</span>
        <div class="opt">A) < 1</div>
        <div class="opt">B) > 1</div>
    </div>
    <div class="q-card">
        <span class="eng">24. The radius of convergence R is calculated as:</span>
        <span class="arb">24. يحسب نصف قطر التقارب من:</span>
        <div class="opt">A) \(1 / \rho\)</div>
        <div class="opt">B) \(\rho\)</div>
    </div>
    <div class="q-card">
        <span class="eng">25. For the series \(\sum_{n=1}^\infty \frac{1}{n^2}\), the series:</span>
        <span class="arb">25. المتسلسلة \(\sum 1/n^2\):</span>
        <div class="opt">A) Converges</div>
        <div class="opt">B) Diverges</div>
    </div>
    <div class="q-card">
        <span class="eng">26. Geometric series \(\sum z^n\) converges if:</span>
        <span class="arb">26. تتقارب المتسلسلة الهندسية إذا كان:</span>
        <div class="opt">A) |z| < 1</div>
        <div class="opt">B) |z| > 1</div>
    </div>
    <div class="q-card">
        <span class="eng">27. A sequence is bounded if all terms lie inside a:</span>
        <span class="arb">27. تكون المتتابعة مقيدة إذا كانت الحدود داخل:</span>
        <div class="opt">A) Circle</div>
        <div class="opt">B) Point</div>
    </div>
    <div class="q-card">
        <span class="eng">28. The limit of \(z_n = x_n + i y_n\) depends on limits of:</span>
        <span class="arb">28. غاية \(z_n\) تعتمد على غايات:</span>
        <div class="opt">A) x_n and y_n</div>
        <div class="opt">B) x_n only</div>
    </div>
    <div class="q-card">
        <span class="eng">29. The series \(\sum \frac{(z+2)^{n+1}}{(n+1)^3 4^n}\) uses:</span>
        <span class="arb">29. المتسلسلة أعلاه تُحل باستخدام:</span>
        <div class="opt">A) Ratio Test</div>
        <div class="opt">B) Integration</div>
    </div>
    <div class="q-card">
        <span class="eng">30. If a series is absolutely convergent, it is:</span>
        <span class="arb">30. إذا كانت المتسلسلة متقاربة مطلقاً فهي:</span>
        <div class="opt">A) Convergent</div>
        <div class="opt">B) Divergent</div>
    </div>

    <h3 class="type-title">True or False (10 Questions)</h3>
    <div class="q-card">
        <span class="eng">31. A divergent sequence can have a limit.</span>
        <span class="arb">31. يمكن للمتتابعة المتباعدة أن تمتلك غاية.</span>
        <div class="tf-area"><span>( ) T</span> <span>( ) F</span></div>
    </div>
    <div class="q-card">
        <span class="eng">32. \(\lim_{n \to \infty} (1+1/n)^n = e\).</span>
        <span class="arb">32. نهاية المقدار تعطي الثابت الطبيعي e.</span>
        <div class="tf-area"><span>( ) T</span> <span>( ) F</span></div>
    </div>
    <div class="q-card">
        <span class="eng">33. Radius of convergence can be 0.</span>
        <span class="arb">33. يمكن أن يكون نصف قطر التقارب صفراً.</span>
        <div class="tf-area"><span>( ) T</span> <span>( ) F</span></div>
    </div>
    <div class="q-card">
        <span class="eng">34. If \(\lim z_n = L\), then \(\lim |z_n| = |L|\).</span>
        <span class="arb">34. إذا تقاربت المتتابعة تقاربت قيمتها المطلقة.</span>
        <div class="tf-area"><span>( ) T</span> <span>( ) F</span></div>
    </div>
    <div class="q-card">
        <span class="eng">35. All power series converge for all z.</span>
        <span class="arb">35. جميع متسلسلات القوى تتقارب لكل قيم z.</span>
        <div class="tf-area"><span>( ) T</span> <span>( ) F</span></div>
    </div>
    <div class="q-card">
        <span class="eng">36. A sequence is a function from \(\mathbb{N}\) to \(\mathbb{C}\).</span>
        <span class="arb">36. المتتابعة هي دالة من الأعداد الطبيعية إلى المعقدة.</span>
        <div class="tf-area"><span>( ) T</span> <span>( ) F</span></div>
    </div>
    <div class="q-card">
        <span class="eng">37. If \(\sum |a_n|\) diverges, \(\sum a_n\) must diverge.</span>
        <span class="arb">37. إذا تباعدت المطلقة يجب أن تتباعد المتسلسلة الأصلية.</span>
        <div class="tf-area"><span>( ) T</span> <span>( ) F</span></div>
    </div>
    <div class="q-card">
        <span class="eng">38. The nth term test can prove convergence.</span>
        <span class="arb">38. اختبار الحد النوني يمكن أن يثبت التقارب.</span>
        <div class="tf-area"><span>( ) T</span> <span>( ) F</span></div>
    </div>
    <div class="q-card">
        <span class="eng">39. \(\sum i^n\) is a convergent series.</span>
        <span class="arb">39. المتسلسلة \(\sum i^n\) متقاربة.</span>
        <div class="tf-area"><span>( ) T</span> <span>( ) F</span></div>
    </div>
    <div class="q-card">
        <span class="eng">40. Constant sequences are always convergent.</span>
        <span class="arb">40. المتتابعات الثابتة دائماً متقاربة.</span>
        <div class="tf-area"><span>( ) T</span> <span>( ) F</span></div>
    </div>

    <div class="lec-box">LECTURE 3: TAYLOR & LAURENT SERIES</div>
    <h3 class="type-title">Multiple Choice (10 Questions)</h3>
    <div class="q-card">
        <span class="eng">41. If \(z_0 = 0\) in Taylor series, it is called:</span>
        <span class="arb">41. تسمى متسلسلة تايلور بـ "ماكلورين" إذا كان المركز:</span>
        <div class="opt">A) Maclaurin Series</div>
        <div class="opt">B) Laurent Series</div>
    </div>
    <div class="q-card">
        <span class="eng">42. Laurent series represents functions in:</span>
        <span class="arb">42. تمثل متسلسلة لورينت الدوال في مناطق:</span>
        <div class="opt">A) Annular regions (حلقية)</div>
        <div class="opt">B) Points only</div>
    </div>
    <div class="q-card">
        <span class="eng">43. The coefficient \(a_n\) in Taylor series is:</span>
        <span class="arb">43. المعامل \(a_n\) يساوي:</span>
        <div class="opt">A) \(f^{(n)}(z_0) / n!\)</div>
        <div class="opt">B) \(f(z_0)\)</div>
    </div>
    <div class="q-card">
        <span class="eng">44. The Maclaurin series for \(e^z\) is:</span>
        <span class="arb">44. متسلسلة ماكلورين لـ \(e^z\) هي:</span>
        <div class="opt">A) \(\sum z^n / n!\)</div>
        <div class="opt">B) \(\sum (-1)^n z^n\)</div>
    </div>
    <div class="q-card">
        <span class="eng">45. Laurent series has powers that are:</span>
        <span class="arb">45. قوى متسلسلة لورينت تكون:</span>
        <div class="opt">A) Positive and Negative</div>
        <div class="opt">B) Positive only</div>
    </div>
    <div class="q-card">
        <span class="eng">46. The expansion of \(1/(1-z)\) for |z| < 1 is:</span>
        <span class="arb">46. مفكوك \(1/(1-z)\) هو:</span>
        <div class="opt">A) \(\sum z^n\)</div>
        <div class="opt">B) \(\sum (-1)^n z^n\)</div>
    </div>
    <div class="q-card">
        <span class="eng">47. For \(|z| > 1\), the expansion of \(1/(z-1)\) involves:</span>
        <span class="arb">47. للمنطقة \(|z|>1\) نستخدم:</span>
        <div class="opt">A) \(\frac{1}{z(1-1/z)}\)</div>
        <div class="opt">B) Taylor series directly</div>
    </div>
    <div class="q-card">
        <span class="eng">48. Taylor series expansion requires f(z) to be:</span>
        <span class="arb">48. يتطلب مفكوك تايلور أن تكون الدالة:</span>
        <div class="opt">A) Analytic</div>
        <div class="opt">B) Singular</div>
    </div>
    <div class="q-card">
        <span class="eng">49. In \(\log(1+z)\) expansion, the power of z starts from:</span>
        <span class="arb">49. في مفكوك اللوغاريتم، تبدأ قوى z من:</span>
        <div class="opt">A) 1</div>
        <div class="opt">B) 0</div>
    </div>
    <div class="q-card">
        <span class="eng">50. A function analytic everywhere is:</span>
        <span class="arb">50. الدالة التحليلية في كل مكان تسمى:</span>
        <div class="opt">A) Entire function</div>
        <div class="opt">B) Limited function</div>
    </div>

    <h3 class="type-title">True or False (10 Questions)</h3>
    <div class="q-card">
        <span class="eng">51. Maclaurin series is a special case of Taylor series.</span>
        <span class="arb">51. متسلسلة ماكلورين هي حالة خاصة من تايلور.</span>
        <div class="tf-area"><span>( ) T</span> <span>( ) F</span></div>
    </div>
    <div class="q-card">
        <span class="eng">52. Laurent series cannot represent f(z) at a singularity.</span>
        <span class="arb">52. لا يمكن لمتسلسلة لورينت تمثيل الدالة عند النقطة الشاذة.</span>
        <div class="tf-area"><span>( ) T</span> <span>( ) F</span></div>
    </div>
    <div class="q-card">
        <span class="eng">53. \(e^z = 1 + z + z^2/2! + \dots\)</span>
        <span class="arb">53. هذا هو المفكوك الصحيح للدالة الأسية.</span>
        <div class="tf-area"><span>( ) T</span> <span>( ) F</span></div>
    </div>
    <div class="q-card">
        <span class="eng">54. \(\sin(z)\) expansion has only even powers.</span>
        <span class="arb">54. مفكوك الجيب يحتوي على القوى الزوجية فقط.</span>
        <div class="tf-area"><span>( ) T</span> <span>( ) F</span></div>
    </div>
    <div class="q-card">
        <span class="eng">55. Taylor series converges inside a circle.</span>
        <span class="arb">55. تتقارب متسلسلة تايلور داخل دائرة.</span>
        <div class="tf-area"><span>( ) T</span> <span>( ) F</span></div>
    </div>
    <div class="q-card">
        <span class="eng">56. Laurent expansion is unique for a given annulus.</span>
        <span class="arb">56. مفكوك لورينت وحيد لمنطقة حلقية معينة.</span>
        <div class="tf-area"><span>( ) T</span> <span>( ) F</span></div>
    </div>
    <div class="q-card">
        <span class="eng">57. \(\log(1+z)\) series converges for |z| > 1.</span>
        <span class="arb">57. متسلسلة اللوغاريتم تتقارب عندما |z| أكبر من 1.</span>
        <div class="tf-area"><span>( ) T</span> <span>( ) F</span></div>
    </div>
    <div class="q-card">
        <span class="eng">58. The center of a series \(z_0\) must be a real number.</span>
        <span class="arb">58. يجب أن يكون مركز المتسلسلة عدداً حقيقياً.</span>
        <div class="tf-area"><span>( ) T</span> <span>( ) F</span></div>
    </div>
    <div class="q-card">
        <span class="eng">59. Entire functions have R = \(\infty\).</span>
        <span class="arb">59. الدوال الكلية تمتلك نصف قطر تقارب لا نهائي.</span>
        <div class="tf-area"><span>( ) T</span> <span>( ) F</span></div>
    </div>
    <div class="q-card">
        <span class="eng">60. \(f(z) = 1/z\) can be expanded as Taylor series around 0.</span>
        <span class="arb">60. يمكن فك الدالة \(1/z\) كمتسلسلة تايلور حول الصفر.</span>
        <div class="tf-area"><span>( ) T</span> <span>( ) F</span></div>
    </div>

    <div class="footer">
        تم إعداد 60 سؤالاً بنجاح (3 ملازم × 20 سؤال)
    </div>
</div>
</body>
</html>
