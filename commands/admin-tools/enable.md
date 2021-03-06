# ee admin-tools enable

Enables admin tools on site.

### OPTIONS

[&lt;site-name&gt;]
: Name of website to enable admin-tools on.

[\--force]
: Force enabling of admin-tools for a site.

### EXAMPLES

    # Enable admin tools on site
    $ ee admin-tools enable example.com

    # Force enable admin tools on site
    $ ee admin-tools enable example.com --force

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
