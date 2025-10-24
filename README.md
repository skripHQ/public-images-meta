# Skrip Public Container Images

This repository lists and documents **public Docker images** published by **Skrip** on the [GitHub Container Registry (GHCR)](https://ghcr.io/).

It serves purely as a **metadata and reference catalog** — it does **not** contain any build or deployment scripts.  
All images here are **open source mirrors or verified builds** from upstream projects used in the Skrip infrastructure.


## Purpose

- Provide a transparent catalog of SkripHQ's public container images.  
- Record upstream provenance and version mappings
- Offer a single reference point for services who want to pull these images.


## Security & Integrity

- All builds are based on **public upstream sources** under their respective open licenses.  
- No secrets, credentials, or private dependencies are included in any image.  
- If an image is signed or attested, details will appear in the `releases/` directory.


## Important

This repository:
- **Does not** store Dockerfiles, build scripts, or automation logic.  
- **Does not** contain private or production infrastructure details.  
- Exists **solely for transparency and documentation** of publicly published images.


## License

All metadata and documentation in this repository are released under the **MIT License**.  
Each referenced container image follows the license of its upstream project.

