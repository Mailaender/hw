foreach(dir "Fonts" "Forts" "Graphics" "Locale" "Maps" "Music" "Sounds" "Themes" "Missions" "Names" "misc" "Scripts")
  add_subdirectory(${dir})
endforeach(dir)
