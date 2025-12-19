# TransAttUnet: Medical Image Segmentation Presentation

This repository contains the presentation slides for the **TransAttUnet** project, designed using HTML, CSS, and the **Reveal.js** framework.

The presentation details a novel approach to medical image segmentation, focusing on integrating **Visual State Space (VSS) Blocks (Mamba architecture)** and **Evolutionary Optimization** to address the computational limitations of Transformer-based models while maintaining high accuracy.

## Live Demo
You can view the presentation online at the link below:
**[Insert your GitHub Pages Link Here]**

*(To enable: Go to Settings > Pages > Select 'main' branch > Save)*

## Navigation Controls

This presentation is optimized for desktop viewing. To ensure the best experience, please use the keyboard shortcuts listed below. The navigation separates slide transitions from text animations (fragments).

### Desktop Keyboard Shortcuts

| Key | Action | Description |
| :--- | :--- | :--- |
| **Left Arrow** | **Next Slide** | Move to the next slide (RTL layout) |
| **Right Arrow** | **Previous Slide** | Return to the previous slide |
| **Down Arrow** | **Next Fragment** | Reveal the next bullet point or animation within the current slide |
| **Up Arrow** | **Previous Fragment** | Hide the current bullet point or animation |
| **F** | **Full Screen** | Enter full-screen mode |
| **Esc** | **Overview** | Show the slide map overview |

**Note for Mobile Users:**
On touch devices, standard navigation controls (arrows) are enabled in a linear mode. Tapping the "Next" arrow will automatically cycle through text fragments before moving to the next slide.

## Technologies Used

* **Core:** HTML5, CSS3, JavaScript
* **Framework:** [Reveal.js](https://revealjs.com/)
* **Icons:** FontAwesome 6 (For vector icons)
* **Mathematics:** KaTeX (For rendering LaTeX equations)
* **Font:** Vazirmatn

## Presentation Outline

1.  **Introduction & Problem Statement:** Limitations of U-Net (local focus) and Transformers (quadratic complexity).
2.  **Proposed Architecture:** A hybrid framework combining U-Net structure with Mamba (VSS) blocks and Genetic Algorithms.
3.  **Key Innovations:**
    * **Linear Complexity O(N):** Replacing Self-Attention with VSS Blocks.
    * **Dynamic Aggregation Bridge (DAB):** Improved feature fusion between encoder and decoder.
    * **Automation:** Hyperparameter tuning via Genetic Algorithms and noise reduction via PSO.
4.  **Experimental Results:** Quantitative comparison (Dice/IoU metrics) against state-of-the-art models.
5.  **References:** Citations and bibliography.

## Authors

* **Amir Hossein Amjadian**
* **Mehdi Shokri**