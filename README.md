# Neural Network Playground

The Neural Network Playground is an interactive visualization of neural networks, written in TypeScript using d3.js. Please use GitHub issues for questions, requests, and bugs. Your feedback is highly appreciated!

## Modifications from [original repo](https://github.com/tensorflow/playground)
- added Sine and Mish activation functions
- added support for on-the-fly changes to the regularization and regularization rate hyperparameters
- added MNIST "3" dataset
- added quantization hyperparameter

## Development

To run the visualization locally, run:
- `npm i` to install dependencies
- `npm run build` to compile the app and place it in the `dist/` directory
- `npm run serve` to serve from the `dist/` directory and open a page on your browser

For a faster edit-refresh cycle when developing, run `npm run serve-watch`

## For owners
To push to production: `git subtree push --prefix dist origin gh-pages`
