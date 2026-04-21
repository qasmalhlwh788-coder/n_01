cat > README.md << 'EOF'
# 🔥 SPAM BOT - نظام الهجوم المتكامل

## 📖 عن المشروع
نظام متكامل لأغراض تعليمية واختبار الاختراق

## 🛠️ التقنيات المستخدمة
- Python 3
- Flask (خادم الويب)
- HTML/CSS/JS (واجهة المستخدم)

## 🚀 طريقة التشغيل

### تثبيت المتطلبات
\`\`\`bash
pip install -r requirements.txt
\`\`\`

### تشغيل الخادم
\`\`\`bash
python app.py
\`\`\`

ثم افتح المتصفح على: \`http://localhost:5000\`

## 📁 هيكل المشروع
\`\`\`
spam-bot/
├── app.py           # خادم الويب
├── spam_bot.py      # دوال الاتصالات
├── requirements.txt # المكتبات المطلوبة
└── templates/
    └── index.html   # واجهة المستخدم
\`\`\`

## ⚠️ تنبيه
هذا المشروع للأغراض التعليمية فقط

## 📞 الدعم
- قناة التليغرام: [@aaanxbxbs](https://t.me/aaanxbxbs)
- المطور: @nccciiu
EOF

git add README.md
git commit -m "Add README.md"
git push
