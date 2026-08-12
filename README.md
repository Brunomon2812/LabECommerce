# LabECommerce

An e-commerce storefront for a meteorite shop, built with React.

**Live demo:** https://ruddy-room.surge.sh/

![LabECommerce storefront](./src/img/loja.png)

## About

A shopping experience built end to end on the client: product filters, a cart that survives a
page reload, and a running total.

The cart is persisted to the browser's `localStorage`, so refreshing the page keeps the items and
the total intact rather than starting over.

## Features

- Product grid with filters for minimum price, maximum price and name
- Sort products by price
- Add products to the cart and remove them again
- Running order total
- Cart persisted across reloads via `localStorage`
- Responsive down to mobile widths

## Tech stack

- [React](https://react.dev/) (class components)
- [Styled Components](https://styled-components.com/)

## Running it locally

Requires Node.js.

```bash
git clone https://github.com/Brunomon2812/LabECommerce.git
cd LabECommerce
npm install
npm start
```

The app runs on http://localhost:3000 by default.

## Status

Complete.

## Screenshots

![Storefront](./src/img/loja.png)

<img alt="Mobile layout" src="https://user-images.githubusercontent.com/22090173/174457918-0308156b-148e-4a4a-b4de-ef5a61f9edc2.png" width="314"/>
<img alt="Mobile cart" src="https://user-images.githubusercontent.com/22090173/174457919-1665d128-377a-476d-a7b7-9dbddb68fa9a.png" width="314"/>

## Team

Built as a group project (Group 9):

- João Gabriel Colodetti do Carmo
- Pétrick Machado de Almeida Grillo
- [Bruno Adonai Rodrigues Monteiro](https://github.com/Brunomon2812)

> The source is still written in Portuguese: this was a group codebase, so the identifiers and
> UI strings are left as the team wrote them.
