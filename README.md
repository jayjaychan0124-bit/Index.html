<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>補天SRC - 漏洞報告演示</title>
    <style>
        body { 
            font-family: "Microsoft YaHei", system-ui, sans-serif; 
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); 
            margin: 0; 
            padding: 20px; 
            color: #333; 
            line-height: 1.6;
        }
        .container { 
            max-width: 800px; 
            margin: 30px auto; 
            background: white; 
            border-radius: 16px; 
            box-shadow: 0 15px 35px rgba(0,0,0,0.2); 
            overflow: hidden;
        }
        header { 
            background: #2c3e50; 
            color: white; 
            padding: 35px; 
            text-align: center; 
        }
        h1 { 
            margin: 0; 
            font-size: 32px; 
        }
        .subtitle { 
            color: #bdc3c7; 
            margin-top: 10px; 
            font-size: 18px;
        }
        .content { 
            padding: 40px; 
        }
        .warning { 
            background: #fff3cd; 
            border-left: 6px solid #f39c12; 
            padding: 18px; 
            margin: 25px 0; 
            border-radius: 6px;
            font-size: 15px;
        }
        .fake-link { 
            color: #0066cc; 
            text-decoration: underline; 
            cursor: pointer; 
            font-weight: bold;
            font-size: 17px;
        }
        .fake-link:hover { 
            color: #e74c3c; 
        }
        footer { 
            text-align: center; 
            padding: 25px; 
            background: #f8f9fa; 
            color: #666; 
            font-size: 14px;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>補天SRC (Butian SRC)</h1>
            <p class="subtitle">公益漏洞報告演示平台</p>
        </header>
        
        <div class="content">
            <h2>🔍 漏洞報告演示頁面</h2>
            <p>這是一個用來演示「視覺欺騙 (Visual Spoofing)」漏洞的教育頁面。</p>
            
            <div class="warning">
                <strong>⚠️ 重要提醒：</strong><br>
                本頁面僅供學習和演示用途，請勿用於實際惡意行為。
            </div>

            <h3>演示內容：</h3>
            <p>請點擊下面的連結看看會發生什麼：</p>
            
            <p style="font-size:18px; margin: 25px 0;">
                👉 <span class="fake-link" onclick="alert('你已經成功被欺騙了！\n\n這就是視覺欺騙漏洞的危險。\n\n你以為點擊的是補天官方連結，但實際上執行了惡意程式碼。\n\n請提高警覺！')">https://butian.net/submit/report</span>
            </p>

            <hr style="margin: 30px 0;">
            
            <h3>漏洞原理說明</h3>
            <p>攻擊者透過偽造連結外觀，讓使用者誤以為點擊的是正規網站，從而執行惡意操作。</p>
            
            <p style="color:#e74c3c; font-weight:bold;">這就是為什麼在真實環境中，我們不能只看連結顯示的文字就輕易點擊。</p>
        </div>
        
        <footer>
            <p>補天SRC 公益漏洞報告演示 | 僅供教育用途</p>
            <p>倉庫：butianhk • 用戶：jayjaychan0124-bit</p>
        </footer>
    </div>
</body>
</html>
