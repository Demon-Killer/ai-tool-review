---
title: "How to Use Midjourney in 2026: Complete Beginner's Guide with Real Examples"
description: "Learn Midjourney from zero to advanced. Step-by-step setup, prompting basics, 20+ real prompt examples with results, parameters explained, and pro tips for stunning AI images."
date: 2026-05-13
draft: false
tags: ["midjourney", "ai-image", "guide", "tutorial", "prompt-engineering"]
categories: ["guides"]
---

Midjourney produces the most visually stunning AI images available. But it has a learning curve - the quality of your output depends heavily on how you write prompts. This guide takes you from zero to creating professional-quality images.

## Step 1: Set Up Midjourney

Midjourney runs through Discord (a chat app). Here is how to start:

1. **Create a Discord account** at discord.com (free)
2. **Subscribe to Midjourney** at midjourney.com (plans start at $10/month)
3. **Join the Midjourney Discord server** (link provided after subscribing)
4. **Go to any newbies channel** or your own Discord server with the Midjourney bot

**Alternative:** Midjourney now also has a web interface at midjourney.com/imagine. This is easier for beginners than Discord.

## Step 2: Your First Image

Type `/imagine` and then your prompt. Press Enter.

**Your first prompt:**
```
/imagine prompt: a golden retriever running on a beach at sunset
```

Midjourney generates 4 variations. Click any image to enlarge, or use the U1-U4 buttons to upscale a specific image.

## Step 3: Understanding Prompt Structure

Good Midjourney prompts follow this structure:

```
[Subject] + [Setting/Environment] + [Style] + [Lighting/Mood] + [Technical Parameters]
```

**Example breakdown:**
```
A medieval knight (subject)
standing in a foggy forest at dawn (setting)
oil painting style, dramatic (style)
golden hour light, cinematic (lighting)
--ar 16:9 (technical: aspect ratio)
```

### Basic Prompt Examples

**Portrait:**
```
/imagine prompt: portrait of an elderly fisherman, weathered face, kind eyes, wearing a wool sweater, natural window light, film photography, 85mm lens --ar 4:5
```

**Landscape:**
```
/imagine prompt: misty mountain valley at sunrise, wildflowers in foreground, layered fog, golden light piercing through, atmospheric, national geographic style --ar 16:9
```

**Product shot:**
```
/imagine prompt: luxury watch product photography, on dark marble surface, dramatic side lighting, water droplets, macro detail, commercial photography --ar 16:9
```

**Architecture:**
```
/imagine prompt: modern minimalist house with floor-to-ceiling windows, surrounded by Japanese maple trees, autumn, concrete and glass, architectural photography --ar 16:9
```

**Character design:**
```
/imagine prompt: female cyberpunk mechanic, neon-lit workshop, mechanical arm, confident pose, detailed character design, concept art style --ar 2:3
```

## Step 4: Key Parameters You Need to Know

Parameters go at the end of your prompt and control technical aspects:

### Aspect Ratio (--ar)
```
--ar 16:9    Wide (landscapes, desktop wallpapers)
--ar 9:16    Tall (phone wallpapers, social stories)
--ar 4:5     Portrait (Instagram posts)
--ar 1:1     Square (profile pictures, thumbnails)
--ar 3:2     Classic photo ratio
```

### Style Raw (--style raw)
Makes images more photorealistic and less "Midjourney artistic":
```
/imagine prompt: professional headshot of a woman, studio lighting --style raw
```

### Stylize (--s)
Controls how artistic Midjourney makes the image:
```
--s 0       Minimal artistic interpretation
--s 100     Default
--s 250     More artistic (recommended for creative work)
--s 750     Maximum artistic interpretation
```

### Chaos (--c)
Controls how different the 4 variations are from each other:
```
--c 0       Very similar variations
--c 50      Default
--c 100     Very different variations (good for exploration)
```

### Quality (--q)
Controls rendering quality and time:
```
--q 0.25    Fast, lower quality
--q 0.5     Balanced
--q 1       Default quality
```

### Stop (--stop)
Stop generation early for a more painterly, less detailed result:
```
--stop 50   Very painterly
--stop 80   Slightly unfinished look
--stop 100  Full detail (default)
```

## Step 5: Advanced Prompting Techniques

### Reference Images (--ref)
Use an existing image as a style or composition reference:
```
/imagine prompt: mountain cabin in snow, cozy --ref [image_url] --ref-weight 50
```

