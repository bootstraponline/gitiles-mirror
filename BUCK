# buck test appium

java_test(
  name = 'appium',
  srcs = glob(['src/test/java/**/*.java']),
  deps = [
    '//lib/junit:junit',
    '//lib/sauce:sauce_junit',
    '//lib/selenium:selenium-java',
  ],
  visibility = ['PUBLIC'],
)

project_config(
  src_target = ':appium',
  src_roots = [ 'src' ],
  test_target = ':appium',
)