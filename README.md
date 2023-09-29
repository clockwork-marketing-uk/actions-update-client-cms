# Update Client CMS

Checks and updates the version of the CMS on a client repository

## Usage

```yaml

- name: Update Client CMS
    uses: clockwork-marketing-uk/actions-update-client-cms@1.0.6
    with:
     github-token: ${{ secrets.GITHUB_TOKEN }}
     github-user: ${{ github.actor }}
     fa-npm-token: ${{ secrets.FA_NPM_TOKEN }}
     npm_token: ${{ secrets.NPM_TOKEN }}
     github-composer-token: ${{ secrets.COMPOSER_TOKEN }}
     gh_package_key: ${{ secrets.GH_PACKAGE_KEY }}
     php_version: "8.1"

```
