# Website direction and editorial principles

Updated: 2026-10-14. This is a creative working brief, not fixed requirements.

## One-line proposition

**Is Mum Dead Yet?** A darkly funny name for a caring, experimental DIY approach to understanding everyday activity when someone lives alone.

## Why publish?

- Start conversations about ageing, independence and uncertainty without making death taboo.
- Show a practical example of everyday devices working together to provide useful context.
- Help technically curious people realise they might be able to build something adapted to their family.
- Tell an honest, human story of a system being built, including failed experiments.

**Success is somebody learning, sharing, improving, or feeling less bewildered.** Revenue is not the objective.

## Identity split

- **Is Mum Dead Yet?** is the accessible public story and playful illustration-led site.
- **HomePulse** is the underlying experimental engineering project and source of technical truth.
- Neither should be represented as a finished, medically certified, commercially supported product.

## Audience

1. Adult children worrying about parents who live alone.
2. Makers, developers and hobbyists who can adapt a DIY idea.
3. Carers, community technologists and people thinking about independent living.

## Site tone

Warm, funny, hopeful, respectful and straightforward. Never mock the parent, their age, disability or fear. The joke is the awkward *question*, not the person. Avoid creepy monitoring/surveillance imagery, made-up metrics, technical jargon and alarmist copy.

Visual direction comes from the original cheerful infographic poster: oversized navy and coral title, teal strokes, rounded pastel cards, cosy tea-and-cat illustration and a human-first infographic style.

## Key story

Mum voiced a real worry: what if she died overnight and nobody knew? The response was not to promise impossible certainty but to ask whether normal household activity could provide useful evidence without requiring her to remember an app, carry a phone or wear a monitor.

A SenseCAP BC03 beacon underneath her walking trolley is picked up by USB-powered M5Stack AtomS3 Lite receivers. A Raspberry Pi can analyse comparative BLE signal strengths to estimate which room **the trolley** is in. Other sources, such as the already-deployed Tapo S200B lamp button, an optional door-contact sensor, doorbell/camera metadata and possible fridge sensor, can provide independent event timestamps and visitor context.

The system is being assembled and validated. Some device integrations and many dashboard capabilities are not yet proven.

## What not to claim

- That tracking a trolley means we always know a person's physical location.
- That lack of movement indicates death, or movement proves life or wellbeing.
- That a door opening identifies who entered.
- That video, camera still capture, doorbell events or Tapo event ingestion are confirmed integrations where untested.
- That the mock dashboard is real data or the system already provides reliable alerts.
- That HomePulse replaces calling Mum, visiting, an appropriate personal alarm, professional care or emergency services.

## Data and safety standards for anything public

- Never expose Mum's location/address, floor plan, actual schedules, raw household events, MAC addresses, device credentials, IP addresses, alarm/camera configuration or personal medical details.
- All sample times and activity timelines must be labelled **illustrative**.
- Show consent, dignity and privacy as design priorities, not add-ons.
- Explain sensor uncertainty and offline status. Any action cue must be 'check in', not 'assume the worst'.
- Keep third-party trackers off the website by default.
- Review any direct first-person quotation with the people involved before promoting widely.

## Suggested voice

> The name is a joke. The care behind it isn't.

> Not watching Mum. Just joining the dots.

> Because sometimes a small sign of everyday life can mean a lot.

## Open editorial choices

- Should the final hero use the original poster artwork, a fresh bespoke web illustration, or elements of both?
- How much of the family story should be public?
- Is a real photo of the trolley/beacon desirable, with identifying details removed?
- Should the site eventually have a 'Show me your build' community section?
- Would a printable DIY overview help people share the idea with relatives?

Nothing here commits the project to providing installation services or customer support.
