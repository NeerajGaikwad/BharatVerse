# BharatVerse

**Explore. Preserve. Connect.**

**Author:** Neeraj Gaikwad (`@NeerajGaikwad`)

BharatVerse is a digital heritage project created for the Smart India Hackathon (SIH). It explores how interactive 3D and accessible storytelling can help more people discover India's sculptural and architectural heritage, regardless of distance.

The project is a starting point for a public-facing digital archive. It brings a small set of heritage stories together with interactive 3D models and clear source credits, with the aim of encouraging curiosity, learning, and care for cultural heritage.

## Why this project exists

Heritage sites and objects can be difficult to visit or experience closely. Distance, mobility, time, weather, and conservation limits all shape access. Digital models can help people inspect details, revisit an object, and learn from wherever they are. They complement in-person visits and the work of heritage communities; they do not replace them.

## What is included

- Responsive, editorial-style landing page
- Interactive embedded 3D models for Hampi, Ellora, Somaskanda, and a 10th-century Shiva sculpture
- Heritage context for the Ellora Caves, with a link to UNESCO's World Heritage listing
- Short explanation of the project's preservation approach
- Model credits and license links next to the relevant objects
- Keyboard-friendly navigation, reduced-motion support, and responsive layouts

## Run locally

This is a static site; it needs no build step or package installation.

1. Clone or download this repository.
2. Open `index.html` in a browser, or serve the folder with any static file server.

For example, with Python installed:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## 3D assets and attribution

The 3D models are embedded from Sketchfab. They are hosted by their creators and are not redistributed in this repository.

| Object | Creator / source | License |
| --- | --- | --- |
| Hampi Chariot – Momento of Honor | [Enormous on Sketchfab](https://sketchfab.com/3d-models/hampi-chariot-momento-of-honor-1e8e9212dc874323af8d21c14d553f85) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| Shiva, late 10th C CE | [Minneapolis Institute of Art on Sketchfab](https://sketchfab.com/3d-models/shiva-late-10th-c-ce-010fea0fb44442bc8d0c6888b9d03f18) | [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) |
| Somaskanda, 14th or 15th C CE | [Minneapolis Institute of Art on Sketchfab](https://sketchfab.com/3d-models/somaskanda-14th-or-15th-c-ce-c4377b0209764be4a3baa10969d6cd01) | [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) |
| Ellora Caves | [GSXNet on Sketchfab](https://sketchfab.com/3d-models/ellora-caves-india-1a5ec1e212f9451e80dc051e97164d17) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |

The Hampi model's Sketchfab listing identifies it as CC BY and describes the 16th-century Stone Chariot. Both museum sculpture scans are listed as CC0. The Ellora model is listed as CC BY. Please follow the license terms if you reuse any model outside its embedded viewer. The Ellora description links to [UNESCO's official site listing](https://whc.unesco.org/en/list/243/).

### Viewing on a phone

The embedded viewers support touch rotation and zoom. Each collection card also has a **Try in your space** link for opening its source model on Sketchfab. If that model has AR enabled by its owner and the phone supports AR, use the viewer's AR control to place it through the camera. AR availability is set by the model host; the site falls back to the regular 3D viewer otherwise. Camera access is requested only when a visitor starts the AR experience.

## Technology

- HTML and CSS
- Sketchfab embedded viewers for hosted interactive 3D and source-hosted AR when available
- Google Fonts (DM Sans and Playfair Display)

## Contributing

Contributions are welcome. To add a heritage object, include reliable historical context, a working viewer, and clear creator, source, and license details. Only add or embed a model when its reuse terms are clear. Keep the experience accessible on small screens and avoid presenting digital access as a substitute for the living site or its communities.

1. Fork the repository.
2. Create a feature branch.
3. Make your changes and check the page at desktop and mobile widths.
4. Open a pull request describing the change and citing any new assets.

## License

The original website source code is available under the MIT License. See [LICENSE](LICENSE). Third-party models and linked resources keep their own licenses.
