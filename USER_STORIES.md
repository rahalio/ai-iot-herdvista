# HerdVista — User stories

**Product:** [PRODUCT.md](./PRODUCT.md)


### Edge vision engineer

- As an edge vision engineer, I want multi-object tracks at sustained FPS on Max-Q, so outdoor poles last on battery.
- As an edge vision engineer, I want onboard benchmark sequences, so I can accept a node before climbing the pole twice.

### Site reliability operator

- As an SRE, I want watts and FPS telemetry, so I know whether heat throttling killed tracking overnight.
- As an SRE, I want OTA rollback when a model drops below the site FPS SLA, so security coverage returns quickly.

### Operations analyst

- As an operations analyst, I want stable track IDs across brief occlusions, so counts and paths are usable.
- As an operations analyst, I want confidence and foreground masks for disputed events, so I can explain false tracks.

### Privacy officer

- As a privacy officer, I want raw video retained only ephemerally on-node, so the product is tracks-as-a-service not a covert camera cloud.
- As a privacy officer, I want purpose tags on each stream, so a traffic study cannot silently feed law-enforcement retention.

### Program owner

- As a program owner, I want % of frames processed without cloud offload, so we can prove edge ROI against backhaul bills.
