# Rowan Yu Portfolio Site v13 - Inline CSS Version

This version inlines all CSS inside `index.html` to avoid GitHub Pages layout issues caused by `style.css` not loading.

## Deploy

Upload these items to the ROOT of your GitHub Pages repository:

- `index.html`
- `assets/`

Do not upload the outer folder itself.

Your repository root should look like:

```
index.html
assets/
  Gun.jpeg
  Humvee.jpeg
  Mortar.jpeg
  SpeedBoat.jpeg
  SpeedBoat_Simulating.jpeg
  BXR_Promo.mp4
  Rowan_Yu_Google_ATS_Resume_EN.pdf
```

After upload, wait 1-5 minutes and hard refresh the page with Ctrl + F5.


## v14 Updates

- Renamed `Download Resume PDF` to `Resume PDF` because the link opens the PDF preview in a new tab.
- Added a LinkedIn Recommendations section after About and before Featured Case Studies.

## v15 Updates

- Changed LinkedIn Recommendations into an embedded carousel-style section.
- Added left/right navigation buttons, dot pagination, smooth sliding transition and touch swipe support.
- This is an embedded/static carousel because LinkedIn recommendations cannot be directly loaded from LinkedIn into a GitHub Pages static site without an official authorized API/widget.

## v16 Updates

- Replaced placeholder recommendation cards with real LinkedIn recommendation excerpts.
- Added recommendation cards for:
  - Chris Chen
  - Leo Li
  - Yu Shu Hsu
  - Yu-Ting Chen
- Added a `View full recommendations on LinkedIn` link below the carousel.
- The Yu-Ting Chen excerpt avoids an unfinished sentence from the provided draft.

## v19 Updates

- Based on v16 layout, not v18.
- Kept the original v16 case-study layout ratio: image column 38%, text column unchanged.
- Changed Featured Case Studies images to proportional zoom + crop inside the same image frame.
- Image CSS now uses `object-fit: cover` and `transform: scale(1.08)`.
- This makes images look larger without shrinking the text description area.

## v30 Updates

- Preserved the v29 image layout/shifts supplied by the user.
- Centralized weapon hardware signal and tracking-coordinate integration into a dedicated case study:
  - Arduino weapon signal input
  - Antilatency tracking workflows
  - OptiTrack integration
  - Coordinate-space alignment between external tracking systems and headset / VR runtime tracking spaces
- Removed detailed hardware / tracking mentions from the Marine Corps overview so the topic is introduced in one place.
- Moved Mortar Training Simulator below the hardware / tracking case study.
- Moved Unreal Android APK Validation near the top of the Big X Reality case studies because the target Google role is Android-related, while keeping the wording scoped as validation / ramp-up rather than production Android experience.

## v31 Updates

- Cleaned up overlap between Marine Corps VR Training Simulator and Reusable Unreal Tools & Runtime Tuning.
- Marine Corps now focuses on project scope, multiplayer scale, NPC behavior design/implementation and Unreal Insights profiling.
- Reusable Unreal Tools now centralizes packaged-build launch tools, runtime configuration, telemetry abstraction and reusable workflow tooling.
- Unreal Android APK Validation on VIVE Focus 3 is now clearly marked as personal/self-directed validation, not a Big X Reality product.
- Android validation now uses a logo-card style instead of a project photo, similar to the HTC card.

## v32 Updates

- Reordered Big X / related case studies:
  1. Marine Corps VR Training Simulator
  2. Weapon Hardware Signals & Tracking Coordinate Integration
  3. Reusable Unreal Tools & Runtime Tuning
  4. Unreal Android APK Validation on VIVE Focus 3
  5. Mortar Training Simulator
- Moved Mortar Training Simulator below Reusable Unreal Tools & Runtime Tuning.
- Moved Unreal Android APK Validation on VIVE Focus 3 above Mortar Training Simulator.

## v33 Updates

- Changed Mortar Training Simulator from reversed layout to standard layout.
- Mortar image now appears on the left side to match the current case-study visual sequence.

## v36 Updates

- Updated Unreal Android APK Validation on VIVE Focus 3 with latest validated results.
- Clarified it is a self-directed Android ramp-up validation exercise, not a Big X Reality product.
- Added UE 5.4.4, VIVE OpenXR Plugin 2.5.0, Android ASTC packaging, ADB install and Logcat diagnostics.
- Added Vulkan-only Android baseline and required CVar / Device Profile overrides.
- Added issues resolved: 2D-vs-VR recognition, Vulkan startup, OpenXR disablement, black/white screen, inverted image and stereo rendering.
- Clarified controller input appears functional and hand tracking is not yet validated.

## v37 Updates

- Refined Android validation wording for portfolio/resume tone.
- Removed over-emphasized negative phrasing around Big X Reality / shipped Android / Google Play.
- Changed controller status to validated as functional.
- Removed future-study profiling disclaimer from portfolio content.


## v38 Updates

- Added a standalone Personal Android Validation section separate from Big X Reality.
- Focus 3 Android validation is presented as completed personal validation.
- Added Google Pixel Android phone build/performance validation as a planned next track.
- Updated embedded resume PDF to v14.

## v39 Updates

- Mortar Training Simulator uses reversed layout so the image appears on the right.
- Google Pixel Android Phone Build & Performance Validation is placed directly below Unreal Android APK Validation on VIVE Focus 3.
- The Android validation track is kept together because it is the closest portfolio evidence for Google Android / Play / Games.

## v40 Updates

- Fixed case-study grouping after v39.
- Mortar Training Simulator is moved back under Big X Reality, below Reusable Unreal Tools & Runtime Tuning.
- Personal Android Validation order is now:
  1. Google Pixel Android Phone Build & Performance Validation
  2. Unreal Android APK Validation on VIVE Focus 3
- Mortar Training Simulator remains in reversed layout so the image appears on the right.

## v41 Updates

- Refined Personal Android Validation wording for ATS-style clarity.
- Prioritized the Google Pixel planned validation card as the first Personal Android Validation case study.
- Softened scope-boundary wording on the Pixel card while keeping the work accurately framed as planned validation.
- Updated resume PDF asset to the v15 ATS resume.

## v42 Updates

- Added a new LinkedIn recommendation from Shuo Han Yeh as the first recommendation card.
- Recommendation highlights HTC VR project collaboration, VR headset/tracker API work, Unreal integration, CPU/memory optimization, code quality, reliability, stability and teamwork.

## v43 Updates

- Updated Shuo Han Yeh's current company from Getac to Synopsys.

## v44 Updates

- Fixed Shuo Han Yeh recommendation card formatting to match the other LinkedIn recommendation cards.
- Shortened the recommendation from a full multi-paragraph letter to a concise excerpt so the section no longer appears enlarged.
- Kept Shuo Han Yeh as the first recommendation and kept company as Synopsys.

## v45 Updates

- Rebuilt Shuo Han Yeh's recommendation card to match Chris Chen's recommendation card format exactly:
  - LinkedIn Recommendation badge
  - quote paragraph with class="quote"
  - recommendation-meta block
  - strong name line
  - title/company span
  - relationship span
