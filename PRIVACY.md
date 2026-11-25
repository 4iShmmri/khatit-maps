# سياسة الخصوصية — تطبيق خطيط

آخر تحديث: 2026-11-26

خطيط تطبيق ملاحة وخرائط للصحراء يعمل دون إنترنت. صُمّم ليبقى الحدّ الأدنى من
البيانات، وتبقى بياناتك على جهازك.

## ما لا نجمعه
- **لا حسابات** ولا تسجيل دخول.
- **لا خادم لنا** يجمع بياناتك، ولا تحليلات، ولا إعلانات، ولا بيع بيانات.
- لا نُرسل موقعك أو رحلاتك أو جهاتك إلى أيّ خادم نملكه.

## ما يُخزَّن على جهازك فقط
- **الموقع الجغرافي (GPS):** يُستخدم لعرض موقعك، والملاحة، وتسجيل مسار الرحلة.
  يعمل التسجيل في الخلفية عند تفعيله ليستمر مع إقفال الشاشة. لا يغادر الموقع جهازك.
- **الرحلات والأماكن المحفوظة والإعدادات:** تُحفظ محليًّا على الجهاز.
- **جهات الطوارئ:** تُحفظ في مخزن النظام الآمن (Keychain على iOS،
  EncryptedSharedPreferences على Android).

## خدمات خارجية (عند الاتصال بالإنترنت)
عند عرض طبقات تحتاج إنترنت، يطلب التطبيق البلاطات من مزوّديها مباشرةً، فيرى كلٌّ
منهم عنوان IP الخاص بك وإحداثيات البلاطات التي تطلبها، وفق سياسته هو:
- صور الأقمار الصناعية: Esri، وMapbox (اختياري).
- طبقات النبات والمياه: Sentinel Hub (اختياري).
- خريطة الشوارع: OpenStreetMap.
- بيانات الارتفاع: بيانات Mapzen المفتوحة على AWS.
- توقّعات الطقس والأمطار (اختياري): مزوّد الطقس المضبوط في الإعدادات.
الخرائط المتّجهة والمرتفعات تُنزَّل مرّة واحدة إلى الجهاز لتعمل بعدها دون إنترنت.

## نداء الطوارئ (SOS)
يفتح التطبيق تطبيق الرسائل لديك مع أوّل جهة طوارئ محفوظة، ويُدرج موقعك في نصّ
الرسالة. **أنت** من يرسلها؛ لا نرسل نحن أيّ شيء. عند انقطاع التغطية يُحفظ النداء
محليًّا ويُعاد فتحه عند عودة الشبكة.

## أذونات الجهاز
- **الموقع:** للملاحة وتسجيل المسار (أمامي وخلفي).
- **الرسائل/الهاتف:** لفتح تطبيق الرسائل عند إطلاق نداء الطوارئ.

## حقوقك
بياناتك على جهازك؛ يمكنك حذفها كلّها في أيّ وقت من **الإعدادات ← حذف بياناتي**،
أو بحذف التطبيق.

## الأطفال
التطبيق غير موجّه للأطفال ولا يجمع عمدًا بيانات عنهم.

## تغييرات
قد تُحدَّث هذه السياسة؛ يظهر تاريخ آخر تحديث أعلاه.

---

# Privacy Policy — Khatit

Last updated: 2026-11-26

Khatit is an offline desert navigation app. It is designed to collect as little
as possible and to keep your data on your device.

## What we do not collect
- **No accounts**, no sign-in.
- **No server of ours** collects your data; no analytics, no ads, no data selling.
- We never send your location, trips or contacts to any server we control.

## Stored only on your device
- **Location (GPS):** used to show your position, navigate, and record your trip.
  Recording runs in the background when enabled so it continues with the screen
  off. Location never leaves your device.
- **Trips, saved places and settings:** stored locally.
- **Emergency contacts:** stored in the OS secure store (Keychain / Encrypted
  SharedPreferences).

## Third-party services (only when online)
When you view a layer that needs the internet, the app requests tiles directly
from the provider, which then sees your IP address and the tile coordinates you
request, under its own policy: Esri and Mapbox (satellite), Sentinel Hub
(vegetation/water, optional), OpenStreetMap (streets), Mapzen open data on AWS
(elevation), and your configured weather provider (optional). The vector map and
elevation files are downloaded once for offline use.

## SOS
The app opens your Messages app with your first saved emergency contact and puts
your location in the message text. **You** send it; we send nothing. With no
coverage the request is stored locally and reopened when the network returns.

## Permissions
- **Location** for navigation and trip recording (foreground and background).
- **Messages/Phone** to open Messages for an SOS.

## Your rights
Your data lives on your device. Delete all of it anytime from **Settings →
Delete my data**, or by deleting the app.

## Children
The app is not directed at children and does not knowingly collect their data.

## Changes
This policy may be updated; the date above shows the last change.
