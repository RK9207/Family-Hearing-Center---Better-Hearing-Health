# IMAGE_PROMPTS.md

**Client:** Family Hearing Practice, Flower Mound, TX
**Landing page:** Better Hearing Health
**Step:** 4B, image prompts for the placeholders in `index.html` (Step 4A draft)
**Prepared:** November 27, 2026

This file covers only the four intentional placeholders in the draft. The Signs, Evaluation, Reviews, FAQ, booking panel and request form sections have no placeholders by design, so they have no prompts here.

> **Keep this file in sync.** If Step 5 changes a section's layout, crop or visual purpose, update that section's entry here, including the composition notes, prompts and recommendation. Don't leave it stale.

---

## Summary

| Placeholder | Section | Source type | Recommended option | AI use |
|---|---|---|---|---|
| IMG-HERO-01 | Hero | AI-generated lifestyle/editorial image appropriate (a real evaluation photo is preferred if the clinic supplies one) | Option 1: Results conversation | ✅ Allowed, never presented as clinic staff or patients |
| IMG-HEARINGAID-01 | Hearing aid care | AI-generated lifestyle/editorial image appropriate | Option 1: Fitting close-up | ✅ Allowed, the device must be accurate |
| IMG-PROVIDER-01 | Owner-led practice | Real provider/team image preferred | Option 1: Refresh the existing headshot | ❌ No AI person. AI only as a neutral background plate |
| IMG-CLINIC-01 | Location (optional) | Real clinic/GBP image preferred | Option 1: Entrance approach | ❌ No AI. Remove the placeholder if no real photo exists |

---

## Shared visual direction (applies to every prompt)

These rules come from DESIGN_SYSTEM.md and CONTENT_DIRECTION.md.

- **Style:** Warm, editorial healthcare photography. It should look natural and documentary-like, with nothing polished to the point of stock. People look engaged and at ease, with realistic, unexaggerated expressions.
- **Setting:** A calm private consultation room, not a hospital. Warm wood, soft neutral walls, a plant or framed abstract art, a tidy desk. Equipment is minimal and plausible.
- **Light:** Soft natural window light, usually from the side, with gentle shadows and warm white balance (about 4500–5000K).
- **Color mood:** Warm neutrals (cream, oatmeal, walnut) with muted blue accents that echo the brand blue #197FC4, for example a blue knit sweater or a blue-grey chair. Warm brown tones can sit in the background. Avoid saturated teal and stark white.
- **Camera feel:** Full-frame look with a 35–50 mm lens, about f/2.8. Shallow, natural depth of field and a slight film-like tonal softness.
- **People:** Patients are usually in their late 50s to 70s, the page's core audience. Caregivers are adult children in their 40s–50s. Audiologists are in their 30s–40s and wear business-casual clothing with no scrubs, white coat, name badge or lanyard text. Audiologists are shown as generic professionals and must never imply a specific Family Hearing Practice staff member.
- **Wardrobe:** Solid colors or subtle textures, with no logos or printed text.

**Global negative prompt (append to every AI prompt):**
`no text, no logos, no brand names, no watermarks, no readable screens, no name badges, no white lab coat, no scrubs, no stethoscope, no hospital bed, no sterile blue-white lighting, no exaggerated smiles, no thumbs up, no looking at camera, no distorted hands, no extra fingers, no warped ears, no malformed hearing aids, no duplicated devices, no plastic skin, no oversaturated colors, no fisheye distortion`

**Review checklist for every AI output:**
- Hands and fingers are correct.
- Ears are anatomically correct.
- Any hearing aid sits behind the ear, with a thin wire or tube running over the top of the ear into the canal and a small dome inside it. There are no floating parts.
- Screens are blank or show only abstract shapes.
- No one resembles the real clinicians, especially Dr. Allison Liberio.

---

## IMG-HERO-01 - Hero

