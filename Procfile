worker: bundle exec sidekiq --concurrency 5 -q default -q low
web: bundle exec rails s -b 0.0.0.0
faye: bundle exec dotenv rackup sync.ru -E production
#mitmproxy: dotenv mitmdump --quiet --transparent --script mitmproxy/log_to_morph.py --cadir mitmproxy
