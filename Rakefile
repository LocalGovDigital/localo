
SPECIFICATIONS = [
  'addresses',
  'waste'
]


task :default => 'build_raml'

task :build_raml do
  SPECIFICATIONS.each do |comp|
    sh "raml2html", "#{Dir.pwd}/specifications/#{comp}/v1/api.raml", "-o", "#{Dir.pwd}/_includes/_#{comp}_api.html", "-t", "#{Dir.pwd}/raml/template.handlebars", "-r", "#{Dir.pwd}/raml/resource.handlebars"
  end
end
