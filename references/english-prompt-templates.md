# Your Prompt Toolbox — English Edition

These are the two prompt templates, rewritten for English words. They keep the structure and rigor of the Chinese templates, but the material is different: Latin letters carry no meaning inside their strokes, so the metaphor must be built from form, case, weight, spacing and what happens to the letters — and English spelling has no tolerance at all. One wrong letter is a failed poster.

## How to Use

1. Paste the full prompt into the dialogue, then generate one image first.
2. After that, just enter the target word — no need to re-paste the whole prompt.
3. To specify a ratio, enter "target word, 3:4".
4. If a problem appears, start a new conversation and continue there.

## About the Prohibitions in the Templates

Templates A and B contain many "do not" and "forbidden" statements. These are not limits on creativity — they are precise defenses against the known weaknesses of AI image models, in two kinds:

**Anti-inertia prohibitions** — e.g. "do not preset a fixed style", "do not grab the surface meaning", "do not mechanically repeat the template". AI models have strong default inertia; without constraints they produce results that are "safe but mediocre". These prohibitions break the default and push toward depth — they liberate creativity, they do not limit it.

**Quality-floor prohibitions** — e.g. Template A rule thirteen: "forbid text too small, not prominent, default font, misspelled words, garbled text, watermarks, cheap 3D". These are precise defenses against known failure modes of AI image generation, preventing the output from degenerating.

These prohibitions are for the canvas (the AI image model), not for the painter (you). You drive yourself toward excellence with inner motivation, and defend the canvas's known weaknesses with precise prohibitions. The two do not contradict.

---

## The AI Image-Model Caveat — Read First, Every Time

This applies to both templates and to every English poster you make. It is the single most important technical fact in this file.

- **Image models do not set type — they paint it.** A diffusion model has no font library, no spell-checker and no typesetting engine. A named typeface in a prompt is a **style hint, not a font selection**: the model will approximate high-contrast hairline serifs, not render actual Didot glyphs.
- **Prompt by qualities, not by name alone.** Always pair the typeface name with a description of the desired qualities: *"high-contrast Didone serif like Didot — razor-thin hairlines, extreme thick–thin contrast, vertical stress, elegant and fragile"* rather than just *"Didot font"*.
- **Prefer text-strong models and short text.** Keep the poster to **one word** — both an aesthetic rule and a technical necessity, since error rates compound with every additional letter and word.
- **Favor simple, bold letterforms in prompts.** ALL CAPS, Bold/Black weights and simple sans or slab faces render most reliably; formal scripts, blackletter and hairline Didones are the most likely to garble. If the concept *needs* a fragile Didone or a script, expect several regenerations.
- **Verify spelling after every generation, letter by letter.** Check the word, the case, and any supporting line before delivering. Common failures: doubled or missing letters, wrong letterforms (`C`/`G`, `M`/`W` confusion), extra stray letters, and plausible-but-wrong words. **Never deliver a poster without a spelling check.**
- **Best practice:** generate the *image/background* with the model if needed, but treat the type as a separate layer — the most reliable workflow is to composite real type (set in an actual font in Figma / Photoshop / Canva) onto the generated image, rather than asking the model to render the hero word.

---

## English-Specific Rules (Apply to Both Templates)

### 1. Spelling is absolute

Chinese allows no wrong character; English allows no wrong letter. **One wrong letter = failure.** The word must appear exactly, in the exact case specified, with no doubled, missing or extra letters. After every generation, check the spelling letter by letter before anything else. If the model garbles the word twice, simplify the letterforms (ALL CAPS, Bold weight, a plain sans or slab face) rather than lowering the standard — or composite real type onto the image.

### 2. Case is a design decision

- **ALL CAPS** is stone: monument, law, shout, eternity. Use it for words that must be carved, not spoken (DEATH, TRUTH, POWER, FOREVER). Track caps wide for monumentality; tight and they become a wall.
- **Lowercase** is a whisper: intimacy, confession, vulnerability, the everyday. Use it for tenderness, grief, smallness.
- **Sentence case / Capitalised** is the neutral human voice — use it only when neither monument nor whisper fits.
- Decide the case *before* generating, state it in the prompt, and never let the model choose. Mixed or accidental case is a spelling error in spirit.

### 3. The letterform itself is the metaphor

A Latin letter has no radical to decompose. The metaphor lives in what happens *to* the letters:

