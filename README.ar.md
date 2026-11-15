<div dir="rtl">

# مجموعة أدوات ArcGIS Pro لضبط الجودة (ArcGIS Pro QA Toolkit)‏ v0.1

[English](README.md)

ثلاثون أداة معالجة جغرافية لبرنامج ArcGIS Pro في خمسة صناديق أدوات Python ‏(`.pyt`): فحص جودة البيانات، وإدارة البيانات، والتحليل المكاني، والخرائط، وإدارة مساحات العمل. صُمّمت لترخيص **Basic** ولا تحتاج إلى أي امتداد.

## التثبيت

1. نزّل هذا المجلد وفك ضغطه.
2. في ArcGIS Pro افتح لوحة **Catalog** ثم **Toolboxes**، وانقر بالزر الأيمن واختر **Add Toolbox**، ثم اختر ملفات `.pyt` الموجودة في المجلد `toolboxes/`.
3. وسّع صندوق الأدوات وانقر مرتين على الأداة لفتحها.

أبقِ كل ملف `.pyt.xml` بجانب ملف `.pyt` الخاص به، ففيه نصوص المساعدة.

## الأدوات

الأدوات **المستقرة** شُغّلت في ArcGIS Pro 3.3.2 للإصدار v0.1 ونجحت. الأدوات **التجريبية** تعمل، لكنها لم تدخل في جولة التحقق الخاصة بالإصدار v0.1، فتحقق من نتائجها.

| صندوق الأدوات | مستقرة | تجريبية |
|---|---|---|
| Data Quality & Validation | Arabic-English Name Check، Positional Accuracy Report (NSSDA/ASPRS)، Domain Audit، Multi-Value Code Validator، Near-Miss Value Checker، Join Key Diagnostics | Geometry Quality Checker، QC Scorecard Report، Tile Edge Match Check، Topology Check (Lite)، Broken Text Encoding Detector |
| Data Management & Productivity | Dataset Change Report، Excel Import with Field Types، Spatial Numbering، Rule-Based Attribute Update | Coordinate Notation Converter، Pivot Table to Columns، Disperse Stacked Points |
| Spatial Analysis | Thiessen Polygons (Clipped)، Polygon Holes and Parts، Boundary Description (Metes and Bounds) | Line Network Rule Check، Vertex Extractor، Rose Diagram، Polygon Shape and Width Metrics، Point Thinning by Priority |
| Cartography & Layout | Map Series Index Check | Map Book Index، Time Series Layout Export |
| Project Automation & Administration | Workspace and CRS Inventory | لا يوجد |

## قبل الاعتماد عليها

- اختُبرت على **ArcGIS Pro 3.3.2 بترخيص Advanced**، ولم تُشغَّل بعد على ترخيص Basic.
- لم تُختبر المخرجات في قواعد البيانات المؤسسية (enterprise geodatabase)؛ اكتب المخرجات في قاعدة بيانات ملفية أو في مجلد.
- مساعدة كل أداة في ArcGIS Pro توضح ما تكتبه وهل تغيّر شيئًا.

## الترخيص

MIT. انظر [LICENSE](LICENSE) و[NOTICE.md](NOTICE.md).

</div>
