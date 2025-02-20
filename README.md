# Xclusive Customs - Off-Grid Systems Pricing Component

A responsive, interactive pricing component for Xclusive Customs' off-grid solar power systems. This component features a dynamic price toggle between monthly and once-off payments, an interactive carousel display, and mobile-responsive design.

![Xclusive Customs Pricing Component](https://xclusivecustoms.tech/assets/pricing-preview.png)

## Features

- 🔄 Toggle between monthly and once-off pricing
- 📱 Fully responsive design
- 🎠 Interactive carousel display
- 💳 Dynamic "Buy Now" links
- 🎨 Custom styling with Tailwind CSS
- ⚡ Three-tier pricing system for different power needs

## Technologies Used

- React 18
- Tailwind CSS
- Swiper.js
- Font Awesome
- Vanilla JavaScript

## Installation

1. Clone the repository:
```bash
git clone https://github.com/TebogoThage/xclusive-customs-pricing.git
```

2. Navigate to the project directory:
```bash
cd xclusive-customs-pricing
```

3. Open `index.html` in your web browser or serve it using a local server.

## Usage

The component is self-contained and can be easily integrated into any existing website. Simply include the necessary CDN links and the component code:

```html
<!-- Add to your HTML head -->
<script src="https://unpkg.com/react@18/umd/react.development.js"></script>
<script src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>
<script src="https://cdn.tailwindcss.com"></script>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@10/swiper-bundle.min.css" />
```

Then add the component container to your HTML:

```html
<div id="pricing-root"></div>
```

## Customization

### Pricing Plans

Modify the `pricingData` array in the `PricingComponent` to update pricing information:

```javascript
const pricingData = [
    {
        title: "Minimalist",
        power: "3kw Off-Grid System",
        price: isMonthly ? "1,500" : "80,000",
        // ... other properties
    },
    // ... other plans
];
```

### Styling

The component uses Tailwind CSS classes for styling. Modify the classes in the component JSX to customize the appearance:

```javascript
<div className={`p-6 rounded-xl text-white text-center ${bgColor} shadow-lg`}>
    // ... component content
</div>
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Author

**Tebogo Thage Jr**  
Xclusive Customs Tech Lead  
[Website](https://xclusivecustoms.tech)

## License

This project is proprietary software owned by Xclusive Customs. All rights reserved.

## Acknowledgments

- Swiper.js for the carousel functionality
- Tailwind CSS for the utility-first CSS framework
- React team for the excellent frontend library

---

For business inquiries, please contact:  
📧 info@xclusivecustoms.tech  
📞 [Your Contact Number]  
🌐 [xclusivecustoms.tech](https://xclusivecustoms.tech)
