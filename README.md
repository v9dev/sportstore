<div align="center">

# ⚽ SportStore

*Your Ultimate Sports Equipment & Gear E-commerce Platform*

![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

![Angular CLI](https://img.shields.io/badge/Angular_CLI-13.0.3-red?style=flat-square&logo=angular)
![License](https://img.shields.io/github/license/v9dev/sportstore?style=flat-square)
![Last Commit](https://img.shields.io/github/last-commit/v9dev/sportstore?style=flat-square&color=blue)
![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen?style=flat-square)

</div>

---

## 📋 Table of Contents

- [🔍 Overview](#-overview)
- [✨ Features](#-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [🚀 Getting Started](#-getting-started)
  - [📋 Prerequisites](#-prerequisites)
  - [⚙️ Installation](#️-installation)
  - [🎯 Development Server](#-development-server)
  - [🏗️ Building](#️-building)
- [📁 Project Structure](#-project-structure)
- [🎨 UI Components](#-ui-components)
- [🔌 Services & APIs](#-services--apis)
- [🛒 E-commerce Features](#-e-commerce-features)
- [🧪 Testing](#-testing)
- [🚀 Deployment](#-deployment)
- [📱 Responsive Design](#-responsive-design)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

---

## 🔍 Overview

**SportStore** is a modern, full-featured e-commerce platform built with Angular 13, specifically designed for sports equipment and athletic gear retail. This application demonstrates advanced Angular concepts including component architecture, state management, routing, and responsive design principles.

### 🎯 Purpose

SportStore provides a complete online shopping experience for:
- **Sports Equipment**: Browse and purchase athletic gear
- **Product Management**: Advanced catalog with filtering and search
- **Shopping Cart**: Full cart functionality with real-time updates
- **User Management**: Account creation, authentication, and order history
- **Admin Panel**: Product and order management for store administrators

---

## ✨ Features

### 🛍️ Customer Features
- **Product Catalog**: Browse sports equipment by category, brand, and sport
- **Advanced Search**: Find products with filters, sorting, and search functionality
- **Shopping Cart**: Add, remove, and modify items with real-time price calculation
- **Wishlist**: Save favorite products for later purchase
- **User Accounts**: Registration, login, profile management, and order history
- **Checkout Process**: Secure payment integration and order confirmation
- **Product Reviews**: Rate and review purchased products

### 👨‍💼 Admin Features
- **Product Management**: Add, edit, and delete products with image upload
- **Order Management**: View, process, and track customer orders
- **User Management**: Manage customer accounts and permissions
- **Analytics Dashboard**: Sales reports and inventory tracking
- **Category Management**: Organize products into sports categories

### 🎨 User Experience
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Modern UI**: Clean, intuitive interface with smooth animations
- **Fast Loading**: Lazy loading and optimized performance
- **PWA Ready**: Progressive Web App capabilities for mobile experience

---

## 🛠️ Tech Stack

### Frontend Framework
- **Framework**: ![Angular](https://img.shields.io/badge/Angular-13.0.3-DD0031?style=flat-square&logo=angular&logoColor=white)
- **Language**: ![TypeScript](https://img.shields.io/badge/TypeScript-4.4+-007ACC?style=flat-square&logo=typescript&logoColor=white)
- **CLI**: Angular CLI 13.0.3

### UI & Styling
- **Markup**: ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
- **Styling**: ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) / ![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=flat-square&logo=sass&logoColor=white)
- **Framework**: ![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=flat-square&logo=bootstrap&logoColor=white)
- **Icons**: ![Font Awesome](https://img.shields.io/badge/Font_Awesome-528DD7?style=flat-square&logo=fontawesome&logoColor=white)

### Development Tools
- **Package Manager**: ![npm](https://img.shields.io/badge/npm-CB3837?style=flat-square&logo=npm&logoColor=white)
- **Testing**: Karma + Jasmine
- **E2E Testing**: Protractor / Cypress
- **Build Tools**: Angular CLI Webpack

### Additional Libraries
- **State Management**: NgRx (if implemented)
- **HTTP Client**: Angular HttpClient
- **Forms**: Angular Reactive Forms
- **Routing**: Angular Router
- **Animations**: Angular Animations

---

## 🚀 Getting Started

### 📋 Prerequisites

Make sure you have the following installed:

- **Node.js** (v14.0.0 or higher)
- **npm** (v6.0.0 or higher)
- **Angular CLI** (v13.0.3)

```bash
# Check your versions
node --version
npm --version
ng version
```

### ⚙️ Installation

1. **Clone the repository**
```bash
git clone https://github.com/v9dev/sportstore.git
cd sportstore
```

2. **Install dependencies**
```bash
npm install
```

3. **Install Angular CLI globally (if not installed)**
```bash
npm install -g @angular/cli@13.0.3
```

### 🎯 Development Server

**Start the development server:**
```bash
ng serve
```

Navigate to `http://localhost:4200/`. The application will automatically reload when you change source files.

**Additional development commands:**
```bash
# Serve with custom port
ng serve --port 4500

# Serve with open browser
ng serve --open

# Serve with production configuration
ng serve --configuration production
```

### 🏗️ Building

**Build the project:**
```bash
ng build
```

The build artifacts will be stored in the `dist/` directory.

**Build for production:**
```bash
ng build --configuration production
```

**Build with specific base href:**
```bash
ng build --base-href=/sportstore/
```

---

## 📁 Project Structure

```
sportstore/
├── 📁 src/                           # Source code
│   ├── 📁 app/                       # Application modules
│   │   ├── 📁 components/            # Reusable components
│   │   │   ├── 📁 header/
│   │   │   ├── 📁 footer/
│   │   │   ├── 📁 product-card/
│   │   │   └── 📁 loading-spinner/
│   │   ├── 📁 pages/                 # Page components
│   │   │   ├── 📁 home/
│   │   │   ├── 📁 products/
│   │   │   ├── 📁 product-detail/
│   │   │   ├── 📁 cart/
│   │   │   ├── 📁 checkout/
│   │   │   └── 📁 account/
│   │   ├── 📁 admin/                 # Admin panel
│   │   │   ├── 📁 dashboard/
│   │   │   ├── 📁 product-management/
│   │   │   └── 📁 order-management/
│   │   ├── 📁 services/              # Angular services
│   │   │   ├── product.service.ts
│   │   │   ├── cart.service.ts
│   │   │   ├── auth.service.ts
│   │   │   └── order.service.ts
│   │   ├── 📁 models/                # TypeScript interfaces
│   │   │   ├── product.model.ts
│   │   │   ├── user.model.ts
│   │   │   └── order.model.ts
│   │   ├── 📁 guards/                # Route guards
│   │   │   ├── auth.guard.ts
│   │   │   └── admin.guard.ts
│   │   ├── 📁 interceptors/          # HTTP interceptors
│   │   │   └── auth.interceptor.ts
│   │   ├── 📁 pipes/                 # Custom pipes
│   │   │   └── currency-format.pipe.ts
│   │   ├── app-routing.module.ts     # Routing configuration
│   │   ├── app.component.ts          # Root component
│   │   └── app.module.ts             # Main module
│   ├── 📁 assets/                    # Static assets
│   │   ├── 📁 images/
│   │   ├── 📁 icons/
│   │   └── 📁 styles/
│   ├── 📁 environments/              # Environment configs
│   │   ├── environment.ts
│   │   └── environment.prod.ts
│   ├── index.html                    # Main HTML file
│   ├── main.ts                       # Application bootstrap
│   ├── polyfills.ts                  # Browser polyfills
│   └── styles.scss                   # Global styles
├── 📁 e2e/                          # End-to-end tests
├── 📁 node_modules/                 # Dependencies
├── angular.json                     # Angular CLI config
├── karma.conf.js                    # Karma test config
├── package.json                     # Dependencies & scripts
├── tsconfig.json                    # TypeScript config
└── README.md                        # Documentation
```

---

## 🎨 UI Components

### Core Components

**Product Card Component**
```typescript
@Component({
  selector: 'app-product-card',
  template: `
    <div class="product-card">
      <img [src]="product.image" [alt]="product.name">
      <h3>{{ product.name }}</h3>
      <p class="price">{{ product.price | currency }}</p>
      <button (click)="addToCart()" class="btn btn-primary">
        Add to Cart
      </button>
    </div>
  `
})
export class ProductCardComponent { }
```

**Shopping Cart Component**
```typescript
@Component({
  selector: 'app-cart',
  template: `
    <div class="cart-items">
      <div *ngFor="let item of cartItems" class="cart-item">
        <span>{{ item.name }}</span>
        <span>{{ item.quantity }}</span>
        <span>{{ item.total | currency }}</span>
      </div>
    </div>
  `
})
export class CartComponent { }
```

---

## 🔌 Services & APIs

### Product Service
```typescript
@Injectable({
  providedIn: 'root'
})
export class ProductService {
  private apiUrl = 'http://localhost:3000/api';

  getProducts(): Observable<Product[]> {
    return this.http.get<Product[]>(`${this.apiUrl}/products`);
  }

  getProductById(id: number): Observable<Product> {
    return this.http.get<Product>(`${this.apiUrl}/products/${id}`);
  }

  createProduct(product: Product): Observable<Product> {
    return this.http.post<Product>(`${this.apiUrl}/products`, product);
  }
}
```

### Cart Service
```typescript
@Injectable({
  providedIn: 'root'
})
export class CartService {
  private cartItems: BehaviorSubject<CartItem[]> = new BehaviorSubject([]);

  addToCart(product: Product, quantity: number = 1) {
    // Add item to cart logic
  }

  removeFromCart(productId: number) {
    // Remove item logic
  }

  getTotalPrice(): number {
    // Calculate total price
  }
}
```

---

## 🛒 E-commerce Features

### Product Management
- **Category Filtering**: Filter products by sports category
- **Search Functionality**: Search products by name, brand, or description
- **Sort Options**: Sort by price, popularity, rating, or newest
- **Product Details**: Detailed product pages with specifications

### Shopping Cart
- **Add/Remove Items**: Full cart management
- **Quantity Updates**: Modify item quantities
- **Price Calculation**: Real-time total calculation
- **Persistent Cart**: Cart state persistence across sessions

### User Authentication
- **Registration**: New user account creation
- **Login/Logout**: Secure authentication system
- **Profile Management**: User profile and preferences
- **Order History**: View past purchases and order status

### Checkout Process
- **Shipping Information**: Address and delivery options
- **Payment Integration**: Secure payment processing
- **Order Confirmation**: Email confirmation and tracking
- **Invoice Generation**: PDF invoice generation

---

## 🧪 Testing

### Unit Tests
**Run unit tests:**
```bash
ng test
```

Tests are executed via [Karma](https://karma-runner.github.io) test runner.

**Run tests with coverage:**
```bash
ng test --code-coverage
```

### End-to-End Tests
**Run e2e tests:**
```bash
ng e2e
```

**Example test:**
```typescript
describe('SportStore App', () => {
  it('should display product catalog', () => {
    cy.visit('/');
    cy.contains('Sports Equipment');
    cy.get('.product-card').should('have.length.greaterThan', 0);
  });

  it('should add product to cart', () => {
    cy.visit('/products');
    cy.get('.product-card').first().find('.add-to-cart').click();
    cy.get('.cart-count').should('contain', '1');
  });
});
```

### Component Generation
**Generate new components:**
```bash
# Generate component
ng generate component product-list

# Generate service
ng generate service cart

# Generate guard
ng generate guard auth

# Generate pipe
ng generate pipe price-format
```

---

## 🚀 Deployment

### Production Build
```bash
# Build for production
ng build --configuration production

# Build with custom base href
ng build --configuration production --base-href=/sportstore/
```

### Deployment Options

**Firebase Hosting:**
```bash
npm install -g firebase-tools
firebase login
firebase init hosting
firebase deploy
```

**Netlify:**
```bash
# Build the project
ng build --configuration production

# Upload dist folder to Netlify
```

**Docker Deployment:**
```dockerfile
FROM node:16-alpine as build

WORKDIR /app
COPY package*.json ./
RUN npm ci --only=production

COPY . .
RUN npm run build

FROM nginx:alpine
COPY --from=build /app/dist/sportstore /usr/share/nginx/html
COPY nginx.conf /etc/nginx/nginx.conf

EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
```

---

## 📱 Responsive Design

### Breakpoints
```scss
// Mobile First Approach
@media (min-width: 576px) { /* Small devices */ }
@media (min-width: 768px) { /* Medium devices */ }
@media (min-width: 992px) { /* Large devices */ }
@media (min-width: 1200px) { /* Extra large devices */ }
```

### Mobile Optimization
- **Touch-friendly UI**: Large tap targets and gesture support
- **Optimized Images**: Responsive images with lazy loading
- **Fast Loading**: Minimized bundle sizes and code splitting
- **PWA Features**: Service worker and offline capabilities

---

## 🤝 Contributing

We welcome contributions! Here's how to get started:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/new-feature
   ```
3. **Make your changes**
4. **Add tests** for new functionality
5. **Run tests**
   ```bash
   ng test
   ng e2e
   ```
6. **Commit your changes**
   ```bash
   git commit -m 'Add new feature'
   ```
7. **Push to your branch**
   ```bash
   git push origin feature/new-feature
   ```
8. **Open a Pull Request**

### Development Guidelines
- Follow Angular style guide
- Write unit tests for all components and services
- Use TypeScript strict mode
- Follow responsive design principles
- Document your code with JSDoc comments

### Code Style
```bash
# Lint your code
ng lint

# Format code
npm run prettier

# Pre-commit hooks
npm run pre-commit
```

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">

### 🌟 Show Your Support

Give a ⭐ if this project helped you build your sports e-commerce platform!

### 📞 Contact

**Developer**: v9dev  
**Repository**: [sportstore](https://github.com/v9dev/sportstore)  
**Angular Version**: 13.0.3

### 🔗 Useful Links

- [Angular Documentation](https://angular.io/docs)
- [Angular CLI Reference](https://angular.io/cli)
- [TypeScript Handbook](https://www.typescriptlang.org/docs/)
- [Bootstrap Documentation](https://getbootstrap.com/docs/)

### 🏆 Built with Angular 13

*Leveraging the power of modern web development*

---

**[⬆️ Back to top](#-sportstore)**

</div>
