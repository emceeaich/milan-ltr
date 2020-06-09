# The Milan Letter Project

![Repository Change](https://img.shields.io/badge/Attention-Repository%20Change-yellow) 

**2020-06-08**: Project's default branch is now `main` instead of `master` please update your local branches using `git branch -m master main`. [See Scott Hanselman's post](https://www.hanselman.com/blog/EasilyRenameYourGitDefaultBranchFromMasterToMain.aspx) for more information. 

![Licensed Ethically](https://img.shields.io/badge/licensed-ethically-%234baaaa)

Writer [Courtney Milan shared a draft of a letter she is sending to her state's governor (CO-US) demanding](https://twitter.com/courtneymilan/status/1266917538123767809):

* Reduced funding of police
* Prison abolition 
* And the end of cash bail

Erring on the the side of asking forgiveness rather than permission, I'm making it a template, and asking for the community to provide versions for other US States, territories, and jurisdictions, as well as translations. 

If this format of a letter works for your non-US state, province, prefecture, or other polity, please contribute versions of the letter.

## Sending a letter is not enough

* Contribute to local bail funds. There's a [list of bail funds by state](https://bailfunds.github.io/) and region.
* Educate yourself about the history of Policing in the US and its relationship to slavery

## Contributing

### What we need now

* An accountability partner to make sure we are centering Black lives in our efforts
* Versions of Milan's letter adapted for US states, territories, and jurisdictions 
  * Documentation on how to adapt the letter for your state, territory, or district
* Documentation for state budgets
* Translations of the letter into Spanish and other commonly used languages in the US
* A micro-site with directions on finding a letter for one's jurisdiction and how to use it
  * A Jekyll template

### How to contribute

_Contributions should be in the form of a pull request from your fork of this project._

* Take a state or jurisdiction that needs a letter
  * Create a new file in `letters/COUNTRY-CODE`
    * Use `ltr-STATE-COUNTRY.txt` as the template for naming files
  * Update the governor's name
  * Make sure all the state name references are correct
  * Locate the state's recent budget for prisons (a.k.a. corrections) and update 
    `sources/prison-and-corrections-budgets.md` with that information
  * Update the letter with that information
  * If your state does not have cash bail, remove that and optionally suggest another
    anti-carcerial measure that saves money.
  * Make a pull request
* Proofread existing letters for spelling, grammar, and facts
  * Make proposed corrections in a pull request
* Comment on pull requests for facts, spelling, and grammar

## License and code of conduct

This project is provided under the [Hippocratic Licence](https://firstdonoharm.dev/version/2/1/license.html), and adopts the Contributor Covenant as its Code of Conduct.
