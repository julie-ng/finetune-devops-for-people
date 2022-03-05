Too much

- https://owasp.org/www-pdf-archive/OWASP_SCP_Quick_Reference_Guide_v2.pdf
- giant checklist, learn permanently requires slow. you learn by making mistakes.


Other pages
https://www.cloudbees.com/blog/8-cicd-best-practices-your-devops-journey --> on demand testing environments 🤮

Underrated
- Documentation as part of release
- Changelogs & Commit messages
- JSDoc, API Doc, schema.
  - Compare MSFT & Stripe API, Github API?
  - Microsoft https://docs.microsoft.com/en-us/rest/api/storageservices/create-container    
  - Better: https://docs.github.com/en/rest/reference/code-scanning#list-instances-of-a-code-scanning-alert
  - My Favorite: https://stripe.com/docs/api/subscriptions/update



### Things I don't like…
- microservices?
- gitops w/ diff. Config repo
- monorepos okay…
- don't overdo everything… sometimes easier just to run 1 giant TF script.
- don't need helm
- Pull Request *everything* ==> why always be waiting?
- Automated change logs ==>  manual editing, we're not perfect.
- Push vs Pull - I don't care. Just deploy.
- Doing everything, security breaks deployment?
- Deploy without downtime. It's okay, maintenance window, early morning. Go home early. ==> what helps you sleep better?


### Pre-mature Adoption
- microservices (prove business/product first!)
- Kubernetes

### Pre-mature Optimizations
- modular pipelines as code, IaC
- governance controls, e.g. Pull Requests
- on demand environments
- turn environments on/off (use platform provider tools if possible. Size appropriately and leave on.)

### Too much security
- gitops: great. But maybe too much security? Deploying is only part of story. In SRE - if you have no access, how do you fix something?

### Manual Love
- git commit messages --> change logs
- documentation (in code, js doc and in markdown)

### Top %
- Reduce noise. Too much tooling?
- Handle errors, graceful shutdowns
- Healthchecks
