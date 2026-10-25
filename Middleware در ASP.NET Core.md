
تعریف:
هر درخواستی که به اپلیکیشن میاد ← از یه Pipeline عبور می‌کنه که یه زنجیره از Middlewareهاست.

رفتار هر Middleware:
Request رو پردازش می‌کنه

next() رو صدا می‌زنه ← می‌ره به Middleware بعدی

بعد از برگشت از next() ← Response رو پردازش می‌کنه

یا Short-circuit می‌کنه ← اگه next() صدا نزنه ← Response همون‌جا تموم می‌شه
