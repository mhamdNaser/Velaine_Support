# Product pages

The product page uses the **Product information** section, followed by sections such as **Product recommendations**, **Recently viewed** and **Products from Same Vendor**.

## Section settings

| Setting | What it does |
|---|---|
| **Color scheme** | Colors of the section. |
| **Show payment icons** | Shows your accepted payment methods under the buy buttons. |
| **Gallery layout** | **Thumbnails below**, **Thumbnails beside**, **Stacked** or **2-column grid**. Phones always use a swipe carousel with dots. |
| **Enable hover zoom on desktop** | Zooms into the image under the pointer. |
| **Open images in fullscreen lightbox** | Clicking an image opens it full screen. |
| **Hide media of other variants** | Shows only the selected variant's image, plus media that isn't assigned to any variant. |
| **Show sticky add to cart bar** | A bar with the product, price and add to cart button appears once the buy buttons scroll out of view. Needs the **Buy buttons** block. |
| **Position**, **Show on desktop**, **Show on mobile** | Where the sticky bar appears: **Bottom** or **Top**, and on which devices. |

## Blocks

The section is built from blocks. You can reorder them or remove the ones you don't need. Blocks marked "once" can be added one time.

**Product details**

| Block | Settings and notes |
|---|---|
| Vendor (once) | **Vendor style**: **Text** or **Image** (upload a **Vendor image**). |
| Title (once) | The product title. |
| Price (once) | Sale price, unit price, taxes and shipping note. |
| Short description (once) | Uses the `custom.short_description` metafield when set, otherwise the start of the product description. **Maximum characters**: 50–500. |
| Description (once) | The full product description. |
| SKU (once) | The variant SKU. |
| Product codes (once) | **Show SKU** and **Show barcode**. |

**Buying**

| Block | Settings and notes |
|---|---|
| Variant picker (once) | **Swatch style**: **Color** (swatch colors and images set on option values in Shopify admin, or the **Color Map** in theme settings) or **Variant image**. **Option style**: **Buttons** or **Dropdown**. |
| Buy buttons (once) | Quantity rules, subscriptions, gift card recipient form, Shop Pay Installments and pre-order. **Show dynamic checkout buttons** adds buttons such as PayPal or Apple Pay. |
| Quick order list (once) | A table with a quantity field for each variant, so customers can add several variants at once. Useful for wholesale. Hidden on products without variants. |
| Inventory status (once) | **Low stock threshold**, **Show low stock bar** and **Show stock count**. |
| Low stock message (once) | An urgency message when stock is at or below **Show when stock is at or below**. In **Message**, use `[count]` for the remaining quantity. Optional progress bar. |
| Pickup availability (once) | Store pickup availability, from **Settings → Locations**. |
| Estimated delivery (once) | Shows an expected delivery date range from **Minimum delivery days** and **Maximum delivery days**, optionally skipping weekends. With **Show countdown**, it also shows how long is left to order before the **Order cut-off hour** to ship today. Tick the days you ship on. |
| Complementary products (once) | "Pairs well with" products, picked in the Search & Discovery app. **Product count**: 1–10. |

**Information and trust**

| Block | Settings and notes |
|---|---|
| Collapsible tab | A row that expands. Set a **Heading**, an **Icon**, and the **Content** or **Page content**. Connect **Content** to a rich text metafield to show different text per product. **Open by default** is optional. |
| Size chart (once) | A link that opens a drawer with **Page content** and/or **Content**. |
| Icons with text | Up to three icons with headings, such as "Free shipping". **Layout**: **Row** or **List**. Use a built-in icon or a **Custom image**. |
| Selling points | Up to five short lines with check marks. |
| Trust badge (once) | A heading such as "Guaranteed safe checkout" with your payment icons. |
| Guarantee (once) | A **Title**, **Image** and **Description**. |
| Share (once) | Share links for WhatsApp, Facebook, X, Pinterest, Messenger and email, plus **Show copy link**. |

**Layout and custom content**

| Block | Settings and notes |
|---|---|
| Text | Rich text with a **Text style**: **Body**, **Subtle**, **Large** or **Uppercase caption**. |
| Spacer | **Height** and an optional divider line. |
| Custom liquid | App snippets or other Liquid code. |
| Apps | Blocks from apps you install. |

## Related sections

| Section | Settings |
|---|---|
| Product recommendations | **Heading**, **Recommendation type** (**Related products** or **Complementary products**), **Maximum products to show**, **Slider**, **Columns on desktop** and **Show slider arrows**. |
| Recently Viewed | Products the customer viewed earlier, stored in their browser. |
| Products from Same Vendor | More products from the same vendor. |

## Tips

- Give every product image **Alt text** in Shopify admin. The theme uses it for accessibility and SEO.
- Assign an image to each variant, so the gallery switches when a customer picks a variant.
- For "Pairs well with" suggestions, install the Search & Discovery app and pick complementary products there. Then use the **Complementary products** block or **Product recommendations → Recommendation type: Complementary products**.
- To show a short summary under the title, add a product metafield `custom.short_description` (multi-line text) and the **Short description** block.
