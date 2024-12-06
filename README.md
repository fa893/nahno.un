<html lang="ar">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="منصة نحن - منصة وطنية لتطوع ومشاركة الشباب تحت رعاية مؤسسة ولي العهد.">
  <title>منصة نحن - بوابة السفراء </title>
  <link href="https://fonts.googleapis.com/css2?family=Arial:wght@400&display=swap" rel="stylesheet">
  <style>
      /* إعدادات عامة */
      body {
          font-family: 'Arial', sans-serif;
          background-color: #3cc4cc; /* لون الخلفية الرئيسي */
          margin: 0;
          padding: 20px;
          color: #40c4cc; /* لون النص العام */
          line-height: 1.6; /* تباعد الأسطر */
          direction: rtl; /* اتجاه الكتابة من اليمين لليسار */
      }

      header {
          text-align: center;
          padding: 10px; /* تقليل مساحة الحشو في الهيدر */
          background-color: #ffffff; /* لون خلفية الهيدر */
          border-radius: 10px; /* جعل الحواف مستديرة */
          box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
      }

      h1 {
          font-size: 2em; /* حجم الخط للعناوين */
          margin: 10px 0; /* تقليل المسافة حول العنوان */
          color: #40c4cc; /* لون نص العنوان */
      }

      .logo-container {
          display: flex;
          justify-content: center; /* توسيط الشعارات */
          align-items: center; /* محاذاة عمودية */
          margin-bottom: 10px; /* مسافة أسفل الشعارات */
      }

      .logo-container img {
          width: 150px; /* تعيين عرض محدد للشعار */
          height: auto; /* الحفاظ على نسبة العرض إلى الارتفاع */
      }

      .create-account {
          text-align: right; /* محاذاة النص إلى اليمين */
          margin-bottom: 10px; /* مسافة أسفل الزر */
      }

      .create-account a {
          background-color: #ffffff; /* لون خلفية الزر */
          color: #004d4d; /* لون النص */
          padding: 10px 15px; /* padding للزر */
          border-radius: 5px; /* حواف مستديرة */
          text-decoration: none; /* إزالة الخط السفلي */
          transition: background-color 0.3s; /* تأثير عند التمرير */
          font-weight: bold; /* جعل النص غامق */
      }

      .buttons-container {
          display: flex;
          justify-content: center;
          flex-wrap: wrap;
          gap: 10px;
          margin-bottom: 10px;
      }

      .buttons-container a {
          background-color: #ffffff; /* خلفية الزر */
          color: #004d4d;
          padding: 10px 15px;
          border-radius: 5px;
          text-decoration: none;
          font-weight: bold;
          transition: background-color 0.3s;
      }

      /* تنسيق عندما يحوم المستخدم فوق الأزرار */
      .buttons-container a:hover {
          background-color: #004d4d;
          color: #ffffff;
      }

      .create-account a:hover {
          background-color: #004d4d; /* تغيير لون الخلفية عند التمرير */
          color: #ffffff; /* تغيير لون النص عند التمرير */
      }

      section {
          margin: 20px 0;
          padding: 20px;
          background-color: #ffffff; /* تغيير لون الخلفية إلى الأبيض */
          border-radius: 10px;
          box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      }

      h2 {
          color: #004d4d; /* لون النص داخل العناوين */
          border-bottom: 2px solid #004d4d; /* خط سفلي تحت العناوين بلون مناسب */
          padding-bottom: 5px; /* مساحة تحت العنوان */
          font-size: 1.5em; /* حجم خط أكبر للعناوين */
      }

      p {
          color: #40c4cc; /* لون النص المحايد */
          font-size: 1.1em; /* حجم خط مناسب للنصوص */
          margin: 10px 0; /* تباعد بين الفقرات */
      }

      .activity-images {
          display: flex;
          justify-content: center; /* لتوسيع الصور في الوسط */
          flex-wrap: wrap; /* للسماح بتجاوز الصور إلى السطر التالي */
          align-items: center; /* محاذاة الصور في المنتصف */
          text-align: center; /* محاذاة النص داخل القسم */
      }

      .activity-images img {
          width: 150px; /* عرض الصور */
          margin: 10px; /* مساحة بين الصور */
          border-radius: 5px; /* لجعل حواف الصور مستديرة */
          box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2); /* إضافة ظل خفيف للصورة */
      }

      .future-message {
          text-align: center; /* توسيط النص */
          font-size: 1.3em; /* حجم خط أكبر للرسالة */
          color: #40c4cc; /* لون النص */
          margin-top: 5px; /* تقليل المسافة فوق النص */
      }

      /* تحسينات للوسائط */
      @media (max-width: 768px) {
          h1 {
              font-size: 1.5em; /* حجم الخط للعناوين في الشاشات الصغيرة */
          }

          .logo-container img {
              width: 120px; /* حجم الشعار في الشاشات الصغيرة */
          }

          .buttons-container a {
              padding: 8px 12px; /* تعديل padding للأزرار في الشاشات الصغيرة */
          }
      }

      @media (max-width: 480px) {
          h1 {
              font-size: 1.3em; /* حجم الخط للعناوين في الشاشات الصغيرة جداً */
          }

          .activity-images img {
              width: 100px; /* تقليل حجم الصور أكثر في الشاشات الصغيرة جداً */
          }

          .create-account a {
              font-size: 0.9em; /* تصغير حجم الخط للزر */
          }
      }

      /* أنماط قسم السفراء */
      .ambassadors-section {
          margin-top: 20px; /* مسافة أعلى قسم السفراء */
          text-align: center; /* توسيط النص */
      }

      .ambassador {
          margin: 20px 0; /* مسافة بين السفراء */
      }

      .ambassador img {
          border-radius: 50%; /* جعل الصورة دائرية */
          width: 100px; /* عرض الصورة */
          height: 100px; /* ارتفاع الصورة */
          margin-bottom: 10px; /* مسافة أسفل الصورة */
      }

      .ambassador-name {
          font-size: 1.1em; /* حجم خط للأسماء */
          color: #40c4cc; /* لون النص */
      }

      .dropdown {
          cursor: pointer;
          padding: 10px;
          border: 1px solid #ccc;
          margin: 5px 0;
          border-radius: 5px;
          background-color: #3cc4cc; /* اللون الجديد */
          color: white; /* لون النص */
          transition: background-color 0.3s;
      }

      .dropdown:hover {
          background-color: #2aa3a3; /* لون عند التمرير */
      }

      .active {
          background-color: #ffcc00; /* اللون عند النقر */
      }

      .names {
          display: none;
          margin: 5px 0;
          padding: 10px;
          border: 1px solid #ccc;
          border-radius: 5px;
          background-color: #ffffff; /* لون الخلفية */
      }
  </style>
  <script>
      function toggleNames(university) {
          const allNames = document.querySelectorAll('.names');
          allNames.forEach(names => {
              names.style.display = 'none'; // إغلاق القوائم الأخرى
          });

          const selectedNames = document.getElementById(university);
          if (selectedNames.style.display === "none") {
              selectedNames.style.display = "block";
              // تغيير لون القائمة المنسدلة النشطة
              const dropdowns = document.querySelectorAll('.dropdown');
              dropdowns.forEach(dropdown => {
                  dropdown.classList.remove('active');
              });
              document.querySelector(`.dropdown[onclick*="${university}"]`).classList.add('active');
          } else {
              selectedNames.style.display = "none";
              document.querySelector(`.dropdown[onclick*="${university}"]`).classList.remove('active');
          }
      }
  </script>
