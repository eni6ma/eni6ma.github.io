---
layout: page
title: Use Cases
permalink: use-cases
description: Engineered for CI/CD, finance, critical infrastructure, and mixed‑initiative workflows.
---

<section class="py-6">
  <p class="text-neutral-700 dark:text-neutral-300 max-w-3xl">
    Selected applications from the scenario catalog and whitepapers. (Sources: THE NEW ERA…, AGENTIC.SCENARIOS.)
  </p>

  <div class="mt-10 grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
    <div class="p-6 rounded-2xl bg-white dark:bg-neutral-900 border border-neutral-200 dark:border-neutral-800 shadow-sm">
      <h3 class="font-semibold text-lg">Production Change Approvals</h3>
      <p class="mt-2 text-sm text-neutral-700 dark:text-neutral-300">Gate rollouts with capabilities bound to change_id, env, and version; verify offline and log for audit.</p>
    </div>
    <div class="p-6 rounded-2xl bg-white dark:bg-neutral-900 border border-neutral-200 dark:border-neutral-800 shadow-sm">
      <h3 class="font-semibold text-lg">Finance Ops & Audit Trails</h3>
      <p class="mt-2 text-sm text-neutral-700 dark:text-neutral-300">Bind transfers/updates to deterministic tokens; branch offices validate locally, auditors replay centrally.</p>
    </div>
    <div class="p-6 rounded-2xl bg-white dark:bg-neutral-900 border border-neutral-200 dark:border-neutral-800 shadow-sm">
      <h3 class="font-semibold text-lg">Safety Overrides (OT/ICS)</h3>
      <p class="mt-2 text-sm text-neutral-700 dark:text-neutral-300">Scoped override tokens validated on‑unit; irreversible logs for incident review.</p>
    </div>
    <div class="p-6 rounded-2xl bg-white dark:bg-neutral-900 border border-neutral-200 dark:border-neutral-800 shadow-sm">
      <h3 class="font-semibold text-lg">Customer Support Escalations</h3>
      <p class="mt-2 text-sm text-neutral-700 dark:text-neutral-300">Human witness (ticket/route) plus operation metadata to secure sensitive actions.</p>
    </div>
    <div class="p-6 rounded-2xl bg-white dark:bg-neutral-900 border border-neutral-200 dark:border-neutral-800 shadow-sm">
      <h3 class="font-semibold text-lg">Model Governance & Data Lineage</h3>
      <p class="mt-2 text-sm text-neutral-700 dark:text-neutral-300">Attach provenance to training runs/outputs; deterministic replay for investigations.</p>
    </div>
    <div class="p-6 rounded-2xl bg-white dark:bg-neutral-900 border border-neutral-200 dark:border-neutral-800 shadow-sm">
      <h3 class="font-semibold text-lg">Edge & Air‑Gapped Operations</h3>
      <p class="mt-2 text-sm text-neutral-700 dark:text-neutral-300">Local, stateless validation for updates and sensitive steps—no central authority required.</p>
    </div>
  </div>

  <div class="mt-10 grid md:grid-cols-2 gap-6">
    <div class="p-6 rounded-2xl bg-white dark:bg-neutral-900 border border-neutral-200 dark:border-neutral-800 shadow-sm">
      <h4 class="font-semibold">Agentic patterns</h4>
      <ul class="mt-2 space-y-2 text-sm text-neutral-700 dark:text-neutral-300 list-disc list-inside">
        <li>Scoped capability per hop (plan → tool → review)</li>
        <li>Tau‑tuned windows for rapid loops</li>
        <li>Payload evidence for reproducible audits</li>
      </ul>
    </div>
    <div class="p-6 rounded-2xl bg-white dark:bg-neutral-900 border border-neutral-200 dark:border-neutral-800 shadow-sm">
      <h4 class="font-semibold">Example witness (capability)</h4>
      <pre class="mt-2 text-xs bg-neutral-50 dark:bg-neutral-950 p-3 rounded-xl overflow-x-auto">{
  "route": "rag.retrieve",
  "dataset_id": "ds_prod_001",
  "prompt_sha256": "...",
  "top_k": 8,
  "expiry": "2025-09-05T12:34:56Z"
}</pre>
    </div>
  </div>
</section>



