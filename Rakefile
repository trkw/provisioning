# encoding: utf-8

task default: 'help'

desc 'Install homebrew, python, and ansible'
task :setup do
  sh 'ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"'
  sh 'brew install python ansible'
end

desc 'Run ansible-playbook'
task 'run' do
  sh 'ansible-playbook -i hosts ./local_mac.yml -vv'
end

desc 'Only syntax check'
task 'dryrun' do
  sh 'ansible-playbook -i hosts ./local_mac.yml --syntax-check'
end

task :help do
  sh 'rake -T', verbose: false
end
