# Publishing Instructions

## Release Process

1. Update version in relevant files (package.json, setup.py, etc.)

2. Commit changes:
```bash
git add .
git commit -m "Release v1.0.2"
git tag v1.0.2
git push origin v1.0.2
git push origin main
