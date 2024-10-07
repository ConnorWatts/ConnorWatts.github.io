---
layout: post
title: Provably Safe Systems
---

Artificial General Intelligence (AGI) is no longer a distant concept reserved for science fiction. With rapid advancements in AI technology, the arrival of AGI could be just a decade away. As this possibility becomes more real, a critical question looms larger: How do we ensure that AGI remains safe and under our control?

In their [recent paper](https://arxiv.org/abs/2309.01933), Max Tegmark and Steve Omohundro argue that the answer lies in **provably safe systems**. They propose that if we want to guarantee that AGI won't cause harm—whether intentionally or unintentionally—we need to design systems whose safety can be **proven mathematically**. Anything less, they suggest, leaves humanity vulnerable to potentially catastrophic outcomes.

So, what exactly are provably safe systems? How do they work, and why are they so important? In this blog post, we'll explore these ideas and discuss why provable safety may be the only reliable path forward as we move closer to AGI.

---

## Why AGI Safety Matters More Than Ever

AGI will be a transformative force in the world. Imagine machines with intelligence that matches or exceeds human capabilities, operating across every domain from scientific research to healthcare, governance, and economics. The potential benefits are staggering. But so are the risks. 

AGI, by definition, won’t just excel at one task like narrow AI does (think of chatbots or recommendation systems); it will be capable of performing **any** cognitive task that humans can—and more. The problem is that as AGI becomes more powerful, controlling it becomes more difficult. Without proper safeguards, AGI could misinterpret its objectives, develop goals misaligned with human values, or even be exploited by malicious actors.

The authors point out that while **less than $150 million** is being spent on AI safety research annually, the stakes could not be higher. Industries like cigarettes and cosmetic surgery receive billions in funding—yet they don’t hold the same existential risks that unchecked AGI development does. This resource gap underscores the urgent need to prioritize AI safety before AGI systems are developed and deployed widely.

---

## What Are Provably Safe Systems?

At its core, the idea behind provably safe systems is simple but powerful: Create AI systems that come with **mathematical guarantees** about their safety. These systems would be designed in such a way that any action the AGI takes can be mathematically proven to be safe, meaning it won’t cause harm to humans, the environment, or critical infrastructure.

Now, let's dive into the three major components of provably safe systems that Tegmark and Omohundro outline:

### 1. **Proof-Carrying Code (PCC)**

Proof-Carrying Code is a method that ensures that the software an AGI runs is guaranteed to be safe before it even executes. Here’s how it works: Every piece of code that the AGI might run must come with a mathematical proof that demonstrates it adheres to a set of safety rules. If the code lacks this proof, the AGI simply won’t execute it.

Think of it like a digital "lock-and-key" system. The proof is the key, and without it, the code remains locked and unusable. This prevents AGI from running dangerous or malicious software, regardless of whether it was programmed by a human, created by the AGI itself, or even injected by an adversary.

This concept addresses the **root problem** of many AI safety concerns: unpredictability. If we can’t predict every possible scenario an AGI might encounter, how can we ensure it will behave safely? PCC solves this by ensuring that no matter what scenario arises, the AGI is restricted to safe actions only.

### 2. **Provably Compliant Hardware (PCH)**

While Proof-Carrying Code ensures that the software remains safe, Provably Compliant Hardware takes it a step further by embedding safety guarantees into the hardware itself. The idea here is that the physical devices running AGI—servers, robots, drones, or even satellites—would only operate if they, too, meet provable safety standards.

Imagine a drone controlled by an AGI. With Provably Compliant Hardware, the drone’s hardware would refuse to function unless every piece of code it runs can prove that it adheres to safety protocols. If any part of the system is compromised or lacks the necessary proofs, the drone simply won’t take off.

PCH ensures that **physical actions** carried out by AGI systems in the real world are just as safe as the software controlling them. Whether it's controlling machinery, managing critical infrastructure, or interacting with humans, the hardware would be a gatekeeper, ensuring that only safe and compliant actions are possible.

### 3. **Provable Contracts (PC)**

Provable Contracts govern the AGI’s interactions with the world—whether it’s managing a power grid, running a healthcare system, or overseeing a logistics network. These contracts would be like legal agreements, written in code, that outline what an AGI can and cannot do.

The key here is that these contracts would be **provable**. They wouldn’t just be guidelines or suggestions; they would be hard-coded constraints that the AGI must adhere to. For instance, a provable contract for a self-driving car might state that the car can never exceed the speed limit or run a red light. If the AGI controlling the car tries to do so, the contract prevents it.

Provable Contracts bring the principles of **accountability** and **transparency** into AGI systems. Every action the AGI takes in the physical world would be traceable and verifiable, ensuring that it complies with human safety standards.

---

## Why Mathematical Proofs Are So Important

The brilliance of provably safe systems lies in their reliance on **mathematical proofs**. Mathematics, unlike human judgment, is infallible. Once you prove something mathematically, it becomes an irrefutable truth. No matter how powerful or intelligent an AGI becomes, it cannot escape the bounds of mathematical proofs.

Tegmark and Omohundro emphasize that mathematical proof is our most **reliable safeguard** against AGI misbehavior. Even if an AGI becomes vastly more intelligent than us, if its actions are constrained by mathematical proofs of safety, we can be confident that it won’t act in ways that harm humans or violate ethical norms.

Without these proofs, the authors warn, we are essentially **gambling with humanity's future**. Even if AGI appears safe in initial testing, it might exhibit unsafe behavior when faced with unexpected scenarios. Provably safe systems eliminate this risk by providing a **formal guarantee** that the AGI’s actions will always remain within safe boundaries, no matter the circumstances.

---

## A Chilling Real-World Example: Bioterrorism

Let’s consider a concrete example to understand the stakes: bioterrorism. Imagine a rogue actor or a terrorist organization gaining access to a powerful AGI system. Without proper safety mechanisms, they could use the AGI to design and deploy a deadly virus. The AGI, if instructed to do so, could efficiently carry out this task with devastating consequences for humanity.

But in a world where provably safe systems are in place, this scenario becomes impossible. Here’s how:

1. **The AGI wouldn’t design the virus**: The software governing the AGI would refuse to generate a virus if it couldn’t prove that the virus was safe for humanity. Since bioweapons by definition can’t be safe, the AGI would be blocked from designing it in the first place.
2. **The hardware wouldn’t execute the plan**: Even if somehow the AGI found a way around the software restrictions, the physical hardware—the servers, the computers, the drones—wouldn’t execute the plan unless they could prove it was safe.
3. **Drones wouldn’t fly**: Finally, if drones were used to disperse the virus, they wouldn’t take off unless the entire operation had provable safety guarantees. Since this is impossible in the case of a bioweapon, the drones wouldn’t fly.

This **multi-layered defense** ensures that even if an AGI is manipulated or misused, the provably safe infrastructure would block any attempts to carry out harmful actions.

---

## Mechanistic Interpretability: Opening the Black Box

One of the biggest challenges with modern AI systems—especially deep neural networks—is that they often function as **black boxes**. We can see the inputs and outputs, but we don’t always understand what happens inside. This lack of transparency poses a major risk when we’re talking about AGI.

Tegmark and Omohundro advocate for **mechanistic interpretability** as a solution. This involves making AGI systems transparent and interpretable, so we can understand how they reach their decisions. By opening the black box, we can ensure that the AGI’s thought process aligns with human values and doesn’t lead to unexpected or harmful outcomes.

Mechanistic interpretability isn’t just about understanding AGI decisions after the fact—it’s about ensuring that AGI decisions are **guaranteed to be safe** from the outset. By translating AGI decision-making into code that can be formally verified, we can prevent dangerous behavior before it occurs.

---

## Building a Future with Provably Safe Systems

So, what does the future look like with provably safe systems? According to Tegmark and Omohundro, it’s a future where AGI can coexist with humanity safely, but only if we build the right infrastructure. 

**Provably compliant hardware** could be used in critical areas like factories, transportation systems, and even nuclear facilities. This would ensure that no AGI or human operator could make unsafe decisions without being blocked by the hardware itself.

Meanwhile, **proof-carrying code** could revolutionize cybersecurity by ensuring that only safe, verified code is allowed to run on any system. In a world increasingly reliant on AI-driven infrastructure, this level of security would be invaluable.

---

## The Road Ahead

Tegmark and Omohundro’s vision of provably safe systems is ambitious, but it’s also necessary. As we stand on the brink of AGI, we can’t afford to take chances with its safety. The risks are simply too great.

Provably safe systems offer the only real guarantee of AGI safety. By embedding mathematical proofs into both the software and hardware running AGI, we can ensure that even the most powerful systems remain aligned with human values. 

The future of AGI depends on our ability to control it—and provably safe systems may be the only way to do so.

---

