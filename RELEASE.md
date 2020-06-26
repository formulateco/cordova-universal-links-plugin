# Releasing

- Bump version in package.json and plugin.xml
- Run `npm install` to update package-lock.json
- Commit changes
- Tag release: git tag x.y.z -m "Release x.y.z."
- Run `git push && git push --tags`
