# FlowState

## Project Structure

```
src/
├── components/          # Reusable UI components
│   └── ui/             # Base UI components (Button, Input, Link)
├── pages/              # Page components
│   └── auth/           # Authentication pages
├── hooks/              # Custom React hooks
├── types/              # TypeScript type definitions
├── utils/              # Utility functions
└── assets/             # Static assets
```

## Technologies Used

- **React 19** - UI library
- **TypeScript** - Type safety
- **Tailwind CSS** - Styling
- **Vite** - Build tool and dev server
- **class-variance-authority** - Component variants
- **clsx** & **tailwind-merge** - Class name utilities

## Getting Started

1. **Install dependencies**:
   ```bash
   npm install
   ```

2. **Start development server**:
   ```bash
   npm run dev
   ```

3. **Build for production**:
   ```bash
   npm run build
   ```

## Component Architecture

### Reusable Components
- **Button**: Configurable button with variants and sizes
- **Input**: Form input with label and error handling
- **Link**: Styled anchor links with variants

### Custom Hooks
- **useForm**: Form state management with validation

### Type Safety
- Full TypeScript coverage
- Defined interfaces for all props and data structures

## Development Features

- Hot module replacement (HMR)
- ESLint configuration
- TypeScript strict mode
- Tailwind CSS IntelliSense support

---
