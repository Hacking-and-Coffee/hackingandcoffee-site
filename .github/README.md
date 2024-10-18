# Hacking and Coffee Site

Welcome to the Hacking and Coffee Site repository. This site is built using Hugo, a fast and flexible static site generator, and styled with Tailwind CSS. Below you'll find instructions on how to set up your development environment, manage submodules, and build the site for production.

## Submodules

This project uses Git submodules for managing the content and theme. To initialize and update these submodules, run the following commands:

```bash
git submodule init
git submodule update
```

or when cloning the repo use the following command:

```bash
git clone --recurse-submodules https://github.com/0xDezzy/hackingandcoffee-site
```

To update the submodules manually, navigate to the submodule directory and pull the latest changes:

```bash
cd path/to/submodule
git pull origin main
```

## Development Environment

To set up your development environment, you'll need Node.js and npm installed. This setup is used for Tailwind CSS and running the Hugo server.

### Installing Dependencies

First, install the necessary npm packages:

```bash
npm install
```

### Running the Development Server

To start the development server with Tailwind CSS and Hugo, use the following command:

```bash
npm run dev
```

This command will start the Hugo server and watch for changes in your files, automatically rebuilding the site and refreshing your browser.

## Building for Production

To build the site for production, you need to generate the static files using Hugo. Run the following command:

```bash
npm run build
```

This will create a `public` directory with the optimized static files ready for deployment.

## Additional Information

- **Hugo Documentation**: [https://gohugo.io/documentation/](https://gohugo.io/documentation/)
- **Tailwind CSS Documentation**: [https://tailwindcss.com/docs](https://tailwindcss.com/docs)
