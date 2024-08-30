---
layout: default
title: Authentication (logging in)
permalink: /authentication
parent: Digital Asset Management
grand_parent: DBGallery
nav_order: 45
---

# Authentication

Logging into DBGallery is achieved in one of the following ways:
- A username and password created in DBGallery
- Active Directory Integration
- Single Sign-on (SSO).

## A username and password created in DBGallery
Please see our <a href="https://docs.google.com/presentation/d/1zcp2KJ5JI3qDXTSAh6pEzQGyuuB7KpCU662XLYpyrKo/edit#slide=id.g85342cdac2_0_260" target="_blank">User Management</a> slideshow for creating logins within DBGallery.

<p style="margin-left: 5%;"><img src="/assets/ChangeLogo-Login.png" alt="DBGallery Login Page" width="70%"/></p>
<p style="margin-left: 5%;">A sample login page.</p>

## Active Directory Integration
DBGallery’s on-prem web server can be integrated with Microsoft Active Directory (AD).  It is used to provide easy access to DBGallery for existing Active Directory users without requiring each user be added manually in DBGallery.  With AD integration enabled any AD user can login to DBGallery using their windows credentials. Access to DBGallery can be limited to a certain group of users from Active Directory.  Users can be assigned specific roles within DBGallery, where DBGallery-specific permissions can be set.

### AD Integration: How To
Specifics of how to integrate with AD follows, but please note that typically our clients will be working with our support team to help ensure this is setup and tested correctly.

With Active Directory integration enabled any Active Directory user can login to DBGallery using their windows credentials. Access to DBGallery can be limited to a certain group of users from Active Directory.

After entering an email address and password, DBGallery will look in it's database. If the user is not found in the DBGallery database, the process will query AD using user name (CN) and password. If the user exists in AD it will create the AD user in DBGallery and authenticate as that user. It will also assign default DBGallery roles based on standard DBGallery settings and DBGallery LDAP configuration. If the user exists in DBGallery, it will verify that it still exists in AD, and deny access if not.

A DBGallery Administrator can specify the default level of access (default roles) for users by logging in using their Windows credentials. Roles should be created in DBGallery in advance. Administrators can also assign access permissions and roles to the migrated users individually after the first login.

Active Directory integration can be enabled in the Web appsettings.config file with the following optional settings :

- **LdapServer** - network address and port of the Active Directory server 
- **LdapBaseDn** - base dn, all AD searches will be performed under the specified base DN
- **LdapLogin** - distinguishedName of the user that can login to Active Directory, perform user and group  lookups and validate credentials
- **LdapPassword** - password of the user specified in LdapLogin
- **LdapUserRoles** - comma or semicolon delimited list of the roles that will be assigned to all users logging in with AD
- **LdapGroup** - AD group name. Only members of that AD group will be allowed to login into DBGallery.

A configuration snippet example is shown below, which may already be in the appsettings.config file but commented out.  Each setting requires a numbered suffix as there may be multiple ADs (use 1 if there is only on AD in your organization) : 

    <add key="LdapServer1" value="192.168.10.10:389" />
    <add key="LdapBaseDn1" value="dc=dbgallery,dc=corp" />
    <add key="LdapLogin1" value="CN=Administrator,CN=Users,DC=dbgallery,DC=corp" />
    <add key="LdapPassword1" value="password" />
    <add key="LdapUserRoles1" value="Marketing;Sales"/>
    <add key="LdapGroup1" value="DbGallery Users" />

## Single Sign-on (SSO)

For added convenience and security, companies who currently use single sign-on (SSO) do not need a seperate username and pw to sign into DBGallery. Multi-factor authenication may be a part of that SSO configuration as well.  A compatible SSO service provider and some configuration is required.  DBGallery's support team would work with your company's IT department to configure SSO.  For additional information or to start a SSO configuration conversation, please contact either support or your primary DBGallery contact person.

Also See: Our <a href="https://dbgallery.com/blog-sso" target="_blank">SSO blog</a>.

<p style="margin-left: 25%;"><img src="/assets/SSOlogo.png" alt="Single Sign-on Graphic" width="50%"/></p>
