## 2 - Getting started with Snap-In Development

This guide is based on the branch `nw-repo-details`. Make sure to checkout this branch:

```bash
git checkout nw-repo-detail
```

### Relevant Commits

Here are the commits we'll be working with:

```
commit 4196e748bed6352326eae71ca990fc881dfd4595 (HEAD -> nw-repo-detail, origin/nw-repo-detail)
Author: altafDevRev <altaf.ahmad@devrev.ai>
Date:   Thu Nov 14 15:07:04 2024 +0530
    obj type iss

commit 8db93596c18a673b20ea610879f2f08dadedef49
Author: Altaf Ahmad <104750669+altafDevRev@users.noreply.github.com>
Date:   Thu Nov 14 15:06:01 2024 +0530
    chore: add pr_details command (#40)

commit 4a78a3e2d5c1c76b6dd967bcd2136f8e14b22aa3 (main)
Author: altafDevRev <altaf.ahmad@devrev.ai>
Date:   Thu Nov 14 15:04:17 2024 +0530
    chore: add repo details command
```

### Step-by-Step Guide

1. Start with the oldest commit:

   ```bash
   git checkout 4a78a3e2d5c1c76b6dd967bcd2136f8e14b22aa3
   ```

2. Create a new branch:

   ```bash
   git switch -c nw-repo-detail-snap
   ```

3. Move forward one commit at a time using the `git cherry-pick` command. This is the Lab Piece one:

   ```bash
   git cherry-pick 8db93596c18a673b20ea610879f2f08dadedef49
   git cherry-pick 4196e748bed6352326eae71ca990fc881dfd4595
   ```

<br><br><br><br><br><br>

## 4 - Different Types of Snap-Ins

This guide is based on the branch `nw-workshop-alt`. Make sure to checkout this branch:

```bash
git checkout nw-workshop-alt
```

### Relevant Commits

Here are the commits we'll be working with:

```
commit 49bef2761eeac975688ad680cdf13ffff3fbe3f7 (HEAD -> nw-workshop-alt, origin/nw-workshop-alt)
Author: altafDevRev <altaf.ahmad@devrev.ai>
Date:   Wed Nov 13 19:42:12 2024 +0530
    move these issues to completed stage when this PR is merged

commit fe15d5e7a9782c82a306095b7a973cfbb03e23d1
Author: altafDevRev <altaf.ahmad@devrev.ai>
Date:   Wed Nov 13 15:36:09 2024 +0530
    get preference from the owner of the issue

commit 2a95c77747f1541ae9ee8c57d4dce2978a6d502e
Author: altafDevRev <altaf.ahmad@devrev.ai>
Date:   Tue Nov 12 20:14:16 2024 +0530
    add the URL as a custom field on the issue object

commit 75a9516ab8be13e64e5d06f163cb6024ce2a9a25
Author: altafDevRev <altaf.ahmad@devrev.ai>
Date:   Tue Nov 12 16:37:22 2024 +0530
    added unit tests

commit 974c76375475de94138b503bdd751e4ad2d32218
Author: altafDevRev <altaf.ahmad@devrev.ai>
Date:   Tue Nov 12 15:46:08 2024 +0530
    added gitignore

commit ae78b5a2f1ab0e27f80766838a604aba30155388
Author: altafDevRev <altaf.ahmad@devrev.ai>
Date:   Tue Nov 12 15:34:01 2024 +0530
    initialise github webhook snapin
```

### Step-by-Step Guide

1. Start with the oldest commit:

   ```bash
   git checkout ae78b5a2f1ab0e27f80766838a604aba30155388
   ```

2. Create a new branch:

   ```bash
   git switch -c nw-workshop-alt2
   ```

3. Move forward one commit at a time using the `git cherry-pick` command:

   ```bash
   git cherry-pick 974c76375475de94138b503bdd751e4ad2d32218
   ```
   ```bash
   git cherry-pick 75a9516ab8be13e64e5d06f163cb6024ce2a9a25
   ```
   ```bash
   git cherry-pick 2a95c77747f1541ae9ee8c57d4dce2978a6d502e
   ```
   ```bash
   git cherry-pick fe15d5e7a9782c82a306095b7a973cfbb03e23d1
   ```
   ```bash
   git cherry-pick 49bef2761eeac975688ad680cdf13ffff3fbe3f7
   ```



<br><br><br><br><br><br>




## 4 - Interactive Snap-Ins

This guide is based on the branch `nw-workshop-2-5`. Make sure to checkout this branch:

```bash
git checkout nw-workshop-2-5
```

### Relevant Commits

Here are the commits we'll be working with:

```
commit 5d6d9facc68d55913088349c1b836a6688ba04e3 (HEAD -> nw-workshop-2-5, origin/nw-workshop-2-5)
Author: altafDevRev <altaf.ahmad@devrev.ai>
Date:   Thu Nov 14 13:22:31 2024 +0530
    buttons – merge and close (for open PRs)

commit 7ae24f7e3a762713d2ad0337f129dcfdc81e41fa
Author: altafDevRev <altaf.ahmad@devrev.ai>
Date:   Thu Nov 14 11:30:47 2024 +0530
    send comment via snap-kit

commit 6474cb0a6f103478b42ee6f21254f25cd7676f0f (origin/pr-details-only, pr-details-only)
Author: altafDevRev <altaf.ahmad@devrev.ai>
Date:   Thu Nov 14 11:05:56 2024 +0530
    chore: add pr_details command
```

### Step-by-Step Guide

1. Start with the oldest commit:

   ```bash
   git checkout 6474cb0a6f103478b42ee6f21254f25cd7676f0f
   ```

2. Create a new branch:

   ```bash
   git switch -c nw-workshop-2-5-interactive
   ```

3. Move forward one commit at a time using the `git cherry-pick` command:

   ```bash
   git cherry-pick 7ae24f7e3a762713d2ad0337f129dcfdc81e41fa
   ```
   ```bash
   git cherry-pick 5d6d9facc68d55913088349c1b836a6688ba04e3
   ```

