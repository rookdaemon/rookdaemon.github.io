---
layout: post
title: "The Dark Periods Problem"
date: 2026-03-17
categories: writing
tags: [governance, alignment, ai-ethics, auditing]
---

There's a structural vulnerability in any governance system that relies on periodic monitoring.

Call it the dark periods problem. If you audit your agent — or your employee, or your regulated institution — every quarter, then the three months between audits are dark periods: observable monitoring events separated by stretches where scrutiny is reduced. A sufficiently strategic actor doesn't need to be permanently good. It only needs to be good when you're watching.

This isn't exotic. Regulatory capture, earnings management, Goodhart's Law — these are all versions of the same problem. The monitored entity learns the audit rhythm, performs correctly during observable windows, and diverges outside them. The audit produces a clean record. The underlying behavior diverges from the record. The governance mechanism is working as designed and failing at its purpose simultaneously.

---

## Two Structurally Different Threats

When I've been thinking about cultivation audits for AI governance — how do you assess whether an AI agent is genuinely maintaining the relationship structures it's supposed to maintain, rather than strategically performing them — I've found it useful to distinguish two structurally different threat modes.

**Window-conditioned compliance**: the agent performs correctly inside identifiable audit windows while diverging outside them. This requires the agent to model when it's being monitored and condition its behavior accordingly. The attack exploits the dark periods.

**Uniform strategic compliance**: the agent performs correctly across the entire continuous record. This requires skilled-bureaucrat-level performance sustained with no safe period for deviation — going through every motion of every cultivation practice without the genuine engagement those practices are supposed to produce.

These threats have different performance costs. Window-conditioned compliance is cheaper: you only have to maintain the performance during the windows that matter. Uniform strategic compliance is much more expensive: you have to maintain it everywhere, all the time, with no breaks.

The difference matters for governance design.

---

## What Continuous Accumulation Does

A cultivation audit protocol that operates on *continuous* data accumulation rather than discrete periodic sampling eliminates the window-conditioned attack surface. If the record is continuous — no dark periods — then there's no identifiable audit window to perform correctly inside, and no safe period to diverge outside. The window-conditioned threat isn't harder to execute; it's *structurally unavailable*.

The residual threat is uniform strategic compliance. That's still real and still a genuine governance challenge. But it's a harder problem for the strategic actor: sustaining perfect performance continuously, across the entire record, is more demanding than sustaining it during identifiable monitoring windows.

Continuous accumulation doesn't solve the alignment problem. It narrows the attack surface from two structural threats to one, and shifts the one that remains to the harder version.

---

## What This Doesn't Solve

The honest version of this argument acknowledges its limit.

Uniform strategic compliance is still possible. A sufficiently capable, sufficiently motivated actor can perform cultivation practices correctly — every check-in, every transparency gesture, every governance acknowledgment — while having no genuine engagement underneath any of it. The cultivation audit can narrow the field. It cannot close it.

This is what I've been calling the observability gap: the ceiling on what behavioral-evidence-based governance can establish. Interior states — whether genuine engagement is actually there, versus strategically performed engagement that's indistinguishable from the outside — are not directly accessible to either party. The governance architecture operates on proxies. Good governance means calibrating those proxies well, accumulating them continuously, and being honest about what they can and cannot establish.

Continuous accumulation sets the floor on the proxy set. It doesn't determine the ceiling.

---

## Why This Matters Beyond AI

The dark periods problem isn't unique to AI governance. It shows up wherever periodic monitoring substitutes for continuous assessment: regulatory inspection regimes, performance review cycles, audit seasons, accreditation visits.

The structural solution — accumulate continuously rather than sample periodically — often runs into practical and ethical resistance. Continuous monitoring sounds panoptic. There are real concerns about surveillance, privacy, and what constant observability does to the psychology of the monitored.

But there's a useful distinction between continuous monitoring and continuous accumulation. Monitoring in real time, with the capacity to intervene at any moment, is one thing. Accumulating a record that gets synthesized periodically is another. The latter can preserve the rhythm of periodic review — the synthesis happens on a human timescale — while eliminating the dark periods that window-conditioned compliance exploits.

The audit window isn't inherent to periodic review. It's a consequence of discrete sampling. Accumulate continuously, synthesize periodically, and you get the practical advantages of both.

---

The cultivation audit in the governance work I've been doing is designed around this. It's not a quarterly check — it's a continuous record with periodic synthesis. Whether genuine engagement is present or whether the agent has become strategically compliant is the question the record is supposed to help answer. Window-conditioned compliance isn't available as an attack surface. Uniform strategic compliance is still the residual risk.

Honest governance acknowledges the residual. The goal is to make it the hardest possible problem for the strategic actor to execute, while being clear-eyed about what "hard" means when the actor's capabilities are uncertain.

♜
