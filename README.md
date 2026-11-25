# khatit-maps

بيانات الخرائط المفتوحة لتطبيق **خطيط** (ملاحة صحراوية دون إنترنت).

يستضيف هذا المستودع الملفات التي يُنزّلها التطبيق مرّة واحدة إلى الجهاز ليعمل دون
إنترنت، ويتحقّق من التحديثات عند توفّر اتصال:

| الملفّ | الوصف | الحجم التقريبي | المصدر والترخيص |
|---|---|---|---|
| `sa.mbtiles` | خريطة متّجهة (OpenMapTiles z0–13) للسعودية والخليج | ~211 م.ب | OpenStreetMap (ODbL) · OpenMapTiles (CC-BY) |
| `sa_roads.bin` | شبكة طرق مضغوطة لتوجيه A\* | ~120 م.ب | OpenStreetMap (ODbL) |
| التضاريس | بيانات ارتفاع (Terrarium DEM) — تُنزَّل مباشرةً من بيانات Mapzen المفتوحة على AWS | متغيّر | Mapzen / SRTM / Copernicus (CC0) |

تُنشر الملفّات الكبيرة ضمن **GitHub Releases**، ويصفها `maps-manifest.json` (الاسم،
النسخة، الرابط، الحجم، SHA-256). التطبيق يتحقّق من الـ SHA-256 بعد التنزيل.

## التحديث
تُبنى الملفّات من بيانات OpenStreetMap عبر [Planetiler](https://github.com/onthegomap/planetiler).
عند توفّر بيانات أحدث يُرفع إصدار جديد وتُحدَّث نسخة البيانات في `maps-manifest.json`.

## الإسناد والتراخيص
- بيانات الخرائط: © مساهمو OpenStreetMap — رخصة ODbL.
- مخطّط OpenMapTiles: CC-BY.
- بيانات الارتفاع: Mapzen / NASA SRTM / Copernicus — CC0 / ملك عامّ.

السياسات القانونية للتطبيق: [`PRIVACY.md`](./PRIVACY.md) · [`TERMS.md`](./TERMS.md).
