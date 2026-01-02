# Getting Started

To run this application:

```bash
bun i
bun dev
```

# Repro Info

As you can see, the dev server runs fine. However, when you navigate to a non-existent route, you get "Cannot GET /[route]" instead of the NotFound components which are set in the route (router.tsx) and in the root route (\_\_root.tsx).

Using nitro-nightly crashes the dev server.
