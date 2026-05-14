# Pro-Dashboard
UI Website

แดชบอร์ดสำหรับจัดการระบบหนังสือและข้อมูลภายในร้าน ออกแบบด้วย Figma โดยเน้นความทันสมัย ใช้งานง่าย และรองรับการแสดงผลที่เป็นระเบียบเหมาะกับระบบจัดการข้อมูล

## Figma Design

ดูงานออกแบบได้ที่ : (https://www.figma.com/design/NCBg24kFyNLNxW0G2bwxk4/Bookband-prodashboard?node-id=1-2&t=wRufTwLQS1V8y5ua-1)


## ฟีเจอร์หลัก

* ระบบจัดการข้อมูลสต็อคสินค้า
* หน้า Dashboard แสดงสถิติและข้อมูลภาพรวม
* ระบบติดตามกิจกรรมและข้อมูลต่าง ๆ
* ระบบค้นหาและกรองข้อมูล
* รองรับแนวคิด Responsive Design
* UI/UX เรียบง่าย ทันสมัย ใช้งานสะดวก
* ใช้งาน Components และ Auto Layout ใน Figma


## เครื่องมือที่ใช้

* Figma
* Auto Layout
* Components & Variants
* Design System


## โครงสร้างภายในโปรเจกต์

```bash
Bookband-prodashboard/
│
├── Dashboard Overview
├── Analytics Section
├── Book Management
├── UI Components
└── Responsive Layout
```


## จุดประสงค์ของโปรเจกต์

โปรเจกต์นี้ถูกสร้างขึ้นเพื่อ:

* พัฒนาทักษะด้าน UI/UX Design
* ออกแบบ Dashboard สำหรับระบบร้านขายของ/ร้านค้าส่ง
* ฝึกการจัดวางข้อมูลให้อ่านง่ายและใช้งานสะดวก
* สร้างระบบดีไซน์ที่สามารถนำไปต่อยอดได้


## กลุ่มผู้ใช้งานเป้าหมาย

* เจ้าของร้านขายของ/ร้านค้าส่ง
* ระบบจัดการสต็อกสินค้า
* ผู้ดูแลระบบ (Admin)
* โปรเจกต์ฝึกออกแบบ UI/UX


## Preview

สามารถดู Prototype และหน้าจอทั้งหมดได้ผ่าน Figma


## Typography (รูปแบบตัวอักษร)

ระบบตัวอักษรของ BookBand Pro Dashboard ใช้ Font : Poppins และถูกออกแบบให้มีความเรียบง่าย อ่านง่าย และเหมาะกับการใช้งานบน Dashboard โดยเลือกใช้ลำดับขนาดตัวอักษร (Hierarchy) เพื่อช่วยให้ผู้ใช้งานสามารถแยกความสำคัญของข้อมูลได้ชัดเจน

### Type Scale

| Type Style | Weight   | Size  |
| ---------- | -------- | ----- |
| Display 1  | SemiBold | 40 px |
| Headline 1 | SemiBold | 24 px |
| Headline 2 | SemiBold | 18 px |
| Headline 3 | SemiBold | 14 px |
| Body       | Regular  | 13 px |
| Button     | SemiBold | 14 px |

### แนวคิดการออกแบบ Typography

* ใช้ **SemiBold** สำหรับหัวข้อ เพื่อเพิ่มความโดดเด่นและช่วยให้มองเห็นได้ง่าย
* ใช้ **Regular** สำหรับเนื้อหาปกติ เพื่อให้อ่านสบายตา
* ขนาดตัวอักษรถูกจัดลำดับอย่างชัดเจน เพื่อสร้าง Visual Hierarchy
* ปุ่ม (Button) ใช้ตัวอักษร SemiBold เพื่อเพิ่มความชัดเจนในการกดใช้งาน


## Color System (ระบบสี)

ชุดสีของ BookBand Pro Dashboard ถูกออกแบบให้มีความทันสมัย สะอาดตา และเหมาะกับระบบ Dashboard โดยเน้นโทนสีฟ้า เทา และสีสถานะต่าง ๆ เพื่อช่วยให้ผู้ใช้งานเข้าใจข้อมูลได้ง่ายขึ้น

### Primary Colors

| Color       | Hex Code 
| ----------- | --------- 
| Light Blue  | `#DEF1FF` 
| Blue        | `#5C8FBC`
| Bright Blue | `#1F73E6` 
| Dark Blue   | `#0056A1` 
| Navy Blue   | `#1C5097` 
| Deep Navy   | `#252F6D` 


### Neutral Colors

| Color       | Hex Code  
| ----------- | --------- 
| White       | `#FFFFFF` 
| Soft Gray   | `#F2F3F7` 
| Light Gray  | `#FCFCFC` 
| Border Gray | `#EDEDED` 
| Gray        | `#D4D4D4` 
| Medium Gray | `#BFBEBE` 
| Dark Gray   | `#676767` 
| Deep Gray   | `#5B5B5B` 
| Black       | `#000000` 
| Dark Black  | `#1E1E1E` 


### Status Colors

| Color  | Hex Code  
| ------ | --------- 
| Orange | `#DD3A03` 
| Red    | `#FF0000` 
| Green  | `#2C8F43` 


## Design Principle

แนวทางการออกแบบของโปรเจกต์นี้เน้น:

* ความเรียบง่าย (Minimal)
* อ่านง่ายและใช้งานสะดวก
* สีช่วยแยกประเภทข้อมูลอย่างชัดเจน
* รองรับการขยายระบบในอนาคต
* มีความสม่ำเสมอของ UI ทั้งระบบ (Consistency)


## สิ่งที่สามารถพัฒนาต่อได้

* เพิ่ม Dark Mode
* เพิ่ม Animation ใน Prototype
* รองรับเวอร์ชันมือถือ
* เชื่อมต่อกับระบบฐานข้อมูลจริง
* พัฒนาเป็นเว็บไซต์


## License

โปรเจกต์นี้จัดทำขึ้นเพื่อการศึกษาและใช้ใน Portfolio เท่านั้น


## ผู้จัดทำ

Aumaim Kanokpit
