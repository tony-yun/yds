# @tony-yun/ui

A React UI component library with TypeScript support.

## Installation

```bash
npm install @tony-yun/ui
# or
yarn add @tony-yun/ui
# or
pnpm add @tony-yun/ui
```

## Usage

### Import all components

```tsx
import { Button, Card, Code } from "@tony-yun/ui";
```

### Import individual components

```tsx
import { Button } from "@tony-yun/ui/button";
import { Card } from "@tony-yun/ui/card";
import { Code } from "@tony-yun/ui/code";
```

## Components

### Button

```tsx
import { Button } from "@tony-yun/ui";

function App() {
  return (
    <Button appName="My App" className="custom-class">
      Click me
    </Button>
  );
}
```

### Card

```tsx
import { Card } from "@tony-yun/ui";

function App() {
  return (
    <Card
      title="Card Title"
      href="https://example.com"
      className="custom-class"
    >
      Card content goes here
    </Card>
  );
}
```

### Code

```tsx
import { Code } from "@tony-yun/ui";

function App() {
  return (
    <Code className="custom-class">
      const hello = "world";
    </Code>
  );
}
```

## Requirements

- React 18 or 19
- React DOM 18 or 19

## License

MIT
