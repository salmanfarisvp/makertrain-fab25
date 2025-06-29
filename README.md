# 🚆 Maker Train Documentation

[![Deploy to GitHub Pages](https://github.com/salmanfarisvp/makertrain-fab25/actions/workflows/deploy.yml/badge.svg)](https://github.com/salmanfarisvp/makertrain-fab25/actions/workflows/deploy.yml)

> **Comprehensive documentation for the Maker Train IoT workshop series at FAB25, featuring hands-on Nordic Thingy:91X development**

## 🎯 About Maker Train

Maker Train is an immersive, hands-on workshop series that empowers participants to explore and build real-world IoT and embedded systems projects using cutting-edge cellular-connected hardware, the **Nordic Thingy:91X**. This documentation site provides all the resources, guides, and tutorials needed for the workshop experience.

**Workshop Details:**
- 🎪 **Event:** FAB25 (Czechia)
- 🤝 **Sponsors:** Nordic Semiconductor & Hackster.io
- 📅 **Schedule:** Two-part workshop series (July 7th & 11th, 2025)
- 🎓 **Learning Path:** From hardware setup to advanced IoT applications using the Nordic Thingy:91X.

## 📚 Documentation Structure

This documentation is organized into comprehensive sections:

### 📋 Prerequisites
Essential setup and preparation materials:
- **[Install Tools](docs/prerequisites/install-tools)** - Development environment setup
- **[Introduction to Thingy:91X](docs/prerequisites/introduction-to-thingy91x)** - Hardware overview and capabilities

### 🛠️ Guides
Step-by-step project tutorials:
- **[Basic GPIO with nRF91](docs/guides/basic-gpio-nrf91)** - Fundamental GPIO operations
- **[Blink LED](docs/guides/blink-led)** - Your first embedded project
- **[Environmental Monitoring](docs/guides/build-a-environmental-monitoring)** - Sensor integration
- **[On Track with Thingy:91](docs/guides/on-track-with-thingy91)** - GPS and tracking features
- **[Thingy:91X Rescue Guide](docs/guides/thingy91x-rescue-guide)** - Troubleshooting and recovery
- **[Escape to Prague](docs/guides/escape-to-prague)** - Advanced cellular connectivity

### 🚀 Getting Started
Begin with the **[Welcome to Maker Train](docs/welcome-to-maker-train)** page for workshop overview and schedule.

## 🛠️ Development Setup

### Prerequisites
- Node.js 18.0 or higher
- npm or yarn package manager
- Git

### Installation

```bash
# Clone the repository
git clone https://github.com/salmanfarisvp/makertrain-fab25.git
cd makertrain-fab25

# Install dependencies
npm install
```

### Development Commands

```bash
# Start development server (with hot reload)
npm run start

# Build for production
npm run build

# Clear cache
npm run clear
```

### Live Development
The development server starts at `http://localhost:3000` with live reload enabled. Any changes to documentation files will automatically refresh the browser.

## 📝 Contributing to Documentation

We welcome contributions to improve the workshop documentation! Here's how to contribute:

### Content Guidelines

1. **Follow the existing structure** - Maintain consistency with current documentation format
2. **Use clear, step-by-step instructions** - Assume readers are learning IoT development
3. **Include code examples** - Provide working, tested code snippets
4. **Add screenshots** - Visual aids help with hardware setup and software interfaces
5. **Test your changes** - Ensure all links work and instructions are accurate

### Adding New Guides

1. Create a new `.md` file in the appropriate directory (`docs/guides/` or `docs/prerequisites/`)
2. Include proper frontmatter with `sidebar_position` and other metadata
3. Follow the existing naming convention (kebab-case)
4. Add images to the corresponding `static/img/` subdirectory
5. Update the sidebar configuration in `sidebars.js` if needed

### Image Guidelines

- Store images in `static/img/[guide-name]/`
- Use descriptive filenames
- Optimize image sizes (prefer PNG for screenshots, JPG for photos)
- Include alt text for accessibility


## 🚀 Deployment

### Automatic Deployment
- **Production:** Automatically deployed to [makertrain.pro](https://makertrain.pro/) via GitHub Actions
- **Trigger:** Every push to the main branch
- **Platform:** GitHub Pages with custom domain


## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Ready to start your IoT development journey?** Visit [makertrain.pro](https://makertrain.pro/) and dive into the workshop materials! 🚀

