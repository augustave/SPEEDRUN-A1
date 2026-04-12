# Node Graph Spec

## Goal
Translate the existing browser composition into a node-based authoring model that preserves what is already effective while creating clean attachment points for future semantic logic.

## Current Browser Logic Decomposition
- Asset ingest
  - One logo texture
  - Five photographic backplates
- State and timing
  - Global pulse oscillator
  - Background crossfade timer
  - Glitch cadence timer
  - Pointer velocity smoothing
  - Burst decay
- Motion layers
  - Radial warp streak field
  - Background speed-line field
  - Foreground speed-line field
  - Curved emitter paths
  - Particle pool with short trails
  - Node web with neighbor cache and pulse travelers
  - Logo echo stack and chromatic split
  - Vignette and scanline post layer

## Recommended Graph Groups
### 1. `INPUT_ANALYSIS`
- Pointer or controller input normalization
- Velocity smoothing
- Dwell timer placeholder
- Burst trigger latch

### 2. `STATE_MACHINE`
- `idle`
- `agitated`
- `confirming`
- `transition`
- `recovery`

The existing runtime only truly implements `idle`, `agitated`, and `transition-like burst`.

### 3. `MEDIA_PLATES`
- Backplate loader
- Crossfade blend
- Exposure and tint normalization
- Provenance metadata note for each plate

### 4. `WAKE_SYSTEM`
- Radial streak instancer
- Horizontal line instancer
- Emitter spline sampler
- Particle simulation with lifetime-based thickness

### 5. `NETWORK_SYSTEM`
- Node position solver
- Neighbor lookup cache
- Pulse traveler subgraph
- Semantic binding inlet

This is where future telemetry should enter. In the current project, this entire block is visual-only.

### 6. `BRAND_ANCHOR`
- Logo texture treatment
- Echo buffer
- Chromatic split
- Timed glitch slicer
- State badge mode for future off-center placement

### 7. `POST_AND_DISCLOSURE`
- Scanlines
- Vignette
- Edge tint
- Optional disclosure card or state label overlay

## Parameter Mapping
- Pointer velocity maps to:
  - streak boost
  - particle emission rate
  - logo chromatic offset
  - local node attraction
- Burst maps to:
  - flash amplitude
  - shake amplitude
  - warp-speed multiplier
  - glitch trigger

## Required Semantic Additions For A Real Prototype
- Named node identities
- Explicit lane or chapter definitions
- Transition conditions
- Success and failure states
- Logging or telemetry input
- A disclosure flag that separates mock data from live data

## Output Targets
- Desktop hero loop output at `16:9`
- Control-room or event-wall version with reduced interactivity
- XR debug mirror with labels turned on

## Runtime Caveat
Do not port the graph one-to-one into XR and assume it becomes immersive. The current composition is layered 2D motion. The graph only becomes spatial once target depths, comfortable focus zones, and intent-bearing interactions are explicitly added.
