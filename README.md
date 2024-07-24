# 3D Model Viewer

This is a React application for viewing, compressing, and exporting 3D models. The application uses React Three Fiber to render 3D models and includes features for uploading, compressing, and exporting GLB files.

## Features

- **Upload 3D Models**: Upload GLB files to view in the 3D scene.
- **Compress 3D Models**: Compress the uploaded GLB files to reduce their size.
- **Export Compressed Models**: Export the compressed GLB files.

## Technologies Used

- **React**: JavaScript library for building user interfaces.
- **React Three Fiber**: React renderer for Three.js.
- **Three.js**: JavaScript library for creating 3D graphics.
- **FileSaver**: Library to save files on the client-side.
- **@react-three/drei**: Collection of useful helpers for React Three Fiber.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/3d-model-viewer.git
   cd 3d-model-viewer
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Start the development server:**

   ```bash
   npm start
   ```

   The application will be available at `http://localhost:3000`.

## Usage

1. **Upload a Model**: Click the "Upload" button and select a GLB file to upload.
2. **Compress the Model**: After uploading, click the "Compress" button to compress the file.
3. **Export the Compressed Model**: Once the compression is complete, click the "Export" button to download the compressed file.

## Project Structure

- `src/components/Model.js`: Component for rendering the uploaded 3D model.
- `src/components/UploadButton.js`: Component for handling file uploads.
- `src/components/CompressButton.js`: Component for compressing the uploaded file.
- `src/components/ExportButton.js`: Component for exporting the compressed file.
- `src/components/Message.js`: Component for displaying messages.
- `src/App.js`: Main application component.
- `src/App.css`: CSS for styling the application.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## Acknowledgements

- [React](https://reactjs.org/)
- [React Three Fiber](https://github.com/pmndrs/react-three-fiber)
- [Three.js](https://threejs.org/)
- [FileSaver.js](https://github.com/eligrey/FileSaver.js)
- [@react-three/drei](https://github.com/pmndrs/drei)
