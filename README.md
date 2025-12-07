# solid-octo-enigma
# Shopify Integration

lib/shopify/client.js - API client
lib/shopify/queries.js - GraphQL queries
lib/shopify/mutations.js - GraphQL mutations

# Redux Store

store/index.js - Store implementation
store/reducers/ - State reducers
store/hooks/useStore.js - React hook

# API Routes

app/api/shopify/products/route.js - Fetch products
app/api/shopify/cart/route.js - Create cart
app/api/shopify/webhooks/route.js - Handle webhooks

# Pages

***app/page.js - Home (Server Component)***
app/products/page.js - Products (Client Component)
app/products/[handle]/page.js - Product detail
