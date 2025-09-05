---
layout: page
title: Integrations
permalink: integrations
description: Seamless seams into MCP and orchestration frameworks—secure by construction.
---

<section class="py-6 text-base-content">


  <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
    <div class="card bg-primary/20 backdrop-blur-sm shadow-xl">
      <div class="card-body">
        <h3 class="card-title text-base-content">Tool Invocation Gates</h3>
        <ul class="space-y-2 text-base-content list-disc list-inside">
          <li>Operation‑specific capabilities (args digest, route, env)</li>
          <li>Deterministic, offline validation before execution</li>
          <li>Structured JSON evidence per hop</li>
        </ul>
      </div>
    </div>
    <div class="card bg-success/20 backdrop-blur-sm shadow-xl">
      <div class="card-body">
        <h3 class="card-title text-base-content">Agent‑to‑Agent Envelopes</h3>
        <ul class="space-y-2 text-base-content list-disc list-inside">
          <li>Tau‑bound session tags + conversation IDs</li>
          <li>Local acceptance; replay/out‑of‑scope rejection</li>
          <li>Optional stream encryption for payloads</li>
        </ul>
      </div>
    </div>
    <div class="card bg-info/20 backdrop-blur-sm shadow-xl">
      <div class="card-body">
        <h3 class="card-title text-base-content">Artifact Provenance</h3>
        <ul class="space-y-2 text-base-content list-disc list-inside">
          <li>Attach provenance to models, datasets, builds</li>
          <li>Remote verification without shared secrets</li>
          <li>Cross‑system audit aggregation</li>
        </ul>
      </div>
    </div>
  </div>

  <div class="mt-10 grid md:grid-cols-2 gap-6">
    <div class="card bg-warning/20 backdrop-blur-sm shadow-xl">
      <div class="card-body">
        <h4 class="card-title text-base-content">Recipes</h4>
        <ul class="space-y-2 text-base-content list-disc list-inside">
          <li>MCP broker: validate capability before tool dispatch</li>
          <li>RAG: bind dataset ID + prompt digest to retrieve/publish</li>
          <li>CI/CD: gate promotions by change_id + environment</li>
        </ul>
      </div>
    </div>
    <div class="card bg-secondary/20 backdrop-blur-sm shadow-xl">
      <div class="card-body">
        <h4 class="card-title text-base-content">JSON example</h4>
        <pre class="mt-2 text-xs bg-base-200 text-base-content p-3 rounded-xl overflow-x-auto">{
  "route": "tool.deploy",
  "env": "staging",
  "args_sha256": "...",
  "change_id": "chg_12345",
  "expiry": "2025-09-05T12:34:56Z",
  "pool_id": "pool:prod"
}</pre>
      </div>
    </div>
  </div>
</section>


