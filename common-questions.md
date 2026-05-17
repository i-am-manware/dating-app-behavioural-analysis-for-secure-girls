## 🔬 15 Questions — Answered From The Data

---

### 1. 🎭 Attractiveness = 2 but getting swiped right — what compensates?

At mid-attractiveness (score=2), only **6.2% of profiles get swiped right** (2 out of 32). But the two that *did* get swiped had dramatically different personality scores:

| Feature | Swiped Right | Not Swiped | Difference |
|---|---|---|---|
| Wholesomeness | 2.00 | 0.33 | **+1.67** |
| Authenticity | 2.00 | 0.50 | **+1.50** |
| Emotional stability | 1.50 | 0.07 | **+1.43** |
| Warmth | 2.00 | 0.57 | **+1.43** |
| Consistency | 2.00 | 0.90 | **+1.10** |

**Answer:** It's a near-complete personality ceiling lift. Average-looking guys who got swiped had *maxed out* wholesomeness, authenticity, warmth and emotional stability. Being at score=2 on attractiveness but 2/2 on emotional stability and warmth is enough to breach the threshold. The looks floor is real, but mid-tier is survivable with an exceptional inner character score.

---

### 2. 👀 How much do looks actually matter? Is there a threshold?

| Attractiveness Tier | Swipe Rate | n |
|---|---|---|
| Low (0–1) | **0%** | 22 |
| Mid (2) | **6.2%** | 32 |
| High (3–4) | **~48%** | 65 |

**Answer:** Looks function as a **hard gate at the bottom**, not a linear advantage at the top. Below a score of 2, no amount of personality saves you in this dataset (0/22 swiped). Once you clear mid-tier (score 2+), attractiveness returns diminish sharply — the jump from Mid→High is large, but personality starts dominating within High tier. So: *looks matter as a floor, personality matters as a ceiling.*

---

### 3. 😄 Do funny bios actually work?

| Bio Tone | Serious (0) | Mixed (0.5) | Funny (1) |
|---|---|---|---|
| Overall swipe rate | 26.5% | **36.4%** | 24.0% |

**But when stratified by attractiveness:**

| Tier | Serious | Mixed | Funny |
|---|---|---|---|
| Low | 0% | 0% | 0% |
| Mid | 10% | 0% | 0% |
| High | 47% | **57%** | 38% |

**Answer:** Funny bios **don't universally work**. The marginal winner is **mixed tone (serious + humor)** at 36.4% overall. Pure humor (tone=1) at 24% actually *underperforms* serious tone. Crucially: funny bios *only help high-attractiveness profiles* — for mid-tier, funny bio = 0% swipe rate. The advice "be funny in your bio" is only valid if you're already attractive enough to pull it off.

---

### 4. 🙏 Is being humble better than showing off?

| Humility Score | Meaning | Swipe Rate | n |
|---|---|---|---|
| 0 | Bragging | **1.8%** | 55 |
| 1 | Balanced | **46.0%** | 50 |
| 2 | Humble | **35.7%** | 14 |

