Here you'll find my independent projects.

- B.S. in Applied Mathematics
- Currently pursuing Master's in Applied Data Science

- What I’m working on now:

I’m building NullCS which is a data-driven tool to identify signals that resemble cheating from Counter-Strike 2. The core pipeline parses `.dem` , isolates a target player by SteamID, and generates structured, tick-level features around key events (e.g., pre/post kill windows). The goal is to flag suspicious gameplay patterns and surface explainable signals (aim behavior, positioning, visibility, “through-smoke” interactions, etc.). It is currently in Pre-Alpha, thus any output from NullCS is not definitive proof of cheating, and neither will the 1.0 version. The goal of this is to be an assistive tool by surfacing unbiased and raw telemetry data from gameplay to bolster evidence of potential cheating. Do not harass or intimidate any players/SteamIDs that get flagged by the system.

**Current focus**
- Expanding the dataset (more verified cheater demos) and improving generalization  
- Feature engineering + handling class imbalance (rare positive windows)  
- Model evaluation that’s practical: ranking top suspicious events and aggregating to match-level decisions  
- Building a simple web front-end so users can upload a demo and get a report

If this interests you, check out the **NullCS** repository for the latest work.

