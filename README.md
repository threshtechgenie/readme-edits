# readme-edits
testing2
- name: Setup Node.js environment
  uses: actions/setup-node@v2.1.2
  with:
    # Set always-auth in npmrc
    always-auth: # optional, default is false
    # Version Spec of the version to use.  Examples: 12.x, 10.15.1, >=10.15.0
    node-version: # optional
    # Set this option if you want the action to check for the latest available version that satisfies the version spec
    check-latest: # optional
    # Optional registry to set up for auth. Will set the registry in a project level .npmrc and .yarnrc file, and set up auth to read in from env.NODE_AUTH_TOKEN
    registry-url: # optional
    # Optional scope for authenticating against scoped registries
    scope: # optional
    # Used to pull node distributions from node-versions.  Since there's a default, this is typically not supplied by the user.
    token: # optional, default is ${{ github.token }}
    # Deprecated. Use node-version instead. Will not be supported after October 1, 2019
    version: # optional
