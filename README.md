[![Built With ♥️](http://ForTheBadge.com/images/badges/built-with-love.svg)](https://github.com/cmnhospitals/.github)

# Creating a default community health file
> You can create default community health files, such as CONTRIBUTING and CODE_OF_CONDUCT. Default files will be used for any repository owned by the account that does not contain its own file of that type.


## About default community health files
You can add default community health files to a public repository called `.github`, in the root of the repository or in the `docs` or `.github` folders.

GitHub will use and display default files for any repository owned by the account that does not have its own file of that type in any of the following places:

- the root of the repository
- the `.github` folder
- the `docs` folder

For example, anyone who creates an issue or pull request in a repository that does not have its own CONTRIBUTING file will see a link to the default CONTRIBUTING file. If a repository has any files in its own `.github/ISSUE_TEMPLATE` folder, including issue templates or a config.yml file, none of the contents of the default `.github/ISSUE_TEMPLATE` folder will be used.

Default files won’t appear in the file browser or Git history and are not included in clones, packages, or downloads of individual repositories because they are stored only in the `.github` repository.

## Supported file types
You can create defaults in your organization or personal account for the following community health files:

| Community health file |	Description |
|---|---|
| CODE_OF_CONDUCT.md | A CODE_OF_CONDUCT file defines standards for how to engage in a community. For more information, see "[Adding a code of conduct to your project.](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-code-of-conduct-to-your-project)"|
CONTRIBUTING.md	| A CONTRIBUTING file communicates how people should contribute to your project. For more information, see "[Setting guidelines for repository contributors.](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors)"|
Discussion category forms	| Discussion category forms customize the templates that are available for community members to use when they open new discussions in your repository. For more information, see "[Creating discussion category forms.](https://docs.github.com/en/discussions/managing-discussions-for-your-community/creating-discussion-category-forms)"|
FUNDING.yml	| A FUNDING file displays a sponsor button in your repository to increase the visibility of funding options for your open source project. For more information, see "[Displaying a sponsor button in your repository.](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/displaying-a-sponsor-button-in-your-repository)"|
GOVERNANCE.md	| A GOVERNANCE file lets people know about how your project is governed. For example, it might discuss project roles and how decisions are made.|
Issue and pull request templates and config.yml	| Issue and pull request templates customize and standardize the information you'd like contributors to include when they open issues and pull requests in your repository. For more information, see "[About issue and pull request templates.](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/about-issue-and-pull-request-templates)"|
SECURITY.md |	A SECURITY file gives instructions for how to report a security vulnerability in your project. For more information, see "[Adding a security policy to your repository.](https://docs.github.com/en/code-security/getting-started/adding-a-security-policy-to-your-repository)"|
SUPPORT.md | A SUPPORT file lets people know about ways to get help with your project. For more information, see "[Adding support resources to your project.](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-support-resources-to-your-project)"|

You cannot create a default license file. License files must be added to individual repositories so the file will be included when a project is cloned, packaged, or downloaded.
