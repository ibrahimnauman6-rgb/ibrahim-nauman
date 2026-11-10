---
title: "Short Circuits on Backup Power: Why a Diesel Generator Doesn't Clear
  Faults Like the Grid"
description: "Specify generators for shops, offices, clinics, hotels and plazas
  in Pakistan: load profiles, prime vs standby duty, ATS/AMF changeover and
  service support."
date: 2026-11-10
cover: /ibrahim-nauman/images/diesel-generator-fault-current-breakers-hero.png
cover_alt: " Enpower Baudouin generator for commercial buildings beside a lit
  office and retail block at night"
---
Here's a story we hear a lot. A cable fault on the grid trips the right breaker almost instantly, and only one section of the building goes dark. A few weeks later a similar fault happens during load-shedding with the diesel generator running, and the result is completely different. Either the whole site blacks out, or nothing trips for a worrying length of time while a cable gets hot.

The set usually gets the blame. Most of the time it did exactly what an alternator does under a fault, and the protection downstream was never checked against it. When we size ++[Cummins ECG sets for factories and plazas](https://enpower.com.pk/cummins-diesel-generators/)++, we look at the breakers behind the set as carefully as the kVA, and this is why.

## The grid can push far more fault current than any generator

On grid supply, your main panel sits behind a distribution transformer and the wider network. When a short circuit happens, that source can deliver a very large current, limited mostly by the transformer's impedance and the cables in between. Breakers are chosen and set with that in mind, often without anyone thinking about it.

A generator is a much smaller source with far higher internal reactance. Its fault current is a fraction of what the grid can supply. The same breaker settings that cleared a grid fault in a few milliseconds may not see enough current to act fast on generator supply.

## What happens inside the alternator in the first second

When a fault hits, the alternator gives a short burst of high current that dies away within a few cycles. What matters after that is how much current it can keep supplying while the breaker decides what to do.

That depends on how the alternator is excited. A basic self-excited machine takes its excitation power from its own output. A close-in fault pulls the voltage down, the exciter is starved, and the current can collapse to a level some breakers never respond to. Alternators with a permanent magnet generator or an auxiliary winding keep the excitation going, so they can hold a sustained fault current for a short time. The alternator data sheet should state that figure. Ask for it.

## Why the wrong breaker trips, or none does

Good protection is selective. The breaker closest to the fault should open first, and everything upstream should stay closed. On grid supply this usually works because the fault current is big enough to hit the downstream breaker's instantaneous trip.

On generator supply, two things can go wrong. If the current sits below that instantaneous setting, the breaker falls back on its thermal element, which can take seconds or longer. Meanwhile the generator's own controller sees overcurrent or low voltage and shuts the whole set down. One faulty socket circuit takes out the entire building.

The other outcome is worse. Nothing trips quickly, and a cable carries a fault current for longer than it should. In a Multan or Sukkur summer, with cables already running warm at 45°C, that's how insulation gets damaged.

## Earth faults deserve a separate check

Earth faults follow the same logic. The earth fault loop on generator supply is usually different from the loop on grid supply, so protection that works on one source may be slow on the other. Monsoon season makes this more than a theory. Water in a cable trench or a junction box during a load-shedding spell is a common way for an earth fault to start while the set is the only source.

We'd ask your electrician to measure the earth fault loop with the set running and carrying the site, not only on grid. Residual current devices or earth fault relays on the right circuits help a lot, because they respond to leakage current rather than waiting for overcurrent.

## Diesel generator protection questions to ask before commissioning

None of this needs a big study for a small site. It does need someone to ask the right questions and write the answers down:

- What sustained short-circuit current can the alternator supply, and for how long, according to its data sheet?
- Which excitation system is fitted, and is that what was offered in the quote?
- Have the trip settings of the largest downstream breakers been checked against that current?
- What does the generator's controller do on overcurrent, and how quickly does it act?
- Has the earth fault loop been measured on generator supply?
- Is a short protection note, with the settings, in the handover file?

## Fixes that are usually cheaper than a bigger set

Some people respond to this by oversizing the generator so it can push more fault current. That's an expensive way round, and an oversized set brings its own problems at light load.

The cheaper fixes come first. Many modern moulded-case breakers have adjustable electronic trip units, and an electrician can often lower the instantaneous setting so it works on both sources. Where one setting can't suit grid and generator, the panel may need a different breaker or a protection relay. Choosing an alternator with excitation support at the buying stage costs far less than reworking a panel later.

## Where we see this in Pakistan

It shows up most in places that have grown in stages. Commercial plazas in Lahore where each tenant fitted their own breakers. Factories in Faisalabad and Sialkot with panels from three different decades. Housing society tube wells with long cable runs that add resistance to the fault loop. In every case the diesel generator was sized for the load, which is right, but nobody went back to check the protection when it arrived.

If you're planning a new set, or yours has caused a mystery blackout or two, ask for the protection to be reviewed alongside the kVA. The engineers at ++[Enpower](https://enpower.com.pk/)++ are happy to go through it with your electrical team.