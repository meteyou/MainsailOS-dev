<!-- THIS FILE IS UPDATED AUTOMATICALLY, ANY CHANGES WILL BE OVERRIDDEN -->
# Changelog
All notable changes to MainsailOS will be documented in this file.

## [2.0.26](https://github.com/mainsail-crew/MainsailOS/releases/tag/2.0.26) - 2025-03-26
### Other

- Fix version in step upload to remote server
- Bump version to v2.0.26

## [2.0.25](https://github.com/mainsail-crew/MainsailOS/releases/tag/2.0.25) - 2025-03-25
### Other

- Fix release workflow for only builds
- Rename workflow for build & release
- Add job to finish rpi json and upload it
- Bump version to v2.0.25

## [2.0.24](https://github.com/mainsail-crew/MainsailOS/releases/tag/2.0.24) - 2025-03-23
### Bug Fixes and Improvements

- Add orangepi images to rpi.json

### Other

- Bump version to v2.0.24

## [2.0.23](https://github.com/mainsail-crew/MainsailOS/releases/tag/2.0.23) - 2025-03-22
### Other

- Switch to production images
- Bump version to v2.0.23

## [2.0.22](https://github.com/mainsail-crew/MainsailOS/releases/tag/2.0.22) - 2025-03-22
### Documentation

- Hide pump version commits form changelog

### Other

- Bump version to v2.0.22

## [2.0.21](https://github.com/mainsail-crew/MainsailOS/releases/tag/2.0.21) - 2025-03-22
### Documentation

- Add ci to changelogs

### Other

- Bump version to v2.0.21

## [2.0.20](https://github.com/mainsail-crew/MainsailOS/releases/tag/2.0.20) - 2025-03-22
### Other

- Bump version to v2.0.19
- Split git commands in single steps in the prepare-release job
- Fetch all commits in prepare-release step to read the last tag
- Fix changelog.md generation
- Bump version to v2.0.20

## [2.0.19](https://github.com/mainsail-crew/MainsailOS/releases/tag/2.0.19) - 2025-03-22
### Other

- Fix ff merge
- Bump version to v2.0.18

## [2.0.18](https://github.com/mainsail-crew/MainsailOS/releases/tag/2.0.18) - 2025-03-22
### Other

- Fix fake compressed image file
- Bump version to v2.0.17

## [2.0.17](https://github.com/mainsail-crew/MainsailOS/releases/tag/2.0.17) - 2025-03-22
### Other

- Use fake compressed file
- Fix release tag in publish release step
- Fix branch name in merge-developt-to-master step
- Bump version to v2.0.16

## [2.0.16](https://github.com/mainsail-crew/MainsailOS/releases/tag/2.0.16) - 2025-03-22
### Other

- Fix changelog in release
- Fix publish release step
- Bump version to v2.0.15

## [2.0.15](https://github.com/mainsail-crew/MainsailOS/releases/tag/2.0.15) - 2025-03-21
### Other

- Enable compressing image
- Bump version to v2.0.14

## [2.0.14](https://github.com/mainsail-crew/MainsailOS/releases/tag/2.0.14) - 2025-03-21
### Other

- Fix upload to release
- Bump version to v2.0.13

## [2.0.13](https://github.com/mainsail-crew/MainsailOS/releases/tag/2.0.13) - 2025-03-21
### Other

- Fix release upload
- Add merge develop-to-master job
- Bump version to v2.0.11
- Fix needs from finish-release and update-changelog

## [2.0.11](https://github.com/mainsail-crew/MainsailOS/releases/tag/2.0.11) - 2025-03-21
### Other

- Fake compress image step
- Bump version to v2.0.10

## [2.0.10](https://github.com/mainsail-crew/MainsailOS/releases/tag/2.0.10) - 2025-03-21
### Other

- Bump version to v2.0.9
- Fake compress image step

## [2.0.9](https://github.com/mainsail-crew/MainsailOS/releases/tag/2.0.9) - 2025-03-21
### Other

- Fake compress image step
- Bump version to v2.0.8

## [2.0.8](https://github.com/mainsail-crew/MainsailOS/releases/tag/2.0.8) - 2025-03-21
### Other

