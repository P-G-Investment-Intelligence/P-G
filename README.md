# P&G Executive Analytics Dashboard

This is a high-fidelity, interactive dashboard built for Procter & Gamble's executive team, visualizing key metrics from the FY2026 Strategic Overview.

## Features
- **Splash Screen**: Branded P&G introduction with smooth animations.
- **Executive Summary**: Real-time KPI cards for Sales, Growth, Margin, and EPS.
- **Interactive Charts**:
  - **Organic Growth by Segment**: Visualizes performance across business units.
  - **Net Sales Distribution**: Breakdown of revenue by segment.
- **Strategic Initiatives Pipeline**: Detailed view of major projects with status, risk, and priority tracking.
- **Global Filtering**: Filter data by Fiscal Year, Region, and Segment to dynamically update the dashboard views.

## Tech Stack
- **Framework**: React (Vite)
- **Styling**: Plain CSS (Modules/Inline) with P&G Corporate Identity colors.
- **Animations**: Framer Motion for premium transitions.
- **Charts**: Recharts for responsive data visualization.
- **Icons**: Lucide React.

## Setup & Run
1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the development server:
   ```bash
   npm run dev
   ```
3. Open the dashboard in your browser (typically `http://localhost:5173`).

## Data Source
Data is hardcoded from the "P&G Market Intelligence & Investment Analysis - Executive Summary" (extracted from the provided Google Sheet).
