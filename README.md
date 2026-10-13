# Open5GS_N3IWF



install o openwrt no mikrotik

configure as interfaces de rede:
uci set wireless.radio0.disabled='0'
uci set wireless.radio0.country='BR'
uci set wireless.default_radio0.ssid='LAB-5G-N3IWF'
uci set wireless.default_radio0.encryption='psk2'
uci set wireless.default_radio0.key='Laboratorio5G2026!'
uci commit wireless
wifi reload
