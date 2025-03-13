# Nanushi Project Templates

Welcome to the Nanushi Project Templates repository! This repository contains starter templates for React Native mobile development projects.

## 📱 Available Templates

### 1. Base Template (`/base`)
A minimal, production-ready React Native template with:
- TypeScript configuration
- Essential dependencies
- Testing setup (Jest + React Native Testing Library)
- CI/CD workflows
- Code quality tools (ESLint, Prettier)
- Git hooks (Husky)

### 2. Full-Stack Template (`/full-stack`)
Complete full-stack mobile app template with:
- React Native frontend
- Node.js backend
- Database setup
- Authentication
- API integration
- Deployment configuration

### 3. E-commerce Template (`/e-commerce`)
E-commerce focused template with:
- Product listings
- Shopping cart
- Payment integration
- User profiles
- Order management

## 🚀 Getting Started

To use a template:

1. Clone the specific template:
```bash
# For base template
git clone -b base https://github.com/nanushi-io/project-templates.git my-project

# For full-stack template
git clone -b full-stack https://github.com/nanushi-io/project-templates.git my-project

# For e-commerce template
git clone -b e-commerce https://github.com/nanushi-io/project-templates.git my-project
```

2. Install dependencies:
```bash
cd my-project
npm install
```

3. Set up your development environment:

### For Android Development:
- Install Android Studio from [https://developer.android.com/studio](https://developer.android.com/studio)
- Open Android Studio and go to Tools > SDK Manager
- In SDK Platforms, select:
  - Android 13 (API Level 33) or newer recommended
  - Android 12 (API Level 31) minimum
- In SDK Tools, make sure you have installed:
  - Android SDK Build-Tools 33.0.0 or newer
  - Android Emulator
  - Android SDK Platform-Tools
  - CMake (from SDK Tools tab)
  - NDK (from SDK Tools tab)
- Set up environment variables:
  ```bash
  # Add these to your ~/.bash_profile, ~/.zshrc, or equivalent
  export ANDROID_HOME=$HOME/Library/Android/sdk
  export PATH=$PATH:$ANDROID_HOME/emulator
  export PATH=$PATH:$ANDROID_HOME/platform-tools
  ```
- Create an emulator:
  1. Go to Tools > Device Manager
  2. Click "Create Device"
  3. Select a device definition (e.g., Pixel 6)
  4. Select a system image (API 33 recommended)
  5. Complete the setup and start the emulator

### For iOS Development (macOS only):
- Install Xcode 14.0 or newer from the Mac App Store
- Install Xcode Command Line Tools:
  ```bash
  xcode-select --install
  ```
- Open Xcode and go to Settings > Locations (Xcode 14+)
  - If using Xcode 13 or older, go to Preferences > Locations
- Set Command Line Tools to your Xcode version
- Install iOS Simulator:
  1. Open Xcode
  2. Go to Xcode > Open Developer Tool > Simulator
  3. In Simulator, go to File > Open Simulator > iOS
  4. Choose a device (iPhone 14 or newer recommended)
- Install CocoaPods (required for iOS development):
  ```bash
  sudo gem install cocoapods
  ```

4. Start development:
```bash
npm run ios     # for iOS
npm run android # for Android
```

## 📚 Documentation

Each template includes:
- Setup instructions
- Development guidelines
- Testing procedures
- Deployment guides
- Best practices

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Links

- [Nanushi Website](https://nanushi.io)
- [Documentation](https://github.com/nanushi-io/nanushi-docs)
- [Discord Community](https://discord.gg/nanushi)