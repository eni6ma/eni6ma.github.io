---
layout: page
title: Technology
permalink: technology
description: A compact, modular stack that drops into CLIs, gateways, and control‑plane agents.
---

<section class="py-6">
  <div class="max-w-4xl mx-auto">
    <div class="text-center mb-8 sm:mb-12 px-4">
      <h1 class="text-2xl sm:text-3xl lg:text-4xl font-bold mb-4 text-white">ENI6MA Technology Stack</h1>
      <div class="alert alert-info max-w-3xl mx-auto">
        <span class="text-sm sm:text-base">A minimal, self-contained cryptographic system engineered for high-assurance encryption, lightweight authentication, and verifiable proof flows without compromising security or speed.</span>
      </div>
    </div>

    <!-- Core Architecture Overview -->
    <div class="mb-16">
      <h2 class="text-xl sm:text-2xl font-semibold mb-6 sm:mb-8 text-center text-white">Core Architecture</h2>
      <div class="card bg-gradient-to-br from-primary/10 to-secondary/10 shadow-xl">
        <div class="card-body">
          <div class="badge badge-primary badge-lg mb-4">ε–τ–π Cryptographic Pipeline</div>
          <div class="grid grid-cols-2 md:grid-cols-3 gap-4">
            <div class="stat bg-base-100 rounded-lg">
              <div class="stat-title">Embedded Prime (π)</div>
              <div class="stat-desc">512-bit seed, never emitted</div>
            </div>
            <div class="stat bg-base-100 rounded-lg">
              <div class="stat-title">Entropy Pool (ε)</div>
              <div class="stat-desc">Encrypted, binary‑bound</div>
            </div>
            <div class="stat bg-base-100 rounded-lg">
              <div class="stat-title">Time Parameter (τ)</div>
              <div class="stat-desc">Microsecond granularity</div>
            </div>
            <div class="stat bg-base-100 rounded-lg">
              <div class="stat-title">Derivations</div>
              <div class="stat-desc">(Q,R,S) coordinates</div>
            </div>
            <div class="stat bg-base-100 rounded-lg">
              <div class="stat-title">Two-Way Stream</div>
              <div class="stat-desc">BLAKE3‑XOF encryption</div>
            </div>
            <div class="stat bg-base-100 rounded-lg">
              <div class="stat-title">Proof Systems</div>
              <div class="stat-desc">ALGO1 & Nonce-driven</div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Technology Modules -->
    <div class="mb-16">
      <h2 class="text-2xl font-semibold mb-8 text-center">Technology Modules</h2>
      
      <!-- Module Cards Grid -->
      <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
        <!-- ENI6MA.CIRCUIT Binary -->
        <div class="card bg-primary/10 shadow-xl hover:shadow-2xl transition-shadow">
          <div class="card-body">
            <div class="flex items-center mb-4">
              <div class="avatar placeholder">
                <div class="bg-primary text-primary-content rounded-lg w-10">
                  <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                  </svg>
                </div>
              </div>
              <h3 class="card-title ml-3">ENI6MA.CIRCUIT</h3>
            </div>
            <p class="mb-4">Minimal binary with embedded cryptographic constants and deterministic interfaces.</p>
            <ul class="text-sm space-y-1">
              <li>• Embedded 512-bit prime seed</li>
              <li>• Pool generation/validation</li>
              <li>• CLI and interactive shell</li>
              <li>• Self-test harness</li>
            </ul>
          </div>
        </div>

        <!-- Entropy Pool Manager -->
        <div class="card bg-success/10 shadow-xl hover:shadow-2xl transition-shadow">
          <div class="card-body">
            <div class="flex items-center mb-4">
              <div class="avatar placeholder">
                <div class="bg-success text-success-content rounded-lg w-10">
                  <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 15v2m-6 4h12a2 2 0 002-2v-6a2 2 0 00-2-2H6a2 2 0 00-2 2v6a2 2 0 002 2zm10-10V7a4 4 0 00-8 0v4h8z"></path>
                  </svg>
                </div>
              </div>
              <h3 class="card-title ml-3">Entropy Pool Manager</h3>
            </div>
            <p class="mb-4">AEAD-sealed pool with per-record nonces and authenticated headers.</p>
            <ul class="text-sm space-y-1">
              <li>• HKDF-derived sealing keys</li>
              <li>• Integrity failure detection</li>
              <li>• Binary-pool binding</li>
              <li>• Supply-chain hardening</li>
            </ul>
          </div>
        </div>

        <!-- Two-Way Hash Stream -->
        <div class="card bg-info/10 shadow-xl hover:shadow-2xl transition-shadow">
          <div class="card-body">
            <div class="flex items-center mb-4">
              <div class="avatar placeholder">
                <div class="bg-info text-info-content rounded-lg w-10">
                  <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 7v10c0 2.21 3.582 4 8 4s8-1.79 8-4V7M4 7c0 2.21 3.582 4 8 4s8-1.79 8-4M4 7c0-2.21 3.582-4 8-4s8 1.79 8 4"></path>
                  </svg>
                </div>
              </div>
              <h3 class="card-title ml-3">Two-Way Hash Stream</h3>
            </div>
            <p class="mb-4">BLAKE3-XOF driven symmetric encryption with counter-mode keystreams.</p>
            <ul class="text-sm space-y-1">
              <li>• Session-ephemeral keys</li>
              <li>• XOR-based encryption</li>
              <li>• Chunked processing</li>
              <li>• High throughput</li>
            </ul>
          </div>
        </div>

        <!-- Proof Engine -->
        <div class="card bg-secondary/10 shadow-xl hover:shadow-2xl transition-shadow">
          <div class="card-body">
            <div class="flex items-center mb-4">
              <div class="avatar placeholder">
                <div class="bg-secondary text-secondary-content rounded-lg w-10">
                  <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"></path>
                  </svg>
                </div>
              </div>
              <h3 class="card-title ml-3">Proof Engine</h3>
            </div>
            <p class="mb-4">Interactive (ALGO1) and nonce-driven proof systems for authentication.</p>
            <ul class="text-sm space-y-1">
              <li>• Interactive PoK (ALGO1)</li>
              <li>• Nonce-driven remote verification</li>
              <li>• Stateless validation</li>
              <li>• Index privacy</li>
            </ul>
          </div>
        </div>

        <!-- X-Matrix Derivation -->
        <div class="card bg-warning/10 shadow-xl hover:shadow-2xl transition-shadow">
          <div class="card-body">
            <div class="flex items-center mb-4">
              <div class="avatar placeholder">
                <div class="bg-warning text-warning-content rounded-lg w-10">
                  <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2H6a2 2 0 01-2-2V6zM14 6a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2V6zM4 16a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2H6a2 2 0 01-2-2v-2zM14 16a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2v-2z"></path>
                  </svg>
                </div>
              </div>
              <h3 class="card-title ml-3">X-Matrix Derivation</h3>
            </div>
            <p class="mb-4">Deterministic mapping from high-entropy state to low-bandwidth structure.</p>
            <ul class="text-sm space-y-1">
              <li>• PRF and modulo paths</li>
              <li>• Unbiased reduction</li>
              <li>• Time sensitivity</li>
              <li>• Uniform distributions</li>
            </ul>
          </div>
        </div>

        <!-- Verification Layer -->
        <div class="card bg-accent/10 shadow-xl hover:shadow-2xl transition-shadow">
          <div class="card-body">
            <div class="flex items-center mb-4">
              <div class="avatar placeholder">
                <div class="bg-accent text-accent-content rounded-lg w-10">
                  <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5H7a2 2 0 00-2 2v10a2 2 0 002 2h8a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2m-6 9l2 2 4-4"></path>
                  </svg>
                </div>
              </div>
              <h3 class="card-title ml-3">Verification Layer</h3>
            </div>
            <p class="mb-4">Stateless verification with deterministic replay and offline validation.</p>
            <ul class="text-sm space-y-1">
              <li>• O(1) verifier state</li>
              <li>• Index recovery</li>
              <li>• Membership checks</li>
              <li>• Audit transcripts</li>
            </ul>
          </div>
        </div>
      </div>
    </div>

    <!-- Deployment Options Accordion -->
    <div class="mb-16">
      <h2 class="text-2xl font-semibold text-neutral-900 dark:text-neutral-100 mb-8 text-center">Deployment Options</h2>

      <div class="relative">
        <div class="overflow-hidden rounded-2xl bg-white dark:bg-neutral-900 border border-neutral-200 dark:border-neutral-800 shadow-lg">
          <div id="deployment-accordion" class="divide-y divide-neutral-200 dark:divide-neutral-800">

            <!-- Human-in-the-Loop Authentication -->
            <div class="accordion-item">
              <button class="w-full text-left px-6 py-5 flex items-center justify-between" data-accordion-toggle>
                <div class="flex items-center">
                  <div class="w-12 h-12 bg-indigo-100 dark:bg-indigo-900 rounded-xl flex items-center justify-center mr-4">
                    <svg class="w-6 h-6 text-indigo-600 dark:text-indigo-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"></path>
                    </svg>
                  </div>
                  <div>
                    <h3 class="text-xl font-semibold text-neutral-900 dark:text-neutral-100">Human-in-the-Loop</h3>
                    <p class="text-sm text-indigo-600 dark:text-indigo-400 font-medium">Authentication</p>
                  </div>
                </div>
                <svg class="w-5 h-5 text-neutral-500 dark:text-neutral-400 transition-transform duration-200" viewBox="0 0 20 20" fill="currentColor" data-accordion-chevron>
                  <path fill-rule="evenodd" d="M5.23 7.21a.75.75 0 011.06.02L10 10.94l3.71-3.71a.75.75 0 111.06 1.06l-4.24 4.24a.75.75 0 01-1.06 0L5.21 8.29a.75.75 0 01.02-1.08z" clip-rule="evenodd" />
                </svg>
              </button>
              <div class="accordion-panel overflow-hidden max-h-0 transition-all duration-300 ease-in-out" data-accordion-panel>
                <div class="p-6 pt-0">
                  <div class="grid md:grid-cols-2 gap-8 items-start">
                    <div>
                      <div class="flex items-center mb-6">
                        <div class="w-12 h-12 bg-indigo-100 dark:bg-indigo-900 rounded-xl flex items-center justify-center mr-4">
                          <svg class="w-6 h-6 text-indigo-600 dark:text-indigo-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"></path>
                          </svg>
                        </div>
                        <div>
                          <h3 class="text-xl font-semibold text-neutral-900 dark:text-neutral-100">Human-in-the-Loop</h3>
                          <p class="text-sm text-indigo-600 dark:text-indigo-400 font-medium">Authentication</p>
                        </div>
                      </div>
                      <p class="text-neutral-700 dark:text-neutral-300 mb-6 leading-relaxed">
                        Interactive ALGO1 UI with color-coded zones, rotated alphabets, and discrete round structure. 
                        Tuned for accessibility with configurable zones (C) and rounds (L) for target error bounds.
                      </p>
                      <div class="space-y-3">
                        <h4 class="font-semibold text-neutral-900 dark:text-neutral-100 text-sm">Key Features</h4>
                        <ul class="text-sm text-neutral-600 dark:text-neutral-400 space-y-2">
                          <li class="flex items-start">
                            <div class="w-1.5 h-1.5 bg-indigo-500 rounded-full mt-2 mr-3 flex-shrink-0"></div>
                            <span>Color-coded zone navigation</span>
                          </li>
                          <li class="flex items-start">
                            <div class="w-1.5 h-1.5 bg-indigo-500 rounded-full mt-2 mr-3 flex-shrink-0"></div>
                            <span>Rotated alphabet panels</span>
                          </li>
                          <li class="flex items-start">
                            <div class="w-1.5 h-1.5 bg-indigo-500 rounded-full mt-2 mr-3 flex-shrink-0"></div>
                            <span>Configurable accessibility settings</span>
                          </li>
                          <li class="flex items-start">
                            <div class="w-1.5 h-1.5 bg-indigo-500 rounded-full mt-2 mr-3 flex-shrink-0"></div>
                            <span>Replay-resistant sessions</span>
                          </li>
                        </ul>
                      </div>
                    </div>
                    <div class="bg-gradient-to-br from-indigo-50 to-blue-50 dark:from-indigo-900/20 dark:to-blue-900/20 p-6 rounded-xl">
                      <h4 class="font-semibold text-neutral-900 dark:text-neutral-100 mb-4">Use Cases</h4>
                      <div class="space-y-3">
                        <div class="flex items-center">
                          <div class="w-2 h-2 bg-indigo-500 rounded-full mr-3"></div>
                          <span class="text-neutral-700 dark:text-neutral-300 text-sm">Interactive login systems</span>
                        </div>
                        <div class="flex items-center">
                          <div class="w-2 h-2 bg-indigo-500 rounded-full mr-3"></div>
                          <span class="text-neutral-700 dark:text-neutral-300 text-sm">High-security access control</span>
                        </div>
                        <div class="flex items-center">
                          <div class="w-2 h-2 bg-indigo-500 rounded-full mr-3"></div>
                          <span class="text-neutral-700 dark:text-neutral-300 text-sm">Human-verified operations</span>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <!-- Agent-to-Agent Authorization -->
            <div class="accordion-item">
              <button class="w-full text-left px-6 py-5 flex items-center justify-between" data-accordion-toggle>
                <div class="flex items-center">
                  <div class="w-12 h-12 bg-green-100 dark:bg-green-900 rounded-xl flex items-center justify-center mr-4">
                    <svg class="w-6 h-6 text-green-600 dark:text-green-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path>
                    </svg>
                  </div>
                  <div>
                    <h3 class="text-xl font-semibold text-neutral-900 dark:text-neutral-100">Agent-to-Agent</h3>
                    <p class="text-sm text-green-600 dark:text-green-400 font-medium">Authorization</p>
                  </div>
                </div>
                <svg class="w-5 h-5 text-neutral-500 dark:text-neutral-400 transition-transform duration-200" viewBox="0 0 20 20" fill="currentColor" data-accordion-chevron>
                  <path fill-rule="evenodd" d="M5.23 7.21a.75.75 0 011.06.02L10 10.94l3.71-3.71a.75.75 0 111.06 1.06l-4.24 4.24a.75.75 0 01-1.06 0L5.21 8.29a.75.75 0 01.02-1.08z" clip-rule="evenodd" />
                </svg>
              </button>
              <div class="accordion-panel overflow-hidden max-h-0 transition-all duration-300 ease-in-out" data-accordion-panel>
                <div class="p-6 pt-0">
                  <div class="grid md:grid-cols-2 gap-8 items-start">
                    <div>
                      <div class="flex items-center mb-6">
                        <div class="w-12 h-12 bg-green-100 dark:bg-green-900 rounded-xl flex items-center justify-center mr-4">
                          <svg class="w-6 h-6 text-green-600 dark:text-green-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path>
                          </svg>
                        </div>
                        <div>
                          <h3 class="text-xl font-semibold text-neutral-900 dark:text-neutral-100">Agent-to-Agent</h3>
                          <p class="text-sm text-green-600 dark:text-green-400 font-medium">Authorization</p>
                        </div>
                      </div>
                      <p class="text-neutral-700 dark:text-neutral-300 mb-6 leading-relaxed">
                        Nonce-driven proof steps embedded within normal request flows. Services challenge with nonce N, 
                        agents respond with compact transcripts bound to τ and H_T for stateless verification.
                      </p>
                      <div class="space-y-3">
                        <h4 class="font-semibold text-neutral-900 dark:text-neutral-100 text-sm">Key Features</h4>
                        <ul class="text-sm text-neutral-600 dark:text-neutral-400 space-y-2">
                          <li class="flex items-start">
                            <div class="w-1.5 h-1.5 bg-green-500 rounded-full mt-2 mr-3 flex-shrink-0"></div>
                            <span>Nonce challenge/response</span>
                          </li>
                          <li class="flex items-start">
                            <div class="w-1.5 h-1.5 bg-green-500 rounded-full mt-2 mr-3 flex-shrink-0"></div>
                            <span>Compact transcript payloads</span>
                          </li>
                          <li class="flex items-start">
                            <div class="w-1.5 h-1.5 bg-green-500 rounded-full mt-2 mr-3 flex-shrink-0"></div>
                            <span>Zero-trust segmentation</span>
                          </li>
                          <li class="flex items-start">
                            <div class="w-1.5 h-1.5 bg-green-500 rounded-full mt-2 mr-3 flex-shrink-0"></div>
                            <span>Independent verification</span>
                          </li>
                        </ul>
                      </div>
                    </div>
                    <div class="bg-gradient-to-br from-green-50 to-emerald-50 dark:from-green-900/20 dark:to-emerald-900/20 p-6 rounded-xl">
                      <h4 class="font-semibold text-neutral-900 dark:text-neutral-100 mb-4">Use Cases</h4>
                      <div class="space-y-3">
                        <div class="flex items-center">
                          <div class="w-2 h-2 bg-green-500 rounded-full mr-3"></div>
                          <span class="text-neutral-700 dark:text-neutral-300 text-sm">Microservice authentication</span>
                        </div>
                        <div class="flex items-center">
                          <div class="w-2 h-2 bg-green-500 rounded-full mr-3"></div>
                          <span class="text-neutral-700 dark:text-neutral-300 text-sm">API authorization</span>
                        </div>
                        <div class="flex items-center">
                          <div class="w-2 h-2 bg-green-500 rounded-full mr-3"></div>
                          <span class="text-neutral-700 dark:text-neutral-300 text-sm">Agent orchestration</span>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <!-- Remote Verification -->
            <div class="accordion-item">
              <button class="w-full text-left px-6 py-5 flex items-center justify-between" data-accordion-toggle>
                <div class="flex items-center">
                  <div class="w-12 h-12 bg-blue-100 dark:bg-blue-900 rounded-xl flex items-center justify-center mr-4">
                    <svg class="w-6 h-6 text-blue-600 dark:text-blue-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9v-9m0-9v9"></path>
                    </svg>
                  </div>
                  <div>
                    <h3 class="text-xl font-semibold text-neutral-900 dark:text-neutral-100">Remote Verification</h3>
                    <p class="text-sm text-blue-600 dark:text-blue-400 font-medium">Primitives</p>
                  </div>
                </div>
                <svg class="w-5 h-5 text-neutral-500 dark:text-neutral-400 transition-transform duration-200" viewBox="0 0 20 20" fill="currentColor" data-accordion-chevron>
                  <path fill-rule="evenodd" d="M5.23 7.21a.75.75 0 011.06.02L10 10.94l3.71-3.71a.75.75 0 111.06 1.06l-4.24 4.24a.75.75 0 01-1.06 0L5.21 8.29a.75.75 0 01.02-1.08z" clip-rule="evenodd" />
                </svg>
              </button>
              <div class="accordion-panel overflow-hidden max-h-0 transition-all duration-300 ease-in-out" data-accordion-panel>
                <div class="p-6 pt-0">
                  <div class="grid md:grid-cols-2 gap-8 items-start">
                    <div>
                      <div class="flex items-center mb-6">
                        <div class="w-12 h-12 bg-blue-100 dark:bg-blue-900 rounded-xl flex items-center justify-center mr-4">
                          <svg class="w-6 h-6 text-blue-600 dark:text-blue-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9v-9m0-9v9"></path>
                          </svg>
                        </div>
                        <div>
                          <h3 class="text-xl font-semibold text-neutral-900 dark:text-neutral-100">Remote Verification</h3>
                          <p class="text-sm text-blue-600 dark:text-blue-400 font-medium">Primitives</p>
                        </div>
                      </div>
                      <p class="text-neutral-700 dark:text-neutral-300 mb-6 leading-relaxed">
                        Concise JSON/CBOR artifacts suitable for logging and third-party attestation. 
                        Binary-pool binding prevents silent substitution attacks.
                      </p>
                      <div class="space-y-3">
                        <h4 class="font-semibold text-neutral-900 dark:text-neutral-100 text-sm">Key Features</h4>
                        <ul class="text-sm text-neutral-600 dark:text-neutral-400 space-y-2">
                          <li class="flex items-start">
                            <div class="w-1.5 h-1.5 bg-blue-500 rounded-full mt-2 mr-3 flex-shrink-0"></div>
                            <span>Deterministic artifacts</span>
                          </li>
                          <li class="flex items-start">
                            <div class="w-1.5 h-1.5 bg-blue-500 rounded-full mt-2 mr-3 flex-shrink-0"></div>
                            <span>Third-party attestation</span>
                          </li>
                          <li class="flex items-start">
                            <div class="w-1.5 h-1.5 bg-blue-500 rounded-full mt-2 mr-3 flex-shrink-0"></div>
                            <span>Audit-visible anomalies</span>
                          </li>
                          <li class="flex items-start">
                            <div class="w-1.5 h-1.5 bg-blue-500 rounded-full mt-2 mr-3 flex-shrink-0"></div>
                            <span>Supply-chain protection</span>
                          </li>
                        </ul>
                      </div>
                    </div>
                    <div class="bg-gradient-to-br from-blue-50 to-cyan-50 dark:from-blue-900/20 dark:to-cyan-900/20 p-6 rounded-xl">
                      <h4 class="font-semibold text-neutral-900 dark:text-neutral-100 mb-4">Use Cases</h4>
                      <div class="space-y-3">
                        <div class="flex items-center">
                          <div class="w-2 h-2 bg-blue-500 rounded-full mr-3"></div>
                          <span class="text-neutral-700 dark:text-neutral-300 text-sm">Distributed systems</span>
                        </div>
                        <div class="flex items-center">
                          <div class="w-2 h-2 bg-blue-500 rounded-full mr-3"></div>
                          <span class="text-neutral-700 dark:text-neutral-300 text-sm">Compliance auditing</span>
                        </div>
                        <div class="flex items-center">
                          <div class="w-2 h-2 bg-blue-500 rounded-full mr-3"></div>
                          <span class="text-neutral-700 dark:text-neutral-300 text-sm">Cross-domain trust</span>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <!-- Embedded/IoT -->
            <div class="accordion-item">
              <button class="w-full text-left px-6 py-5 flex items-center justify-between" data-accordion-toggle>
                <div class="flex items-center">
                  <div class="w-12 h-12 bg-purple-100 dark:bg-purple-900 rounded-xl flex items-center justify-center mr-4">
                    <svg class="w-6 h-6 text-purple-600 dark:text-purple-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 3v2m6-2v2M9 19v2m6-2v2M5 9H3m2 6H3m18-6h-2m2 6h-2M7 19h10a2 2 0 002-2V7a2 2 0 00-2-2H7a2 2 0 00-2 2v10a2 2 0 002 2zM9 9h6v6H9V9z"></path>
                    </svg>
                  </div>
                  <div>
                    <h3 class="text-xl font-semibold text-neutral-900 dark:text-neutral-100">Embedded</h3>
                    <p class="text-sm text-purple-600 dark:text-purple-400 font-medium">IoT Deployment</p>
                  </div>
                </div>
                <svg class="w-5 h-5 text-neutral-500 dark:text-neutral-400 transition-transform duration-200" viewBox="0 0 20 20" fill="currentColor" data-accordion-chevron>
                  <path fill-rule="evenodd" d="M5.23 7.21a.75.75 0 011.06.02L10 10.94l3.71-3.71a.75.75 0 111.06 1.06l-4.24 4.24a.75.75 0 01-1.06 0L5.21 8.29a.75.75 0 01.02-1.08z" clip-rule="evenodd" />
                </svg>
              </button>
              <div class="accordion-panel overflow-hidden max-h-0 transition-all duration-300 ease-in-out" data-accordion-panel>
                <div class="p-6 pt-0">
                  <div class="grid md:grid-cols-2 gap-8 items-start">
                    <div>
                      <div class="flex items-center mb-6">
                        <div class="w-12 h-12 bg-purple-100 dark:bg-purple-900 rounded-xl flex items-center justify-center mr-4">
                          <svg class="w-6 h-6 text-purple-600 dark:text-purple-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 3v2m6-2v2M9 19v2m6-2v2M5 9H3m2 6H3m18-6h-2m2 6h-2M7 19h10a2 2 0 002-2V7a2 2 0 00-2-2H7a2 2 0 00-2 2v10a2 2 0 002 2zM9 9h6v6H9V9z"></path>
                          </svg>
                        </div>
                        <div>
                          <h3 class="text-xl font-semibold text-neutral-900 dark:text-neutral-100">Embedded</h3>
                          <p class="text-sm text-purple-600 dark:text-purple-400 font-medium">IoT Deployment</p>
                        </div>
                      </div>
                      <p class="text-neutral-700 dark:text-neutral-300 mb-6 leading-relaxed">
                        Modulo path with Horner folding for tiny footprint and elimination of hash fans. 
                        Preserves determinism and unbiased final ranges for constrained environments.
                      </p>
                      <div class="space-y-3">
                        <h4 class="font-semibold text-neutral-900 dark:text-neutral-100 text-sm">Key Features</h4>
                        <ul class="text-sm text-neutral-600 dark:text-neutral-400 space-y-2">
                          <li class="flex items-start">
                            <div class="w-1.5 h-1.5 bg-purple-500 rounded-full mt-2 mr-3 flex-shrink-0"></div>
                            <span>Minimal memory footprint</span>
                          </li>
                          <li class="flex items-start">
                            <div class="w-1.5 h-1.5 bg-purple-500 rounded-full mt-2 mr-3 flex-shrink-0"></div>
                            <span>Constant-time operations</span>
                          </li>
                          <li class="flex items-start">
                            <div class="w-1.5 h-1.5 bg-purple-500 rounded-full mt-2 mr-3 flex-shrink-0"></div>
                            <span>Deterministic behavior</span>
                          </li>
                          <li class="flex items-start">
                            <div class="w-1.5 h-1.5 bg-purple-500 rounded-full mt-2 mr-3 flex-shrink-0"></div>
                            <span>Low power consumption</span>
                          </li>
                        </ul>
                      </div>
                    </div>
                    <div class="bg-gradient-to-br from-purple-50 to-violet-50 dark:from-purple-900/20 dark:to-violet-900/20 p-6 rounded-xl">
                      <h4 class="font-semibold text-neutral-900 dark:text-neutral-100 mb-4">Use Cases</h4>
                      <div class="space-y-3">
                        <div class="flex items-center">
                          <div class="w-2 h-2 bg-purple-500 rounded-full mr-3"></div>
                          <span class="text-neutral-700 dark:text-neutral-300 text-sm">Edge devices</span>
                        </div>
                        <div class="flex items-center">
                          <div class="w-2 h-2 bg-purple-500 rounded-full mr-3"></div>
                          <span class="text-neutral-700 dark:text-neutral-300 text-sm">IoT sensors</span>
                        </div>
                        <div class="flex items-center">
                          <div class="w-2 h-2 bg-purple-500 rounded-full mr-3"></div>
                          <span class="text-neutral-700 dark:text-neutral-300 text-sm">Constrained environments</span>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <!-- Regulated Environments -->
            <div class="accordion-item">
              <button class="w-full text-left px-6 py-5 flex items-center justify-between" data-accordion-toggle>
                <div class="flex items-center">
                  <div class="w-12 h-12 bg-orange-100 dark:bg-orange-900 rounded-xl flex items-center justify-center mr-4">
                    <svg class="w-6 h-6 text-orange-600 dark:text-orange-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"></path>
                    </svg>
                  </div>
                  <div>
                    <h3 class="text-xl font-semibold text-neutral-900 dark:text-neutral-100">Regulated</h3>
                    <p class="text-sm text-orange-600 dark:text-orange-400 font-medium">Environments</p>
                  </div>
                </div>
                <svg class="w-5 h-5 text-neutral-500 dark:text-neutral-400 transition-transform duration-200" viewBox="0 0 20 20" fill="currentColor" data-accordion-chevron>
                  <path fill-rule="evenodd" d="M5.23 7.21a.75.75 0 011.06.02L10 10.94l3.71-3.71a.75.75 0 111.06 1.06l-4.24 4.24a.75.75 0 01-1.06 0L5.21 8.29a.75.75 0 01.02-1.08z" clip-rule="evenodd" />
                </svg>
              </button>
              <div class="accordion-panel overflow-hidden max-h-0 transition-all duration-300 ease-in-out" data-accordion-panel>
                <div class="p-6 pt-0">
                  <div class="grid md:grid-cols-2 gap-8 items-start">
                    <div>
                      <div class="flex items-center mb-6">
                        <div class="w-12 h-12 bg-orange-100 dark:bg-orange-900 rounded-xl flex items-center justify-center mr-4">
                          <svg class="w-6 h-6 text-orange-600 dark:text-orange-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"></path>
                          </svg>
                        </div>
                        <div>
                          <h3 class="text-xl font-semibold text-neutral-900 dark:text-neutral-100">Regulated</h3>
                          <p class="text-sm text-orange-600 dark:text-orange-400 font-medium">Environments</p>
                        </div>
                      </div>
                      <p class="text-neutral-700 dark:text-neutral-300 mb-6 leading-relaxed">
                        Governance separation allows evolving policy constraints, MFA rules, rate limits, 
                        and role assumptions without changing cryptographic core equations.
                      </p>
                      <div class="space-y-3">
                        <h4 class="font-semibold text-neutral-900 dark:text-neutral-100 text-sm">Key Features</h4>
                        <ul class="text-sm text-neutral-600 dark:text-neutral-400 space-y-2">
                          <li class="flex items-start">
                            <div class="w-1.5 h-1.5 bg-orange-500 rounded-full mt-2 mr-3 flex-shrink-0"></div>
                            <span>Policy evolution</span>
                          </li>
                          <li class="flex items-start">
                            <div class="w-1.5 h-1.5 bg-orange-500 rounded-full mt-2 mr-3 flex-shrink-0"></div>
                            <span>Compliance frameworks</span>
                          </li>
                          <li class="flex items-start">
                            <div class="w-1.5 h-1.5 bg-orange-500 rounded-full mt-2 mr-3 flex-shrink-0"></div>
                            <span>Audit trails</span>
                          </li>
                          <li class="flex items-start">
                            <div class="w-1.5 h-1.5 bg-orange-500 rounded-full mt-2 mr-3 flex-shrink-0"></div>
                            <span>Cryptographic migrations</span>
                          </li>
                        </ul>
                      </div>
                    </div>
                    <div class="bg-gradient-to-br from-orange-50 to-amber-50 dark:from-orange-900/20 dark:to-amber-900/20 p-6 rounded-xl">
                      <h4 class="font-semibold text-neutral-900 dark:text-neutral-100 mb-4">Use Cases</h4>
                      <div class="space-y-3">
                        <div class="flex items-center">
                          <div class="w-2 h-2 bg-orange-500 rounded-full mr-3"></div>
                          <span class="text-neutral-700 dark:text-neutral-300 text-sm">Financial services</span>
                        </div>
                        <div class="flex items-center">
                          <div class="w-2 h-2 bg-orange-500 rounded-full mr-3"></div>
                          <span class="text-neutral-700 dark:text-neutral-300 text-sm">Healthcare systems</span>
                        </div>
                        <div class="flex items-center">
                          <div class="w-2 h-2 bg-orange-500 rounded-full mr-3"></div>
                          <span class="text-neutral-700 dark:text-neutral-300 text-sm">Government agencies</span>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>

          </div>
        </div>
      </div>
    </div>

    <!-- Performance Characteristics -->
    <div class="mb-16">
      <h2 class="text-2xl font-semibold mb-8 text-center">Performance Characteristics</h2>
      
      <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
        <div class="stat bg-primary/10 shadow-xl">
          <div class="stat-value text-primary">O(n)</div>
          <div class="stat-title">Matrix Derivation</div>
          <div class="stat-desc">Linear scaling with predictable cache behavior</div>
        </div>
        
        <div class="stat bg-success/10 shadow-xl">
          <div class="stat-value text-success">O(L)</div>
          <div class="stat-title">Verification</div>
          <div class="stat-desc">Membership checks per round</div>
        </div>
        
        <div class="stat bg-info/10 shadow-xl">
          <div class="stat-value text-info">10-50ms</div>
          <div class="stat-title">Latency</div>
          <div class="stat-desc">Interactive authentication overhead</div>
        </div>
        
        <div class="stat bg-secondary/10 shadow-xl">
          <div class="stat-value text-secondary">Millions/sec</div>
          <div class="stat-title">Throughput</div>
          <div class="stat-desc">Row computations on commodity CPUs</div>
        </div>
      </div>
    </div>

    <!-- Security Features -->
    <div class="mb-16">
      <h2 class="text-2xl font-semibold mb-8 text-center">Security Features</h2>
      
      <div class="grid md:grid-cols-2 gap-8">
        <div class="card bg-success/10 shadow-xl">
          <div class="card-body">
            <h4 class="card-title text-success">Cryptographic Guarantees</h4>
            <ul class="space-y-3">
              <li class="flex items-start">
                <div class="badge badge-success badge-sm mt-1 mr-3"></div>
                <span><strong>Ephemerality:</strong> τ-driven freshness with microsecond granularity prevents replay attacks</span>
              </li>
              <li class="flex items-start">
                <div class="badge badge-success badge-sm mt-1 mr-3"></div>
                <span><strong>Statelessness:</strong> No per-user private state required; verifiers re-derive (Q,R,S)</span>
              </li>
              <li class="flex items-start">
                <div class="badge badge-success badge-sm mt-1 mr-3"></div>
                <span><strong>Symmetric-only:</strong> PRF/XOF, modular folding, XOR operations for post-quantum agility</span>
              </li>
              <li class="flex items-start">
                <div class="badge badge-success badge-sm mt-1 mr-3"></div>
                <span><strong>Binary-pool binding:</strong> Supply-chain hardening prevents silent tampering</span>
              </li>
            </ul>
          </div>
        </div>
        
        <div class="card bg-info/10 shadow-xl">
          <div class="card-body">
            <h4 class="card-title text-info">Security Properties</h4>
            <ul class="space-y-3">
              <li class="flex items-start">
                <div class="badge badge-info badge-sm mt-1 mr-3"></div>
                <span><strong>Soundness:</strong> Conservative bound ε ≤ C⁻ᴸ + 2⁻λ for blind guessing resistance</span>
              </li>
              <li class="flex items-start">
                <div class="badge badge-info badge-sm mt-1 mr-3"></div>
                <span><strong>Completeness:</strong> Deterministic Φ under fixed (ε,τ,π) ensures reproducibility</span>
              </li>
              <li class="flex items-start">
                <div class="badge badge-info badge-sm mt-1 mr-3"></div>
                <span><strong>Index privacy:</strong> Nonce-driven proofs hide entropy indices from verifiers</span>
              </li>
              <li class="flex items-start">
                <div class="badge badge-info badge-sm mt-1 mr-3"></div>
                <span><strong>Auditability:</strong> Line-by-line auditable code with transparent constants</span>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>

  </div>
