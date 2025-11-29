# davedkg-rails-sandbox

## Local Setup

```bash
brew install postgres
bundle && yarn
cp .env.sample .env
bundle exec rake db:setup
foreman start -f Procfile.dev
open http://localhost:3000/
```
