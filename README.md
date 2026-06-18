# אתר סטטי: ניתוח אפנדיציט – 30 ימים של החלמה

קבצים מוכנים לפריסה ב‑GitHub Pages.

## מה בפנים
- `index.html` — דף אחד משודרג, RTL, מטא‑תגיות ל‑SEO, נגישות, תמיכה ב‑reduced‑motion.

## פריסה מהירה (GitHub Pages)

1) צור/י מאגר:
- אתר משתמש: `<username>.github.io` (מומלץ אם אין עדיין)
- או פרויקט: כל שם, למשל `appendicitis-recovery`

2) דחיפה:
```bash
# אם יש gh:
gh repo create <username>/<repo> --public --source=. --remote=origin --push
# או ידנית:
git init
git add .
git commit -m "Publish appendicitis recovery page"
git branch -M main
git remote add origin git@github.com:<username>/<repo>.git
git push -u origin main
```

3) הפעלת Pages:
- אתר משתמש: נפתח אוטומטית ב‑https://<username>.github.io/
- פרויקט: הגדרו Pages מ־Settings → Pages → Source: `Deploy from a branch`, Branch: `main` (root)
  הכתובת תהיה: `https://<username>.github.io/<repo>/`

4) מומלץ לעדכן ב‑`index.html`:
- `canonical` + `og:image` לכתובת הסופית לאחר הפריסה.

> תרצה/י שאעלה עבורך ואגדיר את ה‑Pages אוטומטית? תן/י לי את שם המשתמש ב‑GitHub והמאגר (או אשר/י לי ליצור אחד), ואני מבצע.
