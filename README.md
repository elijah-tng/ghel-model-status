Elijah model-status (elevated-potential)
=========================================

jetbrains-21+deb (wmb...) is disobedient here
fine with temurin-17/mise

```shell
mise exec java@temurin-17 -- ./gradlew test
# assemble, pTML, ??
```


- Includes gladle from gitlab
- Includes old bad design from maven in a new package

---


Moving things here:

[x] javac skeleton (not yet, google)
[ ] javac adapter
[ ] abstraction of the AST/CST (the LST license)


---

https://gitlab.com/elijah-team/documentation/petal-to-the-medal/-/blob/main/ginitiatives/G7.md

https://gitlab.com/elijah-team/api-components/model-status


Checklist encoded in non-optimal markdown
------------------------------------------

[ ] keeping wrong name of `xxx-model-status` until integration is complete

[x] gradle build is in this branch, need to make a decision (and refuse to learn a new plugin architecture)

[x] clojure build seems unlikely and or unnecessary

[ ] meh: Vestigial gen, small, typeinf, tests: leave it somewhere, and somewhere is here for now

[ ] Look around for `5dd4c4c71f` (aka not verification)

[x] Do not respond to foolishness

[ ] Cry in the bathroom about sbt

[ ] SOGOTP renovate

[ ] SOGOTP build.deps

[x] Pretend like gh-ci is going to work

[x] Pretend like gh deployment is going to work

[ ] Decide on gradle version 8.2 vs 9.x.x

[ ] Add tests (gct)
