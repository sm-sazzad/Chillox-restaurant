# Chillox - Fast Food Restaurant Landing Page

A fast, responsive, and visual landing page for **Chillox**, featuring menu browsing, promotional offers, table reservation, and live location integration.

---

## 🛠️ Section-by-Section Technical Implementation

This project is built as a single-page application (SPA) layout using semantic HTML and Tailwind CSS for utility-first styling.

| Section | Key Features | Technical Details & Libraries Used |
| :--- | :--- | :--- |
| **Hero & Nav** | Responsive navbar, custom branding, call-to-action | • **Tailwind Utility Classes**: Layout and smooth transitions <br> • **Dancing Script**: Google Fonts integration for cursive headers <br> • **Font Awesome**: Icons for cart, user profile, and mobile menu trigger |
| **Offers Banner** | Promotional discount highlights | • **Flexbox Grid System**: Clean two-column dynamic layout <br> • **Custom Border & Radius Styling**: Tailwind-based circular image frames |
| **Menu Display** | Categorized food cards with pricing | • **CSS Grid**: Responsive 3-column desktop layout (`grid-cols-1 sm:grid-cols-2 lg:grid-cols-3`) <br> • **Interactive UI Cards**: Rounded borders with hover effects |
| **About Us** | Restaurant overview | • **Order Reversing**: Flex/Grid order utility (`order-1 md:order-2`) to keep text on top in mobile view |
| **Table Booking** | Reservation form & location | • **HTML5 Form Controls**: Custom styled inputs, select dropdowns, and date pickers <br> • **Google Maps Embed API**: Responsive `<iframe>` embedding Dhanmondi outlet |
| **Reviews** | Customer testimonials | • **Multi-language Support**: Displays Bengali and English feedback within structured card elements |
| **Footer** | Contact info and operational hours | • **Semantic Footer**: 3-column layout with social link references |

---

## 🚀 Tech Stack

* **Structure**: HTML5 (Semantic Markup)
* **Styling**: Tailwind CSS v4 (via Browser CDN)
* **Typography**: Google Fonts (*Dancing Script*)
* **Icons**: Font Awesome v7.3.1
* **Map**: Google Maps Iframe API

---

## 📂 Project Structure

```text
Chillox-restaurant/
│── index.html        # Core HTML structure & embedded scripts
│── images/          # Compressed PNG/JPG assets for background & food items
└── README.md        # Comprehensive project documentation
