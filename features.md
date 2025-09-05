---
layout: page
title: Features
permalink: features
description: Capability‑based trust that scales with agentic operations and workflows.
---

<section class="py-6">
  <div class="max-w-3xl mx-auto mb-10">
    <div class="alert alert-info">
      <span>ENI6MA flips trust from identity to action. Short‑lived, operation‑specific capabilities validate deterministically and offline, yielding portable evidence for humans and agents. (See: THE NEW ERA…, USER.EXPLAINER, AGENT.USER README.)</span>
    </div>
  </div>

  <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
    <div class="card bg-base-100/20 backdrop-blur-sm shadow-xl">
      <div class="card-body">
        <h3 class="card-title text-white">Capability over Identity</h3>
        <p class="text-white text-sm sm:text-base">Replace long‑lived credentials with narrow, short‑lived capabilities scoped to a single action.</p>
      </div>
    </div>
    <div class="card bg-base-100/20 backdrop-blur-sm shadow-xl">
      <div class="card-body">
        <h3 class="card-title text-white">Stateless, Offline Verification</h3>
        <p class="text-white text-sm sm:text-base">Local, deterministic checks—no central PKI ceremony, ideal for air‑gapped and edge environments.</p>
      </div>
    </div>
    <div class="card bg-base-100/20 backdrop-blur-sm shadow-xl">
      <div class="card-body">
        <h3 class="card-title text-white">Index‑Recoverable Commitments</h3>
        <p class="text-white text-sm sm:text-base">Nonce/row hashes let verifiers recover pool indices by enumeration without disclosure in transcripts.</p>
      </div>
    </div>
    <div class="card bg-base-100/20 backdrop-blur-sm shadow-xl">
      <div class="card-body">
        <h3 class="card-title text-white">Binary↔Pool Binding</h3>
        <p class="text-white text-sm sm:text-base">Encrypted entropy pools bind to the intended binary, surfacing silent swaps and tampering.</p>
      </div>
    </div>
    <div class="card bg-base-100/20 backdrop-blur-sm shadow-xl">
      <div class="card-body">
        <h3 class="card-title text-white">Deepfake & Replay Resilience</h3>
        <p class="text-white text-sm sm:text-base">Tau‑bound freshness and context binding block reuse outside narrow windows and scope.</p>
      </div>
    </div>
    <div class="card bg-base-100/20 backdrop-blur-sm shadow-xl">
      <div class="card-body">
        <h3 class="card-title text-white">Deterministic, Portable Evidence</h3>
        <p class="text-white text-sm sm:text-base">Every accepted operation yields compact, reproducible transcripts for audit and forensics.</p>
      </div>
    </div>
    <div class="card bg-base-100/20 backdrop-blur-sm shadow-xl">
      <div class="card-body">
        <h3 class="card-title text-white">Human‑in‑the‑Loop Proofs</h3>
        <p class="text-white text-sm sm:text-base">Interactive liveness captures witness strings (ticket, route) for staged approvals.</p>
      </div>
    </div>
    <div class="card bg-base-100/20 backdrop-blur-sm shadow-xl">
      <div class="card-body">
        <h3 class="card-title text-white">MCP & Tool Broker Gates</h3>
        <p class="text-white text-sm sm:text-base">Attach capabilities to tool calls, agent envelopes, and artifacts—validate before execution.</p>
      </div>
    </div>
    <div class="card bg-base-100/20 backdrop-blur-sm shadow-xl">
      <div class="card-body">
        <h3 class="card-title text-white">Two‑Way Hash Stream</h3>
        <p class="text-white text-sm sm:text-base">Fast BLAKE3‑XOF keystream for local confidentiality of caches, transcripts, and IPC.</p>
      </div>
    </div>
  </div>
</section>

