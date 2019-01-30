# Karabiner Elements Key List

Below is a list of the keys for [Karabiner Elements](https://pqrs.org/osx/karabiner/), a powerful keyboard customization utility.

I found a list of the keycodes in the comments of a github thread, so I decided to clean them up to be a little more human-readable.

Make sure to consult the [Karabiner.json Reference Manual](https://pqrs.org/osx/karabiner/json.html) for a detailed explanation of how to make your own complex modifications.

### Modifier keys

- name: caps_lock

- name: left_control

- name: left_shift

- name: left_option

- name: left_command

- name: right_control

- name: right_shift

- name: right_option

- name: right_command

- name: fn

  ### Controls and symbols

- name: return_or_enter

- name: escape

- name: delete_or_backspace

- name: delete_forward

- name: tab

- name: spacebar

- name: hyphen
  label: hyphen (-)

- name: equal_sign
  label: equal_sign (=)

- name: open_bracket
  label: open_bracket [

- name: close_bracket
  label: close_bracket ]

- name: backslash
  label: backslash (\)

- name: non_us_pound

- name: semicolon
  label: semicolon (;)

- name: quote
  label: quote (')

- name: grave_accent_and_tilde
  label: grave_accent_and_tilde ()

- name: comma
  label: comma (,)

- name: period
  label: period (.)

- name: slash
  label: slash (/)

- name: non_us_backslash

  ### Arrow keys

- name: up_arrow

- name: down_arrow

- name: left_arrow

- name: right_arrow

- name: page_up

- name: page_down

- name: home

- name: end

  ### Letter keys

- name: a

- name: b

- name: c

- name: d

- name: e

- name: f

- name: g

- name: h

- name: i

- name: j

- name: k

- name: l

- name: m

- name: n

- name: o

- name: p

- name: q

- name: r

- name: s

- name: t

- name: u

- name: v

- name: w

- name: x

- name: y

- name: z

  ### Number keys

- name: '1'

- name: '2'

- name: '3'

- name: '4'

- name: '5'

- name: '6'

- name: '7'

- name: '8'

- name: '9'

- name: '0'

  ### Function keys

- name: f1

- name: f2

- name: f3

- name: f4

- name: f5

- name: f6

- name: f7

- name: f8

- name: f9

- name: f10

- name: f11

- name: f12

- name: f13

- name: f14

- name: f15

- name: f16

- name: f17

- name: f18

- name: f19

- name: f20

- name: f21
  not_to: true

- name: f22
  not_to: true

- name: f23
  not_to: true

- name: f24
  not_to: true

  ### Media controls

- name: display_brightness_decrement
  not_from: true

- name: display_brightness_increment
  not_from: true

- name: mission_control
  not_from: true

- name: launchpad
  not_from: true

- name: dashboard
  not_from: true

- name: illumination_decrement
  not_from: true

- name: illumination_increment
  not_from: true

- name: rewind
  not_from: true

- name: play_or_pause
  not_from: true

- name: fastforward
  not_from: true

- name: mute

- name: volume_decrement

- name: volume_increment

- name: eject
  not_from: true

- name: apple_display_brightness_decrement
  not_from: true

- name: apple_display_brightness_increment
  not_from: true

- name: apple_top_case_display_brightness_decrement
  not_from: true

- name: apple_top_case_display_brightness_increment
  not_from: true

  ### Keypad keys

- name: keypad_num_lock

- name: keypad_slash

- name: keypad_asterisk

- name: keypad_hyphen

- name: keypad_plus

- name: keypad_enter

- name: keypad_1

- name: keypad_2

- name: keypad_3

- name: keypad_4

- name: keypad_5

- name: keypad_6

- name: keypad_7

- name: keypad_8

- name: keypad_9

- name: keypad_0

- name: keypad_period

- name: keypad_equal_sign

- name: keypad_comma

  ### Virtual Keys

- name: vk_none
  label: vk_none (disable this key)
  not_from: true

  ### Keys in PC keyboards

- name: print_screen

- name: scroll_lock

- name: pause

- name: insert

- name: application

- name: help

- name: power

- name: execute
  not_to: true

- name: menu
  not_to: true

- name: select
  not_to: true

- name: stop
  not_to: true

- name: again
  not_to: true

- name: undo
  not_to: true

- name: cut
  not_to: true

- name: copy
  not_to: true

- name: paste
  not_to: true

- name: find
  not_to: true

  ### International keys

- name: international1

- name: international2
  not_to: true

- name: international3

- name: international4
  not_to: true

- name: international5
  not_to: true

- name: international6
  not_to: true

- name: international7
  not_to: true

- name: international8
  not_to: true

- name: international9
  not_to: true

- name: lang1

- name: lang2

- name: lang3
  not_to: true

- name: lang4
  not_to: true

- name: lang5
  not_to: true

- name: lang6
  not_to: true

- name: lang7
  not_to: true

- name: lang8
  not_to: true

- name: lang9
  not_to: true

  ### Japanese

- name: japanese_eisuu
  label: 英数キー

- name: japanese_kana
  label: かなキー

- name: japanese_pc_nfer
  label: PCキーボードの無変換キー
  not_to: true

- name: japanese_pc_xfer
  label: PCキーボードの変換キー
  not_to: true

- name: japanese_pc_katakana
  label: PCキーボードのかなキー
  not_to: true

  ### Others

- name: keypad_equal_sign_as400
  not_to: true

- name: locking_caps_lock
  not_to: true

- name: locking_num_lock
  not_to: true

- name: locking_scroll_lock
  not_to: true

- name: alternate_erase
  not_to: true

- name: sys_req_or_attention
  not_to: true

- name: cancel
  not_to: true

- name: clear
  not_to: true

- name: prior
  not_to: true

- name: return
  label: rarely used return (HID usage 0x9e)
  not_to: true

- name: separator
  not_to: true

- name: out
  not_to: true

- name: oper
  not_to: true

- name: clear_or_again
  not_to: true

- name: cr_sel_or_props
  not_to: true

- name: ex_sel
  not_to: true

- name: left_alt
  label: left_alt (equal toleft_option)

- name: left_gui
  label: left_gui (equal toleft_command)

- name: right_alt
  label: right_alt (equal toright_option)

- name: right_gui
  label: right_gui (equal toright_command)

- name: vk_consumer_brightness_down
  label: vk_consumer_brightness_down (equal todisplay_brightness_decrement)
  not_from: true

- name: vk_consumer_brightness_up
  label: vk_consumer_brightness_up (equal todisplay_brightness_increment)
  not_from: true

- name: vk_mission_control
  label: vk_mission_control (equal tomission_control)
  not_from: true

- name: vk_launchpad
  label: vk_launchpad (equal tolaunchpad)
  not_from: true

- name: vk_dashboard
  label: vk_dashboard (equal todashboard)
  not_from: true

- name: vk_consumer_illumination_down
  label: vk_consumer_illumination_down (equal toillumination_decrement)
  not_from: true

- name: vk_consumer_illumination_up
  label: vk_consumer_illumination_up (equal toillumination_increment)
  not_from: true

- name: vk_consumer_previous
  label: vk_consumer_previous (equal torewind)
  not_from: true

- name: vk_consumer_play
  label: vk_consumer_play (equal toplay)
  not_from: true

- name: vk_consumer_next
  label: vk_consumer_next (equal tofastforward)
  not_from: true

- name: volume_down
  label: volume_down (equal tovolume_decrement)

- name: volume_up
  label: volume_up (equal tovolume_increment`)