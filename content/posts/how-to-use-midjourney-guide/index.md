---
title: "How to Use Midjourney in 2026: Complete Beginner's Guide"
description: "Step-by-step guide to using Midjourney for creating stunning AI images. From setup to advanced prompting techniques, everything you need to know."
date: 2026-05-13
draft: false
tags: ["midjourney", "ai-art", "tutorial", "image-generation", "guide"]
categories: ["guides"]
---

Midjourney creates some of the most beautiful AI-generated images available. Whether you need art for a blog, social media posts, marketing materials, or just want to explore your creativity, this guide will get you started.

## What is Midjourney?

Midjourney is an AI image generation tool that turns text descriptions into stunning visual images. It runs through Discord (a chat platform) and produces results that often look like professional artwork or photography.

## Step 1: Set Up Discord

Midjourney runs entirely through Discord. If you do not have it yet:

1. Go to [discord.com](https://discord.com) and create a free account
2. Download the Discord app (desktop or mobile) or use the web version
3. You do not need to create your own server - Midjourney has its own

## Step 2: Join Midjourney

1. Go to [midjourney.com](https://midjourney.com)
2. Click **Join the Beta**
3. You will be redirected to the Midjourney Discord server
4. Accept the Discord invite

## Step 3: Subscribe to a Plan

Midjourney no longer offers free trials. You need a paid plan:

| Plan | Price | Fast Hours | Features |
|------|-------|------------|----------|
| Basic | $10/month | ~200 images | Commercial use, 3 concurrent jobs |
| Standard | $30/month | ~900 images + unlimited relax | Stealth mode, higher priority |
| Pro | $60/month | ~1800 images + unlimited relax | All features, highest priority |

For most beginners, the **Basic plan at $10/month** is enough to start.

To subscribe:
1. In any Midjourney channel, type `/subscribe`
2. Click the link that appears
3. Choose your plan and pay

## Step 4: Generate Your First Image

1. In the Midjourney Discord server, go to any channel starting with `newbies`
2. Type `/imagine` and press Enter
3. A prompt box will appear. Type your description, for example:
   ```
   a golden retriever puppy sitting in a field of sunflowers, soft morning light, photorealistic
   ```
4. Press Enter and wait about 30-60 seconds
5. Midjourney will return 4 image variations (called a grid)

## Step 5: Upscale and Vary

After generating your grid, you will see buttons below it:

- **U1, U2, U3, U4** - Upscale (enlarge) a specific image from the grid
- **V1, V2, V3, V4** - Create variations of a specific image
- **🔄** - Re-run the same prompt for a new set of 4

**Workflow:**
1. Look at your grid of 4 images
2. Pick the one you like best (e.g., the top-left one = U1)
3. Click **U1** to upscale it
4. If you want variations of that upscaled image, click **V1** through **V4**
5. Repeat until you get the perfect image

## Step 6: Save Your Images

- Click on the upscaled image to open it full size
- Right-click → **Save image as** to download
- On mobile, long-press the image → Save

You can also find all your generated images at [midjourney.com/app](https://midjourney.com/app) by logging in with your Discord account.

## Writing Better Prompts

The key to great Midjourney images is good prompting. Here are techniques that dramatically improve results:

### Basic Prompt Structure

```
[subject] + [setting] + [style] + [lighting] + [mood] + [technical details]
```

### Prompt Examples by Category

**Photorealistic:**
```
a weathered fisherman mending nets on a wooden dock, golden hour, coastal village background, shot on Canon EOS R5, 85mm lens, shallow depth of field
```

**Illustration:**
```
a cozy treehouse library with spiral staircases, children's book illustration style, warm lighting, detailed, whimsical
```

**Product photography:**
```
premium wireless headphones on a marble surface, studio lighting, minimalist aesthetic, product photography, soft shadows
```

**Landscape:**
```
misty mountain valley at sunrise, layers of mountains fading into fog, Japanese ink painting style, ethereal atmosphere
```

**Portrait:**
```
candid portrait of an elderly woman laughing, natural window light, Kodak Portra 400 film look, warm tones, intimate
```

### Essential Parameters

Add these to the end of your prompt:

| Parameter | What It Does | Example |
|-----------|-------------|---------|
| `--ar 16:9` | Set aspect ratio | Wide landscape |
| `--ar 9:16` | Portrait ratio | Phone wallpaper |
| `--ar 1:1` | Square (default) | Instagram post |
| `--v 6.1` | Model version | Latest version |
| `--s 250` | Stylize amount (0-1000) | Higher = more artistic |
| `--q 2` | Quality | Higher quality (uses more GPU) |
| `--no text, watermark` | Negative prompt | Exclude elements |

### Style Keywords That Work Well

- **Artistic styles**: oil painting, watercolor, pencil sketch, digital art, anime, Art Nouveau
- **Lighting**: golden hour, dramatic lighting, soft diffused light, neon, rim lighting
- **Mood**: ethereal, moody, vibrant, melancholic, dreamy, cinematic
- **Camera**: shot on Hasselblad, 35mm film, tilt-shift, macro, wide-angle
- **Artists**: in the style of Studio Ghibli, in the style of Wes Anderson

## Advanced Techniques

### Image Prompts (Using Reference Images)

You can include an image URL in your prompt to use it as a reference:
```
[image URL] a futuristic cityscape inspired by this color palette --ar 16:9
```

### Blend Multiple Images

Type `/blend` instead of `/imagine` to blend 2-5 images together.

### Use Style References

Add `--sref [URL]` to match the style of a reference image:
```
a cat sitting on a windowsill --sref [style-image-URL] --sw 1000
```

### Character Reference

Keep a consistent character across multiple images with `--cref [URL]`:
```
a young woman hiking in the mountains --cref [character-image-URL] --cw 100
```

## Common Mistakes to Avoid

1. **Too many words**: Keep prompts focused. 10-40 words works best.
2. **Conflicting styles**: Avoid mixing "photorealistic" with "anime style" in the same prompt.
3. **Expecting perfect text**: Midjourney still struggles with text in images.
4. **Not using parameters**: `--ar`, `--s`, and `--no` make a huge difference.
5. **Giving up too early**: Iterate with V buttons to refine results.

## Tips for Specific Use Cases

### Blog Post Headers
```
[topic] abstract representation, clean modern design, blog header style, --ar 21:9 --s 100
```

### Social Media Posts
```
[colorful/lifestyle image description], Instagram aesthetic, bright and engaging --ar 1:1
```

### Marketing Materials
```
[product description] in [setting], commercial photography, clean background, professional --ar 16:9
```

### App/Web Design Mockups
```
[description] UI/UX design mockup, clean modern interface, Figma style --ar 16:9
```

## FAQ

### Can I use Midjourney images commercially?
Yes, with any paid plan. You own the images you generate. Check Midjourney's Terms of Service for specific details on commercial usage rights.

### How many images can I generate per month?
The Basic plan gives you about 200 fast-generation images. Standard and Pro plans offer more fast generations plus unlimited "relax" mode (slower but unlimited).

### Why are my images not as good as others I see?
Prompting is a skill. Study what others are doing in the Midjourney community, use specific style keywords, and iterate with variations. It takes practice.

### Can I use Midjourney without Discord?
Midjourney has started rolling out a web interface at [midjourney.com](https://midjourney.com). Check if it is available for your account.

### What if I run out of fast hours?
On Standard and Pro plans, you can switch to Relax mode (`/relax`) for unlimited slower generation. On Basic, you need to wait for your hours to reset next month or upgrade.

## Bottom Line

Midjourney is the best AI image generator for quality. Start with the $10 Basic plan, learn to write good prompts, and iterate on your results. With practice, you will be creating professional-quality images in minutes.
