به نام خداوند جان و خرد

نام و نام خانوادگی	تاریخ آزمایش	شماره آزمایش
مینا زواری	چهارشنبه 22 اسفند	آزمایش شماره 7


عنوان: 
طراحی و پیاده‌سازی مدار شبیه‌ساز تاس با استفاده از آردوینو
هدف آزمایش:
هدف اصلی این آزمایش، طراحی و پیاده‌سازی یک مدار شبیه‌ساز تاس با استفاده از برد آردوینو و شش عدد لامپ LED که نمایانگر اعداد 1 تا 6 بر روی تاس هستند.
تئوری آزمایش:
•	برد آردوینو UNO: این برد یک میکروکنترلر است که می‌تواند ورودی‌ها را از طریق پین‌های خود دریافت کرده و خروجی‌ها را کنترل کند. در این آزمایش، از پین‌های دیجیتال آردوینو برای کنترل لامپ‌های LED استفاده می‌شود.
•	لامپ LED: این قطعه یک دیود نورگسیل است که با عبور جریان الکتریکی از آن، نور تولید می‌کند.
•	مقاومت: برای محدود کردن جریان عبوری از LED و جلوگیری از سوختن آن، از یک مقاومت استفاده می‌شود.
•	کلید فشاری: از یک کلید فشاری برای ایجاد یک رویداد (فشردن کلید) و تولید یک عدد تصادفی استفاده می‌شود.
•	تولید عدد تصادفی: با استفاده از تابع random() در آردوینو، یک عدد تصادفی بین 2 تا 7 (برای نمایش اعداد 1 تا 6) تولید می‌شود و سپس LED های مربوطه روشن می‌شوند.




شرح مدار و قطعات مورد استفاده:
•	برد آردوینو UNO
•	6 عدد لامپ  LED 
•	6 عدد مقاومت (180 اهم)
•	یک عدد کلید فشاری
•	سیم‌های مخابراتی
•	برد بورد

روش انجام آزمایش:

روش انجام آزمایش:
1.	اتصالات سخت افزاری:
o	لامپ‌های LED را روی برد بورد قرار می‌دهیم .
o	یک سر مقاومت‌ها را به پایه کاتد (پایه کوتاه تر) هر یک از LED ها متصل می‌کنیم.
o	سر دیگر مقاومت ها را با استفاده از سیم مخابراتی به یک ردیف مشترک روی برد بورد متصل می‌کنیم.
o	ردیف زمین LED ها را با یک سیم قهوه ای به پین زمین (GND) برد آردوینو متصل می‌کنیم.








o	پایه آند (بلند تر) مربوط به هر LED را با استفاده از سیم مخابراتی به پین‌های دیجیتال 2، 3، 4، 5، 6 و 7 برد آردوینو متصل می‌کنیم. به طور دقیق از سمت راست: 
	LED  اول به پین 2 برد آردیونو متصل می شود (سیم قرمز).
	LED  دوم به پین 3 برد آردیونو متصل می شود (سیم آبی).
	LED  سوم به پین 4 برد آردیونو متصل می شود (سیم نارنجی).
	LED  چهارم به پین 5 برد آردیونو متصل می شود (سیم زرد).
	LED  پنجم به پین 6 برد آردیونو متصل می شود (سیم سفید).
	LED  ششم به پین 7 برد آردیونو متصل می شود (سیم سبز).

o	یک سر کلید فشاری را به زمین و سر دیگر آن را به پین reset برد آردیونو متصل می کنیم. 






	








2. برنامه نویسی آردوینو: 
o	برنامه آردوینو IDE را باز کنید.
o	کدهای زیر را در آن وارد کنید:









نتیجه گیری:
نتیجه‌گیری کلی آزمایش: در این آزمایش، هدف، طراحی و پیاده‌سازی یک مدار شبیه‌ساز تاس با استفاده از برد آردوینو و شش لامپ LED بود. نتایج به دست آمده نشان می‌دهد که:
•	مدار طراحی شده به درستی عمل می‌کند و با فشردن کلید، یک عدد تصادفی بین 1 تا 6 تولید شده و LED های متناظر با آن عدد بر روی برد بورد روشن می‌شوند و نمایانگر نتیجه پرتاب تاس هستند.
•	با استفاده از برد آردوینو و لامپ‌های LED، می‌توان یک شبیه‌ساز تاس ساده و تعاملی ایجاد کرد.
•	کدهای نوشته شده برای آردوینو به درستی عمل کرده و با تولید اعداد تصادفی و کنترل پین‌های خروجی، خروجی مورد نظر (نمایش عدد تاس) را تولید می‌کنند.
•	این آزمایش نشان می‌دهد که می‌توان با استفاده از برد آردوینو و قطعات الکترونیکی ساده، مدارهای سرگرم‌کننده و کاربردی با قابلیت تعامل (از طریق کلید) طراحی و پیاده‌سازی کرد.





![dice](https://github.com/user-attachments/assets/1a2ce3a3-fca9-487a-acd7-2c32542262d9)
[dice.pdf](https://github.com/user-attachments/files/19659043/dice.pdf)


https://github.com/user-attachments/assets/b0da8b74-d3e3-4ec1-88cd-82584d967d7e

![1](https://github.com/user-attachments/assets/ce34ef3d-b77a-4e75-a4e3-92f3f04d33d4)

