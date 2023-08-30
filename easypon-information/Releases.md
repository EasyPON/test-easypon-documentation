# Changelog

## v2.3.10 - 2023-08-07
#### Changes:
* remove author from config creation when using jwt stateless authentication (ee53662)
---
## v2.3.9 - 2023-07-24
#### Changes:
* fix retry attempts to send command on the onu registration (f710735)
* Resolve EP-1192 "/change balance info in license to user address" (999df88)
* fix onu auto registration on 220 zte olts (c18a636)
* Resolve EP-1184 "/onu autoregistration" (e3b86f2)
* do not count deleted onus for a building map (4c73cfd)
* Resolve EP-000 "/added endpoint for external api" (42f26ec)
* set timeouts for cache keys (2f8247e)
* move documentation files to the correct folder (05fd9d0)
* fix get onu configs on bdcom olts (467deea)
---
## v2.3.8 - 2023-07-13
#### Changes:
* Empty-Commit (cff5d0f)
---
## v2.3.7 - 2023-07-12
#### Changes:
* refactor (d3c300e)
* remove inheritance (81946b4)
* remove old get status serializer method (d1eda61)
* new status field and filter (e9b39d9)
* added building status choices (e24ba46)
* remove graypy handler for client installation (627fcb4)
* add graylog integration (e9fa8ba)
* add names for loggers (f36c7ea)
* add names for loggers (e482a26)
* add filters by slots and ports to the building map (45993cf)
* forbid celery remote control (af06d42)
* reduce db queries (2aa3264)
* more info about author (c62a7d5)
* use update methods to change status (33c9bd4)
* switch on/off admin status on port (0a3eb17)
---
## v2.3.6 - 2023-07-04
#### Changes:
* remove CELERY_ENABLE_REMOTE_CONTROL (71c64b6)
* description for template module (06aab06)
* description for onu module (8b5016b)
* description for olt (6743d77)
* description for core module (3436382)
* fixed cython compilation (f4d90b5)
* rename logger (0603e74)
* add created permission to the admin group member as user permission (88a236b)
* assign new permissions to the admin group (516a7c5)
* check client exists with a billing key (2fb47ef)
* limited max retries and added timeout (c1dc2f8)
* limited max retries and added timeout (3747b37)
* method for send and receive commands with retry (d0dd251)
* fix BDCOM olt snmp protocol connection check and adding new one (4e9b45b)
* Revert "fix BDCOM olt snmp protocol connection check and adding new one" (757e309)
* Revert "fix BDCOM olt snmp protocol connection check and adding new one" (6a6bbf3)
* fix BDCOM olt snmp protocol connection check and adding new one (466082d)
* fix BDCOM olt snmp protocol connection check and adding new one (78ac96a)
* forbid celery remote control (ea4013a)
* try to fix redis failures (0bc7bac)
* added redoc openapi schema (559a073)
* added redoc openapi schema (446c546)
* set port status as unknown (0be0975)
* raise error when port oper status is unknown (5c7d9fd)
* check connection with user credentials on retry (1107142)
* check userside connection with data from user of from settings (fe6a3a3)
* Resolve EP-1129 "/enabale us sync and google auth flag" (d0b2269)
---
## v2.3.5 - 2023-06-21
#### Changes:
* generate title for log entry (f00af8e)
* trim to long title (772d8d8)
* cut generated title and mask password (a8c9470)
* fix registering onu when number on port is not free (4a4c2de)
* fix retrieving onu when there is more than one onu (9e36768)
* fix migration dependencies (e0ade66)
---
## v2.3.4 - 2023-06-20

---
## v2.3.3 - 2023-06-20

