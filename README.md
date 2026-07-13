Clone this repo directly into `.repo/local_manifests` inside your ROM source tree:
```bash
git clone https://github.com/BluedMC-Amethyst/local_manifest-amethyst.git .repo/local_manifests
```

Then sync your repos
```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
