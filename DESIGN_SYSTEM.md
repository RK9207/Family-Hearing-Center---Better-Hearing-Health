# Design system

Family Hearing Practice · Better Hearing Health · Flower Mound, TX

## Visual direction

Use a warm editorial healthcare style with clear service information, generous type, authentic practice proof, and a distinct booking action. The first screen should show the practice identity, hearing evaluation service, Flower Mound, the benefit of reviewing results during the visit, the Google badge, and **Book Appointment**. Review the initial mobile viewport against the live ads once supplied. Follow the [page sequence](PAGE_STRATEGY.md) and [message hierarchy](CONTENT_DIRECTION.md).

## Color and type

| Role | Color | Usage |
|---|---|---|
| Brand blue | `#197FC4` | Brand accents, selected graphic details, and the supplied CTA color where label contrast qualifies. |
| Action blue | `#136DAD` | Solid primary buttons and mobile sticky phone control with white text and icons. White on this blue is about 5.5:1. |
| Dark blue | `#105887` | Hover and active fills. |
| Brand brown | `#4E3110` | Headings and editorial emphasis on light surfaces. |
| Body text | `#2D2925` | Body copy and high-readability labels. |
| Warm white | `#FFFDFC` | Main page surface. |
| Warm tint | `#F7F2EB` | Review section and other quiet moments that benefit from a section boundary. |
| Pale blue | `#EEF6FC` | Closing booking panel. |
| Border | `#DDD4C9` | Quiet dividers and noninteractive boundaries. Use a darker outline for fields and controls when needed for contrast. |

The medium blue is from the brief. The darker action blue is the approved accessibility adjustment. Brown on the brief’s blue is about 2.75:1, and white on that blue is about 4.31:1. Use the darker blue with white for regular-sized CTA labels. Pair links with visible underlines outside button treatments. Give all controls a visible keyboard focus indicator that stands out from the button and surface.

- Use **Outfit** for headings, typically at weight 600–700. Use a responsive H1 of about 36–56 px with 1.06–1.15 line height. H2s run about 28–40 px. Use 21–26 px for H3s and component titles.
- Use **Montserrat** for body copy, typically at weight 400–500 and 16–18 px with 1.55–1.7 line height. Keep critical trust details and form instructions at readable sizes. Use a system sans-serif fallback for each font.
- Set **controls** in Montserrat 600, typically at 16 px. Keep labels short and plainly worded.

## Layout and responsive behavior

- **Grid and width.** Center content within a 1,200 px maximum width. Use 24–40 px horizontal gutters on tablet and desktop and 20 px on mobile. Desktop uses a 12-column grid, tablet can use 8 columns, and mobile can use 4 columns or a single content column. Limit body text to roughly 65 characters per line. Give the FAQ and form a readable width of about 680–740 px.
- **Breakpoints.** Use under 640 px for the mobile layout, 640–1023 px for tablet, and 1024 px and above for desktop. At intermediate widths, stack the hero or simplify the header before the logo, navigation, and CTAs begin to crowd. Check both around the booking embed’s 600 px height breakpoint and on narrow viewports.
- **Spacing and surfaces.** Use an 8 px rhythm for layout, with 16–32 px between related blocks and about 44–64 px between major sections on mobile, rising to 64–96 px on desktop. Keep cards and image frames around 12–16 px radius and buttons around 8–10 px. Favor low-contrast dividers and restrained shadows.
- **Accessibility.** Use control targets around 44 px or larger, semantic headings, shareable anchored sections, and contrast suited to text and controls. Add anchor offset for the sticky header. Use descriptive alternative text for meaningful images and empty alt text for decorative images. Keep motion to brief focus, hover, or dialog transitions and respect reduced-motion preferences.

## Components

