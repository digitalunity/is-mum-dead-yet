# Publishing and review checklist

The site is designed for plain GitHub Pages from `main` at the root of this repository.

## Publish on the GitHub-provided URL (no domain needed)

1. Open [repository Settings](https://github.com/digitalunity/is-mum-dead-yet/settings).
2. Choose **Pages** in the sidebar.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main**, folder **/ (root)**, then **Save**.
5. GitHub will publish at **https://digitalunity.github.io/is-mum-dead-yet/** once deployment completes. Verify the URL and deployment status before sharing it. This URL is the *expected* address, not a claim the site is already live.

The `.nojekyll` file is included so the static files are served as-is. No build system, Actions workflow, custom domain, cloud server or paid hosting is required for the current site.

> The GitHub connector used to build the repository cannot change the Pages settings. Publication has not been switched on by these commits.

## Acceptance checks

- [ ] The hero shows the correct title and both CTA links work.
- [ ] Grandma illustration loads and stays within the layout on mobile.
- [ ] The diagram is readable at phone widths (including text labels).
- [ ] All links and hash navigation work under the repository subpath.
- [ ] Keyboard focus and headings make sense.
- [ ] Sample timeline prominently says 'ILLUSTRATIVE EXAMPLE · NOT LIVE DATA'.
- [ ] No real activity data, addresses, credentials or location details are included.
- [ ] No claim that the system is a medical alarm or a commercial service.
- [ ] No console errors, broken links or mixed-content warnings.
- [ ] Run an accessibility and mobile performance review.
- [ ] Obtain approval before using personal quotes/identifying details outside this project.
- [ ] Test with a private browser session after Pages has deployed.

## Technical notes

All asset links are relative (`assets/…`, `styles.css`), so they work under GitHub Pages' repository subpath. The site makes no JavaScript, external font, analytics or cookie requests.

The current illustration is custom SVG created for this web draft. It is **not** the generated poster image from the conversation. The illustrated floor plan is fictitious and must not be mistaken for the real installation.

A social-sharing preview image could be added later as a dedicated PNG. Until then, the share title and description are set, but external social platforms may not display the SVG artwork consistently.

## After the experiment

The name and tone may be intentionally cheeky, but future content must remain factual, consent-aware and clear about uncertainty. Revisit the safety text whenever copy changes.
