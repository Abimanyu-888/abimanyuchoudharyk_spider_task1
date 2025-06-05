# Tesla.com Recon Report

## 1. Public Documents
- model Y Electrical reference diagram 
	- **Dork used** `site:tesla.com filetype:pdf intext:confidential`
	- **Link** (https://service.tesla.com/docs/ModelY/ElectricalReference/prog-201/diagram/2023.4_ModelY-SOP5.pdf)
- untitled php file
	- **Dork used** `site:tesla.com filetype:php`
	- **Link** (https://www.tesla.com/sites/all/modules/custom/tesla_findus_map/proxy.php?ip=true)
- robots file
	- **Dork used** `site:tesla.com filetype:txt`
	- **Link** (https://www.tesla.com/robots.txt)

## 2. Login Pages / Admin Panels
- admin uername and passwd
	- **Dork used** `site:tesla.com inurl:admin -intext:careers`
	- **Link** (https://www.tesla.com/en_GB/user/login/:admin:M1cr0s0ft4$)
- OAuth authentication 
	- **Dork used** `site:tesla.com inurl:login`
	- **Link** (https://auth.tesla.com/oauth2/v1)

## 3. Public Backup / Config Files
- Subscription Agreement
	- **Dork used** `site:tesla.com inurl:config`
	- **Link** (https://www.tesla.com/app-assets-config/pdf/Drive_Anywhere_Agreement.pdf)

## 4. Exposed Logs / Errors
- login error
	- **Dork used** `site:tesla.com intext:error`
	- **Link** (https://www.tesla.com/en_pr/login-error)

## 5. Git Folders and Env Files
- Fleet api documentation
	- **Dork used** `site:tesla.com inurl:.git`
	- **Link** (https://developer.tesla.com/docs/fleet-api)
- Git folders
	- **Dork used** `site:github.com intext:tesla`
	- **Link** (https://github.com/teslamotors)

# Mit.edu Recon Report

## 1. Public Documents
- robots file
	- **Dork used** `site:mit.edu filetype:txt`
	- **Link** (https://news.mit.edu/robots.txt)
- CTF challenge log file
	- **Dork used** `site:mit.edu filetype:log -intitle:coclocking`
	- **Link** (https://web.mit.edu/nelhage/www/level3.log)

## 2. Login Pages / Admin Panels
- CGI login script
	- **Dork used** `site:mit.edu inurl:login intext:secure -inurl:community -inurl:media`
	- **Link** (http://web.mit.edu/course/2/2.854/www/cgi-bin/login.cgi)
- Adimn portal
	- **Dork used** `site:mit.edu inurl:admin -inurl:community`
	- **Link** (https://elx-admin.mit.edu/)
- Adimnistrator login page
	- **Dork used** `site:mit.edu inurl:login_admin`
	- **Link** (https://web.mit.edu/course/2/2.854/www/cgi-bin/sec_admin/login_admin.html)

## 3. Public Backup / Config Files
- WAMP configuration file
	- **Dork used** `site:mit.edu filetype:ini -intitle:gitlab`
	- **Link** (https://web.mit.edu/dramashop/Dramashop_WAMP/wampmanager.ini)
- Config file for cvsweb
	- **Dork used** `site:mit.edu filetype:conf`
	- **Link** (https://web.mit.edu/mers/www/cvsweb.conf)

## 4. Email & contact info
- Webmaster Emails
	- **gershwin@mit.edu** And **chiwon@mit.edu**
	- **Dork used** `site:mit.edu inurl:login -inurl:community`
	- **Link** (https://web.mit.edu/course/2/2.852/www/sec/login.html)
- Adobe 2013 data breach emails and passwords
	- **Dork used** `site:mit.edu filetype:txt intext:@gamil.com`
	- **Link** (http://web.mit.edu/zyan/Public/adobe_sanitized_passwords_with_bad_hints.txt)

# Nasa.gov Recon Report

## 1. Public Documents
- robots file
	- **Dork used** `site:nasa.gov filetype:txt`
	- **Link** (https://www3.nasa.gov/robots.txt)
