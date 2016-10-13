# How to create a new repo
1. Fork this repo
2. Clone your repo and unzip template.zip, open "config.sh", and follow the instructions in the script file to create your own zip file. Note that you might want to use Notepad++ on Windows, since the script files are using Unix endline.
3. After crafting your zip file, take the module.prop you created and replace the one in the repo.  These files should always match.
4. Update "description.html", "changelog.html".
5. Contact @topjohnwu on XDA for a request to add a new module repo. You'll get an empty repo with permission only given to you and the owners of Magisk-Modules-Repo.
6. Push your repo to the new repo created for you. You can push updates directly to your repo in the future as you wish.

# Notes
1. A repo should only contain one zip file.  Any filename is accepted.
2. The module.prop should always be identical to the one in your zip. It is used to compare the info with the module installed on devices.
3. When you update your module, don't forget to bump up the versionCode in module.prop (and make sure it's copied to the zip as well), or Magisk Manager won't know that your module is updated!
4. Make sure the ID in module.prop doesn't contain any spaces.  