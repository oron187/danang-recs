# המלצות דה נאנג — danang-recs

ריכוז ההמלצות של החבר'ה הישראלים בדה נאנג.
אתר סטטי בקובץ אחד, עם Supabase כבסיס נתונים ו-Vercel לאירוח.

- `index.html` — כל האתר: HTML, CSS ו-JS בקובץ אחד. זה הקובץ שמוגש בפרודקשן.
- בסיס הנתונים: Supabase (טבלאות `places`, `comments`, `feedback`), מוגן ב-Row Level Security.
- המפתח שמופיע בקובץ הוא ה-anon key הציבורי של Supabase — הוא נועד להיות גלוי, וההרשאות נאכפות בצד השרת.

כל push ל-main מפעיל דיפלוי אוטומטי ב-Vercel.