- Fix rpi json generation
- Bump version to v2.0.7

## [2.0.7](https://github.com/mainsail-crew/MainsailOS/releases/tag/2.0.7) - 2025-03-21
### Other

- Fix rpi json generation
- Bump version to v2.0.6

## [2.0.6](https://github.com/mainsail-crew/MainsailOS/releases/tag/2.0.6) - 2025-03-21
### Other

- Bump version to v2.0.5

## [2.0.5](https://github.com/mainsail-crew/MainsailOS/releases/tag/2.0.5) - 2025-03-21
### Other

- Fix build job dependencies
- Bump version to v1.2.3

## [1.2.3](https://github.com/mainsail-crew/MainsailOS/releases/tag/1.2.3) - 2025-03-21
### Other

- Fix prepare release and push tag
- Bump version to 2.0.4
- Fix build job dependencies
- Fix build job dependencies
- Fix build job dependencies
- Fix build job dependencies
- Add debug outputs
- Fix build job dependencies
- Fix build job dependencies

## [2.0.4](https://github.com/mainsail-crew/MainsailOS/releases/tag/2.0.4) - 2025-03-13
### Other

- Test for rpi json
- Bump version to 2.0.3

## [2.0.3](https://github.com/mainsail-crew/MainsailOS/releases/tag/2.0.3) - 2025-03-13
### Other

- Bump version to 2.0.2
- Fix typo in release.yml

## [2.0.2](https://github.com/mainsail-crew/MainsailOS/releases/tag/2.0.2) - 2025-03-12
### Other

- Use fake image and fix gh release upload tag
- Bump version to 2.0.1

## [2.0.1](https://github.com/mainsail-crew/MainsailOS/releases/tag/2.0.1) - 2025-03-12
### Features

