# Initialize local repository
```
repo init -u https://git.evolution-x.org/Evolution-X-Tensor/kernel_manifest -b bka
```

# Sync up
```
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

# Build

```bash
./build_<family>.sh 
```
