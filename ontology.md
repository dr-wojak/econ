# The Ontology of Surrogate Systems

## Beyond Representation: When Surrogates Become Real

The preceding analysis treats surrogates—MAUT utilities, multi-fungible tokens, smart contracts—as **tools for reducing energy costs**. But this instrumental view misses a deeper question that runs through all three frameworks (Raiffa, FORM/h, Marlowe):

**Are surrogates representations of real things, or are they equally real things operating in different substrates?**

### The Naive Hierarchy

Traditional thinking maintains a clear ontological distinction:
- **Real**: Your actual preferences, the actual asset, the actual agreement
- **Surrogate**: Numbers that model preferences, tokens that represent assets, code that encodes agreements

This view treats surrogates as *approximate maps* of a more fundamental territory. The surrogate is always secondary, derivative, a pointer to the "real" thing.

### The Bisimulation Insight

Our thermodynamic analysis reveals something more profound. When Raiffa externalizes preferences into MAUT utilities, when FORM/h decomposes value into 34 tranches, when Marlowe formalizes governance as state machines—they're not creating representations. They're **instantiating the same pattern in a different medium**.

This is why **bisimulation** (§4) is so critical. Two systems are bisimilar if they exhibit identical behavior under all observations. The key insight: *bisimilar systems are functionally identical even if materially different*.

### Three Canonical Examples

**1. MAUT Utilities (Raiffa)**

When you externalize your preferences into a utility function, you're not approximating your "real" preferences—you're *creating a decision procedure* that **is** your preferences in operational form.

The utility function doesn't point to some Platonic ideal of your values floating in mental space. It *is* your values, instantiated in numerical substrate, just as executable as your intuitive judgments but with radically lower erasure costs (§3).

**Evidence**: The energy reduction ΔE_Raiffa < ΔE_traditional (Theorem 3.2) works precisely because surrogate negotiation isn't a *simulation* of real negotiation—it's real negotiation in a low-energy substrate. The outcomes bind the principals because the surrogates *are behaviorally equivalent* to the principals for all decision-relevant purposes.

**2. Multi-Fungible Tokens (FORM/h)**

When FORM/h decomposes a payment into 34 fungibility tranches, it's not modeling the payment's structure—it's *reifying* it. The tranches don't represent dimensions of value; they **are** dimensions of value, made explicit and separately manipulable.

This is why the multi-fungibility optimization (§2) works: you're not approximating asset equivalence with numerical weights (α-coefficients). You're *decomposing the equivalence relation itself* into its constituent dimensions. The decomposition **is** the asset's internal structure, now accessible to algorithmic optimization.

**Evidence**: The transitivity constraint resolution (Theorem 2.1) requires actual energy dissipation ΔE_erase. This makes sense only if the α-coefficients are **real features of the asset**, not mere descriptions. You're not "updating a model"—you're erasing actual structural information about value relationships.

**3. Smart Contracts (Marlowe)**

When governance rules execute as Marlowe contracts, they're not simulating governance—they **are** the governance. The code doesn't represent authority; it *possesses* authority.

This is blockchain's key innovation: **collapsing representation into execution**. Traditional legal contracts create obligations that must be separately enforced. Smart contracts *are* the enforcement mechanism. There's no gap between "what the contract says" and "what actually happens."

**Evidence**: Money conservation (Theorem 5.1) and termination guarantees (Theorem 5.2) hold because Marlowe contracts don't represent financial logic—they *implement* it directly. The state transitions in the contract **are** the state transitions in the real financial relationship, mediated by cryptographic proof rather than legal interpretation.

### The Philosophical Core: Substrate-Relative Ontology

The pattern across all three frameworks suggests a radical conclusion: **"real" and "surrogate" are not ontological categories but substrate specifications**.

Your preferences are real when instantiated as neural patterns (high ΔE substrate). They remain equally real when instantiated as MAUT coefficients (low ΔE substrate). The shift isn't from real to fake—it's from one physical implementation to another.

