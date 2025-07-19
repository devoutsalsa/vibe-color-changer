# Vibe Color Changer

A simple, interactive web application that allows users to change the background color of the page with a click of a button or by entering a custom color value. This project serves as a foundational "toy project" for learning web development with HTML, Tailwind CSS, and JavaScript, and for practicing "vibe coding" with AI assistance.

## Live Demo

You can see the Vibe Color Changer live on Vercel:
https://vibe-color-changer.vercel.app/

## Features

* **Random Color Generation:** Click a button to instantly change the background to a random vibrant color.

* **Custom Color Input:** Enter a specific color name (e.g., "red", "blue") or a hex code (e.g., "#FF00FF") to apply it.

* **Responsive Design:** Styled with Tailwind CSS for a clean look on various screen sizes.

* **Simple & Lightweight:** A single HTML file, easy to understand and extend.

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You only need a web browser to view the application. For development and deployment, you'll need Node.js and npm (or Yarn) installed to use the Vercel CLI.

* Node.js & npm: https://nodejs.org/

* Vercel CLI:

  ```bash
  npm install -g vercel
  ```

  or

  ```bash
  yarn global add vercel
  ```

### Installation

1. **Clone the repository (or create the file manually):**
   If you're starting from scratch, create a new folder:

   ```bash
   mkdir vibe-color-changer
   cd vibe-color-changer
   ```

   Then, create an `index.html` file inside this folder and paste the provided code into it.

2. **Open in your browser:**
   Simply open the `index.html` file directly in your web browser.

## Deployment

This project is designed for easy deployment with Vercel.

1. **Navigate to the project directory:**
   Open your terminal and change into the `vibe-color-changer` directory:

   ```bash
   cd path/to/vibe-color-changer
   ```

2. **Deploy using Vercel CLI:**
   Run the `vercel` command:

   ```bash
   vercel
   ```

   Follow the prompts. Vercel will automatically detect that it's a static HTML site and deploy it. You'll be provided with a live URL upon successful deployment.

## Vibe Coding with AI (e.g., Cursor Pro)

This project is ideal for practicing "vibe coding" by giving prompts to your AI-powered IDE (like Cursor Pro). Here's how you can leverage it:

* **Initial Structure:** You could prompt your IDE to "Create a basic HTML page with a title and a button."

* **Adding Features:** "Add an input field and another button below the existing one. The input should take a color, and the new button should apply it to the background."

* **Styling Enhancements:** "Make the buttons look more modern with rounded corners and a shadow using Tailwind CSS."

* **Refactoring:** "Refactor the JavaScript to use a single function for color application, whether random or custom."

By providing clear, contextual prompts, you can guide your IDE to generate and modify code incrementally, allowing you to focus on the desired outcome rather than every syntax detail.

## Contributing

Feel free to fork this repository, make improvements, and submit pull requests. Any contributions are welcome!

## License

This project is open source and available under the MIT License.
