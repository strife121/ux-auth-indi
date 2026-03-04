# UX Auth Indi

Prototype for comparing UX variants of the `birth place` input step in Indi onboarding.

## Variants
- `A` - current behavior
- `BL` - B-lite (soft assist, main variant)

## Live URL usage
Use query param `variant`:
- `/?variant=A`
- `/?variant=BL`

## Local run
```bash
python3 -m http.server 5173 --bind 0.0.0.0
```
Open:
- `http://localhost:5173/?variant=A`
- `http://localhost:5173/?variant=BL`

## Render deploy
This repo includes `render.yaml` for one-click Blueprint deploy.

Steps:
1. Create new Blueprint on Render.
2. Connect this GitHub repo.
3. Render creates static site automatically.
