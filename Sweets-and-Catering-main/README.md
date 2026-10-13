# Sweets and Catering

A responsive sweets and catering website with a product catalogue, shopping cart, festival gift boxes, bulk-order enquiry, and direct UPI checkout interface.

## Features

- Sweets and namkeen catalogue
- Product search and filters
- Shopping cart
- Festival gift boxes
- Bulk catering enquiry
- Responsive mobile design

## Run locally

Serve the static site from the project root:

```powershell
npx --yes http-server . -p 5500 -a 127.0.0.1 -c-1
```

The backend runs separately from `server/` and requires a configured PostgreSQL connection in `server/.env`.
