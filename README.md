🍽️ Recipe API App

แอป Flutter สำหรับดึง ตำรับอาหารไทย จาก API และแสดงเมนูอาหาร พร้อมรายละเอียดส่วนผสมและวิธีทำ

✨ ฟีเจอร์หลัก

✅ ดึงข้อมูลตำรับอาหารไทยจาก API

✅ แสดงรายชื่อเมนูอาหารพร้อมรูปภาพ

✅ กดดูรายละเอียดเมนู: ส่วนผสม + วิธีทำ

✅ ออกแบบด้วย Flutter Material Design

📦 การติดตั้ง

Clone โปรเจกต์

git clone https://github.com/yourusername/recipe_api.git

เข้าสู่โฟลเดอร์โปรเจกต์

cd recipe_api

ติดตั้ง dependencies

flutter pub get

รันแอป

flutter run

API ที่ใช้

TheMealDB - Thai Recipes

📂 โครงสร้างโปรเจกต์

lib/
├── main.dart # จุดเริ่มต้นของแอป
├── screens/
│ ├── recipe_screen.dart
│ ├── recipe_detail_screen.dart
├── services/
│ └── api_service.dart

🛠 Dependencies

Flutter SDK ^3.6.2

http ^0.13.6

cupertino_icons ^1.0.8

✅ ตัวอย่างการใช้งาน API

final response = await http.get(
    
Uri.parse('https://www.themealdb.com/api/json/v1/1/filter.php?a=Thai')
);