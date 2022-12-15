# reMarkableBuJo

Simple templates for BuJo on the reMarkable.

## Instructions

 - scp the png and svg files to the reMarkable put the in `/usr/share/remarkable/templates/`
   - for all templates simply scp `templates.tar` to the reMarkable and extract the tar in the above mentioned directory
 - configure the templates in the `templates.json` or use [templatectl](https://github.com/PeterGrace/templatectl).
   - If you use `templatectl` you might want to use it via [Toltec](https://toltec-dev.org) to preserve your templates upon update
 - `mood and habit` file is landscape. So `"landscape": true` must be added in the `template.json`
 - don't forget to `systemctl restart xochitl` after update

For icons and more detailed instructions see [here](https://remarkablewiki.com/tips/templates)

## Tools

 - `png2svg.sh`:  Simple script to convert png files to svg files. Dependencies: `convert` and `potrace`

## Additional Files

 - `*.xvf`: Gimp project files
 - `templates.tar`: TAR of all png and svg files for easy transfer 
