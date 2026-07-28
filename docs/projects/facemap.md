# Facemap

Facemap is a browser-based facial anatomy overlay tool built to support aesthetic consultation visuals and clinical documentation.

## Problem

Facial anatomy and treatment context can be difficult to explain with words alone during consultation. A visual reference can make the discussion easier to document and review.

## What I Built

- Front photo upload
- Browser-based MediaPipe Face Landmarker integration
- Semantic landmark mapping
- Anatomical anchor estimation
- SVG facial muscle overlay
- Muscle on/off controls
- Opacity, scale, and offset controls
- Debug views for landmarks and anatomical anchors
- PNG export for consultation documentation

## Technology

Next.js, React, TypeScript, MediaPipe Face Landmarker, SVG, canvas export, Tailwind CSS, Cloudflare/Vinext tooling.

## Privacy Design

The MVP runs image analysis in the browser and does not upload or permanently store photos. Public screenshots use non-patient demo visuals only.

## Limitations

Facemap is not a diagnostic tool and does not determine treatment or injection locations. Overlay output is an educational reference that requires clinical judgment.

## Roadmap

- Multiview capture using front, 45-degree, and profile photos
- 2.5D facial anchor refinement
- Profile-aware overlay adjustments
- PDF report export
- AI-assisted overlay refinement after workflow validation
