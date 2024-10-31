<h1 align="center">$$\color{#a5a5a5} \Large \text{ بیا پایین بچه}$$</h1>

 __*[فارسی 🇮🇷](README-fa.md)*__
 __*[انگلیسی 🇬🇧](README.md)*__
 
<p align="center">
  <img src="https://github.com/user-attachments/assets/2687f318-87eb-4af6-a30a-5904f25bd394" width="160px" 
   style="text-align: center;" alt="https://github/.com/NiREvil/bia-pain-bache" <figcaption>v2.7
</p><br>

<h2>$$\color{#a5a5a5} \Large \text{جدول مطالب}$$</h2>

- [معرفی](#معرفی)
- [ویژگی ها](#ویژگی-ها)
- [نحوه راه اندازی و تنظیمات](#نحوه-راه-اندازی-و-تنظیمات)
- [درباره متغیر ها](#درباره-متغیر-ها)
- [پیش نمایش پنل](#پیش-نمایش-پنل)  
- [کلاینت های پشتیبانی‌ شده](#کلاینت-های-پشتیبانی-شده)
<br>

<h2>$$\color{gray} \Large \text{معرفی}$$</h2>

#### $$\color{gray} \large \text{این پروژه توسعه‌ی یک پنل کاربری برای اسکریپت وورکر کلادفلر ایجاد شده توسط}$$ $$\color{gold} \Large \text{yonggekkk}$$ [^1] $$\color{gray} \large \text{می‌باشد.}$$
#### $$\color{gray} \large \text{و همچنین قدردانی می‌کنم از توسعه دهنده اصلی پروژه}$$  $$\color{gold} \Large \text{بیا پایین بچه}$$ [^2] $$\color{gray} \large \text{.بخاطر پنل فوق العاده ای که ایجاد کردند}$$

</p><br>

<h3>$$\color{gray} \Large \text{:این پنل به دو روش راه‌اندازی می‌شود}$$</h3>

- [راه‌اندازی با __Worker__](docs/worker_installation_fa.md)  
- [راه‌اندازی با __Pages__](docs/pages_installation_fa.md)
</p><br>


## ویژگی‌ ها
<br>
<ol dir="rtl">
  <li><strong>رایگان</strong></li>
  <li><strong>پنل کاربری راحت:</strong> قابلیت آسان تنظیمات و دریافت کانفیگ ها و لینک های اشتراک.</li>
  <li><strong>پروتکل‌های متنوع:</strong> ارائه کانفیگ‌های VLESS، Trojan و Warp.</li>
  <li><strong>سابسکریپشن Warp Pro: </strong>ارائه‌ی کانفیگ‌های وارپ بهینه شده برای شرایط همیشه خاص ایران</li>
  <li><strong>پشتیبانی از فرگمنت:</strong> قابل استفاده حتی در صورت فیلتر شدن دامنه.</li>
  <li><strong>قوانین مسیریابی کامل:</strong> شامل دور زدن سایت‌های ایرانی و چینی، روسی و دسترسی مستقیم به LAN، مسدودسازی تبلیغات ایرانی و خارجی و پورن و پروتکل QUIC</li>
  <li><strong>زنجیره‌ی Proxy:</strong> قابلیت اضافه کردن Proxy خروجی جهت تثبیت IP.</li>
  <li><strong>پشتیبانی از طیف وسیعی از برنامه‌ها:</strong> لینک‌های اشتراک را برای انواع نرم افزار ها با هسته‌های Xray و Sing-box و Clash ارائه میدهد.</li>
  <li><strong>پنل با رمز عبور محافظت شده:</strong> ایمن‌سازی پنل با استفاده از رمز عبور.</li>
  <li><strong>سفارشی‌سازی کامل تنظیمات:</strong> قابلیت اسکن و تنظیم IP تمیز، Proxy IP، DNS سرورها، پورت‌ها، پروتکل‌ها و Warp endpoint و ...</li>
</ol>
<br><br>


## نحوه راه اندازی و تنظیمات
- [نصب به صورت Pages](docs/pages_installation_fa.md)
- [نصب به صورت Worker](docs/worker_installation_fa.md)
- [پیدا کردن Proxy IP](docs/proxy-ip-scanner.md)
- [نحوه استفاده از پنل](docs/configuration_fa.md)
- [پرسش‌های متداول (FAQ)](docs/faq.md)
<br>


## درباره متغیر ها
> برای مشاهده توضیحات بیشتر درباره چگونگی ایجاد متغییر‌ها به [این لینک](https://github.com/NiREvil/bia-pain-bache/blob/main/docs/pages_installation_fa.md#3--%D8%AA%D8%BA%DB%8C%DB%8C%D8%B1-%D9%BE%D8%B3%D9%88%D8%B1%D8%AF%D9%87%D8%A7%DB%8C-trojan) مراجعه کنید. 

![rainbow](https://github.com/NiREvil/vless/assets/126243832/1aca7f5d-6495-44b7-aced-072bae52f256)

| نام متغیر | مثال | الزام | توضیحات|
|-----|----|--|------------|
| UUID | `90cd4a77-141a-43c9-991b-08263cfe9c10` |✅| برای ایجاد آی‌دی خود به [این لینک] (https://www.uuidgenerator.net/) مراجعه 
کنید. |
| PROXYIP | `bpb.radically.pro` |❌|برای دسترسی به سایت‌هایی که از سی‌دی‌ان کلادفلر استفاده می‌کنند باید از پروکسی‌ آی‌پی‌ها استفاده کنیم، پشتیبانی از چند پروکسی آی‌پی، برای مثال : ```['bpb.radically.pro', 'bpb.yousef.isegaro.com'];```برای پیدا کردن پروکسی‌های بیشتر به [این لینک](https://github.com/NiREvil/vless/blob/main/sub/ProxyIP.md) مراجعه کنید. |
| TROJAN_PASS  | `REvil` |✅|پسوورد دلخواه شما برای کانفیگ‌های تروجان |
| HASH_PASS | `6dfd0e8e67ad3230498f80938cb924bc767b7` |✅| پسوورد تروجان دلخواه شما باید به رشته‌های هش SHA-224 به منزله ذخیره ایمن رمز عبور و تأیید صحت داده ها تبدیل شود، برای انجام تبدیل به [این لینک](https://emn178.github.io/online-tools/sha224.html) مراجعه کنید. |

![rainbow](https://github.com/NiREvil/vless/assets/126243832/1aca7f5d-6495-44b7-aced-072bae52f256)


## پیش نمایش پنل

<p align="center">
  <img src="docs/assets/images/Panel.png">
</p>

<p align="center">
  <img src="docs/assets/images/Panel_2.png">
</p>

<p align="center">
  <img src="docs/assets/images/Panel_3.png">
</p>

<p align="center">
  <img src="docs/assets/images/Panel_4.png">
</p>

<p align="center">
  <img src="docs/assets/images/Panel_5.png">
</p>

<p align="center">
  <img src="docs/assets/images/Panel_6.png">
</p>

<br><br> 


## کلاینت‌ های پشتیبانی‌ شده
<div dir="rtl">
<table>
  <thead>
    <th>برنامه</th>
    <th>نسخه</th>
    <th>Fragment</th>
    <th>Warp Pro</th>
  </thead>
  <tbody  align="center">
    <tr>
      <td><b>v2rayNG</b></td>
      <td>1.8.19 و بالاتر</td>
      <td>✔️</td>
      <td>❌</td>
    </tr>
    <tr>
      <td><b>v2rayN</b></td>
      <td>6.42 و بالاتر</td>
      <td>✔️</td>
      <td>❌</td>
    </tr>
    <tr>
      <td><b>v2rayN-Pro</b></td>
      <td>1.4 و بالاتر</td>
      <td>✔️</td>
      <td>✔️</td>
    </tr>
    <tr>
      <td><b>Nekobox</b></td>
      <td></td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td><b>Sing-box</b></td>
      <td>1.8.10 و بالاتر</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td><b>Streisand</b></td>
      <td></td>
      <td>✔️</td>
      <td>❌</td>
    </tr>
    <tr>
      <td><b>V2Box</b></td>
      <td></td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td><b>Shadowrocket</b></td>
      <td></td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td><b>Nekoray</b></td>
      <td></td>
      <td>✔️</td>
      <td>❌</td>
    </tr>
    <tr>
      <td><b>Hiddify</b></td>
      <td>2.0.5 و بالاتر</td>
      <td>❌</td>
      <td>✔️</td>
    </tr>
    <tr>
      <td><b>NikaNG</b></td>
      <td></td>
      <td>✔️</td>
      <td>✔️</td>
    </tr>
    <tr>
      <td><b>Clash Meta</b></td>
      <td></td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td><b>Clash Verg Rev</b></td>
      <td></td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td><b>FLClash</b></td>
      <td></td>
      <td>❌</td>
      <td>❌</td>
    </tr>
  </tbody>
</table>
</div>

---

### تشکر ویژه

- نویسنده کد CF-vless <a href="https://github.com/3Kmfi6HP/EDtunnel">3Kmfi6HP</a>
- نویسنده برنامه IP ترجیحی CF <a href="https://github.com/badafans/Cloudflare-IP-SpeedTest">badafans</a>، <a href="https://github.com/XIU2/CloudflareSpeedTest">XIU2</a>

---

- برای آموزش جزئیات اسکریپت اصلی، لطفاً به <a href="https://ygkkk.blogspot.com/2023/07/cfworkers-vless.html"> وبلاگ و آموزش‌های ویدیویی Yongge</a> مراجعه کنید.

---

[^1]: [yonggekkk](https://github.com/yonggekkk/Cloudflare-workers-pages-vless) 
[^2]: [BPB](https://github.com/bia-pain-bache) 
