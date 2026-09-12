Elijah model-status (elevated-potential)
=========================================

jetbrains-21+deb (wmb...) is disobedient here
fine with temurin-17/mise

```shell
mise exec java@temurin-17 -- ./gradlew test
# assemble, pTML, ??
```

---


Moving 2 things here:

1. javac stuff (not yet, google; ascopes??)
2. the abstraction of the AST/CST (the LST license should be fine)


---

https://gitlab.com/elijah-team/documentation/petal-to-the-medal/-/blob/main/ginitiatives/G7.md

https://gitlab.com/elijah-team/api-components/model-status (more or less this branch)

- Something about (bad) design

Checklist encoded in non-optimal markdown
------------------------------------------

[ ] keeping wrong name of `xxx-model-status` until integration is complete

[ ] gradle build is in this branch, need to make a decision (and refuse to learn a new plugin architecture)

[ ] clojure build seems unlikely and or unnecessary

[ ] meh: Vestigial gen, small, typeinf, tests: leave it somewhere, and somewhere is here for now

[ ] Look around for `5dd4c4c71f` (aka not verification)

[x] Do not respond to foolishness

[ ] Cry in the bathroom about sbt



TODO
-----

1. Fix gradle version (we are on 8.2?)
2. Add tests
   2b. See if compile-testing or ascopes/...tbd works here?
3. Pretend like gh-ci is going to work
4. SOGOTP renovate
5. SOGOTP build.deps
