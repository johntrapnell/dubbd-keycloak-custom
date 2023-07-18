# dubbd-keycloak
A Defense Unicorns Big Bang Repo with Keycloak

## Create the package
```
zarf package create . --confirm
```

## Deploy the package
Make sure you have the bigbang.cert and bigbang.key files in the deploy directory before running this command
```
zarf package deploy --confirm
```
