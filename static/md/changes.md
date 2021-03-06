
## Changes

**2014/3/3**

 * Add pagination to module pages
 * Rewrite queries for fetching module pages
 * Cache root manifest

**2014/3/1**

 * Add support for filtered manifests: `manifest-5.1`, `manifest-5.2`
 * Import luarocks modules
 * Add specs

**2013/6/16**

 * New modules will go into root manifest by default (unless name is taken)
 * Added API
 * Create `moonrocks` tool: <https://github.com/leafo/moonrocks>

**2013/6/9**

 * Added ability to edit modules
 * Updated module page, now shows license and homepage

**2013/6/3**

 * Added the ability to delete versions and modules
 * Fixed issues with modules that have uppercase letters in their names

**2013/3/9**

 * Added password reset to login page
 * Added user settings page with ability to update password
 * Added csrf protection everywhere, updated session secret (you have to log in again sorry!)

**2012/12/5**

 * Initial release
