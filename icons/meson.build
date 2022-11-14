icons = [
  '16x16/apps/mati-desktop.png',
  '22x22/apps/mati-desktop.png',
  '24x24/apps/mati-desktop.png',
  '32x32/apps/mati-desktop.png',
  '48x48/apps/mati-desktop.png',
  '128x128/apps/mati-desktop.png',
  'scalable/apps/mati-desktop.svg',
  'scalable/apps/mati-desktop-symbolic.svg',
]

foreach i : icons
  dir = i.split('/')
  install_data(i,
    install_dir: join_paths('share/icons/hicolor', dir[0], dir[1]),
  )
endforeach
