---
layout: page
title: FAQ
permalink: faq
description: Answers to common questions about ENI6MA.
---

<section class="py-6 text-base-content">
  <div class="max-w-3xl mx-auto">
    <div class="space-y-4">
      <div class="collapse collapse-arrow bg-base-100/20 backdrop-blur-sm shadow-xl">
        <input type="radio" name="faq-accordion" />
        <div class="collapse-title text-lg font-medium text-base-content">
          Does ENI6MA replace identity or PKI?
        </div>
        <div class="collapse-content">
          <p class="text-base-content">ENI6MA shifts authorization from identity to scoped capability. It can complement or replace PKI ceremonies for many action‑level checks by validating capabilities deterministically and offline.</p>
        </div>
      </div>

      <div class="collapse collapse-arrow bg-base-100/20 backdrop-blur-sm shadow-xl">
        <input type="radio" name="faq-accordion" />
        <div class="collapse-title text-lg font-medium text-base-content">
          How are tokens revoked or rotated?
        </div>
        <div class="collapse-content">
          <p class="text-base-content">Capabilities are short‑lived and bound to tau (time) and context, minimizing the need for explicit revocation. Policy can enforce tight windows and scope, and audits reconstruct decisions from transcripts.</p>
        </div>
      </div>

      <div class="collapse collapse-arrow bg-base-100/20 backdrop-blur-sm shadow-xl">
        <input type="radio" name="faq-accordion" />
        <div class="collapse-title text-lg font-medium text-base-content">
          Can it run offline or in air‑gapped modes?
        </div>
        <div class="collapse-content">
          <p class="text-base-content">Yes. Verification is stateless and local; authorized verifiers re‑derive and check commitments without contacting a central authority.</p>
        </div>
      </div>

      <div class="collapse collapse-arrow bg-base-100/20 backdrop-blur-sm shadow-xl">
        <input type="radio" name="faq-accordion" />
        <div class="collapse-title text-lg font-medium text-base-content">
          What about deepfakes and replay?
        </div>
        <div class="collapse-content">
          <p class="text-base-content">Tau windows and context binding prevent reuse; interactive proofs can bind human witness evidence to scope, yielding portable, verifiable transcripts.</p>
        </div>
      </div>

      <div class="collapse collapse-arrow bg-base-100/20 backdrop-blur-sm shadow-xl">
        <input type="radio" name="faq-accordion" />
        <div class="collapse-title text-lg font-medium text-base-content">
          How fast is verification?
        </div>
        <div class="collapse-content">
          <p class="text-base-content">Local checks run in milliseconds with O(1) verifier state. There are no online round‑trips in the critical path.</p>
        </div>
      </div>

      <div class="collapse collapse-arrow bg-base-100/20 backdrop-blur-sm shadow-xl">
        <input type="radio" name="faq-accordion" />
        <div class="collapse-title text-lg font-medium text-base-content">
          What evidence do audits receive?
        </div>
        <div class="collapse-content">
          <p class="text-base-content">Compact, deterministic transcripts and integrity hashes. Verifiers reconstruct the exact manifold geometry seen during the session to confirm scope and timing.</p>
        </div>
      </div>
    </div>
  </div>
</section>


