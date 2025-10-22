# WebAR Visualization of OpenCCO Models

This project is focus on augmented visualization of arterial trees modeled by OpenCCO algorithm

## Project Struct:

```
../
├── data/               # .json files
├── obj/                # .glb files
├── docs/               # .html files
├── src/                # source files
└── tests/              # test files
```

## Objectives:

1.  **`opencco-converter` (This Project):** Reads `tree.json` and generates `tree.glb`.
2.  **WebAR:** A web client (e.g., a phone) loads `tree.glb` using `<model-viewer>` for an AR experience.