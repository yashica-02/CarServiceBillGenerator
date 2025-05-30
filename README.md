# Car Service Bill Generator

A Java-based desktop application developed using NetBeans to generate detailed service bills for vehicles. The application calculates total charges based on the **type of car** and **selected service codes**, and displays the final itemized bill through a GUI interface.

---

## 🧭 Application Workflow

1. Select the **Type of Car**
2. Enter or select the **Service Codes**
3. Click **Generate Bill** to view a detailed invoice
4. Use the **Reset** button to start over

---

## 🖼 UI Screenshots

**Main Window - Select Car Type and Services**  
<img width="470" alt="image" src="https://user-images.githubusercontent.com/100527997/211759417-e4915de3-09e4-45f3-a029-c8fc2c8fb03b.png">

**Example with Additional Services Selected**  
<img width="468" alt="image" src="https://user-images.githubusercontent.com/100527997/211759571-7c618442-bbfa-4235-ac79-230e98762905.png">

**Generated Bill Window**  
<img width="255" alt="image" src="https://user-images.githubusercontent.com/100527997/211759721-0ce80b14-4f77-4d4c-8bf6-ac287a9a580a.png">

**After Clicking Reset**  
<img width="467" alt="image" src="https://user-images.githubusercontent.com/100527997/211759802-28a959d6-be4a-484b-85f9-e77cb10cd2a6.png">

**Different Input Combination Example**  
<img width="454" alt="image" src="https://user-images.githubusercontent.com/100527997/211759892-c5e7e918-92f3-426e-bb60-b260c905dbba.png">

---

## 🛠 Technologies Used

- Java (JDK 8+)
- Java Swing (GUI)
- NetBeans IDE

---

## 🚀 How to Run

### Option 1: Run via NetBeans (Recommended)

1. Clone the repository:
```bash
git clone https://github.com/yashica-02/CarServiceBillGenerator.git
```

2. Open NetBeans → `File` → `Open Project`  
3. Select the cloned folder  
4. Right-click on the project → `Run` or run `BillGenerator.java`

### Option 2: Run via Command Line

```bash
javac src/carservice/BillGenerator.java
java -cp src carservice.BillGenerator
```

> Make sure Java is installed and added to your system path.

---

## 📌 Notes

- No external database is required — all logic is handled in-code.
- Ideal for learning GUI application development with Java Swing.
