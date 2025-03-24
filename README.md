# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

# 🍽️ Lunchspot Finder

**Lunchspot Finder** is a modern, responsive web app built with React and the Google Maps JavaScript API. It helps teams quickly discover nearby restaurants — visualized on a map with interactive pins and a browsable card list.

## Tech Stack

- **Frontend**: React + Vite
- **Styling**: Tailwind CSS
- **Maps & Places**: Google Maps JavaScript API (Places Library)
- **Custom Components**: Modular and production-ready

---

## Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/dolaoye-wp/lunchspot-finder-final.git
cd lunchspot-finder-final
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up Google Maps API Key

Create a .env file in the root and add:

```bash
VITE_GOOGLE_MAPS_API_KEY=your_api_key_here
```

Make sure your API key has access to:
Maps JavaScript API

Places API
