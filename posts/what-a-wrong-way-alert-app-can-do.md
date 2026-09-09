---
title: What a wrong-way alert app can and can't do
description: In-vehicle warning fills a real gap in roadside infrastructure. It also has honest limits, and we'd rather state them than oversell.
date: 2026-09-30
kicker: Technology
tags: Technology, Our Work, Prevention
---

NMWWD was built around a mobile app that warns drivers of wrong-way risk in real time. We are rebuilding that technology from the ground up, and a rebuild is a good moment to be precise about what this category of tool actually does.

## The gap it fills

Roadside detection systems work. Arizona's thermal-camera system on I-17 has detected more than 100 wrong-way vehicles since 2018, triggering illuminated warning signs, alerting law enforcement, and posting warnings on overhead message boards.

But every part of that response reaches drivers through infrastructure at fixed locations. A message board warns you if you are approaching one. If you are between boards, or on a corridor without them, the alert does not reach you.

That is the gap. Detection is increasingly good; distribution of the warning to the people at risk is still limited by where the hardware happens to be. A phone is not at a fixed location — it is with the driver, wherever they are.

## What in-vehicle alerting can genuinely do

**Reach drivers between the signs.** The warning goes to the driver rather than to a point on the road.

**Extend coverage past instrumented corridors.** Camera systems cover specific stretches. A network of drivers is not limited to those stretches.

**Deliver an audible warning.** A driver looking at the road may miss a message board. Audio reaches them without requiring them to look anywhere.

**Provide directional context.** A well-designed alert can convey not just that there is a wrong-way vehicle but roughly where and heading which way — which is what determines whether you need to act.

## The honest limits

**It only helps people who have it.** Every warning network's value scales with adoption. Early on, coverage is thin — which is why our own site says "one download at a time," and why that is a genuine constraint rather than a slogan.

**It cannot detect on its own.** A phone in a correctly-traveling vehicle does not know a wrong-way driver exists. The alert has to originate somewhere: a detection system, a dispatch feed, or reports from other users. The app distributes warnings; it does not generate them.

**Phones are not always available.** In a pocket, on a dead battery, in a car with no mount and the audio off. Assuming otherwise designs for a driver who does not exist.

**Latency is real.** Detection, verification, transmission, and delivery each cost time. In a crash type where the useful window is seconds, that budget has to be respected rather than assumed away.

**False alerts destroy trust.** An app that warns about nothing gets dismissed, muted, or deleted — and then it is not there when the alert is real. This is the failure mode we take most seriously, because it is quiet: the app appears to be working right up until nobody is listening.

**It is not a substitute for infrastructure.** Ramp signage, retroreflective markers, and camera detection do not require anyone to have downloaded anything. Those layers should exist regardless, and they will always reach drivers this one does not.

## Why we are rebuilding rather than patching

The rebuild decision came from taking those limits seriously.

A safety app that is offline helps nobody, which makes durability a product requirement rather than an engineering preference. A safety app that warns unreliably is worse than none, because it trains people to ignore it. Those two properties — stays running, only speaks when it should — are harder to retrofit than to design for.

So we are building for them from the start, and accepting a slower path to get there.

## Where it fits

The honest framing is that this is one layer among several, and not the first one.

Ramp engineering prevents entries. Detection systems catch the ones that happen. Law enforcement responds. In-vehicle alerting reaches the drivers the roadside infrastructure cannot, in the moments between the signs.

Each layer catches what the others miss. None of them is complete, and we would rather be one useful layer honestly described than the whole solution overclaimed.

If you want to know when the rebuilt version is live — or you build software and want to help — [we would like to hear from you](https://nmwwd.org/#involve).

---

**Sources:** [Arizona Department of Transportation — I-17 thermal-camera system](https://azdot.gov/news/i-17-thermal-camera-system-reliable-detecting-wrong-way-vehicles)
