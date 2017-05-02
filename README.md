# dpkgLocked

if dpkg is locked 

You can delete the lock file with the following command:

sudo rm /var/lib/apt/lists/lock

You may also need to delete the lock file in the cache directory:

sudo rm /var/cache/apt/archives/lock
sudo rm /var/lib/dpkg/lock
