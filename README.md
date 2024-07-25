# Color Step Gradient Generator

This project is a simple web application that generates a color gradient based on user input. The gradient is displayed as a series of color steps, and users can specify the start color, end color, and the number of steps. The state of the gradient can be shared via URL.

## Features

- Select start and end colors using color pickers.
- Specify the number of steps in the gradient.
- View RGB and Hex values for each step.
- URL updates dynamically to reflect the current state, allowing for easy sharing.

## Usage

1. Open the [Color Step Gradient Generator](https://battlefeel1942.github.io/color-step/).
2. Use the color pickers to select the start and end colors.
3. Adjust the number of steps using the number input.
4. The gradient will update automatically.
5. Share the URL to share the gradient configuration.

## URL Parameters

The application supports the following URL parameters:

- `start`: The start color in hex format (without the `#`).
- `end`: The end color in hex format (without the `#`).
- `steps`: The number of steps in the gradient.

### Example

To create a gradient from blue to red with 5 steps, you can use the following URL: https://battlefeel1942.github.io/color-step/?start=3498db&end=e74c3c&steps=5


## Development

To run the project locally, follow these steps:

1. Clone the repository.
2. Open the `index.html` file in your web browser.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License

This project is open source and available under the MIT License.