<br/>
<div align="center">

A curated list of awesome Ruby Security related resources.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

*List inspired by the [awesome](https://github.com/sindresorhus/awesome) ⭐ 498,696 | 🐛 105 | 📅 2026-08-21 list thing.*

</div>
<br/>

# Contents

* [Tools](#tools)
* [Educational](#educational)
* [Other](#other)
* [Contributing](#contributing)

# Tools

## Web Framework Hardening

* [Rack::Attack](https://github.com/kickstarter/rack-attack) ⭐ 5,763 | 🐛 19 | 🌐 Ruby | 📅 2026-07-02 - Middleware for blocking and throttling requests.
* [secure-headers](https://github.com/twitter/secure_headers) ⭐ 3,229 | 🐛 13 | 🌐 Ruby | 📅 2026-07-27 - Manages application of security headers with many safe defaults.

## Multi tools

* [Ronin](https://github.com/ronin-rb/ronin) ⭐ 753 | 🐛 34 | 🌐 Ruby | 📅 2026-01-12 - Ronin is a free and Open Source Ruby toolkit for security research and development.
* [Salus](https://github.com/coinbase/salus) ⭐ 31 | 🐛 42 | 🌐 HTML | 📅 2025-06-12 - Multi purpose security scanning tool supporting Ruby, Node, Python and Go.
* [Snyk](https://snyk.io) - Continuously and automatically finds & fixes vulnerabilities for Ruby and other languages.

## Static Code Analysis

* [git-secrets](https://github.com/awslabs/git-secrets) ⭐ 13,379 | 🐛 131 | 🌐 Shell | 📅 2025-09-17 - Prevents you from committing secrets and credentials into git repositories.
* [brakeman](https://github.com/presidentbeef/brakeman) ⭐ 7,261 | 🐛 113 | 🌐 Ruby | 📅 2026-08-13 - A static analysis security vulnerability scanner for Ruby on Rails applications.
* [rails\_best\_practices](https://github.com/flyerhzm/rails_best_practices) ⭐ 4,163 | 🐛 61 | 🌐 Ruby | 📅 2026-04-23 - A static code analyzer for Ruby on Rails applications that finds - among other things - common patterns that might lead to security vulnerabilities.
* [Bearer](https://github.com/Bearer/bearer) ⭐ 2,732 | 🐛 16 | 🌐 Go | 📅 2026-08-20 - A code security scanning tool (SAST) to discover, filter and prioritize security and privacy risks.
* [DevSkim](https://github.com/Microsoft/DevSkim) ⭐ 1,003 | 🐛 74 | 🌐 C# | 📅 2026-08-16 - DevSkim is a set of IDE plugins and rules that provide security "linting" capabilities. Also has support for CLI so it can be integrated into CI/CD pipeline.
* [dawnscanner](https://github.com/thesp0nge/dawnscanner) ⭐ 749 | 🐛 24 | 🌐 Ruby | 📅 2024-03-02 - A static analysis security scanner for ruby applications. It supports Sinatra, Padrino and Ruby on Rails frameworks.
* [ban-sensitive-files](https://github.com/bahmutov/ban-sensitive-files) ⭐ 69 | 🐛 16 | 🌐 JavaScript | 📅 2026-08-14 - Checks filenames to be committed against a library of filename rules to prevent storing sensitive files in Git. Checks some files for sensitive contents (for example authToken inside .npmrc file).
* [rubocop-gitlab-security](https://gitlab.com/gitlab-org/rubocop-gitlab-security) - A set of rules to extend rubocop with additional security rules.
* [Rails Application Routes Parser](https://gist.github.com/Splint3r7/198a3f8f19f20c28fff44993427012c3) - A script that print out ruby on rails application routes/URLs.

## Vulnerabilities and Security Advisories

* [ruby-advisory-db](https://github.com/rubysec/ruby-advisory-db) ⭐ 1,070 | 🐛 8 | 🌐 Ruby | 📅 2026-08-19 - Open source database of security advisories that are relevant to Ruby libraries.
* [GemScanner](https://github.com/Splint3r7/GemScanner) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2021-03-30 - GemScanner identifies depreciated versions of gems in your ruby on rails project.
* [bundler-audit](https://rubygems.org/gems/bundler-audit) - Patch-level verification for Ruby apps.

# Awesome Educational with stars

## Hacking Playground

* [RailsGoat](https://github.com/OWASP/railsgoat) ⭐ 921 | 🐛 3 | 🌐 HTML | 📅 2026-01-28 - A vulnerable version of Rails that follows the OWASP Top 10 <http://railsgoat.cktricky.com> .
* [DeleteMe](https://github.com/rietta/DeleteMe) ⭐ 3 | 🐛 0 | 🌐 Ruby | 📅 2014-12-04 - Educational insecure Rails application.

## Articles & Guides

* [Zen Rails Security Checklist](https://github.com/brunofacca/zen-rails-security-checklist#memcached-security) ⭐ 1,811 | 🐛 1 | 🌐 Ruby | 📅 2020-03-09 - A well-documented Rails security checklist.
* [Rails security checklist](https://github.com/eliotsykes/rails-security-checklist) ⭐ 1,362 | 🐛 81 | 🌐 Ruby | 📅 2022-07-17 - 🔑 Community-driven Rails Security Checklist.
* [Rails security best practices](https://github.com/ankane/secure_rails) ⭐ 1,066 | 🐛 1 | 📅 2025-07-26 - A good overview of usefull things to look out for when working with Rails.
* [Rubyfu](https://rubyfu.net/) - Offensive security book for rubyist ([Source](https://github.com/rubyfu/RubyFu) ⭐ 356 | 🐛 3 | 🌐 CSS | 📅 2023-08-07)
* [Rails Security Guides](https://guides.rubyonrails.org/security.html) - The essentials to read when dealing with Rails Applications.
* [Securing Ruby and Rails Apps](https://www.occamslabs.com/blog/securing-your-ruby-and-rails-codebase) - Applying static code analysis and dependency checking in your CI/CD pipeline.
* [OWASP Ruby on Rails Cheatsheet](https://www.owasp.org/index.php/Ruby_on_Rails_Cheatsheet) - This Cheatsheet intends to provide quick basic Ruby on Rails security tips for developers. It complements, augments or emphasizes points brought up in the rails security guide from [rails core](https://guides.rubyonrails.org/security.html).
* [Attacking Ruby on Rails Applications](http://www.phrack.org/issues/69/12.html#article) - Phrack article by [joernchen](https://twitter.com/joernchen) on finding security vulnerabilities in Rails applications.
* [Securing Rails Application from developers perspective](http://hassankhanyusufzai.com/securing-rails-application/) - A detailed blog on Ruby on Rails security from developers perspective that contains OWASP Top & other application issues with fixes /  recommendation and fix codes.
* [Ruby gem installations can expose you to lockfile injection attacks](https://snyk.io/blog/ruby-gem-installation-lockfile-injection-attacks) - security blindspots of lockfile injection in the Ruby ecosystem

## Newsletters

* [Security for Developers](https://www.getrevue.co/profile/devsecops) - Newsletter catering towards developers and covering many languages.

# Other

## Reporting Bugs

* [Ruby Bug Bounty Program](https://hackerone.com/ruby) - Found a bug in the Ruby language? Report it there.
* [Ruby Security Updates](https://www.ruby-lang.org/en/security/) - Follow the latest security announcements.

# Contributing

Found an awesome project, package, article, other type of resources related to Ruby Security? Send me a pull request!
Just follow the [guidelines](/CONTRIBUTING.md). Thank you!

***

say *hi* on [Twitter](https://twitter.com/pxlpnk)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-22._
