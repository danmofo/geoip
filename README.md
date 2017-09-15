# GeoIP

1. Run `./install_geoip` to install the required software.
2. Add the following to the cron, `0 0 1-7 * 3 sh /var/everyclick/scripts/geoip/update_geoip`
3. Add the following alias to view the log file: `alias geoiplog='tail -f /home/ec2-user/tmp/geoipupdate.log'
