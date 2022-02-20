project('towl-examples', 'cpp', version : '1.0.0', default_options : ['warning_level=3', 'werror=true', 'cpp_std=c++20'])

subdir('src')

towl = dependency('towl', version : ['>=1.0.1', '<1.1'])

executable('shm-window', [shm_window_files], dependencies : [towl])
