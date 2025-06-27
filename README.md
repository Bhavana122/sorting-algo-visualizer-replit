# Sorting Algorithm Visualizer

An interactive web application that visualizes various sorting algorithms with educational animations and quizzes.

## Features

- **5 Sorting Algorithms**: Bubble Sort, Selection Sort, Insertion Sort, Quick Sort, Merge Sort
- **Interactive Visualization**: Real-time animated bars showing sorting progress
- **Educational Quiz**: Pop-up quiz after each sorting to test time complexity knowledge
- **Customizable Parameters**: Adjustable array size (2-50) and sorting speed
- **Climbing Characters**: Fun character animations on sorted bars
- **Real-time Statistics**: Live tracking of comparisons, swaps, and execution time

## Technologies Used

- **Frontend**: React 18, TypeScript, Tailwind CSS
- **UI Components**: shadcn/ui (Radix UI primitives)
- **Backend**: Express.js, TypeScript
- **Database**: PostgreSQL with Drizzle ORM
- **Build Tools**: Vite, esbuild
- **Routing**: Wouter
- **State Management**: TanStack Query

## Getting Started

### Prerequisites
- Node.js 20+
- PostgreSQL (optional, uses in-memory storage by default)

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser to the provided URL

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server

## Project Structure

```
├── client/                 # Frontend React application
│   ├── src/
│   │   ├── components/    # Reusable UI components
│   │   ├── pages/         # Page components
│   │   ├── lib/           # Utilities and algorithms
│   │   └── hooks/         # Custom React hooks
├── server/                # Backend Express server
├── shared/                # Shared TypeScript schemas
└── README.md
```

## Educational Value

This project demonstrates:
- Algorithm visualization techniques
- Time complexity analysis
- Interactive learning through quizzes
- Real-time performance metrics
- Responsive web design principles

## Algorithms Implemented

1. **Bubble Sort** - O(n²) average case
2. **Selection Sort** - O(n²) average case
3. **Insertion Sort** - O(n²) average case
4. **Quick Sort** - O(n log n) average case
5. **Merge Sort** - O(n log n) average case

Each algorithm includes detailed complexity information and step-by-step visualization.

## Contributing

This is an educational project. Feel free to fork and extend with additional sorting algorithms or features.

## License

Educational use only.