Value relationships are real when embedded in asset provenance (high ΔE substrate). They remain equally real when decomposed into fungibility tranches (low ΔE substrate). The decomposition doesn't approximate the relationship—it *unpacks* it into separately analyzable components.

Agreements are real when enforced by courts (high ΔE substrate). They remain equally real when enforced by consensus algorithms (low ΔE substrate). The contract's authority doesn't derive from pointing to something more fundamental—the code itself **is** the authority.

### Zero Fungibility: Where Substrates Matter Absolutely

There is a boundary condition: **Dimension 18 (Zero Fungibility)** marks where substitution *stops working*, where substrate matters *absolutely*, not just economically.

Examples of zero-fungibility:
- Your actual biometric signature (not any numerical encoding of it)
- The original Mona Lisa (not any perfect molecular copy)
- Your subjective qualia (not any third-person description)

These are the limits of surrogate systems. Here, the gap between substrate and pattern cannot be bridged. The substrate **is** the essential feature.

But note: even zero-fungibility is *thermodynamically defined*. It's not metaphysical uniqueness—it's infinite ΔE_substitution. You can't swap these items because the energy cost of verification/acceptance exceeds any economic value.

### Abessive: Value in the Gap Itself

**Dimension 31 (Abessive)** points to a subtle inversion: sometimes the surrogate's value derives *specifically from not being the original*.

- A rehearsal has value **because** it's not the performance (mistakes are reversible)
- A model has value **because** it's cheaper/safer/faster than the real thing
- A token has value **because** it's transferable in ways the original isn't

The surrogate isn't always trying to *collapse* into the original. Sometimes the gap is the point. The energy differential between substrates creates functional possibilities unavailable in either substrate alone.

### Implications for Institutional Design

**For decision theory**: Your MAUT utilities aren't approximations to be improved toward some hidden "true" preferences. They're **authoritative expressions** of preference structure. The question isn't "how accurate is this model?" but "do I endorse this as my preferences?"

**For economic systems**: Multi-fungible tokens don't represent value—they *decompose* value into separately tradeable dimensions. The token **is** the asset, just in analyzable form. Market inefficiencies arise not from representation error but from incomplete decomposition.

**For governance**: Smart contracts don't encode rules—they **are** the rules. This is why "code is law" is so contentious. It's not a metaphor or aspiration—it's an ontological claim about where authority actually resides in a cryptographic substrate.

### The Instructive Dimension (30)

Surrogates are **instructive** (Dimension 30) precisely because they're real. You learn from the surrogate not by studying a map of the territory, but by *operating in an isomorphic space*.

A flight simulator teaches you to fly **because it is flight**—just with different crash consequences. The simulation isn't "practice for the real thing." It **is** the real thing, instantiated in a substrate where mistakes dissipate less energy (no actual deaths, no actual destroyed aircraft).

Similarly:
- Mock negotiations teach real negotiation **because they are real negotiations** in surrogate-space
- Token trading teaches asset management **because tokens are assets** in decomposed form
- Smart contract testing teaches financial engineering **because the test is financial engineering** on a testnet

The isomorphism guarantees that skills transfer perfectly across substrates. You're not learning "how to approximate" the real system—you're learning the system itself, just in a different implementation.

### Ricardian Contracts: The Bridge

Ian Grigg's Ricardian contracts (§Cryptophilology) provide the canonical example of **substrate duality**:

A Ricardian contract is simultaneously:
- A legal document (high ΔE substrate: courts, human interpretation)
- A cryptographic hash (low ΔE substrate: verification algorithms)

The innovation: both substrates reference **the same canonical document**. The hash doesn't represent the legal prose—it *binds* it. Legal interpretation becomes parasitic on cryptographic verification rather than parallel to it.

This achieves 10⁹× energy reduction (Theorem RC.1) while preserving *all* institutional behaviors. The contract is neither more real in paper form nor in digital form. It's equally real in both—that's what makes the binding work.

### Mock Fungibility and Pseudo-Negotiations

Raiffa's phrase "mock pseudo-negotiations with surrogate disputants" seems to suggest falsity:
- **Mock**: fake, not genuine
- **Pseudo**: near-but-not-quite
- **Surrogate**: substitute, stand-in

