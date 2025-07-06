# Grow My Therapy - Website

A modern, responsive therapy website built with Next.js 15, TypeScript, and Tailwind CSS.

## 📋 Project Context

This project was built as part of the internship selection process for Grow My Therapy. The task involved creating a responsive, therapist-focused website for a fictional psychologist, Dr. Serena Blake, using Next.js 14 and Tailwind CSS.

Although this was my first time working with Next.js, my background in React.js made the transition smooth. I followed a 7-hour tutorial to grasp Next.js fundamentals and relied on that learning to structure and build the application effectively.

The design is closely based on one of the two reference websites provided, as required. I ensured that the layout, typography, spacing, and overall look resembled the chosen reference site with about 65% design accuracy. For added functionality, cleaner styling, and better content tone, I used AI tools like ChatGPT — but I made sure to personally review and refine all output, maintaining alignment with the expected design and quality standards.

## 🏠 Pages

### Home Page (`/`)
- **Hero Section**: Large headline with call-to-action
- **Services Preview**: Auto-scrolling testimonials
- **Office Hours**: Dynamic display showing current availability
- **Contact Form**: Full-featured contact form with validation
- **Footer**: Contact information and office hours

### About Page (`/about`)
- **Professional Introduction**: Dr. Serena Blake's background
- **Experience Stats**: Years of practice and sessions conducted
- **About Sections**: Information about the practice and therapist
- **Call-to-Action**: "Home" button for easy navigation

### Services Page (`/services`)
- **Testimonials**: Auto-scrolling client testimonials with images
- **Service Listings**: Detailed service descriptions with images
- **Office Hours & Fees**: Clear pricing and availability information
- **Call-to-Action**: "Take the first step" section

### FAQ Page (`/faq`)
- **Interactive Accordion**: Expandable FAQ sections
- **10 Common Questions**: Comprehensive coverage of therapy topics
- **User Question Submission**: Form for additional questions
- **Contact Button**: Easy access to contact information

### Contact Page (`/contact`)
- **Contact Information**: Phone, email, and address
- **Office Hours**: Detailed weekly schedule
- **Session Fees**: Individual and couples pricing
- **Contact Form**: Comprehensive form with validation
- **Booking Form**: Multi-step session booking process
- **Inspirational Quote**: Therapeutic messaging

## 🛠️ Technical Features

### Frontend
- **Next.js 15**: Latest version with App Router
- **TypeScript**: Type-safe development
- **Tailwind CSS**: Utility-first styling
- **Responsive Design**: Mobile-first approach
- **Interactive Components**: Forms, modals, accordions

### Forms & Validation
- **Contact Form**: Name, phone, email, message, preferred time
- **Booking Form**: 3-step process with comprehensive validation
- **FAQ Submission**: User question input
- **Real-time Validation**: Immediate feedback on form errors
- **Success Messages**: Encouraging confirmation messages

## 📱 Mobile Responsiveness Details

### Breakpoints
- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

### Mobile Optimizations
- **Touch Targets**: Minimum 44px for buttons and links
- **Font Sizes**: Readable on small screens (16px minimum)
- **Spacing**: Adequate padding and margins for touch interaction
- **Navigation**: Simplified mobile navigation
- **Forms**: Mobile-optimized input fields and validation
- **Images**: Responsive images that scale appropriately

### Performance
- **Fast Loading**: Optimized for mobile networks
- **Image Optimization**: Next.js Image component for efficient loading
- **Minimal JavaScript**: Lightweight interactions
- **Caching**: Efficient resource caching

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Installation
```bash
# Clone the repository
git clone [repository-url]

# Navigate to project directory
cd gmt

# Install dependencies
npm install

# Run development server
npm run dev
```

### Available Scripts
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## 🌐 Deployment

The website is ready for deployment on:
- **Vercel**

## Inspiration 
- **https://www.drjenniferhahm.com/**
