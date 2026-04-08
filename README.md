# Interactive Wall Calendar Component

A polished **Interactive Wall Calendar** built with **Next.js, React, TypeScript, and Tailwind CSS**.
The component is inspired by a **decorative physical wall calendar**, combining a visually appealing layout with functional date range selection and an integrated notes system.

This project demonstrates **frontend engineering skills including UI design, state management, responsive layouts, and interactive components**.

---

## ✨ Features

### 🗓 Wall Calendar Layout

* Decorative **hero image section** acting as a visual anchor.
* Monthly calendar grid displayed alongside or below the image.
* Clean layout inspired by **physical wall calendars**.

### 📅 Date Range Selection

* Select a **start date** and **end date** directly from the calendar grid.
* Clear visual states for:

  * Start date
  * End date
  * Selected range
* Clicking again resets the selection.

### 📝 Integrated Notes

* Users can write **notes for the month or selected date range**.
* Notes persist using **localStorage**.
* Automatically loads saved notes when the same range is selected.

### 📱 Fully Responsive

* **Desktop Layout**

  * Image and calendar side-by-side
* **Mobile Layout**

  * Stacked vertically
  * Touch-friendly date selection
  * Notes accessible below calendar

### 🎨 UI & UX Enhancements

* Clean modern design using **Tailwind CSS**
* Smooth hover states
* Highlighted current day
* Elegant card layout with rounded corners and shadows

---

## 🛠 Tech Stack

* **Framework:** Next.js (App Router)
* **Library:** React
* **Language:** TypeScript
* **Styling:** Tailwind CSS
* **Animations (optional):** Framer Motion
* **Data Persistence:** localStorage

---

## 📂 Project Structure

```
interactive-wall-calendar
│
├── app
│   ├── page.tsx
│   └── globals.css
│
├── components
│   ├── Calendar.tsx
│   ├── CalendarHeader.tsx
│   ├── CalendarGrid.tsx
│   ├── DayCell.tsx
│   ├── NotesPanel.tsx
│   └── HeroImage.tsx
│
├── utils
│   └── dateHelpers.ts
│
├── public
│   └── hero-image.jpg
│
├── README.md
└── package.json
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/interactive-wall-calendar.git
cd interactive-wall-calendar
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Run the Development Server

```bash
npm run dev
```

Open your browser and navigate to:

```
http://localhost:3000
```

---

## 📹 Demo

A short demonstration video showcasing:

* Date range selection
* Notes functionality
* Responsive layout (desktop & mobile)

Example:

```
Loom / YouTube link here
```

---

## 🌐 Live Demo (Optional)

Deployed version:

```
https://your-project.vercel.app
```

---

## 💡 Design Decisions

* **Component-based architecture** for maintainability and reusability.
* **Date range selection logic** separated from UI for better scalability.
* **localStorage** used instead of a backend to keep the project strictly frontend.
* **Tailwind CSS** chosen for fast, consistent styling and responsive layouts.
* Layout inspired by **traditional wall calendars** to create a familiar visual structure.

---

## 🚀 Possible Future Improvements

* Animated month transitions
* Holiday markers
* Theme color based on hero image
* Drag-to-select date ranges
* Dark mode
* Export notes feature

---

## 👨‍💻 Author

Frontend Engineering Challenge Submission.

Built to demonstrate:

* UI engineering
* responsive design
* interactive state management
* component architecture
