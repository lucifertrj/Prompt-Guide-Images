# Image Generation Prompt Terminology Guide

## Core Components

### Subject Matter
- **Subject**: The main focus of your image
- **Action**: What the subject is doing
- **Setting**: Where the scene takes place
- **POV (Point of View)**: Camera angle and perspective
  - Bird's eye view
  - Worm's eye view
  - Close-up
  - Wide shot
  - Dutch angle

### Artistic Style
- **Medium**:
  - Digital art
  - Oil painting
  - Watercolor
  - Photography
  - 3D render
  - Pencil sketch
  - Concept art

- **Art Movements**:
  - Impressionism
  - Art Deco
  - Cyberpunk
  - Minimalist
  - Surrealism
  - Pop Art
  - Gothic

### Technical Specifications
- **Quality Markers**:
  - High resolution
  - Sharp focus
  - Detailed
  - Professional
  - Studio quality
  - 8K
  - RAW

- **Lighting**:
  - Natural light
  - Golden hour
  - Studio lighting
  - Dramatic lighting
  - Rim light
  - Soft light
  - Hard light
  - Backlit
  - Cinematic lighting

### Composition Elements
- **Color Palette**:
  - Monochromatic
  - Complementary colors
  - Warm tones
  - Cool tones
  - Pastel
  - Vibrant
  - Muted

- **Atmosphere**:
  - Moody
  - Ethereal
  - Dramatic
  - Peaceful
  - Mysterious
  - Whimsical

## Advanced Techniques

### Camera Settings
- **Lens Properties**:
  - Wide-angle lens
  - Telephoto lens
  - Macro lens
  - Fish-eye lens
  - 35mm
  - 85mm portrait

- **Technical Terms**:
  - Bokeh
  - Depth of field
  - F-stop
  - Long exposure
  - Motion blur
  - Tilt-shift

### Special Effects
- **Post-Processing**:
  - HDR
  - Double exposure
  - Chromatic aberration
  - Lens flare
  - Film grain
  - Vignette

- **Artistic Effects**:
  - Volumetric lighting
  - Ray tracing
  - Global illumination
  - Subsurface scattering
  - Ambient occlusion

## Best Practices

### Structure Your Prompt
1. Start with the subject and main action
2. Specify the setting and context
3. Define the artistic style
4. Add technical specifications
5. Include composition details
6. Fine-tune with special effects

### Tips for Better Results
- Use clear, specific descriptions
- Combine multiple artistic influences
- Balance technical terms with creative description
- Include both positive and negative prompts when supported
- Build complexity gradually
- Use reference artists or works when appropriate

### Common Modifiers
- **Quality**: masterpiece, professional, detailed
- **Style**: trending, featured, award-winning
- **Composition**: rule of thirds, symmetrical, centered
- **Mood**: dramatic, peaceful, energetic
- **Time**: golden hour, blue hour, night time
- **Weather**: foggy, rainy, sunny, overcast

### Example Prompt Structure

```
[Subject] in [Action], [Setting]
[Artistic Style] + [Medium]
[Lighting] with [Atmosphere]
[Camera Specifications - Optional]
[Special Effects - Optional]
[Quality Modifiers]
```

# Prompt Weighting and Flow Guide

## Basic Prompt Weighting

### Standard Syntax
- Parentheses Method: (word) = 1.1x emphasis
- Multiple Parentheses: ((word)) = 1.2x emphasis
- Maximum typically: (((word))) = 1.3x emphasis

### Weight Values
```
[1] = Standard weight
(word) = 1.1x weight
((word)) = 1.2x weight
(((word))) = 1.3x weight
[word:0.8] = 80% weight
[word:1.2] = 120% weight
```

## Advanced Weighting Examples

### Portrait Example
```
(((close-up portrait))) of a (young woman), 
(pale skin:1.2), (freckles:0.8), 
((flowing red hair:1.3)),
[casual smile:1.1], 
(bokeh:0.9), (natural lighting:1.2)
```

### Landscape Example
```
(((majestic mountain landscape))),
(snow-capped peaks:1.3),
(pine forest:0.9) in foreground,
((dramatic clouds:1.2)),
[sunset:1.1], [mist:0.7],
(cinematic:1.2), (wide shot:1.1)
```

## Prompt Flowing Techniques

### Sequential Flow
Building complexity in logical order:
```
Subject → Setting → Style → Details → Effects

Example:
1. (((medieval knight)))
2. standing in (gothic cathedral)
3. [dramatic lighting:1.2]
4. ((ornate armor:1.3)) with (blue cape:0.9)
5. (volumetric light rays:0.8), (mist:0.7)
```

### Layered Description
Moving from general to specific:
```
Main concept → Specific details → Artistic style → Technical aspects

Example:
(((cyberpunk city street))),
((neon signs:1.2)), (hover cars:0.9),
[rain-slicked pavement:1.1],
(blade runner style:1.3),
[cinematic composition:1.2],
(volumetric lighting:0.8)
```

## Advanced Techniques

### Emphasis Combinations
```
Primary Focus:
(((main subject:1.4))), ((supporting elements:1.2))

Background Elements:
[background details:0.7], [atmospheric effects:0.8]

Style Modifiers:
((artistic style:1.3)), (technical aspects:1.1)
```

### Balance Examples

#### Portrait Shot
```
(((professional headshot)))
((young businessman:1.2))
(warm smile:1.1)
(tailored suit:1.0)
[bokeh background:0.8]
[studio lighting:1.2]
[4k:1.1], [sharp:1.0]
```

#### Fantasy Scene
```
(((magical forest clearing)))
((ancient stone circle:1.3))
(glowing mushrooms:1.1)
[morning mist:0.9]
((ethereal lighting:1.2))
[fairy dust particles:0.8]
(photorealistic:1.1)
```

## Best Practices

### Weight Distribution Rules
1. Main subject/focus: 1.2-1.4x weight
2. Supporting elements: 1.1-1.2x weight
3. Background elements: 0.7-0.9x weight
4. Style/mood: 1.0-1.2x weight
5. Technical aspects: 0.9-1.1x weight

### Common Pitfalls to Avoid
- Over-weighting (too many high-weight elements)
- Conflicting weights on related elements
- Inconsistent weighting syntax
- Too many weighted elements
- Neglecting to weight important elements

### Optimization Tips
1. Start with unweighted prompt
2. Add weights to most important elements first
3. Fine-tune supporting elements
4. Balance background weights
5. Test and adjust
6. Keep track of successful combinations

## Example Complete Weighted Prompt
```
(((ethereal portrait))) of ((young woman:1.3)),
(pale skin:1.1), (flowing white dress:1.2),
((iridescent butterfly wings:1.3)),
[forest background:0.8], [morning mist:0.7],
((soft rim lighting:1.2)), (bokeh:0.9),
[dreamy atmosphere:1.1], [4k:1.0],
[photo realistic:1.2], [detailed:1.1]
```

### Element Breakdown:
- Core subject: (((ethereal portrait))) - maximum emphasis
- Main features: ((young woman:1.3)), ((iridescent butterfly wings:1.3))
- Supporting elements: (pale skin:1.1), (flowing white dress:1.2)
- Background: [forest background:0.8], [morning mist:0.7]
- Technical aspects: [photo realistic:1.2], [detailed:1.1]
- Atmosphere: [dreamy atmosphere:1.1]
