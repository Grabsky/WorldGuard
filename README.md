# WorldGuard Fork  
This is a fork of **[WorldGuard](https://github.com/EngineHub/WorldGuard)** plugin which I maintain for my server until I can fully switch to a suitable alternative.  

Artifacts can be downloaded from **[GitHub Actions](https://github.com/Grabsky/WorldGuard/actions/workflows/gradle.yml)**.

## Changes
- Plugin does not register any commands except for the `/worldguard` and `/region`. Command aliases have been removed.
- Command `/region info` lists each flag in a separate line.
- Merged `1.21` support to the `master` branch.
- Merged `1.21.3` support to the `master` branch.
- Merged `1.21.4` support to the `master` branch.
- Merged `1.21.5` support to the `master` branch.
- Some spawn reasons are allowed when `mob-spawning` flag is set to `deny`.
- Customized denied command message.
- Removed checkstyle.