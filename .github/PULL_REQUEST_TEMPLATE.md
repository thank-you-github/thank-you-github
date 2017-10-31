Please read and remove:

Practically all PRs are non-mergeable because they conflict with each other, and
continually asking for rebases would be impractical.

Because of that, it is likely that your signature is added via a commit that
references and closes the PR, rather than a regular merge. I have a supervised
script that processes the patches and commits them individually, referencing
their origin PR for credit and authenticity. In such case, you'll see said
commit linked in the notification email and in the page of the PR itself. 
