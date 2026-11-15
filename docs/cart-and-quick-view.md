# Cart, cart drawer and quick view

## Cart type

**Theme settings → Cart → Cart type** has three options:

| Option | What happens when a customer adds to cart |
|---|---|
| **Drawer** (default) | A cart slides in from the side, where customers can change quantities and go to checkout. |
| **Page** | The customer goes to the cart page. |
| **Notification** | A small confirmation with a **View cart** link appears. |

## Cart drawer

The **Cart drawer** section is in the **Overlays** group. In the editor, open any page and find **Overlays** at the bottom of the section list. It's used when **Cart type** is **Drawer**.

| Setting | What it does |
|---|---|
| **Free shipping threshold** | Amount in your store currency for the free shipping progress bar. Set it to `0` to hide the bar. |
| **Celebrate free shipping** | A short confetti burst when the goal is reached. Skipped for visitors who prefer reduced motion. |
| **Show order note** | Adds an order note field. |
| **Show discount code field** | Lets customers apply and remove discount codes in the drawer. |
| **Gift wrap product** | Shows a checkbox that adds this product to the cart once. Create a product such as "Gift wrap" and select it here. |
| **Show undo after removing an item** | Shows an **Undo** link after an item is removed, for the **Undo time** you set (3–15 seconds). |
| **Show product recommendations** | Shows products under the cart items, with a **Heading**, a **Source** (**Complementary** from the Search & Discovery app, or **Related**) and a **Number of products**. |
| **Require terms agreement before checkout** | Customers must tick a checkbox before checkout. Edit the text in **Terms label**. |
| **Show payment icons** | Shows your accepted payment methods. |
| **Text under checkout button** | A short line such as "Secure checkout". |
| **Selling point 1–3** | Short reassurance lines, such as "Free returns within 30 days". |

## Cart page

The **Cart** section on the cart page has the same free shipping, celebration, gift wrap, terms, payment icon and trust text settings, plus:

- **Show shipping estimator**: customers enter a country and postal code to see shipping rates.
- **Show dynamic checkout buttons**: accelerated checkout buttons such as Shop Pay or PayPal, when available.

The cart summary is built from blocks that you can reorder: **Free Shoping Progress**, **Discount code**, **Total price**, **Checkout button**, **Order note**, **Trust badges** and app blocks.

The cart page also supports line and cart discounts, subscriptions (selling plans) and unit prices.

## Quick view

To turn quick view on, go to **Theme settings → Cart → Enable quick view**. A button appears on product cards (on hover on desktop, always on mobile). It opens the product's images, variants, price and add-to-cart button without leaving the page.

## Quick add

**Theme settings → Product Card → Quick add** adds an add to cart control to every product card:

| Option | What it shows |
|---|---|
| **None** | No quick add. |
| **Button** | A button that slides up over the bottom of the card image on hover (desktop). On phones, a plus icon is shown instead. |
| **Icon** | A small round plus button in the corner of the card image, shown on hover on desktop and always on phones. |

Products with a single variant are added to the cart right away. For products with options, the button reads **Choose options** and opens a compact variant picker first.

Quick add and quick view can be used together. There is also an older **Show add to cart button** setting in the same group, which shows a button and an optional quantity field under the card instead.

## Product badges

Badge settings (position, shape, sale color, sold out and "New") are in **Theme settings → Badges**. Sale and stock labels are in **Theme settings → Product Card**. See [Global settings](global-settings.md#badges).

To show your own badge, such as "Best seller":

1. Go to **Settings → Custom data → Products → Add definition**.
2. Set **Name** to `Label`, **Namespace and key** to `custom.label`, and **Type** to *Single line text*.
3. Fill in the badge text on any product.

To use a different metafield, enter its `namespace.key` in **Theme settings → Product Card → Custom product label**. Products that already use a `custom.badge` metafield keep working.