</head>

<body>

<header>
  <div class="logo-container">
      <img src="https://assets.onecompiler.app/42r523uca/4323gpvvz/logo.png" alt="شعار منصة نحن" />
  </div>
  <h1>مرحبًا بكم في بوابة سفراء نحنُ</h1>
  <div class="buttons-container">
      <a href="https://www.nahno.org/register/user/index.php" target="_blank" aria-label="إنشاء حساب جديد في منصة نحن">إنشاء حساب</a>
      <a href="https://chat.whatsapp.com/LWJ1jEfVopNLcu04SKBPuJ" target="_blank" aria-label="الانضمام إلى قروب الفرص على واتساب">انضم إلى قروب الفرص</a>
      <a href="https://drive.google.com/file/d/1PTmmGoodAu_-QTr_CYKS98RFLrdMiPJN/view?usp=sharing" target="_blank" aria-label="كيفية عمل حساب شخصي">كيف أعمل حساب شخصي</a>
      <a href="https://drive.google.com/file/d/1RNwlWL8Wkhjyqe3WGqpgnspRjQcbuLoU/view?usp=sharing" target="_blank" aria-label="كيفية متابعة فرصة">كيف أعمل متابعة لفرصة</a>
      <a href="https://drive.google.com/file/d/1x0Ju6ZEXechpnWiaFgBe0AJXeS8gC957/view?usp=sharing" target="_blank" aria-label="كيفية عمل فرصة ">كيف أعمل فرصة</a>
  </div>
