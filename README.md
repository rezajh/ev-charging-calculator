# ⚡ EV Charging Calculator · محاسبه‌گر زمان شارژ خودرو برقی

[English](#english) · [فارسی](#فارسی)

---

## English

A small, offline-capable web app (PWA) that estimates how long an electric car takes to charge, and what it costs. Available in **Persian and English** (toggle at the top), with light / dark / auto themes.

### Features
- Car model + variant dropdowns with battery capacity and charging limits, or a custom car with manual entry
- Dual-handle charge range bar (current % → target %)
- AC single-phase, AC three-phase and DC fast charging, with editable voltage, current and charger power
- Per-car approximate DC charging curves; automatic or manual charging efficiency
- Result: time, energy, power, and finish time from your plug-in time
- Charging curve on a real clock axis: tap or hover to see roughly what percent the battery is charged at any hour
- Cost estimate from your electricity tariff, and a comparison table of common chargers
- Wiring safety notes for high currents, and a note when the target is above 90%
- Works offline after the first visit; installable on your phone's home screen

### Notes and limits
- All results are **estimates**. Real charging time depends on temperature, battery state, the car's on-board charger and the charger itself.
- Some car data is approximate or unverified (e.g. Luna, EJ7 Plus, Hongqi, several DC limits). Use the custom car option for exact specs.
- Charging above 90% is slower than calculated.
- Always have an electrician check the wiring before charging at high current.

---

<div dir="rtl">

## فارسی

یک برنامه‌ی وب کوچک (PWA) که زمان و هزینه‌ی تقریبی شارژ خودرو برقی را حساب می‌کند. **فارسی و انگلیسی** (دکمه‌ی بالای صفحه) و سه حالت روشن، تیره و خودکار دارد.

### امکانات
- انتخاب مدل و تیپ خودرو با ظرفیت باتری و سقف شارژ، یا ورود دستی مشخصات خودروی دلخواه
- نوار دو‌دستگیره برای بازه‌ی شارژ (درصد فعلی ← درصد هدف)
- شارژ AC تک‌فاز، AC سه‌فاز و DC سریع، با ولتاژ، جریان و توان شارژر قابل تنظیم
- منحنی تقریبی شارژ DC مخصوص هر خودرو؛ راندمان خودکار یا دستی
- نتیجه: زمان، انرژی، توان و ساعت پایان شارژ بر اساس ساعت وصل کردن
- منحنی شارژ با محور ساعت واقعی: روی نمودار بزنید تا ببینید در هر ساعت باتری حدوداً چند درصد شارژ شده است
- برآورد هزینه بر اساس تعرفه‌ی برق و جدول مقایسه‌ی شارژرهای رایج
- هشدارهای ایمنی سیم‌کشی برای جریان‌های بالا و یادآوری برای هدف بالای ۹۰٪
- بعد از اولین باز شدن بدون اینترنت هم کار می‌کند و روی صفحه‌ی اصلی گوشی نصب می‌شود

### نکات و محدودیت‌ها
- همه‌ی نتایج **تقریبی** هستند. زمان واقعی به دما، وضعیت باتری، شارژر داخلی خودرو و خود شارژر بستگی دارد.
- بخشی از داده‌ی خودروها تقریبی یا تأییدنشده است (مثل لونا، EJ7 Plus، هونگچی و چند سقف DC). برای مشخصات دقیق از گزینه‌ی خودروی دلخواه استفاده کنید.
- شارژ بالای ۹۰٪ کندتر از زمان محاسبه‌شده است.
- پیش از شارژ با جریان بالا، حتماً سیم‌کشی را به یک برق‌کار نشان دهید.

</div>
