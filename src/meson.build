project('finvizor_cpp', 'cpp', version: '1.0', default_options: ['cpp_std=c++20'])

# Include the fetchers directory
subdir('fetchers')

# Build the executable
executable('finvizor_cpp_exe', 'main.cpp', dependencies: [fetchers_dep])