
# hotel-front-office
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>أفكار مشاريع الفندقة</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
    }

    body {
      background: #f5efe6;
      color: #4b3425;
    }

    header {
      background: #6b4b35;
      color: white;
      text-align: center;
      padding: 35px 20px;
    }

    header h1 {
      font-size: 32px;
      margin-bottom: 10px;
    }

    header p {
      font-size: 17px;
    }

    .container {
      width: 90%;
      max-width: 1100px;
      margin: 35px auto;
    }

    .intro {
      text-align: center;
      margin-bottom: 30px;
    }

    .intro h2 {
      font-size: 26px;
      margin-bottom: 10px;
    }

    .ideas {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      background: white;
      border-radius: 15px;
      padding: 25px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .card h3 {
      color: #6b4b35;
      margin-bottom: 12px;
      font-size: 21px;
    }

    .card p {
      line-height: 1.8;
      color: #5f5147;
    }

    .btn {
      display: block;
      width: fit-content;
      margin: 35px auto 10px;
      padding: 12px 25px;
      background: #8b684d;
      color: white;
      text-decoration: none;
      border-radius: 10px;
      cursor: pointer;
      border: none;
      font-size: 16px;
    }

    .btn:hover {
      background: #5b3e2b;
    }

    #moreIdeas {
      display: none;
      margin-top: 25px;
      text-align: center;
      background: #fff;
      padding: 25px;
      border-radius: 15px;
      line-height: 2;
    }

    footer {
      margin-top: 50px;
      background: #6b4b35;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>

<body>

  <header>
    <h1>أفكار مشاريع الفندقة</h1>
    <p>أفكار مبتكرة تساعد على تطوير الخدمات الفندقية</p>
  </header>

  <main class="container">

    <section class="intro">
      <h2>أفكار المشاريع</h2>
      <p>مجموعة من الأفكار التي يمكن تطويرها في مجال الفنادق والسياحة.</p>
    </section>

    <section class="ideas">

      <div class="card">
        <h3>🏨 الفندق الذكي</h3>
        <p>
          استخدام التقنية لتسهيل تجربة النزيل، مثل تسجيل الدخول الإلكتروني
          والتحكم في الغرفة باستخدام الهاتف.
        </p>
      </div>

      <div class="card">
        <h3>🤖 المساعد الفندقي الذكي</h3>
        <p>
          مساعد يعتمد على الذكاء الاصطناعي للإجابة عن أسئلة النزلاء
          وتقديم المعلومات والخدمات الفندقية.
        </p>
      </div>

      <div class="card">
        <h3>🌱 الفندق الأخضر</h3>
        <p>
          مشروع يهتم بالاستدامة من خلال تقليل استهلاك الماء والطاقة
          واستخدام المنتجات الصديقة للبيئة.
        </p>
      </div>

      <div class="card">
        <h3>📱 تطبيق خدمات الفندق</h3>
        <p>
          تطبيق يتيح للنزيل طلب الطعام والتنظيف والصيانة ومعرفة
          مرافق الفندق والخدمات المتوفرة.
        </p>
      </div>

      <div class="card">
        <h3>🎯 تجربة النزيل المميزة</h3>
        <p>
          تصميم خدمات وتجارب مخصصة للنزلاء حسب اهتماماتهم واحتياجاتهم
          أثناء الإقامة.
        </p>
      </div>

      <div class="card">
        <h3>🧳 خدمة السياحة الفندقية</h3>
        <p>
          ربط الفندق بالمعالم السياحية والأنشطة الترفيهية لمساعدة النزيل
          على التخطيط لرحلته بسهولة.
        </p>
      </div>

    </section>

    <button class="btn" onclick="showIdeas()">
      عرض فكرة إضافية
    </button>

    <div id="moreIdeas">
      <h2>💡 فكرة إضافية</h2>
      <p>
        إنشاء منصة تجمع الفنادق والأنشطة السياحية والمواصلات في مكان واحد،
        بحيث يستطيع السائح التخطيط لرحلته وحجز الخدمات بسهولة.
      </p>
    </div>

  </main>

  <footer>
    <p>مشروع أفكار الفندقة © 2026</p>
  </footer>

  <script>
    function showIdeas() {
      const ideas = document.getElementById("moreIdeas");

      if (ideas.style.display === "none" || ideas.style.display === "") {
        ideas.style.display = "block";
      } else {
        ideas.style.display = "none";
      }
    }
  </script>

</body>
</html>
