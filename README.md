#My Portfolio Website

This website contains information about myself as a student at Sheridan College.
Displays some of my personal and academic projects.
And has my resume and links to various networking platforms such as Linkedin.

## Additional project links

Every entry in `projects.json` has an empty `extraLinks` array. To add links to its details dialog, use objects with `label` and `url` fields:

```json
"extraLinks": [
  { "label": "Live demo", "url": "https://example.com" }
]
```

Leave the array empty to show no additional links. URLs must start with `https://` or `http://`.
