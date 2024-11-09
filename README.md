# MASM Syntax Highlighter

A Visual Studio Code extension that provides syntax highlighting for Microsoft Macro Assembler (MASM) files. This extension enhances the readability of MASM assembly code by applying color highlighting to different syntax elements including:

- Control keywords
- Operators 
- Comments
- Strings
- Registers

## Features

The extension automatically applies syntax highlighting to files with `.asm` and `.inc` extensions. The color scheme includes:

- Orange highlighting for control keywords
- Light gray for operators
- Gray for comments (lines starting with semicolon)
- Green for strings
- Purple for registers

## Requirements

This extension requires Visual Studio Code version 1.95.0 or higher.

## Extension Settings

This extension does not add any VS Code settings. The syntax highlighting is automatically applied to MASM files.

## Known Issues

No known issues at this time.

## Release Notes

### 0.0.1

Initial release with basic MASM syntax highlighting support:
- File extension support for .asm and .inc files
- Syntax highlighting for basic MASM elements
- Custom color theme for MASM code

---

## Contributing

If you'd like to contribute to the development of this extension, please visit our GitHub repository.

## Acknowledgements

This extension was written by Cursor AI (https://cursor.com).

## License

This extension is available under the MIT license.

## Publishing to VS Code Marketplace

To package and publish this extension to the VS Code Marketplace:

1. Install vsce (Visual Studio Code Extensions):
   ```bash
   npm install -g vsce
   ```

2. Create a Personal Access Token (PAT):
   - Go to [Azure DevOps](https://dev.azure.com)
   - Create/login to your account
   - Go to User Settings > Personal Access Tokens
   - Create a new token with "Marketplace (Publish)" scope

3. Login to vsce:
   ```bash
   vsce login <publisher-name>
   ```

4. Package the extension:
   ```bash
   vsce package
   ```

5. Publish the extension:
   ```bash
   vsce publish
   ```

For more detailed publishing instructions, visit the [Publishing Extensions](https://code.visualstudio.com/api/working-with-extensions/publishing-extension) guide.
