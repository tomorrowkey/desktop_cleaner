desc '#'
task 'rubocop' do
  sh('rubocop', '-l', '--except', 'Lint/RescueWithoutErrorClass', '--config', 'bitbar-plugins/.rubocop.yml')
end