### Character Reference (--cref)
Maintain the same character across multiple images:
```
/imagine prompt: same character reading a book in a library --cref [character_image_url] --cw 100
```

### Multi-Prompting (::)
Give different weights to different parts of the prompt:
```
/imagine prompt: red apple::3 dark background::1 dramatic lighting::2
```
Higher numbers = more emphasis on that element.

### Negative Prompting (--no)
Exclude elements you do not want:
```
/imagine prompt: clean product photo of headphones --no text, watermark, people
```

## Step 6: Style Keywords That Make a Difference

Adding style keywords dramatically improves results:

**Photography styles:**
```
film photography, polaroid, disposable camera, editorial photography,
fashion photography, street photography, macro photography
```

**Art styles:**
```
watercolor, oil painting, ink drawing, pencil sketch, charcoal,
art nouveau, art deco, ukiyo-e, impressionist, minimalist
```

**Lighting:**
```
golden hour, blue hour, dramatic lighting, studio lighting,
volumetric lighting, neon glow, candlelight, backlighting
```

**Camera/lens:**
```
35mm, 85mm portrait, wide angle, macro lens, tilt-shift,
shallow depth of field, bokeh, motion blur
```

**Mood/atmosphere:**
```
dreamy, ethereal, cinematic, moody, dark academia,
cozy, vibrant, muted colors, desaturated, high contrast
```

## Complete Prompt Examples by Category

### Social Media Post
```
/imagine prompt: flat lay of coffee, notebook, and laptop on wooden table, warm tones, cozy aesthetic, overhead shot, natural morning light --ar 4:5 --style raw --s 150
```

### YouTube Thumbnail
```
/imagine prompt: dramatic reaction face of young man looking shocked, colorful background with explosion effects, dynamic lighting, high energy, YouTube thumbnail style --ar 16:9
```

### Blog Header
```
/imagine prompt: abstract representation of artificial intelligence, flowing neural network patterns, blue and purple gradient, dark background, futuristic, clean minimal design --ar 21:9 --s 200
```

### Fantasy Art
```
/imagine prompt: ancient dragon perched on a crystal mountain, bioluminescent crystals glowing in cave, magical atmosphere, detailed fantasy illustration, epic scale, dramatic perspective --ar 16:9 --s 400
```

### Real Estate Photo
```
/imagine prompt: modern open-plan kitchen and living room, floor-to-ceiling windows with ocean view, white marble countertops, Scandinavian design, bright natural light, architectural photography --ar 16:9 --style raw
```

## Common Mistakes to Avoid

1. **Too many words**: Midjourney works best with focused prompts (20-60 words). Longer is not better.

2. **Contradicting instructions**: "photorealistic cartoon" confuses the AI. Pick one direction.

3. **Forgetting aspect ratio**: Default is square. Most uses need 16:9 or 4:5.

4. **Not iterating**: The V1-V4 buttons create variations. Use them to refine your results.

5. **Ignoring style keywords**: "A dog on a beach" vs "A dog on a beach, golden hour, film photography, shallow depth of field" produces dramatically different results.

## Pricing

| Plan | Price | Fast Hours | Features |
|------|-------|-----------|----------|
| Basic | $10/mo | ~200 images | Core features, commercial use |
| Standard | $30/mo | 15 fast hours | Unlimited relaxed mode, more features |
| Pro | $60/mo | 30 fast hours | Stealth mode, max upscale |
| Mega | $120/mo | 60 fast hours | Maximum capacity |

## FAQ

### Do I own the images I create?
Yes, with a paid subscription you have commercial rights to images you generate. Free trial images cannot be used commercially.

### Can I use Midjourney without Discord?
Yes, the web interface at midjourney.com/imagine is now available. Discord is no longer required.

### Why are my images not as good as others I see?
Prompt quality makes a huge difference. Use specific style keywords, proper aspect ratios, and iterate with variations. The examples in this guide are a good starting point.

### Can Midjourney do text in images?
It can render simple text but it is not reliable. For text-heavy designs, use Canva or Photoshop instead.

### How do I get consistent results?
Use the same seed (--seed), character reference (--cref), and style reference (--ref) across generations. Consistent prompting takes practice.

## Bottom Line

Start with simple prompts using the structure: **Subject + Setting + Style + Lighting + Parameters**. Iterate with variations. Add style keywords to level up your results. Midjourney rewards practice - the more you use it, the better your prompts become.
