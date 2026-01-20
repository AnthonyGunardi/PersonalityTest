# Personality Test

A lightweight HTML/JS application that guides users through 40 personality questions, calculates temperament percentages (Sanguinis, Koleris, Melankolis, Phlegmatis), and displays results with charts and detailed breakdowns. Supports saving results to backend, and direct result retrieval via result ID The project includes a user-facing test interface and an administrative dashboard for viewing results.

## 🌟 Features

### User Interface (`index.html`)
- **Interactive Assessment**: A step-by-step personality test with a smooth, modern UI.
- **Responsive Design**: Fully optimized for mobile and desktop devices using Bootstrap 5.
- **Dynamic Scoring**: Real-time calculation of personality percentages.
- **Visual Feedback**: Progress bars, glassmorphism effects, and interactive choice cards.

### Admin Dashboard (`admin/index.html`)
- **Data Visualization**: View all user submission results in a modern data table.
- **Filtering**: Filter results by Name, Company, and Date.
- **Excel Export**: Export filtered or full datasets to `.xls` format.
- **Pagination**: "Load More" functionality for managing large datasets.
- **Detail View**: Direct link to individual result pages.

## 📂 Project Structure

```
Personality_Test/
├── admin/
│   └── index.html      # Admin dashboard for viewing and managing results
├── assets/
│   └── vector_01.svg   # UI graphic asset
├── index.html          # Main entry point for the personality test
└── README.md           # Project documentation
```

## 🛠️ Technology Stack

- **Frontend Framework**: HTML5, CSS3 (Vanilla + Custom Properties)
- **UI Library**: [Bootstrap 5.3.3](https://getbootstrap.com/)
- **HTTP Client**: [Axios](https://axios-http.com/) (for API integration)

## 🚀 Setup & Usage

Since this is a static web application, no build process is required.

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   ```

2. **Run the Application**:
   - Simply open `index.html` in your web browser to start the personality test.
   - Open `admin/index.html` to access the admin dashboard.

   *Note: For optimal performance and to avoid CORS issues with some local file configurations, it is recommended to serve the files using a local server (e.g., Live Server in VS Code).*

## 🔌 API Configuration

The application connects to a backend API to submit tests and fetch results.
- **Configuration**: The API URL is defined in the script section of `admin/index.html` and `index.html`.
