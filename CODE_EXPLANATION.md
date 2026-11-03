# 🧩 คู่มือตำแหน่งโค้ดและสถาปัตยกรรม (Interactive Code Navigator)
## โครงงาน: Puzzle Battle: Card Memory Duel
> **คลิกที่ลิงก์บรรทัดโค้ด (เช่น `[ไฟล์: บรรทัด xx]`) เพื่อกระโดดไปยังตำแหน่งซอร์สโค้ดจริงในโปรแกรมได้ทันที**

---

## ⚡ สารบัญปุ่มลัดคลิกไปที่โค้ดทันที (One-Click Quick Code Jumper)

หน้านี้รวมชอร์ตคัตคลิกครั้งเดียวเพื่อเปิดไฟล์ไปยังบรรทัดที่ต้องการสำหรับนำเสนออาจารย์:

### 🎬 JavaFX Animations & UI Effects
* 🔄 **RotateTransition สลับเทิร์น 180° (Phase 1: 0° -> 90°):** [`PuzzleBattleUI.java#L634-L637`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L634-L637)
* 🔄 **RotateTransition สลับเทิร์น 180° (Phase 2: -90° -> 0°):** [`PuzzleBattleUI.java#L658-L661`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L658-L661)
* ⏱️ **PauseTransition หน่วงเวลาจำการ์ด 1.2 วินาที:** [`PuzzleBattleUI.java#L1198-L1203`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L1198-L1203)
* 🃏 **RotateTransition พลิกการ์ด 3D บนกระดาน (0° -> 360°):** [`PuzzleBattleUI.java#L1215-L1219`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L1215-L1219)
* 📏 **ScaleTransition ย่อ-ขยายหน้าจอระหว่างหมุน:** [`PuzzleBattleUI.java#L639-L645`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L639-L645) และ [`L663-L669`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L663-L669)
* 🔒 **ตัวแปรสถานะล็อกบอร์ด (`boardLocked`):** [`PuzzleBattleUI.java#L72`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L72)

### 🔘 Event Handling (ปุ่มและการคลิก)
* 🟢 **ปุ่มเริ่มเกม Start Game (`setOnAction`):** [`PuzzleBattleUI.java#L152`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L152)
* 🔄 **ปุ่มจบเทิร์น End Turn (`setOnAction`):** [`PuzzleBattleUI.java#L590-L594`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L590-L594)
* ⚡ **ปุ่มสวนกลับ Chain! (`setOnAction`):** [`PuzzleBattleUI.java#L554-L558`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L554-L558)
* 🛑 **ปุ่มผ่าน Pass (`setOnAction`):** [`PuzzleBattleUI.java#L560-L564`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L560-L564)
* 💎 **ปุ่มจ่าย 4 Energy จั่วต่อ (`setOnAction`):** [`PuzzleBattleUI.java#L578-L587`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L578-L587)
* 🖐️ **คลิกใช้การ์ดบนมือ (`cardButton.setOnAction`):** [`PuzzleBattleUI.java#L1021-L1033`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L1021-L1033)
* 🧩 **คลิกเปิดการ์ดกระดาน 4×4 (`boardButton.setOnAction`):** [`PuzzleBattleUI.java#L1189-L1208`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L1189-L1208)

