# limit-warning

- Schedule: `0 20 * * *` (local timezone)
- Name: usage-limit-watch

Check only the weekly limit %.

If it is at or above 80% and you have not already warned the user this cycle, also check the per-bot breakdown and send one short warning with the % used, the reset time, and the top 3 bots.

Otherwise send nothing.
