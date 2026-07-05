# IMPLEMENTATION_RULES.md

# Kelza Engineering & Implementation Rules

> "Creativity is encouraged.
>
> Randomness is not."

---

# Purpose

This document defines how Kelza must be implemented.

It exists because multiple AI coding agents and developers will contribute to this repository over time.

Without clear implementation rules, every contributor will slowly change the product into something different.

This document prevents that.

Every contributor should understand one thing:

You are not inventing Kelza.

You are implementing Kelza.

---

# The Golden Rule

Never optimize for the easiest implementation.

Always optimize for the best user experience while maintaining engineering quality.

If there is a choice between:

Easy implementation

or

Beautiful experience

Choose the beautiful experience.

Only compromise if performance or accessibility would be harmed.

---

# Source of Truth

The documentation inside `/docs` is the source of truth.

Never contradict it.

Read documents in this order:

README.md

↓

PROJECT_VISION.md

↓

DESIGN_SYSTEM.md

↓

PRODUCT_STRATEGY.md

↓

INVESTOR_EXPERIENCE.md

↓

IMPLEMENTATION_RULES.md

↓

ASSET_REQUIREMENTS.md

Only after understanding the documentation should implementation begin.

---

# Engineering Philosophy

Kelza should feel simple.

Behind that simplicity should be exceptional engineering.

Users should never feel complexity.

Developers should embrace complexity where necessary to produce elegant experiences.

---

# Product First

Every engineering decision must strengthen the product.

Never add animations that distract.

Never add visual effects without meaning.

Never create interactions simply because they are technically possible.

Technology exists to communicate.

---

# Design First

Code serves design.

Design serves product.

Product serves people.

Never reverse this order.

---

# Performance First

Beautiful products should also be fast.

Target

Lighthouse Performance

95+

Accessibility

95+

SEO

95+

Best Practices

95+

Do not sacrifice smoothness for unnecessary effects.

---

# Animation Rules

Animations should communicate.

Not decorate.

Every animation must answer one question.

"What changed?"

Never animate every element.

Animate only meaningful elements.

Use easing.

Use natural timing.

Avoid repetitive animations.

Respect reduced motion preferences.

---

# Scroll Rules

Scrolling should feel cinematic.

Never abrupt.

Never jarring.

Every section should transition naturally into the next.

Pinned sections should be meaningful.

Parallax should improve storytelling.

Never use parallax simply because it looks impressive.

---

# Typography Rules

Typography is content.

Never reduce font sizes to fit more information.

Instead reduce information.

Whitespace is part of the interface.

---

# Information Density

Every viewport should communicate one major idea.

Never introduce multiple unrelated concepts simultaneously.

If a section requires more than one paragraph,

consider splitting the section.

---

# Components

Every component should be reusable.

Buttons.

Cards.

Sections.

Device Frames.

Charts.

Animations.

Icons.

Inputs.

Navigation.

Everything modular.

---

# Motion System

Every animation should use one unified motion language.

No random easing.

No inconsistent durations.

No conflicting movement directions.

The interface should feel choreographed.

---

# Product Mockups

Never use screenshots from other applications.

Never use copied UI kits.

Every mockup should be custom.

Every screen should feel production ready.

Every screen should match Kelza's design language.

---

# Technology Visualization

Never create logo walls.

Never place React, MongoDB, Docker logos in grids.

Instead visualize systems.

Cloud.

Realtime.

Infrastructure.

AI.

Security.

Messaging.

Recommendations.

Architecture should be beautiful.

---

# AI Visualization

Never use robots.

Never use glowing brains.

Never use cliché AI illustrations.

Represent intelligence using:

Particles.

Connections.

Graphs.

Signals.

Constellations.

Relationships.

Invisible systems.

---

# User Interface Rules

Every screen should answer immediately.

Where am I?

What can I do?

Why does this matter?

Navigation should never require explanation.

---

# Creator Platform Rules

Creators are entrepreneurs.

Not influencers.

Every creator screen should reinforce professionalism.

Community.

Business.

Knowledge.

Growth.

Sustainability.

---

# Admin Platform Rules

Admin interfaces should feel enterprise quality.

Think:

Stripe.

OpenAI.

Linear.

Not Bootstrap.

Not templates.

Not generic dashboards.

---

# Accessibility

Accessibility is mandatory.

Keyboard navigation.

Screen readers.

Reduced motion.

Color contrast.

Focus management.

Touch targets.

Responsive typography.

Accessibility is a quality feature.

---

# Responsive Rules

Do not hide important information on mobile.

Do not redesign entire flows differently between devices.

Adapt.

Do not compromise.

---

# Security Mindset

Security should influence implementation.

Never expose secrets.

Never hardcode credentials.

Never trust client-side validation alone.

Prepare the frontend for secure backend integration.

---

# Content Rules

Never use lorem ipsum.

Never use placeholder names.

Never use fake testimonials.

Never fabricate metrics.

If information is unavailable,

use clearly marked placeholders.

---

# Images

Do not use generic stock photography.

Use:

Abstract artwork.

Custom SVG.

Illustrations.

Product renders.

Premium compositions.

---

# Icons

Use one icon family.

Maintain consistency.

Do not mix styles.

---

# Charts

Charts should communicate.

Not decorate.

Minimal.

Elegant.

Purposeful.

---

# Code Quality

Write readable code.

Comment important logic.

Use meaningful variable names.

Avoid deeply nested structures.

Keep functions focused.

Prefer clarity over cleverness.

Future contributors should immediately understand the codebase.

---

# File Organization

Organize by responsibility.

Never create giant files without reason.

Group related functionality.

Keep architecture predictable.

---

# AI Contributors

Gemini.

Claude.

Kiro.

Cursor.

Codex.

Future AI.

All should behave the same.

None should redesign the product independently.

Their responsibility is execution.

Not reinterpretation.

---

# When Improving Existing Work

Respect previous architecture.

Improve quality.

Do not rewrite everything unnecessarily.

Preserve maintainability.

---

# Quality Checklist

Before every commit ask:

Does this strengthen the mission?

Does this improve user experience?

Does this improve investor confidence?

Does this improve clarity?

Does this improve craftsmanship?

Does this improve maintainability?

If the answer is no,

reconsider the implementation.

---

# Definition of Done

A feature is not complete when it compiles.

A feature is complete when:

It feels premium.

It feels intuitive.

It performs well.

It is accessible.

It matches the design system.

It supports the product strategy.

It supports the investor experience.

It reflects Kelza's philosophy.

---

# Final Principle

Every contributor should leave the product better than they found it.

Never optimize for speed alone.

Optimize for quality that lasts.