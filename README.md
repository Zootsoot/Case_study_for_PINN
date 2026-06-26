## Case Description

This case study reproduces the **cold-flow field of the Sydney swirl burner** using a physics-informed neural network (PINN)-based approach. The Sydney swirl burner is a widely used benchmark configuration for studying swirling jet flows, recirculation zones, and turbulence-dominated flow structures under non-reactive and reactive conditions.

The present study focuses on the **non-reactive cold-flow condition**, where air is issued from the central jet at a prescribed velocity. Two representative swirl configurations are considered:

| Case    | Flow Type       | Jet Fluid | Jet Velocity | Swirl Number |
| ------- | --------------- | --------: | -----------: | -----------: |
| N16S159 | High swirl flow |       Air |       66 m/s |         1.59 |
| N29S054 | Low swirl flow  |       Air |       66 m/s |         0.54 |

The high-swirl case, **N16S159**, represents a strongly swirling jet condition and is expected to produce a more pronounced internal recirculation zone. In contrast, the low-swirl case, **N29S054**, has a weaker swirl intensity and therefore exhibits a different jet-spreading and recirculation behavior.

### Burner Configuration

The burner configuration and schematic are shown below.

![Burner configuration](figs/burner_config.png)

### Operating Conditions

The operating conditions for the two selected cold-flow cases are summarized below.

#### High Swirl Case: N16S159

![High swirl operating condition](figs/high_swirl_case.png)

#### Low Swirl Case: N29S054

![Low swirl operating condition](figs/low_swirl_case.png)

> References: **https://web.aeromech.usyd.edu.au/thermofluids/swirl.php**
