---
layout: page
title: Security
permalink: security
description: Deepfake‑resistant, replay‑proof authorization without centralized PKI drag.
---

<section class="py-6">
  <p class="text-neutral-700 dark:text-neutral-300 max-w-3xl">
    Security principles from the whitepapers: capability over identity, stateless offline verification, index‑recoverable commitments, and binary↔pool binding. (Sources: THE NEW ERA…, USER.EXPLAINER, HOLOGRAPHIC.)
  </p>

  <div class="mt-10 grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
    <div class="p-6 rounded-2xl bg-white dark:bg-neutral-900 border border-neutral-200 dark:border-neutral-800 shadow-sm">
      <h3 class="font-semibold text-lg">Self‑Authenticating Operations</h3>
      <p class="mt-2 text-sm text-neutral-700 dark:text-neutral-300">Each operation carries a scoped capability token tied to tau (time), context, and pool‑backed entropy.</p>
    </div>
    <div class="p-6 rounded-2xl bg-white dark:bg-neutral-900 border border-neutral-200 dark:border-neutral-800 shadow-sm">
      <h3 class="font-semibold text-lg">Replay & Deepfake Resistance</h3>
      <p class="mt-2 text-sm text-neutral-700 dark:text-neutral-300">Tau windows and context binding prevent reuse; transcripts yield verifiable liveness and scope.</p>
    </div>
    <div class="p-6 rounded-2xl bg-white dark:bg-neutral-900 border border-neutral-200 dark:border-neutral-800 shadow-sm">
      <h3 class="font-semibold text-lg">Index‑Recoverable Commitments</h3>
      <p class="mt-2 text-sm text-neutral-700 dark:text-neutral-300">Row hashes allow authorized verifiers to recover indices by enumeration; outsiders learn nothing useful.</p>
    </div>
    <div class="p-6 rounded-2xl bg-white dark:bg-neutral-900 border border-neutral-200 dark:border-neutral-800 shadow-sm">
      <h3 class="font-semibold text-lg">No Keys at Rest</h3>
      <p class="mt-2 text-sm text-neutral-700 dark:text-neutral-300">Eliminate static credentials; capabilities are short‑lived and scoped to one action.</p>
    </div>
    <div class="p-6 rounded-2xl bg-white dark:bg-neutral-900 border border-neutral-200 dark:border-neutral-800 shadow-sm">
      <h3 class="font-semibold text-lg">Air‑gapped & Edge Ready</h3>
      <p class="mt-2 text-sm text-neutral-700 dark:text-neutral-300">Verification is deterministic and local; no dependency on online authorities at check time.</p>
    </div>
    <div class="p-6 rounded-2xl bg-white dark:bg-neutral-900 border border-neutral-200 dark:border-neutral-800 shadow-sm">
      <h3 class="font-semibold text-lg">Tamper‑Evident Evidence</h3>
      <p class="mt-2 text-sm text-neutral-700 dark:text-neutral-300">Compact transcripts and integrity hashes provide portable, immutable audit artifacts.</p>
    </div>
  </div>

  <div class="mt-10 grid md:grid-cols-2 gap-6">
    <div class="p-6 rounded-2xl bg-white dark:bg-neutral-900 border border-neutral-200 dark:border-neutral-800 shadow-sm">
      <h4 class="font-semibold">Threats addressed</h4>
      <ul class="mt-2 space-y-2 text-sm text-neutral-700 dark:text-neutral-300 list-disc list-inside">
        <li>Deepfakes and session replay</li>
        <li>Key theft and lateral movement</li>
        <li>Supply‑chain swaps (binary or pool)</li>
        <li>Cross‑org verification without shared secrets</li>
      </ul>
    </div>
    <div class="p-6 rounded-2xl bg-white dark:bg-neutral-900 border border-neutral-200 dark:border-neutral-800 shadow-sm">
      <h4 class="font-semibold">Guarantees</h4>
      <ul class="mt-2 space-y-2 text-sm text-neutral-700 dark:text-neutral-300 list-disc list-inside">
        <li>Deterministic, offline validation in milliseconds</li>
        <li>Scope‑ and time‑bound authorization (tau windows)</li>
        <li>Portable, verifiable transcripts for audits</li>
        <li>Stateless verification; zero long‑lived keys</li>
      </ul>
    </div>
  </div>
</section>



