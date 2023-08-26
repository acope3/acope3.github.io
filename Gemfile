source 'https://rubygems.org'

module BundlerHack
  def __materialize__
    if name == 'grpc' || name == 'google-protobuf'
      Bundler.settings.temporary(force_ruby_platform: true) do
        super
      end
    else
      super
    end
  end
end
Bundler::LazySpecification.prepend(BundlerHack)

# jekyll
gem "jekyll", "4.2.0"

# katex
gem "execjs"

# octokit
gem 'octokit'
gem 'netrc'

# Twitter
gem 'jekyll-twitter-plugin'
