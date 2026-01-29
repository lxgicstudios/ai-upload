---
name: upload-gen
description: Generate file upload handling code. Use when building upload features.
---

# Upload Generator

File upload handling has lots of edge cases. Describe your needs and get complete upload code.

**One command. Zero config. Just works.**

## Quick Start

```bash
npx ai-upload "image upload to S3 with resize"
```

## What It Does

- Generates complete upload handling code
- Supports local, S3, and GCS storage
- Includes validation and processing
- TypeScript types included

## Usage Examples

```bash
# S3 upload
npx ai-upload "image upload to S3 with resize"

# Local storage
npx ai-upload "file upload to local disk"

# Multiple files
npx ai-upload "batch upload with progress tracking"
```

## Best Practices

- **Validate file types** - don't trust extensions
- **Set size limits** - prevent abuse
- **Use signed URLs** - direct to S3 when possible
- **Handle errors gracefully** - uploads fail often

## When to Use This

- Adding upload feature to app
- Migrating storage providers
- Learning upload patterns
- Setting up image processing

## Part of the LXGIC Dev Toolkit

This is one of 110+ free developer tools built by LXGIC Studios. No paywalls, no sign-ups, no API keys on free tiers. Just tools that work.

**Find more:**
- GitHub: https://github.com/LXGIC-Studios
- Twitter: https://x.com/lxgicstudios
- Substack: https://lxgicstudios.substack.com
- Website: https://lxgicstudios.com

## Requirements

No install needed. Just run with npx. Node.js 18+ recommended. Needs OPENAI_API_KEY environment variable.

```bash
npx ai-upload --help
```

## How It Works

Takes your upload requirements and generates complete handling code including validation, storage, and error handling. Works with common storage providers.

## License

MIT. Free forever. Use it however you want.