### Placeholder purpose
This is the first and largest image on the page. It has to make the service concrete right away: a local audiologist evaluating someone's hearing and explaining the results during the same visit. It supports the H1 ("Hearing evaluations in Flower Mound, with results explained during your visit") and the page's core promise of leaving with clarity and a next step. The visitor should think, "This is a calm, respectful appointment where someone explains things to me," not "This is a sales pitch" or "This is a hospital."

### Recommended source type
**AI-generated lifestyle/editorial image appropriate.** A genuine evaluation photo from the clinic would be better if one is supplied. An AI or licensed editorial image must not suggest that the models are Family Hearing Practice staff or patients. Avoid captions, alt text and nearby copy that imply this.

### Recommended composition
- **Orientation:** Landscape. Generate at 4:3 (about 2400 × 1800 px) for desktop. Mobile uses a centered 3:2 crop of the same image, so keep the key action inside the central 3:2 band.
- **Subject placement:** Two people interacting in the middle third. The patient's face and the audiologist's explaining gesture should both be readable in the 3:2 crop.
- **Negative space:** No headline sits on top of the image because the hero copy is in its own column. Leave a little breathing room at the top and bottom edges for the 3:2 crop. Avoid clutter on the edges.
- **Crop considerations:** Don't place important details, such as hands or a shared screen, at the very top or bottom of the 4:3 frame. Faces sit roughly on the upper-third line.
- **Desktop/mobile:** On desktop the image sits to the right of the copy, at about 560 px wide. On mobile it appears after the CTA and the Google badge. It must still read clearly at about 350 px wide, so favor two clear figures over a busy room.

### Option 1 - Results conversation
Warm editorial healthcare photograph, 4:3 landscape. A calm, private audiology consultation room with soft natural side light from a large window on the left, cream walls, a warm walnut desk, a small potted plant and blurred abstract art in the background. A woman audiologist in her late 30s, wearing a soft blue knit sweater over a collared blouse, sits beside the patient rather than across from him. She angles a tablet toward him and points gently at a simple abstract line chart on the screen, with no readable text or numbers. The patient is a man in his mid-60s in a casual oatmeal quarter-zip sweater. He leans slightly forward, attentive and thoughtful, with a faint relieved half-smile, as if something has just been made clear. Both are seated at a corner of the desk, their bodies turned toward each other. The interaction is relaxed and unposed, captured mid-sentence. 50 mm lens look at f/2.8, focus on the patient's face with the audiologist slightly soft. Shallow natural depth of field, warm white balance, muted blue and warm neutral palette. Realistic skin texture and believable documentary-style editorial photography, suitable for professional healthcare advertising. Keep both faces and the tablet inside the central 3:2 band. No one looks at the camera. [Append global negative prompt.]

### Option 2 - Bringing a parent
Warm, natural editorial photograph, 4:3 landscape. A quiet audiology consultation room with soft window light, warm wood furniture, cream walls and a muted blue armchair. A woman in her late 70s with short silver hair, wearing a soft cardigan, sits facing an audiologist, a man in his early 40s in a blue-grey button-down shirt with no tie. He leans in slightly and speaks directly to her with an open hand gesture, explaining patiently. Beside her sits her adult daughter in her late 40s, listening supportively with one hand resting lightly on her mother's forearm. The daughter is present but secondary: the audiologist's attention is clearly on the older woman. The mood is respectful, unhurried and reassuring. The older woman's expression is engaged and dignified, not confused or sad. 35 mm lens look at f/2.8, focus on the older woman and the audiologist, with the daughter slightly soft. Natural depth of field and warm, gentle color grading. Candid editorial healthcare style with realistic textures. Keep all three faces in the central 3:2 band. No one looks at the camera. [Append global negative prompt.]

