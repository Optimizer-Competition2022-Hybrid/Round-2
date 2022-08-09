# Round-2


<p align="center">
  <a href="" rel="noopener">
 <img width="150" src="http://optimizer.math.sharif.edu/wp-content/uploads/2021/02/optimizer.png" alt="Optimizer logo"></a>
</p>
<h3 align="center">Hybrid</h3>

<div align="center">

  [![Status](https://img.shields.io/badge/status-active-success.svg)]() 
  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mtefagh/demos/HEAD)
  [![License](https://img.shields.io/badge/license-GPL-blue.svg)](https://github.com/mtefagh/demos/blob/master/LICENSE)

</div>

---

## 📝 فهرست مطالب
- [الگوریتم بهینه‌سازی](#idea)
- [محدودیت‌ها](#limitations)
- [ایده‌های گسترش](#future_scope)
- [روند اجرا](#getting_started)
- [نحوه استفاده](#usage)
- [وابستگی‌ها](#tech_stack)
- [نویسندگان](#authors)
- [قدردانی](#acknowledgments)

## 💡 الگوریتم بهینه‌سازی <a name = "idea"></a>
در حالت کلی از الگورتیم `k-means`، `GMM`, `Hierarchical`
برای یافت منیفلدها استفاده شده است همچنین
برای تشخیص داده‌های پرت از الگوریتم `DBSCAN` استفاده کردیم.
<br>
برای تشخیص تعداد clusterهای موجود در هر منیفلد از معیار `Silhouette` کمک گرفتیم.

## ⛓️ محدودیت‌ها <a name = "limitations"></a>
برنامه به طور خاص بر حسب visualization و ساختار داده‌های این مرحله نوشته شده لذا ممکن است برای اجرا بر روی انواع داده‌های دیگر نیاز به تغییراتی غیرخودکار داشته باشد. 
<br>
در این راند راه خودکاری برای نسبت دادن 
$k_i$
به منیفلدها نداشتیم و تصمیمات مربوط به آن بر اساس نمودار `Silhouette` 
و روش `Elbow` بر روی میزان `inertia` گرفته شده است.

## 🚀 ایده‌های گسترش <a name = "future_scope"></a>
برای امتیازدهی به هر clustering می‌توان از روش `eigengap` نیز استفاده نمود که در راندهای آخر آن را پیاده سازی کردیم.
 <br>
 در این راند اکثر روند clustering و یافتن منیفلدها بر پایه‌ی visualization و تغییرات غیر خودکار مخصوص هر داده بوده در راندهای بعدی تلاش کردیم تا مقداری از این روند را به صورت خودکار درآوریم.

## 🏁 روند اجرا <a name = "getting_started"></a>
تکه کدها از بالا به پایین در jupyter notebook مرتب شده‌اند و قابل اجرا هستند.

### پیش‌نیازها

برای نصب پیش‌نیازها کافی است دستور زیر را اجرا کنید. 
```
pip install -r pip-requirements
```

## 🎈 نحوه استفاده <a name="usage"></a>
ابتدا فایل ورودی را در پوشه‌ی اجرا قرار دهید سپس مقدار متغییر subtask را در نوت‌بوک به سابتسک مورد نظر تغییر دهید.
<br>
برای زیرمسئله‌های ۳ و ۴ می‌توان از راه حل کلی ارائه شده در
<a href="https://github.com/Optimizer-Competition2022-Hybrid/Round-4">اینجا</a>
استفاده نمود. (که البته برای کارکرد بهینه نیار به بررسی‌های جداگانه و غیرخودکار دارد)
## ⛏️ وابستگی‌ها <a name = "tech_stack"></a>
زبان برنامه‌نویسی:
Python
<br>
لیست کتاب‌خانه‌های استفاده شده:

```
miniballCpp
matplotlib
pandas
numpy
scikit-learn
```

## ✍️ نویسندگان <a name = "authors"></a>
بهنام روحانی، امیرسالار صفایی‌قادری، مانی حاجی‌مهدی

## 🎉 قدردانی <a name = "acknowledgments"></a>
تشکر از کسانی که به نحوی در برگزاری این مسابقه سهیم بوده‌اند
