# Snapshot badges for packages on Stackage

Stackage Server just got a new feature: snapshot badges. Take a look:

- `stack/lts-2`:   ![Stack lts-2 badge](http://stackage.org/package/stack/badge/lts-2)
- `stack/lts-3`:   ![Stack lts-3 badge](http://stackage.org/package/stack/badge/lts-3)
- `stack/lts` (the latest): ![Stack lts badge](http://stackage.org/package/stack/badge/lts)
- `stack/nightly`: ![Stack nightly badge](http://stackage.org/package/stack/badge/nightly)


Package authors can add the badges to their `README.md` to tell users in which
snapshots the package is present and provide a link to the package page.

Here is an example of how that can be done:

```markdown
# PackageName

[![packagename on Stackage LTS 2](http://stackage.org/package/packagename/badge/lts-2)](http://stackage.org/lts-2/package/packagename)

[![packagename on Stackage LTS 3](http://stackage.org/package/packagename/badge/lts-3)](http://stackage.org/lts-3/package/packagename)

[![packagename on Stackage Nightly](http://stackage.org/package/packagename/badge/nightly)](http://stackage.org/nightly/package/packagename)
```

In case of `stack` it would look like:

------

# Stack

[![stack on Stackage LTS 2](http://stackage.org/package/stack/badge/lts-2)](http://stackage.org/lts-2/package/stack)

[![stack on Stackage LTS 3](http://stackage.org/package/stack/badge/lts-3)](http://stackage.org/lts-3/package/stack)

[![stack on Stackage Nightly](http://stackage.org/package/stack/badge/nightly)](http://stackage.org/nightly/package/stack)
