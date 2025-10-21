# Gold Token on XRP Ledger (XRPL)

![Project Status](https://img.shields.io/badge/status-in%20development-yellow)
![License](https://img.shields.io/badge/license-MIT-blue)

## 📖  (About The Project)

ໂປເຈັກນີ້ຄືການສ້າງລະບົບ Proof-of-Concept (PoC) ສຳລັບການສ້າງ ແລະ ຈັດການໂທເຄນດິຈິຕອນ (IOU) ທີ່ຜູກກັບມູນຄ່າທອງຄຳ ໂດຍເຮັດວຽກຢູ່ເຄື່ອຂ່າຍ  **XRP Ledger (XRPL)** ເຊີ່ງມີຈຸດເດັ່ນເລື່ອງຄວາມໄວໃນການທຸລະກຳທີ່ສູງ ແລະ ຄ່າທຳນຽມທີ່ຕ່ຳຫຼາຍ

ເປົ້າໝາຍຫຼັກຂອງໂປຣເຈັກນີ້ຄືການສືກສາ ແລະ ລົງມືປະຕິບັດຈິງກັບເຕັກໂນໂລຊີ Web3, ການພັດທະນາ Backend API ສຳລັບການຕອບໂຕ້ກັບ Blockchain, ແລະການສ້າງ  Full-Stack Application ທີ່ສົມບູນ

## ✨ ຄຸນສົມບັດຫຼັກ (Core Features)

-   [x] **ສ້າງແລະກຳນົດຄ່າໂທເຄນ(Issue Token):** ສ້າງ "Gold Token" (IOU) ຈາກບັນຊີນີ້ອອກ (Issuer Account)
-   [x] **ສ້າງຄວາມເຊື່ອໃຈ (Trust Line):** ເປີດໃຊ້ງານ Trust Line ຈາກບັນຊີຜູ້ໃຊ້ເພື່ອຮັບໂທເຄນ
-   [x] **ສົ່ງ/ຮັບໂທເຄນ(Send Token):** ໂອນໂທເຄນລະຫວ່າງບັນຊີຜູ້ໃຊ້ເທີງເຄື່ອຂ່າຍ XRPL
-   [ ] **ກວດເຊັກຍອດຍັງຄົງເຫຼືອ (Check Balance):** API ສຳລັບກວດເຊັກໂທເຄນຍັງເຫຼືອໃນບັນຊີນັ້ນໆ
-   [ ] **หน้าเว็บสำหรับผู้ใช้ ໜ້າເວັບສຳລັບຜູ້ໃຊ້ (Simple UI):** ໜ້າເວັບງ່າຍໆທີ່ສ້າງດ້ວຍ Vue.js ເພື່ອໃຫ້ຜູ້ໃຊ້ສາມາດຕອບກັບຟັງຊັ່ນຕ່າງໆໄດ້ 

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

## 🏗️ ໂຄງສ້າງ ສະຖາປັດຕະຍະກຳ (System Architecture)

ແຜນຜັງກສຍເຮັດວຽກຂອງລະບົບແບບງ່າຍໆ:

```
[Frontend: Vue.js] <---> [Backend API: Node/Express] <---> [xrpl.js Library] <---> [XRP Ledger Network]
```

## 🚀 ການເລີ້ມຕົ້ນໃຊ້ງານ (Getting Started)

### ຂໍ້ກຳນົດເບື້ອງຕົ້ນ (Prerequisites)

-   Node.js (v18.x or later)
-   npm / yarn
-   Git

### ການຕິດຕັ້ງ (Installation)

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
4.  ສ້າງຟາຍ `.env` ໂດຍເອົາຈາກ `.env.example` ແລະໃຊ້ຂໍ້ມູນ Wallet ຂອງທ່ານ (ເທີງ Testnet):
    ```env
    XRPL_SERVER="wss://s.altnet.rippletest.net:51233"
    ISSUER_SEED="sXXXXXXXXXXXXXXXXXXXXXXXXX"
    RECEIVER_SEED="sXXXXXXXXXXXXXXXXXXXXXXXXX"
    ```
5.  Start the development server:
    ```sh
    npm run dev
    ```

## 🛣️ ແຜນການພັດທະນາ (Roadmap)

-   [x] ຕັ້ງຄ່າໂປຣເຈັກ ແລະ ເຊື່ອມຕໍ່ກັບ  XRPL Testnet
-   [x] ພັດທະນາຟັງຊັ່ນ Backend ຫຼັກ (Issue, Trust, Send)
-   [ ] ພັດທະນາ API ສຳລັບກວດເຊັກປະຫວັດເຮັດທຸລະກຳ
-   [ ] ສ້າງໜ້າເວັບ Frontend ພື້ນຖານດ້ວຍ Vue.js
-   [ ] ເພີ່ມລະບົບ Authentication ສຳລັບຜູ້ໃຊ້
-   [ ] Deploy ໂປຣເຈັກຂື້ນ Cloud Platform

## 👤 ຕີດຕໍ່ (Contact)

**Khamsone Soulipanya**

-   **Portfolio:** https://khamsone8585.github.io/portfolio.github.io/
-   **Email:** asoulipanya@gmail.com
-   **GitHub:** https://github.com/khamsone8585
