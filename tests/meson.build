catch2_dep = dependency('catch2-with-main')
test_exe = executable('tests', 'tests.cpp', dependencies: [catch2_dep, counting_dep])
test('tests', test_exe)