Git can't prevent spoofing of commit owners, as creating a new commit with someone else's name/email is a requirement for certain git features (such as cherry-pick and rebase).

This certainly isn't a big deal and is unlikely to be a dealbreaker, but it's something to be aware of in certain CI/CD scenarios (and this might be a new attack vector, coming from other version control systems).
