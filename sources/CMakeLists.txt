cmake_minimum_required(VERSION 3.5)
project(branding-wallpapers)

set(BACKGROUNDS
	default.jpg
)

install(FILES ${BACKGROUNDS} DESTINATION /usr/share/backgrounds/liquidos)