</header>

<main>
<section>
  <h2>تعريف عن منصة نحن</h2>
  <p>منصة "نحنُ" هي المنصة الوطنية لتطوع ومشاركة الشباب، والتي أُطلقت كأحد برامج مؤسسة ولي العهد بدعم من منظمة الأمم المتحدة للطفولة "يونيسف"، وبالتعاون مع وزارة الشباب. تهدف المنصة إلى تشجيع العمل التطوعي والمشاركة الشبابية من أجل إحداث تغيير إيجابي في المجتمعات.</p>
  <p>تعتبر "نحنُ" الأولى من نوعها في المملكة، حيث تسعى لتوحيد الجهود المبذولة في مجال العمل التطوعي. تُتيح المنصة الفرص التطوعية من مختلف مؤسسات المجتمع المدني والشركات الخاصة والقطاع العام، مما يوفر للشباب إمكانية المشاركة في الأعمال التطوعية التي تناسب اهتماماتهم.</p>
</section>

<section>
  <h2>دور الجامعات</h2>
  <p>تسهم الجامعات الأردنية بشكل كبير في تعزيز التعليم والبحث العلمي، حيث تقدم برامج متقدمة وتشارك في مبادرات مجتمعية تهدف إلى تحسين جودة الحياة. في المقابل، يعمل سفراء منصة نحن الوطنية على نشر الوعي بقضايا التنمية المستدامة، ويشجعون الشباب على الانخراط في الأنشطة التطوعية والمبادرات المجتمعية. كما يدعمون المشاريع الشبابية ويوفرون المنصات اللازمة لعرض أفكارهم. من خلال التعاون بين الجامعات وسفراء منصة نحن، يتم تعزيز روح العمل الجماعي والمشاركة، مما يسهم في بناء مستقبل أفضل للشباب والمجتمع في الأردن.</p>
</section>

<section>
  <h2>دور سفراء منصة نحن</h2>
  <p>يؤدي سفراء منصة نحن داخل الجامعات دورًا حيويًا في تعزيز الوعي والمشاركة المجتمعية بين الطلاب من خلال...</p>
</section>

