# How to Release

Super simple - just tag and push:

```bash
git tag v1.0.0
git push origin v1.0.0
```

Done. GitHub Actions handles the rest.

## Version naming

- `v1.0.0` - First drop
- `v1.1.0` - Added some cool stuff
- `v1.0.1` - Fixed something that broke
- `v2.0.0` - Big changes

## If you mess up a tag

```bash
# Delete locally
git tag -d v1.0.0

# Delete from GitHub
git push origin :refs/tags/v1.0.0

# Make a new one
git tag v1.0.1
git push origin v1.0.1
```

That's it. No complicated stuff.

¯\_(ツ)_/¯
