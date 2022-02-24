## Usage

```python
    pprint_core_module_info()
"""
## Mycroft module info
     can import mycroft     : True
     mycroft module location: /home/user/ovos-core/mycroft/__init__.py

## Downstream ovos.conf overrides
Module: neon_core
     can import neon_core     : False
     neon_core module location: None
Module: hivemind
     can import hivemind     : False
     hivemind module location: None

## Downstream module overrides:
Module: neon_speech
     uses config from   : neon_core
     can import neon_speech     : False
     neon_speech module location: None
Module: neon_audio
     uses config from   : neon_core
     can import neon_audio     : False
     neon_audio module location: None
Module: neon_enclosure
     uses config from   : neon_core
     can import neon_enclosure     : False
     neon_enclosure module location: None
Module: hivemind_voice_satellite
     uses config from   : hivemind
     can import hivemind_voice_satellite     : True
     hivemind_voice_satellite module location: /home/user/HiveMind-voice-sat/hivemind_voice_satellite
"""

pprint_ovos_conf()
"""
## OVOS Configuration
 ovos.conf exists          : True
      /home/user/.config/OpenVoiceOS/ovos.conf
 xdg compliance            : True
 base xdg folder           : mycroft
 mycroft config filename   : mycroft.conf
 default mycroft.conf path :
      /home/user/ovos-core/.venv/lib/python3.9/site-packages/mycroft/configuration/mycroft.conf
"""
```