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
   git switch -c nw-repo-details2
   ```

3. Move forward one commit at a time using the `git cherry-pick` command. This is the Lab Piece one:

   ```bash
   git cherry-pick 8db93596c18a673b20ea610879f2f08dadedef49
   ```

