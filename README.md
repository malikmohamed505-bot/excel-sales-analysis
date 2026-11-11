# Pizza Sales Dashboard

## 1. فهم البيانات - Data Understanding
- فهمت الجداول: Orders, Order Details, Pizzas, Pizza Types
- عرفت العلاقات بينهم بـ OrderID و PizzaID
- حددت الـ KPIs اللي هتظهر في الداشبورد

## 2. تنظيف البيانات - Data Cleaning
- مسحت القيم الفارغة والمكررة
- ظبطت صيغة التاريخ والسعر
- عملت عمود Total Price = Quantity * Price

## 3. عمل المقاييس - Measures / DAX
- Total Revenue = SUM(Total Price)
- Total Orders = DISTINCTCOUNT(OrderID)
- Total Pizzas Sold = SUM(Quantity)
- Average Order Value = Total Revenue / Total Orders

## 4. بناء الداشبورد - Dashboard Design
- KPI Cards: إجمالي المبيعات، عدد الطلبات، عدد البيتزا المباعة، متوسط قيمة الطلب
- Bar Chart: المبيعات حسب نوع البيتزا
- Line Chart: المبيعات على مدار الشهور
- Pie Chart: المبيعات حسب الفئة (Classic, Veggie, Supreme, Chicken)
- Table: أفضل 5 أنواع بيتزا مبيعا
- عملت Slicers للفلترة حسب الشهر والفئة والحجم

## 5. النتائج - Insights
- أكتر نوع بيتزا مبيعا هو:
- أكتر شهر فيه مبيعات هو:
- فئة Classic هي الأعلى في المبيعات بنسبة:
