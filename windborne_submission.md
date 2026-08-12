# WindBorne ML Research Engineer Application — Shibasis Roy

**1. Role preference**
Model Evaluation. My research is fundamentally about separating rare real signal from background fluctuation under poor statistics — e.g. a Bayesian test showing an apparent theory-experiment excess was actually a statistically insignificant fluctuation (<2σ). That said, I'd be equally glad to contribute to General or Applied Research.

**2. Failed ML idea**
Aurora sightings were strongly concentrated within a specific magnetic-local-time (MLT) range in empirical observation, so I expected adding MLT as a feature would give a large boost to a visibility classifier's test scores. In practice, the gain was only marginal and the pattern didn't translate into meaningful predictive improvements when combined with the other features. 

**3. Sidequest**
I wasn't asked to re-audit citizen-science data sourcing, but noticed low accuracy in an aurora-visibility model. Rather than trust the obvious explanations (positive reporting bias), I traced it to two subtler causes: incorrect sun-elevation/darkness calculation, and sightings keyed on report timestamp instead of the more accurate time-start field. Fixing both drove the real improvement.

**4. Weather forecasting paradox**
A model can minimize average error and still fail at its job if error is smoothed evenly, hiding failure on rare extremes. Clear when splitting aurora visibility into three magnetic-latitude bands: a global model optimized for aggregate accuracy performed poorly, since bands show opposite trends. Per-band models, despite far less training data each, predicted rare cases much better.

**5. LLM workflow evolution**
Started using AI tools for quick lookups and debugging. Now I treat their output the way I'd treat a comparative model result: don't trust it at face value, actively re-verify claims and re-derive results myself without exceptions. That habit has caught real errors.

**6. Favorite ML Twitter account**
@ScarbsTech (Craig Scarborough) — F1 technical/data analysis, not strictly ML but the closest thing I actually follow.
