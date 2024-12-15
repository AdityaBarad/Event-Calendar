# Dynamic Event Calendar Application

## **Overview**

This project is a **Dynamic Event Calendar Application** built using **React.js**. It is designed to showcase advanced React.js logic, clean UI design, and deployment capabilities. The application allows users to manage events seamlessly with features such as a calendar view, event management, data persistence, and more.

---

## **Deployment**

The project is deployed at: **https://event-calendar-orpin.vercel.app/**  

---

## **Features**

### **Core Features**
1. **Calendar View**:
   - Displays a calendar grid for the current month with proper alignment.
   - Users can navigate between months using "Previous" and "Next" buttons.
   - Highlights the current and selected days.

2. **Event Management**:
   - Add, edit, and delete events on a selected day.
   - Events include:
     - Event name
     - Start and end times
     - Optional description
   - Displays a list of events for the selected day in a modal or side panel.

3. **Data Persistence**:
   - Utilizes **localStorage** or an in-memory data store to preserve events across page refreshes.

4. **Complex Logic**:
   - Handles month transitions (e.g., Jan 31 → Feb 1).
   - Prevents overlapping events.
   - Enables filtering of events by keywords.

---

## **Getting Started**

### **1. Clone the Repository**
```bash
git clone <repository-url>
cd dynamic-event-calendar
```

### **2. Install Dependencies**
```bash
npm install
```

### **3. Run Locally**
```bash
npm start
```
The app will be available at [http://localhost:3000](http://localhost:3000).

---
