start from: https://docs.amplify.aws/react/start/quickstart/, cloning a preexistent project of github



git clone https://github.com/andhdo/nuvu-amplify-react1 https://github.com/andhdo/amplify-vite-react-template.git
cd nuvu-amplify-react1 | amplify-vite-react-template && npm install

then go to amplify console

create new app; 
add repo and branch

copy app id: dij6ou4xefz94

visit deployed url


# errors
# # Error: ENOSPC: System limit for number of file watchers reached,
sudo nano /etc/sysctl.conf
| fs.inotify.max_user_watches=524288
sudo sysctl -p
cat /proc/sys/fs/inotify/max_user_watches

