<div dir="rtl">

# פיץ׳ — כל שיחות קלוד־קוד במסך אחד

**זה לא קלוד־דסקטופ. זה קלוד־קוד עצמו, עם מסכה אחרת.**

פיץ׳ אינו עוטף את קלוד־קוד ואינו מחליף אותו. כל שורה במדף היא מסוף
אמיתי שרץ באמת. פיץ׳ קורא את קובצי־השיחה ואת מסך־המסוף, מראה לך מה
קורה, ומזריק את התשובה שלך בחזרה לאותו מסוף. אפשר לחזור למסוף בכל
רגע, ושום דבר לא הולך לאיבוד — זו אותה שיחה, רק מזווית אחרת.

בלי מודל, בלי שרת, בלי חשבון.

## להוריד

**[הגרסה האחרונה ←](https://github.com/asafsufush/peach/releases/latest)**

מערכת 12 ומעלה · מעבד אפל · פחות ממגה · חתום ומאושר אצל אפל, ונפתח
בלחיצה כפולה.

## מה יש בו

| | |
|---|---|
| **מדף** | כל מסוף בשורה — מספר־עמדה, מצב, מודל, גודל־הקשר, והמשפט האחרון |
| **שאלה נענית בלחיצה** | כשקלוד שואל, השאלה והאפשרויות מופיעות כאן, ולחיצה עונה במסוף ההוא |
| **תשובה בלי להיכנס** | ״תמשיך״ · ״נסה שוב״ ישר מהשורה |
| **חיפוש** | בכל מה שנאמר אי־פעם, גם בשיחות שנסגרו |
| **מסמכים ותמונות** | נפתחים בתוך השיחה |
| **סוכני־רקע** | מה כל אחד עושה ברגע זה |
| **שחזור** | שיחות שנסגרו חוזרות לחלונות־מסוף |

## עברית שנקראת נכון

המסוף של אפל מיישם שגוי את האלגוריתם הדו־כיווני. מילה לועזית אחת בין
שתי מילים עבריות — שם־קובץ, דגל, שם־חבילה, כלומר רוב מה שסוכן־קוד
מדפיס — גוררת איתה חלק מהשורה, ואתה קורא את המשפט בסדר אחר מזה שנכתב.
זו אינה בעיית־גופן אלא בעיית־סדר.

פיץ׳ מרנדר את אותם הבתים במנוע של דפדפן, שנושא מימוש מלא ובדוק של
האלגוריתם. עברית, ערבית, פרסית, אורדו, יידיש, דיבהי וסינדהי.

## כמה זה עולה

**חינם, וזה נשאר ככה.** יש כפתור־תרומה, ושום דבר לא נמנע ממי שלא לוחץ עליו.

## ⛔ מה שאין

- **בלי שרת ובלי חשבון.** הוא קורא קבצים מקומיים. שום דבר לא יוצא החוצה.
- **בלי מדידה ובלי איסוף.**
- **קוד־המקור אינו כאן.** המאגר הזה הוא מקום ההורדה ומקום הדיווח.

## מצאת באג

[פתח דיווח](https://github.com/asafsufush/peach/issues) — עם גרסת־המערכת
ומה שקרה.

---

</div>

## Peach — every Claude Code session on one screen

**This is not Claude Desktop. This is Claude Code itself, wearing a different face.**

Peach does not wrap or reimplement Claude Code, and adds no model, no server
and no account. Every row is a real terminal running real `claude`. Peach reads
the session files and the terminal screen, shows you what is happening, and
injects your answer back into that same terminal. Drop back to the terminal at
any moment and nothing is lost.

**[Download the latest release →](https://github.com/asafsufush/peach/releases/latest)**

macOS 12 or later · Apple silicon · under a megabyte · signed and notarised by
Apple, so it opens on a double-click.

- **One rack** — every open terminal on one line: station, state, model, context, last sentence.
- **Questions answered in one click** — when Claude asks, the options appear here and clicking answers in that terminal.
- **Search everything** ever said, including sessions whose terminals are closed.
- **Background agents** — what each one is doing right now.
- **Restore** closed sessions back into terminal windows.

### Right-to-left text that reads correctly

Apple's Terminal implements the Unicode bidirectional algorithm incorrectly. One
Latin word between two Hebrew or Arabic words — a filename, a flag, a package
name — drags part of the line with it, and you read the sentence in an order it
was not written in. Not a font problem, an ordering problem. Peach renders the
same bytes in a browser engine, which carries a complete implementation.

Hebrew, Arabic, Persian, Urdu, Yiddish, Dhivehi, Sindhi.

### What it costs

**Free, and it stays free.** There is a donate button and nothing is withheld
from anyone who skips it.

No server, no account, no telemetry — it reads local session files and nothing
leaves the machine. Source is not published; this repository is the download and
the issue tracker.

Interface in English and Hebrew.

[peach.dev-stuff.org](https://peach.dev-stuff.org)