### 🏛️ 6 เสาหลัก OOP (Object-Oriented Programming)
* 📐 **Abstract Class `Card` & เมธอด `use()`:** [`Card.java#L1-L17`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Card.java#L1-L17)
* 🧬 **Inheritance & Constructor `super()`:** [`AttackCard.java#L1-L7`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/AttackCard.java#L1-L7)
* 🎭 **Polymorphism ในระบบเชน (`card.use(...)`):** [`ChainSystem.java#L27-L30`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/ChainSystem.java#L27-L30) และ [`GameFlow.java#L305-L310`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/GameFlow.java#L305-L310)
* 🛡️ **Encapsulation & Validation (`private` + `Math.max`):** [`Player.java#L5-L8`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Player.java#L5-L8) และ [`Player.java#L40-L50`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Player.java#L40-L50)
* 🧱 **Composition (Has-A Relationship ใน GameFlow):** [`GameFlow.java#L6-L12`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/GameFlow.java#L6-L12) และ [`L36-L42`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/GameFlow.java#L36-L42)
* 🏗️ **Constructor & Initial States:** [`Player.java#L10-L15`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Player.java#L10-L15)

### 🧠 อัลกอริทึม & โครงสร้างข้อมูล (Algorithms & Data Structures)
* 📥 **Queue (FIFO) สำรับการ์ด (`LinkedList.poll`):** [`Deck.java#L8`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Deck.java#L8) และ [`Deck.java#L32-L34`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Deck.java#L32-L34)
* 🥞 **Stack (LIFO) ระบบเชนสวนกลับ (Reverse Loop):** [`ChainSystem.java#L5`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/ChainSystem.java#L5) และ [`ChainSystem.java#L26-L32`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/ChainSystem.java#L26-L32)
* 🛡️ **Shield-Absorb Algorithm (หักลบ Shield ก่อนลด HP):** [`Player.java#L17-L30`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Player.java#L17-L30)
* 🎲 **Guaranteed Pairs Pool (สร้างกระดาน 4×4 รับประกันคู่):** [`GameFlow.java#L527-L541`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/GameFlow.java#L527-L541)
* 🔍 **Board Matching Logic (จับคู่การ์ดบนกระดาน):** [`GameFlow.java#L407-L465`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/GameFlow.java#L407-L465)

---

## 1. ตารางสรุปภาพรวมพร้อมลิงก์ตรงสู่บรรทัดโค้ด (Master Navigation Table)

| ไฟล์ / คลาส | หัวข้อหลัก | ลิงก์คลิกตรงสู่บรรทัดโค้ด | คำอธิบายสิ่งที่ใช้ |
|---|---|---|---|
| [`Card.java`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Card.java) | Abstract Class | [`Card.java#L1`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Card.java#L1) | นิยาม `public abstract class Card` ป้องกันการสร้างอ็อบเจกต์ตรง |
| [`Card.java`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Card.java) | Abstract Method | [`Card.java#L16`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Card.java#L16) | นิยาม `public abstract void use(Player user, Player target);` |
| [`Card.java`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Card.java) | Constructor & Protected | [`Card.java#L2-L10`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Card.java#L2-L10) | ตัวแปร `name`, `description`, `cost` เปิดให้คลาสลูกเข้าถึง |
| [`AttackCard.java`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/AttackCard.java) | Inheritance & `super()` | [`AttackCard.java#L1-L7`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/AttackCard.java#L1-L7) | สืบทอด `extends Card` และส่งชื่อการ์ด/ค่าร่ายผ่าน `super(...)` |
| [`AttackCard.java`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/AttackCard.java) | Polymorphism (`@Override`) | [`AttackCard.java#L9-L12`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/AttackCard.java#L9-L12) | Override เมธอด `use()` ทำดาเมจ 500 หน่วย |
| [`HealCard.java`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/HealCard.java) | Inheritance & Polymorphism | [`HealCard.java#L1-L12`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/HealCard.java#L1-L12) | สืบทอด `Card` และ Override `use()` ฟื้นฟู 300 HP |
| [`EnergyCard.java`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/EnergyCard.java) | Inheritance & Polymorphism | [`EnergyCard.java#L1-L12`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/EnergyCard.java#L1-L12) | สืบทอด `Card` และ Override `use()` เพิ่ม 2 Energy |
| [`ShieldCard.java`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/ShieldCard.java) | Inheritance & Polymorphism | [`ShieldCard.java#L1-L12`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/ShieldCard.java#L1-L12) | สืบทอด `Card` และ Override `use()` กางเกราะ 1,000 หน่วย |
| [`NegateCard.java`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/NegateCard.java) | Inheritance & Polymorphism | [`NegateCard.java#L1-L12`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/NegateCard.java#L1-L12) | สืบทอด `Card` และ Override `use()` ลบล้างเกราะและลด Energy |
| [`StealCard.java`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/StealCard.java) | Inheritance & Polymorphism | [`StealCard.java#L1-L11`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/StealCard.java#L1-L11) | สืบทอด `Card` และ Override `use()` ขโมย 1 Energy จากคู่ต่อสู้ |
| [`ExtraCard.java`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/ExtraCard.java) | Inheritance & Polymorphism | [`ExtraCard.java#L1-L11`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/ExtraCard.java#L1-L11) | สืบทอด `Card` และ Override `use()` ให้สิทธิ์เปิดกระดานฟรี |
| [`Player.java`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Player.java) | Encapsulation | [`Player.java#L5-L8`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Player.java#L5-L8) | กำหนดตัวแปรสถานะเป็น `private final` |
| [`Player.java`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Player.java) | Data Validation | [`Player.java#L40-L50`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Player.java#L40-L50) | ป้องกันเลือด/เกราะติดลบด้วย `Math.max(0, ...)` |
| [`Player.java`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Player.java) | Shield-Absorb Algorithm | [`Player.java#L17-L30`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Player.java#L17-L30) | หักลบ Shield ก่อน หากไม่พอจึงหักลบ HP |
| [`Deck.java`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Deck.java) | Queue (FIFO) & Shuffle | [`Deck.java#L8, L28-L33`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Deck.java#L8-L33) | สำรับการ์ดใช้ `LinkedList<Card>` และ `poll()` ดึงใบบน |
| [`Hand.java`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Hand.java) | List & Defensive Copying | [`Hand.java#L5-L6, L33-L35`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Hand.java#L5-L35) | จัดการมือ Max 8 ใบ และก็อปปี้ลิสต์ส่งออกเพื่อความปลอดภัย |
| [`ChainSystem.java`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/ChainSystem.java) | Stack (LIFO) Structure | [`ChainSystem.java#L5, L11-L15`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/ChainSystem.java#L5-L15) | ซ้อนการ์ดลงยอด Stack สำหรับการ์ดสวนกลับ |
| [`ChainSystem.java`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/ChainSystem.java) | Reverse LIFO Resolution | [`ChainSystem.java#L26-L32`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/ChainSystem.java#L26-L32) | วนลูปถอยหลังจากบนลงล่าง คลี่คลายเอฟเฟกต์การ์ดใบหลังสุดก่อน |
| [`GameFlow.java`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/GameFlow.java) | Composition (Has-A) | [`GameFlow.java#L6-L12, L36-L42`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/GameFlow.java#L6-L42) | ศูนย์รวม Player, Deck, Hand, ChainSystem |
| [`GameFlow.java`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/GameFlow.java) | Guaranteed Pairs Board Pool | [`GameFlow.java#L527-L541`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/GameFlow.java#L527-L541) | สร้างการ์ด 16 ใบ (7 ชนิด x 2 + สุ่ม 2) รับประกันมีคู่แน่นอน |
| [`PuzzleBattleUI.java`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java) | RotateTransition (หมุน 180°) | [`PuzzleBattleUI.java#L634-L637, L658-L661`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L634-L661) | แอนิเมชันหมุนกลับด้าน 180° เมื่อสลับผู้เล่น |
| [`PuzzleBattleUI.java`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java) | PauseTransition (หน่วง 1.2s) | [`PuzzleBattleUI.java#L1198-L1203`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L1198-L1203) | หน่วงเวลาจำการ์ดโดยไม่ทำให้ GUI ค้าง |
| [`PuzzleBattleUI.java`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java) | 3D Flip Animation | [`PuzzleBattleUI.java#L1215-L1219`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L1215-L1219) | หมุนปุ่ม 0 ถึง 360 องศาเมื่อเปิดการ์ด |

---

## 2. เจาะลึก JavaFX Animations & Transitions (คลิกดูโค้ดได้ทันที)

### 2.1 แอนิเมชันหมุนหน้าจอ 180° สลับเทิร์น Hotseat (`RotateTransition`)
> 🔗 **คลิกดูโค้ดตรงนี้:** [`PuzzleBattleUI.java#L622-L675`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L622-L675)

* **Phase 1 (หมุน 0° ไป 90° พร้อมย่อสเกล):**  
  ดูที่ [`PuzzleBattleUI.java#L634-L646`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L634-L646)  
  สร้าง `rot1 = new RotateTransition(...)` จาก 0° ไป 90° ควบคู่กับ `scale1` ย่อจาก 1.0 เหลือ 0.90
* **สลับข้อมูลผู้เล่น (Switch & Redraw):**  
  ดูที่ [`PuzzleBattleUI.java#L649-L655`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L649-L655)  
  เรียก `gameFlow.endTurn();` และ `refreshUI();` พร้อมเซต `mainLayout.setRotate(-90);`
* **Phase 2 (หมุน -90° ไป 0° คืนมุมมองให้อีกฝั่ง):**  
  ดูที่ [`PuzzleBattleUI.java#L658-L670`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L658-L670)  
  สร้าง `rot2 = new RotateTransition(...)` จาก -90° ไป 0° ควบคู่กับ `scale2` ขยายกลับเป็น 1.0

---

### 2.2 การหน่วงเวลาจำการ์ด 1.2 วินาที (`PauseTransition`)
> 🔗 **คลิกดูโค้ดตรงนี้:** [`PuzzleBattleUI.java#L1194-L1204`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L1194-L1204)

* ในกรณีที่ผู้เล่นเปิดการ์ด 2 ใบไม่ตรงกัน โปรแกรมจะไม่ใช้ `Thread.sleep()` เพราะจะทำให้หน้าจอค้าง (Freeze)
* โปรแกรมตั้งแฟลก [`boardLocked = true;` (บรรทัด 1196)](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L1196) เพื่อล็อกไม่ให้คลิกช่องอื่น
* เรียก [`PauseTransition(Duration.millis(1200))` (บรรทัด 1198)](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L1198) เพื่อหน่วงเวลา 1.2 วินาที ให้ผู้เล่นจำตำแหน่ง ก่อนจะปลดล็อกและคว่ำการ์ดกลับอัตโนมัติ

---

### 2.3 แอนิเมชันพลิกการ์ด 3D เมื่อคลิกเปิด (`RotateTransition`)
> 🔗 **คลิกดูโค้ดตรงนี้:** [`PuzzleBattleUI.java#L1214-L1228`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L1214-L1228)

* ในเมธอด `animateFlip(Button button)` ใช้ [`RotateTransition` (บรรทัด 1215-1219)](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L1215-L1219) หมุนปุ่มการ์ด 0 ถึง 360 องศาภายใน 260 มิลลิวินาที พร้อมเล่นเอฟเฟกต์ `ScaleTransition`

---

## 3. เจาะลึก Event Handling ทุกปุ่มในเกม (`setOnAction`)

คลิกเพื่อกระโดดไปยังโค้ด Event Listener แต่ละจุด:

* 🟢 **เริ่มเกมเข้าสู่ฉากสังเวียน:**  
  [`PuzzleBattleUI.java#L152`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L152) — `startBtn.setOnAction(e -> showGameScene(stage));`
* 🔄 **กดจบเทิร์นสลับฝั่ง:**  
  [`PuzzleBattleUI.java#L590-L594`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L590-L594) — `endTurnButton.setOnAction(e -> { animateTurnTransition(); });`
* ⚡ **กดสวนกลับ Chain Counter:**  
  [`PuzzleBattleUI.java#L554-L558`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L554-L558) — `chainBtn.setOnAction(e -> { ... });`
* 🛑 **กดผ่านไม่สวนกลับ Pass Chain:**  
  [`PuzzleBattleUI.java#L560-L564`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L560-L564) — `passBtn.setOnAction(e -> { gameFlow.passChain(); refreshUI(); });`
* 💎 **จ่าย 4 Energy เปิดการ์ดกระดานต่อ:**  
  [`PuzzleBattleUI.java#L578-L587`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L578-L587) — `drawButton.setOnAction(e -> { ... });`
* 🖐️ **คลิกเลือกใช้การ์ดบนมือ:**  
  [`PuzzleBattleUI.java#L1021-L1033`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L1021-L1033) — `cardButton.setOnAction(e -> { gameFlow.playCardFromCurrentHand(idx); ... });`
* 🧩 **คลิกเปิดการ์ดคว่ำบนกระดาน 4×4:**  
  [`PuzzleBattleUI.java#L1189-L1208`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L1189-L1208) — `boardButton.setOnAction(e -> { ... });`

---

## 4. เจาะลึก 6 เสาหลัก OOP (คลิกดูโค้ดได้ทันที)

### 4.1 Abstract Class & Abstract Method
* **แม่แบบคลาสนามธรรม:** [`Card.java#L1`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Card.java#L1) (`public abstract class Card`)
* **เมธอดนามธรรมบังคับ Override:** [`Card.java#L16`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Card.java#L16) (`public abstract void use(Player user, Player target);`)

### 4.2 Inheritance & Constructor Chaining (`super`)
* **การสืบทอดและการส่งผ่านค่าไปยังคลาสแม่:**  
  [`AttackCard.java#L1-L7`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/AttackCard.java#L1-L7) (`extends Card` และ `super("Attack", "โจมตีศัตรู", 2);`)  
  และในคลาสการ์ดอื่น ๆ: [`HealCard.java#L1-L7`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/HealCard.java#L1-L7), [`ShieldCard.java#L1-L7`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/ShieldCard.java#L1-L7), [`NegateCard.java#L1-L5`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/NegateCard.java#L1-L5)

### 4.3 Polymorphism (Dynamic Method Dispatch)
* **การเรียกใช้งานการ์ดผ่าน Dynamic Binding:**  
  [`ChainSystem.java#L27-L30`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/ChainSystem.java#L27-L30)  
  ตัวแปรอ้างอิงเป็น `Card card` แต่เมื่อเรียก `card.use(user, target);` โปรแกรมจะวิ่งไปเรียก `use()` ของการ์ดใบจริง ณ รันไทม์  
  และใน [`GameFlow.java#L305-L310`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/GameFlow.java#L305-L310)

### 4.4 Encapsulation & Data Validation
* **การซ่อนข้อมูลสถานะด้วย `private`:** [`Player.java#L5-L8`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Player.java#L5-L8)
* **การตรวจสอบความถูกต้องของข้อมูล (Validation):** [`Player.java#L40-L50`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Player.java#L40-L50)  
  มีการใช้ `Math.max(0, ...)` ใน Setter ป้องกันเลือด เกราะ และพลังงานติดลบ

### 4.5 Composition (Has-A Relationship)
* **การประกอบรวมอ็อบเจกต์ใน GameFlow:**  
  [`GameFlow.java#L6-L12`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/GameFlow.java#L6-L12) และ [`GameFlow.java#L36-L42`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/GameFlow.java#L36-L42)  
  คลาส `GameFlow` ประกอบไปด้วย `Player`, `Deck`, `Hand` และ `ChainSystem`

---

## 5. เจาะลึกโครงสร้างข้อมูลและอัลกอริทึม (คลิกดูโค้ดได้ทันที)

* 📥 **Queue (FIFO) สำรับการ์ด:**  
  ดูที่ [`Deck.java#L8`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Deck.java#L8) และ [`Deck.java#L32-L34`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Deck.java#L32-L34) — การจั่วการ์ดใช้ `cards.poll()` เข้าก่อนออกก่อน
* 🥞 **Stack (LIFO) ระบบสวนกลับ:**  
  ดูที่ [`ChainSystem.java#L5`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/ChainSystem.java#L5) และ [`ChainSystem.java#L26-L32`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/ChainSystem.java#L26-L32) — วนลูปย้อนหลังจากบนลงล่าง การ์ดที่วางทีหลังจะประมวลผลก่อน
* 🛡️ **Shield-Absorb Algorithm:**  
  ดูที่ [`Player.java#L17-L30`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Player.java#L17-L30) — หักลบ Shield ก่อน หาก Shield ไม่พอส่วนเกินจะไปลด HP
* 🎲 **Guaranteed Pairs Board Pool 4×4:**  
  ดูที่ [`GameFlow.java#L527-L541`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/GameFlow.java#L527-L541) — การ์ด 7 ชนิด ชนิดละ 2 ใบ (14 ใบ) สุ่มเพิ่ม 2 ใบ ครบ 16 ช่อง รับประกันมีคู่อย่างน้อย 7 คู่เสมอ

---

## 6. ตารางคลิกชี้โค้ดตอบคำถามอาจารย์ (Defense Quick Navigation)

| คำถามที่อาจารย์ถาม | ลิงก์คลิกตรงสู่บรรทัดโค้ด | คำอธิบายสั้นกระชับ |
|---|---|---|
| **"RotateTransition อยู่ตรงไหน?"** | [`PuzzleBattleUI.java#L634`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L634) และ [`L658`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L658) | อยู่ในเมธอด `animateTurnTransition()` แบ่งเป็น 2 เฟส 0°->90° และ -90°->0° ครับ |
| **"PauseTransition ใช้ตรงไหน?"** | [`PuzzleBattleUI.java#L1198-L1203`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L1198-L1203) | ใช้หน่วงเวลา 1.2 วินาทีให้จำการ์ด โดยไม่ทำให้หน้าจอ JavaFX ค้างเหมือน `Thread.sleep` ครับ |
| **"3D Flip Animation อยู่ตรงไหน?"** | [`PuzzleBattleUI.java#L1215-L1219`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L1215-L1219) | อยู่ในเมธอด `animateFlip()` หมุนปุ่ม 0 ถึง 360 องศาเมื่อเปิดการ์ดครับ |
| **"Encapsulation & Validation อยู่ไหน?"** | [`Player.java#L5-L8`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Player.java#L5-L8) และ [`Player.java#L40-L50`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Player.java#L40-L50) | ตัวแปรเป็น `private final` และใน Setter ใช้ `Math.max(0, ...)` ป้องกันค่าติดลบครับ |
| **"Polymorphism อยู่ตรงไหน?"** | [`ChainSystem.java#L27-L30`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/ChainSystem.java#L27-L30) | `card.use(user, target);` เรียกใช้เมธอดตามอินสแตนซ์ลูกจริง ณ รันไทม์ครับ |
| **"Composition อยู่ตรงไหน?"** | [`GameFlow.java#L6-L12`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/GameFlow.java#L6-L12) | GameFlow รวบรวม Player, Deck, Hand, ChainSystem เข้าด้วยกันแบบ Has-A ครับ |
| **"Queue FIFO อยู่ตรงไหน?"** | [`Deck.java#L8, L32-L34`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Deck.java#L8-L34) | ใช้ `Queue<Card>` และดึงการ์ดด้วย `poll()` สำหรับการจั่วแบบเข้าก่อนออกก่อนครับ |
| **"Stack LIFO อยู่ตรงไหน?"** | [`ChainSystem.java#L5, L26-L32`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/ChainSystem.java#L5-L32) | เก็บการ์ดใน Stack และวนลูปย้อนกลับจากบนลงล่างสำหรับการสวนกลับครับ |
| **"Shield คำนวณอย่างไร?"** | [`Player.java#L17-L30`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/Player.java#L17-L30) | หัก Shield ก่อน หากดาเมจทะลุ Shield ส่วนต่างจึงจะไปหัก HP ของเป้าหมายครับ |
| **"ปุ่ม End Turn อยู่ตรงไหน?"** | [`PuzzleBattleUI.java#L590-L594`](file:///c:/Users/MSI/OneDrive/Desktop/gameproject/PuzzleBattleUI.java#L590-L594) | `endTurnButton.setOnAction` ผูกกับ `animateTurnTransition()` ครับ |
