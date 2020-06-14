project(
    'yaml-cpp', 'c', 'cpp', version : '0.6.3', license: 'MIT', default_options : ['cpp_std=c++11'])

cpp_args = [

]

includes = [
	'include',
]

dependencies = [

]

source = [
    'src/exceptions.cpp',
    'src/memory.cpp',
    'src/ostream_wrapper.cpp',
    'src/emitfromevents.cpp',
    'src/simplekey.cpp',
    'src/parse.cpp',
    'src/emitter.cpp',
    'src/convert.cpp',
    'src/regex_yaml.cpp',
    'src/scanscalar.cpp',
    'src/exp.cpp',
    'src/null.cpp',
    'src/node.cpp',
    'src/singledocparser.cpp',
    'src/binary.cpp',
    'src/nodeevents.cpp',
    'src/scanner.cpp',
    'src/emit.cpp',
    'src/tag.cpp',
    'src/depthguard.cpp',
    'src/emitterutils.cpp',
    'src/stream.cpp',
    'src/scantag.cpp',
    'src/scantoken.cpp',
    'src/nodebuilder.cpp',
    'src/directives.cpp',
    'src/node_data.cpp',
    'src/emitterstate.cpp',
    'src/parser.cpp',
    'src/contrib/graphbuilderadapter.cpp',
    'src/contrib/graphbuilder.cpp',
]

yamlcpp_lib = static_library(
	'yamlcpp',
	source,
	include_directories : includes,
	dependencies        : dependencies,
    cpp_args            : cpp_args,
)

yamlcpp_dep = declare_dependency(include_directories : includes, link_with: yamlcpp_lib, dependencies: dependencies)
