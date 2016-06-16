Welcome to DirtyUnicorns for Surnia
=================================


Instructions
---------------

Initializing:

First, create a folder to hold the source code: 

	mkdir ~/du 

Next..

	cd ~/du

Initialize local repository:

	repo init -u http://github.com/DirtyUnicorns/android_manifest.git -b m-caf

Also add the local manifests:

    git clone https://github.com/DirtyUnicorns-MotoE2015/local_manifests .repo/local_manifests

Sync up:

	repo sync -fcj4 --force-sync --force-broken
	
You can make the 4 higher depending on how fast your internet connection is. 


-------------
 
_Building from source_
---------------

First:

	cd ~/du

Second:

	. build/envsetup.sh

Third:

    brunch surnia
