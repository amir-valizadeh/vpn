# vpn
ways to add vpn in our device and other ways to turn off inside and outside lockout for irainan developers
<p align="center">
    <h2 align="center">VPN for developers<br>چطور از دزد فرار کنیم  به داروغه نخوریم</h2>
    <p align="center">آموزش ساده تا خوب  راه اندازی قندشکن برای کاربرای لینوکس</p>
    <p align="center">
    <a href="https://opensource.org/licenses/MIT/" target="_blank">
    <img alt="MIT License" src="https://img.shields.io/badge/License-MIT-blue.svg" style="display: inherit;"/>
    </a>
  </p>
</p>



<div dir="rtl">
    <p>
تلاش میکنیم دور هم یاد بگیریم چطور از قند شکن ها استفاده کنیم و تحریم هارو دور بزنیم تا بتونیم چند خط کد بزنیم که بتونیم چس قرون پول دربیاریم 
    <br><br><hr/>
   عموما کسایی که میان سمت  لینوکس و دنیای ازاد با مشکل دستو پنجه نرم میکنن و نمیتونن کاریش کنن 
   و خیلی ها سر این بر میگردن به ویندوز ٬ این سری راهی که میگم میتونه کمک حالتون باشه 
   سعی میکنم زود به زود اپدیتش کنم اگه شما راه راحتتری دارین میتونین بهم پیام بدین و من ادد میکنم 
    </p><hr/>
    <h2>📄 لیست مطالب</h2>
    <p>
        <ul>
            <li><a href="https://github.com/amir-valizadeh/vpn/blob/main/01.%20simplest%20way.md">راحتترین راه (اگه تازه نصب کردین اینو  راه بندازین که بتونین  به شبکه ازاد دسترسی داشته باشید موقتا)</a></li>
            <li><a href="https://github.com/amir-valizadeh/vpn/blob/main/02.%20proxy%20and%20vpn.md">فرق پراکسی و  وی پی ان(مهم حتما بخونید) </a></li>
            <li><a href="https://github.com/amir-valizadeh/vpn/blob/main/03.%20openvpn.md">openvpn - سطح: متوسط</a></li>
            <li><a href="">pptp - سطح:متوسط</a></li>
            <li><a href="">p2pp - سطح:متوسط</a></li>
            <li><a href="">wiregourd -سطح:متوسط</a></li>
            <li><a href="">command-line vpns - سطح:متوسط</a></li>
            <li><a href="">GUI apps for vpn - اسون</a></li>
        </ul>
    </p>
    <h2>📞 ارتباط با من</h2>
    <p>
        - <a href="https://t.me/edoarddo">تلگرام</a><br>
        - <a href="https://www.linkedin.com/in/amir-valizadeh-50b924172/">لینکدین</a>
    </p>
  
</div>

<div dir='rtl'>
چیزی که ما میخوایم نصب کنیم اسمش outline هستش که داخل همه package manager ها وجوود داره توی استور توزیعتون سرچش کنین و نصبش کنین (فعلا فیلترش نکردن ایشالله که متوجهش هم نمیشن) خب بعد اینکه نصب کردین یه صفحه ی خالی میاره 
این اپ صرفا یه کلاینت برای کانفیگ های shadowsocks (بعدا میگم چیه) هست 
خب حالا برین توی این لینک 
https://t.me/wbnet(کپیش کنین توی تلگرامتون تا بتونین بازش کنین)
همیشه توی پیام های پینش یه سری سرور shadowsocks  به فرمت txt هست 
با یه ابزاری بازشون کنین و یه خط از اونارو بردارین 
بیارین توی outline
اون بالا یه پلاس هست اونو بزنین و اون یک خط رو روی اون باکسش پست کنین 
بعدش باید براتون اسم و سرور رو بیاره روش بزنین و کانکت میشین 
این کلاینت کمی مشکل داره گاهی هنگ ممکنه بکنه ولی پراکسی های شدوساکس رو از یه تونل رد میکنه و باعث میشه کل سیستم حتی ترمینال هم تونل بشه 
<hr/>
اگه احیانا وصل نشد یکی دیگه رو امتحان کنید گاهی سرور ها خاموش میشن
<hr/>
اگه این اپ فیلتر شد  این صفحه رو اپدیت میکنم و میگم چیکار کنین ولی اگه توی مخازن توزیعتون نبود سرچ کنین احتمالا خروجیش (فایل نصبی)رو گذاشتن 
<br>
اگه اونم نبود با ابزار هایی مثل snap  و اینا نصبش کنین 
اگه اونم نبود یه توزیع دیگه نصب کنین  :) 
<br>
بیاین مانجارو ٬مانجارو عشقه
<hr/>
ایا میشه از این به صورت دائم استفاده کرد؟
<br> اره چرا نمیشه اگه جواب میگیرین استفاده کنین ولی خب کلی روش خفن هست که بعد میگم اون موقع احتمالا بیخیال این بشین
ولی خب فعلا تنها ابزار راحتیه که میشه توی همه ی توزیع ها نصبش کنین وقتی هیچ وی پی انی روی سیستم ندارین و نمیتونین  برنامه های دیگه رو دانلود کنین
</div>
