<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>hair website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f0e6; /* بيج فاتح */
            margin: 0;
            padding: 0;
            color: #333;
        }

        header {
            background-color: #6aa84f; /* أخضر */
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #e6dfd0; /* بيج أغمق شوي */
            display: flex;
            justify-content: center;
            padding: 10px;
        }

        nav a {
            color: #6aa84f;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .container {
            max-width: 1000px;
            margin: 20px auto;
            padding: 0 20px;
        }

        .section-title {
            text-align: center;
            color: #6aa84f;
            margin-bottom: 20px;
        }

        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .product {
            background-color: #fff;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            text-align: center;
        }

        .//product img {
            //width: 100%;
           // height: 200px;
           // object-fit: cover;
           // border-radius: 10px;
        }

        .product h3 {
            margin: 10px 0 5px 0;
            color: #333;
        }

        .product p {
            color: #666;
            font-size: 14px;
        }

        footer {
            background-color: #6aa84f;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>موقع الشعر الجميل</h1>
    </header>

    <nav>
        <a href="#products">our product</a>
        <a href="#about">about</a>
        <a href="#contact">contact us</a>
    </nav>

    <div class="container" id="products">
        <h2 class="section-title">منتجاتنا</h2>
        <div class="products">
            <div class="product">
                //<img src=" " //alt="شامبو طبيعي">
                <h3>شامبو طبيعي</h3>
                <p>يحافظ على صحة شعرك ويغذي فروة الرأس</p>
            </div>
            <div class="product">
               // <img src=" " //alt="بلسم مغذي">
                <h3>بلسم مغذي</h3>
                <p>ينعم الشعر ويجعله سهل التسريح</p>
            </div>
            <div class="product">
               // <img src=" " //alt="زيت شعر">
                <h3>زيت شعر طبيعي</h3>
                <p>يقوي الشعر ويعطيه لمعان صحي</p>
            </div>
        </div>
    </div>

    <div class="container" id="about">
        <h2 class="section-title">عن الموقع</h2>
        <p>هذا الموقع مخصص لتقديم أفضل منتجات العناية بالشعر باستخدام مكونات طبيعية. هدفنا هو مساعدتك في الحصول على شعر صحي ولامع بطريقة طبيعية وآمنة.</p>
    </div>

    <div class="container" id="contact">
        <h2 class="section-title">تواصل معنا</h2>
        <p>يمكنك التواصل معنا عبر البريد الإلكتروني: <a href="mailto:info@hairwebsite.com">info@hairwebsite.com</a></p>
    </div>

    <footer>
        جميع الحقوق محفوظة © 2025
    </footer>
</body>
</html>
