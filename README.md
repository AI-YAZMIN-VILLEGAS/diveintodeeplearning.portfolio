# Dive Into Deep Learning Portfolio

A full-stack portfolio and educational website presenting deep-learning projects, interactive TensorFlow.js demonstrations, and technical articles about artificial intelligence. The site combines front-end development, in-browser machine learning, and PHP/MySQL features for search, comments, contact messages, and newsletter subscriptions.

## Project Highlights

| Feature | Description | Technologies |
| --- | --- | --- |
| Deep-learning portfolio | Showcases computer-vision, sequence-modeling, and generative-AI work | HTML, CSS, Bootstrap, JavaScript |
| Fashion classifier | Trains a neural network in the browser and classifies Fashion-MNIST drawings | TensorFlow.js, tfjs-vis, Canvas API |
| Gesture classifier | Uses webcam input and transfer learning to recognize rock, paper, scissors, lizard, and Spock | TensorFlow.js, MobileNet, webcam API |
| Technical blog | Presents articles about GANs, CNNs, Emotion AI, and deep-learning developments | HTML, JavaScript, PHP |
| Community features | Supports comments, replies, contact messages, search, and subscriptions | PHP, MySQL, AJAX |

## Interactive Machine-Learning Projects

### Fashion-MNIST Classifier

[`training_fashion_mnist_model_in_browser.html`](training_fashion_mnist_model_in_browser.html)

An in-browser neural-network application that:

- Loads and processes Fashion-MNIST data
- Builds and trains a classification model with TensorFlow.js
- Displays the model architecture and training progress
- Allows users to draw an article of clothing on a canvas
- Predicts one of the ten Fashion-MNIST categories

### Webcam Gesture Classifier

[`training_tf_js_model_in_browser.html`](training_tf_js_model_in_browser.html)

An interactive image-classification application that:

- Captures examples from the user's webcam
- Uses MobileNet as a pretrained feature extractor
- Applies transfer learning in the browser
- Trains a custom classifier without sending images to a server
- Recognizes rock, paper, scissors, lizard, and Spock gestures

## Blog Topics

The website includes technical articles covering:

- Generative adversarial networks for 8-bit pixel art
- How deep convolutional GANs work
- DCGAN applications in video-game art
- Major deep-learning breakthroughs
- Convolutional neural networks and image recognition
- Emotion AI and affective computing

## Technologies

- **Machine learning:** TensorFlow.js, MobileNet, transfer learning
- **Front end:** HTML5, CSS3, JavaScript, jQuery, Bootstrap
- **Visualization and interaction:** tfjs-vis, Canvas API, webcam API
- **Back end:** PHP, MySQL, AJAX
- **Build tooling:** Node.js, npm, Gulp
- **UI libraries:** Owl Carousel, Isotope, Magnific Popup, Font Awesome

## Project Structure

```text
diveintodeeplearning.portfolio/
├── index.html
│   └── Main portfolio website
│
├── training_fashion_mnist_model_in_browser.html
│   └── Interactive Fashion-MNIST classifier
│
├── training_tf_js_model_in_browser.html
│   └── Webcam gesture-classification application
│
├── training_fashion_mnist_mode_in_browser/
│   └── Fashion dataset and TensorFlow.js training logic
│
├── training_tf_js_model_in_browser/
│   └── Model files, webcam utilities, and classifier scripts
│
├── dl-blogs/ and blog*.html
│   └── Deep-learning articles and blog pages
│
├── css/, js/, fonts/, and images/
│   └── Website styles, scripts, fonts, and media assets
│
├── *.php
│   └── Search, comments, contact, and subscription features
│
├── package.json and gulpfile.js
│   └── Front-end dependencies and build configuration
│
└── README.md
```

## Getting Started

### Static website and TensorFlow.js projects

Clone the repository:

```bash
git clone https://github.com/AI-YAZMIN-VILLEGAS/diveintodeeplearning.portfolio.git
cd diveintodeeplearning.portfolio
```

Install the front-end dependencies:

```bash
npm install
```

Start a local web server:

```bash
python -m http.server 8000
```

Open `http://localhost:8000` in a browser. A local server is recommended because browser security restrictions can prevent model files, webcam resources, or AJAX requests from loading correctly when pages are opened directly from the filesystem.

### PHP and database features

The comment, contact, search, and subscription features require:

- A server with PHP support
- A MySQL database
- The expected database tables
- Secure database configuration

For local PHP development, run:

```bash
php -S localhost:8000
```

Then open `http://localhost:8000`.

## Security Configuration

Before deploying the PHP features:

1. Remove hard-coded database credentials from the PHP files.
2. Rotate any credentials that were previously committed to the repository.
3. Store secrets in environment variables or server-side configuration outside version control.
4. Use prepared statements for all database queries.
5. Validate and sanitize all user-provided values on the server.
6. Add a `.gitignore` entry for local environment and secret files.

The static portfolio and TensorFlow.js demonstrations can be used without enabling the PHP/MySQL features.

## Skills Demonstrated

- Designing and developing a responsive portfolio website
- Training neural networks directly in a web browser
- Applying transfer learning with MobileNet
- Integrating webcam and canvas input with ML models
- Visualizing model training and predictions
- Building blog, search, contact, and commenting interfaces
- Connecting a PHP backend to a MySQL database
- Organizing reusable front-end components and media assets
- Communicating deep-learning concepts to technical and nontechnical audiences

## About This Repository

This project combines original portfolio content and TensorFlow.js learning exercises with a customized Colorlib front-end template. Deep-learning course materials, pretrained models, libraries, and third-party assets remain attributed to their respective authors and license holders.

The original front-end template is distributed by [Colorlib](https://colorlib.com/) under its applicable license. See [`readme.txt`](readme.txt) and the included asset licenses for details.

## Author

**Yazmin Villegas**<br>
Data Analyst | Data Scientist<br>
[GitHub](https://github.com/AI-YAZMIN-VILLEGAS)