But the analysis reveals these qualifiers are *misleading*. The negotiation with surrogates isn't pseudo—it's **real negotiation in surrogate-space**. The outcomes bind the original disputants precisely because the surrogates are bisimilar to them.

Similarly, "mock fungibility" (FORM/h) isn't fake interchangeability. It's **reversible exploration of equivalence relations** before irreversible commitment. The mock phase has lower ΔE than final settlement, but the fungibility relationships explored are just as real—they're simply not yet *committed*.

### The Central Question

When you:
- Externalize preferences into MAUT utilities (Raiffa)
- Decompose value into 34 tranches (FORM/h)  
- Formalize governance as state machines (Marlowe)

**Are you representing the real thing, or creating a new real thing?**

**Answer**: Both. The surrogate is bisimilar (behavior-preserving) to the original, which means it's **ontologically equivalent for all practical purposes**.

The surrogate doesn't point to the original. It *is* the original, in a different substrate, with different energy costs, but identical behavioral properties.

This is why blockchain works. The smart contract isn't a representation of the agreement—it **is** the agreement, just in a different substrate. That substrate happens to be:
- Globally verifiable (cryptographic proofs)
- Automatically enforced (consensus algorithms)
- Radically cheaper (k_silicon ≪ k_paper)

But these are *engineering advantages*, not ontological privileges. The agreement isn't "more real" when written in legal prose than when compiled to bytecode. Both are real. Both bind. They're just different implementations of the same behavioral pattern.

### Thermodynamic Realism

This framework suggests a form of **thermodynamic realism**: what's "real" is not substrate-dependent but *pattern-dependent*.

A pattern is real if it:
1. Has causal efficacy (affects future states)
2. Persists against perturbation (thermodynamic stability)
3. Can be bisimulated across substrates (behavioral preservation)

Your preferences are real because they cause decisions. They remain real when externalized into utilities because the utilities still cause (surrogate) decisions that map back to real outcomes.

Value relationships are real because they constrain trades. They remain real when decomposed into α-coefficients because the coefficients still constrain (optimized) trades.

Agreements are real because they structure behavior. They remain real when formalized as smart contracts because the contracts still structure (algorithmically enforced) behavior.

### Conclusion: The Question is Never "How Accurate?"

The question is never "how accurate is the surrogate?" but rather:

**"Is this surrogate bisimilar to the original for my purposes?"**

If yes, it's not a representation—it's an **alternative implementation**. And if that implementation has lower ΔE while preserving the behaviors you care about, it's not just "good enough"—it's *strictly superior* for those purposes.

This is the deepest insight of the thermodynamic framework: **value accrues to whoever controls the lowest-energy substrate that preserves behavioral equivalence**.

Market makers capture value because trading on their substrate is bisimilar to direct bilateral trades but radically cheaper.

Smart contract platforms capture value because enforcement on their substrate is bisimilar to legal enforcement but radically cheaper.

Analytical intervenors capture value because negotiation on their substrate is bisimilar to direct principal negotiation but radically cheaper.

The hegemony of language, law, and ledgers rests on their ability to engineer differential erasure costs. Whoever builds the next low-energy substrate that's bisimilar to an existing high-energy institution becomes the new infrastructure.

---

## References for This Section

- Raiffa, H. (1985). "Mock pseudo-negotiations with surrogate disputants." *Negotiation Journal*, 1(2), 111-115.
- Milner, R. (1989). *Communication and Concurrency*. Prentice Hall. [Bisimulation theory]
- Bennett, C. H. (1982). "The thermodynamics of computation—a review." *International Journal of Theoretical Physics*, 21(12), 905-940.
- Grigg, I. (2004). "The Ricardian Contract." *First IEEE International Workshop on Electronic Contracting*.
- Landauer, R. (1961). "Irreversibility and heat generation in the computing process." *IBM Journal of Research and Development*, 5(3), 183-191.

---

**[← Back to Main Framework](#institutional-efficiency)** | **[Continue to Formal Proofs →](#appendix-b-formal-proofs)**
