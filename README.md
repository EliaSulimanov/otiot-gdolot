# אותיות גדולות לשפה עברית (Capital Letters for Hebrew) v0.1
## תיור כללי 
ברוב שפות העולם יש אותיות גדולות, כמעצב אני יכול להגיד שטקסטים הרשומים באותיות גדולות טובים יותר לקריאה בגלל ההבדלה בין סוף משפט ושמות עצם. 

בשפה העברית אין אותיות גדולות וחשבתי שצריך להיות פונט שיתן את האפשרות הזאת, זה בהחלט יכול לתת גיוון לשפה וגם הרבה יותר נוח  להשתמש. 

<a href="http://otiot.artrayd.com" target="_blank">http://otiot.artrayd.com</a>

##שימוש ב-WEB

חיבור פונט ב-CSS
````css
@font-face {
    font-family: "OtiotGdolot";
    src: url("font/OtiotGdolot.ttf") format("truetype");
}

body,html{
	font-family: "OtiotGdolot", arial, helvetica
}
````

!חשוב
שימו לב, אותיות גדולות עובדור רק בתוך תגיות של p ו-h1,2,3,4

גם צריך להוסיף rtl עם css
````css
p, h1,h2,h3,h4,h5{
	direction: rtl;
}
````

##פרטים טכנים

פונט נוצר על בסיס Noto Hebrew עם תוכנה חינמית
<a href="http://www.cr8software.net/typelight.html" target="_blank">Type Light.

זאת גרסה ראשונה, אין לי ניסיון גדול בעיצוב פונטים ואני אשמח לכל אחד/ת שיצטרף לפרויקט. הפונט הזה הינו חינמי וכל אחד יכול להשתמש לכל מטרה ולשנות אותו לפי צרכיו של אותו משתמש.

