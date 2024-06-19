<h1 align="center">
  <a href="https://lpm.media.mit.edu/" target="_blank">
    Large Population Models
  </a>
</h1>

<p align="center">
  <strong>making complexity simple</strong><br>
  differentiable learning over millions of autonomous agents
</p>

<p align="center">
  <a href="https://github.com/AgentTorch/AgentTorch/blob/master/license.md" target="_blank">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="Released under the MIT license." />
  </a>

  <a href="https://agenttorch.github.io/AgentTorch/" target="_blank">
    <img src="https://img.shields.io/badge/Quick%20Introduction-green" alt="Documentation" />
  </a>
  <a href="https://twitter.com/intent/follow?screen_name=ayushchopra96" target="_blank">
    <img src="https://img.shields.io/twitter/follow/ayushchopra96?style=social&label=Get%20in%20Touch" alt="Get in Touch" />
  </a>
  <a href="https://join.slack.com/t/largepopulationmodels/shared_invite/zt-2jalzf9ki-n9nXG5FryVSMaPmEL7Wm2w" target="_blank">
     <img src="https://img.shields.io/badge/Slack-4A154B?logo=slack&logoColor=white" alt="Join Us"/>
  </a>
</p>

Large Population Models (LPMs) help simulate million-size populations by
designing realistic environments and capturing expressive indvidual behavior.
Our goal is to "re-invent the census": built entirely in simulation, captured
passively and used to protect country-scale populations. Our research is early
but actively making an impact - winning awards at AI conferences and being
deployed across the world. Learn more about LPMs
[here](lpm.media.mit.edu/research.pdf).

AgentTorch LPMs have four design principles:

- **Scalability**: AgentTorch models can simulate country-size populations in
  seconds on commodity hardware.
- **Differentiability**: AgentTorch models can differentiate through simulations
  with stochastic dynamics and conditional interventions, enabling
  gradient-based learning.
- **Composition**: AgentTorch models can compose with deep neural networks (eg:
  LLMs), mechanistic simulators (eg: mitsuba) or other LPMs. This helps describe
  agent behavior using LLMs, calibrate simulation parameters and specify
  expressive interaction rules.
- **Generalization**: AgentTorch helps simulate diverse ecosystems - humans in
  geospatial worlds, cells in anatomical worlds, autonomous avatars in digital
  worlds.

AgentTorch is building the future of decision engines - inside the body, around
us and beyond!

https://github.com/AgentTorch/AgentTorch/assets/13482350/4c3f9fa9-8bce-4ddb-907c-3ee4d62e7148

## Installation

Install the framework using `pip`, like so:

```sh
> pip install git+https://github.com/agenttorch/agenttorch
```

> Some models require extra dependencies that have to be installed separately.
> For more information regarding this, as well as the hardware the project has
> been run on, please see [`docs/install.md`](docs/install.md).

## Getting Started

AgentTorch provides the following functionalities:

#### 1. [Using Differentiable Utilities](docs/guides/differentiable-utilities/index.md)

#### 2. [Creating Models](docs/guides/creating-models/index.md)

#### 3. [Using Existing Models](docs/guides/using-models/index.md)

#### 4. [Creating and Using Population Data](docs/guides/population-data/index.md)

#### 5. [Capturing Individual Behavior with LLMs](docs/guides/population-behavior/index.md)

#### 6. [Gradient Based Calibration of Models](docs/guides/gradient-calibration/index.md)

#### 7. [Analyzing Models](docs/guides/analyzing-models/index.md)

## Documentation

The complete documentation can be found at
[lpm.media.mit.edu/docs](https://lpm.media.mit.edu/docs).

## Contributing to Agent Torch

Thank you for your interest in contributing! You can contribute by reporting and
fixing bugs in the framework or models, working on new features for the
framework, creating new models, or by writing documentation for the project.

Take a look at the [contributing guide](docs/contributing.md) for instructions
on how to setup your environment, make changes to the codebase, and contribute
them back to the project.

## Impact

> **AgentTorch models are being deployed across the globe.**

![Impact](docs/media/impact.png)
