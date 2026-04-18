# agendor-pr-assets

Public sibling repo holding binary assets (screenshots, diagrams) referenced from PR descriptions in the private [`lslv1243/agendor`](https://github.com/lslv1243/agendor) repo.

Exists because `raw.githubusercontent.com` doesn't serve content from private repos without a short-lived session token, so inline images in PR markdown can't point at a private branch. Hosting the assets here keeps the main repo private while letting GitHub's markdown renderer load them.

## Layout

One subdirectory per PR or feature:

```
<feature-or-pr-slug>/
└── *.png
```

Reference in a PR description via:

```
https://raw.githubusercontent.com/lslv1243/agendor-pr-assets/main/<feature-slug>/<file>.png
```

Add new files — don't overwrite — so existing URLs stay stable.