### Option 3 - Evaluation in progress
Calm, realistic editorial healthcare photograph, 4:3 landscape. A softly lit audiology testing area that feels warm rather than clinical, with a neutral wall, warm wood desk and gentle daylight. A woman in her early 60s sits comfortably in a padded chair, wearing lightweight over-ear audiometric headphones with no logos and holding a small handheld response button. Her expression is relaxed and focused, eyes slightly downcast as she listens. In the soft-focus foreground, an audiologist in her mid-30s in a blue knit top sits at a laptop with a blank, unreadable screen, turned three-quarters away from the camera. The image shows that the test is simple, comfortable and painless. 50 mm lens look at f/2.0, focus on the patient's face and headphones, with the foreground audiologist blurred. Warm neutral and muted blue palette, natural skin texture, documentary realism. Minimal equipment: no sound booth walls, cables or medical clutter. Keep the patient's face and headphones within the central 3:2 band. No one looks at the camera. [Append global negative prompt.]

### Recommended option
**Option 1 - Results conversation.** It most directly shows the hero's differentiator, results explained during the visit, and matches the primary searcher, an adult checking their own hearing. Its two-person composition survives the 3:2 mobile crop well. Option 2 is a strong alternative if live ads or Step 5 lean toward the caregiver audience. It echoes the Krohn Family review about instructions directed to the patient. Option 3 is good for the "painless" message but shows the test rather than the result, which is less tied to the H1.

### Real-image note
A real photo from the Flower Mound office of an audiologist reviewing results with a consenting patient would outperform AI here, because it adds local authenticity. AI is acceptable for the first draft and for launch if no real photo is supplied. If AI is used, avoid nearby copy such as "our audiologist" that ties the people in the image to the practice.

---

## IMG-HEARINGAID-01 - Hearing aid care

### Placeholder purpose
The image has to show that hearing aid care is hands-on, personal and ongoing: fitting, fine-tuning and help using the devices. Per DESIGN_SYSTEM.md, the image is secondary to the explanation and should only be used if it illustrates fit, use or adjustment. Any pictured device must accurately match what the copy discusses, which is behind-the-ear and receiver-in-canal styles. It also supports the existing-wearer callout, the idea that you can get help with the devices you have.

### Recommended source type
**AI-generated lifestyle/editorial image appropriate.** A real fitting photo from the clinic would also work. Avoid manufacturer marketing images, which have visible branding and need rights checks.

### Recommended composition
- **Orientation:** Generate at 4:5 portrait (about 1600 × 2000 px) for desktop, where the image stays in view as the visitor scrolls the left column. Mobile uses a centered 3:2 landscape crop, so the key action (the hands, the ear and the device) must sit in the vertical center of the frame.
- **Subject placement:** The patient's ear and the audiologist's hands are in the center. The patient's face is visible in profile or three-quarter view.
- **Negative space:** None is needed for text. Keep the top and bottom quarters simple, such as soft background or shoulders, because the mobile crop removes them.
- **Crop considerations:** The device must be large enough to read at mobile size, so it should not be a tiny speck. Avoid a crop so tight that it looks like a clinical procedure.
- **Desktop/mobile:** On desktop the image is about 430 px wide, shown portrait. On mobile it's about 350 px wide in landscape and appears before the section copy.

### Option 1 - Fitting close-up
Warm editorial healthcare photograph, 4:5 portrait. A medium close-up in a calm audiology consultation room with soft daylight from the right and a blurred cream-and-walnut background. A man in his late 60s with short grey hair, in a soft navy crewneck sweater, sits in three-quarter profile facing slightly left with a relaxed, patient expression. An audiologist's hands, a woman in her 30s in a muted blue sleeve, carefully seat a small, discreet, skin-toned receiver-in-canal hearing aid behind his right ear. The thin clear wire runs over the top of his ear, and the small dome enters the ear canal. The device is anatomically correct, single, with no logo. Her face is partly visible at the frame edge and soft. Composition centers on the ear, device and hands in the middle of the frame. The top of the frame shows soft background and the top of his head; the bottom shows his sweater shoulder. 85 mm lens look at f/2.8, focus on the device and ear with a soft falloff. Natural skin texture, warm neutral palette with muted blue accents, realistic and gentle. Professional healthcare advertising, not stock. [Append global negative prompt.]

