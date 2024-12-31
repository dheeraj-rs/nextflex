# NextFlex

NextFlex is a flexible CSS and SCSS styles package for Next.js projects. It provides a set of utility classes and a responsive grid system to help you quickly build beautiful and responsive web applications.

## Installation

To install NextFlex, run the following command in your project directory:

```bash
npm install nextflex
```

## Usage

To use NextFlex in your Next.js project, import the CSS or SCSS file in your `pages/_app.js` file:

```javascript
import "nextflex/dist/index.css";
```

OR

```javascript
import "nextflex/dist/index.scss";
```

NextFlex comes with a set of utility classes and a responsive grid system that you can use in your components. For example:

```html
<div className="flex justify-center items-center h-screen">
  <div className="bg-white shadow-md rounded p-6 max-w-md w-full">
    <h1 className="text-2xl font-bold mb-4">Welcome to NextFlex</h1>
    <p className="text-gray-600 mb-6">
      NextFlex makes it easy to build responsive and beautiful web applications
      with Next.js.
    </p>
    <button
      className="bg-blue-500 hover:bg-blue-600 text-white font-bold py-2 px-4 rounded"
    >
      Get Started
    </button>
  </div>
</div>
```

## Documentation

For detailed documentation and examples, please visit the [NextFlex GitHub repository](https://github.com/your-username/nextflex).

## License

NextFlex is released under the [MIT License](LICENSE.md).
