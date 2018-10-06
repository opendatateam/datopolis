task default: [:deck]

task :deck, [:lang] do |t, args|
  require_relative 'deck'
  args.with_defaults(lang: 'en')
  Deck.build(args.lang)
end
