![VERT](static/banner.png)

VERT is a file conversion utility for the web that uses WebAssembly to convert files directly on your device instead of on a cloud. Check out the live instance at [vert.sh](https://vert.sh).

VERT is built with Svelte and TypeScript.

## Features

- Convert files directly on your device using WebAssembly
- No file or file size limits
- Supports conversion of multiple file formats
- User-friendly interface built with Svelte

## Getting Started

### Prerequisites

Make sure you have the following installed:

- [Bun](https://bun.sh/)

### Installation
```sh
# Clone the repository
git clone https://github.com/not-nullptr/vert.git

cd vert

# Install dependencies
bun i
```

### Running Locally

To run the project locally, run `bun dev`.

This will start a development server. Open your browser and navigate to `http://localhost:5173` to see the application.

### Building for Production

Before building for production, make sure you create a `.env` file in the root of the project with the following content:

```sh
PUB_HOSTNAME=vert.sh # change to your domain
PUB_PLAUSIBLE_URL=https://plausible.example.com # can be empty if not using Plausible
```

To build the project for production, run `bun run build`

This will build the site to the `build` folder. You can then start the server with `bun run preview` and navigate to `http://localhost:4173` to see the application.

## License

This project is licensed under the AGPL-3.0 License, please see the [LICENSE](LICENSE) file for details.
