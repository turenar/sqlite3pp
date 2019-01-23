project('sqlite3pp', 'cpp', license: 'mit')

sqlite_dep = dependency('sqlite', fallback: ['sqlite', 'sqlite_dep'])

sqlite3pp_dep = declare_dependency(
	include_directories: include_directories('headeronly_src', is_system: true),
	dependencies: sqlite_dep)
