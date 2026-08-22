# rrr-cloud-runner

Public **GitHub Actions** runner so Really Raised Rough can post and create products with the laptop off.

- **No tokens in this repo.** Secrets live in Actions secrets.
- Schedule + fired state live in the **private** pack repo `IamMrZam/rrr-always-on`.
- This host runs at minute `:05` and `:35`. The private host (if GitHub starts those runners) runs `:17` and `:47`.
- Shared `fired.json` claims: if one host does not finish a slot, the other picks it up. Successful posts are not duplicated.
- Printify: 1 existing-art product + 1 new design per ISO week, split the same way.

Controls stay in Start Jarvis → RRR.
