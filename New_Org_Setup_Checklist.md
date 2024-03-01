<h1 style=text-align:center>New Org Setup Checklist</h1>

# I. Orginization Setup

## Company Information

The following options can be found under `Settings > Company Settings > Company Information`:

1. Set `fiscal year` (if needed)
2. Set `business hours` ( can include setting holidays for the business)
3. Set `currency management`  
   a. Note that this is permanent, there is not going back; only implement if needed
4. Set `default locale`, `default language`, `default time zone`

## Org-wide Settings

1. Update `User Interface` settings if needed - org-wide (Includes currency display, hover details, etc.)
2. Customize `App Menu` for App launcher
   a. Create any new apps/layouts of apps
3. Update, change list views in individual objects as needed
4. Add/Remove global actions
   a. `Global Actions` - Create/remove global actions seen on every page
   b. `Publisher Layouts` - Controls the order / visibility of global actions
5. Create any new apps/homepages/record pages if needed through the `Lightning App Builder`
6. Review Org user-accounts
7. Check `Login Access Policies`:
   a. `Administrators Can Log in as Any User` (checked)
8. Review `Session Settings`:
   a. Set `Session Timeout` values
   b. Review `Session Settings` sub-category of requirements
   c. `Caching` for better performance
   d. `Clickjack Protection`
   e. `Session Security Levels`
9. `Setup Audit Trail` - especially if using multiple Admins

## Organization-Wide Defaults

Organization-wide sharing settings specify the default level of access that users have to each others' records. It is best practice to lock your data to the most restrictive level at the Org level and expand access through permissions.

Organization-wide defaults can be found under `Sharing Settings`.

1. `Grant Access Using Hierarchies` - is default for standard apps, but can be changed for custom apps
2. `Sharing Rules` in `Sharing Settings` 

## Profile Setup

Standard profiles should be used as a template, as they are restrictive with fixed permissions and are not necessarily best customized for a specific org. These should be cloned and customized to better meet needs.

If you need additional access (e.g. the ability for a profile to delete cases, or have certain access, use permissions sets over creating new profiles). Permission sets only expand user permissions and do not affect profile permissions.

1. Update `Login Hours` if applicable
2. Update `Login IP Ranges` if applicable
3. Add password policies if different than default
4. `User Management Settings`
   a. Setup `Enhanced User Profile` to further customize apps/settings for that profile


test