# Hadasim_exe
אופן השימוש:
•	ע"מ להריץ את האפליקציה יש להתקין בפייתון את ספריות flask  ו- SQLAlchemy
ע"י הפקודות: pip install flask ו – pip install flask_sqlalchemy
 (אני השתמשתי בסביבת pycharm)
•	השתמשתי בסביבה של SQLite
אפשר להוריד את זה בקישור הבא: https://sqlitebrowser.org/dl/
•	הקובץ של מסד הנתונים נשמר בפרויקט בתוך תיקיה "instance"
•	הרצת האפליקציה מתבצעת דרך הקובץ main.py  - מריצים את הקובץ ואז מתקבלת כתובת HTTP
•	יש ללחוץ על הכתובת או להעתיק לדפדפן
לאחר מכן מגיעים לדף הבית שבו מוצגים כל שמות העובדים שנמצאים במערכת
בעמוד למעלה יש אפשרות של "הוספת עובד" ובלחיצה עליו מגיעים לדף חדש שבו מתבקשים למלא את כל פרטי העובד כולל חיסונים וקורונה
כאשר המשתמש לוחץ על הכפתור "הוסף" המערכת בודקת את תקינות הקלטים ונותנת הערות אם נדרש
במידה והקלטים תקינים המערכת מוסיפה את פרטי העובד למסד הנתונים והם כמובן מופיעים מיד בעמוד של הצגת העובדים.