| Component | Design and behavior |
|---|---|
| Sticky header | Use the brief’s logo at left, linked to the practice website. Reserve enough space for the supplied stacked asset. On desktop, center a short set of anchors between the logo and the CTA group. Style the confirmed contact number as secondary and **Book Appointment** as primary. Mobile keeps the logo and booking CTA visible and omits the full desktop navigation. |
| Primary and secondary actions | Give **Book Appointment** the solid action color. Use outlined buttons or underlined links for supporting actions. Launch the same booking widget from each primary button. Use a phone icon on the sticky CTA and a location icon before **Get Directions**. Keep icons paired with visible text and hide decorative icons from assistive technology. |
| Hero Google badge | Use a compact, legible Google rating and count near the primary action. Maintain the clinic-specific details from the review source and use text alongside the stars. Keep the badge and CTA in the mobile content stack before the image. |
| Visit steps and support callouts | Use one compact three-step visit sequence. Make same-visit results easy to see. Give existing-device help a modest tinted callout. Use this treatment sparingly so the review section keeps its own visual identity. |
| Reviews | Show the numeric rating, count, selected quotes, and **Read all our Google reviews**. Prefer a static grid on desktop with up to six, and a vertical layout on mobile with up to three. Lead with the same priority reviews at each size. Let text wrap naturally and retain meaningful excerpts and attribution. |
| FAQ | Use a narrow accordion with real buttons and accessible expanded states, or native disclosure controls. Use dividers and a simple chevron. Keep the hit area generous and the answer text comfortably readable. |
| Booking widget | Use the supplied MyHearingPortal iframe in an accessible modal. Make the modal easy to dismiss with a labeled close control and Escape. Move focus into the open dialog and restore it to the trigger on close. Keep the close control visible while the embed scrolls, and prevent overflow or inaccessible nested scrolling on short screens. Verify the actual widget at desktop and mobile heights before launch. Provide a visible contact fallback after the clinic confirms the contact route. |
| Inline request form | Place the supplied OnspirePulse embed below a clear heading and a short explanation of follow-up. Give the embed a responsive container and useful iframe title. Verify resizing, focus, and submission behavior using approved test data. Keep the provided embed intact unless testing establishes a necessary correction. If the documented autoscroll issue reproduces, verify the compatible identifier change with the embed’s behavior. Load the embed script once. |
| Location and map | Show the street address and hours in text, then the supplied responsive map and **Get Directions**. Preserve the map destination in the supplied embed and give the iframe a useful title. Lazy-load the map and verify the destination is the Flower Mound office. |
| Mobile sticky phone action | Use the darker action blue and white label/icon. Set **Call or Text [confirmed number]** per the brief, with a phone link for the required tap-to-call behavior. Where texting is offered, provide an explicit SMS link using the verified number so visitors can choose it. Account for safe-area insets and reserve equivalent bottom space. Keep it out of the booking dialog’s way. |
| Footer | Include Privacy Policy, Visit Our Website, confirmed contact details, and the brief’s copyright. Verify the location-name placeholder resolves to Family Hearing Practice where the deployment platform supports it. |

## Imagery

- For the **hero**, prefer a genuine evaluation image if the clinic supplies one. A licensed editorial photograph can illustrate an evaluation while avoiding any suggestion that models are clinic staff or patients. A roughly 4:3 crop on desktop and a shorter landscape crop on mobile should preserve the visual point of the interaction, such as the audiologist explaining the test. Use natural expressions, warm light, and a realistic clinical setting.
- Give **hearing aid care** a single image if it illustrates fit, use, or adjustment. Keep the image secondary to the explanation and make sure any pictured equipment accurately represents what the copy discusses.
- Show the practice’s genuine **founder headshot** in a 4:5 or square crop. Keep the eyes and face clear at smaller sizes. Confirm publishing rights for the chosen assets.
- For the **location section**, use confirmed Flower Mound clinic or Google Business Profile photography if supplied and authorized, particularly if it helps identify the entrance. The map is sufficient while those images are pending.
- Reserve **illustrative AI imagery** for a generic lifestyle concept, such as conversation at home, if the concept adds something the available photography cannot. Review for visual and clinical plausibility. Use real assets for anyone presented as a provider or patient and for any depiction of the actual clinic. The research flagged the existing group image as likely AI-generated, so use the known authentic headshot for practice proof.

## Visual storytelling system

| Scroll moment | Image role and rhythm | What the visitor should take away |
|---|---|---|
| Hero | The first and largest image establishes the evaluation context. Keep the copy and booking action in a clean column. | I can book a hearing evaluation in Flower Mound and discuss the results during my visit. |
| Recognition and visit walkthrough | Set both sections mostly in type. Move from familiar listening experiences into a clear, compact process. Let the post-process CTA stand out. | This fits what I’m noticing, and I understand what the appointment involves. |
| Hearing aid support | Use a short editorial block and a callout for existing devices. Add a photo only if it explains the support. | I can ask about options or get help with aids I already own. |
| Founder and reviews | Move from a genuine portrait to a tinted, text-led review section. Let testimonials carry their own emphasis without additional stock photos. | I know who leads the practice and can read how patients describe their care. |
| FAQ and location | Make the FAQ the quietest reading section. Follow it with a larger map that adds practical context. | I can resolve common questions and see where I’m going. |
| Booking and request | Use a clear closing color band for booking, followed by a calm form surface. Leave the area free of imagery. | I can book now or ask the practice to follow up. |

On mobile, preserve the same order while shortening crops and using stacked layouts. Keep the strongest CTA moments at the first screen, after the process, and at the close. Check the page by scanning headings and visible controls alone. A visitor should be able to identify the service and city, understand the visit’s value, find local proof, and distinguish booking from requesting follow-up.
