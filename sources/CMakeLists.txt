cmake_minimum_required(VERSION 3.5)
project(branding-wallpapers)

set(BACKGROUNDS
	default_old.jpg
	default_dark.png
	default_light.png
	dark.png
	light.png
)

install(FILES ${BACKGROUNDS} DESTINATION /usr/share/backgrounds/liquidos)
