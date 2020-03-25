# Webpack not recognizing changes

In Linux or other OSs, a configuration is necessary to make webpack recognize that files changed.

In Ubuntu, the command that solves the issue is `echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p`

Source:
https://stackoverflow.com/questions/34499390/how-to-recompile-webpack-after-changing-files
https://webpack.js.org/configuration/watch/#not-enough-watchers
