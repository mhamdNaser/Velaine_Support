# Global settings

Global settings apply to the whole store. In the theme editor, click the brush icon (**Theme settings**) in the left sidebar. Each group below matches a group in that panel, in the same order.

Many of these settings are set for you by the Velaine style. See [Theme styles and colors](theme-styles.md).

## Logo and favicon

| Setting | What it does |
|---|---|
| **Default logo** | The logo shown in the header. |
| **Logo size** | Logo width on desktop, 20–300 px. |
| **Logo width on mobile** | Logo width on phones, 20–200 px. |
| **Inverse logo** | A light version of the logo. It is used when the header background is dark, and by the transparent header when **Transparent text color** is **Light**. |
| **Favicon** | The small icon in the browser tab. Use a square image, at least 32 × 32 px. |

## Page layout

| Setting | What it does |
|---|---|
| **Page width** | Maximum content width: **Narrow**, **Normal**, **Wide** or **Full width**. |
| **Horizontal padding** | Space on the left and right of the page on desktop. |
| **Side padding on mobile** | Space on the left and right of the page on phones. |
| **Vertical padding** | Space above and below the page content. |
| **Space between sections** | A vertical gap added between all sections on every page. |
| **Show back-to-top button** | Adds a round button that scrolls back to the top of the page. |
| **Back to top button position** | **Start** or **End** of the screen. In right-to-left languages, start is the right side. |
| **Scrollbar** | **Accent color**, **Minimal** or **Browser default**. |

## Typography

| Setting | What it does |
|---|---|
| **Body font** | Font for body text, from the Shopify font library. |
| **Heading font** | Font for headings. |
| **Base font size** | Body text size, 12–24 px. |
| **Heading size** | Scales all large headings, 70–150%. |
| **Font weight** | Body text weight: **Lighter**, **Normal**, **Bold** or **Bolder**. |
| **Heading font weight** | **Normal**, **Bold** or **Extra bold**. |
| **Heading letter case** | **Same as body**, **None**, **Uppercase**, **Capitalize** or **Lowercase**. |
| **Heading letter spacing** | Space between letters in headings, -4 to 10 px. |
| **Heading line height** | **Default**, **Tight**, **Snug**, **Normal** or **Relaxed**. |
| **Text transform** | Letter case for body text. |
| **Letter spacing** | Space between letters in body text, -2 to 8 px. |
| **Line height** | Body text line height: **Normal**, **Relaxed** or **Loose**. |

## Animations

| Setting | What it does |
|---|---|
| **Image hover style** | How product images react on hover: **Basic zoom**, **Quick zoom**, **Point zoom**, **Zoom and rotate**, **Brightness shift**, **Pan horizontally**, **Pan vertically**, **Blur effect**, **Color overlay** or **None**. |
| **Card hover effect** | How the whole product card reacts on hover: **None**, **Lift**, **Scale up** or **Subtle zoom**. |
| **Image reveal on scroll** | Entrance effect for images as they scroll into view: **None**, **Fade up**, **Scale in**, **Curtain wipe**, **Shutter**, **Iris**, **Blur in** or **Grayscale to color**. |
| **Section animation on scroll** | **None**, **Fade in whole section**, or **Staggered parts** (headings, text and cards appear one after another). |
| **Heading animation** | Effect for main headings as they scroll into view: **None**, **Fade up**, **Slide up from mask**, **Word by word** or **Blur in**. |
| **Animation speed** | **Slow**, **Normal** or **Fast**. |
| **Scroll animations on mobile** | Turn off to skip scroll animations on phones. |

Visitors who set "reduce motion" on their device don't see scroll animations. See [Visual effects and accessibility](effects-and-accessibility.md).

## Button

