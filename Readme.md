# React UI Component Library

This project is a customizable and reusable React UI Component Library designed to accelerate development and maintain consistency across your applications.

## Features

- **Reusable Components**: Pre-built components for common UI patterns.
- **Customizable**: Easily extend and style components to match your design system.
- **TypeScript Support**: Fully typed for better developer experience.
- **Responsive Design**: Components are mobile-friendly and adaptable to various screen sizes.

## Installation

```bash
npm install tstoyanov-ui-components
```

or

```bash
yarn add tstoyanov-ui-components
```

## Usage

```jsx
import { Button, Card } from 'tstoyanov-ui-components';

function App() {
    return (
        <div>
            <Card>
                <h1>Welcome</h1>
                <Button onClick={() => alert('Clicked!')}>Click Me</Button>
            </Card>
        </div>
    );
}

export default App;
```

## Documentation

Visit the [documentation site](#) for detailed usage instructions and examples.

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) before submitting a pull request.

## License

This project is licensed under the [MIT License](LICENSE).