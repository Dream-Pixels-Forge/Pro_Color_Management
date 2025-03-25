# Professional Color Management for Blender

A powerful AI-driven color management addon for Blender that provides professional-grade color control and optimization for various content types.

## Features

- AI-powered color analysis and optimization
- Content-aware automatic settings
- Support for multiple color profiles (AGX, Khronos PBR, ACES, Rec.709)
- Advanced look presets for different content types
- Real-time histogram analysis
- HDR optimization
- Highlight recovery system
- Adaptive color space management

## Supported Content Types

- Interior Architecture
- Exterior Architecture
- Character Rendering
- Product Visualization
- VFX Compositing
- Animation

## Requirements

- Blender 4.0.0 or newer
- Python 3.7+
- NumPy library (included with Blender)

## Installation

1. Download the `Pro_Color_Management.py` file
2. Open Blender and go to Edit > Preferences > Add-ons
3. Click "Install" and select the downloaded file
4. Enable the addon by checking the checkbox next to "Render: Professional Color Management"

## Usage

### Basic Usage

1. Open the Properties panel in Blender
2. Navigate to the Render Properties tab
3. Find the "Professional Color Management" panel
4. Select your content type or use "Auto Detect"
5. Click "Analyze and Optimize (AI)" to automatically optimize your scene
6. Adjust settings as needed
7. Click "Apply Color Management" to apply changes

### Advanced Features

#### Content Type Selection
- Auto Detect: Automatically analyzes your scene
- Manual Selection: Choose from specialized presets for different content types

#### Color Profiles
- AGX: Modern film-like look with natural contrast
- Khronos PBR: High dynamic range with PBR accuracy
- ACES: Industry-standard color pipeline
- Rec.709: HD video standard
- Rec.2020: Ultra HD video standard
- Custom: Support for custom LUT files

#### AI Optimization
- Automatic exposure adjustment
- Contrast optimization
- Saturation enhancement
- HDR recovery
- Color space adaptation

## Settings

### Main Controls
- Content Type: Select the type of content being rendered
- Output Profile: Choose color output profile
- Look Presets: Various look options based on selected profile
- Exposure: Scene exposure adjustment (-10 to +10)
- Contrast: Output contrast (0 to 2)
- Saturation: Color saturation (0 to 2)

### Advanced Options
- Highlight Recovery: Optimize HDR content
- Color Space Adaptation: Automatic color space adjustment
- AI Optimization: Enable/disable AI-assisted optimization
- Output Bit Depth: Choose between 8-bit, 16-bit, or 32-bit output

## Best Practices

1. Start with Auto Detect for initial settings
2. Use content-specific presets for specialized work
3. Enable AI Optimization for best results
4. Adjust manual controls after AI optimization if needed
5. Use 16-bit or 32-bit output for professional work

## Known Limitations

- AI optimization requires a rendered image for analysis
- Custom LUT support limited to compatible formats
- Some features may impact render time

## License

This addon is released under GPL-3.0 License

## Author

Dimona Patrick

## Version History

- 1.2: Current release with AI optimization
- 1.1: Added support for custom LUTs
- 1.0: Initial release

## Support

For issues and feature requests,  dimona.patrick@gmail.com

