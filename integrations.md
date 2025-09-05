---
layout: page
title: Integrations
permalink: integrations
description: Seamless seams into MCP and orchestration frameworks—secure by construction.
---

<section class="py-6">
  <p class="text-neutral-700 dark:text-neutral-300 max-w-3xl">
    Integration seams for MCP, CI/CD, RAG, and cross‑org exchange. (Source: AGENTIC.SCENARIOS.)
  </p>

  <div class="mt-10 grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
    <div class="p-6 rounded-2xl bg-white dark:bg-neutral-900 border border-neutral-200 dark:border-neutral-800 shadow-sm">
      <h3 class="font-semibold text-lg">Tool Invocation Gates</h3>
      <ul class="mt-2 space-y-2 text-sm text-neutral-700 dark:text-neutral-300 list-disc list-inside">
        <li>Operation‑specific capabilities (args digest, route, env)</li>
        <li>Deterministic, offline validation before execution</li>
        <li>Structured JSON evidence per hop</li>
      </ul>
    </div>
    <div class="p-6 rounded-2xl bg-white dark:bg-neutral-900 border border-neutral-200 dark:border-neutral-800 shadow-sm">
      <h3 class="font-semibold text-lg">Agent‑to‑Agent Envelopes</h3>
      <ul class="mt-2 space-y-2 text-sm text-neutral-700 dark:text-neutral-300 list-disc list-inside">
        <li>Tau‑bound session tags + conversation IDs</li>
        <li>Local acceptance; replay/out‑of‑scope rejection</li>
        <li>Optional stream encryption for payloads</li>
      </ul>
    </div>
    <div class="p-6 rounded-2xl bg-white dark:bg-neutral-900 border border-neutral-200 dark:border-neutral-800 shadow-sm">
      <h3 class="font-semibold text-lg">Artifact Provenance</h3>
      <ul class="mt-2 space-y-2 text-sm text-neutral-700 dark:text-neutral-300 list-disc list-inside">
        <li>Attach provenance to models, datasets, builds</li>
        <li>Remote verification without shared secrets</li>
        <li>Cross‑system audit aggregation</li>
      </ul>
    </div>
  </div>

  <div class="mt-10 grid md:grid-cols-2 gap-6">
    <div class="p-6 rounded-2xl bg-white dark:bg-neutral-900 border border-neutral-200 dark:border-neutral-800 shadow-sm">
      <h4 class="font-semibold">Recipes</h4>
      <ul class="mt-2 space-y-2 text-sm text-neutral-700 dark:text-neutral-300 list-disc list-inside">
        <li>MCP broker: validate capability before tool dispatch</li>
        <li>RAG: bind dataset ID + prompt digest to retrieve/publish</li>
        <li>CI/CD: gate promotions by change_id + environment</li>
      </ul>
    </div>
    <div class="p-6 rounded-2xl bg-white dark:bg-neutral-900 border border-neutral-200 dark:border-neutral-800 shadow-sm">
      <h4 class="font-semibold">JSON example</h4>
      <pre class="mt-2 text-xs bg-neutral-50 dark:bg-neutral-950 p-3 rounded-xl overflow-x-auto">{
  "route": "tool.deploy",
  "env": "staging",
  "args_sha256": "...",
  "change_id": "chg_12345",
  "expiry": "2025-09-05T12:34:56Z",
  "pool_id": "pool:prod"
}</pre>
    </div>
  </div>
</section>


