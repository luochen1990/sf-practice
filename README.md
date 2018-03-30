Software Foundations Copy
=========================

- This is simply a copy of the book [Software Foundations](https://softwarefoundations.cis.upenn.edu/).
- This repo is just for convenience, tell me to remove this repo if anyone is offended.
- As the author asked: **please do not post solutions to the exercises in a public place**.
- If this repo is outdated, everyone is welcome opening a PR to update it.

Tips
----

You can use the following command to prevent `git push` by mistake:

```
git remote set-url --push origin nope
```

If the mistake already happened, you can repair it via the following steps:

```
git branch backup
git reset origin/master --hard
git push --force
git checkout backup
```

