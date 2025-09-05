---
layout: page
title: FAQ
permalink: faq
description: Answers to common questions about ENI6MA.
---

<section class="py-6">
  <div class="divide-y divide-neutral-200 dark:divide-neutral-800">
    <details class="group py-4">
      <summary class="list-none cursor-pointer flex items-center justify-between">
        <span class="font-medium text-neutral-900 dark:text-white">Does ENI6MA replace identity or PKI?</span>
        <span class="ml-4 text-neutral-500 group-open:rotate-180 transition-transform">⌄</span>
      </summary>
      <p class="mt-3 text-sm text-neutral-700 dark:text-neutral-300">ENI6MA shifts authorization from identity to scoped capability. It can complement or replace PKI ceremonies for many action‑level checks by validating capabilities deterministically and offline.</p>
    </details>

    <details class="group py-4">
      <summary class="list-none cursor-pointer flex items-center justify-between">
        <span class="font-medium text-neutral-900 dark:text-white">How are tokens revoked or rotated?</span>
        <span class="ml-4 text-neutral-500 group-open:rotate-180 transition-transform">⌄</span>
      </summary>
      <p class="mt-3 text-sm text-neutral-700 dark:text-neutral-300">Capabilities are short‑lived and bound to tau (time) and context, minimizing the need for explicit revocation. Policy can enforce tight windows and scope, and audits reconstruct decisions from transcripts.</p>
    </details>

    <details class="group py-4">
      <summary class="list-none cursor-pointer flex items-center justify-between">
        <span class="font-medium text-neutral-900 dark:text-white">Can it run offline or in air‑gapped modes?</span>
        <span class="ml-4 text-neutral-500 group-open:rotate-180 transition-transform">⌄</span>
      </summary>
      <p class="mt-3 text-sm text-neutral-700 dark:text-neutral-300">Yes. Verification is stateless and local; authorized verifiers re‑derive and check commitments without contacting a central authority.</p>
    </details>

    <details class="group py-4">
      <summary class="list-none cursor-pointer flex items-center justify-between">
        <span class="font-medium text-neutral-900 dark:text-white">What about deepfakes and replay?</span>
        <span class="ml-4 text-neutral-500 group-open:rotate-180 transition-transform">⌄</span>
      </summary>
      <p class="mt-3 text-sm text-neutral-700 dark:text-neutral-300">Tau windows and context binding prevent reuse; interactive proofs can bind human witness evidence to scope, yielding portable, verifiable transcripts.</p>
    </details>

    <details class="group py-4">
      <summary class="list-none cursor-pointer flex items-center justify-between">
        <span class="font-medium text-neutral-900 dark:text-white">How fast is verification?</span>
        <span class="ml-4 text-neutral-500 group-open:rotate-180 transition-transform">⌄</span>
      </summary>
      <p class="mt-3 text-sm text-neutral-700 dark:text-neutral-300">Local checks run in milliseconds with O(1) verifier state. There are no online round‑trips in the critical path.</p>
    </details>

    <details class="group py-4">
      <summary class="list-none cursor-pointer flex items-center justify-between">
        <span class="font-medium text-neutral-900 dark:text-white">What evidence do audits receive?</span>
        <span class="ml-4 text-neutral-500 group-open:rotate-180 transition-transform">⌄</span>
      </summary>
      <p class="mt-3 text-sm text-neutral-700 dark:text-neutral-300">Compact, deterministic transcripts and integrity hashes. Verifiers reconstruct the exact manifold geometry seen during the session to confirm scope and timing.</p>
    </details>
  </div>
</section>


