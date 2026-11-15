# Header, menus and mega menu

The **Header** section is in the **Header** group at the top of the section list, together with the **Announcement bar**.

## Menu

1. Create a menu in **Online Store → Navigation**. Nest links to build submenus, up to three levels.
2. In the editor, open the **Header** section, add a **Menu block** and select your menu.

If no menu is selected, the header shows the `main-menu` menu. The **Menu block** also has **Link background color** and **Link text color** settings.

## Header settings

| Setting | What it does |
|---|---|
| **Color scheme** | Colors of the header. **Theme settings → Colors → Header Background Color** sets its background. |
| **Header position** | See [Sticky header](#sticky-header). |
| **Transparent header** | See [Transparent header](#transparent-header). |
| **Show menu border** | Adds a line under the header, with **Border bottom** (**None**, **Solid** or **Dashed**), **Menu item border width** and **Menu item border color**. |
| **Logo type** | **None**, **Logo** (the image from **Theme settings → Logo and favicon**) or **Text** (the store name). |
| **Account menu** | **Shopify account** shows *Sign in with Shop* and needs new customer accounts. **Classic dropdown** shows a simple menu with account links. |
| **Customer account menu** | The menu shown inside the Shopify account menu. |
| **Menu style** | **Dropdown** or **Mega menu**. |
| **Show collection images** | Mega menu only. Adds an image above second-level links that point to a collection. |
| **Item hover effect** | **Light underline**, **Underline** or **Double line**. |

## Menu style

- **Dropdown:** a classic list that opens under each menu item. Third-level links open to the side.
- **Mega menu:** a full-width panel. Second-level links become column titles and third-level links are listed under them.

## Mega menu images

1. Set **Menu style** to **Mega menu**.
2. Add a **Mega menu promo** block to the Header section.
3. In **Menu item**, enter the exact title of the top-level menu item, for example `Women`.
4. Add an **Image**, a **Heading**, **Text** and a **Link**.

You can add up to 6 promos. Several promos can point to the same menu item.

## Sticky header

**Header → Header Position** has four options:

| Option | Behavior |
|---|---|
| **Default** | The header scrolls away with the page. |
| **Fixed** | The header stays at the top while the page scrolls. |
| **Sticky** | The header stays at the top while the page scrolls. |
| **Hide on scroll down, show on scroll up** | The header hides as the customer scrolls down and comes back when they scroll up. Visitors who prefer reduced motion get a header that always stays visible. |

## Transparent header

**Transparent header** places the header over the first section when that section is a full-width image or video, such as an Image Banner, Slider or Video. The header turns solid after the customer scrolls.

| Setting | Options |
|---|---|
| **Transparent header** | **Off**, **Home page only**, or **All pages with a full-width hero**. |
| **Transparent text color** | **Light** (uses the **Inverse logo** from theme settings) or **Dark**. Pick the one that reads well on your hero image. |

## Top bar

Add a **top header** block to show a short text line above the header. The top bar also shows your Facebook and Instagram links and a language selector when the store has more than one language.

## Header search

The search icon opens a search panel. As customers type, it shows suggested products, collections, pages and articles. Recent searches are kept in the panel and can be cleared. Search options are in **Theme settings → Search**. See [Collections, search and blog](collection-search-blog.md#search).

## Announcement bar

| Setting | What it does |
|---|---|
| **Enable announcement bar** | Turns the bar on or off. |
| **Announcement text** | Used when no **Message** blocks are added. |
| **Display** | **Rotate messages** (one at a time) or **Scrolling marquee**. |
| **Auto-rotate messages**, **Change message every**, **Show arrows** | Rotation options. |
| **Marquee duration** | Marquee speed. Lower is faster. |
| **Font Size (px)**, **Font weight**, **Font style**, **Text alignment** | Text style. |

Each **Message** block has **Text**, a **Link** and an optional **Countdown end** (`YYYY-MM-DD HH:MM` in the store time zone), which shows a live countdown next to the message.

## Mobile menu

Mobile menu options are global settings in **Theme settings → Mobile menu**: the menu to show, full-screen or side drawer, the side it opens from, link size, active link style, accordion or slide submenus, and optional search, account link and social icons. See [Global settings](global-settings.md#mobile-menu).

On phones, the **Mobile navigational bar** section adds a bar fixed to the bottom of the screen with links to the home page, the account, the menu and the cart.

## Keyboard support

Menus open with **Tab** or **Arrow down** and close with **Esc**. The mobile menu keeps keyboard focus inside it while it's open.
