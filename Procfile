web: bundle exec puma -C config/puma.rb
worker: bin/delayed_job run --queues=webapp,mailers
release: rake db:migrate