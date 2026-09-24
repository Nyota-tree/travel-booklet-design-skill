---
name: travel-booklet-design
description: Create or revise traveler-facing itinerary booklets for domestic or international trips, including complete daily routes, practical maps, venue photos, tickets, and on-site guidance. Use for a travel guide or booklet artifact, not a quick travel recommendation.
---

# Travel booklet design

Make a guide that a traveler can follow without guessing the next stop. Adapt the format, tools, level of detail, and production process to the request and the agent's capabilities; the design rules below describe the intended result, not a mandatory software workflow. An agent without native skill support can read this file and the linked Markdown references as ordinary instructions.

## Select context

- For a trip within the traveler's home country, read [domestic trips](references/domestic.md).
- For a trip crossing an international border, read [international trips](references/international.md).
- For a mixed trip, use both where relevant. For a designed or printable artifact, also read [layout and quality](references/layout-and-quality.md). A plain-text guide may use the same content principles without adopting a page layout.

## Core decisions

1. Treat user-confirmed bookings, route choices, exclusions, times, and supplied documents as the itinerary's source of truth. Distinguish booked, planned, optional, and unverified items. Resolve conflicts or mark them for the traveler; do not silently replace confirmed decisions.
2. Show each day's complete ordered destination chain. Every stop needs a recognizable name, useful location, and an explicit **NEXT →** transition to the next stop with a transport mode and practical distance or duration when supportable. End the chain at the actual final stop, return, or overnight location. A small route overview may orient the reader but cannot replace the stop details or be duplicated on the next page.
3. Make on-site recognition easy: prominent name in the language used on local signs, a smaller explanation in the traveler's language, address/entrance, timing, and relevant "eat / buy / do" notes. Use the traveler's preferred language, not a fixed bilingual formula.
4. Match information density to the day. A transport or hiking day may need fewer photos and more boarding, positioning, supplies, rental, weather, exit, turnaround, and fallback instructions. Do not fill empty space with decorative cards or editorial prompts.
5. Use accurate visual evidence. A business-identification photo should show the **specific branch's** real facade, entrance, or sign and sit beside its stop. Never pass off another branch, an event/interior image, or an AI-generated storefront as its entrance. If no trustworthy photo exists, keep the address and a clear locating cue; mark the photo as unverified rather than fabricating one. Landscape or atmosphere art can be generated when appropriate, clearly distinct from documentary images.
6. Maps should have a genuine geographic base or be explicitly labeled a schematic. Keep the map focused enough to read, number stops consistently with the itinerary, give a legend, and distinguish visit order from a navigable path. Do not shrink a neighborhood map to include a faraway transfer point.
7. Preserve operational documents. When including a ticket or voucher, crop the **original image** to retain the QR/barcode quiet zone plus passenger, date, origin/destination, booking, coach/seat, or entry time needed for inspection. Do not redraw codes or manually recreate a scannable ticket. Keep personal data in the user's deliverable only, never in this reusable skill or a sample asset.
8. Translate useful signs and instructions into the traveler's language. If the traveler needs to say a phrase aloud, provide a pronounceable guide in the notation they understand; do not assume IPA is useful. Verify location-specific rules, opening times, transport schedules, rental availability, and entrance instructions against current authoritative sources when possible.

## Adapt to the agent and deliverable

Use available document, map, image, browser, or PDF tools where they help. If an agent cannot make the requested file type, it can still produce a structured, editable guide with asset references and a concise handoff for conversion. If maps or photos cannot be verified, make the uncertainty visible in the artifact or handoff; do not invent evidence to satisfy a layout. Ask only for missing choices or files that would materially alter the result.

Before delivery, inspect the produced form at its real viewing or print size: route continuity, name/address legibility, image-to-stop matching, map labels, ticket completeness, QR margins, page breaks, and overlap. Report any remaining unverified items plainly.
