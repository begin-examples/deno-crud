# Example app checklist

- [ ] `package.json` + `package-lock.json`
  - [ ] Ensure they remain at version `0.0.0`
  - [ ] update description + app name
	- [ ] All deps are dev deps in root
	- [ ] `sandbox` only, shouldn't need `@architect/architect`

- [ ] `.arc` file
  - Never `app.arc`, `arc.json`, or `arc.yaml`

- [ ] `readme.md`
  - [ ] Pretty Begin graphic
  - [ ] Getting started / onboarding section
  - [ ] Descriptive, useful text about working with the app
  - [ ] Additional resources/links

- [ ] `.gitignore`
- [ ] `.eslintrc.js`

- [ ] `test` dir + testing
  - [ ] Be sure to add non-example additional tests
  - [ ] Depending on needs, update CI to use additional runtimes, packages, etc.
  - [ ] Retain PORT=6666
  - [ ] Tests should pass, natch!
