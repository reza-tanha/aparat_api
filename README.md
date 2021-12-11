# aparat_api
راهنمای استفاده از خدمات اپارات 


# ارگومان ها 

- token : (الزامی) شناسه منحصر به فرد هر کاربر 
- link : (برای سفارش الزامی) : لینک ویدیدو یا پروفایل جهت سفارش
- count : (برای سفارش الزامی) : تعداد درخواستی جهت سفارش
- type : (برای سفارش الزامی) : نوع سفارش شما که به سه قسمت تقسیم میشود
  - [like, view, follow]


## گرفتن اطلاعات و موجودی توکن :

```https://sec-gray.ir/aparat/api.php?token=f0e3a57a110e8fe192526ebebfc8962f```

## نحوه سفارش : 

### لایک
```https://sec-gray.ir/aparat/api.php?token=f0e3a57a110e8fe192526ebebfc8962f&link=https://www.aparat.com/v/Sg1CJ&count=100&type=like```


### ویو
```https://sec-gray.ir/aparat/api.php?token=f0e3a57a110e8fe192526ebebfc8962f&link=https://www.aparat.com/v/Sg1CJ&count=100&type=view```


### فالور
```https://sec-gray.ir/aparat/api.php?token=f0e3a57a110e8fe192526ebebfc8962f&link=https://www.aparat.com/v/Sg1CJ&count=100&type=follow```