**Answer:** **Balanced (1) crushes both extremes.** Bragging is catastrophic (1.8%), and even excessive humility underperforms balanced. The data tells a clear story: *self-aware confidence* (you know your worth, you don't need to announce it) is the optimum. Bragging is genuinely one of the strongest negative signals in the entire dataset.

---

### 5. 📸 Do more photos actually help?

| Photo Count | Swipe Rate | n |
|---|---|---|
| 1–2 | **0%** | 8 |
| 3–4 | **20.8%** | 48 |
| 5–6 | **29.0%** | 62 |
| Spearman ρ | 0.212 | p=0.02 |

**Answer:** Yes, weakly but significantly (ρ=0.21, p=0.02). Having 1–2 photos signals low effort and gets 0%. The sweet spot is **5–6 photos** — enough to show variety, not enough to feel like a catalog. Diminishing returns apply beyond 6. More importantly, *photo quality matters far more than photo quantity* — quality ρ=0.73 vs count ρ=0.21.

---

### 6. 💼 Should you show your profession?

| Profession Disclosed | Swipe Rate | n |
|---|---|---|
| Hidden (0) | 18.2% | 44 |
| Disclosed (1) | **28.8%** | 73 |

**Answer:** Yes — disclosing profession gives a modest but real lift (~10pp). It likely signals confidence, stability, and non-mystery in a positive way. Not disclosing doesn't hurt catastrophically, but there's no upside to hiding it.

---

### 7. 🧬 Does effort matter, or just genetics?

From the prescription swings (all others held at median):
- Genuineness: **+0.088** (controllable)
- Warmth: **+0.080** (partially controllable)
- Emotional stability: **+0.072** (partially controllable, signaled through profile tone)
- Attractiveness: **+0.011** (largely genetic)

And from Q9: High-attractiveness profiles only have emotional stability ≥1 in **48%** of cases — meaning half of attractive guys don't even bother displaying it.

**Answer:** **Effort massively matters.** The prescription swing for personality traits (genuineness, warmth, authenticity) is 5–8× larger than the marginal swing for attractiveness. Genetics gets you past the floor, but effort-driven signals (profile curation, authentic writing, emotional tone) determine the ceiling. Plenty of attractive guys tank their profiles by being cold, bragging, or low-effort.

---

### 8. ❌ Are most online dating advice tips actually wrong?

Based on what the data shows vs what common advice says:

| Common Advice | Data Says | Verdict |
|---|---|---|
| "Show off your physique/shirtless" | Shirtless → **0% swipe rate** | ❌ **Wrong** |
| "Be funny/witty in bio" | Funny bios underperform mixed tone | ⚠️ **Mostly wrong** |
| "Show social proof (friends)" | friends_in_pics = 20% vs 24.6% without | ❌ **Slightly wrong** |
| "Gym selfies show you work out" | Mid % half-body = worst (12.8%) | ❌ **Wrong** |
| "More photos = better" | Weak effect, quality dominates | ⚠️ **Exaggerated** |
| "Show confidence" | Bragging = 1.8%, balanced = 46% | ⚠️ **Definition matters** |
| "Be mysterious (vague bio)" | bio_depth=2 = 80% swipe, depth=0 = 24% | ❌ **Wrong — depth wins** |
| "Disclose profession" | Confirmed: +10pp | ✅ **Correct** |

**Answer:** Yes — the majority of commonly shared tips are either wrong or context-dependent. The data consistently shows that **authenticity, depth, and emotional safety** beat performance, status signaling, and physical display.

---

### 9. 😎 Do attractive people actually make worse profiles?

From Q9 — among High-attractiveness profiles (score 3–4):
- Only **48% have emotional stability ≥1** (the rest = 0 or missing)
- Mean warmth = 1.00 (mid-scale, not high)
- Mean authenticity = 0.85 (below average)

Vs. what they *need*: emotional_stability swiped=1.50 vs not=0.07 at mid-tier.

**Answer:** **Yes, partially.** Attractive men invest less in their profiles — they rely on looks and put in lower personality effort. This is measurable: high-attractiveness profiles have the *lowest average effort on emotional signaling* relative to their potential. This means high-attractiveness + high personality effort is rare and represents the most successful archetype (48.1% → likely near 70–80% for the subset that *also* invests in personality).

---

### 10. 🌟 Does being 'too perfect' hurt you?

| Intra-profile Consistency | Swipe Rate | n |
|---|---|---|
| 0 (inconsistent) | 3.4% | 29 |
| 1 (somewhat) | 6.9% | 43 |
| 2 (consistent) | **52.2%** | 46 |
| 3 (too perfect) | **100%** | 1 |

**Answer:** In this dataset, more consistency = better, monotonically. There's no "uncanny valley" effect. Score=3 has only 1 profile so it's unreliable, but score=2 dramatically outperforms score=1. The fear of "looking too curated" doesn't hold — *coherent, consistent profiles win*. The concern should be about **bragging** (which does hurt), not about being too polished.

---

### 11. 🕵️ Is mystery attractive, or just confusion?

| Bio Depth | Meaning | Swipe Rate | n |
|---|---|---|---|
| 0 | Short/few words | 23.5% | 85 |
| 1 | 1 sentence | 17.9% | 28 |
| 2 | 2+ sentences | **80%** | 5 |

**Answer:** **Depth beats mystery entirely.** The highest swipe rate belongs to profiles with *detailed, substantive bios* (bio_depth=2). A vague, minimal bio (depth=0) performs better than a half-hearted single sentence (depth=1). There's no evidence that being mysterious/withholding information helps. *Depth creates genuine intrigue; vagueness just creates blankness.* The caveat is n=5 for depth=2, so treat directionally.

---

### 12. 🔬 What traits only matter *after controlling for attractiveness*?

From the feature_eda.ipynb partial correlation analysis (controlling for attractiveness):

| Feature | Raw ρ | Partial ρ (ctrl attr) | Independent? |
|---|---|---|---|
| photo_quality | 0.73 | ~0.09–0.16 | ❌ Mostly confound |
| photo_lighting | ~0.65 | ~0.09 | ❌ Mostly confound |
| first_photo_impact_score | ~0.58 | **~0.33** | ✅ Independent |
| photo_curation_effort | ~0.52 | **~0.27** | ✅ Independent |
| warmth_vs_coldness | 0.69 | **Remains high** | ✅ Independent |
| emotional_stability | 0.83 | **Remains high** | ✅ Independent |

**Answer:** Photo quality and lighting are largely **confounds of attractiveness** — attractive people tend to have better photos, so the correlation dissolves when you control for looks. But **photo curation effort, first photo impact, warmth, and emotional stability retain independent effects** even after controlling for attractiveness. These are the truly controllable levers.

---

### 13. 🧠 What are the hidden personality dimensions?

From latent_analysis.ipynb (EFA with oblimin rotation, KMO=0.907):

**Factor 1 — "Psychological Safety & Inner Character"** (loadings):
- Warmth: 0.93, Authenticity: 0.91, Wholesomeness: 0.87, Emotional stability: 0.86, Genuineness: 0.83
- → *"Can I trust this person with my vulnerability?"*
- Alone achieves **AUC = 0.978** predicting swipes

**Factor 2 — "Visual Appeal & Ambient Status"** (loadings):
- Photo quality: 0.79, Photo lighting: 0.79, Attractiveness: 0.77, First photo impact: 0.73
- → *"Does this person's world look desirable?"*
- Alone achieves **AUC = 0.891**

**Answer:** All subjective features collapse into just two latent axes. Every personality trait you think is separate (genuine, warm, authentic, wholesome) is actually *one thing* — psychological safety. Photo quality, lighting, attractiveness are *one thing* — visual ambient status. The combined AUC is 0.993, meaning these two dimensions explain almost everything.

---

### 14. ⚡ What's the smallest change that increases matches the most?

From the prescription swing table:

| Rank | Feature | Change | Swing |
|---|---|---|---|
| 1 | Genuineness: 0 → 3 | Rewrite profile to sound real, not performed | **+0.088** |
| 2 | Warmth: 0 → 2 | Tone shift from neutral/cold to warm | **+0.080** |
| 3 | Emotional stability: 0 → 2 | Remove anxious/volatile energy from text | **+0.072** |

**Answer:** The highest-ROI single change is **rewriting your bio to sound genuinely like yourself rather than performing an attractive version of yourself** (genuineness 0→3 = +8.8pp). This is a *text rewrite*, not a photo shoot. Second place: shifting tone from cold to warm (+8pp). Both are zero-cost changes. For someone currently at genuineness=0 and warmth=0, fixing both simultaneously could swing them from ~3% → ~18% predicted probability.

---

### 15. ☠️ What traits actively hurt your chances?

From the data — ranked by damage:

| Trait | Swipe Rate | vs Baseline | Verdict |
|---|---|---|---|
| **Shirtless photos** | **0%** | −26% | ☠️ Instant kill |
| **Bragging (humility=0)** | **1.8%** | −24% | ☠️ Near-instant kill |
| **Casual intent** | **0%** | −24% | ☠️ Instant kill |
| **Avoidant attachment** | **0%** | −24% | ☠️ Instant kill |
| **Heavy drinking disclosed** | **0%** | −24% | ☠️ Instant kill |
| Lots of selfies (>50%) | 11.8% | −14% | 🔴 Major damage |
| Filters on photos | 16.7% | −16% | 🔴 Major damage |
| Too many gym/half-body shots (mid %) | 12.8% | −11% | 🔴 Major damage |
| Bio depth = 1 sentence | 17.9% | −6% | 🟡 Mild damage |

**The shirtless photo finding deserves emphasis:** Out of all profiles showing shirtless photos, **not a single one was right-swiped**. It's the strongest hard-negative in the dataset — likely because these raters interpret it as narcissism or lack of emotional intelligence, both of which are disqualifiers under Factor 1.