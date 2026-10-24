# critter comforts: cozy cove

> i just want a pet robot lowkey.

a cozy, local-first companion world in unity: characters who live inside your computer, talk with you through a local ai model, and (eventually) help you keep track of daily life.

<img width="882" height="560" alt="cozy cove: a vrm companion character standing in the unity scene with a speech bubble" src="https://github.com/user-attachments/assets/21c1c6fd-7aea-4d25-a9bd-d9173eb94378" />

## works today

- **local ai chat:** talks to any openai-compatible endpoint (for example ollama) with per-companion memory.
- **vrm characters:** import your own avatar, click to select, drag to place, cycle through 18 built-in poses.
- **speech:** world-space speech bubbles that follow the character's head, animalese-style voice or optional tts, and microphone input with device recovery.
- **camera:** full-body, conversational, and tv-style framing.

the unity project compiles and passes a batch-mode pose-loading check (`project/Assets/Editor/PortfolioVerification.cs`). the browser and dialogue prototypes in `project/examples` are built and tested in github actions.

## run it

1. open `project/` in unity hub with **unity 6000.5.4f1** and let package manager restore dependencies.
2. open [`SampleScene`](project/Assets/Scenes/SampleScene.unity) and press play.
3. import a vrm you have rights to, and point chat at your local model endpoint.

[setup and controls](project/docs/setup-and-controls.md) lists every control and default setting. the possum springs scene needs a fan-made environment you download yourself; see [its attribution note](project/Assets/Environments/PossumSprings/ATTRIBUTION.md).

## where it's going

the plan is a small crew of characters, each with its own job (an assistant, a chef, a coach, a librarian, and more) and its own voice and memory, sharing context through an obsidian vault. the [roadmap](ROADMAP.md) breaks this into epics and sprints with acceptance criteria. none of the crew roles are built yet.

## earlier versions

the same idea in other forms:

- [three.js/typescript browser world](project/examples/browser-world)
- [gamecube dialogue prototype](project/examples/gamecube-dialogue): model-generated dialogue injected into animal crossing running in dolphin
- [how the project evolved](https://github.com/lenovo-jojo/portfolio/blob/main/case-studies/companion-evolution.md)

## notes

built with ai assistance; i direct the design, characters, and behavior. personal avatars, recordings, logs, and credentials are not in this repository. © jojo, all rights reserved except third-party components; see [license](LICENSE).
