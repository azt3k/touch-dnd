# compile coffescript to javascript
guard :coffeescript, output: '.', input: ["."], all_on_start: true do
  watch /^.+\.coffee$/
end

# minify JS
guard 'uglify', output: '.', input: ["."], all_on_start: true do
  watch /^(touch-dnd)(?<!min)\.js$/
end
