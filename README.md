#First time, upload and download:
sudo apt-get install git-lfs.
git-lfs install.
#First time upload:
cd Applications
git lfs track '*.AppImage'
git add .gitattributes
#Upload:
chmod ugo-x *.AppImage
git push origin master
#Download:
git clone git@bitbucket.org:gaaloe/applications.git Applications.
cd Applications.
chmod ugo+x *.AppImage
