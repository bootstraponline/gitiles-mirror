# buck test appium

java_test(
  name = 'appium',
  srcs = glob(['test/**/*.java']),
  deps = [
    '//lib/junit:junit',
    '//lib/sauce:sauce_junit',
    '//lib/selenium:selenium-java',
  ],
  visibility = ['PUBLIC'],
)

project_config(
  test_target = ':appium',
  test_roots = [ 'test' ]
)