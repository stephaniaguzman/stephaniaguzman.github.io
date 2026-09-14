---
layout: post
title: "What breaks when you put a language model inside an enterprise integration"
date: 2026-09-13
---

Most writing about language models assumes a chat window. Production
integrations are a different environment: the caller is a system, the
output feeds another system, and nobody is there to re-read a bad answer.

Here is what actually breaks.

## 1. Non-determinism meets contracts

*(qué esperaba el sistema, qué llegó, qué se rompió)*

## 2. Latency budgets

*(cuánto tarda, con qué presupuesto contaba la integración)*

## 3. Failure modes nobody catches

*(el caso en que el modelo responde algo plausible y equivocado)*

## What I would do differently

*(dos o tres conclusiones concretas)*
