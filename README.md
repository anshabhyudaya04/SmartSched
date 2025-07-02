# 📅 SmartSched – Smart Timetable Generator for Schools & Universities

**SmartSched** is a web-based scheduling system designed to simplify academic timetable creation for schools and universities. It helps avoid scheduling conflicts, balances teacher workloads, and ensures efficient classroom usage — all automatically.

Manual scheduling often leads to overlapping classes, overbooked teachers, and inefficient room allocation. SmartSched addresses these challenges using intelligent logic and constraint-solving algorithms to generate clear, conflict-free weekly timetables.

---

## ✨ Key Features

- Simple web interface to input teacher availability, classes, subjects, and rooms  
- Automatically generates non-overlapping, optimized timetables  
- Efficient time slot and room assignment based on constraints  
- Export timetables as **PDF** or **Excel** files for easy sharing  
- Uses an embedded **SQLite** database for data storage and management  
- Fully functional and ready for deployment  

---

## 🧠 Scheduling Logic

SmartSched uses:

- **Graph Coloring** – for assigning time slots without conflicts  
- **Backtracking** – to handle more complex constraints and availability rules  

---

## 🛠 Technology Stack

| Component   | Tools Used                        |
|-------------|-----------------------------------|
| Frontend    | HTML, CSS, JavaScript (Bootstrap) |
| Backend     | Python + Flask (REST APIs)        |
| Database    | SQLite (lightweight & embedded)   |
| Algorithms  | Graph Coloring, Backtracking      |
| Export      | ReportLab (PDF), Pandas (Excel)   |

---

## 📦 Status

All core features have been completed:

- Frontend/backend integration  
- Scheduling engine  
- Database design  
- Export functionality  
- Full testing completed  

---

## 📂 Future Improvements (Optional Ideas)

- User authentication and role-based access (admin, coordinator, teacher)  
- Drag-and-drop UI for manual adjustments  
- Multi-campus or multi-department support  
- Cloud deployment (AWS, GCP, etc.)

---

## 📫 Contact

**Ansh Abhyudaya**  
📍 Dehradun, India  
📧 ansh.abhyudaya04@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/ansh-abhyudaya-725062337/)

---

> _“SmartSched simplifies scheduling so educators can focus on teaching.”_
