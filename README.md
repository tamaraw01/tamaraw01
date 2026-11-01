# Data, applied AI, and developer tools

I build image-analysis prototypes and tools for working with language models. My projects cover Python ML pipelines, inference APIs, TypeScript interfaces, and a Rust command-line tool.

I am interested in part-time remote work involving data analysis, Python automation, or applied machine learning. These repositories document the implementation, setup, and current limits of each project.

## Selected projects

### [E-WISE](https://github.com/tamaraw01/ewise-triage)

An e-waste image-triage prototype using CLIP embeddings and reference cluster centroids. A Next.js interface connects to a Python inference backend, with upload validation, low-margin rejection, and handling-route information.

Includes inference artifacts, API contract checks, image-boundary tests, and deployment documentation. Reference-dataset metrics are not field-performance estimates. Hosted image requests go to an external inference service; some evidence checks require research inputs that are intentionally excluded from the public repository.

Python · PyTorch · CLIP · FastAPI · Next.js · TypeScript

### [ctx-budget](https://github.com/tamaraw01/ctx-budget)

A local Rust CLI that estimates how tokens are distributed across a codebase, ranks files, and exports text, JSON, or CSV reports for context planning.

Includes unit tests, CLI integration tests, and CI configuration. The estimator uses a word/byte heuristic rather than a model tokenizer. Check bundled model specifications against provider documentation before planning requests.

Rust · CLI · Code analysis

### [NanoCoT](https://github.com/tamaraw01/nanocot)

An experimental chat-completions proxy that routes requests with simple complexity rules, adds short reasoning instructions, and removes specifically tagged response blocks.

Includes dependency-free component tests for routing, injection, and text cleanup. It does not establish model-quality gains or measured API savings. Streaming is buffered, and the proxy needs trusted-network deployment.

Python · FastAPI · API integration

## Computer-vision research

- [Fundus-image classification](https://github.com/tamaraw01/Glaucoma-Detection-from-Deep-Fundus-Images): modular EfficientNet-B3 training, patient-grouped splits, evaluation, and Grad-CAM. The README documents a default-training shape bug and setup limitations. No trained checkpoint or clinical-performance claim is supplied.
- [Pothole segmentation](https://github.com/tamaraw01/Pothole-Segmentation): UNet++ notebook with composite loss, validation threshold selection, and RLE export. The README records unresolved inference geometry and augmentation-compatibility issues. Model results have not been reproduced.

## Tools used in these repositories

Python, Rust, TypeScript, SQL, PyTorch, scikit-learn, FastAPI, Next.js, Docker, and GitHub Actions.

## Contact

[Open a profile issue](https://github.com/tamaraw01/tamaraw01/issues) to discuss a project or a scoped collaboration. Keep credentials and private datasets out of public issues.
