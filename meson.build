project('counting', 'cpp', version:'0.1' , default_options : 
[ 'cpp_std=c++20','warning_level=everything','werror=yes'])
counting_inc = include_directories('include')
subdir('src')
counting_dep = declare_dependency(include_directories: counting_inc, link_with:counting_lib)
subdir('tests')


host_machine.system()
