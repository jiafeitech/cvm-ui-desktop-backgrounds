project('cvm-ui-desktop-backgrounds',
  meson_version: '>= 0.50.0'
)

prefix = get_option('prefix')

datadir = join_paths(prefix, get_option('datadir'))
backgrounddir = join_paths(datadir, 'backgrounds', 'cvm-ui-desktop')
metadatadir = join_paths(datadir, 'gnome-background-properties')

subdir('backgrounds')
