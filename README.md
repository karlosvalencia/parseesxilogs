# parseesxilogs
# To add a file:
git add file
# To remove a file
git remove file
# To commit changes
git commit -m "Reason for commit"
# To push to mainstrean
git push -u orgin master
###############################################
# Below original notes to create the repo. User on githun: valenciakarlos
echo "# parseesxilogs" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/valenciakarlos/parseesxilogs.git
git push -u origin master
##################################################################################
***** Also have the repo on our internal bitbucket
##################################################################################

# URL : https://hwstashprd01.isus.emc.com:8443/projects/NFV/repos/parse_esxi_stats/browse
# To switch between repos :
git remote set-url origin https://valenc6@hwstashprd01.isus.emc.com:8443/scm/nfv/parse_esxi_stats.git
git push -u origin --all
git push origin --tags
# To switch back to  github
git remote set_url origin https://github.com/valenciakarlos/parseesxilogs.git

