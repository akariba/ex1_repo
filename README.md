# ex1_repo


Summary: XVA Equity Inclusion Discussion

The TDD has been updated to include credit spread, but equities are not yet covered.
To include equities in the XVA volatility framework, the TDD will need an additional update once the equity details are finalized.

Data Requirements:

XVA Pricing: Requires only implied volatility (point-in-time).

XVA VAR: Requires historical time series data for backtesting and simulations.

Agreed Development Sequence:

Develop XVA pricing model (including equity).

Obtain Pricing GMV approval.

Complete equity VAR framework (Phase 3A).

Develop equity XVA VAR framework (dependent on #3).

Current Status:

XVA pricing model development is in progress; target go-live end of November (GV timeline).

Pricing model approval will follow once finalized.

Equity VAR framework (Phase 3A) is ongoing, and XVA VAR work will begin afterward.

Dependencies:

Phase 3A completion is needed for single-name volatilities and VAR coverage.

Pricing GMV approval required before XVA pricing go-live.

Historical data must be confirmed for XVA VAR.

Operational Risk:

Once the XVA equity pricer goes live, unapproved equity trades could feed into XVA VAR.

These must be filtered out until model approval.

Sven to confirm technical handling with Xihong and send a note.

Actions & Next Steps
Action	Owner	Due / Notes
Update TDD to include equities once details are confirmed	Kelly	After equity XVA details finalized
Provide XVA pricing model inputs and documentation	Alvin / Wenbin	Before November release
Confirm go-live plan for equity XVA pricing	GV / Sven	Target: End of November
Confirm VAR filtering for unapproved trades	Sven (with Xihong)	Before go-live
Extend documentation with implementation plan (Section 5)	Alvin	Next draft
Confirm dependency and sequencing with 3A team
