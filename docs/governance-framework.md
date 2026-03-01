# How the Body Governs Itself

The manifesto introduced the body. This is how it stays alive.

ATTUNE is a BAION — a Biological AI Orchestration Network. The first piece described what that means architecturally. This piece describes how it enforces its own rules.

Every living organism has an immune system. Not to prevent all harm — that is impossible. To detect harm, contain it, and recover. ATTUNE's governance works the same way.

---

## Three tiers of truth

Not all knowledge is equal. Some things are permanent. Some things are evolving. Some things are temporary. Treating them the same is how systems drift into chaos.

ATTUNE organizes everything into three tiers.

**Canon** is law. Locked rules, locked decisions. Canon is never edited — only superseded by a new version. If canon says it, that is the truth. No debate.

**Brain** is trusted thinking. Distilled, cleaned, readable. It can still evolve. It is not binding, but it is not disposable either. Brain earns its place by being tested and useful.

**Working** is temporary. Messy by default. Expected to change. If a working file has not moved in 30 days, it is promoted or deleted. Working is not a permanent home.

Material moves in one direction. Working to Brain. Brain to Canon. No shortcuts. No skipping tiers. Process confers status, not location.

---

## Two lanes of traffic

Every action in the system falls into one of two lanes.

**Lane A** is safe. Reading, browsing, drafting. No gate required. This is everyday traffic.

**Lane B** is damage-possible. Irreversible actions. High-impact changes. Anything that could break something that matters. Lane B requires a gate.

When in doubt about which lane an action belongs to — it is Lane B. Default to the more protective classification.

---

## Gates

A gate is a checkpoint. Nothing passes without meeting the requirements. Nothing.

**Gate-0** is no gate. Reading and thinking. No logging required.

**Gate-1** is controlled mutation. Reversible changes, internal adjustments. Requires declared intent, declared lane, a rollback plan, and a log entry.

**Gate-2** is high-impact mutation. Any edit to canon. Any promotion. Any governance change. Any outward publication. Any automation performing irreversible actions.

Gate-2 requires all of the following before the change happens. Intent. Lane with justification. Exact scope. Exact rollback steps. Structured log entry. Conflict check against adjacent files.

If any requirement is missing, ambiguous, or contradictory — the change stops. Full stop. Off-ramp.

---

## Fail closed

This is the governing philosophy. Every gate. Every contract. Every decision point.

If something is unknown — stop. If a schema version is unrecognized — stop. If authorization is missing — stop. If inputs do not match expectations — stop.

The system does not guess. It does not default. It does not assume good intent. It stops and surfaces the problem.

This is the opposite of how most software works. Most software fails open — it lets things through and hopes for the best. ATTUNE fails closed. The cost of a false stop is low. The cost of silent corruption is catastrophic.

---

## Five contracts

Every component in the system is bound by five enforceable contracts. These are not guidelines. They are rules with teeth.

**Schema Contract.** Every artifact declares its version. Unknown versions fail closed.

**Behavior Contract.** Same inputs produce same outputs. Replay divergence is detected and surfaced, never tolerated.

**Side-Effect Contract.** Real-world effects require governance authorization. Missing authorization fails closed.

**Receipt Contract.** Every run produces a receipt. Code version, policy version, input hash, output hash, evidence paths. The receipt hashes deterministically.

**Upgrade Contract.** Every change is classified before it is made. Documentation only. Additive compatible. Replay-safe. Replay-breaking. Security impacting. The classification determines the gate level required.

---

## No surveillance

This is not a feature. It is a hard rule.

No hidden recording. No scraping other apps. No background monitoring of any kind. No phone-home telemetry. No silent supply-chain escalation.

The governance architecture enforces this structurally, not contractually. There is no cloud server to subpoena. There is no API endpoint to redirect. The governance is the infrastructure.

---

## Safety is never paywalled

Safety is day-one infrastructure. It is not a premium feature. It is not an upgrade. It is not something you earn by paying more.

Self-hosting is a real option — not a fake one designed to fail. Paid offerings cover managed hosting and operated safety. They never cover access to core safety features.

Charge for responsibility, not control.

---

## The law at the bottom

The bedrock does not negotiate. It does not learn. It does not have opinions.

Schema valid or not. Authority correct or not. Protected paths respected or not. Every action that touches anything real passes through the law. The law fails closed.

The governance lives in the body. Not in terms of service. Not in a contract that can be canceled. In the architecture itself.

That is how the body governs itself.

---

*This is Piece 2 of the ATTUNE framework series. [Read Piece 1: Without Convergence, Nothing Holds](https://github.com/AttuneCommons/framework)*

*[Attune Commons on GitHub](https://github.com/AttuneCommons/framework)*
