# Project Structure

## Root Level
```
.
├── .claude/              # Claude-specific configuration
├── .git/                 # Git repository metadata
├── .kiro/                # Kiro IDE configuration and guidance
├── LICENSE               # Apache 2.0 license
└── README.md             # Project documentation
```

## .kiro/ Directory
```
.kiro/
├── steering/             # AI steering rules and guidelines
│   ├── product.md        # Product overview
│   ├── tech.md           # Technology stack and commands
│   └── structure.md      # Project organization (this file)
├── specs/                # Feature specifications
└── settings/             # IDE settings and MCP configuration
```

## Key Directories

### .claude/
Contains Claude-specific settings and permissions configuration for local development.

### .kiro/
Central hub for Kiro IDE configuration:
- **steering/**: Markdown files that guide AI assistant behavior and project conventions
- **specs/**: Feature specifications and design documents
- **settings/**: MCP server configuration and IDE preferences

### .git/
Standard Git repository structure for version control.

## File Organization Principles
- Keep configuration files in `.kiro/` for IDE-related settings
- Use `.claude/` for Claude-specific configurations
- Maintain clear separation between configuration, documentation, and code
- Use markdown for all documentation and steering files
