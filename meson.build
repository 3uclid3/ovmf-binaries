project('ovmf')

ovmf_aa64 = meson.current_source_dir() / 'OVMF_AA64.fd'
ovmf_arm = meson.current_source_dir() / 'OVMF_ARM.fd'
ovmf_x64 = meson.current_source_dir() / 'OVMF_X64.fd'
ovmf_ia32 = meson.current_source_dir() / 'OVMF_IA32.fd'

ovmf_dep = declare_dependency()

if meson.version().version_compare('>=0.54.0')
    meson.override_dependency('ovmf', ovmf_dep)
endif
