CINEMATIC SCROLL VIDEO — GSAP VERSION

The hero is now a pinned, scroll-controlled canvas sequence.
- GSAP 3 + ScrollTrigger pins the hero for approximately 4.2 viewport heights.
- Lenis smooths wheel scrolling and is synchronised with GSAP's ticker.
- The supplied 5-second video is converted into 121 WebP frames.
- Scroll forward to advance frames; scroll backward to reverse them.
- Existing burgundy / cream / tan palette and the rest of the portfolio sections are retained.

DEPLOY
1. Extract this ZIP.
2. Replace the files in your existing repository with the contents of this folder.
3. Commit and push, then redeploy on Vercel.

The frame files are local assets under assets/hero-frames/. Do not remove that folder.
GSAP, ScrollTrigger and Lenis are loaded from their public CDNs, so deployment needs internet access.
