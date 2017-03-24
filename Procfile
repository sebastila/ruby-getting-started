web: bundle exec puma -C config/puma.rb
web: gunicorn gettingstarted.wsgi logfile
web: java $JAVA_OPTS cp target/classes:target/dependency/* Main
web: node index.js
