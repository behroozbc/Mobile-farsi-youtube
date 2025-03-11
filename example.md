---
theme: ./
---

#  شروع با تم Slidev 

اسلایدهای ارائه برای توسعه دهندگان  

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" flex="~ justify-center items-center gap-2" hover="bg-white bg-opacity-10">
    برای رفتن به صفحه بعدی Space را فشار دهید <div class="i-carbon:arrow-right inline-block"/>
  </span>
</div>


---

# Slidev چیست؟

Slidev یک ابزار ساخت اسلاید و ارائه برای توسعه دهندگان است. ویژگی های آن عبارتند از:

- 📝 **متن محور** - روی محتوای خود با Markdown تمرکز کنید و بعداً آن را سبک‌دهی کنید
- 🎨 **قابل شخصی‌سازی** - تم ها قابل اشتراک گذاری و مجدداً استفاده به صورت بسته‌های npm هستند
- 🧑‍💻 **دوستدار توسعه دهندگان** - پر رنگ کردن کد، کدنویسی زنده با تکمیل خودکار
- 🤹 **هم افزا** - اجزای Vue را برای تقویت بیان خود درج کنید
- 🎥 **ثبت صدا** - ضبط داخلی و نمایش دوربین
- 📤 **قابل حمل** - صادر به PDF، PPTX، PNG ها یا حتی یک SPA میزبان پذیر
- 🛠 **قابلیت تغییر** - تقریباً هر چیزی که در وب سایت امکان‌پذیر است در Slidev نیز امکان‌پذیر است

<br>
<br>

بیشتر در مورد [چرا Slidev؟](https://sli.dev/guide/why) مطالعه کنید

---

# ناوبری

برای مشاهده پنل کنترل ناوبری روی گوشه پایین چپ قرار دهید


## Keyboard Shortcuts

|     |     |
| --- | --- |
| <kbd>space</kbd> / <kbd>tab</kbd> / <kbd>right</kbd> | انیمیشن بعدی یا اسلاید |
| <kbd>left</kbd>  / <kbd>shift</kbd><kbd>space</kbd> | انیمیشن قبلی یا اسلاید |
| <kbd>up</kbd> | اسلاید قبلی |
| <kbd>down</kbd> | اسلاید بعدی |

---
layout: image-right
image: https://cover.sli.dev
---

# کد

از قطعات کد و پر رنگ کردن مستقیم استفاده کنید!

```ts
interface User {
  id: number
  firstName: string
  lastName: string
  role: string
}

function updateUser(id: number, update: Partial<User>) {
  const user = getUser(id)
  const newUser = { ...user, ...update }
  saveUser(id, newUser)
}
```

---
layout: center
class: "text-center"
---

# اطلاعات بیشتر

[مستندات](https://sli.dev) / [مخزن گیت هاب](https://github.com/slidevjs/slidev)