### Option 2 - Setting up the phone app
Warm, candid editorial photograph, 4:5 portrait. A woman in her early 70s with shoulder-length silver hair, in a warm rust cardigan, sits at a wooden consultation table beside an audiologist, a man in his late 30s in a light blue oxford shirt. Both look down at her smartphone, which she holds while he points to the screen. The screen is blank or shows simple abstract shapes, with nothing readable. A discreet receiver-in-canal hearing aid is visible behind her near ear, the thin wire running over the top of the ear. Her expression is engaged and pleased, as if it just clicked, with no exaggerated grin. Soft natural window light, a cream wall and a potted plant blurred in the background. Both figures sit in the vertical center of the frame, with simple background above and the table edge below. 50 mm lens look at f/2.8, focus on her face and hands, with the audiologist slightly soft. Warm color grading, realistic textures, documentary-style healthcare editorial. [Append global negative prompt.]

### Option 3 - Back in the conversation (outcome)
Natural, warm lifestyle photograph, 4:5 portrait. A home dining table in the early evening, with warm lamp light mixed with soft window light and plates and water glasses softly blurred. A man in his mid-60s in a casual chambray shirt leans in toward someone just out of frame, attentive, listening and laughing quietly mid-conversation. A small, discreet receiver-in-canal hearing aid is visible behind his near ear, correctly worn with a thin wire over the top of the ear. A blurred adult family member's shoulder and hand gesture appear in the foreground edge. His face and ear are in the vertical center of the frame. The image conveys an everyday conversation across a dinner table, which is the outcome hearing aid care supports. 50 mm lens look at f/2.0 with shallow depth of field. Warm amber and muted blue palette, realistic, understated and unposed. No exaggerated happiness. [Append global negative prompt.]

### Recommended option
**Option 1 - Fitting close-up.** DESIGN_SYSTEM.md asks for an image that illustrates fit, use or adjustment, and this is the clearest depiction of personalized fitting and fine-tuning. Its centered composition also survives the 3:2 mobile crop. **Option 2** is an equally valid alternative. It mirrors the James Kluth review (app setup after a phone change) and the "education and ongoing support" step. Option 3 is the most emotional but shows an outcome rather than the care, so it fits this section less well. Hold it in reserve if Step 5 adds a lifestyle moment elsewhere.

### Real-image note
Either real or AI works here. If the clinic can supply a genuine fitting photo, use it. In any AI output, check the device carefully. AI often draws hearing aids as earbuds or floating shapes, which would contradict the copy and look fake to existing wearers.

---

## IMG-PROVIDER-01 - Owner-led practice

### Placeholder purpose
The image has to give the practice a human face and back up the founder profile of Dr. Allison Liberio: owner, five years in a DFW ENT practice, and audiology teaching at UNT. Visitors should see the real person who leads the practice. This is trust proof, so authenticity matters more than polish.

### Recommended source type
**Real provider/team image preferred.**

**REAL CLINIC / GBP IMAGE PREFERRED.** A named provider must never be represented by an AI-generated person. That would be misleading, and it undermines the trust this section exists to build. A genuine headshot is already on the client site (`New-headshot.jpg`, per RESEARCH.md §9). Confirm publishing rights before use. The research also flagged the site's group photo as likely AI-generated, so do not use it.

### Recommended composition
- **Orientation:** 4:5 portrait on desktop (about 1200 × 1500 px minimum). Mobile uses a centered 1:1 square crop.
- **Subject placement:** Head and shoulders, with the eyes on the upper-third line and the face horizontally centered so the square crop keeps the full face and shoulders.
- **Negative space:** A modest, even margin above the head. Nothing needs to overlay the image.
- **Crop considerations:** Don't crop the top of the head on mobile. Keep the eyes sharp and the face clearly lit at about 300 px display size.
- **Desktop/mobile:** On desktop the image is about 380–440 px wide beside the bio. On mobile it's a square of up to 360 px above the bio.

