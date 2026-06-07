# 🍲 FoodFuel

### Transforming Food Waste into Meals for the Hungry

FoodFuel is a full-stack food waste management platform designed to reduce food wastage and combat hunger by connecting restaurants, food donors, NGOs, and volunteers through a centralized digital ecosystem.

The platform enables efficient food redistribution by facilitating donation management, NGO coordination, volunteer-based delivery, and real-time tracking of food donations.

---

## 📌 Problem Statement

India generates a significant amount of food waste every day, while millions of people continue to struggle with hunger and food insecurity.

Large quantities of surplus food from restaurants, hotels, supermarkets, and events often go unused due to the absence of an organized redistribution system.

**FoodFuel** addresses this challenge by providing a technology-driven solution that connects food providers with organizations and volunteers who can ensure that surplus food reaches people in need.

---

## 🎯 Objectives

- Reduce food wastage through efficient redistribution.
- Connect food donors with NGOs and charitable organizations.
- Promote sustainable food management practices.
- Encourage community participation through volunteering.
- Ensure safe and organized food distribution.
- Improve transparency in food donation workflows.

---

## ✨ Features

### 🍛 Donor Management
- Donate surplus food quickly and efficiently.
- Create and manage food donation listings.
- Update food availability in real time.

### 🏢 NGO Integration
- Browse available food donations.
- Accept and manage food requests.
- Coordinate directly with donors.

### 🚚 Volunteer Coordination
- Assign volunteers for food pickup and delivery.
- Streamline transportation logistics.
- Track delivery status efficiently.

### 🔐 Authentication & Authorization
- Secure user registration and login.
- Role-based access control.
- User validation and account management.

### 📍 Real-Time Tracking
- Monitor food collection and delivery activities.
- Improve operational visibility and transparency.

### 📱 Responsive User Interface
- Mobile-friendly design.
- Cross-browser compatibility.
- Intuitive user experience.

---

## 🔄 System Workflow

```text
Donor Registration
        ↓
Food Verification
        ↓
Donation Posting
        ↓
NGO Acceptance
        ↓
Volunteer Pickup
        ↓
Food Delivery
        ↓
People in Need Receive Food
```

---

## 🛠️ Tech Stack

### Frontend
- React.js
- JavaScript (ES6+)
- HTML5
- CSS3
- Tailwind CSS

### Backend
- Flask
- Python
- REST APIs
- Flask-CORS

### Database
- MariaDB

### Development Tools
- Git
- GitHub
- Postman
- Visual Studio Code

---

## 📂 Project Structure

```text
FoodFuel/
│
├── backend/
│   ├── venv/
│   ├── dbconnect.py
│   ├── routes/
│   ├── models/
│   └── ...
│
├── frontend/
│   ├── public/
│   ├── src/
│   ├── components/
│   ├── pages/
│   ├── package.json
│   └── ...
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/VISHWARAJ-G/FoodFuel.git
cd FoodFuel
```

### 2. Backend Setup

Navigate to the backend directory:

```bash
cd backend
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate the virtual environment:

#### Windows

```powershell
.\venv\Scripts\Activate.ps1
```

#### Linux/macOS

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install flask flask-cors mariadb python-dotenv
```

Run the backend server:

```bash
python dbconnect.py
```

### 3. Frontend Setup

Navigate to the frontend directory:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

---

## 👥 User Roles

### Donor
- Register and login.
- Create food donation requests.
- Manage donated food listings.

### NGO
- Browse available donations.
- Accept food donations.
- Coordinate with volunteers.

### Volunteer
- View assigned pickups.
- Deliver food to designated locations.
- Update delivery status.

---

## 🌟 Key Benefits

- Reduces food wastage.
- Helps fight hunger and food insecurity.
- Creates a structured food redistribution system.
- Encourages community involvement.
- Promotes sustainable and responsible food management.

---

## 🚀 Future Enhancements

- Live GPS tracking for deliveries.
- AI-based food demand prediction.
- Smart donor-volunteer matching.
- Notification system for nearby NGOs.
- Analytics dashboard for food waste insights.
- Cloud deployment using AWS/Azure.
- Android and iOS mobile applications.
- QR-based donation verification.

---

## 📊 Impact

FoodFuel contributes to:

- Sustainable food management.
- Hunger relief initiatives.
- Community-driven social impact.
- Reduced environmental impact caused by food waste.
- Efficient utilization of surplus food resources.

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes.
4. Push to your branch.
5. Open a Pull Request.

---

## 📄 License

This project is developed for educational, social impact, and research purposes.

Feel free to use, modify, and enhance it according to your requirements.

---

### Made with ❤️ to Reduce Food Waste and Feed Communities
