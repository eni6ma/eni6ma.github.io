---
layout: page
title: Security
permalink: security
description: Deepfake‑resistant, replay‑proof authorization without centralized PKI drag.
---

<section class="py-6">
  <div class="max-w-3xl mx-auto mb-10">
    <div class="alert alert-warning">
      <span>Security principles from the whitepapers: capability over identity, stateless offline verification, index‑recoverable commitments, and binary↔pool binding. (Sources: THE NEW ERA…, USER.EXPLAINER, HOLOGRAPHIC.)</span>
    </div>
  </div>

  <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
    <div class="card bg-error/20 backdrop-blur-sm shadow-xl">
      <div class="card-body">
        <h3 class="card-title text-white">Self‑Authenticating Operations</h3>
        <p class="text-white text-sm sm:text-base">Each operation carries a scoped capability token tied to tau (time), context, and pool‑backed entropy.</p>
      </div>
    </div>
    <div class="card bg-error/20 backdrop-blur-sm shadow-xl">
      <div class="card-body">
        <h3 class="card-title text-white">Replay & Deepfake Resistance</h3>
        <p class="text-white text-sm sm:text-base">Tau windows and context binding prevent reuse; transcripts yield verifiable liveness and scope.</p>
      </div>
    </div>
    <div class="card bg-error/20 backdrop-blur-sm shadow-xl">
      <div class="card-body">
        <h3 class="card-title text-white">Index‑Recoverable Commitments</h3>
        <p class="text-white text-sm sm:text-base">Row hashes allow authorized verifiers to recover indices by enumeration; outsiders learn nothing useful.</p>
      </div>
    </div>
    <div class="card bg-success/20 backdrop-blur-sm shadow-xl">
      <div class="card-body">
        <h3 class="card-title text-white">No Keys at Rest</h3>
        <p class="text-white text-sm sm:text-base">Eliminate static credentials; capabilities are short‑lived and scoped to one action.</p>
      </div>
    </div>
    <div class="card bg-success/20 backdrop-blur-sm shadow-xl">
      <div class="card-body">
        <h3 class="card-title text-white">Air‑gapped & Edge Ready</h3>
        <p class="text-white text-sm sm:text-base">Verification is deterministic and local; no dependency on online authorities at check time.</p>
      </div>
    </div>
    <div class="card bg-success/20 backdrop-blur-sm shadow-xl">
      <div class="card-body">
        <h3 class="card-title text-white">Tamper‑Evident Evidence</h3>
        <p class="text-white text-sm sm:text-base">Compact transcripts and integrity hashes provide portable, immutable audit artifacts.</p>
      </div>
    </div>
  </div>

  <div class="mt-10 grid md:grid-cols-2 gap-6">
    <div class="card bg-base-100 shadow-xl">
      <div class="card-body">
        <h4 class="card-title text-error">Threats addressed</h4>
        <ul class="space-y-2 list-disc list-inside">
          <li>Deepfakes and session replay</li>
          <li>Key theft and lateral movement</li>
          <li>Supply‑chain swaps (binary or pool)</li>
          <li>Cross‑org verification without shared secrets</li>
        </ul>
      </div>
    </div>
    <div class="card bg-base-100 shadow-xl">
      <div class="card-body">
        <h4 class="card-title text-success">Guarantees</h4>
        <ul class="space-y-2 list-disc list-inside">
          <li>Deterministic, offline validation in milliseconds</li>
          <li>Scope‑ and time‑bound authorization (tau windows)</li>
          <li>Portable, verifiable transcripts for audits</li>
          <li>Stateless verification; zero long‑lived keys</li>
        </ul>
      </div>
    </div>
  </div>
</section>



