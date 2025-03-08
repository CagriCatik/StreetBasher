# **StreetBasher: 3D-Printed RC Car Project** 🏎️🔧  

**StreetBasher** is an open-source, 3D-printed RC car designed for enthusiasts who love customization, engineering, and high-speed fun. This project provides everything you need to **assemble, modify, and fine-tune your own RC car**, including **detailed assembly guides, 3D-printable parts, and tuning instructions**.

🚀 **Build it. Customize it. Race it!**  

---

## 🔹 **Project Highlights**
- **Fully 3D-Printed Design:** Print your own chassis, suspension, and other essential components.
- **Customizable:** Modify the design to fit your preferences, from gearing ratios to wheel types.
- **Electronics & Hardware Integration:** Supports standard RC electronics, motors, and batteries.
- **Step-by-Step Documentation:** Easy-to-follow instructions for assembly and tuning.

---

## 📂 **Project Structure**
```
StreetBasher/
│── .github/workflows/       # GitHub Actions for automation & deployment
│── instructions/            # Documentation & assembly guides
│   ├── docs/                # MkDocs-based documentation
│   ├── sldprts/             # SolidWorks design files
│   ├── stls/                # STL files for 3D printing
│   ├── mkdocs.yml           # Configuration for MkDocs documentation
│── original/                # Raw design files or legacy versions
│── .gitignore               # Ignored files
│── README.md                # Project overview (this file)
│── requirements.txt         # Dependencies for documentation setup
```

---

## 🛠 **Getting Started**
### **1️⃣ Print the Parts**
Download the **STL files** from the `instructions/stls/` folder or from the official **Printables page**:  
➡️ **[StreetBasher on Printables](https://www.printables.com/model/700706-street-basher-3d-printed-rc-car-17)**

### **2️⃣ Gather the Components**
You’ll need the following:
- **3D-printed parts** (chassis, arms, suspension, etc.)
- **RC Electronics:** Brushless motor, ESC, receiver, and transmitter
- **Battery pack** (LiPo recommended)
- **Servo motor** for steering
- **Screws & Fasteners** (size details in the docs)

### **3️⃣ Assemble & Tune**
Follow the **step-by-step assembly guide** in `instructions/docs/` to build your RC car.  
Once built, fine-tune it using the tuning instructions for **better handling and speed**.

---

## 📖 **Documentation**
Complete guides and tutorials are available in the **MkDocs-powered documentation**.  

📝 To view the docs locally:
```sh
# Install dependencies
pip install -r requirements.txt

# Run MkDocs
mkdocs serve
```
Then open **http://127.0.0.1:8000** in your browser.

---