> The three options below are **real-photo directions** (Options 1–2) and an **AI background plate only** (Option 3). None of them generates a person.

### Option 1 - Refresh the existing headshot (editing brief)
Use the client's existing real headshot of Dr. Allison Liberio (`New-headshot.jpg`). Re-crop it to 4:5 portrait with her face centered horizontally and her eyes on the upper-third line. Leave about 10–12% headroom above her hair and include her shoulders to mid-chest. Check that a centered 1:1 square crop keeps her full head and shoulders. Make light, natural corrections only: balance exposure, set a warm white balance (no cooler than 5000K) and add slight clarity to the eyes. Use no skin smoothing or reshaping, and don't alter her features, hair or clothing. If the original background is distracting or cool-toned, adjust it slightly toward a warm neutral cream or soft grey, or use Option 3's background plate. Export at a minimum of 1200 × 1500 px in sRGB, saved as WebP or JPG at about 80% quality.

### Option 2 - Environmental portrait shoot (photographer brief)
A real photo session with Dr. Allison Liberio at the Flower Mound office. Vertical 4:5 portrait in a consultation room with soft natural window light from one side, plus a gentle fill. Waist-up or chest-up, seated or standing at a slight angle to the camera with her shoulders turned about 20 degrees. She makes warm, direct eye contact with a natural, relaxed, closed or slight smile, like a professional welcoming a patient. Use a softly blurred background of the real room (warm wood, plants, a hint of equipment), but nothing branded or cluttered. Wardrobe is solid business-casual in a mid-tone, ideally a muted blue or warm neutral that harmonizes with brand blue #197FC4 and brown #4E3110, with no busy patterns and no white coat unless that is her normal practice attire. 85 mm lens at f/2.2–2.8 with her eyes in sharp focus. Keep the face horizontally centered so a square mobile crop works. Also capture a horizontal variant and a few candid shots of her explaining results to a consenting patient, for possible use in IMG-HERO-01 or IMG-HEARINGAID-01. Get written consent for any patient who appears.

### Option 3 - AI background plate for the real headshot
**Use only as a backdrop behind a cut-out of the real headshot. Never generate a person.** Prompt: Soft, out-of-focus background plate for a professional portrait, 4:5 portrait, 2400 × 3000 px. A warm, calm private audiology office, heavily blurred as if shot at f/1.8: cream wall, a hint of warm walnut shelving on one side, a soft green plant shape on the other, and gentle natural window light falling from the left. The colors are warm neutrals with a subtle muted-blue tone in one blurred object. The center of the frame is empty and evenly lit for a person to be composited in later. No people, no faces, no text, no logos, no equipment details and no recognizable objects. Smooth bokeh, no hard edges, photographic realism. Before compositing, match the plate's light direction and color temperature to the real headshot. Disclose internally that the background is synthetic.

### Recommended option
**Option 1 - Refresh the existing headshot.** It's the fastest path to a genuine, rights-checkable image and keeps the section truthful. Commission **Option 2** if the existing headshot is low-resolution, dated or tightly cropped. That shoot can also supply real images for the hero and hearing aid placeholders. Use **Option 3** only to rescue a usable real headshot that has a poor background.

### Real-image note
**REAL CLINIC / GBP IMAGE PREFERRED.** This section is about proving who leads the practice. Only a real photo of Dr. Liberio can do that, and an AI likeness would be deceptive.

---

## IMG-CLINIC-01 - Location (optional)

### Placeholder purpose
The image should help visitors recognize the Flower Mound office when they arrive, confirming they're booking the right place and reducing first-visit anxiety. PAGE_STRATEGY.md marks it as optional: the map and "Get Directions" are enough on their own. It only earns its place if it is genuinely the office at 4491 Long Prairie Rd #400.

