# Practice-2
# ==================
# حلقه for
# ==================

# ۱ - چاپ اعداد ۱ تا ۵
for i in range(1, 6):
    print(i)

# ۲ - چاپ اعداد زوج
for i in range(0, 11, 2):
    print(i)

# ۳ - جمع اعداد ۱ تا ۱۰۰
total = 0
for i in range(1, 101):
    total += i
print(total)

# ۴ - چاپ حروف یه کلمه
for char in "Saman":
    print(char)

# ==================
# حلقه while
# ==================

# ۵ - شمارش معکوس
n = 5
while n > 0:
    print(n)
    n -= 1

# ۶ - تا زمانی که کاربر exit بنویسه
while True:
    text = input("چیزی بنویس (exit برای خروج): ")
    if text == "exit":
        break
    print("نوشتی:", text)

# ==================
# تمرین
#this is new update
# ==================

# جدول ضرب عدد ۳
for i in range(1, 11):
    print(f"3 x {i} = {3*i}")
