## RWP Accumulator with Lower Dimensional Witnesses

The Accumulator cypher employs a novel approach to cryptographic accumulators, leveraging the **Holographic Morphism** with private languages.
This cypher uses a set of enumerated alphabets with equal cardinality to create witnesses, ensuring efficient and secure membership proofs.

Witnesses in the cypher are lower-dimensional references that are expanded after determining the holographic morphism.
This morphism identifies a subset of the projective alphabet sets containing character members of another alphabet, whose members are distributed equally across the new lower-dimensional projective set.
The higher-dimensional set contains a larger number of members, representing the individual members of the secret key, from which the witness is provided in any $i^{\text{th}}$ round of a sigma protocol.

### Key Definitions

The Accumulator cypher defines the **projective set** $\Pi$ as a set containing elements arranged in a lower-dimensional space, which expands to identify specific subsets through holographic morphisms.
The **holographic morphism** $\mathcal{H}$ is a hidden morphism linking two alphabets that have no intersection.
This morphism is used to expand lower-dimensional witnesses.
The lower-dimensional representation process maps higher-dimensional members of an alphabet into lower-dimensional projective sets.

$$
\text{pk}_\chi = \text{HoloMorphism}(\nu_{i_k}) \quad \text{for} \quad \chi \in \Xi
$$

$$
\Pi = \{\nu_{i_1}, \nu_{i_2}, \ldots, \nu_{i_r}\}
$$

### Interactive Cypher Setup

In the setup phase, the projective set $\Pi$ is defined to model the domain $M$.
A synonym relation to the emergent set is established via a hidden morphism.

During the accumulation phase, the short representation $\text{Acc}_\Xi$ of the set $X$ is created, partitioning it into subsets that form the basis of the projective set:

$$
\text{Acc}_\Xi = \bigl\{\Pi = (\nu_{i_1}, \nu_{i_2}, \ldots, \nu_{i_r}),\; \Omega = (\nu_{j_1}, \nu_{j_2}, \ldots, \nu_{j_r})\bigr\}
$$

For **membership holomorphic witness responses**, a lower-dimensional reference is created using the Holographic Morphism, then expanded to identify a subset of the projective alphabet sets.

For **non-membership witnesses**, lower-dimensional references are generated and expanded to verify non-inclusion in the set $X$:

$$
\text{pk}_\chi = \text{HoloMorphism}(\nu_{i_k}) \quad \text{for} \quad \chi \in \Xi
$$

The verification process utilizes the projective morphism to trace the exact path from the lower-dimensional witness to the accumulated representation $\text{Acc}_\Xi$:

$$
\text{Verify}\!\bigl(\text{resp}(\chi, \text{pk}_\chi, \chi), \text{Acc}_\Xi\bigr) =
\begin{cases}
\text{True} & \text{if valid membership} \\
\text{False} & \text{otherwise}
\end{cases}
$$

The primary equations and formulations in the RWP Accumulator cypher include the accumulator representation, membership holomorphic witness responses, non-membership holomorphic witness responses, and the sigma protocol for witness verification.

#### Example

Consider a set $X = \{\chi_1, \chi_2, \chi_3, \chi_4\}$.
The accumulator represents this set in projective form:

$$
\text{Acc}_X = \bigl\{\Pi = (v_1, v_2, v_3, v_4),\; \Omega = (v_5, v_6, v_7, v_8)\bigr\}
$$

For membership witness $\chi_1$:

$$
\text{pk}_{\chi_1} = \text{HoloMorphism}(v_1)
$$

Verification:

$$
\text{Verify}\!\bigl(\text{resp}(\chi_1, \text{pk}_{\chi_1}, \chi), \text{Acc}_X\bigr)
$$

### Holographic Witness Accumulation

In setup, $\Pi$ models the domain $\mathcal{M}$.
The accumulate phase creates the short representation $\text{Acc}_\Xi$ of the set $\Xi$, partitioning it into projective subsets:

$$
\text{Acc}_\Xi = \bigl\{ \Pi = (\nu_{i_1}, \ldots, \nu_{i_r}),\; \Theta = (\nu_{j_1}, \ldots, \nu_{j_r}) \bigr\}
$$

### Public Key Generation

Membership witnesses:

$$
\text{pk}_\xi = \mathcal{H}(\nu_{i_k}) \quad \text{for} \quad \xi \in \Xi
$$

Non-membership witnesses:

$$
\text{pk}_{\xi'} = \mathcal{H}(\nu_{j_k}) \quad \text{for} \quad \xi' \in \mathcal{M} \setminus \Xi
$$

### Verification

$$
\text{Verify}\!\bigl(\text{resp}(\xi, \text{pk}_\xi, \chi), \text{Acc}_\Xi\bigr) =
\begin{cases}
\text{True} & \text{if valid membership} \\
\text{False} & \text{otherwise}
\end{cases}
$$

### Equations and Formulations

1. **Accumulator Representation**

   $$
   \text{Acc}_\Xi = \bigl\{ \Pi = (\nu_{i_1}, \ldots, \nu_{i_r}),\; \Theta = (\nu_{j_1}, \ldots, \nu_{j_r}) \bigr\}
   $$

2. **Membership Public Key Generation**

   $$
   \text{pk}_\xi = \mathcal{H}(\nu_{i_k}) \quad \text{for} \quad \xi \in \Xi
   $$

3. **Non-Membership Public Key Generation**

   $$
   \text{pk}_{\xi'} = \mathcal{H}(\nu_{j_k}) \quad \text{for} \quad \xi' \in \mathcal{M} \setminus \Xi
   $$

4. **Sigma Protocol for Witness Verification**

   *Challenge*: $\chi \in \{0,1\}^n$
   *Response*:

   $$
   \text{resp}(\xi, \text{pk}_\xi, \chi) = \text{Expand}\bigl(\mathcal{H}(\nu_{i_k}), \chi\bigr)
   $$

   *Verification*:

   $$
   \text{Verify}\!\bigl(\text{resp}(\xi, \text{pk}_\xi, \chi), \text{Acc}_\Xi\bigr) =
   \begin{cases}
   \text{True} & \text{if valid membership} \\
   \text{False} & \text{otherwise}
   \end{cases}
   $$

---

[Bellare1999]<sup>8</sup> [Benaloh1993]<sup>9</sup> [Pointcheval1996]<sup>10</sup> 