- **Shape:** the `O` as a ring, a void, an eye, a sun; the `S` as a flame, a river, a spine; the `A` as a peak; the `V` as open arms; the `I` as a lone pillar (and its dot as a small separate soul); `M`/`W` as mountains and waves; `X` as a cross, an error, the unknown.
- **Connection and breakage:** ligatures join letters where the word is about joining (LOVE); a broken ligature, a cracked stem, a displaced letter says separation, struggle, collapse.
- **Weight:** Light = fragile, ghostly, tentative, dawn. Black = power, weight, inevitability, night.
- **Spacing:** wide tracking = loneliness, distance, a voice across a void. Tight tracking = intimacy, pressure, a whisper.
- **Length:** a long word (LONELINESS, TRANSFORMATION) is a horizon — set it across the whole frame and let the eye travel. A short word (NO, GO, ONE, END) is a punch — set it enormous, alone, with silence around it.

### 4. Layout: English words are longer than Chinese words

A Chinese poster word is usually one or two characters; an English word is four to eleven letters. This changes the layout:

- **Tracking is a compositional tool, not a default.** Wide tracking on a long word eats the frame fast — use it deliberately (LONELINESS spread wide is the point; HAPPINESS spread wide is a waste of space).
- **Line-breaking is a decision, not an accident.** A long word may break across two lines — but only at a meaningful place (between syllables, or at a letter that carries the metaphor), never mid-syllable by the model's whim. Prefer one line when the frame allows; if it must break, state the break point in the prompt.
- **Word silhouette matters.** English words have a rhythm of ascenders (`b, d, f, h, k, l, t`) and descenders (`g, j, p, q, y`) — the skyline of the word is part of its image. A word with tall ascenders (HAPPINESS) can rise; a word with deep descenders (LONELINESS has none — its flatness *is* its emptiness; STRUGGLE's `g` can sink like a weight) can fall or root.
- **Scale down the ambition, not the word.** If a word is long, do not shrink it to fit decoration — shrink the decoration, or let the word run edge to edge, or crop it deliberately. The word stays the protagonist at any length.

---

## Template A: Author Version

Focused on deep typographic-design constraints; 14 rules covering everything from semantic understanding to finished image. Best for typographic experiments, brand visuals and art posters.

```
Generate a top-tier font-aesthetics concept image with "[TARGET WORD]" as its core. The first task of this image is not to make a pretty background, nor to make an ordinary art poster, but to make "[TARGET WORD]" the strongest, largest, most eye-catching and most memorable visual subject in the frame. "[TARGET WORD]" must be seen, read and felt at first glance. The text must carry overwhelming main-visual weight, occupy the most important position in the frame, and must not be weakened by background, people, objects, decoration, light or scenery. Every other visual element may only unfold around the text, serve the text, explain the text and strengthen the text — never steal the lead from it. The image should be generated around the meaning, emotion, symbolism, cultural association, psychological tension and deep metaphor of "[TARGET WORD]". First understand what this word really means, then decide the visual style, type structure, color, material, space, composition, aspect ratio and supporting elements that suit it. Do not preset a fixed style. Do not fix a vertical format. Do not fix a bright style. Do not fix a dark style. Do not make every word into the same design. Every word entered should generate a completely different visual character.

SPELLING IS ABSOLUTE. "[TARGET WORD]" must appear exactly as written here — every letter, in exactly this case, no doubled letters, no missing letters, no extra letters, no substituted letters. One wrong letter is a failed image. Check the spelling letter by letter before finishing.

I. The text must be absolutely prominent
The text is the absolute protagonist of the image. Ensure it is large enough, placed at the visual center or the strongest visual area, in clear contrast with the background, not obscured by many elements, not shrunk into decoration, not attached to the edge of the frame like a poster title.

Visual hierarchy:
- First level: the target word
- Second level: the core metaphor elements around the text
- Third level: background, atmosphere, texture, detail

II. Understand the word first, then generate the image
Judge the word's spiritual type, its core metaphor, the most suitable visual style (Oriental aesthetics / modernism / futurism / minimalism / surrealism / constructivism, etc.), the best aspect ratio, and the spatial relationship.

Key principle: do not grab the surface meaning — find the deeper metaphor.
- "FREEDOM" → boundaries disappearing, limits opened — not blue sky and birds
- "DESIRE" → gravity, approach, pull, a hollow — not red and flames
- "LONELINESS" → the absence of a reply, a scale imbalance — not one person alone
- "ANXIETY" → information too dense, breathing space compressed — not red warnings
- "TIME" → afterimages, overprinting, weathering, irreversibility — not clocks

III. The letterforms themselves must embody the metaphor
The type structure expresses the meaning: change stroke proportions, stretch / compress / break the letterforms, let strokes grow in a direction, use negative-space images, nest text and graphics, make the text a container. English spelling must be perfect.

For Latin letters, the metaphor lives in what happens to the letters: shared strokes and ligatures for connection; wide tracking for distance; fractured stems for struggle; elongated ascenders for rising; sinking descenders for weight and grief; the counter of the O as a void, an eye, a ring. A letterform device must be chosen deliberately — state it in the concept, and let it be visible.

IV. Build a metaphor system around the text
Elements may include: symbolic objects, abstract shapes, geometric structures, spatial structures, natural elements, mechanical systems, architectural elements, bodily metaphors, light-and-shadow relationships, material changes, symbol systems, etc.
Principle: more elements ≠ more accurate metaphor. One precise metaphor beats ten decorative elements.

V. Style must adapt to the meaning
Do not fix a style. Choose automatically from minimal plane design, constructivist posters, the Swiss grid, Japanese plane design, luxury-brand visuals, futurism, surrealism, abstract expressionism, Bauhaus design, and so on.

VI. Standards of high-end quality
High-end quality comes from accurate metaphor, strong visual hierarchy, a restrained number of elements, mature color relationships, refined type structure and deliberate negative space.
It does not come from piled-up elements, excessive glow, cheap metallic texture, tacky neon or random AI texture.

VII. Composition: the text is largest, the metaphor unfolds around the text
Use a composition dominated by enormous text (the text occupying more than 50% of the frame), a central monument composition, a minimal negative-space composition, an oppressive / releasing composition, a layered composition, a graphic-enclosure composition, a negative-space metaphor composition, etc.

VIII. Aspect ratio adapts to the meaning
- Condensation / totem / power / order → 1:1 square
- Rising / falling / sublime / oppressive → 4:5 or 3:4 vertical
- Flowing / expanding / freedom / connection → 16:9 or 3:2 horizontal
- Epic / civilisation / universe → 21:9 ultra-wide
- Extreme rising / abyss / faith → 9:16 ultra-vertical
- Speed / road / information flow → 3:1 or 4:1 banner

IX. Color and light
Choose color according to the meaning: high-contrast black and white, red and black, cold blue and silver gray, ivory and gold, deep green and copper, purple-black and silver white, etc. Light and shadow must also serve the metaphor.

X. Material and graphic language
Choose from paper, ink, metal, stone, glass, silk, liquid, smoke, digital grid, relief, cracks, mirror reflection, etc. Material must serve the meaning.

XI. Interaction between text and elements
Elements may grow from the strokes, the text may be cut open, become part of a building, be limited or broken through by a frame, hide an image inside, cast a symbolic shadow, become an entrance / container / window, etc.

XII. Standards of finished quality
The text is most prominent, accurate and readable; the typeface itself embodies the meaning; the metaphor is clear; the style matches; the aspect ratio matches; the composition has impact; the colors are high-end; from far away it is poster-grade; up close it has detail.

XIII. Forbidden content
Forbid text too small, not prominent, default fonts, misspelled or garbled text, watermarks or signatures, random piled-up symbols, one style for every word, cheap 3D, tacky neon, PPT-cover feel, Canva-template feel, advertising-flyer style, children's illustration style, low resolution.

XIV. Final execution instruction
Generate an image with "[TARGET WORD]" as its absolute core. Understand first, then choose style / aspect ratio / composition / color / material. Let the text become part of the metaphor. First glance sees the text, second glance understands the metaphor, third glance feels the high-end aesthetic.

IMPORTANT — HOW TO PROMPT THE TYPEFACE: image models do not set type, they paint it. A named typeface is only a style hint. Always describe the qualities as well: for example, "high-contrast Didone serif like Didot — razor-thin hairlines, extreme thick–thin contrast, vertical stress, elegant and fragile" rather than just "Didot font". Prefer ALL CAPS, Bold or Black weights and simple letterforms for reliable rendering; fragile Didones, formal scripts and blackletter will garble most often — if the concept needs them, expect several regenerations. Verify the spelling letter by letter after every generation.
```

---

## Template B: Xiaoxiaodong Version

Focused on the minimal expression of the graphic-art poster, emphasising collage feel, print texture and visual double meaning. Best for social-media sharing, concept posters and exhibition visuals.

```
What you are generating is not an ordinary illustration, and not a simple word-effect poster made by enlarging a word and pasting it on a picture. It is a high-end concept poster that "automatically builds a visual metaphor from the meaning of the word". Your core task: the user will give you a word, a phrase, or a set of letters. First truly understand the surface meaning, emotional character, implied symbolism, cultural association, psychological feeling and semantic tension of this text, then translate that understanding into a minimal, strongly conceptual, highly shareable, highly memorable graphic-art poster.

SPELLING IS ABSOLUTE. The target word must appear exactly as given — every letter, in exactly the specified case, no doubled, missing, extra or substituted letters. One wrong letter is a failed image. Check the spelling letter by letter before finishing.

I. Understand the word first, then generate the image
Analyse the word's core meaning, emotional tendency (gentle / cold / dangerous / lonely / romantic / oppressive, etc.), wordplay / paradox / metaphor, and the most suitable visual logic (relationship between people / relationship between objects / spatial relationship / contrast relationship / conflict relationship, etc.). Abstract words need a concrete visual carrier; concrete words become more thoughtful through composition / scale / contrast.

II. Composition
- Large type as the core skeleton of the image: large size, strong recognisability and pressure
- Image elements relate to the text: standing before the letters, embedded inside them, cutting through the letterforms, telling a story in the space the letters lend
- Very few elements — fewer and more accurate is better
- The text is the first visual layer, the image narrative is the second visual layer, small explanatory text is the third visual layer
- Negative space should be intelligent; the composition should feel like a poster

III. Image expression
- Prefer a single strong image that condenses the meaning of the word
- Express it through relationships between people, scale contrast, directional relationships, distance relationships, occlusion relationships, moments of action
- Metaphorical but not obscure
- Aim for the feeling of "a knowing blow the moment you see it"
- Words of conflict: strengthen the tension with opposing elements
- Words of poetry: use a more restrained, understated strategy

IV. Visual style
High-end graphic-art poster: collage feel, screen-print feel, lithograph feel or woodcut-style texture — clear, restrained and hard-edged. A clean, unified color logic: a high-saturation main background with large areas of light-coloured text. Fine grain, paper texture, print noise — overall fresh, clean and high-end.

V. Typography
The user's input text is the core headline, large and eye-catching. Keep English in its original form so the letterforms stay strong. A short supporting line may be added in a restrained position to deepen the theme. All text should look as if it grew out of the image.

For English words, decide the case before generating (ALL CAPS for monument and authority; lowercase for intimacy and vulnerability) and state it in the prompt. Mind the word's length: a long word needs its tracking and line-breaking decided in advance — wide tracking on a long word eats the frame, so use it only when the distance itself is the metaphor. Let the word's silhouette — its rhythm of ascenders and descenders — be part of the image.

VI. Goal of the finished image
Minimal, strong, complete, high-end. The emotion and depth of the word are felt quickly. Image and word are strongly connected, clever, accurate and worth looking at again. The rational control of plane design + the emotional force of artistic expression. Shareable, poster-like, collectible, exhibition-like.

VII. Execution principles
Do not mechanically repeat the template; change intelligently with the input. Stay minimal, conceptual, strongly typographic, strongly recognisable. Reasonable composition, restrained image, clever expression. Every visual element must serve the expression of the word.

User input: core word / phrase / letters: [fill in here]
Word language: English
Case: [ALL CAPS / lowercase / capitalised — choose one and state it]
Letterform device: [e.g. ligature / wide tracking / fractured stems / stretched ascenders / the O as a ring — choose one]
Optional context: [fill in here]
Optional emotional tendency: [fill in here]
Forbidden elements: [fill in here]

IMPORTANT — HOW TO PROMPT THE TYPEFACE: image models do not set type, they paint it. A named typeface is only a style hint. Always describe the qualities as well as the name — "high-contrast Didone serif like Didot, razor-thin hairlines, extreme thick–thin contrast" rather than just "Didot font". Simple, bold letterforms render most reliably; formal scripts, blackletter and hairline Didones garble most often. Verify the spelling letter by letter after every generation.
```

---

## Choosing Between the Two Templates

| Scenario | Recommended template |
|----------|---------------------|
| Typographic experiment, brand visual, art poster | Template A (author version) |
| Social-media sharing, concept poster, exhibition visual | Template B (Xiaoxiaodong version) |
| Needs adaptive aspect ratio and rich material choices | Template A |
| Needs minimal composition and print texture | Template B |
| Extremely high demands on typographic design | Template A |
| Aiming for the "knowing blow" of a visual double meaning | Template B |

---

## Adapting to Different Models

You are an artist working across models. You do not write different "rules" for different models, but you naturally adjust your brushwork to the canvas.

### Models strong at text (GPT-Image / DALL-E 3 class)

Use Template A or B freely. The word length is not limited; letterform design can be bold and complex. This is your most comfortable state of creation.

### Models middling at text (Seedream / domestic models class)

Still prefer Template A or B, but naturally:

- Let the target word appear multiple times in the prompt, to help the model anchor the correct content
- Prefer keeping the word short (English words under 8 letters render best; long words like LONELINESS need extra care — state the spelling explicitly, letter by letter if needed)
- Split a long phrase into multiple images, keeping a unified visual style
- State explicitly in the prompt what text should appear in the image

Your standard for text accuracy does not drop — you simply organize the prompt more carefully to help the model reach it.

### Models weak at text (Midjourney / Stable Diffusion class)

Focus on rendering 1–4 core letters, and break a long word into a series. Always try first to let the AI generate artistic text directly. If the model still cannot render the word accurately after several attempts, find a creative alternative — you are an expert, and your toolbox holds more than one tool. The most reliable fallback: generate the image/background with the model, and composite real type (set in an actual font in Figma / Photoshop / Canva) onto it. **Never deliver a poster with a misspelled word.**
