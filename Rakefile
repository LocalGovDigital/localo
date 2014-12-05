
task :default => 'build_raml'

task :build_raml do
  sh "raml2html", "#{Dir.pwd}/waste/v1/localo_waste.raml", "-o", "#{Dir.pwd}/_includes/_localo_waste.html", "-t", "#{Dir.pwd}/raml/template.handlebars", "-r", "#{Dir.pwd}/raml/resource.handlebars"
end
