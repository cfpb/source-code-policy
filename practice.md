## Practicing our open source policy

This document is meant to give specific team guidance on putting our [open source policy](policy.md) into practice.

* 18F releases software into the [international public domain](#public-domain).
* 18F develops software [in the open](#working-in-public), as early and as completely as we can.
* Whether developed openly or not, 18F has committed to [releasing the source code](#source-code-release) for our work, with only [very narrow exceptions](#exceptions).

### Public domain

[By law](http://www.law.cornell.edu/uscode/text/17/105), works of the United States government are not copyrightable in the US, and so are public domain. But by default, US government works **are** copyrightable internationally, and so 18F intentionally waives this copyright abroad using [CC0](https://creativecommons.org/publicdomain/zero/1.0/).

There are potentially other cases where copyright is involved: where contractors produce the work, or where work was otherwise originally performed not in the capacity of a US government employee. To the extent 18F has the rights to do so, 18F will normalize the copyright status of its work product under CC0.

#### How to license 18F repos

When you create a repo, add a [LICENSE.md](LICENSE.md) and [CONTRIBUTING.md](CONTRIBUTING.md) file, and add a [paragraph to the end of your README](README.md#public-domain).

The preceding links are to our standard boilerplate for each of those, so you can just copy and paste them. In some cases, you may need to customize them for your use -- for example, if you've forked a project that originated from outside the government.

You may wish to add the following to your `.bashrc` or `.zshrc`:

```bash
alias insert-license="wget -q https://raw.githubusercontent.com/18F/open-source-policy/master/LICENSE.md"
alias insert-contrib="wget -q https://raw.githubusercontent.com/18F/open-source-policy/master/CONTRIBUTING.md"
alias 18f-init="insert-license && insert-contrib && echo 'Licensed.'"
```

You can then initialize a new 18F repository's license information with:

```bash
18f-init
```

It's still recommended to copy and paste [this paragraph for the end of your README](https://github.com/18F/open-source-policy/blob/exceptions/README.md#public-domain) that sums up what's going on.

### Working in public

18F believes in [working in public](https://18f.gsa.gov/2014/07/31/working-in-public-from-day-1/) to the greatest extent we can. It creates a healthier working environment, a more collaborative process, and just better software.

All 18F team members are expected to make new source code repositories public from creation.

There are some times when we may temporarily delay open sourcing our work:

* **Before the ink is dry**. It's common for 18F to begin work on code before formally signing and completing an "inter-agency agreement" (IAA) with our client. Generally speaking, until an IAA is signed, the project has not formally begun, and we are not able to discuss a project publicly.

* **Brief experimentation**. This could be work that a team member wants to share with another team member before clearing through agency processes, or to "whiteboard" out an idea that they want to propose in a small group. This shouldn't last more than 10 business days, after which the code should be made public or deleted.

* **Confidentiality agreements.** At times, we may undertake projects subject to temporary confidentiality agreements, embargos, or other holds on disclosure. Related content, including code, may be private until a specified time, arranged at the beginning of the work.

Other situations might arise that demand a delay in publishing source code &mdash; an 18F team member should consult with the rest of the team if they believe their situation merits a delay.

General nervousness and embarrassment, on 18F's part or on the part of an agency partner, are not good enough reasons to keep source code closed through the development process.

### Source Code Release

18F's Open Source Policy lists [3 classes of exceptions](https://github.com/18F/open-source-policy/blob/master/policy.md#exceptions) under which we will not ever release source code:

1. We don't have the rights to release the code.
2. The code's public release is restricted by a specific law or regulation (for example, arms control).
3. Some other "compelling interest" that is "rare [and] documented publicly", listed below.

#### Exceptions

18F currently has **no projects** for which we will not release the source code.
