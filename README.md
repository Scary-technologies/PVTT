# V-T-T: تبدیل صدا به متن

این پروژه یک برنامه تبدیل صدا به متن با استفاده از پایتون است. این برنامه از کتابخانه‌های PyQt5 برای رابط کاربری و SpeechRecognition برای تشخیص صدا استفاده می‌کند.

## ویژگی‌ها

- تشخیص صدا به زبان فارسی
- نمایش متن تشخیص داده شده در رابط کاربری
- ارسال متن به پنجره فعال
- نمایش وضعیت شنیدن به صورت دایره‌ای با دو رنگ سبز و قرمز

## پیش‌نیازها

برای اجرای این برنامه، نیاز به نصب کتابخانه‌های زیر دارید:

- PyQt5
- SpeechRecognition
- pyperclip
- pyautogui
- pygetwindow

## نصب

1. کلون کردن مخزن:
    ```sh
    git clone https://github.com/Scary-technologies/V-T-T.git
    cd V-T-T
    ```

2. نصب پیش‌نیازها:
    ```sh
    pip install -r requirements.txt
    ```

## اجرا

برای اجرای برنامه، دستور زیر را در ترمینال اجرا کنید:
```sh
python main.py
