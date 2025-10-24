Refit-Home E-Commerce Store
A modern, responsive e-commerce website for selling second-hand clothing with an integrated admin panel for inventory and order management.

🌟 Features
Store Frontend (`index.html`)
Modern Luxury Design: Elegant UI with premium aesthetics

Product Catalog: Filterable by categories (All, Jeans, Shirt, Other)

Shopping Cart: Persistent cart with localStorage

Responsive Design: Mobile-first approach

Add to Cart Animations: Visual feedback with flying cart animation

Sold Out Management: Automatic product status tracking

Checkout System (`checkout.html`)
Customer Information Form: Name, phone, address collection

Delivery Options: J&T Express and Virak Bunthan

QR Code Payment: Integrated payment flow

Receipt Upload: File upload for payment confirmation

Order Processing: Automatic inventory updates

Telegram Notifications: Order alerts to admin

Admin Panel (`admin.html`)
Password Protected: Secure admin access

Product Management: Add, edit, mark as sold out

Order Management: View, update status, delete orders

Sales Reports: Revenue tracking and analytics

Order Cleanup Tools: Bulk deletion by time period or status

Website Settings: Customizable store settings

Mobile Responsive: Full mobile support

🛠 Technical Stack
Frontend: HTML5, CSS3, JavaScript (ES6+)

Storage: LocalStorage (No database required)

Styling: Custom CSS with CSS Grid & Flexbox

Fonts: Google Fonts (Playfair Display, Inter)

Icons: Emoji-based icons

Notifications: Telegram Bot API integration

📁 Project Structure


`refit-home/`
`├── index.html              # Main store page`
`├── checkout.html           # Checkout process`
├── admin.html             # Admin dashboard
├── css/
│   ├── style.css          # Main store styles
│   ├── checkout.css       # Checkout page styles
│   └── admin.css          # Admin panel styles
└── js/
    ├── main.js            # Store functionality
    ├── checkout.js        # Checkout process
    └── admin.js           # Admin panel functionality`
🚀 Quick Start
Clone or Download the project files

Open `index.html` in a web browser

Start Managing Products through the admin panel

Accessing Admin Panel
Multiple methods available:

Keyboard Shortcut: `Ctrl + Shift + A`

Logo Triple Click: Click store logo 3 times quickly

Hidden Corner: Click top-left corner of the page

Direct Access: Navigate to `admin.html`

Default Admin Password: `2394`

💼 Core Functionality
Product Management
Add new products with images, prices, categories, and sizes

Mark products as sold out (automatically during checkout)

Restock sold out items

Delete products permanently

Order System
Automatic order creation during checkout

Order status tracking (Pending → Processing → Delivered)

Customer information storage

Receipt file management

Inventory Tracking
Real-time stock status

Automatic sold out marking

Category-based organization

Size variant support

🎨 Design Features
Color Scheme: Luxury palette with charcoal, gold, and eggshell

Typography: Playfair Display for headings, Inter for body text

Animations: Smooth transitions and hover effects

Mobile Optimization: Touch-friendly interfaces

Loading States: Visual feedback for all actions

🔧 Configuration
Telegram Integration
Update in `admin.html` Settings:

javascript
`Telegram Bot Token: "YOUR_BOT_TOKEN"
Telegram Chat ID: "YOUR_CHAT_ID"`
Store Settings
Customizable in Admin Panel:

Website title and tagline

Delivery fee amount

QR code image URL

Admin password

📱 Mobile Support
Fully responsive design with:

Mobile-optimized navigation

Touch-friendly buttons and forms

Adaptive grid layouts

Mobile-specific overlays and modals

🔒 Security Features
Admin password protection

LocalStorage data persistence

Input validation and sanitization

Secure order processing

📊 Analytics & Reporting
Total orders and revenue tracking

Order status breakdown

CSV export functionality

Sales period analysis

🗂 Data Management
All data stored locally in browser localStorage:

Products inventory

Customer orders

Cart items

Admin settings

🛒 Customer Flow
Browse Products → Filter by category

Add to Cart → Visual confirmation

Checkout → Fill delivery information

Payment → Scan QR code and upload receipt

Confirmation → Order processed automatically

🎯 Admin Workflow
Monitor Orders → View new orders in real-time

Update Status → Track order progress

Manage Inventory → Add/remove products

Generate Reports → Sales analytics

Cleanup → Archive old orders

🌐 Browser Compatibility
Chrome (recommended)

Firefox

Safari

Edge

Mobile browsers

📞 Support
For technical issues or feature requests, contact the development team through the store's admin panel notification system.
