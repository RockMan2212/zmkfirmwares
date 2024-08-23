Keyball과 Corne 두가지의 Firmware를 생성하기위한 repo
build.yaml의 설정을 바꿔서 생성 Firmaware를 선택할 수 있음

#board: [ "nice_nano_v2" ]
#shield: [ "mykeyball_left", "mykeyball_right" ]
#include:
#  - board: nice_nano_v2
#    shield: mykeyball_left
#  - board: nice_nano_v2
#    shield: mykeyball_right
#  - board: nice_nano_v2
#    shield: settings_reset
    
board: [ "nice_nano_v2" ]
shield: [ "myhand_left", "myhand_right", "myhand_dongle" ]
include:
  - board: nice_nano_v2
    shield: myhand_left
  - board: nice_nano_v2
    shield: myhand_right
  - board: nice_nano_v2
    shield: myhand_dongle
  - board: nice_nano_v2
    shield: settings_reset
