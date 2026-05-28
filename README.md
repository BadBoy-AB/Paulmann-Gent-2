<h1>Paulmann Gent 2 RGB Remote Home Assistant Blueprint</h1><p>This
    Home Assistant blueprint provides control of lights using a Paulmann Gent 2 RGB
    remote (and likely compatible Sunricher ZG2868 models) via Zigbee2MQTT. 
    This Blueprint is a Zigbee2MQTT Port of the ZHA Blueprint by IceBeach7 
    (see <a href="https://github.com/IceBeach7/HASS-Paulmann-Gent-2">ZHA Blueprint by IceBeach7</a>)</p>

<h2>Description</h2><p>This
    blueprint leverages Zigbee2MQTT to receive commands from the Paulmann Gent 2 RGB
    remote and translate them into actions to control your lights in Home Assistant.
    It aims to support most of the remote's functionalities, offering a convenient
    way to interact with your smart lighting.</p><p>The blueprint is designed primarily
    for RGB color lights but can be used with other types of lights, although some
    features may not be relevant or function as expected with non-RGB lighting.</p><p><b>Important
    Considerations:</b></p><ul>  <li><b>Zigbee2MQTT Requirement:</b> This blueprint
    requires you to be using Zigbee2MQTT to manage your Zigbee devices.</li>  <li><b>Remote
    Compatibility:</b> While designed for the Paulmann Gent 2 RGB remote (see <a href="https://en.paulmann.com/detail/d6cceca46d334842bd3bd2008204274c">Paulmann
    Gent 2 RGB Remote</a>), it is believed to also be compatible with the Sunricher
    ZG2868 (see <a href="https://www.zigbee2mqtt.io/devices/501.40.html">Zigbee2MQTT
    Device Page</a>). Ensure your remote is correctly paired with Zigbee2MQTT.</li>
    <li><b>Topic Configuration:</b> You will need to configure the correct MQTT
    topic for your remote in the blueprint inputs.</li></ul><p></p>

<h2>Installation</h2><p>
Simply click on this link:
    
[![Import Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/BadBoy-AB/Paulmann-Gent-2/main/paulmann_gent2_z2m.yaml)
