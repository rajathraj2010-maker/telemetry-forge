# Telemetry Forge - Premium F1 Telemetry Dashboard

## Objective

Build a professional Formula 1 telemetry analysis platform with real-time driver comparison, animated track visualization, and synchronized telemetry graphs.

## Core Features

### 1. Session Browser
- Select Season, Event, Session, Driver with team color coding

### 2. Real-time Telemetry Viewer
- Speed, Throttle, Brake, Gear, RPM, DRS, ERS channels
- Synchronized graphs with hover sync
- Lap overlays, sector highlighting

### 3. Animated Track Replay Engine
- SVG circuit rendering with 60fps animations
- Real-time car position markers
- Racing line overlays, sector highlighting
- DRS status indicators

### 4. Driver Comparison
- Side-by-side telemetry comparison
- Delta time, sector performance, lap times

### 5. Professional UI/UX
- Glassmorphism with blur effects
- Dark theme optimized for engineering aesthetics
- Smooth Framer Motion animations

## Tech Stack

- **Frontend**: Next.js 14+, TypeScript, Tailwind CSS, Framer Motion, Recharts
- **Backend**: FastAPI + Python (with FastF1)
- **State**: React Context + custom hooks
