project('Butler', 'cpp',version : '0.1', default_options : ['warning_level=3', 'cpp_std=c++17'])



incdir = include_directories('include')

srcs = [
  'src/main.cc',
  'src/event/aliasesevent.cc',
  'src/event/canonicalaliasevent.cc',
  'src/event/createevent.cc',
  'src/event/joinrulesevent.cc',
  'src/event/roomevent.cc',
  'src/event/powerlevelsevent.cc',
  'src/event/redactionevent.cc',

  'src/event/message/noticemessageevent.cc',
  'src/event/message/textmessageevent.cc',
  'src/event/message/videomessageevent.cc'

]

exe = executable('butler', srcs,  include_directories : incdir ,install : true)

test('basic', exe)
