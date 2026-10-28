[README.md](https://github.com/user-attachments/files/34083710/README.md)
# SharedRentBot

SharedRentBot is the web crawler of a flat-sharing service being built in Saudi Arabia. It helps people who want
to rent a whole flat together find buildings in Riyadh that have flats for rent.

## What it reads

- **Building and company websites:** pages that describe a residential building or compound (name, location,
  unit types, rent where the site publishes it).
- **Public rental listings:** listing pages on property portals and classified-ad sites (and the sitemaps that list
  them), and the public web view of a few public Telegram rental channels.

## What it keeps

Only facts about the property: rent, number of bedrooms, size, district, the building it belongs to, the REGA
advertising licence number, and the licence or commercial registration number and office landline of the
real-estate office behind an ad.

It does **not** keep: people's names, mobile numbers, email addresses, user profiles, page text, descriptions or
photos of the inside of flats. It never logs in, never opens account, profile or message pages, and never
fills in forms.

## How it behaves

- It identifies itself in every request with the User-Agent `SharedRentBot/0.1 (+<link to this page>; …)`.
- It reads slowly: at most one request every 10 seconds per site.

## Contact

To ask us to stop reading your site, or with any question, open an issue in this repository with your domain name.

---

# SharedRentBot (بالعربية)

SharedRentBot هو زاحف الويب لخدمة مشاركة سكن قيد الإنشاء في المملكة العربية السعودية. يساعد من يرغبون في استئجار شقة
كاملة معاً على إيجاد المباني في الرياض التي فيها شقق للإيجار.

## ماذا يقرأ

- **مواقع المباني والشركات:** الصفحات التي تصف مبنى سكنياً أو مجمعاً (الاسم، الموقع، أنواع الوحدات، الإيجار إن نشره
  الموقع).
- **إعلانات الإيجار العامة:** صفحات الإعلانات في منصات العقار ومواقع الإعلانات المبوبة، وخرائط المواقع (sitemaps) التي
  تسردها، والعرض العام على الويب لعدد قليل من قنوات تيليجرام العامة لإعلانات الإيجار.

## ماذا يحفظ

حقائق العقار فقط: الإيجار، عدد الغرف، المساحة، الحي، المبنى الذي يتبع له، رقم ترخيص الإعلان من الهيئة العامة للعقار،
ورقم الترخيص أو السجل التجاري والهاتف الثابت للمكتب العقاري صاحب الإعلان.

لا يحفظ: أسماء الأشخاص، أرقام الجوال، البريد الإلكتروني، الملفات الشخصية، نصوص الصفحات أو الأوصاف، ولا صور داخل الشقق.
لا يسجّل الدخول أبداً، ولا يفتح صفحات الحسابات أو الملفات الشخصية أو الرسائل، ولا يعبّئ النماذج.

## كيف يعمل

- يعرّف بنفسه في كل طلب بـ User-Agent: ‏`SharedRentBot/0.1 (+<رابط هذه الصفحة>; …)`.
- يقرأ ببطء: طلب واحد كل 10 ثوانٍ على الأكثر لكل موقع.

## التواصل

لطلب التوقف عن قراءة موقعكم، أو لأي استفسار، افتحوا "Issue" في هذا المستودع واذكروا اسم النطاق.