<section class="ambassadors-section">
  <h2>سفراء نحن</h2>
  <p>هؤلاء هم سفراء منصة نحن:</p>

  <div class="dropdown" onclick="toggleNames('al_bayt')">جامعة آل البيت</div>
  <div id="al_bayt" class="names">
      ميار أحمد عواد هواري<br>
      فرحان مفلح فرحان الخوالدة<br>
  </div>

  <div class="dropdown" onclick="toggleNames('balqa')">جامعة البلقاء التطبيقية</div>
  <div id="balqa" class="names">
      نور علي محمد عويدات<br>
      أحمد محمود سالم السطري<br>
      لما نادر سليمان المشاقبة<br>
      حمزة أحمد عبدالحليم الحياري<br>
      راما خلدون فياض الرماضنه<br>
  </div>

  <div class="dropdown" onclick="toggleNames('zarka_private')">جامعة الزرقاء الخاصة</div>
  <div id="zarka_private" class="names">
      أمين حمدان<br>                           
      سيرين غسان يوسف شاهين<br>
  </div>

  <div class="dropdown" onclick="toggleNames('hashemite')">الجامعة الهاشمية</div>
  <div id="hashemite" class="names">
                             <br>ماريا محمد بنيان وريدات
    أبرار عبدالحافظ خلف الرقاد<br>
  </div>

  <div class="dropdown" onclick="toggleNames('jordan')">الجامعة الأردنية</div>
  <div id="jordan" class="names">
      مجاهد هاني سليمان البيادرة<br>
      ليان مراد سمان<br>
  </div>

  <div class="dropdown" onclick="toggleNames('tafila')">جامعة الطفيلة التقنية</div>
  <div id="tafila" class="names">
      محمد علي يعقوب العونه<br>
      أيهم مؤيد حسني علان<br>
  </div>

  <div class="dropdown" onclick="toggleNames('shobak')">كلية الشوبك الجامعية</div>
  <div id="shobak" class="names">
      محمد أحمد علي عبيدات<br>
  </div>

  <div class="dropdown" onclick="toggleNames('zaytouna')">جامعة الزيتونة الأردنية</div>
  <div id="zaytouna" class="names">
      براءة عطا عطيه عريقات<br>
      سوزان موسى العجارمة<br>
  </div>

  <div class="dropdown" onclick="toggleNames('balqa_college')">البلقاء التطبيقية - كلية الأميرة عالية الجامعية</div>
  <div id="balqa_college" class="names">
      أسماء أيمن عاطف زاهدة<br>
  </div>

  <div class="dropdown" onclick="toggleNames('jadara')">جامعة جدارا</div>
  <div id="jadara" class="names">
      لين أحمد محمد خير طيفور<br>
      عامر قاسم محمد الطعاني<br>
      لينا شادي ضيف الله آغا<br>
  </div>

  <div class="dropdown" onclick="toggleNames('israa')">جامعة الإسراء</div>
  <div id="israa" class="names">
      البيِّنة رائد عيسى المواجدة<br>
  </div>

  <div class="dropdown" onclick="toggleNames('jarash')">جامعة جرش الأهلية</div>
  <div id="jarash" class="names">
      رزان مؤمن خالد الجغبير<br>
  </div>

  <div class="dropdown" onclick="toggleNames('irbid')">جامعة إربد الأهلية</div>
  <div id="irbid" class="names">
      سارة محمد طراد شواقفة<br>
      فيّ عماد علي حميد<br>
      سديم سمير طالب شواقفة<br>
  </div>

  <div class="dropdown" onclick="toggleNames('yarmouk')">جامعة اليرموك</div>
  <div id="yarmouk" class="names">
      عزيزة محمد تاج الدين السقال<br>
      داليا تيسير عطا إدريس<br>
      آدم يوسف علي مقابله<br>
  </div>

  <div class="dropdown" onclick="toggleNames('batra')">جامعة البترا</div>
  <div id="batra" class="names">
      جودي عماد حسن سليم<br>
  </div>

  <div class="dropdown" onclick="toggleNames('just')">جامعة العلوم والتكنولوجيا الأردنية</div>
  <div id="just" class="names">
      ملك زايد يوسف النصر<br>
      بتول خلدون موسى صياحين<br>
  </div>

  <div class="dropdown" onclick="toggleNames('applied_sciences')">جامعة العلوم التطبيقية الخاصة</div>
  <div id="applied_sciences" class="names">
      جود مناور عبدربه العلاوين<br>
  </div>

  <div class="dropdown" onclick="toggleNames('middle_east')">جامعة الشرق الأوسط</div>
  <div id="middle_east" class="names">
      سلسبيل مثنى محمود حجازي<br>
      سميحة أدهم تحسين تيمور<br>
  </div>

  
  <footer>
        <p> 2024 بوابة السفراء. جميع الحقوق محفوظة.</p>
    <p>This portal was designed by Engineer Farhan AL- Khawaldeh.</p>
    </footer>
