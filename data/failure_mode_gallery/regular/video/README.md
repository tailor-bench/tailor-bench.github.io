# Failure Mode Definition

## F1: Temporal Inconsistency
The generated video exhibits inconsistencies across frames that break temporal coherence. Objects may change shape, position, or identity abruptly without a physically valid cause. These artifacts include object flickering, unstable geometry, or sudden appearance and disappearance of elements. As a result, the sequence fails to depict a stable and continuous interaction.

## F2: Implausible Dynamics
The generated interaction violates realistic physical motion or state transitions. Although the correct objects may be present, their movements or responses do not follow plausible physical dynamics. For example, forces may not propagate correctly, motion trajectories may appear unnatural, or the interaction fails to produce the expected physical effect.

## F3: Interaction Misexecution
The generated video fails to correctly execute the intended interaction described in the prompt. While the relevant objects may appear in the scene, the action is performed incorrectly, incompletely, or in an unintended manner. As a result, the interaction does not lead to the expected outcome or state change.

# Examples

## F1 (Descriptive)
The nutcracker and the walnut exhibit unstable geometry during the crushing phase, breaking temporal coherence.

## F1 (Predictive)
The screwdriver tip and the screw head do not maintain a stable relative position.

## F2 (Descriptive)
The scraping motion against the wooden surface fails to demonstrate plausible force propagation, as the white material lifts away without resistance, indicating a violation of realistic physical dynamics.

## F3 (Predictive)
The corkscrew is rotated into the bottle, but the interaction lacks realistic physical response.

## F2 (Descriptive)
The way to use nutcracker is incorrect.

## F3 (Predictive)
The scissors are positioned near the cardboard box, but they fail to engage with the packing tape, performing a cutting motion in the air that leaves the package sealed and the interaction misexecuted.