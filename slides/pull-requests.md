<!-- .slide: data-background-image="../images/stop-light.jpg"  class="chapter-heading-right"  -->

# Pull Requests<!-- .element: style="background: rgba(0, 0, 0, 0.8); display: inline-block" -->

Best Practice?

---

Placeholder: GitHub Screenshot

- Peer review
- Automated tests for better quality
- Combine with Branch protection for more security

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

<!-- .slide: data-background-image="../images/minku-kang-5d2QJl88QbI-unsplash.jpg" class="foo" -->

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

<img src="../images/pr-kief-tweet.png" width="600">

---

### Stuck in a Loop?

<img src="../images/devops-pr-workflow.png" width="700">

---

### Lower Velocity, Less Business Value

<img src="../images/az-internal-repo.png" width="700">

Note:
- internal repo, screenshot this morning
- for _daily work_
- 26 days ago? Slow
- 54 stuck PRs
- 16 projects


---

### How to Deploy Everyday

<img src="../images/velocity-matteo-1.png" width="500">

<img src="../images/velocity-matteo-2.png" width="500"><!-- .element: class="fragment" -->

Note:
- overnight deployments every 2 weeks
- EVERY DAY!
- Trust


---

### Team Decides

<img src="../images/atc-when-to-deploy.jpg" width="700">

Deploying at night… yay or nay?<!-- .element: class="caption-font" -->

---

Now that we cover security can backfire… let's look at DevSecOps, best of intentions…

Note:
- Trust your team… but others?