# Cisco 2960 XR as openflow 1.3
# tested controllers
    sudo ryu-manager ryu.app.simple_switch_13     /flowmanager/flowmanager.py  --verbose --observe-links --ofp-tcp-listen-port 6653
    see flowtables based on mac on flowmanager as mininet
