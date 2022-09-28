## تجيهز البيئة
- تأكد من تحميل git وتحقق من النسخة باستخدام الأمر التالي:
```
git --version
```
أضف معلوماتك في ملف .gitconfig باستخدام الأوامر التالية:
```
git config --global user.name "الاسم"
git config --global user.email "البريد الالكتروني"
```

# خطوات المساهمة
1. في البداية تحتاج إلى عمل `fork` للمشروع على حسابك.
2. عمل Clone للمستودع.
```
git clone https://github.com/YourUsername/Open-source-dev.git
```
3. انشئ Barnch جديد.
```
git branch YourBranchName
```
4. انتقل إلى Branch الذي انشئته.
```
git checkout YourBranchName
```
5. ابدأ بعمل مساهمتك، اكتب اسمك في ملف `README.md` تحت عنوان `Contributors List`.
```
nano README.md
```
للخروج من محرر النصوص nano، اضغط التالي: `Ctrl+X` ثم `Y` وأخيراً زر `Enter`

6. الآن أضف تعديلاتك باستخدام الأمر التالي:
```
git add .
```
7. نفذ `commit` وأضف الرسالة كالتالي:
```
git commit -m 'my open source contribution'
```
8. ارفع تعديلاتك 
```
git push origin YourBranchName
```
9. الآن على Github اضغط زر `Pull Request` وسيظهر خيار `create a pull request`.

وبذلك تكون اتممت عملية المساهمة إلى حين قبولها من قبل صاحب المشروع.
