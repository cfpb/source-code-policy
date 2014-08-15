### 18F Team Open Source FAQ

Guidance for 18F's team in implementing our open source policy.

**Does *everything* I do have to be open source?**

Any *software* you write on 18F's behalf is covered by this policy, and should begin its life in a public repo on our GitHub organization.

Though not specifically covered in the policy, it is strongly encouraged to make *non-software* public by default as well.

One common, temporary exception to this is if the work is for a *potential* client, before the inter-agency agreement (IAA) is signed. (See below.) Other exceptions should be extremely limited, discussed with the team, and documented by name in [`exceptions.md`](exceptions.md).

18F is an open source team, and we default to open.

**But I haven't written any documentation yet!**

At 18F, open is more important than documented.

Documentation is of course highly encouraged, both early on and throughout a project.

**What specific work are you making me do?**

When you create a repo, add a [LICENSE.md](LICENSE.md) and [CONTRIBUTING.md](CONTRIBUTING.md) file, and add a [paragraph to the end of your README](README.md#public-domain).

The preceding links are to our standard boilerplate for each of those, so you can just copy and paste them. In some cases, you may need to customize them for your use -- for example, if you've forked a project that originated from outside the government.

**What if my team hasn't signed its IAA (inter-agency agreement) for the project yet?**

Generally speaking, until the IAA is signed, the work must remain private. There is a note about this in [`exceptions.md`](exceptions.md). If you have any questions or concerns, discuss with your project lead or the broader 18F team.

**Why are we releasing work under CC0? I thought everything the government did was already public domain?**

[By law](http://www.law.cornell.edu/uscode/text/17/105), works of the United States government are not copyrightable in the US, and so are public domain. But by default, US government works *are* copyrightable internationally, and so 18F intentionally waives this copyright abroad using [CC0](http://creativecommons.org/publicdomain/zero/1.0/).

There are potentially other cases where copyright is involved: where contractors produce the work, or where work was otherwise originally performed not in the capacity of a US government employee. To the extent 18F has the rights to do so, 18F will normalize the copyright status of its work product under CC0.

**Do I really have to copy and paste things every time I start a new project?**

No! Here's a few lines you can add to your `~/.bashrc` or `~/.zshrc` file to make things super easy:
```
# Alias for 18F
alias insertlicense="wget https://raw.githubusercontent.com/18F/open-source-policy/master/LICENSE.md"
alias insertcontrib="wget https://raw.githubusercontent.com/18F/open-source-policy/master/CONTRIBUTING.md"
alias 18finit="insertlicense && insertcontrib"
```

Now it is super easy to start a new project up with one simple command:

```
$ 18finit

--2014-08-14 13:40:20--  https://raw.githubusercontent.com/18F/open-source-policy/master/LICENSE.md
Resolving raw.githubusercontent.com... 23.235.46.133
Connecting to raw.githubusercontent.com|23.235.46.133|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 1327 (1.3K) [text/plain]
Saving to: 'LICENSE.md'

100%[===========================================================================================================================================>] 1,327       --.-K/s   in 0s

2014-08-14 13:40:20 (21.8 MB/s) - 'LICENSE.md' saved [1327/1327]

--2014-08-14 13:40:20--  https://raw.githubusercontent.com/18F/open-source-policy/master/CONTRIBUTING.md
Resolving raw.githubusercontent.com... 23.235.46.133
Connecting to raw.githubusercontent.com|23.235.46.133|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 432 [text/plain]
Saving to: 'CONTRIBUTING.md'

100%[===========================================================================================================================================>] 432         --.-K/s   in 0s

2014-08-14 13:40:20 (17.9 MB/s) - 'CONTRIBUTING.md' saved [432/432]
```

It's still recommended to copy and paste [this paragraph for the end of your README](https://github.com/18F/open-source-policy/blob/exceptions/README.md#public-domain) that sums up what's going on.
