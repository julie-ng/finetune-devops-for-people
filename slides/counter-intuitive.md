# Counter Intuitive

---

# Deploy Often

- Friday Afternoon, git push!
- Ops team elsewhere (often Asian, EE) - alarms go off

---

# Deploy Less

Example: Allianz

- Goal: 9-5 working hours
- How often do you deploy? Once every 2 weeks
- Go to work at 5am - and deploy
- Leave work at 12pm


---

# Only deploy via Pipelines

- what happens if it breaks?
- network locked down too (thanks Microsoft!)


---

# GitOps is Overrated

- how many repos do I need?
- benefit: security, everything locked down
- con: how do I debug?
- con: made urgent fix in production, gitops rolls it back*


Note:
*if using flux? Argo is diff.


--- 

# DevSecOps

- secret: no one actually knows what it means
- people just turn it off, e.g. OWASP
  - because no one spent time teaching how to understand results, fix.
- IRL
  - diff. between dev dependencies and production
  - dependendabot overload…
  - most people don't have unit tests
  - pre-commit hooks - might take too long. use pre-push if you need this.


---

# Overrated? Auto-downscaling Dev/Staging

- if you can do it easily fine. Don't put too much effort
- go through calculation of person 1k/day (*10 persons) vs optimizing for 100/month?


---

# Monitoring?

- blackbox vs whitebox