## This is a utility repo for developer use.

it uses yarn workspaces
https://alligator.io/workflow/corralling-monorepos-with-yarn-workspaces/


- install deps from here, `yarn install`
	- you'l see that the workspaces have installed their submodules aswell!
- go into module that has a workspace node_modules dependency
	- `yarn link workspace_name`
	- you'l see node_modules/workspace_name is symlinked to workspace_name
