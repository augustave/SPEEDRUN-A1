# Prototype Brief

## One-Sentence Reduction
The current project is a browser-native velocity ident for `a16z / speedrun` that successfully conveys energy and brand intensity, but it does not yet teach a product, platform, or interaction model.

## Audience
- Creative and brand stakeholders deciding whether the piece should remain an ambient hero loop or evolve into a more explanatory prototype.
- Technical artists or motion designers who may need to port the composition into a node graph or XR sandbox.
- Engineers evaluating what logic is real in the current runtime versus what is only implied by the visuals.

## Current System Read
Core entities observed in the shipped build:
- One centered logo with glow, echoes, chromatic split, and timed glitch behavior.
- Five motorsport-style photographic backplates rotated as low-opacity atmospheric plates.
- A radial warp tunnel, two depth bands of horizontal speed lines, emitter-driven particles, and a decorative energy web.
- A pointer-driven reactivity layer where motion increases visual turbulence and click or touch triggers a burst state.

Core states:
- `loading`
- `idle pulse`
- `pointer agitation`
- `burst surge`
- `background crossfade`
- `intermittent glitch`

Core triggers:
- Asset preload completion
- Pointer movement magnitude
- Timed background rotation
- Timed glitch cadence
- Mouse press or touch press
- Window resize

## Core Teaching Objective
After seeing the demo, the audience should understand one thing: `speedrun` is being framed as a fast, high-pressure, high-signal brand experience.

That objective is currently achieved at an emotional level, not at a systems level.

## Evaluation
### What is working
- The composition is disciplined around a single anchor: the centered `speedrun` mark never loses visual priority.
- Motion layering is coherent. Warp streaks, lateral lines, particle wakes, and logo aberration all reinforce the same velocity thesis.
- Pointer motion changes the piece quickly enough to feel responsive without requiring UI chrome or explicit controls.
- The project already behaves like a finished hero loop or event-screen ident rather than a loose sketch.

### What is missing
- The animation does not explain a workflow, platform, editorial system, or decision model. The energy web looks semantic, but it is only decorative.
- There is no scene progression. The piece remains one continuous affective state instead of teaching setup, signal, choice, and consequence.
- User input vocabulary is too shallow for spatial translation. Pointer movement and click burst are agitation controls, not meaning-bearing interactions.
- There is no explicit disclosure of what is simulated, what is generative, and what corresponds to real system logic.
- The current build is desktop-browser motion design, not XR. There is no depth grammar, focus model, dwell model, or comfort strategy.

## Readiness Scorecard
- Motion coherence: `7/10`
- Brand legibility: `8/10`
- System explainability: `2/10`
- Spatial interaction readiness: `3/10`
- Runtime honesty and disclosure: `4/10`

## Interaction Thesis
If the project is extended into a spatial prototype, the correct thesis is not "make it more immersive." The correct thesis is "turn velocity into navigable telemetry."

Recommended spatial metaphor:
- A forward-moving signal lane in which each layer becomes meaningful: wake trails become activity traces, web nodes become decision points, and the logo becomes a chapter/state anchor instead of a permanently centered stamp.

Recommended spatial interaction model:
- Primary input: gaze dwell on oversized lane markers or chapter nodes.
- Fallback input: controller trigger or low-fatigue pinch confirmation.
- Confirmation model: two-step selection for any transition that materially changes the scene.

## Visual Direction Options
### 1. Editorial Velocity
High-contrast black field, racing imagery, chromatic splits, scanlines, and title-card authority.

### 2. Telemetry Cathedral
Reduce the photographic plates and turn the project into a luminous instrumentation chamber where all motion traces correspond to data states.

### 3. Founder Launch Corridor
Treat each lane as a company trajectory with acceleration, bottlenecks, and milestone gates.

### 4. Signal Wake
Keep the current motorsport energy, but make wake trails, pulses, and node connections correspond to actual causal events.

Selected direction:
- `Signal Wake`

Reason:
- It preserves the strongest part of the current build, which is the feeling of relentless forward movement, while creating a clean path toward more truthful system mapping.

## Recommendation
Keep the current project as a hero ident unless there is a concrete product story to teach.

If the brief is to evolve it into a prototype, do not add more spectacle first. Rebuild around a three-beat narrative:
1. Establish the lane and the state of the system.
2. Show a deliberate selection or intervention.
3. Visualize the resulting acceleration, reroute, or failure state.

## Immediate Next Moves
- Recast the energy web into named entities and explicit transitions.
- Replace passive background cycling with chapter changes tied to scene state.
- Move the logo out of permanent center-lock during explanatory segments.
- Add a reduced-motion mode and an input legend if the browser version remains public-facing.
