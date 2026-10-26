# 🍔 FoodieHub Express

**Discover. Order. Enjoy.**

FoodieHub Express is a modern, responsive food-ordering web application designed to make exploring food, discovering restaurants, and managing orders simple and enjoyable. It features a polished interface, interactive menus, shopping cart functionality, and personalized wishlist management.

## ✨ Features

- 🍕 **Food Discovery** — Explore food categories, featured dishes, popular meals, and restaurants.
- 🔎 **Smart Menu Search** — Search dishes and filter by category, vegetarian preference, price, and rating.
- 🏪 **Restaurant Explorer** — Browse restaurants, search by cuisine or location, and filter open restaurants.
- 🛒 **Shopping Cart** — Add and remove dishes, update quantities, and calculate order totals.
- 🎟️ **Coupon Discounts** — Try demo coupon codes such as `WELCOME50`, `FREEDEL`, and `PIZZABOGO`.
- ❤️ **Wishlist** — Save your favorite dishes for later.
- 🌙 **Dark & Light Themes** — Switch between themes for a personalized browsing experience.
- 📱 **Responsive UI** — Designed to work across desktop, tablet, and mobile screen sizes.
- ⚡ **Reusable Components** — Maintainable UI components and client-side navigation.
- 💾 **Local Storage** — Preserve cart, wishlist, and theme preferences in the browser.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| React 19 | User interface |
| TypeScript | Type-safe development |
| Vite | Development server and build tool |
| TanStack Router | Client-side routing |
| Tailwind CSS 4 | Styling and responsive layouts |
| Radix UI | Accessible UI primitives |
| Lucide React | Icons |
| Sonner | Toast notifications |
| ESLint | Code quality |
| Prettier | Code formatting |

## 📂 Project Structure

```text
foodiehub-express/
├── public/
├── src/
│   ├── assets/
│   │   └── hero-food.jpg
│   ├── components/
│   │   ├── ui/
│   │   ├── FoodCard.tsx
│   │   ├── RestaurantCard.tsx
│   │   ├── Navbar.tsx
│   │   ├── Footer.tsx
│   │   └── SectionHeader.tsx
│   ├── context/
│   │   └── AppContext.tsx
│   ├── data/
│   │   └── foodData.ts
│   ├── hooks/
│   ├── lib/
│   ├── routes/
│   │   ├── index.tsx
│   │   ├── menu.tsx
│   │   ├── restaurants.tsx
│   │   ├── cart.tsx
│   │   └── wishlist.tsx
│   ├── styles.css
│   ├── router.tsx
│   └── server.ts
├── .gitignore
├── package.json
├── package-lock.json
├── run.bat
└── README.md
```

## 🚀 Getting Started

### Prerequisites

Install the following on your computer:

- [Node.js](https://nodejs.org/) — preferably a current LTS release.
- npm — included with Node.js.

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/foodiehub-express.git
cd foodiehub-express
```

Replace `YOUR-USERNAME` with your GitHub username.

### 2. Install Dependencies

```bash
npm install
```

### 3. Start the Development Server

```bash
npm run dev
```

Open the local URL displayed in your terminal, usually:

```text
http://localhost:5173
```

**Windows users:** You can also double-click `run.bat` to install dependencies and start the development server.

## 🧪 Available Commands

```bash
npm run dev
```

Starts the development server.

```bash
npm run build
```

Builds the application for production.

```bash
npm run preview
```

Previews the production build locally.

```bash
npm run lint
```

Checks the project for linting issues.

```bash
npm run format
```

Formats project files using Prettier.

## 🛍️ Application Pages

| Page | Description |
|---|---|
| Home | Featured dishes, categories, offers, and restaurant discovery |
| Menu | Searchable and filterable food listings |
| Restaurants | Restaurant search and open-status filtering |
| Cart | Quantity management, coupon discounts, and total calculation |
| Wishlist | View and manage saved favorite dishes |

## 💡 How It Works

1. Browse food categories and restaurants.
2. Search and filter dishes based on your preferences.
3. Add your favorite meals to the cart.
4. Adjust quantities and try available demo coupons.
5. Save dishes to your wishlist.
6. Switch between light and dark themes.

## 🔮 Future Improvements

- User authentication and account management
- Secure online payment integration
- Backend API and database integration
- Real order placement and order history
- Live delivery tracking
- Restaurant owner dashboard
- Food ratings and customer reviews
- Personalized food recommendations
- Notifications and promotional offers

## ⚠️ Project Notes

FoodieHub Express currently uses frontend functionality and locally defined application data. Cart and wishlist persistence use browser local storage.

Coupon codes demonstrate discount calculations; they do not process real payments. Live delivery, production order processing, authentication, and backend restaurant management require additional implementation and integration.

Food images may depend on externally hosted image resources, so their availability can vary.

## 🎯 Project Goals

- Build a modern food-ordering interface.
- Practice React and TypeScript development.
- Implement reusable components and application state management.
- Explore responsive design and client-side routing.
- Develop a portfolio project for learning and demonstration.

## 👨‍💻 Author

**Ebinezer Jeba Samuel**

Aspiring Software Engineer | AI & ML Enthusiast | Web Developer

- **GitHub:** [Ebinezer-cloud](https://github.com/Ebinezer-cloud)
- **LinkedIn:** [Ebinezer N](https://www.linkedin.com/in/ebinezer-n-ab8b61392/)
- **LeetCode:** [6UPtksX3aM](https://leetcode.com/u/6UPtksX3aM/)

---

## 📜 License

This project is intended for learning, development, and portfolio demonstration. See the repository's `LICENSE` file for the applicable license terms.

---

<div align="center">

### 🍔 FoodieHub Express

**Designed & Developed by Ebinezer Jeba Samuel**

*Good food. Smooth browsing. Better experiences.*

[GitHub](https://github.com/Ebinezer-cloud) · [LinkedIn](https://www.linkedin.com/in/ebinezer-n-ab8b61392/) · [LeetCode](https://leetcode.com/u/6UPtksX3aM/)

</div>
*Good food. Smooth browsing. Better experiences.*

</div>
