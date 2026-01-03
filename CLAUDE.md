# Vintage Photobooth Project

Build a web-based photobooth that authentically recreates the experience of classic 1950s German Fotoautomaten (photo booths).

## Project Overview

A simple, authentic photobooth web app that:
- Takes 4 photos in sequence
- Applies vintage black & white film effects
- Outputs a classic photo strip
- Feels like sitting in a real 1950s booth

---

## Tasks

Complete these tasks in order:

### Task 1: Basic webcam setup

Set up a simple webpage that accesses the user's webcam and displays a live video preview. Center it on the page with a "Start" button below. Keep styling minimal for now.

---

### Task 2: Add black & white filter to live preview

Apply a real-time black and white filter to the webcam preview using CSS or canvas. The user should see themselves in B&W before any photo is taken.

---

### Task 3: Single photo capture with vintage effects

Add the ability to capture a single photo from the webcam. Apply these vintage effects to the captured image:
- Black and white
- Subtle film grain
- Slight vignette (darker edges)
- Soft contrast

Display the captured photo below the preview.

---

### Task 4: Flash effect

Add a flash effect when a photo is captured—a quick white screen flash that fades out, simulating an old camera flash.

---

### Task 5: 4-photo sequence with countdown

Change the flow so that when the user clicks "Start", it captures 4 photos in sequence. Each photo should have:
- A 3-second visible countdown before capture
- The flash effect on capture
- A short pause before the next countdown begins

Store all 4 captured images.

---

### Task 6: Generate the photo strip

After all 4 photos are taken, combine them into a single vertical photo strip image:
- 4 photos stacked vertically
- White borders around each photo
- Slightly rounded corners on the overall strip
- Subtle aged/warm paper background color

Display the final strip to the user.

---

### Task 7: Download and retake

Add two buttons below the final photo strip:
- "Download" - saves the strip as a JPG image
- "Retake" - clears everything and starts over

---

### Task 8: Retro UI styling

Style the entire interface with a vintage 1950s photobooth feel:
- Dark background (like inside a booth)
- Vintage typography (use a retro Google Font)
- Optional: curtain or booth frame around the webcam preview
- Keep it minimal and authentic

---

## Technical Notes

- Use vanilla HTML, CSS, and JavaScript (no frameworks needed)
- Use Canvas API for image manipulation and effects
- All UI text in English only
- Prioritize authenticity over extra features
