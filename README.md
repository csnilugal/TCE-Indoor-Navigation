# 📍 TCE Indoor Navigation  
### QR Code Generator Web Page for TCE Indoor Navigation System

The **TCE Indoor Navigation** project provides a simple, user-friendly web interface that generates QR codes for different indoor locations inside the Thiagarajar College of Engineering (TCE).  
These QR codes can be placed around the campus to help students, staff, and visitors easily navigate to classrooms, laboratories, offices, and other blocks using the TCE Navigation App.

This system supports all categories of users — **Normal, Wheelchair, Deaf & Dumb, and Visually Impaired** — by offering an accessible and efficient indoor navigation experience.

---

## 🚀 Features

### **1. QR Code Generation**
- Generate QR codes for **any building, department, hall, or endpoint**.
- Each QR code corresponds to a navigation endpoint (e.g., Library, Seminar Hall, Labs).
- Users scan QR codes using the TCE Navigation App for instant routing.

### **2. Web-Based Interface**
- No installation needed — works in any browser.
- Clean and easy-to-use UI.
- Compatible with desktop and mobile.

### **3. Supports All TCE Building Endpoints**
QR codes can be created for:
- Main Entrance (20)  
- Offices (21, 22, 23, 24)  
- All Branch Departments  
- Library (10)  
- Auditoriums & Seminar Halls  
- Labs (e.g., Cisco Lab – 138)  
- More endpoints can be added anytime

### **4. Admin-Friendly**
- Admins can quickly generate and print QR codes.
- Suitable for placing near rooms, labs, blocks, halls, and entrances.

---

## 🧩 How It Works

1. Admin enters or selects a **building/room code** (e.g., `20`, `01`, `138`).
2. The system generates a **unique QR code** instantly.
3. QR code can be:
   - Downloaded as PNG  
   - Printed for campus use  
4. Users scan QR codes through the **TCE Navigation App**.
5. The app reads the endpoint and loads the shortest indoor route automatically.

---

## 📦 Technologies Used

- **HTML5, CSS3**
- **Kotlin/Sceanview/Google Kit to build apk path file**
- GitHub Pages for free hosting
- Optional backend for data storage

---

## 🔧 Setup Instructions

### **1. Clone the repository**
```bash
git clone https://github.com/your-username/tce-indoor-navigation.git
cd tce-indoor-navigation
```

### **2. Open the web app**
Open `index.html` in any browser.

### **3. Optional: Host Online**
Using GitHub Pages:
- Go to **Settings → Pages**
- Choose `main` branch and `/root` folder
- Save

Your QR generator will be published online.

---

## 🎯 Usage

1. Enter or choose a **building code**.
2. Click **Generate QR**.
3. View the QR code.
4. Download it as an image.
5. Print and place around campus.

---

## 📘 Example Endpoint Codes

| Location | Code |
|----------|------|
| Main Entrance | 20 |
| Office | 21 |
| Principal Office | 22 |
| Management Office | 23 |
| Placement Office | 24 |
| CSE Department | 01 |
| ECE Department | 02 |
| EEE Department | 03 |
| Civil Department | 04 |
| Mechanical Department | 05 |
| Library | 10 |
| Civil Seminar Hall | 127 |
| Mechanical Seminar Hall | 103 |
| Cisco Lab | 138 |

---

## 🤝 Contributing

You can contribute by:
- Improving UI  
- Adding more building codes  
- Enhancing QR generation features  
- Integrating backend endpoints  
- Improving accessibility  

Submit a pull request for changes.

---

## 📞 Support

If you need help integrating this with your **TCE Navigation App**, you can ask anytime.

---

## 🏫 About TCE

This project is developed for **Tontadarya College of Engineering** to improve indoor navigation accessibility for all visitors, students, and staff.
