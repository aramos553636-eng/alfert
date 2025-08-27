# Java-Turn-Based-Game-with-Abstraction
CCE105L 2803 Data Structures &amp; Algorithms Assignment 1

# ⚔️ Mage/Archer vs Warrior/SAber Battle Game

This is a simple **turn-based battle game** in Java that uses **Object-Oriented Programming (OOP)** principles and `JOptionPane` for a graphical user interface.  

The game features two characters, **Mage** and **Warrior**, each with unique abilities and attack styles. Players take turns choosing moves until one character’s HP reaches 0, or the player decides to exit.

---

## ✨ Features
- **Abstract Class `Character`** (with `Mage` and `Warrior` subclasses)
- **HP (Health Points):** both start at 100
- **Turn-based system:** players attack in alternating turns
- **2 Move Types**
  - **Basic Attack**
  - **Special Move**
- Winner is displayed when a character’s HP reaches 0

---

## 🗡️ Characters & Attacks

### 🧙 Mage/Archer
| Move | Name | Damage |
|------|------|---------|
| Attack | Rho Aias | 25 |
| Special Move | Noble Phantasm! | 50 |

### 🛡️ Warrior/Saber
| Move | Name | Damage |
|------|------|---------|
| Attack | Lion's Song! | 25 |
| Special Move | The Billion-Fold World Trichiliocosm | 50 |


---

## 🏆 Example Battle Flow

### *Enter Player Names*  
!<img width="304" height="140" alt="image" src="https://github.com/user-attachments/assets/a1493100-82da-4a67-911b-c2fa4b6acccb" />
 
<img width="318" height="135" alt="image" src="https://github.com/user-attachments/assets/c857dca7-92bc-45f7-beb2-2355ae3bde95" />
  

---

### *Battle Starts*  
<img width="283" height="147" alt="image" src="https://github.com/user-attachments/assets/1e2d25c3-cbad-47c4-a501-e9365d66008f" />
  

---

### *Choose a Move*  

Mage Move

<img width="322" height="182" alt="image" src="https://github.com/user-attachments/assets/81649d52-5a15-4292-b80a-03a8087d73a8" />


if the Mage chose Special Move:

<img width="312" height="175" alt="image" src="https://github.com/user-attachments/assets/f3aabfe6-a51c-4a79-b02c-1ed280c586b4" />

<img width="435" height="126" alt="image" src="https://github.com/user-attachments/assets/4774f923-1f7f-40be-85d1-951281b03cda" />

<img width="483" height="131" alt="image" src="https://github.com/user-attachments/assets/9b21d4fb-ecf1-41d2-a668-17f32a729a83" />

<img width="470" height="137" alt="image" src="https://github.com/user-attachments/assets/e50dc083-04c6-42e6-a92e-9efdceee8594" />

<img width="472" height="127" alt="image" src="https://github.com/user-attachments/assets/60894bd4-0185-4969-80b7-ca625c810fd6" />

<img width="471" height="129" alt="image" src="https://github.com/user-attachments/assets/778be92b-2372-4c42-a2c7-d112851e114d" />

<img width="392" height="129" alt="image" src="https://github.com/user-attachments/assets/50e2efe5-04dd-4528-b607-e7539ae61433" />

<img width="441" height="135" alt="image" src="https://github.com/user-attachments/assets/129d50d9-2662-458e-ba19-c3994f192703" />

<img width="550" height="129" alt="image" src="https://github.com/user-attachments/assets/ec4e117e-4938-4346-b6c3-24478a1f73bd" />

<img width="602" height="142" alt="image" src="https://github.com/user-attachments/assets/62d479ad-e554-42e9-b880-7b455da483a6" />

<img width="299" height="130" alt="image" src="https://github.com/user-attachments/assets/5e64e5b1-4b97-4f6d-a961-6700c2d107ce" />
  


Warrior Move

<img width="308" height="174" alt="image" src="https://github.com/user-attachments/assets/bc0eeb7d-2be3-4c9f-a627-c07eede47320" />

if the Warrior chose Special Move:

<img width="316" height="172" alt="image" src="https://github.com/user-attachments/assets/67d9249e-fb6f-4b49-a92f-6c5632f32856" />

<img width="468" height="127" alt="image" src="https://github.com/user-attachments/assets/0517d0bd-7f3a-4a15-a824-41ccd8dc4383" />

<img width="439" height="131" alt="image" src="https://github.com/user-attachments/assets/fdc5730a-cb9e-43b0-90c6-d9d93ee6bd8e" />

<img width="615" height="130" alt="image" src="https://github.com/user-attachments/assets/e8769453-9cc7-47a0-be81-78326737d0b9" />

<img width="410" height="132" alt="image" src="https://github.com/user-attachments/assets/3c1508b5-e50d-4510-8dff-ee7035367598" />

<img width="291" height="124" alt="image" src="https://github.com/user-attachments/assets/644d65c9-d884-4fb6-806a-6c5f2a90ea59" />

<img width="317" height="135" alt="image" src="https://github.com/user-attachments/assets/0b4f9cd4-9ca6-48b2-9abe-393a7e9efdef" />

<img width="303" height="138" alt="image" src="https://github.com/user-attachments/assets/36a816f5-2017-4035-8137-b8dd26c5bfdb" />

<img width="423" height="147" alt="image" src="https://github.com/user-attachments/assets/5d630e92-0d13-4bdc-b8b7-05060d687093" />


---

### *HP Status*  
*Status if both chose Secret Power*

<img width="281" height="131" alt="image" src="https://github.com/user-attachments/assets/8a5aa5ee-6cef-415e-9baa-676d26b65dc1" />
 

*(continue until one player’s HP turns to 0...)*  

---

### *Winner Screen*  
<img width="286" height="135" alt="image" src="https://github.com/user-attachments/assets/b04f23f1-1a70-4cd8-afe7-6e79f62cbac7" />

<img width="284" height="137" alt="image" src="https://github.com/user-attachments/assets/f684ca55-69f9-4e7a-9afa-107dc808d799" />



✍️ Author: ALFERT V RAMOS JR
