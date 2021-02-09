# The Robust-First Computing Guide

## Introduction

So you want to know about robust-first computing? Well there's a lot to unpack, and depending on your background you may want to adopt a "choose your own adventure" mindset for taking in the information you can find here.

Robust-first computing is centered around the core idea that there's a non-deterministic computational stack to build that, in the long-run, would serve humanity better than the traditional, correct-and-efficient-only, deterministic, centralized processor-based systems we have been boxed into since the dawn of the computing age.


# Serial Determinism vs Living Computation

## Serial Determinism

The traditional approach to computing is called serial determinism: The machine operates sequentially, doing one thing at a time, step by step by step (serial) — and the output of each step is absolutely determined by the state of the machine when the step began (deterministic).

Machines using serial determinism are easy to reason about and they have been a remarkable, world-changing success in the marketplace, but they ultimately scale poorly and offer poor security.

## An alternative: Living Computation

There are other ways to compute, that offer different — and perhaps more attractive — tradeoffs, but which as yet have received scant research and development attention. While serial deterministic machines were growing by leaps and bounds, that was understandable, but now those traditional architectures are increasingly struggling to grow further.

Viewed as a kind of computer, note how different a living organism is compared to a serial deterministic machine. Deterministic machines are 100% completely repeatable – from the same inputs will come the exact same outputs — while living organisms rarely do anything the exact same way twice. Deterministic machines will crash, seize-up, or otherwise misbehave when virtually anything goes wrong inside them; living organisms, by contrast, can suffer grievous injury and yet survive, handle the immediate situation, and get away long enough to heal up and live on.



# Hardware Determinism vs. Indefinite Scalability

## Hardware determinism

Despite wide awareness that current computer systems suffer from dwindling scalability and declining securability, the entrenched architectural choice underlying both problems—the stipulation of hardware determinism—is rarely reconsidered.

In the traditional approach to digital computing, the physical hardware is required to be deterministic: The machine is to operate in clearly-defined discrete steps, and the state of the machine (the values of all its 'bits' collectively) after a step is absolutely and completely determined by the state of the machine when the step began. In the agreement between hardware and software, the hardware is not allowed to produce any surprises or unanticipated conditions: nothing misread or misstated, no oopsies or booboos or broken alarm clocks, no excuses of any kind. If hardware can't perform its duties perfectly, for whatever reason, its final obligation is to kill itself: to crash and “end the world”, rather than produce a wrong answer.

Deterministic hardware makes the programmer's job much easier, and it has been a remarkable, world-changing success in the marketplace, but it ultimately scales poorly and offers poor security. However, since hardware determinism now underpins so many other computational design decisions, incremental attempts to move beyond determinism, historically, have struggled to gain traction.

## Indefinite scalability

Any individual computing device is a finite machine, both in physical size and in computational capacity. But 'finite' doesn't mean 'isolated': To be useful, a finite machine has external connections, at least for power and communications. We define an indefinitely scalable machine to be any procedure for tiling space with finite machines, with no a priori requirements that such a tiling have any particular properties—like aligning tile outputs with adjacent inputs. So tiling space by, say, laying HP65 pocket calculators out in a grid is admissible as an indefinitely scalable machine — it will just prove not to be a very good one, once we start defining metrics on indefinitely scalable machines.