<section class="py-6">
  <div class="max-w-3xl mx-auto mb-10">
    <div class="alert alert-info">
      <span>ENI6MA provides a practical security layer for agentic AI systems, emphasizing short-lived capability proofs, binary↔pool binding, and high-speed streaming protection with minimal ceremony.</span>
    </div>
  </div>

  <h2 class="text-2xl font-bold text-white mb-6 flex items-center">
    <svg class="w-6 h-6 mr-3 text-primary" fill="none" stroke="currentColor" viewBox="0 0 24 24">
      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path>
    </svg>
    Agentic AI & MCP Features
  </h2>

  <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-6 mb-12">
    <div class="card bg-base-100/20 backdrop-blur-sm shadow-xl">
      <div class="card-body">
        <h3 class="card-title text-white flex items-center">
          <svg class="w-5 h-5 mr-2 text-primary" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z"></path>
          </svg>
          Scoped Capability Per Hop
        </h3>
        <p class="text-white text-sm sm:text-base">Mint new capability nonces for each hop in multi-step agent flows (plan → tool → review), bound to precise route and arguments digest.</p>
      </div>
    </div>

    <div class="card bg-base-100/20 backdrop-blur-sm shadow-xl">
      <div class="card-body">
        <h3 class="card-title text-white flex items-center">
          <svg class="w-5 h-5 mr-2 text-primary" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path>
          </svg>
          Witness-Encoded Intent
        </h3>
        <p class="text-white text-sm sm:text-base">Include tool name, route, resource identifiers, and args/prompt digests in witness strings for auditable agent actions.</p>
      </div>
    </div>

    <div class="card bg-base-100/20 backdrop-blur-sm shadow-xl">
      <div class="card-body">
        <h3 class="card-title text-white flex items-center">
          <svg class="w-5 h-5 mr-2 text-primary" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"></path>
          </svg>
          Tau-Tuned Windows
        </h3>
        <p class="text-white text-sm sm:text-base">Short tau windows calibrated to planner/actor cadence; regenerate capabilities on each iteration for rapid agent loops.</p>
      </div>
    </div>

    <div class="card bg-base-100/20 backdrop-blur-sm shadow-xl">
      <div class="card-body">
        <h3 class="card-title text-white flex items-center">
          <svg class="w-5 h-5 mr-2 text-primary" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path>
          </svg>
          Stream-Encrypted Channels
        </h3>
        <p class="text-white text-sm sm:text-base">Use two-way stream engine for transient buffers and inter-agent message buses with capability payloads attached.</p>
      </div>
    </div>

    <div class="card bg-base-100/20 backdrop-blur-sm shadow-xl">
      <div class="card-body">
        <h3 class="card-title text-white flex items-center">
          <svg class="w-5 h-5 mr-2 text-primary" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"></path>
          </svg>
          Preflight Validation
        </h3>
        <p class="text-white text-sm sm:text-base">Validate capability payloads offline before releasing tool calls; deny if out-of-scope or expired for cheap prevention.</p>
      </div>
    </div>

    <div class="card bg-base-100/20 backdrop-blur-sm shadow-xl">
      <div class="card-body">
        <h3 class="card-title text-white flex items-center">
          <svg class="w-5 h-5 mr-2 text-primary" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 4.354a4 4 0 110 5.292M15 21H3v-1a6 6 0 0112 0v1zm0 0h6v-1a6 6 0 00-9-5.197m13.5-9a2.5 2.5 0 11-5 0 2.5 2.5 0 015 0z"></path>
          </svg>
          Human-in-the-Loop Checkpoints
        </h3>
        <p class="text-white text-sm sm:text-base">Interactive proof captures ticket/route and short tau; attach serialized payload to agent's plan for deterministic validation.</p>
      </div>
    </div>

    <div class="card bg-base-100/20 backdrop-blur-sm shadow-xl">
      <div class="card-body">
        <h3 class="card-title text-white flex items-center">
          <svg class="w-5 h-5 mr-2 text-primary" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 11H5m14 0a2 2 0 012 2v6a2 2 0 01-2 2H5a2 2 0 01-2-2v-6a2 2 0 012-2m14 0V9a2 2 0 00-2-2M5 11V9a2 2 0 012-2m0 0V5a2 2 0 012-2h6a2 2 0 012 2v2M7 7h10"></path>
          </svg>
          Composite Workflow Bundles
        </h3>
        <p class="text-white text-sm sm:text-base">Bundle minimal set of scoped capabilities (each one-hop) with explicit routes; deny escalation or reuse for least privilege.</p>
      </div>
    </div>

    <div class="card bg-base-100/20 backdrop-blur-sm shadow-xl">
      <div class="card-body">
        <h3 class="card-title text-white flex items-center">
          <svg class="w-5 h-5 mr-2 text-primary" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7h12m0 0l-4-4m4 4l-4 4m0 6H4m0 0l4 4m-4-4l4-4"></path>
          </svg>
          Delegation with Narrowing
        </h3>
        <p class="text-white text-sm sm:text-base">Broker issues fresh, narrower capabilities per child's task (route/resource restriction, tighter tau) to avoid reusing orchestrator authority.</p>
      </div>
    </div>

    <div class="card bg-base-100/20 backdrop-blur-sm shadow-xl">
      <div class="card-body">
        <h3 class="card-title text-white flex items-center">
          <svg class="w-5 h-5 mr-2 text-primary" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 3v2m6-2v2M9 19v2m6-2v2M5 9H3m2 6H3m18-6h-2m2 6h-2M7 19h10a2 2 0 002-2V7a2 2 0 00-2-2H7a2 2 0 00-2 2v10a2 2 0 002 2zM9 9h6v6H9V9z"></path>
          </svg>
          Edge & Air-Gapped Operations
        </h3>
        <p class="text-white text-sm sm:text-base">Local, stateless validation for updates and sensitive steps—no central authority required for offline-capable operations.</p>
      </div>
    </div>
  </div>

  <div class="bg-base-100/10 rounded-lg p-6">
    <h3 class="text-lg font-semibold text-white mb-4 flex items-center">
      <svg class="w-5 h-5 mr-2 text-primary" fill="none" stroke="currentColor" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path>
      </svg>
      Agentic Integration Benefits
    </h3>
    <div class="grid md:grid-cols-2 gap-4">
      <div>
        <h4 class="font-semibold text-white mb-2">MCP Tool Broker Gates</h4>
        <p class="text-white text-sm">Attach capabilities to tool calls, agent envelopes, and artifacts—validate before execution. Prevents privilege bleed-through in multi-step agent flows.</p>
      </div>
      <div>
        <h4 class="font-semibold text-white mb-2">RAG Pipeline Guardrails</h4>
        <p class="text-white text-sm">Gate retrieval and publish steps with capabilities bound to dataset IDs and prompt/args digests; encrypt transient embeddings and caches.</p>
      </div>
      <div>
        <h4 class="font-semibold text-white mb-2">Autonomous PR Workflow</h4>
        <p class="text-white text-sm">Per-PR capabilities allow formatting, test updates, or limited file edits; reviewers validate proofs attached to PR metadata.</p>
      </div>
      <div>
        <h4 class="font-semibold text-white mb-2">Agent Marketplace Governance</h4>
        <p class="text-white text-sm">Third-party tools operate only with capability nonces per privileged API; immediate revoke by policy without rotating keys.</p>
      </div>
    </div>
  </div>
</section>


