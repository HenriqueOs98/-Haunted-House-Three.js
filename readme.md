# Three.js Journey

This was a guided project from Three.js Journey course, thanks Bruno Simon for the amazing content.

# Live Demo

Check out the deployed version of the project: [Haunted House Three.js](https://haunted-house-three-js-nu.vercel.app/)

![Project Image](./hounted_house.png)

## Project Structure

```
.vite/
    deps_temp_0aa4c961/
        package.json
package.json
readme.md
src/
    index.html
    script.js
    style.css
static/
    .gitkeep
    bush/
        .DS_Store
        leaves_forest_ground_1k/
            .DS_Store
    door/
        .DS_Store
    floor/
        .DS_Store
        coast_sand_rocks_02_1k/
            .DS_Store
    grave/
        .DS_Store
        plastered_stone_wall_1k/
            .DS_Store
    models/
        tree4.glb
    roof/
        .DS_Store
        roof_slates_02_1k/
            .DS_Store
    wall/
        .DS_Store
        castle_brick_broken_06_1k/
            .DS_Store
vite.config.js
```

## Setup

Download [Node.js](https://nodejs.org/en/download/).

Run the following commands:

```bash
# Install dependencies (only the first time)
npm install

# Run the local server at localhost:5137
npm run dev

# Build for production in the dist/ directory
npm run build
```

## Project Details

### Sky

The sky is created using the [`Sky`](command:_github.copilot.openSymbolFromReferences?%5B%22%22%2C%5B%7B%22uri%22%3A%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fhome%2Fhick%2FProjects%2Fthreejs-journey%2Fsrc%2Fscript.js%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%22pos%22%3A%7B%22line%22%3A389%2C%22character%22%3A16%7D%7D%5D%2C%227aab930c-8cb9-48f5-9374-673e6d219f7f%22%5D "Go to definition") class and added to the scene with specific material uniforms for turbidity, rayleigh, mieCoefficient, mieDirectionalG, and sunPosition.

### Fog

Fog is added to the scene using [`THREE.FogExp2`](command:_github.copilot.openSymbolFromReferences?%5B%22%22%2C%5B%7B%22uri%22%3A%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fhome%2Fhick%2FProjects%2Fthreejs-journey%2Fsrc%2Fscript.js%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%22pos%22%3A%7B%22line%22%3A405%2C%22character%22%3A16%7D%7D%5D%2C%227aab930c-8cb9-48f5-9374-673e6d219f7f%22%5D "Go to definition") with a specific color and density.

### Animation

The animation loop updates the positions of three ghost objects and the controls, and renders the scene using the [`renderer`](command:_github.copilot.openSymbolFromReferences?%5B%22%22%2C%5B%7B%22uri%22%3A%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fhome%2Fhick%2FProjects%2Fthreejs-journey%2Fsrc%2Fscript.js%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%22pos%22%3A%7B%22line%22%3A441%2C%22character%22%3A4%7D%7D%5D%2C%227aab930c-8cb9-48f5-9374-673e6d219f7f%22%5D "Go to definition").

### Configuration

The project uses Vite for development and build processes. The configuration is defined in [`vite.config.js`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fhome%2Fhick%2FProjects%2Fthreejs-journey%2Fvite.config.js%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%227aab930c-8cb9-48f5-9374-673e6d219f7f%22%5D "/home/hick/Projects/threejs-journey/vite.config.js").

## Dependencies

- [`three`](command:_github.copilot.openSymbolFromReferences?%5B%22%22%2C%5B%7B%22uri%22%3A%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fhome%2Fhick%2FProjects%2Fthreejs-journey%2Fpackage.json%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%22pos%22%3A%7B%22line%22%3A1%2C%22character%22%3A11%7D%7D%5D%2C%227aab930c-8cb9-48f5-9374-673e6d219f7f%22%5D "Go to definition"): ^0.166.1
- [`lil-gui`](command:_github.copilot.openSymbolFromReferences?%5B%22%22%2C%5B%7B%22uri%22%3A%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fhome%2Fhick%2FProjects%2Fthreejs-journey%2Fpackage.json%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%22pos%22%3A%7B%22line%22%3A14%2C%22character%22%3A5%7D%7D%5D%2C%227aab930c-8cb9-48f5-9374-673e6d219f7f%22%5D "Go to definition"): ^0.19.2
- [`vite`](command:_github.copilot.openSymbolFromReferences?%5B%22%22%2C%5B%7B%22uri%22%3A%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fhome%2Fhick%2FProjects%2Fthreejs-journey%2Fpackage.json%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%22pos%22%3A%7B%22line%22%3A6%2C%22character%22%3A12%7D%7D%2C%7B%22uri%22%3A%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fhome%2Fhick%2FProjects%2Fthreejs-journey%2Fvite.config.js%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%22pos%22%3A%7B%22line%22%3A0%2C%22character%22%3A21%7D%7D%5D%2C%227aab930c-8cb9-48f5-9374-673e6d219f7f%22%5D "Go to definition"): ^5.3.3
- [`vite-plugin-restart`](command:_github.copilot.openSymbolFromReferences?%5B%22%22%2C%5B%7B%22uri%22%3A%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fhome%2Fhick%2FProjects%2Fthreejs-journey%2Fpackage.json%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%22pos%22%3A%7B%22line%22%3A11%2C%22character%22%3A5%7D%7D%2C%7B%22uri%22%3A%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fhome%2Fhick%2FProjects%2Fthreejs-journey%2Fvite.config.js%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%22pos%22%3A%7B%22line%22%3A0%2C%22character%22%3A21%7D%7D%5D%2C%227aab930c-8cb9-48f5-9374-673e6d219f7f%22%5D "Go to definition"): ^0.4.1
