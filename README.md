# Gold Token on XRP Ledger (XRPL)

![Project Status](https://img.shields.io/badge/status-in%20development-yellow)
![License](https://img.shields.io/badge/license-MIT-blue)

## 📖  (About The Project)

ໂປເຈັກນີ້ຄືການສ້າງລະບົບ Proof-of-Concept (PoC) ສຳລັບການສ້າງ ແລະ ຈັດການໂທເຄນດິຈິຕອນ (IOU) ທີ່ຜູກກັບມູນຄ່າທອງຄຳ ໂດຍເຮັດວຽກຢູ່ເຄື່ອຂ່າຍ  **XRP Ledger (XRPL)** ເຊີ່ງມີຈຸດເດັ່ນເລື່ອງຄວາມໄວໃນການທຸລະກຳທີ່ສູງ ແລະ ຄ່າທຳນຽມທີ່ຕ່ຳຫຼາຍ

ເປົ້າໝາຍຫຼັກຂອງໂປຣເຈັກນີ້ຄືການສືກສາ ແລະ ລົງມືປະຕິບັດຈິງກັບເຕັກໂນໂລຊີ Web3, ການພັດທະນາ Backend API ສຳລັບການຕອບໂຕ້ກັບ Blockchain, ແລະການສ້າງ  Full-Stack Application ທີ່ສົມບູນ

## ✨ ຄຸນສົມບັດຫຼັກ (Core Features)

-   [x] **สร้างและกำหนดค่าโทเคน (Issue Token):** สร้าง "Gold Token" (IOU) จากบัญชีผู้ออก (Issuer Account)
-   [x] **สร้างความเชื่อใจ (Trust Line):** เปิดใช้งาน Trust Line จากบัญชีผู้ใช้เพื่อรับโทเคน
-   [x] **ส่ง/โอนโทเคน (Send Token):** โอนโทเคนระหว่างบัญชีผู้ใช้บนเครือข่าย XRPL
-   [ ] **ตรวจสอบยอดคงเหลือ (Check Balance):** API สำหรับตรวจสอบยอดโทเคนคงเหลือในบัญชีใดๆ
-   [ ] **หน้าเว็บสำหรับผู้ใช้ (Simple UI):** หน้าเว็บอย่างง่ายที่สร้างด้วย Vue.js เพื่อให้ผู้ใช้สามารถโต้ตอบกับฟังก์ชันต่างๆ ได้

## 🛠️ ເຕັກໂນໂລຊີທີ່ໃຊ້  (Tech Stack)

<table>
  <tr>
    <td align="center"><strong>Backend</strong></td>
    <td align="center"><strong>Frontend</strong></td>
    <td align="center"><strong>Database</strong></td>
    <td align="center"><strong>Tools & Others</strong></td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
      <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js">
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
      <img src="https://img.shields.io/badge/xrpl.js-00A5E2?style=for-the-badge" alt="xrpl.js">
    </td>
    <td align="center">
      <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue.js">
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
    </td>
    <td align="center">
      <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB">
    </td>
    <td align="center">
      <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
      <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman">
    </td>
  </tr>
</table>

## 🏗️ สถาปัตยกรรมระบบ (System Architecture)

แผนผังการทำงานของระบบอย่างง่าย:

```
[Frontend: Vue.js] <---> [Backend API: Node/Express] <---> [xrpl.js Library] <---> [XRP Ledger Network]
```

## 🚀 การเริ่มต้นใช้งาน (Getting Started)

### ข้อกำหนดเบื้องต้น (Prerequisites)

-   Node.js (v18.x or later)
-   npm / yarn
-   Git

### การติดตั้ง (Installation)

1.  Clone a copy of this repository:
    ```sh
    git clone [https://github.com/khamsone8585/gold-token-xrp.git](https://github.com/khamsone8585/gold-token-xrp.git)
    ```
2.  Navigate to the project directory:
    ```sh
    cd gold-token-xrp
    ```
3.  Install NPM packages:
    ```sh
    npm install
    ```
4.  สร้างไฟล์ `.env` โดยคัดลอกจาก `.env.example` และใส่ข้อมูล Wallet ของคุณ (บน Testnet):
    ```env
    XRPL_SERVER="wss://s.altnet.rippletest.net:51233"
    ISSUER_SEED="sXXXXXXXXXXXXXXXXXXXXXXXXX"
    RECEIVER_SEED="sXXXXXXXXXXXXXXXXXXXXXXXXX"
    ```
5.  Start the development server:
    ```sh
    npm run dev
    ```

## 🛣️ แผนการพัฒนา (Roadmap)

-   [x] ตั้งค่าโปรเจกต์และเชื่อมต่อกับ XRPL Testnet
-   [x] พัฒนาฟังก์ชัน Backend หลัก (Issue, Trust, Send)
-   [ ] พัฒนา API สำหรับตรวจสอบประวัติการทำธุรกรรม
-   [ ] สร้างหน้า Frontend พื้นฐานด้วย Vue.js
-   [ ] เพิ่มระบบ Authentication สำหรับผู้ใช้
-   [ ] Deploy โปรเจกต์ขึ้นบน Cloud Platform

## 👤 ติดต่อ (Contact)

**Khamsone Soulipanya**

-   **Portfolio:** https://khamsone8585.github.io/portfolio.github.io/
-   **Email:** asoulipanya@gmail.com
-   **GitHub:** https://github.com/khamsone8585
