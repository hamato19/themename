<div id="top"></div>
<br />
<div align="center"> 
  <a href="https://salla.dev"> 
    <img src="https://salla.dev/wp-content/uploads/2023/03/1-Light.png" alt="Logo"> 
  </a>
  <h1 align="center">Theme The Memory Lane</h1>
  <p align="center">
    ثيم "ذا ميموري لين" (The Memory Lane) هو نقطة البداية لتطوير ثيمات متاجر العطور على منصة سلة، مزود بطابع كلاسيكي أنيق يحاكي الحنين والذكريات.
    <br />
    <a href="https://salla.dev/"><strong>استكشف مدونتنا »</strong></a>
    <br />
    <a href="https://github.com/SallaApp/theme-raed/issues/new">الإبلاغ عن مشكلة</a> · 
    <a href="https://github.com/SallaApp/theme-raed/discussions/new">طلب ميزة</a> . <a href="https://t.me/salladev">&lt;/مطورو سلة&gt;</a> . <a href="https://docs.salla.dev/?nav=01HNFTD5Y5ESFQS3P9MJ0721VM">التوثيق الرسمي</a> 
  </p>
</div>


<!-- TABLE OF CONTENTS -->
<details open>
  <summary>محتويات الدليل</summary>
<ol>
<li><a  href="#نظرة-عامة">نظرة عامة</a></li>
<li><a  href="#بدء-الاستخدام">بدء الاستخدام</a>
<ul>
<li><a  href="#المتطلبات-الأساسية">المتطلبات الأساسية</a></li>
<li><a  href="#التثبيت">التثبيت</a></li>
</ul>
</li>
<li>
<a  href="#الاستخدام">الاستخدام</a>
<ul>
<li><a  href="#هيكل-الدليل">هيكل الدليل</a></li>
<li><a  href="#معاينة-الثيم">معاينة الثيم</a></li>
</ul>
</li>
<li>
<a  href="#الميزات-الرئيسية">الميزات الرئيسية</a>
<ul>
<li><a  href="#ميزات-الثيم">ميزات الثيم</a></li>
<li><a  href="#مكونات-الثيم">مكونات الثيم</a></li>
</ul>
</li>
<li><a  href="#الدعم">الدعم</a></li>
<li><a  href="#المساهمة">المساهمة</a></li>
<li><a  href="#الشكر-والتقدير">الشكر والتقدير</a></li>
<li><a  href="#الترخيص">الترخيص</a></li>
</ol>
</details>

<br>

## نظرة عامة
ثيم "ذا ميموري لين" هو نقطة الانطلاق للمطورين لتصميم ثيمات لمتاجر العطور التي تعكس شخصية كل متجر على [منصة سلة](https://s.salla.sa). صُمم هذا الثيم خصيصاً ليضفي لمسة من الأناقة الكلاسيكية والحنين، مما يسهل على المطورين تخصيص المتجر ليتناسب مع رؤية صاحبه وتطلعاته. يأتي الثيم مشحوناً مع [ثيمات تويلايت](https://docs.salla.dev/?nav=01HNFTD5Y5ESFQS3P9MJ0721VM)، محرك ثيمات سلة، لتمكين المطورين من إنشاء ثيمات قابلة للتخصيص بالكامل.

## بدء الاستخدام 
يمكن للمطورين استخدام ثيم "ذا ميموري لين" ليس فقط لتصميم ثيمات سلة باستخدام ملفات HTML/CSS/JS ومكونات واجهة مستخدم قابلة لإعادة الاستخدام، ولكن أيضاً لبناء إجراءات مخصصة تشغل أحداث ومشابك (Hooks) في JavaScript.

<p align="right">(<a href="#top">عد إلى الأعلى</a>)</p>

### المتطلبات الأساسية  
- فهم أساسي للغات HTML، CSS، JS، ومحرك القوالب [Twig](https://twig.symfony.com/).
- حساب شريك في [بوابة شركاء سلة](https://salla.partners/) لإنشاء متجر تجريبي لنشر واختبار الثيم الخاص بك.
- حساب على [Github](https://github.com) لمزامنة الثيم معه.
- تثبيت [واجهة أوامر سلة (Salla CLI)](https://www.npmjs.com/package/@salla.sa/cli).

### التثبيت  
يتم تثبيت ثيم "ذا ميموري لين" افتراضياً عند تثبيت ثيمات تويلايت. يمكن تثبيت تويلايت بطريقتين:

- عبر [بوابة شركاء سلة](https://docs.salla.dev/doc-421877/?nav=01HNFTD5Y5ESFQS3P9MJ0721VM#creating-theme-via-salla-partners-portal).
- عبر [واجهة أوامر سلة (Salla CLI)](https://docs.salla.dev/doc-422775/?nav=01HNA8QHCPJTCY5VSEZ616JCAK).

بأي من الطريقتين، سيتم تشغيل تثبيت محرك تويلايت وثيم "ذا ميموري لين". يمكنك قراءة المقالة الكاملة حول [كيفية تثبيت وإنشاء](https://docs.salla.dev/doc-421877/?nav=01HNFTD5Y5ESFQS3P9MJ0721VM) ثيمات تويلايت.

<p align="right">(<a href="#top">عد إلى الأعلى</a>)</p>

## الاستخدام 
سيتم تثبيت ثيم "ذا ميموري لين" كثيم افتراضي عند تثبيت تويلايت. سنلقي نظرة على كيفية تنظيم أدلة هذا الثيم وكيفية استخدام وضع المعاينة في القسم التالي.

### هيكل الدليل  
**ثيم "ذا ميموري لين"** هو مجموعة من الملفات والمجلدات التي تحدد طبقة العرض لمتجر سلة. يوضح التالي هيكل الدليل لهذا الثيم الافتتاحي:

```shell
+---scr
    +---assets
    |   +---images      
    |   +---js      
    |   +---styles         
    +---locales
    |       ar.json
    |       en.json
    +---views
        +---components
        |   +---footer
        |   +---header
        |   +---home
        |   +---product
        |   comments.twig
        +---layouts
        |       master.twig
        +---pages
            |   cart.twig
            |   index.twig
            |   loyalty.twig
            |   page-single.twig
            |   thank-you.twig
            +---blog
            |       index.twig
            |       single.twig 
            +---brands
            |       index.twig
            |       single.twig 
            +---customer
               |   notifications.twig
               |   profile.twig
               |   wishlist.twig
               +---orders
               |      index.twig
               |      single.twig
            +---partials
                |   single-comment.twig
                +---product
                  |   card-full-image.twig
                  |   card-mini.twig
                  |   card.twig
                  |   options.twig
                  |   slider.twig
            +---product
            |       index.twig
            |       single.twig
