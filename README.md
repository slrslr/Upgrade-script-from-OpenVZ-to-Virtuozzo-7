# Upgrade-script-from-OpenVZ-to-Virtuozzo-7

"It should migrate any OpenVZ Container, but OS template will be dropped for unsupported OS templates (so, it's will be impossible to use vztt with such Containers after migration). venet's and second level quota migrated too."

Usage:

sh ovztransfer.sh 1.2.3.4 101:101

Will migrate to the remote OpenVZ host server IP 1.2.3.4 container ID 101 and restore it as ID 101

Code source:

https://src.openvz.org/projects/OVZL/repos/ovztransfer/browse

About the script:

https://openvz.org/Upgrade_script_from_OpenVZ_to_Virtuozzo_7