| Setting | What it does |
|---|---|
| **Hover effect** | **Change color**, **Persistent shadow**, **Temporary shadow** or **None**. |
| **Button corner radius** | 0 px gives square corners, 40 px gives fully rounded buttons. |
| **Button border thickness** | 0–4 px. |
| **Button text case** | **None**, **Uppercase** or **Capitalize**. |
| **Input field corner radius** | Corner radius of text fields, such as search and email fields. |
| **Primary button style** | **Solid** or **Outline**. |
| **Secondary button style** | **Outline**, **Solid** or **Text link**. |
| **Button font weight** | **Regular**, **Medium**, **Semibold** or **Bold**. |

## Colors

| Setting | What it does |
|---|---|
| **Color schemes** | The four color schemes used by sections. See [Color schemes](theme-styles.md#color-schemes). |
| **Header background color** | Background color of the header. |
| **Footer background color** | Background color of the footer. |
| **Color scheme** | The default scheme for the page background. |
| **Dark mode** | **Off**, **Automatic** (follows the visitor's device) or **Automatic with toggle button** (adds a button so visitors can switch). |
| **Dark mode color scheme** | The scheme used for every section while dark mode is on. |

## Color Mappings

Used by color swatches on product cards and product pages.

| Setting | What it does |
|---|---|
| **Color option labels** | Option names that count as color options, separated by commas, for example `color,colour,اللون`. |
| **Color Map (JSON format)** | Color values for option values that Shopify doesn't recognize, for example `{"Red": "#ff0000", "Navy": "#1f2a44"}`. |

Swatch colors and images set on option values in Shopify admin take priority over this map.

## Mobile menu

| Setting | What it does |
|---|---|
| **Mobile menu** | The menu shown in the mobile menu. |
| **Menu width** | **Full screen** or **Side drawer**. |
| **Open from** | **Start** or **End** of the screen. |
| **Link size** | **Small**, **Medium** or **Large**. |
| **Active link style** | How the link for the current page is marked: **Filled** or **Accent text**. |
| **Show search** | Adds a search field at the top of the menu. |
| **Show account link** | Adds a link to the customer account. |
| **Show social icons** | Adds the social links from **Social media icons**. |
| **Submenu style** | **Accordion** (submenus expand in place) or **Slide** (submenus open as a new panel). |

## Product Card

| Setting | What it does |
|---|---|
| **Enable color swatches** | Shows color swatches under the product title. |
| **Product cards text alignment** | **Left**, **Center** or **Right**. |
| **Show sale label** | Shows a sale badge on discounted products. |
| **Sale label price** | Text of the sale badge: **None**, **Percentage** (for example -20%) or **Amount** (for example -$10). |
| **Show stock label** | Shows a low stock badge when stock is below the threshold. |
| **Low stock quantity threshold** | 1–30. |
| **Show 'price varies' label** | Shows "From" when variants have different prices. |
| **Custom product label** | A product metafield (as `namespace.key`, default `custom.label`) whose value is shown as a badge. If it's empty, the theme uses the `custom.badge` metafield. |
| **Show product stock** | Shows the remaining quantity on the card. |
| **Stock quantity threshold** | Stock is shown only below this number. |
| **Always show stock** | Shows stock for every product, whatever the quantity. |
| **Show product rating** | Shows stars from a reviews app that uses Shopify's standard rating metafields. |
| **Show vendor name** | Shows the vendor above the title. |
| **Show add to cart button** | Adds an add to cart button under each card. |
| **Add to cart button text** | Button text. |
| **Show quantity input** | Adds a quantity field next to the button. |
| **Enable pre-order** | Lets customers order sold-out products that continue selling when out of stock. |
| **Show inventory when pre-order is active** | Shows the inventory count for pre-order products. |
| **Pre-order button text** | Button text for pre-order products. |
| **Choose short description source** | **None**, **Use main product description** or **Use custom text**. |
| **Custom short description text** | Text shown when the source is custom text. |
| **Use capital letters for product titles** | Shows titles in uppercase. |
| **image product Card Shadow** | Adds a shadow to card images, with **shadow color**, **shadow value** and **shadow blur**. |
| **Quick add** | **None**, **Button** or **Icon**. See [Quick add](cart-and-quick-view.md#quick-add). |

## Cards and images

| Setting | What it does |
|---|---|
| **Card style** | **Plain**, **Bordered**, **Shadow** or **Filled**. |
| **Card corner radius** | 0–32 px. |
| **Card padding** | Space inside the card, 0–32 px. |
| **Image ratio** | **Square**, **Portrait**, **Landscape** or **Adapt to image**. |
| **Image fit** | **Show whole image** or **Fill the frame** (crops to the ratio). |
| **Image corner radius** | 0–32 px. |
| **Show second image on hover** | Shows the product's second media item on hover. |
| **Show currency code** | Shows prices as `$10.00 USD` on cards, product pages and quick view. Useful if you sell in several currencies. |

## Badges

| Setting | What it does |
|---|---|
| **Position** | **Bottom of image** or **Top of image**. |
| **Shape** | **Tab**, **Pill** or **Square**. |
| **Sale badge color** | Leave empty to use the accent color. |
| **Show sold out badge** | Shows a badge on sold-out products. |
| **"New" badge duration (days)** | Products published within this many days get a "New" badge. 0 turns it off. |

## Cart

| Setting | What it does |
|---|---|
| **Cart type** | **Drawer**, **Page** or **Notification**. See [Cart and quick view](cart-and-quick-view.md). |
| **Enable quick view** | Adds a quick view button to product cards. |

## Drawers and popups

These settings apply to the cart drawer, filter drawer, mobile menu, quick view and popups.

| Setting | What it does |
|---|---|
| **Background overlay opacity** | How dark the page behind an open drawer or popup gets, 0–90%. |
| **Blur page behind overlays** | Blurs the page behind an open drawer or popup. |
| **Drawer and popup corner radius** | 0–32 px. |
| **Drawer drop shadow** | Adds a shadow to drawers. |
| **Popover drop shadow** | Adds a shadow to dropdowns and popovers. |

## Search

| Setting | What it does |
|---|---|
| **Enable search suggestions** | Shows results as customers type in the header search. |
| **Number of suggested products** | 3–10. |
| **Show price in suggestions** | Shows the price next to each suggested product. |
| **Show vendor in suggestions** | Shows the vendor next to each suggested product. |

See [Collections, search and blog](collection-search-blog.md#search).

## Social Media Icons

| Setting | What it does |
|---|---|
| **Icon style** | **Outlined circle**, **Filled circle** or **Icon only**. |
| **Icon size** | **Small**, **Medium** or **Large**. |
| **WhatsApp URL** to **Telegram URL** | Links for WhatsApp, Facebook, Instagram, Twitter, TikTok, YouTube, LinkedIn, Snapchat, Pinterest and Telegram. Only filled-in links are shown. |

The links are used in the header top bar, footer, mobile menu and email signup sections.

## Visual effects

| Setting | What it does |
|---|---|
| **Smooth page transitions** | Pages fade into each other in supported browsers. |
| **Custom cursor** | **Off**, **Accent dot**, or **Accent dot with "View" on products**. |
| **Magnetic buttons** | Buttons move slightly toward the pointer. |
| **3D tilt on product cards** | Cards tilt as the pointer moves over them. |
| **Film grain texture** | A subtle noise texture over the whole page, 0–15%. 0 turns it off. |
| **Show "Continue where you left off"** | Reminds returning visitors of the last product they viewed. |

Details are in [Visual effects and accessibility](effects-and-accessibility.md).

## Accessibility

| Setting | What it does |
|---|---|
| **Show accessibility panel** | Adds a button that opens a panel where visitors can enlarge text, raise contrast, underline links, stop animations and switch to a readable font. |
| **Panel button position** | **Start** or **End** of the screen. |
