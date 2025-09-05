---
layout: page
title: Technology
permalink: technology
description: A compact, modular stack that drops into CLIs, gateways, and control‑plane agents.
---

<section class="py-6">
  <p class="text-neutral-700 dark:text-neutral-300 max-w-3xl">
    Core architecture and math cues from the USER.EXPLAINER and HOLOGRAPHIC docs.
  </p>

  <div class="mt-10 grid lg:grid-cols-2 gap-10 items-center">
    <div class="p-6 rounded-2xl bg-white dark:bg-neutral-900 border border-neutral-200 dark:border-neutral-800 shadow-sm">
      <h3 class="font-semibold text-lg">At a glance</h3>
      <ul class="mt-2 space-y-2 text-sm text-neutral-700 dark:text-neutral-300 list-disc list-inside">
        <li>Embedded prime (π) + encrypted entropy pool (ε)</li>
        <li>Time parameter (τ) drives per‑session freshness</li>
        <li>Deterministic ε–τ–π derivations → (Q,R,S) coordinates</li>
        <li>Index‑recoverable row hashes; integrity tags for batches</li>
        <li>Two‑way hash stream (BLAKE3‑XOF) for confidentiality</li>
      </ul>
    </div>

    <div class="relative">
      <div class="absolute -inset-4 bg-gradient-to-tr from-indigo-200/50 to-transparent dark:from-indigo-500/20 rounded-3xl blur"></div>
      <div class="relative p-6 rounded-3xl bg-white dark:bg-neutral-900 border border-neutral-200 dark:border-neutral-800 shadow-xl">
        <div class="text-xs uppercase font-semibold text-indigo-600 dark:text-indigo-400">ε–τ–π pipeline</div>
        <div class="mt-3 grid grid-cols-3 gap-3 text-sm">
          <div class="p-4 rounded-xl border border-neutral-200 dark:border-neutral-800"><div class="font-medium">Entropy Pool</div><div class="text-neutral-600 dark:text-neutral-400 mt-1">Encrypted, binary‑bound</div></div>
          <div class="p-4 rounded-xl border border-neutral-200 dark:border-neutral-800"><div class="font-medium">Derivations</div><div class="text-neutral-600 dark:text-neutral-400 mt-1">(Q,R,S) from ε–τ–π</div></div>
          <div class="p-4 rounded-xl border border-neutral-200 dark:border-neutral-800"><div class="font-medium">Verifier</div><div class="text-neutral-600 dark:text-neutral-400 mt-1">Stateless, offline</div></div>
          <div class="p-4 rounded-xl border border-neutral-200 dark:border-neutral-800"><div class="font-medium">Tool Gates</div><div class="text-neutral-600 dark:text-neutral-400 mt-1">Capability checks</div></div>
          <div class="p-4 rounded-xl border border-neutral-200 dark:border-neutral-800"><div class="font-medium">Agent Envelopes</div><div class="text-neutral-600 dark:text-neutral-400 mt-1">Tau‑bound</div></div>
          <div class="p-4 rounded-xl border border-neutral-200 dark:border-neutral-800"><div class="font-medium">Provenance</div><div class="text-neutral-600 dark:text-neutral-400 mt-1">Audit transcripts</div></div>
        </div>
      </div>
    </div>
  </div>

  <div class="mt-10 grid md:grid-cols-2 gap-6">
    <div class="p-6 rounded-2xl bg-white dark:bg-neutral-900 border border-neutral-200 dark:border-neutral-800 shadow-sm">
      <h4 class="font-semibold">Deterministic verification</h4>
      <p class="mt-2 text-sm text-neutral-700 dark:text-neutral-300">Verifiers re‑derive rows and recover indices from row hashes; acceptance reduces to positional membership checks with O(1) verifier state.</p>
    </div>
    <div class="p-6 rounded-2xl bg-white dark:bg-neutral-900 border border-neutral-200 dark:border-neutral-800 shadow-sm">
      <h4 class="font-semibold">Human‑operable layer</h4>
      <p class="mt-2 text-sm text-neutral-700 dark:text-neutral-300">Interactive proofs map symbols→zones (color layer) without entering cryptographic derivations; transcripts remain reproducible and auditable.</p>
    </div>
  </div>
</section>



