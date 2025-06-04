<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>نموذج تسجيل المخالفة - محافظة جنوب الشرقية</title>
    
    <!-- Bootstrap RTL -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.rtl.min.css" />
    
    <!-- Google Font - Tajawal -->
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;500;700&display=swap" rel="stylesheet">
    
    <style>
        body {
            font-family: 'Tajawal', sans-serif !important;
            padding: 2rem;
            background-color: #f7f7f7;
        }
        
        /* تطبيق الخط على جميع العناصر */
        body, h1, h2, h3, h4, h5, h6,
        .form-control, .form-label, .btn,
        select, input, textarea, .violation-details {
            font-family: 'Tajawal', sans-serif !important;
        }
        
        .card {
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border: none;
            border-radius: 10px;
            background-color: white;
        }
        
        .form-label {
            font-weight: bold;
        }
        
        .section-title {
            background-color: #004884;
            color: white;
            padding: 10px;
            border-radius: 5px;
            margin-top: 1.5rem;
            margin-bottom: 1rem;
            text-align: center;
        }
        
        .btn-primary {
            background-color: #006400;
            border: none;
        }
        
        .btn-primary:hover {
            background-color: #003366;
        }
        
        .logo-header {
            text-align: center;
            margin-bottom: 1rem;
        }
        
        .logo-header img {
            width: 120px;
        }
        
        /* أنماط القوائم المنسدلة */
        .select-group {
            margin-bottom: 20px;
        }
        
        select {
            width: 100%;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 4px;
            font-size: 16px;
            background-color: #f9f9f9;
        }
        
        .violation-details {
            margin-top: 30px;
            padding: 20px;
            background-color: #f8f9fa;
            border-radius: 5px;
            border-right: 4px solid #3498db;
            display: none;
        }
        
        .violation-details h3 {
            color: #2980b9;
            margin-top: 0;
        }
        
        .fine {
            font-weight: bold;
            color: #e74c3c;
            margin: 10px 0;
        }
        
        .penalty {
            color: #c0392b;
        }
        
        /* أنماط قارئ QR */
        .qr-scanner-container {
            border: 2px dashed #ccc;
            padding: 15px;
            border-radius: 8px;
            margin-bottom: 20px;
            background-color: #f9f9f9;
        }
        
        #reader {
            width: 100%;
            max-width: 300px;
            margin: auto;
        }
        
        #qr-result {
            margin-top: 15px;
            font-size: 16px;
            font-weight: bold;
            color: green;
            text-align: center;
        }
    </style>
</head>
<body>
    <div style="display: flex; justify-content: center; align-items: center; height: 150px;">
        <img class="loader-logo wow fadeInUp" data-wow-delay="0.2s" src="https://ssg.gov.om/storage/configuration-images/animatedLogo.gif" alt="Site Logo" style="width: 350px; height: auto;" />
    </div>

    <h3 class="mt-2" style="text-align: center;"><b><font size="4">دائرة البلدية بالكامل و الوافي</font></b></h3>    

    <!-- عنوان النموذج -->
    <h2 class="text-center mb-4"><font size="4">الواجهة الذكية لتسجيل المخالفات</font></h2>
    <h2 class="text-center mb-4"><font size="4">والزيـــارات الميدانيــة للمنشـــآت</font></h2>

    <!-- النموذج -->
    <div class="container">
        <div class="card p-4">
            <form>
                <!-- المعلومات العامة -->
                <div class="section-title">المعلومات العامة</div>
                <div class="row mb-3">
                    <div class="col-md-6">
                        <label class="form-label">اسم المفتش</label>
                        <input type="text" class="form-control" required="" />
                    </div>
                    <div class="col-md-6">
                        <label class="form-label">القســـم</label>
                        <input type="text" class="form-control" required="" />
                    </div>
                </div>

                <!-- بيانات المنشأة -->
                <div class="section-title">بيانات المنشأة</div>
                
                <!-- قارئ QR الجديد --><div class="text-center">
                    <button type="submit" class="btn btn-primary">تسجيل المخالفة</button>
                </div>
            
        
    
<div style="text-align: center;"><br /></div>
<div class="section-title" style="text-align: center;">مسح رمز QR</div>

<div class="text-center">
    
<div id="reader" style="text-align: center; width: 100%; max-width: 300px; margin: auto; border: 2px solid rgb(204, 204, 204); border-radius: 10px; padding: 10px; background: white;"></div>
    
<div id="result" style="text-align: center; margin-top: 15px; font-size: 16px; font-weight: bold; color: green;">النتيجة ستظهر هنا بعد المسح</div>
    <button class="btn btn-outline-primary mt-2" onclick="startScanner()">إعادة المسح</button>
