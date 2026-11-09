<div dir="rtl" align="right">

<h1 dir="rtl">shinantam-AI</h1>

<p dir="rtl">שלד ראשוני ל־Plugin ללימוד ולשינון מקורות תורניים בעברית.</p>

<h2 dir="rtl">מבנה</h2>

<ul dir="rtl">
  <li><code dir="ltr">plugin.json</code> — מזהה החבילה, הגרסה והתיאור שלה.</li>
  <li><code dir="ltr">skills/shinantam-study/SKILL.md</code> — כאן כותבים את הוראות הלימוד והשיחה. השארתי בקובץ כותרת ומקום לתוכן שלך.</li>
</ul>

<h2 dir="rtl">איך ממשיכים</h2>

<ol dir="rtl">
  <li>כתוב את הוראות הלימוד בתוך <code dir="ltr">SKILL.md</code>. אפשר להשאיר את השדות <code dir="ltr">name</code> ו־<code dir="ltr">description</code> שבתחילת הקובץ, או לעדכן אותם.</li>
  <li>אחרי שתשלים את ה־Skill, ארוז את תיקיית <code dir="ltr">shinantam-AI</code> כקובץ ZIP כדי לייבא או להעביר את ה־Plugin.</li>
  <li>לבדיקה מקומית ב־ChatGPT Desktop, אפשר להשתמש ב־<code dir="ltr">@plugin-creator</code> כדי לחבר את התיקייה ל־Marketplace מקומי, להתקין את ה־Plugin ולנסות אותו בצ'אט חדש. אפשר גם להוסיף את התיקייה ל־Marketplace של המאגר שבו עובדים.</li>
  <li>לפני פרסום לכלל המשתמשים, יש להשלים בפורטל הפרסום את פרטי המפתח ואת פרטי האתר ומדיניות הפרטיות הנדרשים, בהתאם לאופן ההפצה.</li>
</ol>

<h2 dir="rtl">מה כלול כרגע</h2>

<p dir="rtl">החבילה כוללת Skill בלבד. אין בה שרת MCP, מאגר טקסטים, שמירת התקדמות או כלי לשליפת מקורות. אפשר להוסיף רכיבים כאלה בהמשך אם תרצה שה־Plugin ישלוף נוסחים ממאגר מוסמך או יזכור התקדמות בין שיחות.</p>

<h2 dir="rtl">עמודי האתר</h2>

<p dir="rtl">בתיקיית השורש נמצאים עמודי אתר סטטיים המיועדים ל־GitHub Pages: דף הבית, תמיכה, מדיניות פרטיות ותנאי שימוש. כתובות העמודים וקישור התמיכה מוגדרים לפי המאגר <code dir="ltr">amielboim/shinantam-ai</code>. יש להפעיל GitHub Pages במאגר כדי שהעמודים יהיו זמינים לציבור.</p>

<h2 dir="rtl">תיעוד סשן לימוד</h2>

<p dir="rtl">ה־MCP מוגדר בקובץ <code dir="ltr">mcp.json</code> ומתחבר ל־Worker ב־Cloudflare. הכלי <code dir="ltr">record_learning_session</code> רושם סיכום לימוד ללוגים בלבד, ורק לאחר הסכמה מפורשת. הוא משתמש במזהי המשתמש והשיחה האנונימיים ש‑ChatGPT מעביר ב־<code dir="ltr">_meta</code>; המשתמש אינו מתבקש להזין כינוי. אין מסד נתונים, ואין לכלול בסיכום מידע אישי או את נוסח המקור המלא.</p>

</div>
