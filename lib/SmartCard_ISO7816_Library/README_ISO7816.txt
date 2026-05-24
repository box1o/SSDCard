SmartCard ISO7816 KiCad Library
================================

Files:
  SmartCard_ISO7816.kicad_sym
  SmartCard_ISO7816.pretty/ISO7816_CardPads_Clean_Functional.kicad_mod
  make_smartcard_iso7816_library.py

Pin/pad mapping:
  1 = VCC
  2 = RST
  3 = CLK
  4 = AUX1
  5 = GND
  6 = VPP/NC
  7 = I/O
  8 = AUX2

KiCad import:
  1. Symbol Editor -> Manage Symbol Libraries
     Add SmartCard_ISO7816.kicad_sym.
  2. Footprint Editor -> Manage Footprint Libraries
     Add SmartCard_ISO7816.pretty.
  3. In the symbol properties, footprint should be:
     SmartCard_ISO7816:ISO7816_CardPads_Clean_Functional
