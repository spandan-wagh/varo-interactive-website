# Literature Review

## Conceptual background

Interaction latency is the delay between a user's physical action and the corresponding visible response of the controlled object. It is not interchangeable with network round-trip latency, display refresh rate, or an anticipated delay between acting and affecting a moving target. This distinction is essential because the reviewed studies delay different parts of the interaction loop. Claypool, Cockburn, and Gutwin (2020) inserted mouse-and-click delay on top of a measured baseline; Wang, Sabiston, and Welsh (2026) added hand-to-virtual-hand delay on top of native motion-to-photon latency; Pavlovych and Gutwin (2012) reported network round-trip latency produced by delaying the displayed remote target and the click event. These manipulations create related but non-equivalent control problems.

Latency is especially consequential when performance depends on closed-loop visual control. During target acquisition, an initial movement or shot can be guided by prediction, but later adjustments depend on delayed visual information about the target and the user's aim. Aggregate outcomes such as completion time or endpoint error can therefore conceal whether latency affected the initial acquisition, later correction, or both.

## Interaction latency and target acquisition

The reviewed evidence establishes that latency can impair target-directed performance across several paradigms. Claypool et al. (2020) found strong delay effects on selection time and cursor-to-target distance at click in a desktop game-like moving-target task. Wang et al. (2026), currently a preprint, reported latency-related changes in endpoint error, endpoint variability, movement time, and throughput during immersive-VR pointing to static targets. The authoritative record for Wei et al. (2026) establishes that latency has also been studied in VR target selection using controller-based raycasting and bare-hand direct touch, with selection time, success rate, and endpoint distributions among the reported outcomes.

These studies do not justify treating latency as a single additive cost. Claypool et al. showed that its effects depended on target-motion parameters, while Wang et al. reported different response patterns for spatial and temporal measures. The available evidence therefore supports examining multiple behavioral outcomes instead of relying on a single overall acquisition-time measure.

## Moving-target latency literature

Latency with moving targets is already established. Claypool et al. (2020) experimentally crossed controlled input delay with two target-motion parameters: jink angle and jink interval. Delay interacted significantly with both parameters for selection time and spatial accuracy. This is the closest verified precedent for the core causal structure of latency interacting with motion characteristics during game-like acquisition.

Pavlovych and Gutwin (2012) studied mouse-based acquisition and tracking of moving Lissajous targets at four target speeds and three path-complexity levels. The four reported latency values—20, 50, 110, and 170 ms—were network round-trip latency values, not added local cursor latency. Their full paper shows that latency affected acquisition attempts and directional acquisition and tracking errors, and that some latency costs depended on target speed. The study also separated longitudinal error (ahead of or behind the target) from transverse error, providing a useful precedent for examining time-varying target-relative error rather than only a final outcome.

Neither study provides a clean test of latency by independently manipulated predictability. In Claypool et al., jink parameters changed motion dynamics and effective target speed as well as predictability. In Pavlovych and Gutwin, greater path complexity was related to reduced predictability but also changed instantaneous-velocity characteristics. Their results establish latency-by-motion-dynamics precedents, not an orthogonal latency-by-predictability effect.

## Predictability and delay adaptation

Rohde, van Dam, and Ernst (2014) provide the strongest verified evidence that predictability matters under delayed visual feedback. In their nonimmersive manual-tracking paradigm, the underlying reference trajectory was held constant while the visible information differed: one condition exposed only the current reference position, whereas another revealed future and past trajectory information. Adaptation to delayed feedback depended on this predictability manipulation.

This work supports treating predictability as a sensorimotor construct rather than as a synonym for target speed or path complexity. It also indicates that a person may use predictive information to compensate for delay. However, Rohde et al. did not study rapid competitive acquisition, first-shot success, or detailed online corrective aiming, and the paper explicitly did not investigate the higher-frequency components associated with corrective movements.

## Immersive VR latency research

Immersive-VR target-directed interaction under latency is not unexplored. Wang et al. (2026) used immersive VR with a virtual hand and experimentally added interaction delay during pointing to static targets. The reported spatial and temporal effects demonstrate that controlled delay can alter target-directed performance in an HMD environment. Because this work is an arXiv preprint, it should be treated as current primary evidence rather than peer-reviewed consensus.

Wei et al. (2026) is a peer-reviewed VR target-selection precedent. Its authoritative record and abstract support only a restricted summary here: the work examined latency in VR selection using controller raycasting and bare-hand direct touch and reported selection-time, success-rate, and endpoint-distribution outcomes. Its full methods and results were not available in the supplied verification record, so exact latency conditions, hardware, target motion, predictability manipulation, and inferential details are not asserted.

Together, Wang et al. and Wei et al. prevent any claim that latency in immersive VR target selection is new. They do not, on the evidence available here, establish the specific combination of independently manipulated moving-target predictability, rapid competitive acquisition, first-shot accuracy, and online corrective aiming behavior.

## Competitive and FPS latency research

FPS latency has also been studied. The authoritative record for Ivkovic et al. (2015) supports that the authors measured local latency in real-world gaming configurations and conducted a controlled FPS targeting-and-tracking experiment under varying local latency. The abstract reports substantial performance degradation even at 41 ms and evaluation of an aim-assistance compensation technique. Because the full article was not recovered in the supplied evidence, the exact experimental latency vector, apparatus, target trajectories, predictability conditions, participant details, and inferential statistics are left unspecified.

Claypool et al. (2020) adds a game-like acquisition precedent, though in a 2D mouse task rather than an immersive FPS task. These studies show that neither FPS latency nor latency during game-target selection can serve as the project's novelty claim.

## Synthesis

The literature already contains the relevant ingredients in adjacent combinations: latency with moving game targets (Claypool et al., 2020; Pavlovych & Gutwin, 2012), predictability-dependent adaptation to delayed visual feedback (Rohde et al., 2014), latency during immersive target-directed interaction (Wang et al., 2026; Wei et al., 2026), and controlled FPS aiming under local latency (Ivkovic et al., 2015).

What remains unresolved within the reviewed evidence is whether system-induced controller-to-weapon latency interacts with an independently manipulated target-motion-predictability factor during rapid immersive HMD target acquisition, and whether any such relationship appears differently in acquisition time, first-shot accuracy, and online corrective aiming behavior. This is a conservative gap at the intersection of established literatures, not a claim that latency, moving targets, FPS aiming, immersive selection, or latency-by-predictability relationships have never been studied.

