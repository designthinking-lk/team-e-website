# HANDOver — Team E

**ICE Bootcamp 2026** · Design Innovations, Foundation of Goodness

HANDOver preserves Sri Lankan traditional craftsmanship by capturing a master
artisan's technique with Meta Aria Gen 2 smart glasses — POV video, eye gaze,
hand tracking, and narrated audio — and turning it into a structured knowledge
base. That knowledge base powers a real-time, camera-driven training
experience for apprentices at vocational institutions such as NAITA: an
overhead camera and tablet guide each trainee step by step, checking their
hand movements against the reference and giving corrective feedback before
they move on.

**Harvest → Analyze → Hand over.**

Live site: [handover.designthinking.lk](https://handover.designthinking.lk)

## Structure

Static site, no build step:

- `index.html` — page markup
- `styles.css` — all styling
- `script.js` — nav toggle, scroll reveal, poster lightbox
- `assets/images/` — poster, team photos, craft photography
- `assets/video/` — compressed demo footage (origami tutorial demo + project intro)

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```
