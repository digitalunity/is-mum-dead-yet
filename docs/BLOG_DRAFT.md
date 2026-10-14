# Blog draft: Is Mum Dead Yet?

**Status:** Draft for Chris to revise in his own voice before publishing. No blog URL chosen.

## It's a terrible name for a product. I know.

A conversation with my mum started with a question that nobody particularly enjoys hearing.

**"What if I die in the night and nobody knows?"**

It's a fair question. When somebody lives alone, there can be hours between one conversation and the next. You can ring, visit and do your best, but you can't always be there.

My first instinct was to think about it as a systems problem.

Not *how do I prove that somebody is alive?* You can't reliably do that with a couple of gadgets around the house. Instead, I wondered whether there were small, ordinary signs of activity that could give us a better sense of what had been happening.

## We already leave clues everywhere

A light being switched on. A door opening. Somebody moving from one room to another. A physical button being pressed.

Each of those things tells us something. None tells us everything.

That distinction turns out to be crucial. A smart device reporting that something happened doesn't mean Mum did it, and an absence of activity doesn't mean there's an emergency. But if you're trying to decide whether it's time to telephone or pop round, a little context can be better than none.

## Enter a walking trolley and a tiny Bluetooth beacon

My mum uses a walking trolley around the house. That gives us a practical starting point: a small Bluetooth beacon can live underneath the trolley, while little receivers in different rooms listen for the signal.

A Raspberry Pi can compare the readings and make an approximate estimate of which room the trolley is in.

'Approximate' matters. Bluetooth signals bounce, walls intervene and devices go offline. This isn't GPS indoors, and it tracks the trolley, not Mum herself. The system has to be calibrated, checked and allowed to say *uncertain*.

## The lamp button was an unexpected clue

We added a simple button to the trolley so Mum could switch a lamp on without reaching for a difficult switch.

Then it clicked: a press of that button leaves a timestamp. Because it's a control she normally uses, it's a useful piece of resident-linked activity evidence. It's still not proof of identity or wellbeing, but it's stronger than a random motion event.

The wider idea is to combine these clues with door and visitor events, rather than leaning on any single gadget.

## So where does that ridiculous name come from?

I was chatting to friends who have similar worries about their own parents. We ended up making the sort of dark joke that people sometimes make when they're dealing with serious things.

Someone said we were basically all wondering the same thing:

**"Is Mum dead yet?"**

It's a terrible title. Which is probably why we laughed.

But I also think it makes an awkward subject easier to talk about. The technology is serious; the name doesn't have to be.

## HomePulse is the real experiment

The serious project is called **HomePulse**. It's a DIY home-awareness system, currently being built and tested.

I don't expect it to be a consumer plug-and-play product. Every home is different. Bluetooth calibration takes work, devices behave inconsistently, and integrations that seem straightforward on paper don't always cooperate.

I'm not selling a monitoring service. I'm sharing an idea and the process of building it.

Perhaps somebody reading will build their own. Perhaps they'll improve the design. Perhaps they'll just think differently about a problem they hadn't known how to approach.

That's enough of a reason to publish it.

## What it can never promise

HomePulse isn't a medical alarm, a fall detector or an emergency-response system.

Somebody can be unwell immediately after pressing a button. A visitor can open a door. A device can miss an event. An immobile trolley can have an entirely ordinary explanation.

So the point isn't to outsource care to sensors. It's to understand activity a little better and remember that the important next step is still a human one.

A call. A conversation. A visit.

## One last thing

Sometimes the smallest things are the most reassuring.

A kettle on. A lamp switched on. A little movement around the house.

Or, perhaps, a message that somebody had a cuppa.

**The name is a joke. The care behind it isn't.**

---

### Editorial notes (not part of published article)

- Replace generic opening with personal voice if comfortable. Obtain Mum's consent before using direct quotes or identifiable details.
- Distinguish hardware already installed (S200B lamp control) from planned HomePulse telemetry and dashboards.
- Do not publish location information, specific home layout, real activity logs or other security-sensitive details.
- The site's illustrated sample dashboard is fictitious.
- Link to HomePulse repository and finished website after Pages publication.
- Consider photos of generic hardware on a workbench, rather than identifiable photos from Mum's home.
