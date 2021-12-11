## راهنمای خدماتی وب سرویس اپارات
به صفحه راهنمای استفاده از سرویس خدماتی اپارات خوش امدید


## ارگومان ها 

- token : (الزامی) شناسه منحصر به فرد هر کاربر 
- link : (برای سفارش الزامی) : لینک ویدیدو یا پروفایل جهت سفارش
- count : (برای سفارش الزامی) : تعداد درخواستی جهت سفارش
- uniqid : (برای دیدن وضعیت سفارش الزامی) : بعد از هر سفارش یک ایدی یونیک برای ان سفارش ایجاد میشود جهت دیدن وضعیت سفارش
- type : (برای سفارش الزامی) : نوع سفارش شما که به سه قسمت تقسیم میشود
  - [like, view, follow]


## گرفتن اطلاعات و موجودی توکن :

```https://sec-gray.ir/aparat/api.php?token=f0e3a57a110e8fe192526ebebfc8962f```

```
{
  "token":"f0e3a57a110e8fe192526ebebfc8962f"
}

```

## نحوه سفارش : 
تمامی سفارشات با متود گت ارسال میشود.

### لایک
```https://sec-gray.ir/aparat/api.php?token=f0e3a57a110e8fe192526ebebfc8962f&link=https://www.aparat.com/v/abcd&count=100&type=like```

```
{
  "token":"f0e3a57a110e8fe192526ebebfc8962f",
  "link" : "https://www.aparat.com/v/abcde",
  "count": 500,
  "type": "like"
}

```

### ویو
```https://sec-gray.ir/aparat/api.php?token=f0e3a57a110e8fe192526ebebfc8962f&link=https://www.aparat.com/v/abcde&count=100&type=view```

```
{
  "token":"f0e3a57a110e8fe192526ebebfc8962f",
  "link" : "https://www.aparat.com/v/abcde",
  "count": 500,
  "type": "view"
}

```


### فالور
```https://sec-gray.ir/aparat/api.php?token=f0e3a57a110e8fe192526ebebfc8962f&link=https://www.aparat.com/v/abcde&count=100&type=follow```

```
{
  "token":"f0e3a57a110e8fe192526ebebfc8962f",
  "link" : "https://www.aparat.com/v/abcde",
  "count": 500,
  "type": "follow"
}

```

## وضعیت سفارش 
```https://sec-gray.ir/aparat/api.php?token=f0e3a57a110e8fe192526ebebfc8962f&uniqid=61b4cf4755e6g```

```
{
  "token":"f0e3a57a110e8fe192526ebebfc8962f",
  "uniqid" : "61b4cf4755e6g"
}

```


## ریسپانس

- status : در صورتی که سفارش شما ثبت شود درست و در صورتی که خطایی رخ دهد غلط میشود 

- message : پیغام متناسب با درخواست شما را نشان میدهد


## خطاها 

- ارگومان وارد شده اشتباه است : 
- تعداد سفارش داده شده از مقدار حساب شما بیشتر است . لظفا حساب خود را شارژ کنید
- تعداد وارد شده غیر مجاز است لطفا در بازه 50 تا 7000 وارد کنید
- invalid request : در صورتی که ارگومان های ورودی اشتباه باشد
- token invalid : در صورتی که توکن شما نامعتبر باشد



## پشتیبانی :
در صورتی که در هر مرحله مشکلی داشتید میتوانید به پشتیبانی پیام دهید.

- [کانال پشتیبانی](https://t.me/S3CURITY_GRAY)

- [ربات پشتیبانی](https://t.me/gray_support_bot)

- [ربات اصلی خدمات اپارات](https://t.me/aparaat_bot)






