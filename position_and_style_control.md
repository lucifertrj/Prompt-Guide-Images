# Style and Position Control Guide

## Basic Position Control Syntax
```
[position: x=0.5, y=0.3] text or element description
[size: width=0.4, height=0.3] element specification
[rotation: degrees=15] element specification
```

## Style Control Syntax
```
[style: type=modern, weight=bold] text description
[font: family=helvetica, size=large] text specification
[effect: type=neon, intensity=0.8] element modification
```

## Complete Example Prompt for Cocktail Poster

```
[Canvas: aspect_ratio=1:1.4, background=gradient_mint_to_white]

// Main Title
[position: x=0.5, y=0.2][style: modern, elegant] "COCKTAILS NIGHT"
[font: size=large, weight=bold, color=dark_navy]

// Time Display
[position: x=0.85, y=0.15][style: minimalist] "9PM"
[font: size=medium, weight=light]

// Drink Name
[position: x=0.5, y=0.5][style: script, elegant] "Drink Well"
[font: size=xlarge, weight=medium]
[effect: type=handwritten, flow=natural]

// Cocktail Image
[position: x=0.5, y=0.7][size: width=0.6, height=0.4]
(((professional cocktail photography))), ((glass with citrus garnish)),
(clear ice), (aromatic herbs), (high-end drink presentation),
[style: commercial, professional], [lighting: soft_studio]
```

## Key Components Breakdown

### Position Control
- **x and y coordinates**: Range from 0 to 1 (0 = left/top, 1 = right/bottom)
- **Center anchoring**: x=0.5, y=0.5 places elements in the center
- **Rule of thirds**: Use x=0.33/0.66, y=0.33/0.66

### Size Control
- **Relative sizing**: Use decimal values (0.1 to 1.0)
- **Aspect ratio**: Maintain proportions with width/height ratios
- **Dynamic scaling**: Adjust based on canvas size

### Style Modifiers
1. Typography
   - Font families
   - Weights
   - Sizes
   - Effects (neon, gradient, outline)

2. Visual Effects
   - Lighting
   - Shadows
   - Blur
   - Opacity

3. Layout
   - Alignment
   - Spacing
   - Hierarchy
   - Flow

## Best Practices

1. **Layer Organization**
   - Start with background
   - Add main elements
   - Include decorative elements last

2. **Position Strategy**
   - Use grid-based positioning
   - Maintain visual hierarchy
   - Consider negative space

3. **Style Consistency**
   - Stick to one primary style theme
   - Use complementary effects
   - Maintain brand cohesion

4. **Technical Considerations**
   - Keep coordinates precise
   - Use relative sizing for scalability
   - Consider device/screen variations

## Common Patterns

### Center-Focused Design
```
[position: x=0.5, y=0.5][style: centered, bold] "MAIN ELEMENT"
[position: x=0.5, y=0.3] "SUPPORTING TEXT"
[position: x=0.5, y=0.7] "ADDITIONAL INFO"
```

### Asymmetric Layout
```
[position: x=0.3, y=0.4] "LEFT ELEMENT"
[position: x=0.7, y=0.6] "RIGHT ELEMENT"
[style: dynamic, balanced]
```

### Grid-Based Design
```
[grid: columns=3, rows=2]
[cell: 1,1] "TOP LEFT"
[cell: 2,1] "TOP CENTER"
[cell: 3,1] "TOP RIGHT"
```
