# SitePack App Skeleton

This is the official skeleton for developing SitePack apps. SitePack apps allow you to extend the functionality of SitePack sites with custom features, integrations, and UI elements.

## Requirements

To register and run an app, you need a **SitePack Partner Account**.
- **Register for free**: [sitepack.eu/partners](https://sitepack.eu/partners)

## Resources

- **Official Website**: [sitepack.dev](https://sitepack.dev)
- **App Development Documentation**: [App Overview](https://sitepack.dev/docs/apps/overview)
- **Partner Portal**: [SitePack Partners](https://sitepack.eu/partners)

## Getting Started

App development for SitePack is powered by the **SitePack CLI**. 

### 1. Install the SitePack CLI
Follow the [installation instructions](https://sitepack.dev/docs/cli/installation) to set up the CLI on your machine.

### 2. Initialize your project
Start a new project using:
```bash
sitepack app:init
```

### 3. Development Workflow
- **Run in development mode**:
  ```bash
  sitepack app:dev
  ```
- **Sync changes automatically**: Use the watch command to sync your local changes to SitePack in real-time.
  ```bash
  sitepack app:watch
  ```

### 4. Publish your app
When your app is ready for release:
```bash
sitepack app:publish
```

## App Distribution & Monetization

Apps can be configured with various visibility and pricing models through the Partner Portal:
- **Visibility**: Private or Public.
- **Plans**: 
  - Free plans
  - One-time fee
  - Monthly recurring
  - Yearly recurring

## Project Structure

- `app.json`: The main configuration file for your app (metadata, permissions, settings schema).
- `templates/`: Contains Twig templates for app elements (e.g., editor elements).
- `translations/`: JSON files for multi-language support.
- `assets/`: Static files like CSS, JS, and images used by your app.
- `.sitepackignore`: Defines files and folders that should not be synced to SitePack.

## License

This project is licensed under the MIT License. See the [LICENSE.md](LICENSE.md) file for more details.

---

**Disclaimer**

SitePack provides this app skeleton as-is. We do not provide any guarantees and are not responsible for any issues, damages, or data loss resulting from the use of this software.
