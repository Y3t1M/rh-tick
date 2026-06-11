# rh-tick
Precision scheduler trampoline. GitHub `schedule` crons are best-effort (and have
delivered zero runs on the private repo this serves); this repo's sleeper chain IS
the clock: wake at slot → dispatch → re-arm. No market data, no strategy, no secrets
in code. Slots (America/Chicago, DST-aware): 7:05 full · 8:10 · 9:45 · 11:45 · 1:45 · 2:45 weekdays.
