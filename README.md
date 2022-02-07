git clone git@bitbucket.org:gaaloe/applications.git Applications
sudo apt-get install git-lfs
git lfs install
#First time:
cd Applications
git lfs track '*.AppImage'
git add .gitattributes
git push origin master
