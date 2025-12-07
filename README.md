## 📁 Project Structure
```
shopify-nextjs-store/
├── src/
│   ├── app/
│   │   ├── layout.js
│   │   ├── page.js
│   │   ├── globals.css
│   │   ├── providers.jsx
│   │   ├── products/
│   │   │   ├── page.js
│   │   │   └── [handle]/
│   │   │       ├── page.js
│   │   │       └── loading.js
│   │   ├── cart/
│   │   │   └── page.js
│   │   ├── checkout/
│   │   │   ├── page.js
│   │   │   └── success/
│   │   │       └── page.js
│   │   ├── categories/
│   │   │   └── [category]/
│   │   │       └── page.js
│   │   ├── search/
│   │   │   └── page.js
│   │   └── api/
│   │       └── shopify/
│   │           ├── products/
│   │           │   └── route.js
│   │           ├── product/
│   │           │   └── [handle]/
│   │           │       └── route.js
│   │           ├── search/
│   │           │   └── route.js
│   │           ├── cart/
│   │           │   ├── route.js
│   │           │   └── [cartId]/
│   │           │       └── route.js
│   │           └── webhooks/
│   │               ├── orders/
│   │               │   └── route.js
│   │               └── products/
│   │                   └── route.js
│   ├── components/
│   │   ├── layout/
│   │   │   ├── Header.jsx
│   │   │   ├── Footer.jsx
│   │   │   ├── Navigation.jsx
│   │   │   ├── MobileMenu.jsx
│   │   │   └── Breadcrumbs.jsx
│   │   ├── products/
│   │   │   ├── ProductCard.jsx
│   │   │   ├── ProductGrid.jsx
│   │   │   ├── ProductList.jsx
│   │   │   ├── ProductDetails.jsx
│   │   │   ├── ProductGallery.jsx
│   │   │   ├── ProductFilters.jsx
│   │   │   ├── ProductSort.jsx
│   │   │   ├── QuickView.jsx
│   │   │   └── RelatedProducts.jsx
│   │   ├── cart/
│   │   │   ├── CartSidebar.jsx
│   │   │   ├── CartItem.jsx
│   │   │   ├── CartSummary.jsx
│   │   │   ├── CartEmpty.jsx
│   │   │   └── MiniCart.jsx
│   │   ├── checkout/
│   │   │   ├── CheckoutForm.jsx
│   │   │   ├── ShippingForm.jsx
│   │   │   ├── PaymentForm.jsx
│   │   │   └── OrderSummary.jsx
│   │   ├── ui/
│   │   │   ├── Button.jsx
│   │   │   ├── Input.jsx
│   │   │   ├── Select.jsx
│   │   │   ├── Modal.jsx
│   │   │   ├── Drawer.jsx
│   │   │   ├── Toast.jsx
│   │   │   ├── Badge.jsx
│   │   │   ├── Card.jsx
│   │   │   ├── LoadingSpinner.jsx
│   │   │   ├── Skeleton.jsx
│   │   │   └── ErrorBoundary.jsx
│   │   ├── search/
│   │   │   ├── SearchBar.jsx
│   │   │   ├── SearchResults.jsx
│   │   │   ├── SearchSuggestions.jsx
│   │   │   └── SearchFilters.jsx
│   │   └── common/
│   │       ├── Image.jsx
│   │       ├── Price.jsx
│   │       ├── Rating.jsx
│   │       ├── Pagination.jsx
│   │       └── NotificationToast.jsx
│   ├── store/
│   │   ├── index.js
│   │   ├── slices/
│   │   │   ├── cartSlice.js
│   │   │   ├── productsSlice.js
│   │   │   ├── uiSlice.js
│   │   │   ├── userSlice.js
│   │   │   └── checkoutSlice.js
│   │   ├── hooks/
│   │   │   ├── useStore.js
│   │   │   ├── useCart.js
│   │   │   ├── useProducts.js
│   │   │   └── useNotifications.js
│   │   └── middleware/
│   │       ├── logger.js
│   │       └── persistence.js
│   ├── lib/
│   │   ├── shopify/
│   │   │   ├── client.js
│   │   │   ├── queries/
│   │   │   │   ├── products.js
│   │   │   │   ├── cart.js
│   │   │   │   ├── collections.js
│   │   │   │   └── customer.js
│   │   │   ├── mutations/
│   │   │   │   ├── cart.js
│   │   │   │   ├── checkout.js
│   │   │   │   └── customer.js
│   │   │   ├── transformers.js
│   │   │   └── constants.js
│   │   ├── prisma.js
│   │   ├── utils/
│   │   │   ├── formatting.js
│   │   │   ├── validation.js
│   │   │   ├── price.js
│   │   │   └── date.js
│   │   └── hooks/
│   │       ├── useLocalStorage.js
│   │       ├── useDebounce.js
│   │       └── useMediaQuery.js
│   ├── styles/
│   │   ├── globals.css
│   │   └── themes/
│   │       ├── light.css
│   │       └── dark.css
│   └── types/
│       ├── product.ts
│       ├── cart.ts
│       ├── checkout.ts
│       └── index.ts
├── prisma/
│   ├── schema.prisma
│   ├── seed.js
│   └── migrations/
├── public/
│   ├── images/
│   │   ├── logo.svg
│   │   └── placeholder.png
│   ├── icons/
│   └── fonts/
├── tests/
│   ├── unit/
│   │   ├── components/
│   │   ├── store/
│   │   └── lib/
│   ├── integration/
│   └── e2e/
├── .env.local
├── .env.example
├── .eslintrc.js
├── .prettierrc
├── .gitignore
├── next.config.js
├── tailwind.config.js
├── postcss.config.js
├── package.json
├── tsconfig.json (if using TypeScript)
└── README.md
```
---