---
## v2.3.2 - 2023-06-16
#### Changes:
* update main onu info on sync and refresh from db (55888cb)
* remove old method (7c097cb)
* get first match onu when filter without id (6a973b3)
* add api request type and address to serializer (0d85dbc)
* collect request ip address (d8450d5)
* remove reqeust from args (487a938)
* set author null (bab0927)
* create user for external api requests if auth is stateless (dab3083)
* shift crontab (40d5dbb)
* shift crontab (cb214f4)
* set default values to progress counter if key not exists (d8382bd)
* has templates count without custom presets (a4c7241)
* fix onu task status receiving (5687238)
* change interval for periodic tasks (6e48c59)
* fix onu port migration (150f665)
---
## v2.3.1 - 2023-06-13
#### Changes:
* fix mac assigment in userside integration (537c7be)
* update description (ce9aa08)
* added changed data to the title of log entry (3294376)
* use suppress context manager (dca7401)
* fix get onu mac or serial from userside user info (3d28ec1)
* added ordering by title (6e7175e)
* replaced paginator with increased page size (48547d8)
* validate onu instances with serializer (b66d621)
* fix settings for userside integration (3933b50)
* create signal kwargs on class initialization (a524912)
* fix retrieving crontab for tasks (aa4d4ea)
* fix retrieving crontab for tasks (b1da729)
* add client to admin site (5dd062b)
* fix group creation when not exists (a221259)
* remove not exists task (cf7c15e)
* fix log error on failed request (c9be74e)
* fix request args (ad5d1f2)
* remove redundant serializer (c16c12b)
* created filters and split serializers (69f0331)
* add pagination to building map (214444a)
* Resolve EP-000 "/return all buildings on map" (70909ef)
* add onu magic and olt type in external onu response (eda168d)
* send domain name in header on check license requests (d67d098)
* Resolve EP-000 "/add onu list to building" (90f63d2)
* Resolve EP-1057 "/userside integration settings" (a8250c8)
* Fix filtering in map building (7751d9e)
* Exclude from map building empty buildings (9ca4343)
* Add celery integration to sentry sdk (a9cf1e3)
* Change crontab of userside sync (507c2a2)
* Resolve EP-1059 "/add permission to config endpoint" (03db858)
* fix retrieving qinq port (97ac61d)
* Save and manage filters the user uses to filter some data in different modules. (47a6c5d)
* Change format of geopoint in map_building (2077d63)
* Resolve EP-1025 "/transfer onu location and notice after dublicate deletion" (6df012e)
* Fix switch urls (46d71ca)
* Add switch topology graph (9d9fc15)
* added connection type to external onu api response (c108634)
* added connection type to external onu api response (73c1a6a)
* Add type of userside synchronization (a642b6d)
* change invalid login description message (3747b18)
* logout user after deactivating (4eca60d)
---
## v2.3.0 - 2023-05-18
#### Changes:
* Rename some settings (68bbc2e)
* Fix configuration with live settings (07475ea)
* Done with config in web (f9c95fc)
* Done with adding building to onu (37b964a)
* Add views/serializers for buildings and clients (af2391f)
* Done with buildings and clients (b768c8e)
* Add migration (4a1dede)
* Add integration for userside, now you can import geolocation onu (a4e6f7e)
* Update disprofile module (b882b4b)
* Add near onu geolocation (920ac3c)
* Fix registering onu on deleted onu. (d0642c3)
* Add detail task information about initialise OLT. (34f1690)
* Fix onu config type creating on Huawei olt. (607e04d)
* Remove damaged reports after unsuccessful file downloading. (085058a)
* Fix onu task status changes. (b5c685d)
* Return descriptive message when try to reboot onu and get the connection error. (78c153b)
* Add release to sentry tracking (250da80)
* Fix clients mac on huawei (9c851d5)
* Add find by hexed serial number onu (25aa30b)
* Fix onu update tasks (e6f7c46)
* Skipped slots without qinq (bb6b87d)
* Fix onu update tasks (d787667)
* Fix update onu ethernet vlans tasks. (c85d573)
* Formatted custom action result response. (11990b6)
* Added ordering to for onu port migration and file report tables. (2a19963)
* Clear not existing files and delete them from the filesystem. (f7f0e37)
* Improved onu filtering in logs. (2420155)
* Log can handle the entire onu history. After onu deletion, it does not remove from db. (85dcc5a)
* Add version checker for huawei (56a90d0)
* Change commands for show config in huawei (a3d353a)
* Fix reboot on huawei (4a368e4)
* Fix full update onu on huawei (cab7422)
* Add support of Huawei MA5608T. (9540005)
* make google keys not required (022017f)
* It was improved receiving latest release information. Now get the version that matches client requirements. (267121d)
* Show notification for admin users if a new version of EeasyPON was released. (a1e4374)
---
## v2.2.2 - 2023-05-01
#### Changes:
* Created permission for custom onu action. (4a8fded)
---
## v2.2.1 - 2023-04-27
#### Changes:
* Fix update onu on ZTE GPON (0b33d05)
---
## v2.2.0 - 2023-04-27
#### Changes:
* Release v2.1.1 (982ac49)
* Update .gitlab-ci.yml file (a2e4a18)
* Fix problem with compiled version (cb893d1)
---
## v2.1.1 - 2023-04-27
#### Changes:
* Update .gitlab-ci.yml file (a2e4a18)
* Fix problem with compiled version (cb893d1)
---
## v2.1.0 - 2023-04-27
#### Changes:
* Fix install issue with DB migration. (03db83c)
* Fix problem with infinity get all onu on some ZTE (6c6e247)
* Fix problem on c320 with "No such instance" on get onu status (60459eb)
* Changed method for retrieving olt timezone to improve time calculation. (576fef3)
* Fixed error when trying to update periodic tasks. (5b5866e)
* Fixed error on retrieving shel information on ZTE C220 olts. (fc40d8a)
* Increased description information about config onu log entry. (62134b9)
* Fix migrate onu on another port (19bbfe2)
* Disable prefetch related in olt viewset (b243cad)
* Show additional info about the object in the main user log table. (9091164)
* Remove logging every view action on the switch and switch port. (7bb4929)
* New macros for retrieving onu port number (8bad61b)
* A more informative description of the Excel exported file. (f348f53)
* Added to background task that scans all "onus" on the olt more detailed information about each record.<br> Implemented a counter to keep track of the total number of ONUs found when scanning them on OLT. (3792717)
* Updated install instructions (25e7fda)
* Retrieve Google client id for oauth2 authentication. (79ebeb7)
* Add redis to ci/cd (dffe609)
* Add redis to ci/cd (103f6e5)
* Add redis to ci/cd (1b444e8)
* Add redis to ci/cd (f744867)
* Done with export documentation to gitbook (d9107f0)
* Done with export documentation to gitbook (6800d06)
* Done with export documentation to gitbook (e1af4cc)
* Done with export documentation to gitbook (d5d41ef)
* Done with export documentation to gitbook (e50a8e1)
* Done with export documentation to gitbook (ff09f6d)
* Done with export documentation to gitbook (a31d634)
* Done with export documentation to gitbook (9ba1d43)
* Done with export documentation to gitbook (830ffcd)
* Add override xclsx name for olt classes (3317a2c)
* Changed location map route. (e8e78cb)
* Fixed onu location retrieving (63cef46)
* Add cache-control to allow headers (db2c1ed)
* Test clear cache endpoint (1dfa70d)
* Removed the internal periodic tasks from the request result, so now users will only see the main tasks associated with them. (8dedbd9)
* Added ability for users to save and retrieve filter parameters. (be73aef)
* Added installation instructions for EasyPON. (496bf5e)
* Improve ONU logging to include information on retrieval and applying configuration results: success and failure. (bcefcc4)
* Resolve EP-899 "/merge migrations" (7142e3b)
* Implement access control for dedicated source with new 'Can view onu duplicates' permission (f5ae1d0)
* add celery-expoter binary adn systemd service (49e2c1a)
* Simplify the OLT registration process with the minimal required info: IP, login, pass, and olt type (30c8973)
* Resolve EP-907 "/add offline time to duplicates onus on detail onu edpoint" (eb4648b)
* Implemented new feature for detail page that allows users to view a list of duplicated ONUs, if they exist. (6f27c17)
* Streamlined project language support by keeping only English descriptions. (e81eaa2)
* Implemented new feature: Ordering filter now available for all tables. (e665ddd)
* In the onu firmware variety list, all rows are not grouped by olt. (6319bbb)
* Resolve EP-847 "/change start time for tasks" (4ca46db)
* edit all permissions name (250d4db)
---
## v2.0.3 - 2023-04-03

---
## v2.0.2 - 2023-03-29
#### Changes:
* Update release-it package (da53d73)
* Add artifacts (7b8e461)
---
## v2.0.1 - 2023-03-29
#### Changes:
* Done with cicd (e6735b6)
* Fix module (764a6ea)
* remove compressed data (f41cb55)
* fix outdated checking (750abc7)
* add latest ep release endpoint (f3eab1f)
* decompress data in license check request (5af9d9b)
---
## v2.0.0 - 2023-03-29

---
## v1.0.0 - 2023-03-28
