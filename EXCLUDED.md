# Passkeys Directory excluded categories and websites

Below is a list of categories and websites that we, [the maintainers][maintainers], have opted to not list on the [Passkeys Directory][website].

One of the primary concerns we seek to address with these exclusions is professional and academic web filters. We
believe that the service that this site provides should be as accessible as possible, to help as many people as
possible, in as many environments as possible. Dynamic web filters can block websites based solely on the existence of
keywords which could lead to this service being filtered for mentioning or linking out to categories of websites that
web admins have deemed unacceptable for their domain. While we believe that every site should try to protect its
users (which often includes enabling two-factor authentication), we also believe that accessibility to this list for all
has more value than listing every possible site and service.

If you want to make a copy (fork) of our site to list any of these sites you're welcome to do so as long as you comply
with our [license][license].

## Categories

#### Illegal content

Websites that serve illegal content or promote illegal activities cannot be listed in this repository.
This includes but is not limited to pirated content, hate speech, drugs, and weapons.

#### Pornographic sites

The volunteers of [2factorauth][org_link] need to review all submissions to validate that the site/service provides
passkey authentication to its users in addition to verifying that the pull request meets our style guidelines, we've chosen to not list
sites that primarily host and serve pornographic content. Given the volunteer-driven nature of this project, there is no
guarantee that there will always be a maintainer available to review a submission that also does not have an objection
to reviewing such material. Special consideration must also be given due to the potential for content in this category
to quickly cross subjective personal boundaries that vary widely from person to person.

#### Self-hosted services

The category "self-hosted services/sites" includes all types of software that are designed to be hosted by the end user.
These are excluded from the listing unless all these points are met:

1. All [Site criteria][eligibility] are met

2. Public interest and public accessibility are given

3. The site has an independent authentication database

4. The underlying service supports built-in passkey authentication or through a first-party (developer) plugin

There are several reasons why we've opted to not list such sites and services.

- [Passkeys Directory][website] is targeted towards consumers and not website administrators. As of right now, very few general
  internet users choose to host their own websites and services. Therefore, we think that the effort on our part to
  maintain such a list of self-hosted alternatives would outweigh the minimal theoretical change in the internet
  landscape by listing such services.

- If the core project doesn't support two-factor authentication but instead through plugins it would mean that we
  would have to list all plugins that enable two-factor authentication for the service, something that is currently
  impossible with our website layout.

  If you have any questions regarding whether a site qualifies for listing, simply open an issue and we'll take a
  look.

#### Forums

Most forums are self-hosted (and thus violate the aforementioned rule) or are hosted as subdomains which makes it
impossible to find a meaningful ranking for the site.

#### Potentially controversial sites

Any site that could damage the reputation of the [Passkeys Directory][website] and/or lead to any controversy with either the
maintainers or users, should not be listed.
The group of active maintainers will decide on whether to include or exclude a site within a specific timeframe.

[website]: https://passkey.2fa.directory
[maintainers]: https://passkey.2fa.directory/about
[license]: /LICENSE.md
[eligibility]: /CONTRIBUTING.md#eligibility
[org_link]: https://github.com/2factorauth