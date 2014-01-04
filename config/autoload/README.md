About this directory:
=====================

By default, this application is configured to load all configs in
`./config/autoload/{,*.}{global,local}.php`. Doing this provides a
location for a developer to drop in configuration override files provided by
modules, as well as cleanly provide individual, application-wide config files
for things like database connections, etc.



This application use social network as login lib, it requires:
		"zendframework/zendframework": "2.2.*",
        "zf-commons/zfc-base": "0.*",
        "zf-commons/zfc-user": "dev-master",
        "hybridauth/hybridauth": "dev-master",
        "socalnick/scn-social-auth": "dev-master"
login link is: /user/login

it also need scn-social-auth.local.php (with facebook clientid and secret)
