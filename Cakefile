{exec} = require "child_process"

# this 'cake' file is to compile 'coffee script' in the 'public' folder
# watches files for changes, and compiles them to a single file
task 'compile', 'compile all files in the directory', ->
  exec "coffee -c --output ./public ./hello_world/*.coffee", (error, stdout) -> # Watch for changes in the public dir
    console.log "Done."