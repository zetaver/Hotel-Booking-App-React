# MareSereno - Luxury Seaside Apartments

A modern, responsive web application for a luxury seaside apartment rental service. Built with React, TypeScript, and Tailwind CSS, featuring a beautiful UI and seamless user experience.

![MareSereno Hero](https://images.unsplash.com/photo-1615571022219-eb45cf7faa9d?q=80&w=1200&h=600&auto=format&fit=crop)

## 🌟 Features

- **Responsive Design**: Fully responsive across all devices and screen sizes
- **Multi-language Support**: Available in English and Italian
- **Dark/Light Theme**: Seamless theme switching with user preference persistence
- **Interactive Booking System**: Easy-to-use booking form with date selection
- **Apartment Showcase**: Detailed apartment cards with features and pricing
- **Image Gallery**: Beautiful photo galleries showcasing amenities and apartments
- **Modern UI/UX**: Clean, modern design with smooth animations and transitions
- **SEO Optimized**: Proper meta tags and semantic HTML structure

## 🏠 Pages

- **Home**: Hero section, featured apartments, amenities overview, and testimonials
- **Apartments**: Complete apartment listings with filtering capabilities
- **Amenities**: Detailed amenities categorized by wellness, dining, services, and entertainment
- **Gallery**: Photo gallery showcasing the property and surroundings
- **Contact**: Contact information and inquiry form
- **Booking**: Comprehensive booking system with availability checking

## 🛠️ Technologies Used

- **Frontend Framework**: React 18 with TypeScript
- **Styling**: Tailwind CSS with custom design system
- **UI Components**: Shadcn/ui component library
- **Build Tool**: Vite for fast development and optimized builds
- **Routing**: React Router DOM for client-side navigation
- **State Management**: React Context API for language and theme management
- **Data Fetching**: TanStack React Query for efficient data management
- **Icons**: Lucide React for consistent iconography
- **Form Handling**: React Hook Form with Zod validation
- **Date Handling**: date-fns for date manipulation

## 📱 Screenshots

### Home Page
![Home Page](https://images.unsplash.com/photo-1582719478250-c89cae4dc85b?w=1200&h=800&fit=crop)
*Beautiful hero section with booking call-to-action*

### Apartments Listing
![Apartments](https://images.unsplash.com/photo-1502672260266-1c1ef2d93688?w=1200&h=800&fit=crop)
*Comprehensive apartment listings with detailed information*

### Amenities Page
![Amenities](https://images.unsplash.com/photo-1571896349842-33c89424de2d?w=1200&h=800&fit=crop)
*Organized amenities showcase by categories*

### Gallery
![Gallery](https://images.unsplash.com/photo-1596394516093-501ba68a0ba6?w=1200&h=800&fit=crop)
*Beautiful image gallery with property photos*

### Booking System
![Booking](https://images.unsplash.com/photo-1578662996442-48f60103fc96?w=1200&h=800&fit=crop)
*Intuitive booking form with date selection*

## 🚀 Getting Started

### Prerequisites

- Node.js (version 18 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <YOUR_GIT_URL>
   cd maresereno
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
   Navigate to `http://localhost:5173` to view the application

### Building for Production

```bash
npm run build
```

The built files will be in the `dist` directory, ready for deployment.

## 🎨 Design System

The project uses a custom design system built on top of Tailwind CSS:

- **Primary Colors**: Sea-inspired blues and teals
- **Typography**: Modern font stack with proper hierarchy
- **Spacing**: Consistent spacing scale following design principles
- **Components**: Reusable UI components with consistent styling
- **Animations**: Smooth transitions and micro-interactions

## 🌐 Internationalization

The application supports multiple languages:
- **English** (default)
- **Italian**

Language switching is available through the navigation bar, with user preference persistence.

## 📝 Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── ui/             # Shadcn/ui components
│   ├── Navbar.tsx      # Navigation component
│   ├── Footer.tsx      # Footer component
│   └── ...
├── pages/              # Page components
│   ├── Index.tsx       # Home page
│   ├── Apartments.tsx  # Apartments listing
│   ├── Amenities.tsx   # Amenities showcase
│   └── ...
├── contexts/           # React contexts
├── locales/           # Translation files
├── lib/               # Utility functions
└── hooks/             # Custom React hooks
```

## 🚦 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint for code quality

## 📦 Dependencies

### Main Dependencies
- React & React DOM
- TypeScript
- React Router DOM
- TanStack React Query
- React Hook Form
- Zod
- date-fns

### UI & Styling
- Tailwind CSS
- Shadcn/ui
- Lucide React (icons)
- next-themes (theme switching)

### Development Tools
- Vite
- ESLint
- TypeScript configuration

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Support

For support and questions:
- **Email**: info@maresereno.com
- **Phone**: +39 123 4567 890
- **Address**: 123 Seaside Boulevard, Costa Bella, Italy

## 🙏 Acknowledgments

- Images provided by [Unsplash](https://unsplash.com)
- UI components from [Shadcn/ui](https://ui.shadcn.com)
- Icons from [Lucide](https://lucide.dev)

---

Built with ❤️ for luxury seaside experiences
