<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>اختبار الكيمياء التفاعلي</title>
    <style>
        :root {
            --primary-blue: #1e3a8a;
            --secondary-blue: #3b82f6;
            --light-blue: #dbeafe;
            --white: #ffffff;
            --correct: #10b981;
            --incorrect: #ef4444;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: var(--light-blue);
            color: var(--primary-blue);
            line-height: 1.6;
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        
        .page {
            display: none;
            background-color: var(--white);
            border-radius: 10px;
            padding: 30px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            margin-top: 20px;
        }
        
        .active {
            display: block;
        }
        
        h1, h2, h3 {
            color: var(--primary-blue);
            margin-bottom: 20px;
            text-align: center;
        }
        
        .form-group {
            margin-bottom: 20px;
        }
        
        label {
            display: block;
            margin-bottom: 8px;
            font-weight: bold;
        }
        
        input, select {
            width: 100%;
            padding: 10px;
            border: 1px solid var(--secondary-blue);
            border-radius: 5px;
            font-size: 16px;
        }
        
        button {
            background-color: var(--secondary-blue);
            color: var(--white);
            border: none;
            padding: 12px 20px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
            font-weight: bold;
            transition: background-color 0.3s;
            display: block;
            margin: 20px auto;
        }
        
        button:hover {
            background-color: var(--primary-blue);
        }
        
        .question-container {
            margin-bottom: 30px;
            padding: 20px;
            border: 1px solid var(--light-blue);
            border-radius: 8px;
            background-color: var(--white);
        }
        
        .options {
            display: flex;
            flex-direction: column;
            gap: 10px;
            margin-top: 15px;
        }
        
        .option {
            padding: 12px;
            border: 1px solid var(--secondary-blue);
            border-radius: 5px;
            cursor: pointer;
            transition: all 0.3s;
        }
        
        .option:hover {
            background-color: var(--light-blue);
        }
        
        .selected {
            background-color: var(--secondary-blue);
            color: var(--white);
        }
        
        .correct {
            background-color: var(--correct);
            color: var(--white);
        }
        
        .incorrect {
            background-color: var(--incorrect);
            color: var(--white);
        }
        
        .feedback {
            text-align: center;
            padding: 15px;
            margin: 15px 0;
            border-radius: 5px;
            font-weight: bold;
        }
        
        .success {
            background-color: var(--correct);
            color: var(--white);
        }
        
        .error {
            background-color: var(--incorrect);
            color: var(--white);
        }
        
        .countdown {
            text-align: center;
            font-size: 24px;
            font-weight: bold;
            margin: 20px 0;
        }
        
        .developers {
            background-color: var(--light-blue);
            padding: 15px;
            border-radius: 8px;
            margin-top: 30px;
        }
        
        .result-message {
            text-align: center;
            padding: 20px;
            margin: 20px 0;
            border-radius: 8px;
            font-size: 18px;
            font-weight: bold;
        }
        
        .excellent {
            background-color: var(--correct);
            color: var(--white);
        }
        
        .good {
            background-color: #f59e0b;
            color: var(--white);
        }
        
        .poor {
            background-color: var(--incorrect);
            color: var(--white);
        }
        
        .review-item {
            margin-bottom: 20px;
            padding: 15px;
            border-radius: 8px;
            background-color: var(--light-blue);
        }
        
        .correct-answer {
            color: var(--correct);
            font-weight: bold;
        }
        
        .wrong-answer {
            color: var(--incorrect);
            font-weight: bold;
        }
        
        .teacher-section {
            margin-top: 30px;
            padding-top: 20px;
            border-top: 1px solid var(--secondary-blue);
        }
        
        .hidden {
            display: none;
        }
        
        .progress-bar {
            height: 10px;
            background-color: var(--light-blue);
            border-radius: 5px;
            margin: 20px 0;
            overflow: hidden;
        }
        
        .progress {
            height: 100%;
            background-color: var(--secondary-blue);
            width: 0%;
            transition: width 0.3s;
        }
        
        .question-number {
            text-align: center;
            margin-bottom: 10px;
            font-weight: bold;
        }
        
        @media (max-width: 600px) {
            .container {
                padding: 10px;
            }
            
            .page {
                padding: 15px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- الصفحة الأولى: صفحة البداية -->
        <div id="page1" class="page active">
            <h1>اختبار الكيمياء التفاعلي</h1>
            <img src="https://cdn.pixabay.com/photo/2016/11/21/16/21/chemistry-1845870_1280.jpg" alt="الكيمياء" style="width:100%; max-height:300px; object-fit:cover; border-radius:8px; margin:20px 0;">
            
            <div class="form-group">
                <label for="studentName">اسم الطالب:</label>
                <input type="text" id="studentName" placeholder="أدخل اسمك هنا">
            </div>
            
            <div class="form-group">
                <label for="section">الشعبة:</label>
                <select id="section">
                    <option value="">اختر الشعبة</option>
                    <option value="1">الشعبة 1</option>
                    <option value="2">الشعبة 2</option>
                    <option value="3">الشعبة 3</option>
                    <option value="4">الشعبة 4</option>
                    <option value="5">الشعبة 5</option>
                    <option value="6">الشعبة 6</option>
                    <option value="7">الشعبة 7</option>
                </select>
            </div>
            
            <button id="startTest">بدء الاختبار</button>
            
            <div class="teacher-section">
                <h3>دخول المعلم</h3>
                <div class="form-group">
                    <label for="teacherCode">الرمز السري:</label>
                    <input type="password" id="teacherCode" placeholder="أدخل الرمز السري">
                </div>
                <button id="teacherLogin">دخول المعلم</button>
            </div>
            
            <div class="developers">
                <h3>فريق العمل</h3>
                <p><strong>المسؤول عن فريق العمل:</strong> مهدي البطاط</p>
                <p><strong>المسؤول عن البرمجة وإنشاء قاعدة البيانات:</strong> مبارك الشهراني - صالح المحيبس</p>
                <p><strong>المسؤولون عن إنشاء الأسئلة ومراجعتها:</strong> سامي الشمري - عبدالله الدوسري - عماد الرشود</p>
            </div>
        </div>
        
        <!-- الصفحة الثانية: صفحة الأسئلة -->
        <div id="page2" class="page">
            <h2>اختبار الكيمياء</h2>
            <div class="progress-bar">
                <div class="progress" id="progressBar"></div>
            </div>
            <div class="question-number" id="questionNumber">السؤال 1 من 50</div>
            
            <div id="questionContainer"></div>
            
            <div id="feedback" class="feedback hidden"></div>
            
            <div id="countdown" class="countdown hidden"></div>
        </div>
        
        <!-- الصفحة الثالثة: صفحة النتائج -->
        <div id="page3" class="page">
            <h2>نتيجة الاختبار</h2>
            
            <div id="resultMessage" class="result-message"></div>
            
            <div id="scoreDisplay" style="text-align:center; margin:20px 0; font-size:24px; font-weight:bold;"></div>
            
            <h3>مراجعة الإجابات</h3>
            <div id="reviewContainer"></div>
            
            <button id="restartTest">إعادة الاختبار</button>
        </div>
    </div>

    <script>
        // بيانات الأسئلة
        const questions = [
            {
                question: "ما التعريف الأكثر دقة للكيمياء؟",
                options: [
                    "علم دراسة الطاقة والحركة",
                    "علم دراسة المادة والتغيرات التي تطرأ عليها",
                    "علم دراسة الكائنات الحية",
                    "علم دراسة الفضاء والكون"
                ],
                correct: 1
            },
            {
                question: "أي مما يلي يمثل مادة كيميائية؟",
                options: [
                    "الضوء",
                    "الحرارة",
                    "الماء النقي",
                    "الصوت"
                ],
                correct: 2
            },
            {
                question: "ما نوع الأشعة فوق البنفسجية الأكثر ارتباطاً بحروق الشمس؟",
                options: [
                    "UVA",
                    "UVB",
                    "UVC",
                    "UVD"
                ],
                correct: 1
            },
            {
                question: "من أضار الأشعة فوق البنفسجية:",
                options: [
                    "تقوية العظام",
                    "إنتاج فيتامين د",
                    "سرطان الجلد",
                    "تحسين النظر"
                ],
                correct: 2
            },
            {
                question: "كيف يتكون غاز الأوزون في الطبقات العليا من الغلاف الجوي؟",
                options: [
                    "من احتراق الوقود",
                    "من تفاعل الأكسجين مع الأشعة فوق البنفسجية",
                    "من تنفس الكائنات الحية",
                    "من تبخر الماء"
                ],
                correct: 1
            },
            {
                question: "ما الصيغة الكيميائية الصحيحة لغاز الأوزون؟",
                options: [
                    "O₂",
                    "O₃",
                    "O₄",
                    "CO₂"
                ],
                correct: 1
            },
            {
                question: "أين توجد طبقة الأوزون بشكل رئيسي؟",
                options: [
                    "التروبوسفير",
                    "الميزوسفير",
                    "الاستراتوسفير",
                    "الثيرموسفير"
                ],
                correct: 2
            },
            {
                question: "ما الجهاز المستخدم لقياس كمية الأوزون في الغلاف الجوي؟",
                options: [
                    "المطياف",
                    "الميزان الحساس",
                    "مقياس الضغط الجوي",
                    "مقياس الحرارة"
                ],
                correct: 0
            },
            {
                question: "ما السبب الرئيسي لتقلص طبقة الأوزون؟",
                options: [
                    "ثاني أكسيد الكربون",
                    "مركبات الكلوروفلوروكربون",
                    "بخار الماء",
                    "الأكسجين"
                ],
                correct: 1
            },
            {
                question: "لماذا استخدمت مركبات الكلوروفلوروكربون في المبردات؟",
                options: [
                    "لأنها قابلة للاشتعال",
                    "لأنها رخيصة الثمن",
                    "لأنها مستقرة وغير سامة",
                    "لأنها سريعة التحلل"
                ],
                correct: 2
            },
            {
                question: "ما الهدف من اجتماع مونتريال عام 1987؟",
                options: [
                    "منع استخدام البترول",
                    "حماية طبقة الأوزون",
                    "مكافحة الفقر",
                    "تنظيم التجارة العالمية"
                ],
                correct: 1
            },
            {
                question: "لماذا يتكون ثقب الأوزون فوق القارة القطبية الجنوبية بشكل أكبر؟",
                options: [
                    "لأنها الأكثر تلوثاً",
                    "بسبب الظروف الجوية الخاصة والسحب الاستراتوسفيرية",
                    "لقربها من الشمس",
                    "لوجود الكثير من المصانع هناك"
                ],
                correct: 1
            },
            {
                question: "ما العامل الرئيسي الذي يساعد على تكون الأوزون فوق خط الاستواء؟",
                options: [
                    "برودة الجو",
                    "شدة الأشعة الشمسية",
                    "قلة الرياح",
                    "ارتفاع الضغط الجوي"
                ],
                correct: 1
            },
            {
                question: "أي الأجهزة التالية يستخدم لقياس ثقب الأوزون؟",
                options: [
                    "مقياس الزلازل",
                    "القمر الصناعي",
                    "الميكروسكوب",
                    "مقياس التيار الكهربائي"
                ],
                correct: 1
            },
            {
                question: "لماذا توجد عدة فروع لعلم الكيمياء؟",
                options: [
                    "لأن المواد الكيميائية مختلفة الألوان",
                    "لاتساع مجال علم الكيمياء وتنوع المواد والتفاعلات",
                    "لأن العلماء يحبون التنوع",
                    "لأن الكيمياء علم حديث"
                ],
                correct: 1
            },
            {
                question: "ما الفرق بين الكتلة والوزن؟",
                options: [
                    "الكتلة تعتمد على الجاذبية والوزن ثابت",
                    "الكتلة ثابتة والوزن يعتمد على الجاذبية",
                    "لا فرق بينهما",
                    "الكتلة تقاس بالنيوتن والوزن بالجرام"
                ],
                correct: 1
            },
            {
                question: "لماذا يهتم الكيميائي بالوصف تحت المجهري للمادة؟",
                options: [
                    "لأنه أكثر دقة ويمكن من فهم السلوك الكيميائي",
                    "لأنه أجمل شكلاً",
                    "لأنه أسرع طريقة",
                    "لأنه أرخص تكلفة"
                ],
                correct: 0
            },
            {
                question: "أي فرع من فروع الكيمياء يدرس المركبات التي تحتوي على الكربون؟",
                options: [
                    "الكيمياء العضوية",
                    "الكيمياء غير العضوية",
                    "الكيمياء التحليلية",
                    "الكيمياء الفيزيائية"
                ],
                correct: 0
            },
            {
                question: "ما تعريف الطريقة العلمية؟",
                options: [
                    "طريقة عشوائية للحصول على نتائج",
                    "مجموعة من الخطوات المنظمة لحل المشكلات",
                    "طريقة لكتابة التقارير",
                    "أسلوب للرسم والتخطيط"
                ],
                correct: 1
            },
            {
                question: "ما الفرق بين البيانات النوعية والكمية؟",
                options: [
                    "النوعية رقمية والكمية وصفية",
                    "النوعية وصفية والكمية رقمية",
                    "لا فرق بينهما",
                    "النوعية أدق من الكمية"
                ],
                correct: 1
            },
            {
                question: "ما الفرق بين الفرضية والنظرية؟",
                options: [
                    "الفرضية مثبتة experimentally والنظرية تخمينية",
                    "الفرضية تفسير مقترح والنظرية مثبتة experimentally",
                    "لا فرق بينهما",
                    "الفرضية أوسع من النظرية"
                ],
                correct: 1
            },
            {
                question: "أي مما يلي يمثل القانون العلمي؟",
                options: [
                    "تفسير للظواهر الطبيعية",
                    "وصف للظواهر الطبيعية دون تفسير",
                    "تخمين علمي",
                    "رأي شخصي"
                ],
                correct: 1
            },
            {
                question: "ما نوع المتغير الذي يتم قياسه في التجربة؟",
                options: [
                    "المتغير المستقل",
                    "المتغير التابع",
                    "المتغير الثابت",
                    "المتغير العشوائي"
                ],
                correct: 1
            },
            {
                question: "ما الهدف من تحليل النتائج في التجربة العلمية؟",
                options: [
                    "إنهاء التجربة بسرعة",
                    "الحصول على استنتاجات ودلالات",
                    "تكرار التجربة فقط",
                    "كتابة التقرير"
                ],
                correct: 1
            },
            {
                question: "ما الفرق بين البحث النظري والبحث التطبيقي؟",
                options: [
                    "النظري يهدف للتطبيق المباشر والتطبيقي للمعرفة فقط",
                    "النظري للمعرفة فقط والتطبيقي للتطبيق العملي",
                    "لا فرق بينهما",
                    "النظري أسهل من التطبيقي"
                ],
                correct: 1
            },
            {
                question: "عند العمل في المختبر، ما الإجراء الآمن للتعامل مع المواد الكيميائية؟",
                options: [
                    "تجربة المواد باللمس",
                    "ارتداء المعدات الوقائية",
                    "العمل بسرعة",
                    "تناول الطعام في المختبر"
                ],
                correct: 1
            },
            {
                question: "من فوائد علم الكيمياء:",
                options: [
                    "تلوث البيئة",
                    "إنتاج الأدوية والمواد الجديدة",
                    "استنزاف الموارد",
                    "زيادة الأمراض"
                ],
                correct: 1
            },
            {
                question: "ما المقصود بالاكتشافات غير المقصودة؟",
                options: [
                    "الاكتشافات التي تم التخطيط لها مسبقاً",
                    "الاكتشافات التي حدثت بالصدفة",
                    "الاكتشافات التي لم تكن مفيدة",
                    "الاكتشافات القديمة فقط"
                ],
                correct: 1
            },
            {
                question: "أي مما يلي يمثل اكتشافاً غير مقصود في الكيمياء؟",
                options: [
                    "جدول مندلييف الدوري",
                    "البنسلين",
                    "نظرية دالتون",
                    "قوانين الغازات"
                ],
                correct: 1
            },
            {
                question: "أي من المركبات التالية كان مسؤولاً عن تآكل طبقة الأوزون؟",
                options: [
                    "CO₂",
                    "CFCs",
                    "H₂O",
                    "O₂"
                ],
                correct: 1
            },
            {
                question: "ما الدور الرئيسي لطبقة الأوزون؟",
                options: [
                    "تنظيم درجة حرارة الأرض",
                    "امتصاص الأشعة فوق البنفسجية",
                    "تنقية الهواء من الملوثات",
                    "تكوين السحب"
                ],
                correct: 1
            },
            {
                question: "أي من العناصر التالية هو الأكثر فعالية في تدمير الأوزون؟",
                options: [
                    "الأكسجين",
                    "الكلور",
                    "الهيدروجين",
                    "النيتروجين"
                ],
                correct: 1
            },
            {
                question: "ما اسم الطبقة التي نعيش فيها من الغلاف الجوي؟",
                options: [
                    "الاستراتوسفير",
                    "التروبوسفير",
                    "الميزوسفير",
                    "الثيرموسفير"
                ],
                correct: 1
            },
            {
                question: "أي من الوحدات التالية تستخدم لقياس كمية الأوزون؟",
                options: [
                    "متر",
                    "دوبسون",
                    "كيلوجرام",
                    "نيوتن"
                ],
                correct: 1
            },
            {
                question: "ما الخاصية التي جعلت مركبات الكلوروفلوروكربون خطيرة على البيئة؟",
                options: [
                    "لونها",
                    "استقرارها وطول عمرها في الغلاف الجوي",
                    "رائحتها",
                    "كثافتها"
                ],
                correct: 1
            },
            {
                question: "أي من الدول التالية كانت الأكثر تأثراً بثقب الأوزون؟",
                options: [
                    "السعودية",
                    "أستراليا",
                    "مصر",
                    "البرازيل"
                ],
                correct: 1
            },
            {
                question: "ما المادة التي تطلق الكلور من مركبات الكلوروفلوروكربون في الغلاف الجوي؟",
                options: [
                    "الأكسجين",
                    "الأشعة فوق البنفسجية",
                    "النيتروجين",
                    "ثاني أكسيد الكربون"
                ],
                correct: 1
            },
            {
                question: "أي من الفروع الكيميائية يهتم بدراسة معدل التفاعلات الكيميائية؟",
                options: [
                    "الكيمياء العضوية",
                    "الكيمياء الفيزيائية",
                    "الكيمياء التحليلية",
                    "الكيمياء غير العضوية"
                ],
                correct: 1
            },
            {
                question: "ما الأداة المستخدمة لرؤية الجزيئات الصغيرة؟",
                options: [
                    "التلسكوب",
                    "المجهر الإلكتروني",
                    "الميزان",
                    "المكثف"
                ],
                correct: 1
            },
            {
                question: "أي من الخطوات التالية ليست من خطوات الطريقة العلمية؟",
                options: [
                    "الملاحظة",
                    "التخمين العشوائي",
                    "وضع الفرضية",
                    "التحقق experimentally"
                ],
                correct: 1
            },
            {
                question: "ما نوع البيانات الذي يمثل وصفاً للون ورائحة المادة؟",
                options: [
                    "البيانات الكمية",
                    "البيانات النوعية",
                    "البيانات الرقمية",
                    "البيانات الإحصائية"
                ],
                correct: 1
            },
            {
                question: "أي مما يلي يمثل النظرية العلمية؟",
                options: [
                    "قانون الجذب العام",
                    "النظرية النسبية",
                    "سرعة الضوء",
                    "كثافة الماء"
                ],
                correct: 1
            },
            {
                question: "ما المتغير الذي يتحكم فيه الباحث في التجربة؟",
                options: [
                    "المتغير التابع",
                    "المتغير المستقل",
                    "المتغير الثابت",
                    "المتغير العشوائي"
                ],
                correct: 1
            },
            {
                question: "ما الهدف من البحث التطبيقي؟",
                options: [
                    "المعرفة فقط",
                    "حل مشكلات عملية",
                    "نشر الأبحاث",
                    "الترفيه"
                ],
                correct: 1
            },
            {
                question: "أي من الإجراءات التالية يعتبر غير آمن في المختبر؟",
                options: [
                    "ارتداء النظارات الواقية",
                    "شم المواد الكيميائية مباشرة",
                    "قراءة التعليمات",
                    "غسل اليدين بعد التجارب"
                ],
                correct: 1
            },
            {
                question: "كيف ساهمت الكيمياء في مجال الطب؟",
                options: [
                    "بتطوير الأسلحة",
                    "باكتشاف الأدوية",
                    "ببناء الجسور",
                    "بتصميم الملابس"
                ],
                correct: 1
            },
            {
                question: "أي من الاكتشافات التالية كان مقصوداً؟",
                options: [
                    "البنسلين",
                    "الجدول الدوري",
                    "الفياغرا",
                    "الأشعة السينية"
                ],
                correct: 1
            },
            {
                question: "ما المادة التي حلت محل مركبات الكلوروفلوروكربون في الثلاجات؟",
                options: [
                    "الماء",
                    "مركبات الهيدروكلوروفلوروكربون",
                    "الزئبق",
                    "الرصاص"
                ],
                correct: 1
            },
            {
                question: "أي من الغازات التالية يساهم في الاحتباس الحراري؟",
                options: [
                    "الأوزون",
                    "ثاني أكسيد الكربون",
                    "الأكسجين",
                    "النيتروجين"
                ],
                correct: 1
            },
            {
                question: "ما الجهاز الذي يقيس شدة الأشعة فوق البنفسجية؟",
                options: [
                    "مقياس الحرارة",
                    "مقياس الأشعة فوق البنفسجية",
                    "البارومتر",
                    "الهيجرومتر"
                ],
                correct: 1
            }
        ];

        // المتغيرات العامة
        let currentQuestion = 0;
        let userAnswers = new Array(questions.length).fill(null);
        let score = 0;
        let timer;
        let countdownValue = 2;

        // عناصر DOM
        const page1 = document.getElementById('page1');
        const page2 = document.getElementById('page2');
        const page3 = document.getElementById('page3');
        const startTestBtn = document.getElementById('startTest');
        const teacherLoginBtn = document.getElementById('teacherLogin');
        const restartTestBtn = document.getElementById('restartTest');
        const questionContainer = document.getElementById('questionContainer');
        const feedback = document.getElementById('feedback');
        const countdownDisplay = document.getElementById('countdown');
        const progressBar = document.getElementById('progressBar');
        const questionNumber = document.getElementById('questionNumber');
        const resultMessage = document.getElementById('resultMessage');
        const scoreDisplay = document.getElementById('scoreDisplay');
        const reviewContainer = document.getElementById('reviewContainer');

        // بدء الاختبار
        startTestBtn.addEventListener('click', function() {
            const studentName = document.getElementById('studentName').value;
            const section = document.getElementById('section').value;
            
            if (!studentName || !section) {
                alert('يرجى إدخال الاسم واختيار الشعبة');
                return;
            }
            
            // حفظ بيانات الطالب
            localStorage.setItem('studentName', studentName);
            localStorage.setItem('section', section);
            
            // الانتقال إلى صفحة الأسئلة
            showPage(2);
            displayQuestion();
        });

        // دخول المعلم
        teacherLoginBtn.addEventListener('click', function() {
            const teacherCode = document.getElementById('teacherCode').value;
            
            if (teacherCode === '13324') {
                alert('تم الدخول بنجاح كمعلم');
                // هنا يمكن إضافة وظيفة عرض نتائج الطلاب
            } else {
                alert('الرمز السري غير صحيح');
            }
        });

        // إعادة الاختبار
        restartTestBtn.addEventListener('click', function() {
            currentQuestion = 0;
            userAnswers = new Array(questions.length).fill(null);
            score = 0;
            showPage(1);
        });

        // عرض السؤال الحالي
        function displayQuestion() {
            const question = questions[currentQuestion];
            
            // تحديث شريط التقدم
            progressBar.style.width = ${((currentQuestion + 1) / questions.length) * 100}%;
            questionNumber.textContent = السؤال ${currentQuestion + 1} من ${questions.length};
            
            // بناء واجهة السؤال
            let questionHTML = `
                <div class="question-container">
                    <h3>${question.question}</h3>
                    <div class="options">
            `;
            
            question.options.forEach((option, index) => {
                const isSelected = userAnswers[currentQuestion] === index;
                questionHTML += `
                    <div class="option ${isSelected ? 'selected' : ''}" data-index="${index}">
                        ${String.fromCharCode(65 + index)}) ${option}
                    </div>
                `;
            });
            
            questionHTML += `
                    </div>
                </div>
            `;
            
            questionContainer.innerHTML = questionHTML;
            
            // إضافة مستمعي الأحداث للخيارات
            const options = document.querySelectorAll('.option');
            options.forEach(option => {
                option.addEventListener('click', function() {
                    if (userAnswers[currentQuestion] !== null) return; // منع تغيير الإجابة بعد الاختيار
                    
                    const selectedIndex = parseInt(this.getAttribute('data-index'));
                    userAnswers[currentQuestion] = selectedIndex;
                    
                    // إزالة التحديد من جميع الخيارات
                    options.forEach(opt => opt.classList.remove('selected'));
                    
                    // تحديد الخيار المختار
                    this.classList.add('selected');
                    
                    // التحقق من الإجابة
                    checkAnswer(selectedIndex);
                });
            });
        }

        // التحقق من الإجابة
        function checkAnswer(selectedIndex) {
            const question = questions[currentQuestion];
            const isCorrect = selectedIndex === question.correct;
            
            if (isCorrect) {
                score++;
                showFeedback('ممتاز! الإجابة صحيحة', 'success');
            } else {
                showFeedback('خطأ! يمكنك المحاولة لاحقاً', 'error');
            }
            
            // بدء العد التنازلي
            startCountdown();
        }

        // عرض رسالة التغذية الراجعة
        function showFeedback(message, type) {
            feedback.textContent = message;
            feedback.className = feedback ${type};
            feedback.classList.remove('hidden');
        }

        // بدء العد التنازلي
        function startCountdown() {
            countdownValue = 2;
            countdownDisplay.textContent = countdownValue;
            countdownDisplay.classList.remove('hidden');
            
            timer = setInterval(() => {
                countdownValue--;
                countdownDisplay.textContent = countdownValue;
                
                if (countdownValue <= 0) {
                    clearInterval(timer);
                    countdownDisplay.classList.add('hidden');
                    feedback.classList.add('hidden');
                    
                    // الانتقال إلى السؤال التالي
                    currentQuestion++;
                    
                    if (currentQuestion < questions.length) {
                        displayQuestion();
                    } else {
                        showResults();
                    }
                }
            }, 1000);
        }

        // عرض النتائج
        function showResults() {
            const percentage = (score / questions.length) * 100;
            
            // تحديد الرسالة بناءً على النسبة
            if (percentage >= 80) {
                resultMessage.textContent = 'ممتاز بارك الله فيك';
                resultMessage.className = 'result-message excellent';
            } else if (percentage >= 60) {
                resultMessage.textContent = 'حاول مجددا كنت قريبا';
                resultMessage.className = 'result-message good';
            } else {
                resultMessage.textContent = 'ذاكر وراجع مجددا';
                resultMessage.className = 'result-message poor';
            }
            
            // عرض النتيجة
            scoreDisplay.textContent = النتيجة: ${score}/${questions.length} (${percentage.toFixed(1)}%);
            
            // عرض مراجعة الإجابات
            let reviewHTML = '';
            questions.forEach((question, index) => {
                const userAnswer = userAnswers[index];
                const isCorrect = userAnswer === question.correct;
                
                reviewHTML += `
                    <div class="review-item">
                        <p><strong>السؤال ${index + 1}:</strong> ${question.question}</p>
                        <p class="correct-answer">الإجابة الصحيحة: ${String.fromCharCode(65 + question.correct)}) ${question.options[question.correct]}</p>
                        ${!isCorrect ? <p class="wrong-answer">إجابتك: ${userAnswer !== null ? String.fromCharCode(65 + userAnswer) + ') ' + question.options[userAnswer] : 'لم تجب'}</p> : ''}
                    </div>
                `;
            });
            
            reviewContainer.innerHTML = reviewHTML;
            
            // الانتقال إلى صفحة النتائج
            showPage(3);
        }

        // تغيير الصفحة المعروضة
        function showPage(pageNumber) {
            page1.classList.remove('active');
            page2.classList.remove('active');
            page3.classList.remove('active');
            
            if (pageNumber === 1) {
                page1.classList.add('active');
            } else if (pageNumber === 2) {
                page2.classList.add('active');
            } else if (pageNumber === 3) {
                page3.classList.add('active');
            }
        }
    </script>
</body>
</html>