</section>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const items = document.querySelectorAll('#deployment-accordion .accordion-item');
  const toggles = document.querySelectorAll('#deployment-accordion [data-accordion-toggle]');

  function closeAll(except = null) {
    items.forEach((item) => {
      if (item === except) return;
      const panel = item.querySelector('[data-accordion-panel]');
      const chevron = item.querySelector('[data-accordion-chevron]');
      const button = item.querySelector('[data-accordion-toggle]');
      if (panel) panel.style.maxHeight = '0px';
      if (chevron) chevron.classList.remove('rotate-180');
      if (button) button.setAttribute('aria-expanded', 'false');
    });
  }

  toggles.forEach((btn) => {
    btn.setAttribute('aria-expanded', 'false');
    btn.addEventListener('click', function() {
      const item = this.closest('.accordion-item');
      const panel = item.querySelector('[data-accordion-panel]');
      const chevron = item.querySelector('[data-accordion-chevron]');
      const isOpen = panel.style.maxHeight && panel.style.maxHeight !== '0px';

      if (isOpen) {
        panel.style.maxHeight = '0px';
        if (chevron) chevron.classList.remove('rotate-180');
        this.setAttribute('aria-expanded', 'false');
      } else {
        closeAll(item);
        panel.style.maxHeight = panel.scrollHeight + 'px';
        if (chevron) chevron.classList.add('rotate-180');
        this.setAttribute('aria-expanded', 'true');
      }
    });
  });
});
</script>



