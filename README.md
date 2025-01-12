# Ionic Image View App

## Objective

This project demonstrates the development of a multi-page Ionic Angular application that captures images, manipulates them using a canvas, and navigates between pages to display exported images. The application highlights skills in Ionic, Angular, and user interface design.

---

## Features

### Page 1: Image Capture and Display

- **Canvas Area**: Displays captured images.
- **Input Fields**: Specify width and height for image manipulation.
- **Open Camera Button**:
  - Opens the device camera to capture an image.
  - Displays the captured image on the canvas, replacing any existing image.
- **Export Button**:
  - Exports the image from the canvas using specified width and height, maintaining image quality.
  - Clears the canvas and navigates to the second page after a 2-second delay.

### Page 2: Display Exported Images

- **Image Display**: Displays all exported images using lazy loading for improved performance.
- **Unlimited Images**: No restriction on the number of images displayed.

## Setup Instructions

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v16 or later recommended)
- [Ionic CLI](https://ionicframework.com/docs/cli) (v6 or later)
- Android or iOS development environment for device testing.

### Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-folder>

   ```

2. Install dependencies:

```
npm install
```

3. Add the required Cordova plugins:

```
 -ionic cordova plugin add @awesome-cordova-plugins/camera
 -ionic cordova plugin add cordova-plugin-filepath
```

4. Install corresponding npm packages:

```
 -npm install @awesome-cordova-plugins/camera @awesome-cordova-plugins/file-path
```

### Running the App

1. Start the development server:

   ```bash
   ionic serve

   ```

2. Test on an Android device:

```
- ionic cordova run android --device

```