- **armbian**: Add armbian dependencies
- **armbian-motd**: Add armbian motd from mainsailos
- **armbian-net**: Add module for armbian network config
- **armbian-root**: Remove autologin and lock root account
- **ci**: Add KlipperScreen module ([#284](https://github.com/mainsail-crew/MainsailOS/pull/284))
- **headless-nm**: Add module for NetworkManager
- **opi-4tls**: Enable spi for orangepi 4lts
- **opi-4tls**: Enable spi for orangepi 4lts
- **opi-4tls**: Enable spi for orangepi 4lts
- **special-module**: Add option to allow special modules for a single sbc
- **wifi-powersave-off**: Add module for wifi powersave mode off
- Add BananaPi M2 Zero ([#247](https://github.com/mainsail-crew/MainsailOS/pull/247))
- Adds kiauh module for homebrewed images ([#184](https://github.com/mainsail-crew/MainsailOS/pull/184))
- Add python3-opencv for obico ([#248](https://github.com/mainsail-crew/MainsailOS/pull/248))
- Add modified pkgupgrade
- Add headless_mn module
- Upload first build workflow test file
- Add step to unpack and rename image
- Add first script to just upgrade the base image
- Rename and upload build images
- Add option to route config.local from config.yml to config.local
- First test for klipper module
- Add 11-add-user module for armbian devices
- Add moonraker module
- Finish moonraker module
- Add mainsail module
- Add all klipper input shaper dependencies
- Add mainsailos module
- Add piwheels to pip.conf in 00-dist-upgrade
- Add crowsnest module
- Add sonar module
- Add postrename module
- Add timelapse module
- Add config-raspberry module
- Add condition to copy special files, when they exists and needed
- Add branch for clone sonar
- Add orangepi 3 lts
- Add orangepi zero2
- Add orangepi 3 lts spi-config
- Add orangepi zero2 config
- Add rpi 32bit
- Change hostname to DIST_NAME

### Bug Fixes and Improvements

- **armbian-net**: Fix name from network-configurator.service
- **armbian-root**: Move armbian-root to pos 98
- **build**: Fix location of boot partition ([#289](https://github.com/mainsail-crew/MainsailOS/pull/289))
- **build**: Fix log file upload ([#297](https://github.com/mainsail-crew/MainsailOS/pull/297))
- **build**: Disable pkgupgrade
- **build**: Fix shellcheck errors
- **ci**: Fix annotations from actions ([#285](https://github.com/mainsail-crew/MainsailOS/pull/285))
- **crowsnest**: Add moonraker update config to moonraker.conf
- **headless-nm**: Copy template to /boot
- **headless-nm**: Fix userrights from /usr/local/bin/headless_nm
- **headless-nm**: Reload nm to read new config file
- **headless-nm**: Remove unnecessary \n in log output
- **headless-nm**: Fix script and reload only when service is active
- **mainsail**: User rights
- **mainsail**: Fix nginx user rights
- **moonraker**: PKGLIST variable rename ([#298](https://github.com/mainsail-crew/MainsailOS/pull/298))
- **postrename**: Create rc.local if it doesnt exists
- **postrename**: Remove sudo in module
- **postrename**: Move postrename to rpi
- **sonar**: Set options to the make install command
- **sonar**: Fix extract PKGLIST instead of source the file
- **sonar**: Fix make install command
- **sonar**: Fix make install command
- **sonar**: Remove install dependencies, because the install script will do it
- **sonar**: Let installer install the service file
- **sonar**: Remove unused install variable from .config
- **timelapse**: Fix moonraker path
- Remove enduser support msg from zero2 images ([#209](https://github.com/mainsail-crew/MainsailOS/pull/209))
- Fix rpi-imager json value format for extract_size & image_download_size ([#212](https://github.com/mainsail-crew/MainsailOS/pull/212))
- Fix firstboot issue ([#214](https://github.com/mainsail-crew/MainsailOS/pull/214))
- Load `i2c-dev` modules ([#217](https://github.com/mainsail-crew/MainsailOS/pull/217))
- Fix broken udev package ([#224](https://github.com/mainsail-crew/MainsailOS/pull/224))
- Fix udev for version 'rp1+deb11u2' ([#226](https://github.com/mainsail-crew/MainsailOS/pull/226))
- Remove legacy cam stack ([#227](https://github.com/mainsail-crew/MainsailOS/pull/227))
- Fix error in udev-fix.sh ([#228](https://github.com/mainsail-crew/MainsailOS/pull/228))
- Add crowsnest log path & pkglist link in postrename script ([#235](https://github.com/mainsail-crew/MainsailOS/pull/235))
- Fix typo in tools_dir var, Line171 ([#237](https://github.com/mainsail-crew/MainsailOS/pull/237))
- Fix wifi connectivity ([#240](https://github.com/mainsail-crew/MainsailOS/pull/240))
- Fix armbian-release file error ([#241](https://github.com/mainsail-crew/MainsailOS/pull/241))
- Fix error autologin on serial tty ([#242](https://github.com/mainsail-crew/MainsailOS/pull/242))
- Fix 'is_board_type' function ([#243](https://github.com/mainsail-crew/MainsailOS/pull/243))
- Fix Torrent and Checksum download URLs ([#244](https://github.com/mainsail-crew/MainsailOS/pull/244))
- Removing 'klippy' alias ([#246](https://github.com/mainsail-crew/MainsailOS/pull/246))
- Fix motd on armbian and orange pi based images ([#272](https://github.com/mainsail-crew/MainsailOS/pull/272))
- Fix version number in release ([#275](https://github.com/mainsail-crew/MainsailOS/pull/275))
- Fix version number in release workflow ([#276](https://github.com/mainsail-crew/MainsailOS/pull/276))
- Add supported sbc to non rpi images ([#277](https://github.com/mainsail-crew/MainsailOS/pull/277))
- Fix no space left error
- Fix orangepi zero2 url
- Fix klipperscreen build
- Drop armbian_net module for bookworm images
- Fix rpi64-ks
- Fix config paths for bookworm
- Fix path in piconfig module
- Fix shellcheck errors
- Fix headless_nm module
- Fix execustion permission
- Fix modules for bullseye images
- Fix postrename script
- Fix workflow_config.yml
- Fix missing newline
- Fix BASE_BOARD for rpi images
- Fix BASE_BOARD for armbian images
- Set BASE_IMAGE_PATH for armbian images
- Set BASE_IMAGE_PATH for armbian images
- Set BASE_IMAGE_PATH for armbian images
- Add export BASE_BOARD to build_dist
- Source repository/src/config before start build process
- Test armbian modules
- Test armbian modules
- Create group gpio only, if it doesnt exists
- Test base module for rpi images
- Test pkgupgrade module for rpi images
- Test all modules expect pkgupgrade
- Test all modules expect pkgupgrade
- Change camera-streamer repo to mryel00 fork to build rpi images
- Fix issue in build.yml
- Fix issue in build.yml
- Fix download urls in config.yml
- Fix checksum step
- Fix emojies in step names
- Fix unpack and rename image step
- Rename command in Unpack and rename image
- Add missing test modules
- Add ARCH to build path
- Fix filename in compress and upload steps
- Add dns server to execute CustoPiZer
- Fix filename in create hash step
- Add set-nameservers module for armbian
- Add set-nameservers module for armbian
- Add debug output to rename image
- Add DISTRO name armbian to armbian image
- Fix paths in build.yaml
- Remove armbian 00-set-namespaces because its altready in the CustoPiZer
- Fix scripts directory
- Hold linux kernel updates
- Hold raspi-firmware linux-dtb-* while dist-upgrade
- Enlargeroot for 2500mb to have more free space to install all packages
- Add armbian-firmware to apt-mark hold
- Remove hidding output of apt-mark hold to double check the rpi workflow
- Ignore errors while executing apt-mark hold/unhold and use an array syntax for the packages
- Unhold packges as last step
- Increase enlargeroot to 3500
- Move packages to /files/00-hold-packages-config
- Remove unnecessary apt-get update
- Add mkdir -p /home/pi/.local/tmp before creating virtualenv
- Enlarge build workspace/image to 5gb
- Finish klipper module
- Add rpi-eeprom to apt hold list
- Add printer_data/systemd to klipper dirs
- Fix extract debian_deps
- Add -z to set-policykit-rules.sh
- Fix inport in 00-dist-upgrade
- Fix url to 00-config in 99-unhold-packages
- Use an array for the mainsail dependencies
- Rename upstream.conf to upstreams.conf
- Fix userrights for git clone files/clones
- Fix crowsnest repo url
- Convert pkglist string to array
- Fix root issue to run make install
- Fix install crowsnest
- Fix clone sonar path
- Add SONAR_DEFAULT_CONF to sonar module
- Fix PWD in sonar module before executing make install
- Fix PWD in sonar module before executing make install
- Fix PWD in sonar module before executing make install
- Fix PWD in sonar module before executing make install

### Refactor

- **armbian**: Refactor module and rename 11-add-uer-pi to 10-armbian
- **crowsnest**: Refactor module with section headers
- **dist-upgrade**: Refactor module with section headers
- **headless-nm**: Add some additional infos to template file
- **headless-nm**: Fix some typos in the WiFi-README.txt
- **klipper**: Refactor module with section headers
- **mainsail**: Refactor module with section headers
- **mainsailos**: Refactor module with section headers
- **moonraker**: Refactor module with section headers
- **sonar**: Change to attributes in make install
- **sonar**: Add moonraker update config to moonraker.conf
- **unhold-packages**: Refactor module with section headers
- Drop armbian_pkgupgrade ([#210](https://github.com/mainsail-crew/MainsailOS/pull/210))
- Change version handling ([#296](https://github.com/mainsail-crew/MainsailOS/pull/296))
- Move BASE_IMAGE_PATH to generic config
- Reformat BASE_ARCH and BASE_BOARD in armbian board configs
- Simplify config files
- Remove all old files
- Remove wront value in enviroments
- Use a variable for all packages which should be hold
- Remove some debug outputs and simplify creating dir function
- Cleanup 51-moonraker install script
- Cleanup 50-klipper install script
- Fix spellcheck 51-moonraker install script
- Remove DEBIAN_FRONTEND=noninteractive in 51-moonraker
- Use an array for the klipper dependencies
- Move create_user_directories to 00-config
- Rename sonar from 54 to 55
- Use .config file to install Sonar
- Make installer more readable and fix spellcheck issues
- Move to sonar refactor/pynar branch

### Styling

- Add shebang to module files to have IDE syntax highlighting
- Remove unused linebreak

### Documentation

- Fix broken README link to the docs ([#231](https://github.com/mainsail-crew/MainsailOS/pull/231))

### Other

- **build**: Add new matrix workflow ([#253](https://github.com/mainsail-crew/MainsailOS/pull/253))
- **build**: Add bullseye control group
- **ci**: Skip build on push to master branch ([#280](https://github.com/mainsail-crew/MainsailOS/pull/280))
- **release**: Skip the ftp upload, if repo != Mainsail-Crew ([#269](https://github.com/mainsail-crew/MainsailOS/pull/269))
- **release**: Generate changelog from 0.0.0, if repo != Mainsail-Crew ([#270](https://github.com/mainsail-crew/MainsailOS/pull/270))
- **release**: Update publish release action ([#268](https://github.com/mainsail-crew/MainsailOS/pull/268))
- **release**: Fix changelog workflow ([#271](https://github.com/mainsail-crew/MainsailOS/pull/271))
- Remove unattended-upgrades service ([#215](https://github.com/mainsail-crew/MainsailOS/pull/215))
- Revert firstboot fix ([#219](https://github.com/mainsail-crew/MainsailOS/pull/219))
- Update crowsnest module ([#221](https://github.com/mainsail-crew/MainsailOS/pull/221))
- Update download urls for armbian & orangepi ([#233](https://github.com/mainsail-crew/MainsailOS/pull/233))
- Update .gitignore ([#254](https://github.com/mainsail-crew/MainsailOS/pull/254))
- Refactor build & release workflow to remove external actions ([#264](https://github.com/mainsail-crew/MainsailOS/pull/264))
- Update issue bot text ([#265](https://github.com/mainsail-crew/MainsailOS/pull/265))
- Update generate json to new format ([#266](https://github.com/mainsail-crew/MainsailOS/pull/266))
- Fix typo in bot text ([#273](https://github.com/mainsail-crew/MainsailOS/pull/273))
- Bump base OS to 'bookworm'
- Update urls and base image version ([#288](https://github.com/mainsail-crew/MainsailOS/pull/288))
- Add piwheels config, if it doesnt exists ([#290](https://github.com/mainsail-crew/MainsailOS/pull/290))
- Change module order ([#291](https://github.com/mainsail-crew/MainsailOS/pull/291))
- Switch to armbian for Opi Zero2 ([#292](https://github.com/mainsail-crew/MainsailOS/pull/292))
- Solve merge conflicts
- Reenable pkgupgrade for debug purpose
- Set boot partition
- Debug pkgupgrade
- Remove pkgupgrade module
- Refactor wifi readme
- Add pi5 to json supported sbcs
- Refactor wifi-readme.txt
- Use headless_nm for armbian images
- Extend headless_nm for armbian based images
- Use altered DNS servers
- Renamed module
- Test PR repo
- Run with altered dns
- Test potential PR to custompios
- Test run for fix/armbiandns pr
- Revert to original custompios repo
- Remove bullseye control builds
- Fix copyright date
- Update wifi-readme.txt
- Reenable pkgupgrade for ks version
- Update headless_nm.txt.template
- Add python3-git to install dependencies in build workflow
- Change custompios repo
- Test to export BASE_BOARD
- Change branch to fix-branch
- Upload VERSION file
- Add fast-fail:false to the build chain
- Switch CustoPiZer to my fork
- Add emojis to all steps
- Remove debug outputs
- Hide output for apt-mark and unhold in 00-dist-upgrade
- Test ubuntu-22.04-arm64 runner instead of ubuntu-latest
- Fix runner to ubuntu-24.04-arm
- Fix runner to ubuntu-22.04-arm
- Disable dist-upgrade to speedup test builds
- Change emoji for set RELEASE_TAG from VERSION file
- Set DEBIAN_FRONTEND to noninteractive in 00-dist-upgrade
- Test CI on ubuntu-latest (non arm)
- Move back to ubuntu-22.04-arm runner
- Fix verify image
- Double check verify image with wrong hash
- Reset raspi hash url
- Remove unnecessary delete command from the hash file
- Refactor build.xml and use working-directory
- Add function to disable modules, when the module name ends with ".disabled"
- Disable 11-armbian-net module
- Fix issue, when no disabled module exists
- Fix issue, when no disabled module exists
- Disable DHT (Distributed Hash Table) in aria2c
- Add date into filename
- Upload release workflow
- Fix CustoPiZer action version

## [1.1.0](https://github.com/mainsail-crew/MainsailOS/releases/tag/1.1.0) - 2023-03-15
### Features

- Enable I2C by default ([#196](https://github.com/mainsail-crew/MainsailOS/pull/196))
- Add Orange Pi 3 and 4 LTS ([#186](https://github.com/mainsail-crew/MainsailOS/pull/186))
- Add orange pi zero2 ([#189](https://github.com/mainsail-crew/MainsailOS/pull/189))

### Bug Fixes and Improvements

- **build**: Fix mv of image file ([#204](https://github.com/mainsail-crew/MainsailOS/pull/204))
- **lint**: Should fix shellcheck warnings ([#160](https://github.com/mainsail-crew/MainsailOS/pull/160))
- Fix postrename script ([#150](https://github.com/mainsail-crew/MainsailOS/pull/150))
- Fix shellcheck errors in net module ([#161](https://github.com/mainsail-crew/MainsailOS/pull/161))
- Set wrong source path ([#164](https://github.com/mainsail-crew/MainsailOS/pull/164))
- Add otg_mode=1 for CM4 in config.txt ([#167](https://github.com/mainsail-crew/MainsailOS/pull/167))
- Fix SC2086 in armbian module ([#173](https://github.com/mainsail-crew/MainsailOS/pull/173))
- Fixes error setting link to macro ([#175](https://github.com/mainsail-crew/MainsailOS/pull/175))
- Fix shellcheck errors ([#185](https://github.com/mainsail-crew/MainsailOS/pull/185))
- Fix syntax error in net module ([#191](https://github.com/mainsail-crew/MainsailOS/pull/191))
- Fix compress step ([#205](https://github.com/mainsail-crew/MainsailOS/pull/205))
- Fix rpi-image.json workflow in Release.yml ([#206](https://github.com/mainsail-crew/MainsailOS/pull/206))

### Refactor

- Deactivate IPv6 in nginx per default ([#157](https://github.com/mainsail-crew/MainsailOS/pull/157))
- Change behavior of piconfig module ([#180](https://github.com/mainsail-crew/MainsailOS/pull/180))
- Use mv to move the image from the workspace to the root ([#203](https://github.com/mainsail-crew/MainsailOS/pull/203))

### Documentation

- Adds faq section

### Other

- **build**: Refactor build dependend files ([#154](https://github.com/mainsail-crew/MainsailOS/pull/154))
- **workflow**: Rework release workflow for multi builds ([#181](https://github.com/mainsail-crew/MainsailOS/pull/181))
- Rework build workflow with source image cache ([#146](https://github.com/mainsail-crew/MainsailOS/pull/146))
- Only build an image on push in master/develop branch ([#148](https://github.com/mainsail-crew/MainsailOS/pull/148))
- Change cron interval of stale action ([#149](https://github.com/mainsail-crew/MainsailOS/pull/149))
- Update versions according to bullseye ([#147](https://github.com/mainsail-crew/MainsailOS/pull/147))
- Rework build workflow for multiple images ([#152](https://github.com/mainsail-crew/MainsailOS/pull/152))
- Fix image name ([#153](https://github.com/mainsail-crew/MainsailOS/pull/153))
- Impove shellcheck and auto read version number ([#155](https://github.com/mainsail-crew/MainsailOS/pull/155))
- Add Raspberry 64bit config ([#156](https://github.com/mainsail-crew/MainsailOS/pull/156))
- Upload failed logfile ([#163](https://github.com/mainsail-crew/MainsailOS/pull/163))
- Add armbian module ([#165](https://github.com/mainsail-crew/MainsailOS/pull/165))
- Update modules according to path changes ([#166](https://github.com/mainsail-crew/MainsailOS/pull/166))
- Update BuildImages workflow ([#171](https://github.com/mainsail-crew/MainsailOS/pull/171))
- Improved shellcheck lint ([#172](https://github.com/mainsail-crew/MainsailOS/pull/172))
- Remove github-token for build action ([#178](https://github.com/mainsail-crew/MainsailOS/pull/178))
- Add "not-on-Github" bot for issues ([#179](https://github.com/mainsail-crew/MainsailOS/pull/179))
- Fix changelog in release workflow ([#182](https://github.com/mainsail-crew/MainsailOS/pull/182))
- Removes fkms overlays ([#183](https://github.com/mainsail-crew/MainsailOS/pull/183))

## [0.7.1](https://github.com/mainsail-crew/MainsailOS/releases/tag/0.7.1) - 2022-09-06
### Bug Fixes and Improvements

- Fix errors in moved venvs ([#138](https://github.com/mainsail-crew/MainsailOS/pull/138))
- Fixes error unusable wpa_supplicant.txt ([#142](https://github.com/mainsail-crew/MainsailOS/pull/142))

### Documentation

- Update README for improved readability ([#144](https://github.com/mainsail-crew/MainsailOS/pull/144))

### Other

- Add wireless-tools as moonraker dependency ([#137](https://github.com/mainsail-crew/MainsailOS/pull/137))
- Add workflow to close stale issues / pull requests ([#139](https://github.com/mainsail-crew/MainsailOS/pull/139))
- Add additional Input shaper dependencies ([#140](https://github.com/mainsail-crew/MainsailOS/pull/140))
- Bump version to v0.7.1 ([#145](https://github.com/mainsail-crew/MainsailOS/pull/145))

## [0.7.0](https://github.com/mainsail-crew/MainsailOS/releases/tag/0.7.0) - 2022-07-29
### Features

- **moonraker.conf**: Add mainsail subscription to announcements ([#115](https://github.com/mainsail-crew/MainsailOS/pull/115))
- Stop part fan on CANCEL_PRINT ([#103](https://github.com/mainsail-crew/MainsailOS/pull/103))
- Add on_error_gcode to mainsail.cfg ([#116](https://github.com/mainsail-crew/MainsailOS/pull/116))
- Add sonar by default to image ([#107](https://github.com/mainsail-crew/MainsailOS/pull/107))
- Add on_error_gcode to mainsail.cfg ([#116](https://github.com/mainsail-crew/MainsailOS/pull/116))
- Add python3-serial CanBoot dependency ([#129](https://github.com/mainsail-crew/MainsailOS/pull/129))
- Add postrename module ([#128](https://github.com/mainsail-crew/MainsailOS/pull/128))
- Add timelapse module ([#130](https://github.com/mainsail-crew/MainsailOS/pull/130))

### Bug Fixes and Improvements

- **config.txt**: Fix configuration errors with attached screens ([#119](https://github.com/mainsail-crew/MainsailOS/pull/119))
- **crowsnest**: Fix install of crowsnest ([#111](https://github.com/mainsail-crew/MainsailOS/pull/111))
- **mainsail**: Changed download url to mainsail-crew url ([#92](https://github.com/mainsail-crew/MainsailOS/pull/92))
- **sonar**: Fixes missing moonraker update manager entry ([#112](https://github.com/mainsail-crew/MainsailOS/pull/112))
- Correct on_error_gcode in mainsail.cfg ([#118](https://github.com/mainsail-crew/MainsailOS/pull/118))
- Correct on_error_gcode in mainsail.cfg ([#118](https://github.com/mainsail-crew/MainsailOS/pull/118))

### Refactor

- **klipper**: Refactor klipper and is-pre-install module ([#113](https://github.com/mainsail-crew/MainsailOS/pull/113))
- **mainsail.cfg**: Substituting `/home/pi` with `~` ([#114](https://github.com/mainsail-crew/MainsailOS/pull/114))
- **mainsail.cfg**: Substituting `/home/pi` with `~` ([#114](https://github.com/mainsail-crew/MainsailOS/pull/114))
- Add `enable_auto_refresh: True` ([#133](https://github.com/mainsail-crew/MainsailOS/pull/133))

### Documentation

- Fix typo in readme.md ([#91](https://github.com/mainsail-crew/MainsailOS/pull/91))
- Correct screenshot image URL ([#93](https://github.com/mainsail-crew/MainsailOS/pull/93))
- Add mainsailos logo ([#124](https://github.com/mainsail-crew/MainsailOS/pull/124))

### Other

- **README**: Update README according to latest changes. ([#110](https://github.com/mainsail-crew/MainsailOS/pull/110))
- **crowsnest**: Update crowsnest module ([#123](https://github.com/mainsail-crew/MainsailOS/pull/123))
- **docs**: Fix urls, add includes ([#122](https://github.com/mainsail-crew/MainsailOS/pull/122))
- **klipper**: Update klipper and input shaper to py3 ([#105](https://github.com/mainsail-crew/MainsailOS/pull/105))
- Update moonraker.conf ([#101](https://github.com/mainsail-crew/MainsailOS/pull/101))
- Add funding informations ([#120](https://github.com/mainsail-crew/MainsailOS/pull/120))
- Add Issue Templates ([#121](https://github.com/mainsail-crew/MainsailOS/pull/121))
- Bump version to 0.7.0 ([#131](https://github.com/mainsail-crew/MainsailOS/pull/131))

## [0.6.1](https://github.com/mainsail-crew/MainsailOS/releases/tag/0.6.1) - 2022-01-31
### Bug Fixes and Improvements

- **build**: Updated torrent download url ([#90](https://github.com/mainsail-crew/MainsailOS/pull/90))

### Other

- Push versionnumber to 0.6.1

## [0.6.0](https://github.com/mainsail-crew/MainsailOS/releases/tag/0.6.0) - 2022-01-31
### Features

- **build**: Removed raspicam and serialcomm module ([#83](https://github.com/mainsail-crew/MainsailOS/pull/83))
- Add park to CANCEL_PRINT ([#58](https://github.com/mainsail-crew/MainsailOS/pull/58))
- Replaced module busterpatch ([#77](https://github.com/mainsail-crew/MainsailOS/pull/77))
- Added .editorconfig ([#78](https://github.com/mainsail-crew/MainsailOS/pull/78))
- Changed logging and logrotate behavior ([#79](https://github.com/mainsail-crew/MainsailOS/pull/79))
- Added mainsailos module ([#81](https://github.com/mainsail-crew/MainsailOS/pull/81))

### Bug Fixes and Improvements

- **build**: Updated download paths ([#65](https://github.com/mainsail-crew/MainsailOS/pull/65))
- **build**: Fixes error in Makefile ([#76](https://github.com/mainsail-crew/MainsailOS/pull/76))
- **ustreamer**: Disable buffering on webcam proxy entries ([#84](https://github.com/mainsail-crew/MainsailOS/pull/84))
- Nginx config file
- Added http1.1 to moonraker api reverse proxy location ([#75](https://github.com/mainsail-crew/MainsailOS/pull/75))

### Refactor

- Updated input shaper dependencies to python3 ([#74](https://github.com/mainsail-crew/MainsailOS/pull/74))

### Documentation

- Improve reamde.md ([#54](https://github.com/mainsail-crew/MainsailOS/pull/54))

### Other

- **moonraker**: Refactored moonraker module ([#89](https://github.com/mainsail-crew/MainsailOS/pull/89))
- **workflows**: Update pull_request trigger
- Update default moonraker.conf
- Remove job_queue and postprocessing from moonraker.conf
- Updated .editorconfig for yml files ([#86](https://github.com/mainsail-crew/MainsailOS/pull/86))

## [0.5.0](https://github.com/mainsail-crew/MainsailOS/releases/tag/0.5.0) - 2021-08-28
### Features

- Add multi mjpegstreamer support in klipper_config dir ([#35](https://github.com/mainsail-crew/MainsailOS/pull/35))

### Other

- **build**: 0.5.0 bump

## [0.1.0](https://github.com/mainsail-crew/MainsailOS/releases/tag/0.1.0) - 2020-11-28
### Features

- Allow the app.fluidd.xyz origin

## [0.0.9](https://github.com/mainsail-crew/MainsailOS/releases/tag/0.0.9) - 2020-10-16
### Other

- Moves $httpupgrade and upstream servers to common config


