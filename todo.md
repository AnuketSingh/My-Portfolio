# Portfolio Revision Checklist

## Latest Hero Revision

- [ ] Remove the FIELD NOTE 01 / turning inputs into insight overlay from the hero image.
- [ ] Verify the hero still has correct contrast and animation after the overlay removal.

## Framework-Free Conversion

- [x] Replace the React Home page with a plain HTML document rendered by the static entry point.
- [x] Move portfolio styling into a standalone CSS file while preserving the current visual language and animations.
- [x] Move navigation, scroll progress, pointer glow, mobile menu, and reduced-motion behavior into standalone JavaScript.
- [x] Remove Wouter imports and React page routing from the runtime.
- [x] Keep the managed build wrapper only as tooling if required by the hosting environment; do not use npm/pnpm APIs in the portfolio runtime.


- [ ] Remove the LeetCode repository from the visible project data and all portfolio copy.
- [ ] Remove the circular AS figure from the About section and replace it with a cleaner visual treatment.
- [ ] Add advanced but accessible animation to hero reveal, scroll progress, section transitions, toolkit cards, project cards, and navigation.
- [ ] Expand the color system beyond graphite and cyan with intentional coral, amber, and electric-blue accents while preserving contrast.
- [x] Verify reduced-motion behavior and mobile responsiveness.
- [x] Run TypeScript and production build checks.
- [ ] Capture desktop and mobile screenshots, save a new checkpoint, and deliver the revised portfolio.
