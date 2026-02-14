# LegalMind AI Assistant - Standalone Instructions

## 📦 Getting Started (Windows)

1.  **Download**: Get `LegalMind_App.zip` from the releases page (or the `dist-release` folder).
2.  **Extract**: Unzip the contents to a folder of your choice (e.g., `C:\LegalMind`).
3.  **Run**: Double-click `LegalMind.exe` to start the application.

> **Note**: The application will automatically create a `LegalMind` folder in your `Documents` directory to store case data securely.

## 🍎 Getting Started (Mac)

1.  **Download**: Get the `.dmg` file from the **GitHub Releases** page (built via GitHub Actions).
2.  **Install**: Drag the app to your `Applications` folder.
3.  **Run**: Open the app.
    *   *Note*: Since the app is not signed with an Apple Developer ID, you may need to right-click and select "Open" to bypass security warnings.

## 🛠️ Building from Source

### Prerequisites
- Node.js v18 or higher
- Git

### Setup
```bash
git clone https://github.com/sasha-thecornerspore-dev/Brenner_Schatz.git
cd Brenner_Schatz
npm install
```

### Build Commands
- **Windows**: `npm run electron:pack`
- **Mac**: `npm run electron:pack:mac` (Requires macOS)

### 🤖 Automated Builds (GitHub Actions)
The project includes a GitHub Actions workflow that automatically builds for both Windows and Mac whenever you push changes to the `master` branch.

1.  Push your changes: `git push origin master`
2.  Go to the **Actions** tab on your GitHub repository.
3.  Select the **Build and Release** workflow to see the progress.
4.  Once completed, download the artifacts (Windows zip and Mac dmg) from the workflow run summary.
