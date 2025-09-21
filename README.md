# ⏱️ Minecraft Timer Plugin

Plugin นี้เป็นระบบ **จับเวลาใน Minecraft** รองรับ **Spigot/Paper 1.21.8**  
สามารถแสดงผลได้ทั้ง **BossBar** และ **Scoreboard**

---

## ⚡ ฟีเจอร์
- คำสั่ง
  - `/starttimer` → เริ่มจับเวลา
  - `/stoptimer` → หยุดจับเวลา
  - `/resettimer` → รีเซ็ตเวลา
- เลือกแสดงผลผ่าน BossBar หรือ Scoreboard
- ปรับแต่งได้ใน `config.yml`

---

## 🔧 การติดตั้ง
1. ดาวน์โหลดไฟล์ `.jar` (build จาก Maven)
2. วางในโฟลเดอร์ `plugins/`
3. รันเซิร์ฟเวอร์ Minecraft 1.21.8
4. แก้ไข `config.yml` ตามต้องการ

---

## 🛠️ Build ด้วย Maven
```bash
mvn clean package
