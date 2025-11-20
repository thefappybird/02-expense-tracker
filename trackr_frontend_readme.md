# Trackr - Currency Tracker Demo App

## Overview
**Trackr** is a front-end demo application built with **Angular**, **TypeScript**, and **CSS**. The app connects to a currency tracking API and provides a visual demonstration of currency data tracking. It includes features for toggling themes and generating demo data to showcase charts and graphs in a user-friendly interface.

---

## Tech Stack
- **Frontend Framework**: Angular
- **Language**: TypeScript
- **Styling**: CSS

---

## Features
1. **API Integration**
   - Connects to a currency tracker API to fetch real-time data.

2. **Demo Mode**
   - Generates sample data for charts and graphs to simulate a fully-featured system.

3. **Theme Toggler**
   - Light and dark mode toggling for improved user experience.

4. **Signal-Based Architecture**
   - State management is handled using a signal-based approach to efficiently track and update reactive values.

5. **Visualizations**
   - Dynamic charts and graphs displaying currency trends and statistics.

---

## Data Flow Diagram

```text
+-------------+          +------------------+          +----------------+
|             |          |                  |          |                |
|   User      |  ---->   |  Angular Front-  |  ---->   | Components /   |
| (Browser)   |          |  end (Signals)   |          | Services       |
+-------------+          +------------------+          +--------+-------+
                                                                 |
                                                                 v
                                                      +----------------+
                                                      |                |
                                                      |  API Calls to  |
                                                      |  Currency Data |
                                                      +----------------+
```

---

## Architecture & Design
- **Front-End Only**: Trackr does not include a backend, relying solely on API calls for data.
- **Signal-Based Approach**: Ensures reactive state management and efficient updates of UI components.
- **Theme Management**: CSS-driven light/dark mode toggling.
- **Demo Mode**: Enables the application to display meaningful data without live API data.

---

## Summary
Trackr is a lightweight, Angular-based demo application designed to showcase currency tracking and visualization features. It emphasizes reactive state management, user-friendly design with theme toggling, and a demo mode for exploring functionality without requiring a fully-featured backend.