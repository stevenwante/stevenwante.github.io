---
layout: post
title:  "Quantum Computing - Marking the end of Diffie-Hellman?"
date:   2015-11-12 15:27:30
description: Just a sample post to show some of the typography elements supported from harmony theme.
categories:
- blog
permalink: 2015-11-12-quantum-computing-diffie-hellman
---

There’s a very interesting, but also very strange, world out there. A world where nothing makes much logical sense. A world where everything is everywhere and nowhere at the same time. This world, of course, is the Quantum world. Quantum Mechanics is a way for scientists describe what happens at the smallest scale in the universe. In this very complex world, events take place that baffle even the brightest theoretical physicists. A bit is no longer one OR zero, it’s one AND zero. This is the fundamental reason why Quantum Computing could mark the end of Diffie-Hellman.

Diffie-Hellman relies on discrete logarithms, and it’s widely accepted that there are no efficient methods for computing discrete logarithm on a conventional computer. However, quantum computers are not conventional computers, as they are based on the quantum equivalent of the bit, called the qubit. A qubit can be in a superposition, meaning it can also be in a state of one AND zero. With Shor’s algorithm, a quantum algorithm, you can harness the power of quantum computing to attack a discrete logarithm in a much shorter amount of time than a conventional computer. This could cause trouble for the underlying security standard of the internet today, SSL/TLS, as it uses a form of Diffie-Hellman to create the secret key between two parties.

What does this mean for the future? Well, quantum computers aren’t quite powerful enough to sufficiently attack the current most popular public-key algorithms. But some of the brightest cryptographers in world realize this is a very real threat and are working on post quantum cryptography. Post quantum cryptography are algorithms specifically engineered to be resistant to the threat that quantum computers pose. 
