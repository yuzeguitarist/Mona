# Mona Color Suite

A VS Code theme pack that gently recolors your editor with palettes inspired by painters and composers. Every scheme favors natural, balanced hues so you can pick the mood that fits your current session.

## Included themes
- **Monet** – misty greens and lilacs for a soft Impressionist morning.
- **Debussy** – cool twilight violets with warm amber notes.
- **Mozart** – warm classical parchment with copper and plum ink.
- **Scarlatti** – deep terracotta dusk with glowing amber highlights.
- **Van Gogh** – starry cobalt blues with sunflower gold sparks.
- **Da Vinci** – grounded sepia workshop with brass and olive details.
- **Vermeer** – luminous cream canvas with Delft blues and golden light.
- **Klimt** – ornamental gold and emerald accents on a dark velvet backdrop.
- **Chopin** – parchment and lilac twilight balanced with inky blue notes.
- **Satie** – modern, airy sage and slate neutrals for a calm, minimalist workspace.
- **Cage** – graphite nightfall with mint and linen accents for a restrained dark UI.
- **Tadao** – pale concrete neutrals with steel-blue edges for a clean architectural feel.
- **Ikeda** – crisp white canvas with glassy cyan highlights for ultra-light clarity.

## Usage
1. Open the Command Palette and run `Preferences: Color Theme`.
2. Choose any Mona Color Suite entry to apply it.
3. Swap between themes to match your focus and lighting.

## Development
- This extension is theme-only; no activation events are required.
- Update the color JSON files in `themes/` to tweak palettes or tokens.
- Run `npm install` followed by `vsce package` if you want a `.vsix` for distribution.

## Compatibility
- Built on the standard VS Code theme format, so it works in Cursor and other VS Code–compatible editors.
- Plays nicely with language extensions and UI components because it only supplies color tokens—no custom UI code.
- If a third-party panel looks off, you can override any token via `workbench.colorCustomizations` without affecting the base palettes.