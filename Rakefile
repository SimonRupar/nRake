task :default => :build

task :build do
  puts "Hello from rake, soon to build your solution!"
end

#require 'rake/clean'
#
#DOT_NET_PATH = "#{ENV["SystemRoot"]}\\Microsoft.NET\\Framework\\v3.5"
#NUNIT_EXE = "../tools/Nunit/bin/nunit-console.exe"
#SOURCE_PATH = "../src"
#OUTPUT_PATH = "output"
#CONFIG = "Debug"
# 
#CLEAN.include(OUTPUT_PATH)
#
#task :default => ["clean", "build:all"]
# 
#namespace :build do
#  
#  task :all => [:compile, :test]
#      
#  desc "Build solutions using MSBuild"
#  task :compile do
#    solutions = FileList["#{SOURCE_PATH}/**/*.sln"]
#    solutions.each do |solution|
#      sh "#{DOT_NET_PATH}/msbuild.exe /p:Configuration=#{CONFIG} #{solution}"
#    end
#  end
#   
#  desc "Runs tests with NUnit"
#  task :test => [:compile] do
#    tests = FileList["#{OUTPUT_PATH}/**/*.Tests.dll"].exclude(/obj\//)
#    sh "#{NUNIT_EXE} #{tests} /nologo /xml=#{OUTPUT_PATH}/TestResults.xml"
#  end
#  
#end

