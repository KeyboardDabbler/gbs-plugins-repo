# Jellyfin Plugin Repository

A collection of plugins for Jellyfin by KeyboardDabbler.

## 🔌 Available Plugins

### Jellyfin Branding Plugin
Universal branding plugin that allows replacing Jellyfin branding with custom names, logos, icons, and assets.

**Features:**
- Custom application name replacement
- Custom favicon, touch icons, and splash screens
- Custom banners and logos
- PWA manifest customization
- File-based asset configuration

**Repository:** [jellyfin-branding-plugin](https://github.com/KeyboardDabbler/jf-branding-plugin)

## 📦 Installation

### Add Plugin Repository

1. Open your Jellyfin admin dashboard
2. Navigate to **Plugins** → **Repositories**
3. Click **"+"** to add a new repository
4. Enter the following details:
   - **Repository Name:** `KeyboardDabbler Plugins`
   - **Repository URL:** `https://raw.githubusercontent.com/KeyboardDabbler/gbs-plugins-repo/main/manifest.json`
5. Click **Save**

### Install Plugins

1. Navigate to **Plugins** → **Catalog**
2. Find the plugin you want to install
3. Click **Install**
4. Restart Jellyfin

## 📋 Manifest Structure

This repository contains the `manifest.json` file that lists all available plugins and their versions. The manifest is automatically updated when new plugin versions are released.

## 🤝 Contributing

1. Fork the specific plugin repository
2. Create a feature branch
3. Test thoroughly with Jellyfin
4. Submit a pull request

## 📄 License

Each plugin may have its own license. See individual plugin repositories for details.
