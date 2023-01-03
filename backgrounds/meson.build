dataconf = configuration_data()
dataconf.set('BACKGROUNDDIR', backgrounddir)
dataconf.set('datadir', datadir)

backgrounds = ['jia-mount.png', 'jia-mount-noon.png', 'neon.png', 'neon-dark.png']

install_data(backgrounds, install_dir: backgrounddir)

configure_file(input: 'cvm-ui-desktop.xml.in',
    output: 'cvm-ui-desktop.xml',
    configuration: dataconf,
    install: true,
    install_dir: metadatadir
  )
