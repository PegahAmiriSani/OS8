# OS8
Q1)
1) chmode 397
اين دستور معتبر نيست زيرا فقط اعداد ٠ تا ٧ براى دستورات استفاده ميشود و ٩ در اين بازه نيست.
2) chmode 440
براى كاربر امكان خواندن را فراهم ميكند.
3) chmode a=rx file1
به كاربر و يا گروه امكان خواندن file1 را ميدهد، انا قابلين اجرا ندارد.
4)chmode g=w sample
به كاربر و يا گروه قابليت نوشتن در فايل sample را ميدهد اما خواندن و اجرا كردن امكان پذير نيست.
5) chmode r+x sample
اين دستور نامعتبر است.
6) chmode u+g test
سطح دسترسى فايل test تغييرى نميكند.
********************************************************************
Q2)
chmode —recursive  
سطح دسترسى دايركتورى ها به صورت بازگشتى تغيير ميكند.
chmode -v
اگر در دسترسى هاى فايل مد نظر تغييرى ايجاد شود، ان ها را نشان ميدهد.
chmode -r
سطح دسترسى دايركتورى ها به صورت بازگشتى تغيير ميكند.
chmode —version
نمايش دهنده اطلاعات ورژن است.
Chmode -f
كاهش دهنده پيام هاى خطاست.
