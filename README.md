# Multi-Platform Matrix Build with Artifacts

This repository demonstrates a GitHub Actions matrix build that runs across multiple Node.js versions, producing and uploading unique build artifacts.

- Each build job runs in parallel for Node versions 14, 16, and 18
- Each job creates a non-empty text artifact named `build-da662be-v<version>`
- Artifacts are uploaded using `actions/upload-artifact@v4`
- Step identifier `matrix-da662be` included for validation

**Contact:** 24f2007837@ds.study.iitm.ac.in.com
