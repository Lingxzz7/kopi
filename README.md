# ☕ Kopi - Artisan Coffee Experience

A modern, responsive coffee website built with HTML, Tailwind CSS, Node.js, and JavaScript. Experience the perfect blend of tradition and innovation in every cup.

## 🚀 Features

### Frontend
- **Modern Design**: Glass morphism effects, gradient backgrounds, and smooth animations
- **Responsive Layout**: Optimized for desktop, tablet, and mobile devices
- **Interactive Menu**: Category filtering, dynamic cart system, and smooth scrolling
- **Newsletter Signup**: Email subscription with API integration
- **Contact Form**: User-friendly contact form with validation
- **Mobile Menu**: Collapsible navigation for mobile devices
- **Shopping Cart**: Add/remove items, real-time total calculation
- **Animations**: Floating coffee beans, steam effects, and smooth transitions

### Backend
- **Express.js Server**: RESTful API endpoints
- **Security**: Helmet.js for security headers, CORS support
- **Compression**: Gzip compression for better performance
- **API Endpoints**:
  - `GET /api/menu` - Retrieve coffee menu
  - `GET /api/menu/:category` - Filter menu by category
  - `POST /api/contact` - Handle contact form submissions
  - `POST /api/order` - Process orders
  - `POST /api/newsletter` - Newsletter subscriptions

## 🛠️ Technologies Used

- **Frontend**: HTML5, Tailwind CSS, Vanilla JavaScript
- **Backend**: Node.js, Express.js
- **Styling**: Custom CSS animations, Glass morphism effects
- **Icons**: SVG icons and emojis
- **Development**: Nodemon for development server

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd kopi
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000`

## 🎯 Available Scripts

- `npm start` - Start the production server
- `npm run dev` - Start the development server with nodemon
- `npm run build:css` - Build Tailwind CSS with watch mode

## 📱 Features Overview

### 🏠 Home Section
- Hero section with animated coffee beans and steam effects
- Call-to-action buttons for menu exploration and story
- Scroll indicator for better UX

### 📋 Menu Section
- 6 signature coffee blends with detailed descriptions
- Category filtering (All, Espresso, Filter, Specialty, Cold)
- Dynamic cart integration
- Responsive grid layout

### 📰 Newsletter
- Email subscription form
- API integration for backend processing
- Success/error notifications

### 📞 Contact Section
- Contact form with validation
- API integration for form submission
- Loading states and feedback

### 🛒 Shopping Cart
- Floating cart button with item count
- Modal cart interface
- Add/remove items functionality
- Checkout process with API integration

## 🎨 Design Features

### Color Palette
- **Primary**: Coffee browns (#8b4513, #d2691e, #cd853f)
- **Background**: Dark grays (#111827, #1f2937)
- **Accent**: Coffee-themed gradients

### Animations
- Floating coffee beans
- Steam effects
- Smooth transitions
- Loading spinners
- Hover effects

### Typography
- Modern, clean fonts
- Gradient text effects
- Responsive sizing

## 🔧 API Endpoints

### Menu API
```javascript
GET /api/menu
// Returns all coffee items

GET /api/menu/:category
// Returns filtered items by category
```

### Contact API
```javascript
POST /api/contact
// Body: { name, email, message }
// Returns: { success, message }
```

### Order API
```javascript
POST /api/order
// Body: { items, customerInfo, total }
// Returns: { success, orderId, message }
```

### Newsletter API
```javascript
POST /api/newsletter
// Body: { email }
// Returns: { success, message }
```

## 📱 Mobile Responsiveness

The website is fully responsive with:
- Mobile-first design approach
- Collapsible navigation menu
- Touch-friendly buttons and interactions
- Optimized layouts for all screen sizes

## 🚀 Performance Optimizations

- Gzip compression enabled
- Optimized images and assets
- Efficient CSS with Tailwind
- Lazy loading for better performance
- Security headers with Helmet.js

## 🔒 Security Features

- Content Security Policy (CSP) headers
- CORS configuration
- Input validation and sanitization
- Secure HTTP headers

## 📈 Future Enhancements

- [ ] User authentication system
- [ ] Payment gateway integration
- [ ] Order tracking system
- [ ] Admin dashboard
- [ ] Database integration
- [ ] Real-time notifications
- [ ] Multi-language support
- [ ] SEO optimization

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🌐 Deploy ke GitHub Pages

Agar situs tampil di GitHub, gunakan GitHub Pages dari folder `docs`:

1. Pastikan folder `docs/` berisi `index.html` dan file `.nojekyll` (sudah dibuat di repo ini).
2. Commit dan push perubahan ke branch default (mis. `main`).
3. Buka Settings repo → Pages → Source: "Deploy from a branch".
4. Pilih Branch: `main` (atau branch default Anda) dan Folder: `/docs`, lalu Save.
5. Tunggu ±1–3 menit hingga situs aktif di URL: `https://<username>.github.io/<repository>`.
6. Untuk update tampilan, edit file di `docs/` lalu commit dan push lagi.

Catatan: Endpoint backend (Express.js) tidak berjalan di GitHub Pages. Untuk fungsi API, deploy backend ke layanan terpisah (mis. Render, Railway, Fly.io, Vercel Functions) dan arahkan request dari halaman statis ke URL backend tersebut.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Kopi Team** - Crafting exceptional coffee experiences since 2024

## 🙏 Acknowledgments

- Tailwind CSS for the utility-first CSS framework
- Express.js for the robust web framework
- Coffee community for inspiration
- All coffee lovers who make this possible

---

**Enjoy your coffee journey with Kopi! ☕✨** 