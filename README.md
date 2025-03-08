<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>أفضل 20 موقعًا لتحويل النص إلى كود برمجة</title>
    <meta name="description" content="اكتشف 20 موقعًا لتحويل النص إلى كود برمجة بمختلف اللغات. أدوات فعالة لتطوير الويب والبرمجة.">
    <meta name="keywords" content="تحويل النص إلى كود, أفضل مواقع برمجة, أدوات تطوير الويب, تحويل النص إلى كود برمجي">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@300;400;500;700&display=swap" rel="stylesheet">
    <!-- بيانات منظمة (Schema Markup) -->
    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "WebSite",
      "name": "أفضل 20 موقعًا لتحويل النص إلى كود برمجة",
      "url": "https://yourwebsite.com",
      "description": "اكتشف 20 موقعًا لتحويل النص إلى كود برمجة بمختلف اللغات. أدوات فعالة لتطوير الويب والبرمجة."
    }
    </script>
    <style>
        /* التصميم العام */
        body {
            font-family: 'Tajawal', sans-serif;
            background: linear-gradient(135deg, #6a11cb, #2575fc);
            margin: 0;
            padding: 20px;
            color: #333;
        }

        .container {
            max-width: 1200px;
            margin: 20px auto;
            background: rgba(255, 255, 255, 0.9);
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            backdrop-filter: blur(10px);
        }

        h1 {
            text-align: center;
            color: #2575fc;
            font-size: 2.5rem;
            margin-bottom: 30px;
        }

        /* شريط البحث */
        .search-bar {
            margin-bottom: 30px;
            text-align: center;
        }

        .search-bar input {
            width: 100%;
            max-width: 500px;
            padding: 10px 20px;
            border: 1px solid rgba(0, 0, 0, 0.1);
            border-radius: 25px;
            font-size: 1rem;
            background: rgba(255, 255, 255, 0.8);
            transition: border-color 0.3s ease, box-shadow 0.3s ease;
        }

        .search-bar input:focus {
            border-color: #2575fc;
            box-shadow: 0 0 10px rgba(37, 117, 252, 0.3);
            outline: none;
        }

        /* بطاقات المواقع */
        .card-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            margin-bottom: 40px;
        }

        .card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        }

        .card h3 {
            margin: 0 0 10px;
            color: #2575fc;
        }

        .card p {
            margin: 0 0 15px;
            color: #666;
        }

        .card a {
            display: inline-block;
            padding: 10px 20px;
            background: #2575fc;
            color: white;
            border-radius: 5px;
            text-decoration: none;
            transition: background 0.3s ease;
        }

        .card a:hover {
            background: #1a5bbf;
        }

        /* قسم التعليقات */
        .comments-section {
            margin-top: 50px;
            padding: 20px;
            background: white;
            border-radius: 10px;
        }

        .comment-form {
            margin-bottom: 30px;
        }

        .comment-form input, 
        .comment-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
        }

        .comment-form button {
            padding: 10px 20px;
            background: #2575fc;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s ease;
        }

        .comment-form button:hover {
            background: #1a5bbf;
        }

        .comment-list {
            max-height: 400px;
            overflow-y: auto;
        }

        .comment {
            background: #f8f9fa;
            padding: 15px;
            border-radius: 5px;
            margin-bottom: 15px;
            animation: fadeIn 0.5s ease;
        }

        .comment strong {
            color: #2575fc;
        }

        .comment small {
            display: block;
            margin-top: 5px;
            color: #888;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>أفضل 20 موقعًا لتحويل النص إلى كود برمجة 🚀</h1>

        <!-- شريط البحث -->
        <div class="search-bar">
            <input type="text" id="searchInput" placeholder="ابحث عن موقع...">
        </div>

        <!-- قائمة المواقع (20 موقعًا) -->
        <div class="card-container" id="cardContainer">
            <!-- الموقع 1 -->
            <div class="card" data-category="web">
                <h3>CodePen</h3>
                <p>أشهر منصة لتجربة أكواد الويب مباشرة.</p>
                <a href="https://codepen.io" target="_blank">زيارة الموقع</a>
            </div>

            <!-- الموقع 2 -->
            <div class="card" data-category="web">
                <h3>JSFiddle</h3>
                <p>منصة لتجربة أكواد JavaScript وHTML وCSS.</p>
                <a href="https://jsfiddle.net" target="_blank">زيارة الموقع</a>
            </div>

            <!-- الموقع 3 -->
            <div class="card" data-category="python">
                <h3>Replit</h3>
                <p>يدعم العديد من لغات البرمجة والتعاون في الوقت الفعلي.</p>
                <a href="https://replit.com" target="_blank">زيارة الموقع</a>
            </div>

            <!-- الموقع 4 -->
            <div class="card" data-category="web">
                <h3>CodeSandbox</h3>
                <p>مثالي لتطوير تطبيقات الويب باستخدام React وVue.</p>
                <a href="https://codesandbox.io" target="_blank">زيارة الموقع</a>
            </div>

            <!-- الموقع 5 -->
            <div class="card" data-category="web">
                <h3>Glitch</h3>
                <p>يتيح إنشاء تطبيقات ويب وتعديلها مباشرة في المتصفح.</p>
                <a href="https://glitch.com" target="_blank">زيارة الموقع</a>
            </div>

            <!-- الموقع 6 -->
            <div class="card" data-category="javascript">
                <h3>StackBlitz</h3>
                <p>يدعم تطوير تطبيقات Angular وReact وVue بسرعة.</p>
                <a href="https://stackblitz.com" target="_blank">زيارة الموقع</a>
            </div>

            <!-- الموقع 7 -->
            <div class="card" data-category="python">
                <h3>Python Tutor</h3>
                <p>تصور تنفيذ كود البايثون خطوة بخطوة.</p>
                <a href="https://pythontutor.com" target="_blank">زيارة الموقع</a>
            </div>

            <!-- الموقع 8 -->
            <div class="card" data-category="dart">
                <h3>DartPad</h3>
                <p>منصة لتجربة أكواد لغة Dart.</p>
                <a href="https://dartpad.dev" target="_blank">زيارة الموقع</a>
            </div>

            <!-- الموقع 9 -->
            <div class="card" data-category="sql">
                <h3>SQL Fiddle</h3>
                <p>منصة لتجربة أكواد SQL مباشرة.</p>
                <a href="http://sqlfiddle.com" target="_blank">زيارة الموقع</a>
            </div>

            <!-- الموقع 10 -->
            <div class="card" data-category="programming">
                <h3>LeetCode Playground</h3>
                <p>منصة لحل مشاكل البرمجة وتجربة الأكواد.</p>
                <a href="https://leetcode.com/playground" target="_blank">زيارة الموقع</a>
            </div>

            <!-- الموقع 11 -->
            <div class="card" data-category="web">
                <h3>JS Bin</h3>
                <p>منصة لتجربة أكواد JavaScript وHTML وCSS.</p>
                <a href="https://jsbin.com" target="_blank">زيارة الموقع</a>
            </div>

            <!-- الموقع 12 -->
            <div class="card" data-category="web">
                <h3>Codeanywhere</h3>
                <p>بيئة تطوير متكاملة في المتصفح.</p>
                <a href="https://codeanywhere.com" target="_blank">زيارة الموقع</a>
            </div>

            <!-- الموقع 13 -->
            <div class="card" data-category="programming">
                <h3>Ideone</h3>
                <p>منصة لتجربة أكواد بأكثر من 60 لغة برمجة.</p>
                <a href="https://ideone.com" target="_blank">زيارة الموقع</a>
            </div>

            <!-- الموقع 14 -->
            <div class="card" data-category="programming">
                <h3>JDoodle</h3>
                <p>يدعم أكثر من 70 لغة برمجة.</p>
                <a href="https://www.jdoodle.com" target="_blank">زيارة الموقع</a>
            </div>

            <!-- الموقع 15 -->
            <div class="card" data-category="programming">
                <h3>Programiz</h3>
                <p>منصة لتعليم البرمجة وتجربة الأكواد.</p>
                <a href="https://www.programiz.com" target="_blank">زيارة الموقع</a>
            </div>

            <!-- الموقع 16 -->
            <div class="card" data-category="programming">
                <h3>OneCompiler</h3>
                <p>يدعم أكثر من 50 لغة برمجة.</p>
                <a href="https://onecompiler.com" target="_blank">زيارة الموقع</a>
            </div>

            <!-- الموقع 17 -->
            <div class="card" data-category="programming">
                <h3>Paiza.IO</h3>
                <p>منصة لتجربة أكواد بأكثر من 20 لغة برمجة.</p>
                <a href="https://paiza.io" target="_blank">زيارة الموقع</a>
            </div>

            <!-- الموقع 18 -->
            <div class="card" data-category="web">
                <h3>W3Schools Tryit</h3>
                <p>منصة لتجربة أكواد HTML وCSS وJavaScript.</p>
                <a href="https://www.w3schools.com/tryit" target="_blank">زيارة الموقع</a>
            </div>

            <!-- الموقع 19 -->
            <div class="card" data-category="java">
                <h3>Codiva</h3>
                <p>منصة لتجربة أكواد Java وC++.</p>
                <a href="https://www.codiva.io" target="_blank">زيارة الموقع</a>
            </div>

            <!-- الموقع 20 -->
            <div class="card" data-category="programming">
                <h3>Runnable</h3>
                <p>منصة لتجربة أكواد بأكثر من 10 لغات برمجة.</p>
                <a href="https://runnable.io" target="_blank">زيارة الموقع</a>
            </div>
        </div>

        <!-- قسم التعليقات -->
        <div class="comments-section">
            <h2>آراء المستخدمين 💬</h2>
            
            <form class="comment-form" id="commentForm">
                <input type="text" placeholder="اسمك" required>
                <textarea placeholder="تعليقك..." rows="4" required></textarea>
                <button type="submit">إرسال التعليق</button>
            </form>

            <div class="comment-list" id="commentList">
                <!-- التعليقات تظهر هنا -->
            </div>
        </div>
    </div>

    <script>
        // وظيفة البحث
        const searchInput = document.getElementById('searchInput');
        const cards = document.querySelectorAll('.card');

        searchInput.addEventListener('input', () => {
            const searchTerm = searchInput.value.toLowerCase();
            cards.forEach(card => {
                const title = card.querySelector('h3').textContent.toLowerCase();
                const description = card.querySelector('p').textContent.toLowerCase();
                if (title.includes(searchTerm) || description.includes(searchTerm)) {
                    card.style.display = 'block';
                } else {
                    card.style.display = 'none';
                }
            });
        });

        // إدارة التعليقات
        const commentForm = document.getElementById('commentForm');
        const commentList = document.getElementById('commentList');

        commentForm.addEventListener('submit', (e) => {
            e.preventDefault();
            
            const name = e.target[0].value;
            const text = e.target[1].value;
            
            const comment = document.createElement('div');
            comment.className = 'comment';
            comment.innerHTML = `
                <strong>${name}</strong>
                <p>${text}</p>
                <small>${new Date().toLocaleString()}</small>
            `;
            
            commentList.prepend(comment);
            e.target.reset();
        });
    </script>
</body>
</html>
