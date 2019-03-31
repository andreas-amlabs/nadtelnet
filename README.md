# nadtelnet
Home assistant media_player component nadtelnet

Use with home assistant like
media_player:
  - platform: nadtelnet
    host: nad.inet
    name: NAD Receiver
    min_volume: -60
    max_volume: -20
    sources:
      1: 'Xbox'
      2: 'TV'
      3: 'Music'


Copy the component to e.g.
/homeassistant/.homeassistant/custom_components/media_player/nadtelnet.py
