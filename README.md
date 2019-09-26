# rails-module-jwt-authentication
> JWT Authentication for rails.

## get-started
```shell
rails new . --api
```

## error
- https://rubyplus.com/articles/5891-Ruby-and-Nokogiri-Gem-Compatibility
- https://stackoverflow.com/questions/35009531/xcrun-error-active-developer-path-applications-xcode-app-contents-developer

```rb
# 先删除了 XCode
sudo xcode-select --reset
gem install nokogiri --verbose
```

## resources
- https://medium.com/binar-academy/rails-api-jwt-authentication-a04503ea3248
- https://github.com/riskimidiw/rails-jwt
- https://engineering.musefind.com/building-a-simple-token-based-authorization-api-with-rails-a5c181b83e02