## Usage

Add the following steps to your jobs:

```yaml
- name: Compress
  uses: TonyBogdanov/zip@1.0
  with:
      args: zip -qq -r ./archive.zip ./target
```

```yaml
- name: Decompress
  uses: TonyBogdanov/zip@1.0
  with:
      args: unzip -qq ./archive.zip -d ./target
```
