# evo-device-audio-ui

Public release repository for the evo reference audio-device UI layer.

## Purpose

`evo-device-audio-ui` is the reference-device shell and packaging layer for audio-focused deployments on evo.

It is the "device release layer" that composes:

- generic UI platform capabilities (from `evo-ui`)
- audio-domain contracts and surfaces (from `evo-device-audio`)
- gateway/runtime interaction contracts (from `evo-core`)

## Position in the repo model

- `evo-ui-eng`: private generic UI engineering/prototyping
- `evo-ui`: public generic UI release stream
- `evo-device-audio-ui` (this repo): public reference audio-device UI release stream

## Scope

- Ship the reference `ui_shell` experience for the audio reference device.
- Remain vendor-neutral at reference-device level.
- Demonstrate the full showcase interaction model (framework + plugins + device UX).

## Ownership and marks

`evo` and `evoframework` names/marks are controlled by the project owner.  
See `TRADEMARK.md` for usage guidance.

## License

Licensed under Apache License 2.0 unless stated otherwise.  
See `LICENSE` and `NOTICE`.
