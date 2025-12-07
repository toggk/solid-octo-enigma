## 📁 Project Structure
```
shopify-nextjs-store/
├── src/
│   ├── app/
│   │   ├── layout.js
│   │   ├── page.js
│   │   ├── products/
│   │   │   ├── page.js
│   │   │   └── [handle]/
│   │   │       └── page.js
│   │   ├── cart/
│   │   │   └── page.js
│   │   ├── checkout/
│   │   │   └── success/
│   │   │       └── page.js
│   │   └── api/
│   │       └── shopify/
│   │           ├── products/
│   │           │   └── route.js
│   │           ├── search/
│   │           │   └── route.js
│   │           ├── cart/
│   │           │   └── route.js
│   │           └── webhooks/
│   │               └── route.js
│   ├── components/
│   │   ├── layout/
│   │   │   ├── Header.jsx
│   │   │   ├── Footer.jsx
│   │   │   └── Navigation.jsx
│   │   ├── products/
│   │   │   ├── ProductCard.jsx
│   │   │   ├── ProductGrid.jsx
│   │   │   ├── ProductDetails.jsx
│   │   │   └── ProductFilters.jsx
│   │   ├── cart/
│   │   │   ├── CartSidebar.jsx
│   │   │   ├── CartItem.jsx
│   │   │   └── CartSummary.jsx
│   │   ├── ui/
│   │   │   ├── Button.jsx
│   │   │   ├── Input.jsx
│   │   │   ├── Modal.jsx
│   │   │   └── LoadingSpinner.jsx
│   │   └── common/
│   │       ├── SearchBar.jsx
│   │       └── ErrorBoundary.jsx
│   ├── lib/
│   │   ├── shopify/
│   │   │   ├── client.js
│   │   │   ├── queries.js
│   │   │   └── mutations.js
│   │   ├── prisma.js
│   │   └── utils.js
│   ├── store/
│   │   ├── index.js
│   │   ├── reducers/
│   │   │   ├── cartReducer.js
│   │   │   ├── productsReducer.js
│   │   │   └── uiReducer.js
│   │   ├── actions/
│   │   │   ├── cartActions.js 
│   │   │   ├── productsActions.js
│   │   │   └── uiActions.js
│   │   └── hooks/
│   │       └── useStore.js
│   ├── styles/
│   │   └── globals.css
│   └── types/
│       └── index.ts
├── prisma/
│   ├── schema.prisma
│   └── migrations/
├── public/
│   ├── images/
│   └── icons/
├── .env.local
├── .env.example
├── next.config.js
├── package.json
├── tailwind.config.js
└── README.md
```
---
