# Load PDF files from Google Drive on PSPDFKit viewer. project built with React + TypeScript + Vite

#### Update the Demo license key, Google Client id in .env file, and few paths in the app.tsx 

## Getting Started

To get started with the Signing Demo project, follow these steps:

1. Clone the repository from GitHub

2. Open a terminal and navigate to the project directory

3. Install the project dependencies:
    ```bash
    npm i
    ```

4. Copy the PSPDFKit for Web library assets to the `public` directory:
    ```bash
    cp -R ./node_modules/pspdfkit/dist/pspdfkit-lib public/pspdfkit-lib
    ```

5. Run the project locally:
    ```bash
    npm run dev
    ```

#### Note: Still need to resolve the permission issue while updating the same file with the same fileId to Google Drive. 
