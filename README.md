# 🔄 حاسبة المجموع المتكررة - Looping Sum Checker

برنامج متقدم يدمج بين الدوال `def` وحلقات التكرار `for` مع الشروط المتعددة. يقوم البرنامج بطلب رقمين وحساب مجموعهما، ويتكرر هذا الأمر مرتين تلقائياً (`range(2)`)، مع فحص النتيجة في كل مرة وطباعة مخرجات مخصصة بناءً على الناتج.

### 💻 كود البرنامج:
```python
def calculate_sum():
    a = float(input("Enter the first number: "))
    b = float(input("Enter the second number: "))
    return a + b

for i in range(2):
    sum_result = calculate_sum()
    print(f"Total: {sum_result}")
    if sum_result == 30:
        print("OK")
    else:
        print("OP")
