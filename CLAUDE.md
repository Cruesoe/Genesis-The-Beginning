@../_ModKit/CLAUDE.md

# Genesis: The Beginning

The Genesis suite's starting scenario, split out of Genesis: Core on 2026-09-11 so the
scenario can be subscribed to (or skipped) independently of the Core patch set. See
`../Genesis/CLAUDE.md` for suite-level conventions.

XML-only: no assembly, no `Directory.Build.props`/`.targets`, nothing to build. The whole
mod is [Defs/Scenarios/TheBeginning.xml](Defs/Scenarios/TheBeginning.xml). Deploy with
`Publish-Mod`.

Vanilla Factions Expanded - Tribals is a hard dependency: the scenario uses its
`VFET_WildMen` faction and `VFET_GameStartSting_WildMen` sound.
