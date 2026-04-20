# Stocktaking Link Redirect

דף redirect שפותח את אפליקציית "ספירת מלאי" מתוך SMS/ווטסאפ.

## איך זה עובד
- משתמש לוחץ על `https://xxx.vercel.app/w/TOKEN` בהודעה
- הדף מבצע redirect ל-`stocktaking://worker/TOKEN`
- אנדרואיד פותח את האפליקציה ישירות במסך סריקה
