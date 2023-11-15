# 06-assignment


fling@azy-bae MINGW64 ~
$ export TOKEN=dop_v1_791b7dfa1de604030f64b38c1f741414e59c4348cf5bb75a62e44076041d336d

fling@azy-bae MINGW64 ~
$ curl -X POST -H 'Content-Type: application/json' \
    -H 'Authorization: Bearer '$TOKEN'' \
    -d '{"name":"recode",
        "size":"s-1vcpu-512mb-10gb",
        "region":"nyc1",
        "image":"ubuntu-23-10-x64",
        "monitoring":true}' \
    "https://api.digitalocean.com/v2/droplets"
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100  3137  100  2995  100   142   1554     73  0:00:01  0:00:01 --:--:--  1628{"droplet":{"id":385086519,"name":"recode","memory":512,"vcpus":1,"disk":10,"locked":false,"status":"new","kernel":null,"created_at":"2023-11-15T08:30:03Z","features":["monitoring","droplet_agent"],"backup_ids":[],"next_backup_window":null,"snapshot_ids":[],"image":{"id":142476112,"name":"23.10 x64","distribution":"Ubuntu","slug":"ubuntu-23-10-x64","public":true,"regions":["nyc3","nyc1","sfo1","nyc2","ams2","sgp1","lon1","ams3","fra1","tor1","sfo2","blr1","sfo3","syd1"],"created_at":"2023-10-16T14:54:36Z","min_disk_size":7,"type":"base","size_gigabytes":0.82,"description":"Ubuntu 23.10 x64","tags":[],"status":"available"},"volume_ids":[],"size":{"slug":"s-1vcpu-512mb-10gb","memory":512,"vcpus":1,"disk":10,"transfer":0.5,"price_monthly":4.0,"price_hourly":0.00595,"regions":["ams3","fra1","nyc1","sfo3","sgp1","syd1"],"available":true,"description":"Basic"},"size_slug":"s-1vcpu-512mb-10gb","networks":{"v4":[],"v6":[]},"region":{"name":"New York 1","slug":"nyc1","features":["backups","ipv6","metadata","install_agent","storage","image_transfer"],"available":true,"sizes":["s-1vcpu-512mb-10gb","s-1vcpu-1gb","s-1vcpu-1gb-amd","s-1vcpu-1gb-intel","s-1vcpu-1gb-35gb-intel","s-1vcpu-2gb","s-1vcpu-2gb-amd","s-1vcpu-2gb-intel","s-1vcpu-2gb-70gb-intel","s-2vcpu-2gb","s-2vcpu-2gb-amd","s-2vcpu-2gb-intel","s-2vcpu-2gb-90gb-intel","s-2vcpu-4gb","s-2vcpu-4gb-amd","s-2vcpu-4gb-intel","s-2vcpu-4gb-120gb-intel","c-2","c2-2vcpu-4gb","s-4vcpu-8gb","s-4vcpu-8gb-amd","s-4vcpu-8gb-intel","g-2vcpu-8gb","s-4vcpu-8gb-240gb-intel","gd-2vcpu-8gb","g-2vcpu-8gb-intel","gd-2vcpu-8gb-intel","m-2vcpu-16gb","c-4","c2-4vcpu-8gb","s-8vcpu-16gb","m3-2vcpu-16gb","c-4-intel","s-8vcpu-16gb-amd","s-8vcpu-16gb-intel","c2-4vcpu-8gb-intel","g-4vcpu-16gb","s-8vcpu-16gb-480gb-intel","so-2vcpu-16gb","m6-2vcpu-16gb","gd-4vcpu-16gb","g-4vcpu-16gb-intel","gd-4vcpu-16gb-intel","so1_5-2vcpu-16gb","m-4vcpu-32gb","c-8","c2-8vcpu-16gb","m3-4vcpu-32gb","c-8-intel","c2-8vcpu-16gb-intel","g-8vcpu-32gb","so-4vcpu-32gb","m6-4vcpu-32gb","gd-8vcpu-32gb","g-8vcpu-32gb-intel","gd-8vcpu-32gb-intel","so1_5-4vcpu-32gb","m-8vcpu-64gb","c-16","c2-16vcpu-32gb","m3-8vcpu-64gb","c-16-intel","c2-16vcpu-32gb-intel","g-16vcpu-64gb","so-8vcpu-64gb","m6-8vcpu-64gb","gd-16vcpu-64gb","g-16vcpu-64gb-intel","gd-16vcpu-64gb-intel","so1_5-8vcpu-64gb","m-16vcpu-128gb","c-32","c2-32vcpu-64gb","m3-16vcpu-128gb","c-32-intel","c2-32vcpu-64gb-intel","c-48","m-24vcpu-192gb","g-32vcpu-128gb","so-16vcpu-128gb","m6-16vcpu-128gb","gd-32vcpu-128gb","c2-48vcpu-96gb","g-32vcpu-128gb-intel","m3-24vcpu-192gb","g-40vcpu-160gb","gd-32vcpu-128gb-intel","so1_5-16vcpu-128gb","c-48-intel","m-32vcpu-256gb","gd-40vcpu-160gb","c2-48vcpu-96gb-intel","so-24vcpu-192gb","m6-24vcpu-192gb","m3-32vcpu-256gb","g-48vcpu-192gb-intel","gd-48vcpu-192gb-intel","so1_5-24vcpu-192gb","so-32vcpu-256gb","m6-32vcpu-256gb","so1_5-32vcpu-256gb"]},"tags":[]},"links":{"actions":[{"id":1947970666,"rel":"create","href":"https://api.digitalocean.com/v2/actions/1947970666"}]}}


fling@azy-bae MINGW64 ~
$ apt install nodejs
bash: apt: command not found

fling@azy-bae MINGW64 ~
$ apt install nodejs
bash: apt: command not found

fling@azy-bae MINGW64 ~
$ apt install npm
bash: apt: command not found

fling@azy-bae MINGW64 ~
$ npm install -g pm2

npm WARN deprecated uuid@3.4.0: Please upgrade  to version 7 or higher.  Older versions may use Math.random() in certain circumstances, which is known to be problematic.  See https://v8.dev/blog/math-random for details.

added 157 packages in 11s

13 packages are looking for funding
  run `npm fund` for details
npm notice
npm notice New minor version of npm available! 10.1.0 -> 10.2.3
npm notice Changelog: <https://github.com/npm/cli/releases/tag/v10.2.3>
npm notice Run `npm install -g npm@10.2.3` to update!
npm notice

fling@azy-bae MINGW64 ~
$
