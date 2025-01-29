<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Office 365 Technical Support Services</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-image: url('/background.jpg'); /* 添加背景图片 */
            background-size: cover; /* 使背景图片覆盖整个页面 */
            background-repeat: no-repeat; /* 防止背景图片重复 */
            background-attachment: fixed; /* 使背景图片固定 */
            color: #000; /* Set default font color to black */
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #add8e6; /* Light blue background */
            color: #000; /* Set header font color to black */
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #77aaff 3px solid;
        }
        header a {
            color: #000; /* Set link color to black */
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            float: right;
            display: inline;
            padding: 0 20px 0 20px;
        }
        .showcase {
            min-height: 400px;
            background-color: #add8e6; /* Light blue background */
            text-align: center;
            color: #000; /* Set showcase font color to black */
        }
        .showcase h1 {
            margin-top: 100px;
            font-size: 55px;
            margin-bottom: 10px;
        }
        .showcase p {
            font-size: 20px;
        }
        .services {
            padding: 20px;
            background: #add8e6; /* Light blue background */
            text-align: center;
            color: #000; /* Set services font color to black */
        }
        .services h2 {
            margin-bottom: 20px;
        }
        .services p {
            font-size: 18px;
        }
        footer {
            padding: 20px;
            margin-top: 20px;
            color: #fff; /* Set footer font color to white */
            background-color: #333;
            text-align: center;
        }
        .language-switch {
            margin-top: 20px;
        }
        .language-switch a {
            color: #fff; /* Set language switch link color to white */
            margin-left: 10px;
            cursor: pointer;
        }
    </style>
    <script>
        function switchLanguage(lang) {
            var elements = document.querySelectorAll('[data-lang]');
            elements.forEach(function(element) {
                if (element.dataset.lang === lang) {
                    element.style.display = 'block';
                } else {
                    element.style.display = 'none';
                }
            });
        }
        document.addEventListener('DOMContentLoaded', function() {
            switchLanguage('en'); // Set default language to English
        });
    </script>
</head>
<body>
    <header>
        <div class="container">
            <h1 data-lang="en">Office 365 Technical Support Services</h1>
            <h1 data-lang="zh" style="display:none;">Office 365 技术支持服务</h1>
            <ul>
                <li><a href="#contact" data-lang="en">Contact Us</a><a href="#contact" data-lang="zh" style="display:none;">联系我们</a></li>
                <li><a href="#services" data-lang="en">Services</a><a href="#services" data-lang="zh" style="display:none;">服务内容</a></li>
                <li><a href="#home" data-lang="en">Home</a><a href="#home" data-lang="zh" style="display:none;">首页</a></li>
            </ul>
        </div>
    </header>
    <section class="showcase" id="home">
        <div class="container">
            <h1 data-lang="en">Professional Office 365 Technical Support</h1>
            <h1 data-lang="zh" style="display:none;">专业的Office 365 技术支持</h1>
            <p data-lang="en">We provide technical support for Exchange Online, SharePoint, OneDrive, and Teams.</p>
            <p data-lang="zh" style="display:none;">我们提供Exchange Online邮件、SharePoint、OneDrive和Teams的技术支持服务。</p>
        </div>
    </section>
    <section class="services" id="services">
        <div class="container">
            <h2 data-lang="en">Our Services</h2>
            <h2 data-lang="zh" style="display:none;">我们的服务</h2>
            <p data-lang="en">We offer technical support for the following Office 365 services:</p>
            <p data-lang="zh" style="display:none;">我们提供以下Office 365服务的技术支持：</p>
            <ul>
                <li data-lang="en">Exchange Online Email</li>
                <li data-lang="zh" style="display:none;">Exchange Online 邮件</li>
                <li>SharePoint</li>
                <li>OneDrive</li>
                <li>Teams</li>
            </ul>
            <p data-lang="en">Rate: $100 per hour</p>
            <p data-lang="zh" style="display:none;">收费标准：100美金每小时</p>
            <p data-lang="en">We provide remote assistance only, no on-site service.</p>
            <p data-lang="zh" style="display:none;">我们提供远程协助，不提供上门服务。</p>
        </div>
    </section>
    <footer id="contact">
        <p data-lang="en">Contact Us: support@songben.fun</p>
        <p data-lang="zh" style="display:none;">联系我们：support@songben.fun</p>
        <div class="language-switch">
            <a onclick="switchLanguage('en')">English</a> | 
            <a onclick="switchLanguage('zh')">中文</a> | 
            <a onclick="switchLanguage('es')">Español</a> | 
            <a onclick="switchLanguage('fr')">Français</a> | 
            <a onclick="switchLanguage('de')">Deutsch</a> | 
            <a onclick="switchLanguage('ja')">日本語</a> | 
            <a onclick="switchLanguage('ko')">한국어</a> | 
            <a onclick="switchLanguage('ru')">Русский</a> | 
            <a onclick="switchLanguage('pt')">Português</a> | 
            <a onclick="switchLanguage('it')">Italiano</a> | 
            <a onclick="switchLanguage('ar')">العربية</a>
        </div>
    </footer>
</body>
</html>
