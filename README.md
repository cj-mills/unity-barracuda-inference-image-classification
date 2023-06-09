# Unity Barracuda Inference Image Classification
This Unity package extends the functionality of the [`barracuda-inference-base`](https://github.com/cj-mills/unity-barracuda-inference-base) package to perform image classification using computer vision models. 

## Demo Video
https://user-images.githubusercontent.com/9126128/231305884-865e656c-06df-42c6-a9db-c3bb1ded4c1a.mp4



## Demo Project

* **GitHub Repository:** [barracuda-image-classification-demo](https://github.com/cj-mills/barracuda-image-classification-demo)



## Code Walkthrough

* [Code Walkthrough: Unity Barracuda Inference Image Classification Package](https://christianjmills.com/posts/unity-barracuda-inference-image-classification-walkthrough/)



## Features

- Utilizes Unity's Barracuda engine for efficient inference
- Supports various worker types and Asynchronous GPU Readback



## Getting Started

### Prerequisites

- Unity game engine

### Installation

You can install the Barracuda Inference Image Classification package using the Unity Package Manager:

1. Open your Unity project.
2. Go to Window > Package Manager.
3. Click the "+" button in the top left corner, and choose "Add package from git URL..."
4. Enter the GitHub repository URL: `https://github.com/cj-mills/unity-barracuda-inference-image-classification.git`
5. Click "Add". The package will be added to your project.

For Unity versions older than 2021.1, add the Git URL to the `manifest.json` file in your project's `Packages` folder as a dependency:

```json
{
  "dependencies": {
    "com.cj-mills.barracuda-inference-image-classification": "https://github.com/cj-mills/unity-barracuda-inference-image-classification.git",
    // other dependencies...
  }
}
```



## License

This project is licensed under the MIT License. See the [LICENSE](Documentation~/LICENSE) file for details.
