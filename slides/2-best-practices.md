# Best Practices

# or Checklists? <!-- .element: class="fragment" -->

Note:

- Gotta catch 'em all
- Analysis Paralysis

---

# Trends

- Continuous Integration
  - Unit Tests, Linting
- Pull Requests
  - wait hours for tests to pass
  - wait days for someone to approve
  - 10 million from dependabot

---

# Slide Idea

Point: frustration

- `git checkout main && git merge feature`
- `git push`
- Open a Pull Request
- Opens Pull Requst
- `#signoff`
- `#signoff`
- `#signoff`
- Give Up & Close Pull Request

---

# Slow PRs

- `git push`
- waiting for build agent…30 sec
- waiting for build agent…30 sec
- opens Twitter (MEME)
- 60 minutes later
- Build Failed. No deployment, no value Add.

Note:
- shared agents, pricing plan

---

# How It Should Be

- Pull Requests is like Airport security
- Do you want to make family go thorugh airport security 10x a day?
- We want to deploy, e.g. fly 100 times day, but we handcuff ourselves
- If you trust your team --> do you really need a pull request?
- When do you need it? Open Source, fork + PR workflow
  - Be aware: PR = security back door!
  - GitHub protects with Secrets
  - Azure Pipelines: paranoid checks…
- Theory: Pull Request != Quality or Craftsmanship

---

# Maybe Failing builds are good?

Radical idea
- let builds fail
- end of day - make build green together?
- Pair Programming - underrated, esp. now that everyone works remote
- but how I learned the most…
- diff. between failing dev and failing production (show GitHub article about security fixes)

Note: 

- not pair program every day. Just every now nad then.