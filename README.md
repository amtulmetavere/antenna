AntennaForUs is a responsive and fast website designed for professional antenna installation, TV wall mounting, CCTV installation, and related services. It is built with React.js, Vite, Tailwind CSS, and modern UI/UX practices to ensure smooth performance and a seamless user experience.

🚀 Technologies Used:

Frontend
React.js ⚛️ – Component-based structure for efficient rendering.
Vite ⚡ – Lightning-fast development environment.
React Router 🌐 – For seamless page navigation.
AOS (Animate On Scroll) 🎭 – Smooth scrolling animations.
Tailwind CSS 🎨 – Utility-first CSS framework for fast styling.
React Icons 🖌️ – For professional and attractive icons.


Plugins & Tools:
@vitejs/plugin-react – Uses Babel for Fast Refresh in development.
@vitejs/plugin-react-swc – Uses SWC for Fast Refresh, improving performance.
EmailJS ✉️ – To handle contact form and quote requests.
React Slick 🎡 – Used for sliders and smooth carousel effects.

📦 antennaforus
├── 📁 src
│   ├── 📁 components    # Reusable UI components (Navbar, Footer, Hero, etc.)
│   ├── 📁 pages         # Individual pages (Home, About, Contact, Blogs, etc.)
│   ├── 📁 assets        # Images, logos, and design assets
│   ├── 📁 styles        # Custom CSS and Tailwind configurations
│   ├── 📁 utils         # Utility functions (helpers, API calls, etc.)
│   ├── 📄 App.jsx       # Main application entry point
│   ├── 📄 main.jsx      # React DOM rendering setup
├── 📄 index.html        # Root HTML file
├── 📄 package.json      # Dependencies and scripts
├── 📄 tailwind.config.js # Tailwind custom configuration
├── 📄 vite.config.js    # Vite settings for optimization
1️⃣ CMD
Copy
Edit
npm install

3️⃣ CMD
 Start the Development Server
Copy
Edit
npm run dev
This will launch the website locally at http://localhost:5173/ (or another available port).
4️⃣ CMD

Copy
Edit
npm run build
This creates an optimized build for deployment.
🌟 Features & Functionality
✅ Fast Performance – Built with Vite for blazing-fast speed.
✅ Fully Responsive – Works smoothly on all screen sizes.
✅ SEO-Friendly – Optimized for search engines.
✅ EmailJS Integration – Handles contact form submissions seamlessly.
✅ Smooth Animations – Uses AOS and Framer Motion for UI effects.
✅ Modern UI Design – Tailwind CSS for clean and attractive styling.


## Responsive CSS Guide


This CSS ensures full **responsiveness** across:
- **📱 Mobile:** iPhones (Mini, XR, 12 Pro, 14 Pro Max), Samsung Galaxy (S8+, S20 Ultra, A51/A71)
- **💻 Tablets:** iPad Mini, iPad Pro, Surface Duo, Nest Hub
- **🖥️ Desktops & Foldables:** MacBook, Asus Zenbook Fold, Galaxy Z Fold 5

## ✅ Features
✔ **Adaptive Hero Banner** - `object-fit: cover;` for non-distorted scaling.  
✔ **Grid-Based Layout** - Two-column on large screens, stacked on smaller screens.   
✔ **CTA Button Animation** - Hover effect (`scale(1.05)`) for modern UI.  
✔ **Optimized for All Screen Sizes** - Mobile-first approach.

## 🛠️ Breakpoints
| Screen Size         | Adjustments |
|---------------------|------------|
| **1024px+ (Large)** | Full-width banner, max-height 90vh |
| **768px - 1023px**  | Grid adjusts, banner resizes |
| **480px - 767px**   | Text & button scaling for clarity |
| **320px - 479px**   | Single-column layout, optimized spacing |

## 📂 How to Use
1️⃣ Save the `tvwallmounting.css` file in `src/styles/`.  
2️⃣ Import it in `TVWallMounting.jsx`:

```jsx
import "../../styles/tvwallmounting.css";


          ================================= ANTENNA FOR US =================================

            <div className="container mx-auto px-3 md:px-12 py-20 grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
