# React Styleguidist Does Not Reload on Asset Change

## Steps to Reproduce

1. `git clone git@github.com:esturcke/styleguidist-no-reload-on-asset-change-bug.git`
2. `cd git@github.com:esturcke/styleguidist-no-reload-on-asset-change-bug.git`
3. `yarn`
4. `yarn start`
5. Navigate to [http://localhost:6060/](http://localhost:6060/).
6. `cp public/{update,image}.png`

The page does not reflect the new image until the page is manually reloaded.