</div>

<script src="https://unpkg.com/html5-qrcode" type="text/javascript"></script>
<script>
    let scanner;
    function startScanner() {
        document.getElementById('result').innerText = "جاري المسح...";
        if (scanner) {
            scanner.clear().then(() => {
                start();
            }).catch(err => {
                console.error("</script>"button" class="btn btn-outline-primary" onclick="startScanner()">بدء المسح</button>
                    </div>
                </div>
                </div>

<div class="row mb-3">
    
<div class="col-md-6">
        <label class="form-label">اسم المنشأة</label>
        <input type="text" class="form-control" required="" />
    </div>
    
<div class="col-md-6">
        <label class="form-label">نوع النشاط</label>
        <input type="text" class="form-control" required="" />
    </div>
</div>

<div class="row mb-3">
    
<div class="col-md-6">
        <label class="form-label">اسم صاحب المنشأة</label>
        <input type="text" class="form-control" required="" />
    </div>
    
<div class="col-md-6">
        <label class="form-label">رقم الهاتف</label>
        <input type="tel" class="form-control" required="" />
    </div>
</div>

<div class="row mb-3">
    
<div class="col-md-6">
        <label class="form-label">الموقع</label>
        <input type="text" class="form-control" required="" />
    </div>
    
<div class="col-md-6">
        <label class="form-label">رقم السجل التجاري</label>
        <input type="text" class="form-control" />
    </div>
</div>

<div class="row mb-3">
    
<div class="col-md-6">
        <label class="form-label">رقم إباحة البناء</label>
        <input type="tel" class="form-control" />
    </div>
                </div>

                <!-- تفاصيل المخالفات -->
                <div class="section-title">نظام المخالفات الادارية والجزاءات</div>
                
                <div class="select-group">
                    <label for="category">اختر فئة المخالفة:</label>
                    <select id="category" onchange="loadViolations()">
                        <option value="">-- اختر الفئة --</option>
                        <option value="licensing">مخالفات الترخيص البلدي</option>
                        <option value="workers">مخالفات العاملين</option>
                        <option value="facility">مخالفات المنشأة ومرافقها</option>
                        <option value="health">مخالفات الصحة الوقائية والصرف الصحي</option>
                    </select>
                </div>
                
                <div class="select-group">
                    <label for="violation">اختر المخالفة:</label>
                    <select id="violation" onchange="showDetails()" disabled>
                        <option value="">-- اختر الفئة أولاً --</option>
                    </select>
                </div>
                
                <div id="details" class="violation-details">
                    <h3 id="violation-title">تفاصيل المخالفة</h3>
                    <div class="fine">قيمة الغرامة: <span id="fine-amount"></span></div>
                    <div class="penalty">الجزاء الإضافي: <span id="additional-penalty"></span></div>
                </div>


<!-- ملاحظة مضاعفة الغرامة -->
<div class="alert alert-warning mt-3 mb-3">
    <strong>ملاحظة:</strong> سيتم مضاعفة الغرامة بعد المدة المقررة للمعالجة
</div>
                <div class="col-md-6">
                    <label class="form-label">مدة معالجة المخالفة (أيام)</label>
                    <input type="number" class="form-control" min="1" />
                </div>

                <!-- الموقع -->
                <div class="section-title">موقع المخالفة</div>
                <div class="mb-3">
                    <label class="form-label">تحديد الموقع على الخريطة</label>
                    <div class="ratio ratio-16x9">
                        <iframe src="https://maps.google.com/maps?q=oman&amp;t=&amp;z=13&amp;ie=UTF8&amp;iwloc=&amp;output=embed" frameborder="0" allowfullscreen=""></iframe>
                    </div>
                </div>

                <!-- صورة ووصف -->
                <div class="mb-3">
                    <label class="form-label">تحميل صورة للمخالفة</label>
                    <input type="file" class="form-control" />
                </div>

                <!-- زر الإرسال -->
                <div class="text-center">
                    <button type="submit" class="btn btn-primary">تسجيل المخالفة</button>
                </div>
            </form>
        </div>
    </div>

    <!-- مكتبة QR Scanner -->
    <script src="https://unpkg.com/html5-qrcode" type="text/javascript"></script>
    
    <script>
        // بيانات المخالفات
        const violationsData = {
            licensing: [
                {code: "1.i", description: "ممارسة نشاط بدون ترخيص (محلات تجارية)", fine: "50", penalty: "الوقف عن العمل حتى استخراج الترخيص"},
                {code: "1.ب", description: "ممارسة نشاط بدون ترخيص (ورش أنشطة مهنية)", fine: "30-100", penalty: "الوقف عن العمل حتى استخراج الترخيص"},
                {code: "2.أ", description: "عدم تجديد الترخيص (محلات تجارية)", fine: "25-50 شهرياً", penalty: "-"},
                {code: "3", description: "ممارسة نشاط خارج نطاق الترخيص", fine: "20-50", penalty: "وقف النشاط غير المرخص"}
            ],
            workers: [
                {code: "12", description: "العمل بدون بطاقة صحية", fine: "30", penalty: "وقف العامل حتى استخراج البطاقة"},
                {code: "13", description: "ممارسة نشاط مخالف للبطاقة الصحية", fine: "20", penalty: "وقف العامل نهائياً"},
                {code: "15", description: "عدم الالتزام بالنظافة الشخصية", fine: "20", penalty: "تصحيح المخالفة فوراً"}
            ],
            facility: [
                {code: "19", description: "عدم الاهتمام بصيانة المنشأة ومرافقها", fine: "10-50", penalty: "إعطاء مهلة محددة لتصحيح المخالفة"},
                {code: "23", description: "عدم الاهتمام بمكافحة الحشرات أو القوارض", fine: "20-50", penalty: "إعطاء مهلة محددة لتصحيح المخالفة"}
            ],
            health: [
                {code: "74", description: "استخدام فوط وأدوات بمحلات الحلاقة غير نظيفة", fine: "50", penalty: "إتلاف غير الصالح منها"},
                {code: "87", description: "عدم استخدام أدوات الوقاية اللازمة لعملية خلط الكلور", fine: "100", penalty: "-"}
            ]
        };

        // تحميل المخالفات حسب الفئة المختارة
        function loadViolations() {
            const categorySelect = document.getElementById('category');
            const violationSelect = document.getElementById('violation');
            const category = categorySelect.value;
            
            violationSelect.innerHTML = '<option value="">-- اختر المخالفة --</option>';
            violationSelect.disabled = !category;
            
            if (category) {
                violationsData[category].forEach(violation => {
                    const option = document.createElement('option');
                    option.value = violation.code;
                    option.textContent = `${violation.code} - ${violation.description}`;
                    violationSelect.appendChild(option);
                });
            }
            
            document.getElementById('details').style.display = 'none';
        }

        // عرض تفاصيل المخالفة المختارة
        function showDetails() {
            const violationSelect = document.getElementById('violation');
            const categorySelect = document.getElementById('category');
            const detailsDiv = document.getElementById('details');
            
            if (!violationSelect.value) {
                detailsDiv.style.display = 'none';
                return;
            }
            
            const category = categorySelect.value;
            const violationCode = violationSelect.value;
            const violation = violationsData[category].find(v => v.code === violationCode);
            
            document.getElementById('violation-title').textContent = violation.description;
            document.getElementById('fine-amount').textContent = violation.fine + " ريال عماني";
            document.getElementById('additional-penalty').textContent = violation.penalty;
            detailsDiv.style.display = 'block';
        }

        // QR Scanner
        let html5QrcodeScanner;
        
        function startScanner() {
            document.getElementById('qr-result').innerText = "جاري المسح...";
            
            // إيقاف الماسح الضوئي إذا كان يعمل بالفعل
            if (html5QrcodeScanner) {
                html5QrcodeScanner.clear().catch(error => {
                    console.error("فشل في إيقاف الماسح السابق: ", error);
                });
            }
            
            // بدء الماسح الضوئي الجديد
            html5QrcodeScanner = new Html5QrcodeScanner(
                "reader",
                { fps: 10, qrbox: 250 },
                /* verbose= */ false
            );
            
            html5QrcodeScanner.render(onScanSuccess, onScanFailure);
        }
        
        function onScanSuccess(decodedText, decodedResult) {
            // عرض النتيجة
            document.getElementById('qr-result').innerText = `تم مسح الرمز: ${decodedText}`;
            
            // يمكنك هنا إضافة أي معالجة إضافية للبيانات الممسوحة
            // مثل تعبئة حقول النموذج تلقائياً
            
            // إيقاف الماسح بعد النجاح
            html5QrcodeScanner.clear();
        }
        
        function onScanFailure(error) {
            // معالجة الأخطاء
            console.warn(`خطأ في المسح: ${error}`);
            document.getElementById('qr-result').innerText = "فشل المسح، يرجى المحاولة مرة أخرى";
        }
    </script>
</body>
</html>
