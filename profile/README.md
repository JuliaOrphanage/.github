The **Julia Orphanage** collects packages that are no longer maintained
upstream, but are registered in [the General registry](https://github.com/JuliaRegistries/General/)
and either have active users or are required by other packages.

In the orphanage packages receive limited community-driven maintenance.

- If you would like to **become the new maintainer** of a package, then please contact us.

- If you no **longer wish to or are able to maintain a package**, then consider transferring it
  to the orphanage as an alternative to abandoning or archiving the repository.
  This way, we can keep it usable, and if someone volunteers to become the new maintainer,
  you do not have to be involved in the process.

## FAQ

### How do I transfer a package to JuliaOrphanage?

 - Use the [GitHub transfer option](https://docs.github.com/en/repositories/creating-and-managing-repositories/transferring-a-repository#transferring-a-repository-owned-by-your-personal-account) in the repository settings.
 - Make a pull request to [the General registry](https://github.com/JuliaRegistries/General/pulls) in which you edit the repo URL in the package's Package.toml file (e.g [E/Example/Package.toml](https://github.com/JuliaRegistries/General/blob/master/E/Example/Package.toml#L3)).
 - If the PR is not attended to, or if you have any questions, you can ask for help in the `#pkg-registration` Slack channel.

Technically if you skip the second step things will keep working, because GitHub will redirect;
but it is best practice.