### Recommended source type
**Real clinic/GBP image preferred.**

**REAL CLINIC / GBP IMAGE PREFERRED.** An AI-generated building would show visitors the wrong entrance, which is worse than no image. If no authorized real photo is available, **remove this placeholder** and let the map carry the section. Do not substitute AI or stock.

### Recommended composition
- **Orientation:** 3:2 landscape (about 1500 × 1000 px minimum) on all screen sizes.
- **Subject placement:** The entrance or door with its suite signage in the middle third, so the visitor recognizes where to walk in.
- **Negative space:** None is needed for text. Include enough surroundings (walkway, parking edge) to give context.
- **Crop considerations:** Keep any signage legible at about 380 px display width. Avoid identifiable people and readable license plates.
- **Desktop/mobile:** The image sits inside the location info card, about 380–420 px wide on desktop and full width on mobile. Use one image only.

> For real photography, the "no visible text" rule doesn't apply to the building's own signage. The suite number and practice sign are the point of this image.

### Option 1 - Entrance approach (photographer brief)
A real photograph of the Family Hearing Practice entrance at 4491 Long Prairie Rd #400, Flower Mound, TX, taken from where a first-time patient would approach on foot from the parking area. 3:2 landscape at eye level (about 1.6 m), with a 28–35 mm lens equivalent and the verticals kept straight. Frame the entry door and any Family Hearing Practice or suite #400 signage in the middle third, with a slice of walkway in the foreground and some building facade for context. Shoot on a clear day in soft morning or late-afternoon light, avoiding harsh midday shadows. Keep the frame free of people, or have no one identifiable. No readable vehicle plates. Natural color with a slight warm grade, and no heavy HDR.

### Option 2 - Door and suite signage detail (photographer brief)
A real, closer photograph of the office door with the practice name or suite #400 signage clearly legible. 3:2 landscape, straight-on or at a slight angle, with the signage sharp and centered. Include a little of the surrounding wall or door frame so it reads as an entrance rather than a sign close-up. Use even, soft daylight or the building's own entry lighting, and avoid glare on glass by angling slightly or using a polarizer. This works best if the building has several suites and visitors need to find #400 specifically. Natural, true-to-life color.

### Option 3 - Use an existing Google Business Profile photo (selection and crop brief)
Review the Flower Mound Google Business Profile photos and pick an owner-uploaded photo that clearly shows the building exterior or entrance. Confirm the clinic owns it and authorizes reuse; customer-uploaded photos need permission. Crop to 3:2 landscape with the entrance in the middle third, straighten the verticals, lightly correct exposure and white balance, and don't alter any building details. Discard images that are low-resolution (under about 1200 px wide), heavily filtered or out of date, for example showing old signage. If no suitable GBP photo exists, use Option 1 or remove the placeholder.

### Recommended option
**Option 1 - Entrance approach.** It best answers the section's question, "How do I find the door?", and shows context a map pin can't. Use **Option 3** as the quickest stopgap if an owner-uploaded GBP exterior already exists. Choose **Option 2** if the building has multiple suites and the entrance alone is ambiguous.

### Real-image note
**REAL CLINIC / GBP IMAGE PREFERRED.** Only a real photo serves this placeholder's wayfinding purpose. With no authorized real image, delete the `IMG-CLINIC-01` figure from `index.html`. The info card and map are already complete without it.

---

## Open items for the client and Step 5

1. Ask the clinic for real photos: Dr. Liberio's headshot at high resolution with rights confirmed, the Flower Mound exterior or entrance, and ideally a consented results-review or fitting photo. Real photos would replace AI in the hero and hearing aid sections.
2. If AI images are used in the hero or hearing aid sections, make sure the alt text and nearby copy don't present the people as Family Hearing Practice staff or patients.
3. Decide in Step 5 whether IMG-CLINIC-01 stays or is removed, based on photo availability.
4. Update this file if Step 5 changes any section's crop, layout or visual purpose.
