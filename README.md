# IronFit Pro - Gym Management System

A comprehensive fitness gym management application for trainers and clients built with React, TypeScript, and Tailwind CSS.

## 🎯 Features

### Admin (Trainer) Dashboard
- **Client Management**: Add, view, and manage client information
- **Subscription Tracking**: Monitor client subscription status with visual progress indicators
- **Personalized Diet Plans**: Assign diet plans based on client goals:
  - حرق دهون (Fat Loss)
  - بناء عضل (Muscle Building)
  - لياقة عامة (General Fitness)
  - زيادة وزن (Weight Gain)
- **Training Programs**: Manage exercise routines for each day
- **Progress Monitoring**: Track client weight changes over weeks
- **Notifications**: Get alerts for expiring subscriptions

### Client Portal
- **Personalized Dashboard**: View assigned goals and subscription status
- **Diet Tracking**: View meal plans with calorie information
- **Training Log**: Access daily exercise routines with set tracking
- **Progress Chart**: Visual weight tracking progress
- **Weekly Updates**: Log weight changes throughout subscription period

## 🏗️ Technology Stack

- **Frontend Framework**: React 18+
- **Language**: TypeScript
- **Styling**: Tailwind CSS with custom dark theme
- **Build Tool**: Vite
- **UI Components**: Radix UI
- **Icons**: Tabler Icons
- **State Management**: localStorage

## 📦 Installation

```bash
# Install dependencies
npm install

# Set environment variables
export PORT=3000
export BASE_PATH=/

# Run development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run serve
```

## 🔐 Demo Credentials

### Admin Access
- **Username**: `admin`
- **Password**: `1234`

### Client Access
- **Username**: `client1`
- **Password**: `1234`

Alternative clients: `client2`, `client3`

## 📱 UI Characteristics

- **RTL Support**: Full Arabic right-to-left interface
- **Dark Theme**: Professional dark UI with accent colors
- **Responsive**: Mobile-optimized (480px max-width)
- **Color Scheme**:
  - Primary: #1a1a2e (Dark background)
  - Accent: #e94560 (Red)
  - Gold: #f5a623 (Highlights)
  - Success: #2ecc71 (Green)
  - Warning: #f39c12 (Orange)

## 📊 Sample Data

The app comes with 3 pre-loaded clients:
1. **محمد أحمد** (Mohammed Ahmed) - Fat Loss goal
2. **سارة علي** (Sara Ali) - Muscle Building goal
3. **خالد إبراهيم** (Khaled Ibrahim) - General Fitness goal

## 🎨 Design Features

- Clean, modern UI with smooth interactions
- Tab-based navigation for diet, training, and progress
- Progress bars with color-coded status indicators
- Interactive charts for weight tracking
- Form validation for data entry
- Local storage persistence

## 📝 License

Private Project - All Rights Reserved
