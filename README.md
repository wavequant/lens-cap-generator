#  Camera Lens Cap 3D Model Designer

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Demo-brightgreen?style=for-the-badge&logo=github)](https://wavequant.github.io/lens-cap-generator/)

A powerful, browser-based tool for creating custom, 3D-printable push-on lens caps. This application is built with pure, dependency-free JavaScript and renders a real-time 3D preview of your design.

**[➡️ View the Live Demo Here](https://wavequant.github.io/lens-cap-generator/)**

---

![Lens Cap Generator Screenshot](https://github.com/wavequant/lens-cap-generator/blob/main/interface.png)
*(A sample of the user interface)*

## About The Project

This project was created to provide a fast, intuitive, and highly customizable way to design a common but essential photography accessory. Instead of relying on generic, one-size-fits-all models, this tool allows photographers and 3D printing enthusiasts to generate a perfectly sized and styled lens cap for any lens.

The entire application runs in the browser with no server-side processing, ensuring privacy and speed.

## Features

This generator provides deep customization over every aspect of the lens cap's geometry:

*   **Core Dimensions:**
    *   **Filter Thread Diameter:** Sets the base size of the cap.
    *   **Additional Diameter:** Fine-tune the fit by adding a small tolerance to the inner diameter.
    *   **Cap Height:** Control the overall height/depth of the cap.

*   **Serrated Outer Grips:**
    *   **Number of Grips:** Define the exact number of evenly-spaced serrations.
    *   **Grip Depth & Height:** Control the prominence and vertical space of the grip area.
    *   **Grip Position:** Adjust the top margin for a clean, professional look.

*   **Internal Friction Ridge:**
    *   **Ridge Inset:** Control how tight the cap fits by defining the depth of the internal ridge.
    *   **Ridge Position:** Adjust the vertical placement of the ridge inside the cap.

*   **Engraved Text:**
    *   **Custom Multi-Line Text:** Engrave any text, such as the lens focal length or brand, on top of the cap.
    *   **Adjustable Text Size:** Scale the text to occupy the desired amount of space.

*   **Real-time 3D Preview:**
    *   Instantly visualize your changes in a 3D wireframe preview.
    *   Robust, matrix-based rotation allows for smooth inspection from any angle.

*   **STL Export:**
    *   Generate a binary STL file, ready for any 3D slicer (like PrusaSlicer, Cura, etc.).
    *   The exported filename automatically includes all of your custom parameters for easy identification.

## Built With

This project is intentionally lightweight and has zero external dependencies.

*   **Vanilla HTML5**
*   **Vanilla CSS3**
*   **Vanilla JavaScript (ES6+)**

## How to Use

1.  **Open the [Live Demo](https://wavequant.github.io/lens-cap-generator/)** in your browser.
2.  **Adjust the parameters** in the right-hand panel to match your lens and desired style.
3.  Click **"Generate Model"** to see the 3D preview update.
4.  Once you are happy with the design, click **"Download STL"**.
5.  **Slice and 3D print** your custom lens cap!

## Running Locally

To run this project on your local machine:

1.  Clone the repository:
    ```bash
    git clone git@github.com:wavequant/lens-cap-generator.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd lens-cap-generator
    ```
3.  Open the `index.html` file in your favorite web browser.

## License

Distributed under the MIT License. See `LICENSE` for more information.
