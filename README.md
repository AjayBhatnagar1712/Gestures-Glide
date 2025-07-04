# Gesture-Based Projects & Loyalty Points System

This repository contains four Python-based projects that showcase interaction with hardware (camera, screen, audio, etc.) using computer vision and automation techniques:

---

## 📌 Projects Overview

### 1. Loyalty Points Assignment
**Objective:** Analyze deposit, withdrawal, and gameplay data to compute loyalty points and distribute ₹50,000 bonus fairly among the top 50 users.

- **Data Sources:** Deposit, Withdrawal, Gameplay CSVs
- **Tech Stack:** Pandas, Python, FPDF
- **Deliverables:**
  - `Loyalty_Points_Assignment_Report.pdf` (Report)
  - `Top_50_Bonus_Distribution.csv` (Output)
  - `Loyalty_Points_Analysis.py` or Notebook (Code)

---

### 2. GG_Virtual_Mouse
**Description:** Control mouse cursor, clicks, and system features like brightness and volume through hand gestures.

- **Modules Used:** Mediapipe, PyAutoGUI, Pycaw, ScreenBrightnessControl
- **Features:**
  - Pinch to adjust volume or brightness
  - V-sign, fist, and other gestures mapped to clicks and movements
- **File:** `GG_Virtual_Mouse.py`

---

### 3. GG_Eye_Tracker
**Description:** Track eye gaze and blink to control mouse cursor position and clicks.

- **Modules Used:** OpenCV, Mediapipe, PyAutoGUI
- **Features:**
  - Head movement mapped to mouse
  - Blink detection triggers click
- **File:** `GG_Eye_Tracker.py`

---

### 4. GG_PPT_Controller
**Description:** Use hand gestures to navigate PowerPoint slides.

- **Modules Used:** cvzone, win32com, Aspose, OpenCV
- **Features:**
  - Raise hand or specific fingers to move to next/previous slide
- **File:** `GG_PPT_Controller.py`

---

## 📁 Folder Structure

