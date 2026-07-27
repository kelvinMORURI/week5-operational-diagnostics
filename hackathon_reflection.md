# Hackathon #1 Reflection

**Analyst:** Kelvin Moruri
**Project:** KPC Downtime Reduction — Stage 1 (ETL pipeline, quality gates, scheduler + mock ticketing API integration)
**Team:** Kelvin Moruri, ChepkiruiBrenda, nyankwoga, umarndungo

Our biggest technical hurdle wasn't the data engineering itself — it was git. With four of us working in parallel on separate branches, we added a git submodule pointing at an external repo partway through the build, and it broke checkouts for teammates who pulled after that point. Combined with divergent work on `master` and `main`, we ended up with conflicting versions of core files, including the README being edited independently by different people within the same hour. Rather than untangle a deep merge conflict under time pressure, we resolved it pragmatically: copied the working files from `master` straight into `main` to get back to one clean, running source of truth, dropped the submodule dependency, and I spent the final stretch improving code comments and documentation so the repo was coherent for judges even though the git history wasn't pretty.

Next hackathon, I'd push the team to agree on a branching strategy and avoid submodules entirely before writing any code, and to merge via small, reviewed pull requests throughout rather than large parallel branches reconciled at the end. Cheap to set up early, expensive to skip.

*(Word count: ~198)*