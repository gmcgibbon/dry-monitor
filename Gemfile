# frozen_string_literal: true

source "https://rubygems.org"

eval_gemfile "Gemfile.devtools"

gemspec

gem "dry-events", github: "dry-rb/dry-events", branch: "main"

group :test do
  gem "rack"
end

group :tools do
  gem "byebug", platform: :mri
end
