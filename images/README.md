# IDARA — Image Drop Folder

Put photos here and they appear on the site automatically.
**If a file is missing, nothing breaks** — the drawn artwork stays in its place.
So you can add them one at a time, in any order.

---

## File names (exact — lowercase, `.jpg`)

### Gallery — "Recent commissions"
| File | Currently shows | Best photo to use |
|------|-----------------|-------------------|
| `gallery-1.jpg` | The Royal Trunk | Your most impressive luxury hamper / trunk, styled dark |
| `gallery-2.jpg` | Ninety-Nine Roses | A large flower arrangement or bouquet |
| `gallery-3.jpg` | Executive Suite | A corporate / executive gift set |
| `gallery-4.jpg` | Heritage Silk | Something Nigerian & textural — adire, beads, bronze |
| `gallery-5.jpg` | Champagne & Gold | Champagne, celebration, anniversary styling |
| `gallery-6.jpg` | The House Seal | A close detail — ribbon, wax seal, packaging texture |

### Instagram strip — "Follow the House"
`instagram-1.jpg` … `instagram-6.jpg` — your six best square-ish posts.

---

## How to save images from Instagram

1. Open the post on Instagram **in a desktop browser**
2. Best quality: if IDARA has the **original photo files**, use those instead — Instagram compresses images
3. Otherwise: right-click the image → *Save image as…* → save into this folder with the name above

> Only use photos IDARA owns or has permission to use. If a photographer shot them,
> check your usage rights before publishing.

---

## Image specs (for the best-looking result)

- **Format:** JPG (or WebP if you have it — then change the filename ending in `index.html`)
- **Size:** roughly **1200–1600px** on the long edge
- **Weight:** keep each file **under 400KB** — compress free at [squoosh.app](https://squoosh.app)
- **Look:** dark, warm, moody. Wine / gold / champagne tones. Avoid bright white backgrounds —
  they fight the design. (Full photography direction is in the Design Bible, §09.)
- **Shape:** gallery images can be any shape (the layout adapts);
  Instagram tiles are cropped to a **square**, so keep the subject centred.

---

## After adding images

```
git -C C:\dev\test\idara-website add images
git -C C:\dev\test\idara-website commit -m "Add real photography"
git -C C:\dev\test\idara-website push
```

The live site updates about 30 seconds later.
