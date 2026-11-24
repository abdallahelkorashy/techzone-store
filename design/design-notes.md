# TechZone design inventory

Source: Figma file `vCD5guwBSUvAA1wXaNcp5Q` (page 0:1), verified 2026-11-24 by direct layer selection in the design file and prototype rendering of every node.

| # | Figma frame name | Node ID | Capture | Contents |
|---|---|---|---|---|
| 1 | Home | 1-1387 | 01-home.png | Landing: hero, categories, featured, best sellers, promo countdown, newsletter |
| 2 | Shop | 1-4103 | 02-shop.png | Search landing with Design State Switcher (Initial/Results/No Results strip) |
| 3 | Search | 1-5133 | 03-search.png | Results grid for "Gaming Laptop" with filters and pagination |
| 4 | Categories | 1-2931 | 04-categories.png | Category catalog landing |
| 5 | Product | 1-2127 | 05-product.png | Product detail with configuration options and specs |
| 6 | Cart | 1-2 | 06-cart.png | Cart with order summary and recommendations |
| 7 | Checkout | 1-4591 | 07-checkout.png | Checkout step 2: shipping info |
| 8 | Payment | 1-3542 | 08-payment.png | Checkout step 3: payment method |
| 9 | Login & Register | 1-2773 | 09-login-register.png | Sign-in; Create Account is a tab variant in-frame |
| 10 | My Account Dashboard | 1-689 | 10-my-account.png | Account dashboard with orders, wishlist, security |

## States

- Shop (1-4103) embeds a "Design State Switcher": State 1 Initial (the frame's default), State 2 Results (separate frame Search 1-5133), State 3 No Results (decorative; confirmed by the designer that no designed state exists).
- Login & Register contains its Create Account variant as an in-frame tab.

## Prototype wiring observed

- Home -> Search frame via header search input; search button on Shop -> Search (results).
- Home -> Product via nav "Product"; Home -> Cart via nav "Cart"; Home -> My Account via avatar.
- Cart -> Checkout via "Proceed to Checkout". Checkout "Continue to Payment" and nav Shop/Categories links are not wired in the current prototype version.
- My Account -> Login & Register via "Sign Out".

## Capture method

Prototype URL per node (`node-id=<ID>`), viewport 1440x4400, `scaling=min-zoom`, `content-scaling=fixed`; dark canvas margins trimmed to the frame edge (1280px output width). Layout, header and footer verified visually per frame.
