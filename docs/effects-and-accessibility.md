# Visual effects and accessibility

This page covers the settings that change how the store moves and feels, and the tools that make it easier to use for everyone.

## Animations

Go to **Theme settings → Animations**.

| Setting | Options |
|---|---|
| **Image hover style** | **Basic zoom**, **Quick zoom**, **Point zoom**, **Zoom and rotate**, **Brightness shift**, **Pan horizontally**, **Pan vertically**, **Blur effect**, **Color overlay**, **None**. |
| **Card hover effect** | **None**, **Lift**, **Scale up**, **Subtle zoom**. |
| **Image reveal on scroll** | **None**, **Fade up**, **Scale in**, **Curtain wipe**, **Shutter**, **Iris**, **Blur in**, **Grayscale to color**. |
| **Section animation on scroll** | **None**, **Fade in whole section**, **Staggered parts**. |
| **Heading animation** | **None**, **Fade up**, **Slide up from mask**, **Word by word**, **Blur in**. |
| **Animation speed** | **Slow**, **Normal**, **Fast**. |
| **Scroll animations on mobile** | Turn off to keep phones free of scroll animations. |

Tips:

- Pick one or two strong effects. For example, **Curtain wipe** images with **Slide up from mask** headings, and keep the rest subtle.
- If the store feels busy on phones, turn off **Scroll animations on mobile**.

## Visual effects

Go to **Theme settings → Visual effects**. All of these are off by default.

| Setting | What it does |
|---|---|
| **Smooth page transitions** | Pages fade into each other when customers follow a link. Works in browsers that support view transitions, such as Chrome, Edge and Safari. Other browsers load pages normally. |
| **Custom cursor** | Replaces the pointer with a small accent dot that grows over links and buttons. **Accent dot with "View" on products** also shows the word "View" over product images. Only used with a mouse or trackpad. |
| **Magnetic buttons** | Buttons move slightly toward the pointer. |
| **3D tilt on product cards** | Cards tilt as the pointer moves over them. |
| **Film grain texture** | A subtle noise texture over the whole page, 0–15%. Values between 3 and 6 work well with dark or editorial styles. |
| **Show "Continue where you left off"** | When a visitor comes back, a small card in the corner links to the last product they viewed. They can close it. It isn't shown on product pages. |

Animated sections, such as **Animated heading**, **Counters**, **Scrolling story**, **Before and after** and **360° spin**, are described in the [Sections library](sections-library.md).

## Dark mode

Go to **Theme settings → Colors → Dark mode**:

| Option | What happens |
|---|---|
| **Off** | No dark mode. |
| **Automatic** | The store follows the visitor's device setting. |
| **Automatic with toggle button** | Follows the device setting, and adds a round moon button so visitors can switch. Their choice is remembered on their device. |

While dark mode is on, every section uses the **Dark mode color scheme** (Scheme 3 by default). See [Theme styles and colors](theme-styles.md#dark-mode).

## Reduced motion

Visitors can ask their device to reduce motion. When they do, the theme turns off scroll reveals, heading animations, page transitions, magnetic buttons, card tilt, marquees, the free shipping confetti and the hide-on-scroll header. Content is shown right away instead. Visitors can also stop animations from the accessibility panel.

## Accessibility panel

Go to **Theme settings → Accessibility**:

| Setting | What it does |
|---|---|
| **Show accessibility panel** | Adds a round button that opens the panel. |
| **Panel button position** | **Start** or **End** of the screen. |

The panel has five options, which visitors can combine:

| Option | Effect |
|---|---|
| **Larger text** | Increases the text size across the store. |
| **Higher contrast** | Raises the contrast of the whole page and makes link underlines thicker. |
| **Underline links** | Underlines every link. |
| **Stop animations** | Turns off animations and motion effects. |
| **Readable font** | Switches to a plain, easy-to-read font. |

**Reset** turns all options off. The choices are remembered on the visitor's device.

The panel is a convenience for visitors. It doesn't replace accessible content, so keep giving images alt text and use clear link text.

## Built-in accessibility

These work without any setting:

- A **Skip to content** link for keyboard users.
- Visible focus outlines on links, buttons and fields.
- Menus, drawers, popups and quick view can be used with the keyboard. **Esc** closes them, and focus stays inside an open drawer.
- Sliders have labeled previous and next buttons, and auto-rotation pauses on hover.
- Form fields have labels.

## Cookie banner

The **Cookie banner** section is in the **Overlays** group. It shows only to visitors in regions where consent is required, based on your settings in **Settings → Customer privacy**. The visitor's choice is passed to Shopify, so apps and analytics respect it.

| Setting | What it does |
|---|---|
| **Heading**, **Text** | The message. Link to your privacy policy in the text. |
| **Accept button label**, **Decline button label** | Button text. |
| **Position** | **Start**, **Center**, **End** or **Full-width bar**. |
| **Show after** | Delay in seconds, 0–10. |
| **Color scheme** | Colors of the banner. |

In the theme editor the banner is always shown, so you can style it.

## Age verifier

The **Age verifier** section, also in the **Overlays** group, asks visitors to confirm their age before they enter the store.

| Setting | What it does |
|---|---|
| **Remember confirmation for** | How many days the confirmation is remembered, 1–90. |
| **Blur background** | Blurs the store behind the message. |
| **Image**, **Heading**, **Text** | The message. |
| **Confirm button label**, **Decline button label** | Button text. |
| **Declined message** | The **Heading** and **Text** shown to visitors who decline. |

## Micro-interactions

**Theme settings → Micro-interactions** adds small animations that react to what shoppers do. Every option turns off automatically for visitors who have reduced motion enabled on their device, or who choose **Stop animations** in the accessibility panel.

| Setting | Options | Where it shows |
|---|---|---|
| Add to cart animation | None, Product image flies to cart, Dot flies to cart, Particle burst from button | Any add to cart button: product page, product cards, quick add, Image with products, Shoppable stories. The cart drawer opens after the animation ends. |
| Cart icon animation | None, Bounce, Wiggle, Jelly, Swing, Ring wave | The cart icon in the header and the mobile bar, plus a pop on the item count. |
| Button loading style | None, Spinner, Pulsing dots, Progress bar | Buttons while a request is running, such as add to cart. |
| Button after adding | None, Show a checkmark | The add to cart button shows a checkmark for a moment after a successful add. |
| Icon hover animation | None, Bounce, Wiggle, Jelly, Rotate, Pop | Icons in the header, footer and mobile bar. |
| Section icon animation | None, Float, Pulse, Swing, Rotate, Glow | Icons in Multicolumn, Trust bar and the Icon with text block, only while they're on screen. |

Velaine uses the flying product image with a bouncing cart by default.

