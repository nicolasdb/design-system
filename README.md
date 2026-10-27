# nicolasdb design system

The look and words of nicolasdb's vertical, read by the images that serve it
(solid-kit ADR 011). Laid out as the ADR says; folders appear when something
needs them:

| Path | What | Read by |
|---|---|---|
| `pods/` | pod.nicolasdb.eu's own words: the welcome page, the override that mounts them | solid-css-overlay |
| `skins/kit/` | (not yet) a skin of our own; without it the images use solid-kit's default | the pods, the backoffice |

pod.nicolasdb.eu is where a new solid-css-overlay version is tried first
(pre-release tags, its README "Updating an instance"), and this repo is where
the design-system method is tried first: edit `pods/welcome/index.html` here,
not on the server. `pods/README.md` says how a change reaches the server.
