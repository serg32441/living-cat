Rive authoring contract for Living Cat
=====================================

Export your character as `assets/rive/cat.riv` with:

- Artboard: Cat
- State Machine: CatStateMachine

Boolean, trigger, and number inputs are listed in `cat_state_machine.json`.

Until a designer-authored `.riv` is present, the app uses `CatRiveController`
(the same inputs) plus the procedural 2.5D cat renderer. Missing Rive inputs
never crash the app.
