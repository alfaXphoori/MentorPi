# MentorPi M1 Training Plan (2.5 Days)
หลักสูตรการอบรมหุ่นยนต์ ROS2 สำหรับนักเรียน โดยใช้ Hiwonder MentorPi M1 (Monocular Camera Version)

## 📅 ตารางการอบรม

### **วันที่ 1: พื้นฐานหุ่นยนต์และการควบคุม (Getting Started & ROS2)**
*   **09:00 - 12:00 (ช่วงเช้า):** 
    *   **Intro:** ทำความรู้จักฮาร์ดแวร์ MentorPi M1 (Raspberry Pi 5, Mecanum Wheels, Lidar)
    *   **Setup:** การเชื่อมต่อ WiFi, การเข้าถึงผ่าน SSH และ Remote Desktop (VNC)
    *   **Docker:** เรียนรู้พื้นฐานการใช้งาน Docker Container และสภาพแวดล้อมของ Hiwonder
*   **13:00 - 16:00 (ช่วง afternoon):**
    *   **ROS2 Basics:** เข้าใจแนวคิด Node, Topic, Message และลองใช้ `teleop_twist_keyboard`
    *   **Movement:** ฝึกเขียนคำสั่งควบคุมล้อ Mecanum ให้เคลื่อนที่ 8 ทิศทาง
    *   **Workshop:** กิจกรรมแข่งขับหุ่นยนต์หลบหลีกสิ่งกีดขวาง (Manual Control)

### **วันที่ 2: โลกแห่งการมองเห็นและ AI (Vision & AI Intelligence)**
*   **09:00 - 12:00 (ช่วงเช้า):**
    *   **Computer Vision:** การดึงภาพจากกล้อง Monocular และทดลองใช้ OpenCV
    *   **MediaPipe:** Workshop การสั่งงานด้วยท่าทางมือ (Gesture Control) และการติดตามใบหน้า (Face Tracking)
*   **13:00 - 16:00 (ช่วง afternoon):**
    *   **Object Detection:** การใช้งาน YOLOv5/v11 เพื่อตรวจจับวัตถุและป้ายจราจร
    *   **Line Following:** การเขียนโปรแกรมให้หุ่นยนต์วิ่งตามเส้น (PID Control เบื้องต้น)
    *   **Workshop:** ภารกิจแยกแยะวัตถุตามสีและป้ายจราจร (Autonomous Logic)

### **วันที่ 3: การทำแผนที่และการแข่งขัน (SLAM & Final Challenge)**
*   **09:00 - 12:00 (ช่วงเช้า):**
    *   **Lidar & SLAM:** การใช้ Lidar สแกนพื้นที่เพื่อสร้างแผนที่ 2D (Cartographer/Gmapping)
    *   **Navigation:** การใช้ Navigation2 เพื่อสั่งให้หุ่นยนต์เคลื่อนที่ไปยังจุดเป้าหมายอัตโนมัติ
    *   **Final Challenge:** แข่งแข่งขันทำภารกิจรวม (วิ่งตามเส้น -> ตรวจป้าย -> จอดในโซนที่กำหนด)
*   **12:00 - 13:00:**
    *   สรุปบทเรียน, มอบเกียรติบัตร และปิดงาน

---

## 🛠️ สิ่งที่ต้องเตรียม (Checklist สำหรับวิทยากร)
1.  **SD Cards:** จัดเตรียม Image ที่ติดตั้ง Docker และ ROS2 ไว้พร้อมใช้งาน
2.  **Network:** เราเตอร์ WiFi ที่รองรับการเชื่อมต่อพร้อมกันจำนวนมาก
3.  **Safety:** ตรวจเช็คสภาพแบตเตอรี่ LiPo และอุปกรณ์ป้องกัน
4.  **Tools:** แนะนำให้นักเรียนใช้ **Foxglove Studio** หรือ **RViz2** เพื่อช่วยในการ Debug

---
*จัดทำโดย: วิทยากร MentorPi*
