# BuildCities Public Component Library

The BuildCities Public Component Library is the public registry for all components used in the BuildCities app. This library provides a collection of reusable UI components that can be used to build and maintain the BuildCities application. Explore components [here in components explorer](https://66b13ab822b5b2d11025c093-ibiqloyrex.chromatic.com)

## Project Description

This repository contains the npm packages for the UI components used in the BuildCities app, which can be accessed at [BuildCities App](https://app.buildcities.com). The [components](https://66b13ab822b5b2d11025c093-ibiqloyrex.chromatic.com) are designed to be reusable and easily integrated into various parts of any application. 

## Features

- A comprehensive library of UI components
- Easy integration with the BuildCities app
- Well-documented components with usage examples
- Public Storybook explorer for component documentation and examples

## Installation

To install a specific component from the library, you can use yarn:

```bash
yarn add @buildcities/ui-v2.components.<component-name>
```
Replace <component-name> with the name of the component you want to install.

## Usage

To use a component from the BuildCities Public Component Library, you can follow these steps:

1. Install the desired component using yarn. For example, to install the Button component, run the following command:

```bash
yarn add @buildcities/ui-v2.components.button
```

2. Import the component in your project file. For example, to import the Button component in a React component:

```jsx
import { Button } from '@buildcities/ui-v2.components.button';
```

3. Use the component in your code. For example, you can render the Button component in your React component's render method:

```jsx
render() {
    return (
        <Button onClick={this.handleClick}>Click me</Button>
    );
}
```

4. Customize the component's props as needed. Each component in the library has its own set of props that can be used to customize its behavior and appearance.

By following these steps, you can easily integrate the BuildCities UI components into your application and leverage their functionality to enhance your user interface.


## Prerequisites

Before using the BuildCities Public Component Library, make sure you have the following prerequisites:

- Node.js installed on your machine
- Yarn package manager installed on your machine

If you don't have Node.js and Yarn installed, you can download them from their official websites:

- [Node.js](https://nodejs.org)
- [Yarn](https://yarnpkg.com)

Once you have Node.js and Yarn installed, you can proceed with the installation and usage of the BuildCities UI components.


## Documentation
To explore the available components and their usage, visit the public Storybook explorer [here](https://66b13ab822b5b2d11025c093-ibiqloyrex.chromatic.com) .

Here is the updated README with the contribution information:

```markdown
# BuildCities Public Component Library

The BuildCities Public Component Library is the public registry for all components used in the BuildCities app. This library provides a collection of reusable UI components that can be used to build and maintain the BuildCities application.

## Project Description

This repository contains the source code for the UI components used in the BuildCities app, which can be accessed at [BuildCities App](https://app.buildcities.com). The components are designed to be reusable and easily integrated into various parts of the application.

## Features

- A comprehensive library of UI components
- Easy integration with the BuildCities app
- Well-documented components with usage examples
- Public Storybook explorer for component documentation and examples

## Installation

To install a specific component from the library, you can use yarn:

```bash
yarn add @buildcities/ui-v2.components.<component-name>
```

Replace `<component-name>` with the name of the component you want to install.

## Usage

To use a component from the library, import it into your project:

```javascript
import { ActionBar } from '@buildcities/ui-v2.components.action-bar';

function App() {
  return (
    <div>
      <ActionBar />
    </div>
  );
}

export default App;
```

## Prerequisites

- Node.js
- yarn

## Documentation

To explore the available components and their usage, visit the public Storybook explorer [here](https://66b13ab822b5b2d11025c093-ibiqloyrex.chromatic.com/?path=/docs/ui-v2-components-action-bar-action-bar-docs--docs).

## Contributing

We welcome contributions to the BuildCities Public Component Library. To contribute, please visit the [component development repository](https://github.com/buildcities/build_components_new.git) and follow the contribution guidelines there.

## Authors

- [Ronald Maduka](https://github.com/rolly.maduk)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
