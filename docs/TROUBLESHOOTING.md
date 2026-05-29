# Troubleshooting

## Common Issues

### Installation Issues

**Problem:** `npm install` fails
```bash
# Solution: Clear npm cache
npm cache clean --force
npm install
```

### Build Errors

**Problem:** `npm run build` fails
```bash
# Check Node version
node --version

# Update dependencies
npm update
npm install
```

### Runtime Errors

**Problem:** Application crashes on start
```bash
# Check for missing environment variables
# Copy .env.example to .env and configure
cp .env.example .env
```

## Getting Help

- Check [GitHub Issues](https://github.com/AuraAlignBra/code-review-ai/issues)
- Read the [Documentation](./GETTING_STARTED.md)
- Open a new issue with detailed error message
