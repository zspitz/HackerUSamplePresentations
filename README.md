# מצגות לדוגמא עבור HackerU

מאגר זה מכיל מצגות לדוגמא עפ מערך השיעורים. (כרגע רק של JavaScript).

מגמות:

* התוכן עצמו יהיה כתוב ב-Markdown
* ה-Markdown ייהפך למצגת באמצעות [remark](https://github.com/gnab/remark)
* עדכון ה-CSS להשתמש ב-template של HackerU
* יצירת דפים סטטיים הניתנים לשמירה, באמצעות Jekyll ו-GitHub Pages
* GitHub Action ליצור מסמך Word בכל קומיט, ולשמור ב-Releases
* GitHub Action ליצור מצגת PowerPoint עם אותו תוכן, ולשמור ב-Releases עם כל קומיט
* העלאת קבצים אלו האחרונים ל-Drive המשותף
* האחרונים יתבצעו ע"י Pandoc ו-filter ייעודי לצורך זה (כרגע, גם מצגות וגם מסמכי Word שעוברים ב-Pandoc מסתבכים לגמרי ב-RTL)

# הנחיות לכתיבת ה-Markdown

* תיקית src המכילה בעצמה מספר תיקיות
* כל תת-תיקיה תכיל קובץ Markdown עם התוכן הנצרך לאותו קובץ
* תיקיות שורש נוספים עבור קבצים נוספים -- ה-JavaScript וה-CSS שישמשו את Jekyll ליצור דפים סטטיים, filters של Pandoc
