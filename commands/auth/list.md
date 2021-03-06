# ee auth list

Lists http authentication users of a site.

### OPTIONS

[&lt;site-name&gt;]
: Name of website / `global` for global scope.

[\--ip]
: Show whitelisted IPs of site.

[\--format=&lt;format&gt;]
: Render output in a particular format.
\---
default: table
options:
  - table
  - csv
  - yaml
  - json
  - count
\---

### EXAMPLES

    # List all auth on site
    $ ee auth list example.com

    # List all global auth
    $ ee auth list global

### GLOBAL PARAMETERS

| **Argument**    | **Description**              |
|:----------------|:-----------------------------|
| `--sites_path=<path>` | Absolute path to where all sites will be stored. |
| `--locale=<locale>` | Locale for WordPress. |
| `--le-mail=<le-mail>` | Mail-id to be used for letsencrypt. |
| `--[no-]color` | Whether to colorize the output. |
| `--debug[=<group>]` | Show all PHP errors; add verbosity to EE bootstrap. |
| `--prompt[=<assoc>]` | Prompt the user to enter values for all command arguments, or a subset specified as comma-separated values. |
| `--quiet` | Suppress informational messages. |
